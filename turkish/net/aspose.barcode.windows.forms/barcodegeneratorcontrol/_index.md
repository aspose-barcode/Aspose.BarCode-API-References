---
title: "Sınıf BarCodeGeneratorControl"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Windows.Forms.BarCodeGeneratorControl sınıfı. BarCode Windows Kontrolü, araç kutusu panelinize gidin ve Aspose.BarCode.dll ekleyin ve BarCodeGeneratorControl görünecektir. Sadece sürükleyip Windows formunuza bırakın. bkz  bkz"
type: docs
weight: 1800
url: /tr/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Kontrolü, araç kutusu panelinize gidin ve Aspose.BarCode.dll'yi ekleyin, ardından BarcodeGeneratorControl'ün göründüğünü göreceksiniz. Sadece sürükleyip Windows formunuza bırakın. bak  bak

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol/)() | Varsayılan yapıcı. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode/) { get; set; } | Barkodun otomatik olarak yeniden boyutlandırıldığı modu alır veya ayarlar. Varsayılan değer AutoSizeMode.None. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor/) { get; set; } | Barkod görüntüsünün arka plan rengi. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight/) { get; } | BarCode görüntü yüksekliği, [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) özelliği AutoSizeMode.Nearest veya AutoSizeMode.Interpolation olarak ayarlandığında. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings/) { get; } | Barkod dolgu parametrelerini alır veya ayarlar [`Padding`](../../aspose.barcode.generation/padding/). |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype/) { get; set; } | BarCode'un kodlama tipi (semboloji). Mevcut sembolojiyi almak için [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) kullanın. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth/) { get; } | BarCode görüntü genişliği, [`AutoSizeMode`](../../aspose.barcode/generation/autosizemode/) özelliği AutoSizeMode.Nearest veya AutoSizeMode.Interpolation olarak ayarlandığında. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor/) { get; set; } | Çubukların rengi. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight/) { get; } | 1D barkodların çubuk yüksekliği. [`AutoSizeMode`](../../aspose.barcode/generation/autosizemode/) özelliği AutoSizeMode.Nearest veya AutoSizeMode.Interpolation olarak ayarlandıysa yok sayılır. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border/) { get; } | Kenar parametrelerini alır veya ayarlar [`BorderParameters`](../../aspose.barcode/generation/borderparameters/). |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove/) { get; } | BarCode görüntüsünün üzerindeki başlık. Bakınız [`CaptionUI`](../captionui/). |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow/) { get; } | BarCode görüntüsünün altındaki başlık. Bakınız [`CaptionUI`](../captionui/). |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow/) { get; set; } | Code128 ve GS1Code128 barkodları için insan tarafından okunabilir metinde her zaman kontrol toplamı basamağını göster. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext/) { get; set; } | Kodlanacak veri, farklı BarCode türleri farklı CodeText uzunluk kısıtlamalarına sahip olabilir. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters/) { get; } | CodeText parametrelerini alır veya ayarlar [`CodetextParametersUI`](../codetextparametersui/). |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype/) { get; set; } | BarCode'un kodlama tipi (semboloji). Mevcut sembolojiyi almak için [`EncodeTypes`](../../aspose.barcode.generation/encodetypes/) kullanın. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars/) { get; set; } | Çubukların doldurulup doldurulmadığını gösteren değeri alır veya ayarlar. Sadece 1D barkodlar için. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled/) { get; set; } | 1D barkodlar oluşturulurken sağlama toplamını etkinleştir. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution/) { get; set; } | BarCode görüntüsünün çözünürlüğünü alır veya ayarlar. Her iki boyut için tek bir değer. Varsayılan değer: 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle/) { get; set; } | BarCode görüntüsü döndürme açısı, derece cinsinden ölçülür, ör. RotationAngle = 0 veya RotationAngle = 360 dönüş olmadığını gösterir. RotationAngle 90, 180, 270 veya 0'a eşit değilse, tarayıcının görüntüyü okumasını zorlaştırabilir. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific/) { get; } | Belirli parametreler |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect/) { get; set; } | Yalnızca 1D barkodlar için. codetext hatalı ve değer true olarak ayarlanmışsa - istisna fırlatılır. Aksi takdirde codetext barkodun spesifikasyonuna uygun şekilde düzeltilir. İstisna her zaman şu durumlarda fırlatılır: Databar sembolojisi için codetext hatalıysa. İstisna hiçbir zaman fırlatılmaz: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Code128 sembolojisi için codetext hatalıysa. |
| [UseAntiAlias](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/useantialias/) { get; set; } | Görüntüyü renderlemek için anti-aliasing modunun kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar. |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio/) { get; set; } | Geniş çubukların Dar çubuklara oranı. Varsayılan değer: 3, yani geniş çubuklar dar çubukların 3 katı genişliğindedir. ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII için kullanılır. |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension/) { get; } | X-dimension, BarCode çubukları veya boşluklarının biriminin en küçük genişliğidir. Bunu artırmak, tüm barkod görüntüsü genişliğini artırır. [`AutoSizeMode`](../../aspose.barcode.generation/autosizemode/) özelliği AutoSizeMode.Nearest veya AutoSizeMode.Interpolation olarak ayarlanmışsa göz ardı edilir. |

### Ayrıca Bakınız

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol/)
* namespace [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms/)
* assembly [Aspose.BarCode](../../)


