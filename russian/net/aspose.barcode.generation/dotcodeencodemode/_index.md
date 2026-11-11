---
title: "Перечисление DotCodeEncodeMode"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Перечисление Aspose.BarCode.Generation.DotCodeEncodeMode. Режим кодирования для штрихкодов DotCode"
type: docs
weight: 1240
url: /ru/net/aspose.barcode.generation/dotcodeencodemode/
---
## DotCodeEncodeMode enumeration

Режим кодирования для штрихкодов DotCode.

```csharp
public enum DotCodeEncodeMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Auto | `0` | В режиме Auto кодировка CodeText выполняется с максимальной компактностью данных. Символы Unicode перекодируются в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. |
| Binary | `3` | В режиме Binary кодировка CodeText выполняется с максимальной компактностью данных. Если найден символ Unicode, генерируется исключение. |
| ECI | `4` | В режиме ECI всё сообщение перекодируется в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. Обратите внимание, что некоторые старые сканеры (до 2006 года) могут не поддерживать этот режим. |
| Extended | `5` | Расширенный режим, поддерживающий несколько режимов ECI. |

## Примеры

```csharp
[C#]
//Автоматический режим с макросами
var codetext = ""[)>\u001E05\u001DCodetextWithMacros05\u001E\u0004"";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Save("test.bmp");
}

//Режим Auto
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Режим Bytes
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.DotCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Режим расширенного кодового текста
//создать кодовый текст
DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddFNC3SymbolSeparator();
textBuilder.AddFNC1FormatIdentifier();
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//сгенерировать кодовый текст
string codetext = textBuilder.GetExtendedCodetext();    

//сгенерировать
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, codetext))
{
    generator.Parameters.Barcode.DotCode.DotCodeEncodeMode = DotCodeEncodeMode.Extended;
	generator.Save("test.bmp");
}
```

### См. также

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


