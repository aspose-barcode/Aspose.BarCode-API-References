---
title: "Aspose::BarCode::BarCodeRecognition::QualitySettings class"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::BarCodeRecognition::QualitySettings sınıfı. QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmanıza olanak tanır. QualitySettings'i gömülü ön ayarlarla hızlıca ayarlayabilirsiniz: HighPerformance, NormalQuality, HighQuality, MaxQuality veya ayrı seçenekleri manuel olarak yapılandırabilirsiniz. C++'da QualitySettings'in varsayılan değeri NormalQuality'dir."
type: docs
weight: 3100
url: /tr/cpp/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class


[QualitySettings](./) allows to configure recognition quality and speed manually. You can quickly set up [QualitySettings](./) with embedded presets: HighPerformance, NormalQuality, HighQuality, MaxQuality or you can manually configure separate options. Default value of [QualitySettings](./) is NormalQuality.

```cpp
class QualitySettings : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_AllowIncorrectBarcodes](./get_allowincorrectbarcodes/)() const | Motorun hatalı kontrol toplamına veya hatalı değerlere sahip barkodları tanımasına izin verir. Mod, hatalı metne sahip hasar görmüş barkodları tanımak için kullanılabilir. |
| [get_BarcodeQuality](./get_barcodequality/)() const | Seçilen kaliteyle barkod öğelerini tanıyan yöntemleri etkinleştiren mod. Daha düşük kaliteye sahip barkod öğesi, tanıma süresini yavaşlatan daha zor yöntemler gerektirir. |
| [get_ComplexBackground](./get_complexbackground/)() const | Renkli görüntülerde renkli barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod. |
| [get_Deconvolution](./get_deconvolution/)() const | Görüntü bozulma seviyesini tanımlayan dekonvolüsyon (görüntü restorasyonu) modu. Aslen dekonvolüsyon, kamera ile görüntü elde edilirken bulanıklık gibi doğal bir fonksiyon tarafından bozulmuş (konvolüsyonlu) görüntüyü geri getirebilen bir işlevdir. Görüntüyü bozan fonksiyonu tespit edemediğimiz için, keskinlik veya matematiksel morfoloji gibi en iyi bilinen fonksiyonları kontrol etmemiz gerekir. |
| static [get_HighPerformance](./get_highperformance/)() | HighPerformance tanıma kalite ön ayarı. Yüksek kaliteli barkodlar bu modda iyi tanınır. |
| static [get_HighQuality](./get_highquality/)() | HighQuality tanıma kalite ön ayarı. Bu ön ayar düşük kaliteli barkodlar için geliştirilmiştir. Aşırı hasarlı barkodları tespit etmeye olanak tanır. |
| [get_InverseImage](./get_inverseimage/)() const | Ters renkli (parlaklık) görüntülerde barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod. |
| static [get_MaxQuality](./get_maxquality/)() | MaxQuality tanıma kalitesi ön ayarı. Bu ön ayar, tüm olası barkodları, hatta hatalı barkodları tanımak için geliştirilmiştir. |
| [get_MinimalXDimension](./get_minimalxdimension/)() const | UseMinimalXDimension ile kullanılan XDimension'ın piksel cinsinden minimal boyutu. |
| static [get_NormalQuality](./get_normalquality/)() | NormalQuality tanıma kalitesi ön ayarı. Çoğu barkod için uygundur. |
| [get_XDimension](./get_xdimension/)() const | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) modu, barkodun minimal öğesinin (matris hücresi veya çubuk) boyutunu (1'den sonsuza) ayarlar. |
| [set_AllowIncorrectBarcodes](./set_allowincorrectbarcodes/)(bool) | Motorun hatalı kontrol toplamına veya hatalı değerlere sahip barkodları tanımasına izin verir. Mod, hatalı metne sahip hasar görmüş barkodları tanımak için kullanılabilir. |
| [set_BarcodeQuality](./set_barcodequality/)(BarcodeQualityMode) | Seçilen kaliteyle barkod öğelerini tanıyan yöntemleri etkinleştiren mod. Daha düşük kaliteye sahip barkod öğesi, tanıma süresini yavaşlatan daha zor yöntemler gerektirir. |
| [set_ComplexBackground](./set_complexbackground/)(ComplexBackgroundMode) | Renkli görüntülerde renkli barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod. |
| [set_Deconvolution](./set_deconvolution/)(DeconvolutionMode) | Görüntü bozulma seviyesini tanımlayan dekonvolüsyon (görüntü restorasyonu) modu. Aslen dekonvolüsyon, kamera ile görüntü elde edilirken bulanıklık gibi doğal bir fonksiyon tarafından bozulmuş (konvolüsyonlu) görüntüyü geri getirebilen bir işlevdir. Görüntüyü bozan fonksiyonu tespit edemediğimiz için, keskinlik veya matematiksel morfoloji gibi en iyi bilinen fonksiyonları kontrol etmemiz gerekir. |
| [set_InverseImage](./set_inverseimage/)(InverseImageMode) | Ters renkli (parlaklık) görüntülerde barkodların ek tanımını etkinleştiren veya devre dışı bırakan mod. |
| [set_MinimalXDimension](./set_minimalxdimension/)(float) | UseMinimalXDimension ile kullanılan XDimension'ın piksel cinsinden minimal boyutu. |
| [set_XDimension](./set_xdimension/)(XDimensionMode) | [Recognition](../../aspose.barcode.barcoderecognition.recognition/) modu, barkodun minimal öğesinin (matris hücresi veya çubuk) boyutunu (1'den sonsuza) ayarlar. |
## Açıklamalar


Bu örnek, [QualitySettings](./) ile [BarCodeReader](../barcodereader/) kullanımını gösterir.
```cpp
[C#]
//HighPerformance yüksek performanslı tanıma modunu ayarla
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//HighQuality yüksek kalite tanıma modunu ayarla
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighQuality;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//Düşük boyutlu barkodlar için HighPerformance yüksek performanslı tanıma modunu ayarla
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}

//Düşük kaliteli barkodlar için HighPerformance yüksek performanslı tanıma modunu ayarla
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings = QualitySettings.HighPerformance;
    reader.QualitySettings.BarcodeQuality = BarcodeQualityMode.Low;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
