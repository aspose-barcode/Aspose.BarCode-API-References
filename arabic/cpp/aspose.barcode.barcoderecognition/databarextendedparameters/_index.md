---
title: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters فئة"
linktitle: "DataBarExtendedParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters class. يخزن معلومات إضافية عن DataBar للباركود المعترف به في C++."
type: docs
weight: 1400
url: /ar/cpp/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class


يخزن معلومات إضافية من نوع DataBar للباركود المُعترف به

```cpp
class DataBarExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_Is2DCompositeComponent](./get_is2dcompositecomponent/)() const | يحصل على علامة مكوّن مركب DataBar ثنائي الأبعاد. القيمة الافتراضية هي false. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [ToString](./tostring/)() const override | يعيد تمثيل سلسلة قابل للقراءة من قبل الإنسان لهذا [DataBarExtendedParameters](./). |
## ملاحظات


يعرض هذا المثال كيفية الحصول على معلومات إضافية عن DataBar
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DatabarOmniDirectional))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.DatabarOmniDirectional)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
    Next
End Using
```

## انظر أيضًا

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
