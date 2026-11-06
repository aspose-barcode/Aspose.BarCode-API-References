---
title: "طريقة"
linktitle: "set_Timeout"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يحدد مهلة عملية التعرف بالميليثانية في C++."
type: docs
weight: 400
url: /ar/cpp/aspose.barcode.barcoderecognition/barcodereader/set_timeout/
---
## BarCodeReader::set_Timeout method


يضبط مهلة عملية التعرف بالمللي ثانية.

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::set_Timeout(int32_t value)
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
