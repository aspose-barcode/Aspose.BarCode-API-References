---
title: "Sınıf CodetextParametersUI"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Windows.Forms.CodetextParametersUI sınıfı. Codetext parametreleri"
type: docs
weight: 1820
url: /tr/net/aspose.barcode.windows.forms/codetextparametersui/
---
## CodetextParametersUI class

Kod metni parametreleri.

```csharp
public class CodetextParametersUI
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Alignment](../../aspose.barcode.windows.forms/codetextparametersui/alignment/) { get; set; } | Kod metninin hizalamasını alır veya ayarlar. Varsayılan değer: StringAlignment.Center. |
| [Color](../../aspose.barcode.windows.forms/codetextparametersui/color/) { get; set; } | Görüntülenen CodeText'in Rengini belirtin. Varsayılan değer: Color.Black. |
| [Font](../../aspose.barcode.windows.forms/codetextparametersui/font/) { get; set; } | Görüntülenen CodeText'in yazı tipini belirtin. Varsayılan değer: Arial 5pt regular. FontMode FontMode.Auto olarak ayarlandığında yok sayılır. |
| [FontMode](../../aspose.barcode.windows.forms/codetextparametersui/fontmode/) { get; set; } | FontMode'u belirtin. FontMode Auto olarak ayarlanırsa, yazı tipi boyutu xDimension değerine göre otomatik olarak hesaplanır. FontMode.Auto'yu özellikle AutoSizeMode.Nearest veya AutoSizeMode.Interpolation içinde kullanmanız önerilir. Varsayılan değer: FontMode.Auto. |
| [Location](../../aspose.barcode.windows.forms/codetextparametersui/location/) { get; set; } | Görüntülenen CodeText konumunu belirtin, CodeText'i gizlemek için CodeLocation.None olarak ayarlayın. Varsayılan değer: 1D barkodlar için CodeLocation.Below ve 2D barkodlar için CodeLocation.None. |
| [Space](../../aspose.barcode.windows.forms/codetextparametersui/space/) { get; } | CodeText ve BarCode arasındaki boşluk [`Unit`](../../aspose.barcode.generation/unit/) değerinde. Varsayılan değer: 2pt. EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon için yoksayılır. |
| [TwoDDisplayText](../../aspose.barcode.windows.forms/codetextparametersui/twoddisplaytext/) { get; set; } | 2D barkodlarda codetext yerine görüntülenecek metin. Şu barkodlar için kullanılır: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [ToString](../../aspose.barcode.windows.forms/codetextparametersui/tostring/)() | Bu [`CodetextParameters`](../../aspose.barcode.generation/codetextparameters/) nesnesinin insan tarafından okunabilir dize temsilini döndürür. |

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


