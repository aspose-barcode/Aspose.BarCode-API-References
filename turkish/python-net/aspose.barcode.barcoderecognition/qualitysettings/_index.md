---
title: "QualitySettings"
second_title: "Python için .NET API Referansı aracılığıyla Aspose.BarCode"
description: 
type: docs
url: /tr/python-net/aspose.barcode.barcoderecognition/qualitysettings/
---

## QualitySettings class

QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmanıza olanak tanır.<br/>            Gömülü ön ayarlarla QualitySettings'i hızlıca ayarlayabilirsiniz: HighPerformance, NormalQuality, HighQuality, MaxQuality veya ayrı seçenekleri manuel olarak yapılandırabilirsiniz.<br/>            QualitySettings'in varsayılan değeri NormalQuality'dir.

QualitySettings türü aşağıdaki üyeleri sunar:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| high_performance | HighPerformance tanıma kalite ön ayarı. Yüksek kaliteli barkodlar bu modda iyi tanınır. |
| normal_quality | NormalQuality tanıma kalitesi ön ayarı. Çoğu barkod için uygundur. |
| high_quality | HighQuality tanıma kalitesi ön ayarı. Bu ön ayar düşük kaliteli barkodlar için geliştirilmiştir. Çok hasar görmüş barkodların tespit edilmesini sağlar. |
| max_quality | MaxQuality tanıma kalitesi ön ayarı. Bu ön ayar, hatalı barkodlar dahil olmak üzere tüm olası barkodları tanımak için geliştirilmiştir. |
| x_dimension | Barkodun en küçük öğesinin (matris hücresi veya çubuk) boyutunu (1'den sonsuza) ayarlayan tanıma modu. |
| minimal_x_dimension | UseMinimalXDimension ile kullanılan XDimension'ın piksel cinsinden minimum boyutu. |
| barcode_quality | Seçilen kaliteye sahip barkod öğelerini tanımak için yöntemleri etkinleştiren mod. Daha düşük kaliteye sahip barkod öğesi, tanıma süresini yavaşlatan daha zor yöntemler gerektirir. |
| deconvolution | Deconvolution (görüntü restorasyonu) modu, görüntü bozulma seviyesini tanımlar. Aslen deconvolution, kamera ile görüntü elde ederken bulanıklık gibi doğal bir fonksiyon tarafından bozulmuş <br/>            (konvolüsyon) görüntüyü geri getirebilen bir işlevdir. Görüntüyü bozan fonksiyonu tespit edemediğimiz için, <br/>            keskinlik veya matematiksel morfoloji gibi en iyi bilinen fonksiyonları kontrol etmemiz gerekir. |
| inverse_image | Renkleri (parlaklığı) ters çevrilmiş görüntülerde barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod. |
| complex_background | Renkli görüntülerde renkli barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod. |
| allow_incorrect_barcodes | Motorun hatalı kontrol toplamına veya hatalı değerlere sahip barkodları tanımasına izin verir. Mod, hatalı metne sahip hasar görmüş barkodları tanımak için kullanılabilir. |

### Ayrıca Bakınız

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

