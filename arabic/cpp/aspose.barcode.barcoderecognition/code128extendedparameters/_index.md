---
title: "فئة Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters"
linktitle: "Code128ExtendedParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::BarCodeRecognition::Code128ExtendedParameters. تخزن بيانات خاصة لباركود Code128 المعترف به في C++."
type: docs
weight: 1300
url: /ar/cpp/aspose.barcode.barcoderecognition/code128extendedparameters/
---
## Code128ExtendedParameters class


يخزن بيانات خاصة للباركود المُعترف به من نوع Code128

```cpp
class Code128ExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_Code128DataPortions](./get_code128dataportions/)() const | يحصل على مصفوفة [Code128DataPortion](../code128dataportion/) لباركود Code128 المعترف به |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [ToString](./tostring/)() const override | يرجع تمثيلًا نصيًا مقروءًا للإنسان لهذا [Code128ExtendedParameters](./). |
## ملاحظات


يمثل منطقة الباركود المُعترف به وزاوية الباركود

يعرض هذا المثال كيفية الحصول على القيم الأولية لـ code128
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128);
    }
}
[VB.NET]
Using generator As New BarcodeGenerator(EncodeTypes.Code128, "12345")
    generator.Save("c:\test.png")
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("Code128 Data Portions: " + result.Extended.Code128)
    Next
End Using
```

## انظر أيضًا

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
