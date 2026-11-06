---
title: "طريقة"
linktitle: "get_StripFNC"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. إزالة أحرف FNC1 وFNC2 وFNC3 من النص المشفر. القيمة الافتراضية هي false في C++."
type: docs
weight: 300
url: /ar/cpp/aspose.barcode.barcoderecognition/barcodesettings/get_stripfnc/
---
## BarcodeSettings::get_StripFNC method


إزالة أحرف FNC1 وFNC2 وFNC3 من نص الرمز. القيمة الافتراضية هي false.

```cpp
bool Aspose::BarCode::BarCodeRecognition::BarcodeSettings::get_StripFNC() const
```

## ملاحظات


هذا المثال يوضح كيفية إزالة أحرف FNC
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC معطل
    reader.BarcodeSettings.StripFNC = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    //StripFNC مفعّل
    reader.BarcodeSettings.StripFNC = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.GS1Code128, "(02)04006664241007(37)1(400)7019590754")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    'StripFNC disabled
    reader.BarcodeSettings.StripFNC = False
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    'StripFNC enabled
    reader.BarcodeSettings.StripFNC = True
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```


إزالة أحرف FNC1 وFNC2 وFNC3 من نص الرمز. القيمة الافتراضية هي false.
## انظر أيضًا

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
