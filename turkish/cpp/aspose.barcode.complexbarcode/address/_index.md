---
title: "Aspose::BarCode::ComplexBarcode::Address sınıfı"
linktitle: "Adres"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::Address sınıfı. C++'da alacaklı veya borçlunun adresi."
type: docs
weight: 100
url: /tr/cpp/aspose.barcode.complexbarcode/address/
---
## Address class


[Address](./) of creditor or debtor.

```cpp
class Address : public System::IEquatable<System::SharedPtr<Address>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [Address](./address/)() | [Address](./) örneği oluşturur |
| [Clear](./clear/)() | Tüm alanları temizler ve türü [AddressType::Undetermined](../addresstype/) olarak ayarlar. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Belirtilen nesnenin mevcut nesneye eşit olup olmadığını belirler. |
| [Equals](./equals/)(System::SharedPtr\<Address\>) override | Belirtilen adresin mevcut adrese eşit olup olmadığını belirler. |
| [get_AddressLine1](./get_addressline1/)() const | Adres satırı 1'i alır. |
| [get_AddressLine2](./get_addressline2/)() const | Adres satırı 2'yi alır. |
| [get_CountryCode](./get_countrycode/)() const | İki harfli ISO ülke kodunu alır. |
| [get_HouseNo](./get_houseno/)() const | Ev numarasını alır. |
| [get_Name](./get_name/)() const | İsmi alır; gerçek kişinin ad ve soyadı ya da tüzel kişinin şirket adı. |
| [get_PostalCode](./get_postalcode/)() const | Posta kodunu alır. |
| [get_Street](./get_street/)() const | Sokağı alır. |
| [get_Town](./get_town/)() const | Kasaba veya şehri alır. |
| [get_Type](./get_type/)() const | Adres tipini alır. |
| [GetHashCode](./gethashcode/)() const override | Bu örnek için karma kodunu alır. |
| [set_AddressLine1](./set_addressline1/)(System::String) | Adres satırı 1'i ayarlar. |
| [set_AddressLine2](./set_addressline2/)(System::String) | Adres satırı 2'yi ayarlar. |
| [set_CountryCode](./set_countrycode/)(System::String) | İki harfli ISO ülke kodunu ayarlar. |
| [set_HouseNo](./set_houseno/)(System::String) | Ev numarasını ayarlar. |
| [set_Name](./set_name/)(System::String) | İsmi ayarlar; gerçek kişinin ad ve soyadı ya da tüzel kişinin şirket adı. |
| [set_PostalCode](./set_postalcode/)(System::String) | Posta kodunu ayarlar. |
| [set_Street](./set_street/)(System::String) | Sokak ayarlanır. |
| [set_Town](./set_town/)(System::String) | Kasaba veya şehir ayarlanır. |
## Açıklamalar


İsterseniz sokak, ev numarası, posta kodu ve kasaba (tür *structured address*) ya da adres satırı 1 ve 2 (tür *combined address elements*) ayarlayabilirsiniz. Bu alanlardan herhangi biri ayarlandığında tür otomatik olarak belirlenir. Alanlar ayarlanmadan önce adres türü *undetermined*'dır. Her iki türden alanlar ayarlanırsa, adres türü *conflicting* olur. Tüm alanlar boş olmadıkça isim ve ülke kodu her zaman ayarlanmalıdır.
## Ayrıca Bakınız

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
