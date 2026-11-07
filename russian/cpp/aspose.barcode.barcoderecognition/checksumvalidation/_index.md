---
title: "enum"
linktitle: "ChecksumValidation"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Как использовать enum в C++."
type: docs
weight: 3300
url: /ru/cpp/aspose.barcode.barcoderecognition/checksumvalidation/
---
## ChecksumValidation enum




```cpp
enum class ChecksumValidation
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| По умолчанию | 0 | Если контрольная сумма требуется спецификацией, она будет проверена. |
| Включено | 1 | Всегда проверять контрольную сумму, если возможно. |
| Выключено | 2 | Не проверять контрольную сумму. |

## Примечания


Включить проверку контрольной суммы при распознавании 1D и почтовых штрихкодов.

По умолчанию считается «Да» для символогий, где контрольная сумма обязательна, и «Нет», где она лишь возможна.

Контрольная сумма никогда не используется: Codabar, PatchCode, Pharmacode, DataLogic2of5

Контрольная сумма возможна: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Контрольная сумма всегда используется: остальные символогии

Этот пример показывает влияние ChecksumValidation на качество распознавания и результаты
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //контрольная сумма отключена
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    //контрольная сумма включена
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value);
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.EAN13, "1234567890128")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum disabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.Off
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.EAN13)
    'checksum enabled
    reader.BarcodeSettings.ChecksumValidation = ChecksumValidation.On
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
