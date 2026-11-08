---
title: "Aspose::BarCode::Generation::AztecParameters sınıfı"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Generation::AztecParameters sınıfı. C++'da Aztec parametreleri."
type: docs
weight: 300
url: /tr/cpp/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class


Aztec parametreleri.

```cpp
class AztecParameters : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) modülünün Yükseklik/Genişlik oranı. |
| [get_ECIEncoding](./get_eciencoding/)() const | ECI kodlamasını alır. AztecEncodeMode Auto olduğunda kullanılır. Varsayılan değer: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Aztec kodlama modunu alır. Varsayılan değer: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Aztec barkod tiplerinin hata düzeltme seviyesi. Değer 5 ile 95 arasında olmalıdır. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Sembolde bulunan verileri okuyucu başlatma programlaması olarak yorumlaması için okuyucuya talimat vermek amacıyla kullanılır. |
| [get_LayersCount](./get_layerscount/)() const | Aztec sembolünün katman sayısını alır. Katman sayısı Kompakt mod için 1 ile 3 arasında, Tam Aralık mod için 1 ile 32 arasında olmalıdır. Varsayılan değer: 0 (otomatik). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Aztec barkodunun Structured Append modunda Barkod Kimliği. Barkod Kimliği 1 ile barkod sayısı arasında olmalıdır. Varsayılan değer: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Aztec barkodunun Structured Append modunda Barkod sayısı. Barkod sayısı 1 ile 26 arasında olmalıdır. Varsayılan değer: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Aztec barkodunun Structured Append modunda Dosya Kimliği (isteğe bağlı alan). Dosya Kimliği boşluk içermemelidir. Varsayılan değer: boş dize |
| [get_SymbolMode](./get_symbolmode/)() const | Aztec Sembol modunu alır. Varsayılan değer: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) modülünün Yükseklik/Genişlik oranı. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | ECI kodlamasını ayarlar. AztecEncodeMode Auto olduğunda kullanılır. Varsayılan değer: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(AztecEncodeMode) | Aztec kodlama modunu ayarlar. Varsayılan değer: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(int32_t) | Aztec barkod tiplerinin hata düzeltme seviyesi. Değer 5 ile 95 arasında olmalıdır. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Sembolde bulunan verileri okuyucu başlatma programlaması olarak yorumlaması için okuyucuya talimat vermek amacıyla kullanılır. |
| [set_LayersCount](./set_layerscount/)(int32_t) | Aztec sembolünün katman sayısını ayarlar. Katman sayısı Kompakt mod için 1 ile 3 arasında, Tam Aralık mod için 1 ile 32 arasında olmalıdır. Varsayılan değer: 0 (otomatik). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Aztec barkodunun Structured Append modunda Barkod Kimliği. Barkod Kimliği 1 ile barkod sayısı arasında olmalıdır. Varsayılan değer: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Aztec barkodunun Structured Append modunda Barkod sayısı. Barkod sayısı 1 ile 26 arasında olmalıdır. Varsayılan değer: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(System::String) | Aztec barkodunun Structured Append modunda Dosya Kimliği (isteğe bağlı alan). Dosya Kimliği boşluk içermemelidir. Varsayılan değer: boş dize |
| [set_SymbolMode](./set_symbolmode/)(AztecSymbolMode) | Aztec Sembol modunu ayarlar. Varsayılan değer: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Bu [AztecParameters](./) nesnesinin insan tarafından okunabilir dize temsili döndürür. |
## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
