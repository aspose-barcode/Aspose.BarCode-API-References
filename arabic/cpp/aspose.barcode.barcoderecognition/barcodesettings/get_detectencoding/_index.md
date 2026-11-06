---
title: "طريقة"
linktitle: "get_DetectEncoding"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. العلامة التي تجبر المحرك على اكتشاف ترميز نص الرمز لمجموعات Unicode. القيمة الافتراضية هي true في C++."
type: docs
weight: 700
url: /ar/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_detectencoding/
---
## BarcodeSettings::get_DetectEncoding method


العلم الذي يجبر المحرك على اكتشاف ترميز نص الرمز لمجموعات Unicode. القيمة الافتراضية هي true.

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_DetectEncoding() const
```

## ملاحظات


يعرض هذا المثال كيفية اكتشاف ترميز النص أثناء التشغيل إذا كان DetectEncoding مفعلاً
```cpp
[C#]
using (MemoryStream ms = new MemoryStream())
{
    using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR))
    {
        generator.SetCodeText("Слово", Encoding.UTF8);
        generator.Save(ms, BarCodeImageFormat.Png);
    }
    //تم تمكين اكتشاف الترميز لمجموعات Unicode
    ms.Position = 0;
    using (BarCodeReader reader = new BarCodeReader(ms, DecodeType.QR))
    {
        reader.BarcodeSettings.DetectEncoding = true;
        foreach (BarCodeResult result in reader.ReadBarCodes())
            Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
    //تم تعطيل اكتشاف الترميز
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


العلامة التي تجبر المحرك على اكتشاف ترميز نص الرمز لمجموعات Unicode
## انظر أيضًا

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
