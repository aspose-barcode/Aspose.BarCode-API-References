---
title: "Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters sınıfı"
linktitle: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::BarCodeRecognition::DataMatrixExtendedParameters sınıfı. C++'ta DataMatrix tanınan barkodun özel verilerini depolar."
type: docs
weight: 1500
url: /tr/cpp/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class


[DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) tanınan barkodun özel verilerini depolar

```cpp
class DataMatrixExtendedParameters : public Aspose::BarCode::BarCodeRecognition::BaseExtendedParameters
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_IsEmpty](../baseextendedparameters/get_isempty/)() const | **Tests** tüm parametrelerin yalnızca varsayılan değerleri içerip içermediğini. |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Kodun, okuyucuya aşağıdaki verileri barkod okuyucusunun başlatılması veya yeniden programlanması için talimat olarak yorumlamasını söylemek için kullanılıp kullanılmadığını gösterir. Varsayılan değer false'tur. |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) yapılandırılmış ekleme modundaki barkodun kimliğini alır. Kimlik 1'den başlar ve barkod sayısına eşit veya daha az olmalıdır. Varsayılan değer -1'dir. |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) yapılandırılmış ekleme modundaki barkod sayısını alır. Varsayılan değer -1'dir. Sayı 1 ile 35 arasında olmalıdır. |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) yapılandırılmış ekleme modundaki barkodun kimliğini alır. Kimlik 1'den başlar ve barkod sayısına eşit veya daha az olmalıdır. Varsayılan değer -1'dir. |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için hash kodunu döndürür. |
| [ToString](./tostring/)() const override | Bu [DataMatrixExtendedParameters](./) nesnesinin insan tarafından okunabilir dize temsilini döndürür. |
## Açıklamalar


Bu örnek, [DataMatrix](../../aspose.barcode.barcoderecognition.datamatrix/) ham değerlerini nasıl alacağınızı gösterir
```cpp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

## Ayrıca Bakınız

* Class [BaseExtendedParameters](../baseextendedparameters/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
