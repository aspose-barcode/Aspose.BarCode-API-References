---
title: "Aspose::BarCode::Generation::DataMatrixParameters sınıfı"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Generation::DataMatrixParameters sınıfı. C++'da DataMatrix parametreleri."
type: docs
weight: 2000
url: /tr/cpp/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class


DataMatrix parametreleri.

```cpp
class DataMatrixParameters : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | 2D [BarCode](../../aspose.barcode/) modülünün Yükseklik/Genişlik oranı. |
| [get_EccType](./get_ecctype/)() const | Bir DataMatrix ECC türü alır. Varsayılan değer: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [get_ECIEncoding](./get_eciencoding/)() const | ECI kodlamasını alır. EncodeMode Auto olduğunda kullanılır. Varsayılan değer: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | DataMatrix barkodunun kodlama modu. Varsayılan değer: [EncodeMode.Auto](../aztecencodemode/). |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Okuyucuya sembol içinde bulunan veriyi okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır. Varsayılan değer: false |
| [get_MacroCharacters](./get_macrocharacters/)() const | Macro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. Yalnızca [DataMatrixEccType.Ecc200](../datamatrixecctype/) veya [DataMatrixEccType.EccAuto](../datamatrixecctype/) ile kullanılabilir. [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) ile kullanılamaz. Varsayılan değer: [MacroCharacters.None](../barcodeclassifications/). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | DataMatrix barkodunun Yapılandırılmış Ek modu için Barkod Kimliği. Varsayılan değer: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | DataMatrix barkodunun Yapılandırılmış Ek modu için barkod sayısı. Varsayılan değer: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Datamatrix barkodunun Structured Append modu için Dosya Kimliği. Varsayılan değer: 0 |
| [get_Version](./get_version/)() const | Bir Datamatrix sembol boyutunu alır. Varsayılan değer: [Version.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | 2D [BarCode](../../aspose.barcode/) modülünün Yükseklik/Genişlik oranı. |
| [set_EccType](./set_ecctype/)(DataMatrixEccType) | Bir Datamatrix ECC tipini ayarlar. Varsayılan değer: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | ECI kodlamasını ayarlar. EncodeMode Auto olduğunda kullanılır. Varsayılan değer: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DataMatrixEncodeMode) | DataMatrix barkodunun kodlama modu. Varsayılan değer: [EncodeMode.Auto](../aztecencodemode/). |
| [set_IsReaderProgramming](./set_isreaderprogramming/)(bool) | Okuyucuya sembol içinde bulunan veriyi okuyucu başlatması için programlama olarak yorumlamasını söylemek için kullanılır. Varsayılan değer: false |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Macro Karakter 05 ve 06 değerleri, özel modlarda daha kompakt kodlama elde etmek için kullanılır. Yalnızca [DataMatrixEccType.Ecc200](../datamatrixecctype/) veya [DataMatrixEccType.EccAuto](../datamatrixecctype/) ile kullanılabilir. [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) ile kullanılamaz. Varsayılan değer: [MacroCharacters.None](../barcodeclassifications/). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | DataMatrix barkodunun Yapılandırılmış Ek modu için Barkod Kimliği. Varsayılan değer: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | DataMatrix barkodunun Yapılandırılmış Ek modu için barkod sayısı. Varsayılan değer: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(int32_t) | Datamatrix barkodunun Structured Append modu için Dosya Kimliği. Varsayılan değer: 0 |
| [set_Version](./set_version/)(DataMatrixVersion) | Bir Datamatrix sembol boyutunu ayarlar. Varsayılan değer: [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Bu [DataMatrixParameters](./) nesnesinin insan tarafından okunabilir dize temsili döndürür. |
## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
