---
title: "Sınıf Mailmark2DCodetext"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.ComplexBarcode.Mailmark2DCodetext sınıfı. Royal Mail 2D Mailmark koduna gömülü metni kodlamak ve çözmek için sınıf."
type: docs
weight: 650
url: /tr/net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class

Royal Mail 2D Mailmark kodunda gömülü metni kodlamak ve çözmek için sınıf.

```csharp
public sealed class Mailmark2DCodetext : IComplexCodetext
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Mailmark2DCodetext](mailmark2dcodetext/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmark2dcodetext/class/) { get; set; } | Öğenin sınıfını tanımlar. |
| [CustomerContent](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontent/) { get; set; } | Müşteri tarafından kullanılmak üzere isteğe bağlı alan. |
| [CustomerContentEncodeMode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/customercontentencodemode/) { get; set; } | Datamatrix barkodunun kodlama modu. Varsayılan değer: EncodeMode.C40. |
| [DataMatrixType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/datamatrixtype/) { get; set; } | 2D Mailmark Türü, Data Matrix barkodunun boyutunu tanımlar. |
| [DestinationPostCodeAndDPS](../../aspose.barcode.complexbarcode/mailmark2dcodetext/destinationpostcodeanddps/) { get; set; } | Teslimat Adresinin Posta Kodu ve DPS'yi içerir. İç bölgelerde Posta Kodu/DP aşağıdaki karakter sayılarını içerir. Bölge (1 veya 2 karakter) İlçe (1 veya 2 karakter) Sektör (1 karakter) Birim (2 karakter) DPS (2 karakter). Posta Kodu ve DPS geçerli bir PAF® formatına uymalıdır. |
| [InformationTypeID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/informationtypeid/) { get; set; } | Her ürün türü için Royal Mail Mailmark barkod yükünü tanımlar. |
| [ItemID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/itemid/) { get; set; } | Tedarik Zinciri Kimliği içinde benzersiz öğeyi tanımlar. Her Mailmark barkodu, en az 90 gün boyunca benzersiz olarak tanımlanabilmesi için bir kimlik taşımalıdır. Azami değer: 99999999. |
| [ReturnToSenderPostCode](../../aspose.barcode.complexbarcode/mailmark2dcodetext/returntosenderpostcode/) { get; set; } | Gönderenin Geri Dönüş Posta Kodunu içerir ancak DPS yoktur. PC (DPS olmadan) geçerli bir PAF® formatına uymalıdır. |
| [RTSFlag](../../aspose.barcode.complexbarcode/mailmark2dcodetext/rtsflag/) { get; set; } | İstenen Gönderenin Geri Dönüş hizmet seviyesini gösteren bayrak. |
| [SupplyChainID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/supplychainid/) { get; set; } | Posta işlemine dahil olan benzersiz müşteri grubunu tanımlar. Azami değer: 9999999. |
| [UPUCountryID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/upucountryid/) { get; set; } | UPU Ülke Kimliğini tanımlar. Azami uzunluk: 4 karakter. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmark2dcodetext/versionid/) { get; set; } | Her Bilgi Türü Kimliği için ilgili barkod sürümünü tanımlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getbarcodetype/)() | Barkod tipini alır. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmark2dcodetext/getconstructedcodetext/)() | Mailmark verilerinden kod metni oluştur. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmark2dcodetext/initfromstring/)(string) | Oluşturulan kod metninden Mailmark verilerini başlatır. |

### Ayrıca Bakınız

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


