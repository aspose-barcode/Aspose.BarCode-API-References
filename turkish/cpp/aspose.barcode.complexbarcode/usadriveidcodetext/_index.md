---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext sınıfı"
linktitle: "USADriveIdCodetext"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext sınıfı. C++'da ABD Sürücü Belgesi PDF417 koduna gömülü metni kodlamak ve çözmek için sınıf."
type: docs
weight: 2900
url: /tr/cpp/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class


ABD Sürücü [License](../../aspose.barcode/license/) PDF417 koduna gömülü metni kodlamak ve çözmek için sınıf.

```cpp
class USADriveIdCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_AAMVAVersionNumber](./get_aamvaversionnumber/)() const | AAMVA Sürüm Numarası 00-99 |
| [get_IssuerIdentificationNumber](./get_issueridentificationnumber/)() const | Bu sayı, veren yargı bölgesini benzersiz bir şekilde tanımlar ve ISO Yayın Yetkilisi (AAMVA) ile iletişime geçilerek elde edilebilir. Tam 6 haneli IIN kodlanmalıdır. |
| [get_JurisdictionSpecificSubfile](./get_jurisdictionspecificsubfile/)() const | Yargı Bölgesi Özel Alanları |
| [get_JurisdictionVersionNumber](./get_jurisdictionversionnumber/)() const | Yargı Bölgesi Sürüm Numarası 00-99 |
| [get_MandatoryElements](./get_mandatoryelements/)() const | Kartın zorunlu öğeleri (alanları) |
| [get_NumberOfEntries](./get_numberofentries/)() const | Alt dosyaların 00-99 numarası |
| [get_OptionalElements](./get_optionalelements/)() const | Kartın isteğe bağlı öğeleri (alanları) |
| [get_SubfileDesignator](./get_subfiledesignator/)() const | Aşağıdaki alt dosyalar, türler, ofsetler ve uzunluklar hakkında bilgi içerir. Önemli: yalnızca tür ayarlandığında, ofset ve uzunluk otomatik olarak ayarlanacaktır. |
| [GetBarcodeType](./getbarcodetype/)() override | ABD Sürücü Belgesi (Pdf417) barkod tipini döndürür |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | ABD Sürücü Belgesi verilerinden kod metni oluştur |
| [InitFromString](./initfromstring/)(System::String) override | Kod metninden ABD Sürücü Belgesi nesnesini başlat |
| [SaveToXml](./savetoxml/)(System::SharedPtr\<System::IO::Stream\>) | XML'ye kaydeder |
| [set_AAMVAVersionNumber](./set_aamvaversionnumber/)(System::String) | AAMVA Sürüm Numarası 00-99 |
| [set_IssuerIdentificationNumber](./set_issueridentificationnumber/)(System::String) | Bu sayı, veren yargı bölgesini benzersiz bir şekilde tanımlar ve ISO Yayın Yetkilisi (AAMVA) ile iletişime geçilerek elde edilebilir. Tam 6 haneli IIN kodlanmalıdır. |
| [set_JurisdictionSpecificSubfile](./set_jurisdictionspecificsubfile/)(System::SharedPtr\<USADriveIdJurisdSubfile\>) | Yargı Bölgesi Özel Alanları |
| [set_JurisdictionVersionNumber](./set_jurisdictionversionnumber/)(System::String) | Yargı Bölgesi Sürüm Numarası 00-99 |
| [set_MandatoryElements](./set_mandatoryelements/)(System::SharedPtr\<USADriveIdCodetext::MandatoryFields\>) | Kartın zorunlu öğeleri (alanları) |
| [set_NumberOfEntries](./set_numberofentries/)(int32_t) | Alt dosyaların 00-99 numarası |
| [set_OptionalElements](./set_optionalelements/)(System::SharedPtr\<USADriveIdCodetext::OptionalFields\>) | Kartın isteğe bağlı öğeleri (alanları) |
| [set_SubfileDesignator](./set_subfiledesignator/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<USADriveIdCodetext::SubfileProperties\>>>) | Aşağıdaki alt dosyalar, türler, ofsetler ve uzunluklar hakkında bilgi içerir. Önemli: yalnızca tür ayarlandığında, ofset ve uzunluk otomatik olarak ayarlanacaktır. |
| [USADriveIdCodetext](./usadriveidcodetext/)() | Varsayılan yapıcı |
## Ayrıca Bakınız

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
