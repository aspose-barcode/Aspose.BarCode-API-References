---
title: QualitySettings
second_title: Aspose.BarCode for.NETAPIリファレンス
description: QualitySettings を使用すると認識の品質と速度を手動で構成できます 組み込みのプリセット HighPerformanceNormalQuality HighQualityMaxBarCodes によって QualitySettings をすばやくセットアップできますまたは個別のオプションを手動で構成することもできます QualitySettings のデフォルト値は NormalQuality です
type: docs
weight: 60
url: /ja/net/aspose.barcode.barcoderecognition/barcodereader/qualitysettings/
---
## BarCodeReader.QualitySettings property

QualitySettings を使用すると、認識の品質と速度を手動で構成できます。 組み込みのプリセット (HighPerformance、NormalQuality、 HighQuality、MaxBarCodes) によって QualitySettings をすばやくセットアップできます。または、個別のオプションを手動で構成することもできます。 QualitySettings のデフォルト値は NormalQuality です。

```csharp
public QualitySettings QualitySettings { get; set; }
```

### プロパティ値

認識品質と速度を構成する QualitySettings.

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
   //ハイパフォーマンスモードを設定
   reader.QualitySettings = QualitySettings.HighPerformance;
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
   'ハイパフォーマンスモードを設定
   reader.QualitySettings = QualitySettings.HighPerformance
   '別のオプションを設定する
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### 関連項目

* class [QualitySettings](../../qualitysettings/)
* class [BarCodeReader](../)
* 名前空間 [Aspose.BarCode.BarCodeRecognition](../../barcodereader/)
* 組み立て [Aspose.BarCode](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
