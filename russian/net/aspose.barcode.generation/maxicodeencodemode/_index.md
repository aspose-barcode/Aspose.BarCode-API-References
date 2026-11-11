---
title: "Перечисление MaxiCodeEncodeMode"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Перечисление Aspose.BarCode.Generation.MaxiCodeEncodeMode. Режим кодирования для штрих‑кодов MaxiCode"
type: docs
weight: 1460
url: /ru/net/aspose.barcode.generation/maxicodeencodemode/
---
## MaxiCodeEncodeMode enumeration

Режим кодирования для штрих‑кодов MaxiCode.

```csharp
public enum MaxiCodeEncodeMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Auto | `0` | В режиме Auto кодировка CodeText выполняется с максимальной компактностью данных. Символы Unicode перекодируются в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. |
| Extended | `3` | Расширенный режим, поддерживающий несколько режимов ECI. |
| Binary | `4` | В режиме Binary кодировка CodeText выполняется с максимальной компактностью данных. Если найден символ Unicode, генерируется исключение. |
| ECI | `5` | В режиме ECI всё сообщение перекодируется в указанную кодировку ECIEncoding с вставкой идентификатора ECI. Если найден символ, не поддерживаемый выбранной кодировкой ECI, генерируется исключение. Обратите внимание, что некоторые старые сканеры (до 2006 года) могут не поддерживать этот режим. |

## Примеры

```csharp
[C#]
//Режим Auto
var codetext = "犬Right狗";
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

//Режим Bytes
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.MaxiCode))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Режим расширенного кодового текста
//создать кодовый текст
MaxiCodeExtCodetextBuilder textBuilder = new MaxiCodeExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//сгенерировать кодовый текст
string codetext = textBuilder.GetExtendedCodetext();    

//сгенерировать
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.MaxiCode, codetext))
{
    generator.Parameters.Barcode.MaxiCode.MaxiCodeEncodeMode = MaxiCodeEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### См. также

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


