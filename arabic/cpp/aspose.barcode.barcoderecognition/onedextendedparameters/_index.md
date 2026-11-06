---
title: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters فئة"
linktitle: "OneDExtendedParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "Aspose::BarCode::BarCodeRecognition::OneDExtendedParameters فئة. يخزن بيانات خاصة لباركود 1D تم التعرف عليه مثل نص الرمز المنفصل ومجموع التحقق في C++."
type: docs
weight: 2700
url: /ar/cpp/aspose.barcode.barcoderecognition/onedextendedparameters/
---
## OneDExtendedParameters class


يخزن بيانات خاصة للباركود أحادي الأبعاد المُعترف به مثل نص الشيفرة المنفصل ومجموع التحقق

```cpp
class OneDExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_CheckSum](./get_checksum/)() const | يحصل على مجموع التحقق لباركودات 1D. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية |
| [get_Value](./get_value/)() const | يحصل على نص الرمز لباركودات 1D بدون مجموع التحقق. |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [ToString](./tostring/)() const override | يرجع تمثيل سلسلة مقروءة للإنسان لهذا [OneDExtendedParameters](./). |
## ملاحظات


هذا المثال يوضح كيفية الحصول على قيمة باركود 1D ومجموع التحقق
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "1234567890128"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.EAN13))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
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
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("BarCode Value: " + result.Extended.OneD.Value)
        Console.WriteLine("BarCode Checksum: " + result.Extended.OneD.CheckSum)
    Next
End Using
```

## انظر أيضًا

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
