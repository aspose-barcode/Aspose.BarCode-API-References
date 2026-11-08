---
title: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters class"
linktitle: "DotCodeExtendedParameters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::BarCodeRecognition::DotCodeExtendedParameters sınıfı. C++'da tanınan DotCode barkodunun özel verilerini depolar."
type: docs
weight: 2000
url: /tr/cpp/aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
## DotCodeExtendedParameters class


DotCode tanınan barkodun özel verilerini depolar

```cpp
class DotCodeExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** tüm parametrelerin yalnızca varsayılan değerleri içerip içermediğini. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Kodun, okuyucuya aşağıdaki verileri barkod okuyucusunun başlatılması veya yeniden programlanması için talimat olarak yorumlamasını söylemek için kullanılıp kullanılmadığını gösterir. Varsayılan değer false'tur. |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | DotCode yapılandırılmış ekleme modu barkodunun kimliğini alır. Kimlik 1'den başlar ve barkod sayısına eşit veya daha az olmalıdır. Varsayılan değer -1'dir. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | DotCode yapılandırılmış ekleme modu barkod sayısını alır. Varsayılan değer -1'dir. Sayı 1 ile 35 arasında bir değer olmalıdır. |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [ToString](./tostring/)() const override | Bu [DotCodeExtendedParameters](./) nesnesinin insan tarafından okunabilir bir dize temsili döndürür. |
## Açıklamalar


Bu örnek, DotCode ham değerlerini nasıl alacağınızı gösterir.
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DotCode, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DotCode))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DotCode barcode ID: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodeId);
        Console.WriteLine("DotCode barcodes count: " + result.Extended.DotCode.DotCodeStructuredAppendModeBarcodesCount);
    }
}
```

## Ayrıca Bakınız

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
