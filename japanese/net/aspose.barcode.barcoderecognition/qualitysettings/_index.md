---
title: QualitySettings
second_title: Aspose.BarCode for.NETAPIリファレンス
description: QualitySettings を使用すると認識の品質と速度を手動で構成できます 組み込みのプリセット HighPerformanceNormalQuality HighQualityMaxBarCodes によって QualitySettings をすばやくセットアップできますまたは個別のオプションを手動で構成することもできます QualitySettings のデフォルト値は NormalQuality です
type: docs
weight: 270
url: /ja/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings を使用すると、認識の品質と速度を手動で構成できます。 組み込みのプリセット (HighPerformance、NormalQuality、 HighQuality、MaxBarCodes) によって QualitySettings をすばやくセットアップできます。または、個別のオプションを手動で構成することもできます。 QualitySettings のデフォルト値は NormalQuality です。

```csharp
public sealed class QualitySettings
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance/) { get; } | 高性能認識品質のプリセット。このモードでは、高品質のバーコードがよく認識されます。 |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality/) { get; } | 高品質認識品質プリセット。このプリセットは、低品質のバーコード用に開発されています. 斜めのバーコードや損傷の激しいバーコードを検出できます. |
| static [HighQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/highqualitydetection/) { get; } | HighQualityDetection 認識品質プリセット。 NormalQuality と同じですが、高品質です[`DetectorSettings`](./detectorsettings/) |
| static [MaxBarCodes](../../aspose.barcode.barcoderecognition/qualitysettings/maxbarcodes/) { get; } | MaxBarCodes 認識品質プリセット。このプリセットは、間違ったバーコードであっても、考えられるすべてのバーコードを認識するように開発されています. |
| static [MaxQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/maxqualitydetection/) { get; } | MaxQualityDetection 認識品質プリセット。 NormalQuality と同じですが、最高品質です[`DetectorSettings`](./detectorsettings/). 斜めのバーコードや破損したバーコードを検出できます. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality/) { get; } | NormalQuality 認識品質プリセット。ほとんどのバーコード に適しています |
| [AllowComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/allowcomplexbackground/) { get; set; } | エンジンがカラー背景のカラー バーコードを追加スキャンとして認識できるようにします。非常に遅いモード. |
| [AllowDatamatrixIndustrialBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowdatamatrixindustrialbarcodes/) { get; set; } | Datamatrix のエンジンが破線の工業用 Datamatrix バーコードを認識できるようにします。 スポットから構成される破線のバーコードにのみ役立つ低速モード。 |
| [AllowDecreasedImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowdecreasedimage/) { get; set; } | エンジンが減少した画像を追加スキャンとして認識できるようにします。縮小するサイズは、内部エンジン アルゴリズムによって選択されます。 モードは、ノイズが多くぼやけているが、高解像度でキャプチャされたバーコードを認識するのに役立ちます. |
| [AllowDetectScanGap](../../aspose.barcode.barcoderecognition/qualitysettings/allowdetectscangap/) { get; set; } | エンジンがスキャン間のギャップを使用して認識速度を向上できるようにします。モードでは、バーコードの高さが低いと認識の問題が発生する可能性があります. |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes/) { get; set; } | 不正確なチェックサムまたは不正確な値を持つバーコードをエンジンが認識できるようにします。 モードは、破損したバーコードを正しくないテキストで認識するために使用できます。 |
| [AllowInvertImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowinvertimage/) { get; set; } | エンジンが反転カラー画像を追加スキャンとして認識できるようにします。バーコードが黒地に白の場合に使用できるモードです。 |
| [AllowMedianSmoothing](../../aspose.barcode.barcoderecognition/qualitysettings/allowmediansmoothing/) { get; set; } | エンジンが追加スキャンとして中央値平滑化を有効にできるようにします。モードは、ノイズのあるバーコードの認識に役立ちます。 |
| [AllowMicroWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowmicrowhitespotsremoving/) { get; set; } | 郵便バーコードのエンジンがわずかにノイズのある画像を認識できるようにします。モードは、わずかに破損した郵便バーコードを認識するのに役立ちます. |
| [AllowOneDFastBarcodesDetector](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedfastbarcodesdetector/) { get; set; } | 1D バーコードのエンジンが、画像のほぼ全体を占める高品質のバーコードをすばやく認識できるようにします。 モードは、インターネットから生成されたバーコードをすばやく認識するのに役立ちます. |
| [AllowOneDWipedBarsRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedwipedbarsrestoration/) { get; set; } | 1D バーコード用のエンジンが、単一のワイプ/接着バーをパターンで含むバーコードを認識できるようにします。 |
| [AllowQRMicroQrRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowqrmicroqrrestoration/) { get; set; } | QR/MicroQR のエンジンが破損した MicroQR バーコードを認識できるようにします。 |
| [AllowRegularImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowregularimage/) { get; set; } | エンジンが復元なしの通常のイメージをメイン スキャンとして認識できるようにします。画像をそのまま認識するモード. |
| [AllowSaltAndPaperFiltering](../../aspose.barcode.barcoderecognition/qualitysettings/allowsaltandpaperfiltering/) { get; set; } | エンジンがソルトおよびペーパー ノイズ タイプのバーコードを認識できるようにします。モードでは、白と黒のドットで小さなノイズを除去できます. |
| [AllowWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowwhitespotsremoving/) { get; set; } | エンジンが小さな白い斑点のない画像を追加スキャンとして認識できるようにします。モードは、ノイズのある画像と中央平滑化フィルタリングを認識するのに役立ちます. |
| [CheckMore1DVariants](../../aspose.barcode.barcoderecognition/qualitysettings/checkmore1dvariants/) { get; set; } | より多くの認識バリアントをチェックすることにより、エンジンがチェックサム付きの 1D バーコードを認識できるようにします。デフォルト値: False. |
| [DetectorSettings](../../aspose.barcode.barcoderecognition/qualitysettings/detectorsettings/) { get; set; } | バーコード検出器の設定. |
| [FastScanOnly](../../aspose.barcode.barcoderecognition/qualitysettings/fastscanonly/) { get; set; } | 時間のかかるアルゴリズムを使用せずに、1D バーコードのエンジンが画像の中央のスライスをすばやく認識し、結果を返すことができるようにします。 |
| [MedianSmoothingWindowSize](../../aspose.barcode.barcoderecognition/qualitysettings/mediansmoothingwindowsize/) { get; set; } | 中央値平滑化のウィンドウ サイズ。一般的な値は 3 または 4 です。デフォルト値は 3 です。AllowMedianSmoothing を設定する必要があります。 |
| [ReadTinyBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/readtinybarcodes/) { get; set; } | エンジンが大きな画像の小さなバーコードを認識できるようにします。次の場合は無視されます[`AllowIncorrectBarcodes`](./allowincorrectbarcodes/)真に設定されています。デフォルト値: False. |
| [UseOldBarcodeDetector](../../aspose.barcode.barcoderecognition/qualitysettings/useoldbarcodedetector/) { get; set; } | 古いバーコード検出器に切り替えます。 |

### 例

このサンプルは、BarCodeReader で QualitySettings を使用する方法を示しています。

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //ハイパフォーマンスモードを設定
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //デフォルトでは通常の品質モードが設定されています
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //低速認識で高品質モードを設定 
   reader.QualitySettings = QualitySettings.HighQuality;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // 最大バーコード モードを設定します。これは、すべての可能なバーコードを見つけようとしますが、正しくない場合もあります。最も遅い認識モード
   reader.QualitySettings = QualitySettings.MaxBarCodes;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //ハイパフォーマンスモードを設定
   reader.QualitySettings = QualitySettings.HighPerformance;
   //個別のオプションを設定
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   //デフォルト モードは NormalQuality です
   //個別のオプションを設定
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'ハイパフォーマンスモードを設定
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    '通常の品質モードはデフォルトで設定されています
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    '低速認識で高品質モードを設定する
    reader.QualitySettings = QualitySettings.HighQuality
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'すべての可能なバーコードを見つけようとする最大バーコード モードを設定します。最も遅い認識モード
    reader.QualitySettings = QualitySettings.MaxBarCodes
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'ハイパフォーマンスモードを設定
   reader.QualitySettings = QualitySettings.HighPerformance
   '別のオプションを設定する
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'デフォルトモードはNormalQualityです
   '別のオプションを設定する
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### 関連項目

* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* 組み立て [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
