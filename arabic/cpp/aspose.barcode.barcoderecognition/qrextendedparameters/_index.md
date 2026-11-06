---
title: "فئة Aspose::BarCode::BarCodeRecognition::QRExtendedParameters"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: "فئة Aspose::BarCode::BarCodeRecognition::QRExtendedParameters. تخزن معلومات QR Structured Append للباركود المُعترف به في C++."
type: docs
weight: 2900
url: /ar/cpp/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class


تخزن معلومات [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append للباركود المُعترف به

```cpp
class QRExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_ErrorLevel](./get_errorlevel/)() const | مستوى تصحيح الأخطاء Reed-Solomon للباركود المُعترف به. من منخفض إلى عالي: LevelL, LevelM, LevelQ, LevelH. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** ما إذا كانت جميع المعلمات تحتوي فقط على القيم الافتراضية |
| [get_MicroQRVersion](./get_microqrversion/)() const | إصدار رمز MicroQR المُعترف به. من M1 إلى M4. |
| [get_RectMicroQRVersion](./get_rectmicroqrversion/)() const | إصدار رمز RectMicroQR المُعترف به. من R7x43 إلى R17x139. |
| [get_StructuredAppendModeBarCodeIndex](./get_structuredappendmodebarcodeindex/)() const | يحصل على فهرس الباركود في وضع الإلحاق المنظم [QR](../../aspose.barcode.barcoderecognition.qr/). يبدأ الفهرس من 0. القيمة الافتراضية هي -1. |
| [get_StructuredAppendModeBarCodesQuantity](./get_structuredappendmodebarcodesquantity/)() const | يحصل على عدد الباركودات في وضع الإلحاق المنظم [QR](../../aspose.barcode.barcoderecognition.qr/). القيمة الافتراضية هي -1. |
| [get_StructuredAppendModeParityData](./get_structuredappendmodeparitydata/)() const | يحصل على بيانات التكافؤ في وضع الإلحاق المنظم [QR](../../aspose.barcode.barcoderecognition.qr/). القيمة الافتراضية هي -1. |
| [get_Version](./get_version/)() const | إصدار رمز [QR](../../aspose.barcode.barcoderecognition.qr/) المُعترف به. من Version1 إلى Version40. |
| [GetHashCode](./gethashcode/)() const override | يعيد قيمة التجزئة لهذه المثيلة. |
| [ToString](./tostring/)() const override | يعيد تمثيل نصي قابل للقراءة البشرية لهذا [QRExtendedParameters](./). |
## ملاحظات


يعرض هذا المثال كيفية الحصول على بيانات [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.QR))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex);
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.QR)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
        Console.WriteLine("QR Structured Append Index: " + result.Extended.QR.QRStructuredAppendModeBarCodeIndex)
        Console.WriteLine("QR Structured Append ParityData: " + result.Extended.QR.QRStructuredAppendModeParityData)
    Next
End Using
```

## انظر أيضًا

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
