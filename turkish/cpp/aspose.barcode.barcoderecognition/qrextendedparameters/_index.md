---
title: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters sınıfı"
linktitle: "QRExtendedParameters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::BarCodeRecognition::QRExtendedParameters sınıfı. Tanımlanan barkodun C++'ta QR Structured Append bilgisini depolar."
type: docs
weight: 2900
url: /tr/cpp/aspose.barcode.barcoderecognition/qrextendedparameters/
---
## QRExtendedParameters class


Tanımlanan barkodun [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append bilgisini depolar

```cpp
class QRExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_ErrorLevel](./get_errorlevel/)() const | Tanımlanan barkodun Reed-Solomon hata düzeltme seviyesi. Düşükten yükseğe: LevelL, LevelM, LevelQ, LevelH. |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** tüm parametrelerin yalnızca varsayılan değerleri içerip içermediğini. |
| [get_MicroQRVersion](./get_microqrversion/)() const | Tanımlanan MicroQR Kodunun sürümü. M1'den M4'e. |
| [get_RectMicroQRVersion](./get_rectmicroqrversion/)() const | Tanımlanan RectMicroQR Kodunun sürümü. R7x43'ten R17x139'a. |
| [get_StructuredAppendModeBarCodeIndex](./get_structuredappendmodebarcodeindex/)() const | [QR](../../aspose.barcode.barcoderecognition.qr/) yapılandırılmış ekleme modlu barkodun indeksini alır. İndeks 0'dan başlar. Varsayılan değer -1'dir. |
| [get_StructuredAppendModeBarCodesQuantity](./get_structuredappendmodebarcodesquantity/)() const | [QR](../../aspose.barcode.barcoderecognition.qr/) yapılandırılmış ekleme modlu barkodların miktarını alır. Varsayılan değer -1'dir. |
| [get_StructuredAppendModeParityData](./get_structuredappendmodeparitydata/)() const | [QR](../../aspose.barcode.barcoderecognition.qr/) yapılandırılmış ekleme modlu parite verisini alır. Varsayılan değer -1'dir. |
| [get_Version](./get_version/)() const | Tanımlanan [QR](../../aspose.barcode.barcoderecognition.qr/) Kodunun sürümü. Version1'den Version40'a. |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [ToString](./tostring/)() const override | Bu [QRExtendedParameters](./) öğesinin insan tarafından okunabilir dize temsilini döndürür. |
## Açıklamalar


Bu örnek, [QR](../../aspose.barcode.barcoderecognition.qr/) Structured Append verisini nasıl alacağınızı gösterir
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

## Ayrıca Bakınız

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
