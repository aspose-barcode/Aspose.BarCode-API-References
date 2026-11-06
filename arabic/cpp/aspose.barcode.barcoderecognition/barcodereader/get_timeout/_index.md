---
title: "طريقة"
linktitle: "get_Timeout"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يحصل على مهلة عملية التعرف بالمللي ثانية في C++."
type: docs
weight: 300
url: /ar/cpp/aspose.barcode.barcoderecognition/barcodereader/get_timeout/
---
## BarCodeReader::get_Timeout method


يحصل على مهلة عملية التعرف بالمللي ثانية.

```cpp
int32_t Aspose::BarCode::BarCodeRecognition::BarCodeReader::get_Timeout()
```

## ملاحظات


المهلة.

يعرض هذا المثال كيفية تجنب تعطل عملية التعرف بسبب المهلة على الصور الكبيرة.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png"))
{
    reader.Timeout = 5000;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png")
    reader.Timeout = 5000
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## انظر أيضًا

* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
