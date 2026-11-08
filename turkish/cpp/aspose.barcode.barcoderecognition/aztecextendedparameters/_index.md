---
title: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters class"
linktitle: "AztecExtendedParameters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::BarCodeRecognition::AztecExtendedParameters sınıfı. C++'ta tanınan Aztec barkodunun özel verilerini depolar."
type: docs
weight: 300
url: /tr/cpp/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class


Aztec tanınan barkodun özel verilerini depolar

```cpp
class AztecExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** tüm parametrelerin yalnızca varsayılan değerleri içerip içermediğini. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Kodun, okuyucuya aşağıdaki verileri barkod okuyucusunun başlatılması veya yeniden programlanması için talimat olarak yorumlamasını söylemek için kullanılıp kullanılmadığını gösterir. Varsayılan değer false'tur. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Aztec yapılandırılmış ekleme modundaki barkodun kimliğini alır. Kimlik 1'den başlar ve barkod sayısına eşit ya da daha az olmalıdır. Varsayılan değer 0'dır. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Aztec yapılandırılmış ekleme modundaki barkod sayısını alır. Varsayılan değer 0'dır. Sayı 1 ile 26 arasında bir değer olmalıdır. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Aztec yapılandırılmış ekleme modunun dosya kimliğini alır. Varsayılan değer boş dizedir. |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [ToString](./tostring/)() const override | Bu [AztecExtendedParameters](./) öğesinin insan tarafından okunabilir bir dize temsili döndürür. |
## Açıklamalar


Bu örnek, Aztec ham değerlerini nasıl alacağınızı gösterir.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

## Ayrıca Bakınız

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
