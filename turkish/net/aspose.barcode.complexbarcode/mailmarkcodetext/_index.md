---
title: "Sınıf MailmarkCodetext"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.ComplexBarcode.MailmarkCodetext sınıfı. 4 durumlu Royal Mailmark koduna gömülü metni kodlamak ve çözmek için sınıf."
type: docs
weight: 670
url: /tr/net/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class

4 durumlu Royal Mailmark kodunda gömülü metni kodlamak ve çözmek için sınıf.

```csharp
public sealed class MailmarkCodetext : IComplexCodetext
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MailmarkCodetext](mailmarkcodetext/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Class](../../aspose.barcode.complexbarcode/mailmarkcodetext/class/) { get; set; } | "0" - Boş veya Test "1" - 1C (Perakende) "2" - 2C (Perakende) "3" - 3C (Perakende) "4" - Premium (Perakende Yayın Mail) (potansiyel gelecek kullanım için) "5" - Ertelenmiş (Perakende) "6" - Hava (Perakende) (potansiyel gelecek kullanım için) "7" - Yüzey (Perakende) (potansiyel gelecek kullanım için) "8" - Premium (Ağ Erişimi) "9" - Standart (Ağ Erişimi) |
| [DestinationPostCodePlusDPS](../../aspose.barcode.complexbarcode/mailmarkcodetext/destinationpostcodeplusdps/) { get; set; } | PC ve DP, PAF formatına uymalıdır. Uluslararası "XY11 " (5 boşluk olduğunu unutmayın) gösteren dokuz karakterlik dize veya yerel sıralama kodunu belirten bir karakter deseni. Yerel sıralama kodu, dış posta kodu, iç posta kodu ve Teslim Noktası Soneki'nden oluşur. |
| [Format](../../aspose.barcode.complexbarcode/mailmarkcodetext/format/) { get; set; } | "0" – Boş veya Test "1" – Mektup "2" – Büyük Mektup |
| [ItemID](../../aspose.barcode.complexbarcode/mailmarkcodetext/itemid/) { get; set; } | Azami değer 99999999'dur. |
| [SupplychainID](../../aspose.barcode.complexbarcode/mailmarkcodetext/supplychainid/) { get; set; } | Azami değerler Barcode C için 99 ve Barcode L için 999999'dur. |
| [VersionID](../../aspose.barcode.complexbarcode/mailmarkcodetext/versionid/) { get; set; } | Şu anda "1" – Mailmark barkodu için (0 ve 2'den 9'a ve A'dan Z'ye gelecek kullanım için ayrılmıştır) |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/mailmarkcodetext/getbarcodetype/)() | Barkod tipini alır. |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/mailmarkcodetext/getconstructedcodetext/)() | Mailmark verilerinden kod metni oluştur. |
| [InitFromString](../../aspose.barcode.complexbarcode/mailmarkcodetext/initfromstring/)(string) | Oluşturulan kod metninden Mailmark verilerini başlatır. |

### Ayrıca Bakınız

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


