---
title: "Sınıf CodetextParameters"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.CodetextParameters sınıfı. Kod metni parametreleri"
type: docs
weight: 1160
url: /tr/net/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class

Kod metni parametreleri.

```csharp
public class CodetextParameters
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Alignment](../../aspose.barcode.generation/codetextparameters/alignment/) { get; set; } | Kod metninin hizalamasını alır veya ayarlar. Varsayılan değer: StringAlignment.Center. |
| [Color](../../aspose.barcode.generation/codetextparameters/color/) { get; set; } | Görüntülenen CodeText'in Rengini belirtin. Varsayılan değer: Color.Black. |
| [Font](../../aspose.barcode.generation/codetextparameters/font/) { get; } | Görüntülenen CodeText'in yazı tipini belirtin. Varsayılan değer: Arial 5pt regular. FontMode FontMode.Auto olarak ayarlandığında yok sayılır. |
| [FontMode](../../aspose.barcode.generation/codetextparameters/fontmode/) { get; set; } | FontMode'u belirtin. FontMode Auto olarak ayarlanırsa, yazı tipi boyutu xDimension değerine göre otomatik olarak hesaplanır. FontMode.Auto'yu özellikle AutoSizeMode.Nearest veya AutoSizeMode.Interpolation içinde kullanmanız önerilir. Varsayılan değer: FontMode.Auto. |
| [Location](../../aspose.barcode.generation/codetextparameters/location/) { get; set; } | Görüntülenen CodeText konumunu belirtin, CodeText'i gizlemek için CodeLocation.None olarak ayarlayın. Varsayılan değer: 1D barkodlar için CodeLocation.Below ve 2D barkodlar için CodeLocation.None. |
| [NoWrap](../../aspose.barcode.generation/codetextparameters/nowrap/) { get; set; } | Metin içinde kelime kaydırmalarını (satır sonlarını) belirtin. Varsayılan değer: false. |
| [Space](../../aspose.barcode.generation/codetextparameters/space/) { get; set; } | CodeText ve BarCode arasındaki boşluk, [`Unit`](../unit/) değerinde. Varsayılan değer: 2pt. EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon için yok sayılır. |
| [TwoDDisplayText](../../aspose.barcode.generation/codetextparameters/twoddisplaytext/) { get; set; } | 2D barkodlarda codetext yerine görüntülenecek metin. Şu barkodlar için kullanılır: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/codetextparameters/tostring/)() | Bu `CodetextParameters` nesnesinin insan tarafından okunabilir dize temsilini döndürür. |

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


