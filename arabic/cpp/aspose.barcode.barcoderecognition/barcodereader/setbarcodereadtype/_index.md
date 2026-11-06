---
title: "طريقة"
linktitle: "SetBarCodeReadType"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "طريقة. يضبط مصفوفة النوع SingleDecodeType للتعرف. يجب استدعاؤها قبل طريقة ReadBarCodes() في C++."
type: docs
weight: 1600
url: /ar/cpp/aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/
---
## BarCodeReader::SetBarCodeReadType method


يضبط مصفوفة النوع [SingleDecodeType](../../singledecodetype/) للتعرف. يجب استدعاؤها قبل طريقة [ReadBarCodes()](../readbarcodes/).

```cpp
void Aspose::BarCode::BarCodeRecognition::BarCodeReader::SetBarCodeReadType(const System::ArrayPtr<System::SharedPtr<SingleDecodeType>> &barcodeTypes)
```


| معامل | نوع | الوصف |
| --- | --- | --- |
| barcodeTypes | const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\& | مصفوفة النوع [SingleDecodeType](../../singledecodetype/) للقراءة. |
## ملاحظات



يعرض هذا المثال كيفية اكتشاف باركودات Code39 و Code128.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader())
{
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128);
    reader.SetBarCodeImage(@"c:\test.png");
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader()
    reader.SetBarCodeReadType(DecodeType.Code39, DecodeType.Code128)
    reader.SetBarCodeImage("c:\test.png")
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## انظر أيضًا

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BarCodeReader](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
