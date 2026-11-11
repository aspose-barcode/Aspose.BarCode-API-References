---
title: "Sınıf QualitySettings"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.QualitySettings sınıfı. QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmanıza olanak tanır. QualitySettings'i, yerleşik ön ayarlar HighPerformance, NormalQuality, HighQuality, MaxQuality ile hızlıca ayarlayabilir veya ayrı seçenekleri manuel olarak yapılandırabilirsiniz. QualitySettings'in varsayılan değeri NormalQuality'dir."
type: docs
weight: 370
url: /tr/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmanıza olanak tanır. QualitySettings'i gömülü ön ayarlarla hızlıca ayarlayabilirsiniz: HighPerformance, NormalQuality, HighQuality, MaxQuality veya ayrı seçenekleri manuel olarak yapılandırabilirsiniz. QualitySettings'in varsayılan değeri NormalQuality'dir.

```csharp
public sealed class QualitySettings
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance/) { get; } | HighPerformance tanıma kalite ön ayarı. Bu modda yüksek kaliteli barkodlar iyi tanınır. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality/) { get; } | HighQuality tanıma kalite ön ayarı. Bu ön ayar düşük kaliteli barkodlar için geliştirilmiştir. Aşırı hasar görmüş barkodların tespit edilmesini sağlar. |
| static [MaxQuality](../../aspose.barcode.barcoderecognition/qualitysettings/maxquality/) { get; } | MaxQuality tanıma kalite ön ayarı. Bu ön ayar, hatalı barkodlar dahil olmak üzere tüm olası barkodları tanımak için geliştirilmiştir. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality/) { get; } | NormalQuality tanıma kalite ön ayarı. Çoğu barkod için uygundur |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes/) { get; set; } | Motorun hatalı kontrol toplamına veya hatalı değerlere sahip barkodları tanımasına izin verir. Mod, hatalı metne sahip hasar görmüş barkodları tanımak için kullanılabilir. |
| [BarcodeQuality](../../aspose.barcode.barcoderecognition/qualitysettings/barcodequality/) { get; set; } | Seçilen kaliteyle barkod öğelerini tanıyan yöntemleri etkinleştiren mod. Daha düşük kaliteye sahip barkod öğesi, tanıma süresini yavaşlatan daha zor yöntemler gerektirir. |
| [ComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/complexbackground/) { get; set; } | Renkli görüntülerde renkli barkodların ek tanımasını etkinleştiren veya devre dışı bırakan mod. |
| [Deconvolution](../../aspose.barcode.barcoderecognition/qualitysettings/deconvolution/) { get; set; } | Dekonvolüsyon (görüntü restorasyonu) modu, görüntü bozulma seviyesini tanımlar. Aslen dekonvolüsyon, kamera ile görüntü elde edilirken bulanıklık gibi doğal bir fonksiyon tarafından bozulmuş (konvolüsyonlu) görüntüyü geri yükleyebilen bir işlevtir. Görüntüyü bozan fonksiyonu tespit edemediğimiz için, keskinlik veya matematiksel morfoloji gibi en iyi bilinen fonksiyonları kontrol etmemiz gerekir. |
| [InverseImage](../../aspose.barcode.barcoderecognition/qualitysettings/inverseimage/) { get; set; } | Renkleri (parlaklığı) ters çevrilmiş görüntülerde barkodların ek tanımasını etkinleştiren veya devre dışı bırakan mod. |
| [MinimalXDimension](../../aspose.barcode.barcoderecognition/qualitysettings/minimalxdimension/) { get; set; } | UseMinimalXDimension ile kullanılan XDimension'ın piksel cinsinden minimal boyutu. |
| [XDimension](../../aspose.barcode.barcoderecognition/qualitysettings/xdimension/) { get; set; } | Barkodun en küçük öğesinin (matris hücresi veya çubuk) boyutunu (1'den sonsuza) belirleyen tanıma modu. |

## Örnekler

Bu örnek, QualitySettings'i BarCodeReader ile nasıl kullanacağınızı gösterir

```csharp
[C#]
//HighPerformance tanıma modunu ayarla
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//HighQuality tanıma modunu ayarla
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//Düşük boyutlu barkodlar için HighPerformance tanıma modunu ayarla
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//Düşük kalite barkodlar için HighPerformance tanıma modunu ayarla
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}    
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


