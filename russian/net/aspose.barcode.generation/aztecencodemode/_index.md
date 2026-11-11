---
title: "Enum AztecEncodeMode"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Перечисление Aspose.BarCode.Generation.AztecEncodeMode. Режим кодирования для штрих‑кодов Aztec"
type: docs
weight: 940
url: /ru/net/aspose.barcode.generation/aztecencodemode/
---
## AztecEncodeMode enumeration

Режим кодирования для штрих‑кодов Aztec.

```csharp
public enum AztecEncodeMode
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
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.bmp");
}

byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.Aztec))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Binary;
    generator.Save("test.bmp");
}

//Режим Extended
//создать кодовый текст
AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
textBuilder.AddECICodetext(ECIEncodings.Win1251, "Will");
textBuilder.AddECICodetext(ECIEncodings.UTF8, "犬Right狗");
textBuilder.AddECICodetext(ECIEncodings.UTF16BE, "犬Power狗");
textBuilder.AddPlainCodetext("Plain text");

//сгенерировать кодовый текст
string codetext = textBuilder.GetExtendedCodetext();    

//сгенерировать
using(BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, codetext))
{
    generator.Parameters.Barcode.Aztec.AztecEncodeMode = AztecEncodeMode.Extended;
    generator.Parameters.Barcode.CodeTextParameters.TwoDDisplayText = "My Text";
	generator.Save("test.bmp");
}
```

### См. также

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


