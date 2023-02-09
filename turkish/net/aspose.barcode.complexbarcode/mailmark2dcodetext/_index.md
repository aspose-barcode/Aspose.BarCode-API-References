---
title: Mailmark2DCodetext
second_title: Aspose.BarCode for .NET API Referansı
description: Royal Mail 2D Posta İşareti koduna gömülü metnin kodlanması ve kodunun çözülmesi için sınıf.
type: docs
weight: 360
url: /tr/net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class

Royal Mail 2D Posta İşareti koduna gömülü metnin kodlanması ve kodunun çözülmesi için sınıf.

```csharp
public sealed class Mailmark2DCodetext : IComplexCodetext
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Mailmark2DCodetext](mailmark2dcodetext)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmark2dcodetext/class) { get; set; } | Öğenin sınıfını tanımlar. |
| [CustomerContent](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontent) { get; set; } | Müşteri tarafından kullanılmak üzere isteğe bağlı alan. |
| [CustomerContentEncodeMode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontentencodemode) { get; set; } | Datamatrix barkodunun kodlama modu. Varsayılan değer: DataMatrixEncodeMode.C40. |
| [DataMatrixType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/datamatrixtype) { get; set; } | 2D Posta İşareti Türü, Veri Matrisi barkodunun boyutunu tanımlar. |
| [DestinationPostCodeAndDPS](../../aspose.barcode.complexbarcode/mailmark2dcodetext/destinationpostcodeanddps) { get; set; } | DPS ile Teslimat Adresinin Posta Kodunu içerir Yurt içinde ise Posta Kodu/DP aşağıdaki karakter sayısını içerir. Alan (1 veya 2 karakter) Bölge(1 veya 2 karakter) Sektör(1 karakter) Birim(2 karakter) DPS (2 karakter). Posta Kodu ve DPS, geçerli bir PAF® formatına uygun olmalıdır. |
| [InformationTypeID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/informationtypeid) { get; set; } | Her ürün türü için Royal Mail Posta İşareti barkod yükünü tanımlar. |
| [ItemID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/itemid) { get; set; } | Tedarik Zinciri Kimliği içindeki benzersiz öğeyi tanımlar. En az 90 gün boyunca benzersiz bir şekilde tanımlanabilmesi için her Posta İşareti barkodunun bir ID taşıması gerekir. Maksimum değer: 99999999. |
| [ReturnToSenderPostCode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/returntosenderpostcode) { get; set; } | Gönderene İade Posta Kodunu içerir, ancak DPS içermez. Bilgisayar (DPS'siz) bir PAF® formatına uygun olmalıdır. |
| [RTSFlag](../../aspose.barcode.complexbarcode/mailmark2dcodetext/rtsflag) { get; set; } | Gönderene İade hizmetinin hangi düzeyde talep edildiğini gösteren işaret. |
| [SupplyChainID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/supplychainid) { get; set; } | Postalamaya dahil olan benzersiz müşteri grubunu tanımlar. Maksimum değer: 9999999. |
| [UPUCountryID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/upucountryid) { get; set; } | UPU Ülke Kimliğini tanımlar. Maksimum uzunluk: 4 karakter. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/versionid) { get; set; } | Her Bilgi Türü Kimliği ile ilgili olarak barkod sürümünü tanımlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getbarcodetype)() | Barkod türünü alır. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getconstructedcodetext)() | Posta İşareti verilerinden kod metni oluşturun. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmark2dcodetext/initfromstring)(string) | Oluşturulan kod metninden Posta İşareti verilerini başlatır. |

### Ayrıca bakınız

* interface [IComplexCodetext](../icomplexcodetext)
* ad alanı [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode)
* toplantı [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->