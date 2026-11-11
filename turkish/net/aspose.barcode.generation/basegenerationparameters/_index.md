---
title: "Sınıf BaseGenerationParameters"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Generation.BaseGenerationParameters sınıfı. Barkod görüntüsü oluşturma parametreleri"
type: docs
weight: 1030
url: /tr/net/aspose.barcode.generation/basegenerationparameters/
---
## BaseGenerationParameters class

Barkod görüntüsü üretim parametreleri.

```csharp
public class BaseGenerationParameters
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.generation/basegenerationparameters/autosizemode/) { get; set; } | Otomatik boyutlandırma modlarının farklı türlerini belirtir. Varsayılan değer: AutoSizeMode.None. |
| [BackColor](../../aspose.barcode.generation/basegenerationparameters/backcolor/) { get; set; } | Barkod görüntüsünün arka plan rengi. Varsayılan değer: Color.White. Bkz. Color. |
| [Barcode](../../aspose.barcode.generation/basegenerationparameters/barcode/) { get; } | Tüm barkod özelliklerini içeren [`BarcodeParameters`](../barcodeparameters/) alır. |
| [Border](../../aspose.barcode.generation/basegenerationparameters/border/) { get; } | Barkod kenarı için tüm yapılandırma özelliklerini içeren [`BorderParameters`](../borderparameters/) alır. |
| [CaptionAbove](../../aspose.barcode.generation/basegenerationparameters/captionabove/) { get; } | BarCode görüntüsünün üstündeki başlık. Bkz. [`CaptionParameters`](../captionparameters/). |
| [CaptionBelow](../../aspose.barcode.generation/basegenerationparameters/captionbelow/) { get; } | BarCode görüntüsünün altındaki başlık. Bkz. [`CaptionParameters`](../captionparameters/). |
| [Image](../../aspose.barcode.generation/basegenerationparameters/image/) { get; } | Görüntü parametreleri. Bkz. [`ImageParameters`](../imageparameters/). |
| [ImageHeight](../../aspose.barcode.generation/basegenerationparameters/imageheight/) { get; set; } | BarCode görüntü yüksekliği, [`AutoSizeMode`](./autosizemode/) özelliği AutoSizeMode.Nearest veya AutoSizeMode.Interpolation olarak ayarlandığında. |
| [ImageWidth](../../aspose.barcode.generation/basegenerationparameters/imagewidth/) { get; set; } | BarCode görüntü genişliği, [`AutoSizeMode`](./autosizemode/) özelliği AutoSizeMode.Nearest veya AutoSizeMode.Interpolation olarak ayarlandığında. |
| [Resolution](../../aspose.barcode.generation/basegenerationparameters/resolution/) { get; set; } | BarCode görüntüsünün çözünürlüğünü alır veya ayarlar. Her iki boyut için tek bir değer. Varsayılan değer: 96 dpi. |
| [RotationAngle](../../aspose.barcode.generation/basegenerationparameters/rotationangle/) { get; set; } | BarCode görüntüsü döndürme açısı, derece cinsinden ölçülür, ör. RotationAngle = 0 veya RotationAngle = 360 dönüş olmadığını gösterir. RotationAngle 90, 180, 270 veya 0'a eşit değilse, tarayıcının görüntüyü okumasını zorlaştırabilir. Varsayılan değer: 0. |
| [UseAntiAlias](../../aspose.barcode.generation/basegenerationparameters/useantialias/) { get; set; } | Görüntüyü renderlamak için anti-aliasing modunun kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar |

### Ayrıca Bakınız

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


