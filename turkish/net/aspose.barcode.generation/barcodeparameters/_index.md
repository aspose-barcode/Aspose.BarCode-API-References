---
title: BarcodeParameters
second_title: Aspose.BarCode for .NET API Referansı
description: Barkod oluşturma parametreleri.
type: docs
weight: 500
url: /tr/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

Barkod oluşturma parametreleri.

```csharp
public class BarcodeParameters
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost) { get; } | AustralianPost barkod parametreleri. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec) { get; } | Aztek parametreleri. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor) { get; set; } | Çubuklar color. Varsayılan değer: Color.Black. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight) { get; set; } | 1D barkod çubuklarının yüksekliği[`Unit`](../unit) value. Varsa yoksayılırAutoSizeMode özellik, AutoSizeMode.Nearest veya AutoSizeMode.Interpolation. olarak ayarlandı |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction) { get; set; } | Yazdırma sırasında mürekkebin yayılmasını telafi etmek için kullanılan çubuk azaltma değerini alın veya ayarlar. Varsayılan değer: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow) { get; set; } | Code128 ve GS1Code128 barkodları için insan tarafından okunabilir metinde her zaman sağlama toplamı rakamını görüntüleyin. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar) { get; } | Codabar parametreleri. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock) { get; } | Codablock parametreleri. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k) { get; } | Code16K parametreleri. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters) { get; } | Kod metni parametreleri. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon) { get; } | Kupon parametreleri. UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. için kullanılır |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar) { get; } | Veri çubuğu parametreleri. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix) { get; } | DataMatrix parametreleri. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode) { get; } | DotCode parametreleri. |
| [EnableEscape](../../aspose.barcode.generation/barcodeparameters/enableescape) { get; set; } | "\" karakterinin CodeText özelliğinde bir çıkış karakteri olarak açıklanıp açıklanmadığını gösterir. Yalnızca Pdf417, DataMatrix, Code128 için kullanılır EnableEscape true ise, "\" özel bir kaçış karakteri olarak açıklanacaktır. Aksi takdirde, "\" normal karakterler gibi davranır. Aspose.BarCode, ASCII kontrol kodu karakterleri için ondalık ascii kodu ve anımsatıcı girişini destekler. Örneğin, \013 ve \\CR, CR anlamına gelir. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars) { get; set; } | Çubukların doldurulup doldurulmadığını gösteren bir değer alır veya ayarlar. Yalnızca 1D barkodlar için. Varsayılan değer: true. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar) { get; set; } | GS1 Bileşik Çubuk parametreleri. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled) { get; set; } | Nesil 1D barkodlar sırasında sağlama toplamını etkinleştirin. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf) { get; } | ITF parametreleri. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode) { get; } | MaxiCode parametreleri. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding) { get; } | Barkod dolguları. Varsayılan değer: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode) { get; } | Yama Kodu parametreleri. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417) { get; } | PDF417 parametreleri. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal) { get; } | Posta parametreleri. Postnet için kullanılır, Planet. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr) { get; } | QR parametreleri. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement) { get; } | Ek parametreler. Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. için kullanılır |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect) { get; set; } | Yalnızca 1D barkodlar için. Kod metni yanlışsa ve değer true olarak ayarlanmışsa - istisna atılır. Aksi takdirde, kod metni, barkodun spesifikasyonuna uyacak şekilde düzeltilir. Şu durumlar için istisna oluşturulur: Kod metni yanlışsa veri çubuğu sembolojisi. Kod metni yanlışsa, AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128 sembolojisi için her zaman istisna atılmaz . |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio) { get; set; } | Geniş çubuklar - Dar çubuklar oranı. Varsayılan değer: 3, yani geniş çubuklar dar çubukların 3 katıdır. ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost için kullanılır , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension) { get; set; } | x-boyutu, BarCode çubuklarının veya boşluklarının biriminin en küçük genişliğidir. Bunu artırın, tüm barkod görüntü genişliğini artıracaktır. Varsa yoksayılırAutoSizeMode özellik, AutoSizeMode.Nearest veya AutoSizeMode.Interpolation. olarak ayarlandı |

### Ayrıca bakınız

* ad alanı [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* toplantı [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
