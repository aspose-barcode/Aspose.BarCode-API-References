---
title: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext sınıfı"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext sınıfı. C++'ta Royal Mail 2D Mailmark koduna gömülü metni kodlamak ve çözmek için sınıf."
type: docs
weight: 1400
url: /tr/cpp/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class


Royal Mail 2D Mailmark kodunda gömülü metni kodlamak ve çözmek için sınıf.

```cpp
class Mailmark2DCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Class](./get_class/)() const | Öğenin sınıfını tanımlar. |
| [get_CustomerContent](./get_customercontent/)() const | Müşteri tarafından kullanılmak üzere isteğe bağlı alan. |
| [get_CustomerContentEncodeMode](./get_customercontentencodemode/)() const | Datamatrix barkodunun kodlama modu. Varsayılan değer: EncodeMode.C40. |
| [get_DataMatrixType](./get_datamatrixtype/)() const | 2D Mailmark Türü, Data Matrix barkodunun boyutunu tanımlar. |
| [get_DestinationPostCodeAndDPS](./get_destinationpostcodeanddps/)() const | Teslimat [Address](../address/) adresinin posta kodunu DPS ile içerir. İç bölgelerde posta kodu/DP aşağıdaki karakter sayılarına sahiptir. Bölge (1 veya 2 karakter) İlçe (1 veya 2 karakter) Sektör (1 karakter) Birim (2 karakter) DPS (2 karakter). Posta kodu ve DPS geçerli bir PAF® formatına uymalıdır. |
| [get_InformationTypeID](./get_informationtypeid/)() const | Her ürün türü için Royal Mail Mailmark barkod yükünü tanımlar. |
| [get_ItemID](./get_itemid/)() const | Tedarik Zinciri Kimliği içinde benzersiz öğeyi tanımlar. Her Mailmark barkodu, en az 90 gün boyunca benzersiz şekilde tanımlanabilmesi için bir kimlik taşımalıdır. Azami değer: 99999999. |
| [get_ReturnToSenderPostCode](./get_returntosenderpostcode/)() const | Gönderenin Geri Dönüş Posta Kodunu içerir ancak DPS yoktur. DPS'siz PC, bir PAF® formatına uymalıdır. |
| [get_RTSFlag](./get_rtsflag/)() const | İstenen geri gönderim hizmet seviyesini gösteren bayrak. |
| [get_SupplyChainID](./get_supplychainid/)() const | Posta gönderiminde yer alan benzersiz müşteri grubunu tanımlar. Azami değer: 9999999. |
| [get_UPUCountryID](./get_upucountryid/)() const | UPU Ülke Kimliğini tanımlar. Azami uzunluk: 4 karakter. |
| [get_VersionID](./get_versionid/)() const | Her Bilgi Türü Kimliği için ilgili barkod sürümünü tanımlar. |
| [GetBarcodeType](./getbarcodetype/)() override | Barkod tipini alır. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Mailmark verilerinden kod metni oluşturur. |
| [InitFromString](./initfromstring/)(System::String) override | Oluşturulan kod metninden Mailmark verilerini başlatır. |
| [Mailmark2DCodetext](./mailmark2dcodetext/)() | Yapıcı. Varsayılan bir [Mailmark2DCodetext](./) sınıf örneği oluşturur. |
| [set_Class](./set_class/)(System::String) | Öğenin sınıfını tanımlar. |
| [set_CustomerContent](./set_customercontent/)(System::String) | Müşteri tarafından kullanılmak üzere isteğe bağlı alan. |
| [set_CustomerContentEncodeMode](./set_customercontentencodemode/)(Generation::DataMatrixEncodeMode) | Datamatrix barkodunun kodlama modu. Varsayılan değer: EncodeMode.C40. |
| [set_DataMatrixType](./set_datamatrixtype/)(Mailmark2DType) | 2D Mailmark Türü, Data Matrix barkodunun boyutunu tanımlar. |
| [set_DestinationPostCodeAndDPS](./set_destinationpostcodeanddps/)(System::String) | Teslimat [Address](../address/) adresinin posta kodunu DPS ile içerir. İç bölgelerde posta kodu/DP aşağıdaki karakter sayılarına sahiptir. Bölge (1 veya 2 karakter) İlçe (1 veya 2 karakter) Sektör (1 karakter) Birim (2 karakter) DPS (2 karakter). Posta kodu ve DPS geçerli bir PAF® formatına uymalıdır. |
| [set_InformationTypeID](./set_informationtypeid/)(System::String) | Her ürün türü için Royal Mail Mailmark barkod yükünü tanımlar. |
| [set_ItemID](./set_itemid/)(int32_t) | Tedarik Zinciri Kimliği içinde benzersiz öğeyi tanımlar. Her Mailmark barkodu, en az 90 gün boyunca benzersiz şekilde tanımlanabilmesi için bir kimlik taşımalıdır. Azami değer: 99999999. |
| [set_ReturnToSenderPostCode](./set_returntosenderpostcode/)(System::String) | Gönderenin Geri Dönüş Posta Kodunu içerir ancak DPS yoktur. DPS'siz PC, bir PAF® formatına uymalıdır. |
| [set_RTSFlag](./set_rtsflag/)(System::String) | İstenen geri gönderim hizmet seviyesini gösteren bayrak. |
| [set_SupplyChainID](./set_supplychainid/)(int32_t) | Posta gönderiminde yer alan benzersiz müşteri grubunu tanımlar. Azami değer: 9999999. |
| [set_UPUCountryID](./set_upucountryid/)(System::String) | UPU Ülke Kimliğini tanımlar. Azami uzunluk: 4 karakter. |
| [set_VersionID](./set_versionid/)(System::String) | Her Bilgi Türü Kimliği için ilgili barkod sürümünü tanımlar. |
## Ayrıca Bakınız

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
