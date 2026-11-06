---
title: "طريقة"
linktitle: "ReadBarCodes"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يقرأ BarCodeResults من الصورة في C++."
type: docs
weight: 1300
url: /ar/cpp/aspose.barcode.barcoderecognition/barcodereader/readbarcodes/
---
## BarCodeReader::ReadBarCodes method


يقرأ [BarCodeResult](../../barcoderesult/)s من الصورة.

```cpp
System::ArrayPtr<System::SharedPtr<BarCodeResult>> Aspose::BarCode::BarCodeRecognition::BarCodeReader::ReadBarCodes()
```


### ReturnValue

يعيد مصفوفة من [BarCodeResult](../../barcoderesult/)s المعترف بها على الصورة. إذا لم يتم التعرف على شيء، يتم إرجاع مصفوفة صفر.
## ملاحظات


يعرض هذا المثال كيفية قراءة الباركود باستخدام [BarCodeReader](../)
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    reader.ReadBarCodes();
    for(int i = 0; reader.FoundCount > i; ++i)
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes[i].CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    reader.ReadBarCodes()
    For i As Integer = 0 To reader.FoundCount - 1 Step 1
        Console.WriteLine("BarCode CodeText: " + reader.FoundBarCodes(i).CodeText)
    Next
End Using

Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```


## انظر أيضًا

* Class [BarCodeResult](../../barcoderesult/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
