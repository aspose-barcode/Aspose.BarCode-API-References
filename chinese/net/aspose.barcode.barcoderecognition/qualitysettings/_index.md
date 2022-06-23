---
title: QualitySettings
second_title: Aspose.BarCode for .NET API 参考
description: QualitySettings 允许手动配置识别质量和速度 您可以通过嵌入式预设快速设置 QualitySettingsHighPerformanceNormalQuality HighQualityMaxBarCodes 或者您可以手动配置单独的选项 QualitySettings 的默认值为 NormalQuality
type: docs
weight: 250
url: /zh/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings 允许手动配置识别质量和速度。 您可以通过嵌入式预设快速设置 QualitySettings：HighPerformance、NormalQuality、 HighQuality、MaxBarCodes 或者您可以手动配置单独的选项。 QualitySettings 的默认值为 NormalQuality。

```csharp
public sealed class QualitySettings
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance) { get; } | 高性能识别质量预设。在此模式下可以很好地识别高质量的条码。 |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality) { get; } | 高质量识别质量预设。此预设是为低质量条码开发的。 允许检测对角线和高度损坏的条码。 |
| static [HighQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/highqualitydetection) { get; } | HighQualityDetection 识别质量预设。与 NormalQuality 相同但具有高质量[`DetectorSettings`](./detectorsettings) |
| static [MaxBarCodes](../../aspose.barcode.barcoderecognition/qualitysettings/maxbarcodes) { get; } | MaxBarCodes 识别质量预设。此预设旨在识别所有可能的条形码，甚至是不正确的条形码。 |
| static [MaxQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/maxqualitydetection) { get; } | MaxQualityDetection 识别质量预设。与 NormalQuality 相同，但质量最高[`DetectorSettings`](./detectorsettings)。 允许检测对角和损坏的条码。 |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality) { get; } | NormalQuality 识别质量预设。适用于大多数条码 |
| [AllowComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/allowcomplexbackground) { get; set; } | 允许引擎将彩色背景上的彩色条码识别为附加扫描。极慢模式。 |
| [AllowDatamatrixIndustrialBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowdatamatrixindustrialbarcodes) { get; set; } | 允许 Datamatrix 引擎识别虚线工业 Datamatrix 条码。 慢速模式，仅适用于由斑点组成的虚线条码。 |
| [AllowDecreasedImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowdecreasedimage) { get; set; } | 允许引擎将缩小的图像识别为附加扫描。减小的大小由内部引擎算法选择。 模式有助于识别噪声和模糊但以高分辨率捕获的条形码。 |
| [AllowDetectScanGap](../../aspose.barcode.barcoderecognition/qualitysettings/allowdetectscangap) { get; set; } | 允许引擎使用扫描之间的间隙来提高识别速度。模式会使低高度条码出现识别问题。 |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes) { get; set; } | 允许引擎识别校验和或值不正确的条形码。 模式可用于识别文本不正确的损坏条码。 |
| [AllowInvertImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowinvertimage) { get; set; } | 允许引擎将反色图像识别为附加扫描。当条形码为黑色背景上的白色时，可以使用模式。 |
| [AllowMedianSmoothing](../../aspose.barcode.barcoderecognition/qualitysettings/allowmediansmoothing) { get; set; } | 允许引擎启用中值平滑作为附加扫描。模式有助于识别噪声条码。 |
| [AllowMicroWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowmicrowhitespotsremoving) { get; set; } | 允许邮政条码引擎识别轻微噪点的图像。模式有助于识别轻微损坏的邮政条码。 |
| [AllowOneDFastBarcodesDetector](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedfastbarcodesdetector) { get; set; } | 允许一维条码引擎快速识别几乎填满整个图像的高质量条码。 模式有助于快速识别从互联网生成的条码。 |
| [AllowOneDWipedBarsRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedwipedbarsrestoration) { get; set; } | 允许一维条码引擎识别图案中带有单个擦拭/胶合条的条码。 |
| [AllowQRMicroQrRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowqrmicroqrrestoration) { get; set; } | 允许 QR/MicroQR 引擎识别损坏的 MicroQR 条码。 |
| [AllowRegularImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowregularimage) { get; set; } | 允许引擎将没有任何恢复的常规图像识别为主扫描。按原样识别图像的模式。 |
| [AllowSaltAndPaperFiltering](../../aspose.barcode.barcoderecognition/qualitysettings/allowsaltandpaperfiltering) { get; set; } | 允许引擎识别带有盐和纸张噪声类型的条码。模式可以去除带有白点和黑点的小噪点。 |
| [AllowWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowwhitespotsremoving) { get; set; } | 允许引擎识别没有小白点的图像作为附加扫描。模式有助于识别噪声图像以及中值平滑滤波。 |
| [CheckMore1DVariants](../../aspose.barcode.barcoderecognition/qualitysettings/checkmore1dvariants) { get; set; } | 允许引擎通过检查更多识别变体来识别带有校验和的一维条码。默认值:假。 |
| [DetectorSettings](../../aspose.barcode.barcoderecognition/qualitysettings/detectorsettings) { get; set; } | 条码检测器设置。 |
| [FastScanOnly](../../aspose.barcode.barcoderecognition/qualitysettings/fastscanonly) { get; set; } | 允许一维条码引擎快速识别图像的中间切片并返回结果，而无需使用任何耗时的算法。 |
| [MedianSmoothingWindowSize](../../aspose.barcode.barcoderecognition/qualitysettings/mediansmoothingwindowsize) { get; set; } | 中值平滑的窗口大小。典型值为 3 或 4。默认值为 3。必须设置 AllowMedianSmoothing。 |
| [ReadTinyBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/readtinybarcodes) { get; set; } | 允许引擎识别大图像上的小条形码。如果[`AllowIncorrectBarcodes`](./allowincorrectbarcodes)设置为 True，则忽略。默认值:假。 |
| [UseOldBarcodeDetector](../../aspose.barcode.barcoderecognition/qualitysettings/useoldbarcodedetector) { get; set; } | 切换到旧的条码检测器。 |

### 例子

此示例显示如何将 QualitySettings 与 BarCodeReader 一起使用

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
      //设置高性能模式
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
     //默认设置正常质量模式
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
     //设置低速识别的高质量模式
   reader.QualitySettings = QualitySettings.HighQuality;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //设置最大条形码模式，尝试找到所有可能的条形码，即使不正确。最慢的识别模式
   reader.QualitySettings = QualitySettings.MaxBarCodes;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
      //设置高性能模式
   reader.QualitySettings = QualitySettings.HighPerformance;
      //设置单独的options
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
     //默认模式是NormalQuality
      //设置单独的options
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    ' 设置高性能模式
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    ' 默认设置正常质量模式
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    ' 设置低速识别的高质量模式
    reader.QualitySettings = QualitySettings.HighQuality
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    ' 设置最大条形码模式，它会尝试找到所有可能的条形码，即使是不正确的。 最慢的识别模式
    reader.QualitySettings = QualitySettings.MaxBarCodes
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   ' 设置高性能模式
   reader.QualitySettings = QualitySettings.HighPerformance
   ' 设置单独的选项
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   ' 默认模式是 NormalQuality
   ' 设置单独的选项
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### 也可以看看

* 命名空间 [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition)
* 部件 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
