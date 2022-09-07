---
title: QualitySettings
second_title: Aspose.BarCode for .NET API Referansı
description: QualitySettings tanıma kalitesini ve hızını manuel olarak yapılandırmanıza olanak tanır. QualitySettingsi yerleşik ön ayarlarla hızlı bir şekilde ayarlayabilirsiniz HighPerformance NormalQuality HighQuality MaxBarCodes veya ayrı seçenekleri manuel olarak yapılandırabilirsiniz. QualitySettingsin varsayılan değeri NormalQualitydir.
type: docs
weight: 250
url: /tr/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings, tanıma kalitesini ve hızını manuel olarak yapılandırmanıza olanak tanır. QualitySettings'i yerleşik ön ayarlarla hızlı bir şekilde ayarlayabilirsiniz: HighPerformance, NormalQuality, HighQuality, MaxBarCodes veya ayrı seçenekleri manuel olarak yapılandırabilirsiniz. QualitySettings'in varsayılan değeri NormalQuality'dir.

```csharp
public sealed class QualitySettings
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance) { get; } | HighPerformance tanıma kalitesi ön ayarı. Yüksek kaliteli barkodlar bu modda iyi tanınır. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality) { get; } | Yüksek Kalite tanıma kalitesi ön ayarı. Bu ön ayar, düşük kaliteli barkodlar için geliştirilmiştir. Çapraz ve çok hasarlı barkodları algılamaya olanak tanır. |
| static [HighQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/highqualitydetection) { get; } | HighQualityDetection tanıma kalitesi ön ayarı. NormalQuality ile aynı, ancak yüksek kalitede[`DetectorSettings`](./detectorsettings) |
| static [MaxBarCodes](../../aspose.barcode.barcoderecognition/qualitysettings/maxbarcodes) { get; } | MaxBarCodes tanıma kalitesi ön ayarı. Bu ön ayar, hatalı barkodlar dahil tüm olası barkodları tanımak için geliştirilmiştir. |
| static [MaxQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/maxqualitydetection) { get; } | MaxQualityDetection tanıma kalitesi ön ayarı. NormalQuality ile aynı, ancak en yüksek kalitede[`DetectorSettings`](./detectorsettings). Çapraz ve hasarlı barkodları algılamayı sağlar. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality) { get; } | NormalQuality tanıma kalitesi ön ayarı. Barkodların çoğu için uygundur |
| [AllowComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/allowcomplexbackground) { get; set; } | Motorun, ek tarama olarak renkli arka plandaki renkli barkodları tanımasını sağlar. Son derece yavaş mod. |
| [AllowDatamatrixIndustrialBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowdatamatrixindustrialbarcodes) { get; set; } | Datamatrix motorunun kesikli endüstriyel Datamatrix barkodlarını tanımasını sağlar. Yalnızca noktalardan oluşan kesikli barkodlar için yardımcı olan yavaş mod. |
| [AllowDecreasedImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowdecreasedimage) { get; set; } | Motorun ek tarama olarak azaltılmış görüntüyü tanımasına izin verir. Küçültme boyutu dahili motor algoritmaları tarafından seçilir. Mod, gürültülü ve bulanık ancak yüksek çözünürlükte yakalanan barkodların tanınmasına yardımcı olur. |
| [AllowDetectScanGap](../../aspose.barcode.barcoderecognition/qualitysettings/allowdetectscangap) { get; set; } | Motorun tanıma hızını artırmak için taramalar arasındaki boşluğu kullanmasına izin verir. Mod, alçak barkodlarla tanıma sorunları yapabilir. |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes) { get; set; } | Motorun hatalı sağlama toplamı veya yanlış değerlere sahip barkodları tanımasını sağlar. Modu, hatalı metin içeren hasarlı barkodları tanımak için kullanılabilir. |
| [AllowInvertImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowinvertimage) { get; set; } | Motorun ters renkli görüntüyü ek tarama olarak tanımasını sağlar. Barkod siyah zemin üzerine beyaz olduğunda mod kullanılabilir. |
| [AllowMedianSmoothing](../../aspose.barcode.barcoderecognition/qualitysettings/allowmediansmoothing) { get; set; } | Motorun ek tarama olarak medyan yumuşatmayı etkinleştirmesine izin verir. Mod, gürültülü barkodları tanımaya yardımcı olur. |
| [AllowMicroWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowmicrowhitespotsremoving) { get; set; } | Posta barkodlarının hafif gürültülü görüntüleri tanımasını sağlar. Mod, hafif hasar görmüş Posta barkodlarını tanımaya yardımcı olur. |
| [AllowOneDFastBarcodesDetector](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedfastbarcodesdetector) { get; set; } | 1D barkodlar için motorun, neredeyse tüm görüntüyü dolduran yüksek kaliteli barkodları hızla tanımasını sağlar. Modu, İnternet'ten oluşturulan barkodların hızla tanınmasına yardımcı olur. |
| [AllowOneDWipedBarsRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedwipedbarsrestoration) { get; set; } | 1D barkodlar motorunun, desende tek silinmiş/yapıştırılmış çubuklarla barkodları tanımasını sağlar. |
| [AllowQRMicroQrRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowqrmicroqrrestoration) { get; set; } | QR/MicroQR motorunun hasarlı MicroQR barkodlarını tanımasını sağlar. |
| [AllowRegularImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowregularimage) { get; set; } | Motorun, ana tarama olarak herhangi bir geri yükleme olmaksızın normal görüntüyü tanımasını sağlar. Resmi olduğu gibi tanıma modu. |
| [AllowSaltAndPaperFiltering](../../aspose.barcode.barcoderecognition/qualitysettings/allowsaltandpaperfiltering) { get; set; } | Motorun, tuz ve kağıt gürültü türüyle barkodları tanımasını sağlar. Mod, beyaz ve siyah noktalarla küçük gürültüyü kaldırabilir. |
| [AllowWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowwhitespotsremoving) { get; set; } | Motorun ek tarama olarak küçük beyaz noktalar olmadan görüntüyü tanımasını sağlar. Mod, parazitli görüntünün yanı sıra medyan yumuşatma filtrelemesini tanımaya yardımcı olur. |
| [CheckMore1DVariants](../../aspose.barcode.barcoderecognition/qualitysettings/checkmore1dvariants) { get; set; } | Daha fazla tanıma varyantını kontrol ederek motorun 1D barkodları sağlama toplamı ile tanımasını sağlar. Varsayılan değer: False. |
| [DetectorSettings](../../aspose.barcode.barcoderecognition/qualitysettings/detectorsettings) { get; set; } | Barkod algılayıcı ayarları. |
| [FastScanOnly](../../aspose.barcode.barcoderecognition/qualitysettings/fastscanonly) { get; set; } | 1D barkodlar için motorun bir görüntünün orta dilimini hızlı bir şekilde tanımasını ve herhangi bir zaman alıcı algoritma kullanmadan sonucu döndürmesini sağlar. |
| [MedianSmoothingWindowSize](../../aspose.barcode.barcoderecognition/qualitysettings/mediansmoothingwindowsize) { get; set; } | Medyan yumuşatma için pencere boyutu. Tipik değerler 3 veya 4'tür. Varsayılan değer 3'tür. AllowMedianSmoothing ayarlanmalıdır. |
| [ReadTinyBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/readtinybarcodes) { get; set; } | Motorun büyük resimlerdeki küçük barkodları tanımasını sağlar. yoksa yoksayıldı[`AllowIncorrectBarcodes`](./allowincorrectbarcodes) True olarak ayarlanır. Varsayılan değer: False. |
| [UseOldBarcodeDetector](../../aspose.barcode.barcoderecognition/qualitysettings/useoldbarcodedetector) { get; set; } | Eski barkod algılayıcıya geçer. |

### Örnekler

Bu örnek, BarCodeReader ile QualitySettings'in nasıl kullanılacağını gösterir.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //yüksek performans modunu ayarla
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //normal kalite modu varsayılan olarak ayarlanmıştır
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //düşük hız tanıma ile yüksek kalite modunu ayarla 
   reader.QualitySettings = QualitySettings.HighQuality;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // yanlış bile olsa olası tüm barkodları bulmaya çalışan maksimum barkod modunu ayarlayın. En yavaş tanıma modu
   reader.QualitySettings = QualitySettings.MaxBarCodes;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //yüksek performans modunu ayarla
   reader.QualitySettings = QualitySettings.HighPerformance;
   // ayrı seçenekleri ayarla
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //varsayılan mod NormalQuality'dir
   // ayrı seçenekleri ayarla
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'yüksek performans modunu ayarla
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'normal kalite modu varsayılan olarak ayarlanmıştır
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'düşük hız tanıma ile yüksek kalite modunu ayarlayın
    reader.QualitySettings = QualitySettings.HighQuality
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'Tüm olası barkodları, hatta yanlış bile bulmaya çalışan maksimum barkod modunu ayarlayın. En yavaş tanıma modu
    reader.QualitySettings = QualitySettings.MaxBarCodes
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'yüksek performans modunu ayarla
   reader.QualitySettings = QualitySettings.HighPerformance
   'ayrı seçenekler ayarla
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'varsayılan mod NormalQuality'dir
   'ayrı seçenekler ayarla
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### Ayrıca bakınız

* ad alanı [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* toplantı [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
