---
title: BarCodeGeneratorControl
second_title: Aspose.BarCode for .NET API Referansı
description: BarCode Windows Control araç kutusu panelinize gidin ve Aspose.BarCode.dll ekleyin ve BarcodeGeneratorControlün göründüğünü göreceksiniz. Sadece sürükleyip Windows formunuza bırakın. bkz. bkz.
type: docs
weight: 1050
url: /tr/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control, araç kutusu panelinize gidin ve Aspose.BarCode.dll, ekleyin ve BarcodeGeneratorControl'ün göründüğünü göreceksiniz. Sadece sürükleyip Windows formunuza bırakın. bkz. bkz.

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode) { get; set; } | Barkodun otomatik olarak yeniden boyutlandırılacağı modu alır veya ayarlar. Varsayılan değer AutoSizeMode.None. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor) { get; set; } | Barkod görüntüsünün arka plan rengi. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight) { get; } | BarCode görüntü yüksekliği[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) özellik, AutoSizeMode.Nearest veya AutoSizeMode.Interpolation. olarak ayarlandı |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings) { get; } | Barkod dolgu parametrelerini alır veya ayarlar[`Padding`](../../aspose.barcode.generation/padding) . |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype) { get; set; } | BarCode'un kodlama türü (sembololoji). Kullanım[`EncodeTypes`](../../aspose.barcode.generation/encodetypes) mevcut sembolojiyi almak için. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth) { get; } | BarCode görüntü genişliği[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) özellik, AutoSizeMode.Nearest veya AutoSizeMode.Interpolation. olarak ayarlandı |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor) { get; set; } | Çubuk rengi. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight) { get; } | 1D barkodların çubuklarının yüksekliği. Varsa yoksayılır[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) özellik, AutoSizeMode.Nearest veya AutoSizeMode.Interpolation. olarak ayarlandı |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border) { get; } | Kenarlık parametrelerini alır veya ayarlar[`BorderParameters`](../../aspose.barcode.generation/borderparameters) . |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove) { get; } | Başlık Barkod görüntüsünün üstünde. Görmek[`CaptionParameters`](../../aspose.barcode.generation/captionparameters) . |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow) { get; } | Başlık Barkod görüntüsünün altında. Görmek[`CaptionParameters`](../../aspose.barcode.generation/captionparameters) . |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow) { get; set; } | Code128 ve GS1Code128 barkodları için insan tarafından okunabilir metinde her zaman sağlama toplamı rakamını görüntüleyin. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext) { get; set; } | Kodlanacak veriler, farklı BarCode türlerinin farklı CodeText uzunluk kısıtlamaları olabilir. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters) { get; } | CodeText parametrelerini alır veya ayarlar[`CodetextParameters`](../../aspose.barcode.generation/codetextparameters) . |
| [EnableEscape](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/enableescape) { get; set; } | "\" karakterinin CodeText özelliğinde bir çıkış karakteri olarak açıklanıp açıklanmadığını gösterir. Yalnızca Pdf417, DataMatrix, Code128 için kullanılır EnableEscape true ise, "\" özel bir kaçış karakteri olarak açıklanacaktır. Aksi takdirde, "\" normal karakterler gibi davranır. Aspose.BarCode, ASCII kontrol kodu karakterleri için ondalık ascii kodu ve anımsatıcı girişini destekler. Örneğin, \013 ve \\CR, CR anlamına gelir. |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype) { get; set; } | BarCode'un kodlama türü (sembololoji). Kullanım[`EncodeTypes`](../../aspose.barcode.generation/encodetypes) mevcut sembolojiyi almak için. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars) { get; set; } | Çubukların doldurulup doldurulmadığını gösteren bir değer alır veya ayarlar. Yalnızca 1D barkodlar için. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled) { get; set; } | Nesil 1D barkodlar sırasında sağlama toplamını etkinleştirin. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution) { get; set; } | BarCode görüntüsünün çözünürlüğünü alır veya ayarlar. Her iki boyut için bir değer. Varsayılan değer: 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle) { get; set; } | BarCode görüntü döndürme açısı, derece cinsinden ölçülür, örneğin Dönme Açısı = 0 veya DönmeAçısı = 360, döndürme olmadığı anlamına gelir. Döndürme Açısı 90, 180, 270 veya 0'a eşit DEĞİLSE, tarayıcının görüntüyü okuma zorluğunu artırabilir. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific) { get; } | Belirli parametreler |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect) { get; set; } | Yalnızca 1D barkodlar için. Kod metni yanlışsa ve değer true olarak ayarlanmışsa - istisna atılır. Aksi takdirde, kod metni, barkodun spesifikasyonuna uyacak şekilde düzeltilir. Şu durumlar için istisna oluşturulur: Kod metni yanlışsa veri çubuğu sembolojisi. Kod metni yanlışsa, AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128 sembolojisi için her zaman istisna atılmaz . |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio) { get; set; } | Geniş çubuklar - Dar çubuklar oranı. Varsayılan değer: 3, yani geniş çubuklar dar çubukların 3 katıdır. ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost için kullanılır , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension) { get; } | X-boyutu, Barkod çubuklarının veya boşluklarının biriminin en küçük genişliğidir. Bunu artırın, tüm barkod görüntü genişliğini artıracaktır. Varsa yoksayılır[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) özellik, AutoSizeMode.Nearest veya AutoSizeMode.Interpolation. olarak ayarlandı |

### Ayrıca bakınız

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol)
* ad alanı [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms)
* toplantı [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
