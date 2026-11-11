---
title: "Sınıf BarcodeParameters"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.BarcodeParameters sınıfı. Barkod oluşturma parametreleri"
type: docs
weight: 1010
url: /tr/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

Barkod üretim parametreleri.

```csharp
public class BarcodeParameters
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost/) { get; } | AustralianPost barkod parametreleri. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec/) { get; } | Aztec parametreleri. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor/) { get; set; } | Çubukların rengi. Varsayılan değer: Color.Black. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight/) { get; set; } | 1D barkodların çubuk yüksekliği [`Unit`](../unit/) biriminde. [`AutoSizeMode`](../basegenerationparameters/autosizemode/) özelliği AutoSizeMode.Nearest veya AutoSizeMode.Interpolation olarak ayarlanmışsa yok sayılır. |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction/) { get; set; } | Baskı sırasında mürekkep yayılımını dengelemek için kullanılan çubuk azaltma değerini alır veya ayarlar. Varsayılan değer: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow/) { get; set; } | Code128 ve GS1Code128 barkodları için insan tarafından okunabilir metinde her zaman kontrol toplamı basamağını göster. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar/) { get; } | Codabar parametreleri. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock/) { get; } | Codablock parametreleri. |
| [Code128](../../aspose.barcode.generation/barcodeparameters/code128/) { get; } | Code128 parametreleri. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k/) { get; } | Code16K parametreleri. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters/) { get; } | Kod metni parametreleri. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon/) { get; } | Kupon parametreleri. UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon için kullanılır. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar/) { get; } | Databar parametreleri. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix/) { get; } | DataMatrix parametreleri. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode/) { get; } | DotCode parametreleri. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars/) { get; set; } | Çubukların doldurulup doldurulmadığını gösteren bir değeri alır veya ayarlar. Yalnızca 1D barkodlar için. Varsayılan değer: true. |
| [GS1](../../aspose.barcode.generation/barcodeparameters/gs1/) { get; } | GS1 parametreleri. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar/) { get; set; } | GS1 Bileşik Çubuk parametreleri. |
| [HanXin](../../aspose.barcode.generation/barcodeparameters/hanxin/) { get; } | HanXin parametreleri. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled/) { get; set; } | 1D barkodlar oluşturulurken sağlama toplamını etkinleştir. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf/) { get; } | ITF parametreleri. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode/) { get; } | MaxiCode parametreleri. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding/) { get; } | Barkod dolguları. Varsayılan değer: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode/) { get; } | PatchCode parametreleri. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417/) { get; } | PDF417 parametreleri. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal/) { get; } | Postal parametreleri. Postnet ve Planet için kullanılır. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr/) { get; } | QR, MicroQR ve RectMicroQR parametreleri. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement/) { get; } | Supplement parametreleri. Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN için kullanılır. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect/) { get; set; } | Yalnızca 1D barkodlar için. codetext hatalıysa ve değer true olarak ayarlanmışsa - bir istisna fırlatılır. Aksi takdirde codetext barkodun spesifikasyonuna uyması için düzeltilir. Aşağıdaki durumlarda her zaman istisna fırlatılır: Databar sembolojisi codetext hatalıysa. Aşağıdaki durumlarda istisna hiçbir zaman fırlatılmaz: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 sembolojisi codetext hatalıysa. |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio/) { get; set; } | Geniş çubukların Dar çubuklara oranı. Varsayılan değer: 3, yani geniş çubuklar dar çubukların 3 katı genişliğindedir. ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII için kullanılır. |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension/) { get; set; } | x-dimension, BarCode çubukları veya boşluklarının biriminin en küçük genişliğidir. Bunu artırmak, tüm barkod görüntüsü genişliğini artırır. [`AutoSizeMode`](../basegenerationparameters/autosizemode/) özelliği AutoSizeMode.Nearest veya AutoSizeMode.Interpolation olarak ayarlanmışsa yok sayılır. |

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


