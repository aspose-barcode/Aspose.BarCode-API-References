---
title: "Перечисление MaxiCodeMode"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Перечисление Aspose.BarCode.Generation.MaxiCodeMode. Режим кодирования для штрих‑кодов MaxiCode"
type: docs
weight: 1480
url: /ru/net/aspose.barcode.generation/maxicodemode/
---
## MaxiCodeMode enumeration

Режим кодирования для штрих‑кодов MaxiCode.

```csharp
public enum MaxiCodeMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Mode2 | `2` | Режим 2 кодирует почтовую информацию в первом сообщении и данные во втором сообщении. Содержит 9‑значный почтовый индекс (используется только в США). |
| Mode3 | `3` | Режим 3 кодирует почтовую информацию в первом сообщении и данные во втором сообщении. Содержит 6‑символьный буквенно-цифровой почтовый индекс, используемый во всем мире. |
| Mode4 | `4` | Режим 4 кодирует данные в первом и втором сообщении, с короткой коррекцией ECC. |
| Mode5 | `5` | Режим 5 кодирует данные в первом и втором сообщении, с длинной коррекцией ECC. |
| Mode6 | `6` | Режим 6 кодирует данные в первом и втором сообщении, с короткой коррекцией ECC. Используется для кодирования устройства. |

## Примеры

Этот пример показывает, как генерировать штрих‑коды MaxiCode с использованием ComplexBarcodeGenerator

```csharp
[C#]
//Режим 2 со стандартным вторым сообщением
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Режим 2 со структурированным вторым сообщением
MaxiCodeCodetextMode2 maxiCodeCodetext = new MaxiCodeCodetextMode2();
maxiCodeCodetext.PostalCode = "524032140";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Режим 3 со стандартным вторым сообщением
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStandardSecondMessage maxiCodeStandardSecondMessage = new MaxiCodeStandardSecondMessage();
maxiCodeStandardSecondMessage.Message = "Test message";
maxiCodeCodetext.SecondMessage = maxiCodeStandardSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext))
{
    complexGenerator.GenerateBarCodeImage();
}
//Режим 3 со структурированным вторым сообщением
MaxiCodeCodetextMode3 maxiCodeCodetext = new MaxiCodeCodetextMode3();
maxiCodeCodetext.PostalCode = "B1050";
maxiCodeCodetext.CountryCode = 056;
maxiCodeCodetext.ServiceCategory = 999;
MaxiCodeStructuredSecondMessage maxiCodeStructuredSecondMessage = new MaxiCodeStructuredSecondMessage();
maxiCodeStructuredSecondMessage.Add("634 ALPHA DRIVE");
maxiCodeStructuredSecondMessage.Add("PITTSBURGH");
maxiCodeStructuredSecondMessage.Add("PA");
maxiCodeStructuredSecondMessage.Year = 99;
maxiCodeCodetext.SecondMessage = maxiCodeStructuredSecondMessage;
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
//Режим 4
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode4;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
}
//Режим 5
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode5;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
} 
//Режим 6
MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
maxiCodeCodetext.Mode = MaxiCodeMode.Mode6;
maxiCodeCodetext.Message = "Test message";
using (ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.GetConstructedCodetext())
{
    complexGenerator.GenerateBarCodeImage();
} 
```

### См. также

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


