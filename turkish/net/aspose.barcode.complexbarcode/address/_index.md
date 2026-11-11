---
title: "Sınıf Address"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.ComplexBarcode.Address sınıfı. Alacaklı veya borçlunun adresi"
type: docs
weight: 480
url: /tr/net/aspose.barcode.complexbarcode/address/
---
## Address class

Alacaklı veya borçlunun adresi.

Cadde, ev numarası, posta kodu ve kasaba (yapılandırılmış adres türü) ya da adres satırı 1 ve 2 (birleştirilmiş adres öğeleri türü) ayarlayabilirsiniz. Bu alanlardan herhangi biri ayarlandığında tür otomatik olarak belirlenir. Alanlar ayarlanmadan önce adres türü belirsizdir. Her iki türden alanlar ayarlanırsa, adres türü çelişkili olur. İsim ve ülke kodu, tüm alanlar boş olmadıkça her zaman ayarlanmalıdır.

```csharp
public sealed class Address : IEquatable<Address>
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Address](address/)() | Address örneği oluşturur |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AddressLine1](../../aspose.barcode.complexbarcode/address/addressline1/) { get; set; } | Adres satırı 1'i alır veya ayarlar. |
| [AddressLine2](../../aspose.barcode.complexbarcode/address/addressline2/) { get; set; } | Adres satırı 2'yi alır veya ayarlar. |
| [CountryCode](../../aspose.barcode.complexbarcode/address/countrycode/) { get; set; } | İki harfli ISO ülke kodunu alır veya ayarlar. |
| [HouseNo](../../aspose.barcode.complexbarcode/address/houseno/) { get; set; } | Ev numarasını alır veya ayarlar. |
| [Name](../../aspose.barcode.complexbarcode/address/name/) { get; set; } | İsmi alır veya ayarlar; bu, gerçek bir kişinin ad ve soyadı ya da tüzel bir kişinin şirket adı olabilir. |
| [PostalCode](../../aspose.barcode.complexbarcode/address/postalcode/) { get; set; } | Posta kodunu alır veya ayarlar. |
| [Street](../../aspose.barcode.complexbarcode/address/street/) { get; set; } | Sokağı alır veya ayarlar. |
| [Town](../../aspose.barcode.complexbarcode/address/town/) { get; set; } | Kasaba veya şehri alır veya ayarlar. |
| [Type](../../aspose.barcode.complexbarcode/address/type/) { get; } | Adres türünü alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Clear](../../aspose.barcode.complexbarcode/address/clear/)() | Tüm alanları temizler ve türü Belirsiz olarak ayarlar. |
| [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals)(Address) | Belirtilen adresin mevcut adrese eşit olup olmadığını belirler. |
| override [Equals](../../aspose.barcode.complexbarcode/address/equals/#equals_1)(object) | Belirtilen nesnenin mevcut nesneye eşit olup olmadığını belirler. |
| override [GetHashCode](../../aspose.barcode.complexbarcode/address/gethashcode/)() | Bu örnek için karma kodunu alır. |

### Ayrıca Bakınız

* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


