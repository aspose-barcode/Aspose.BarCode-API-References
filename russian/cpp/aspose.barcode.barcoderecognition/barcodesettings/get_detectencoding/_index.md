---
title: "method"
linktitle: "get_DetectEncoding"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Флаг, который заставляет движок определять кодировку текста для наборов Unicode. Значение по умолчанию — true в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_detectencoding/
---
## BarcodeSettings::get_DetectEncoding method


Флаг, заставляющий движок определять кодировку текста кода для наборов Unicode. Значение по умолчанию — true.

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_DetectEncoding() const
```

## Примечания


Этот пример показывает, как обнаруживать кодировку текста на лету, если DetectEncoding включён
```cpp
[C#]
using (MemoryStream ms = new MemoryStream())
{
    using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
    {
        generator.SetCodeText("Слово", Encoding.UTF8);
        generator.Save(ms, BarCodeImageFormat.Png);
    }
    //обнаружение кодировки для наборов Unicode включено
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    //обнаружение кодировки отключено
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = false;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using ms As New MemoryStream
    Using generator As New BarcodeGenerator(EncodeTypes.QR, "Слово")
        generator.SetCodeText("Слово", System.Text.Encoding.UTF8)
        generator.Save(ms, BarCodeImageFormat.Png)
    End Using
    'detects encoding for Unicode codesets is enabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = True
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
    'detect encoding is disabled
    ms.Position = 0
    Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
        reader.BarcodeSettings.DetectEncoding = False
        For Each result As BarCodeResult In reader.ReadBarCodes()
            Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Next
    End Using
End Using
```


Флаг, который заставляет движок определять кодировку текста для наборов Unicode
## См. также

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
