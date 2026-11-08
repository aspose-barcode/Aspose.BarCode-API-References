---
title: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters sınıfı"
linktitle: "DataBarExtendedParameters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::BarCodeRecognition::DataBarExtendedParameters sınıfı. Tanınan barkodun DataBar ek bilgilerini C++'da depolar."
type: docs
weight: 1400
url: /tr/cpp/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class


Tanınan barkodun DataBar ek bilgilerini depolar

```cpp
class DataBarExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Is2DCompositeComponent](./get_is2dcompositecomponent/)() const | DataBar 2D birleşik bileşen bayrağını alır. Varsayılan değer false'tur. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** tüm parametrelerin yalnızca varsayılan değerleri içerip içermediğini. |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [ToString](./tostring/)() const override | Bu [DataBarExtendedParameters](./) öğesinin insan tarafından okunabilir dize temsilini döndürür. |
## Açıklamalar


Bu örnek, DataBar ek bilgisinin nasıl alınacağını gösterir.
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

## Ayrıca Bakınız

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
