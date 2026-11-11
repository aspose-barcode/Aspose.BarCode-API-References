---
title: "Enum XDimensionMode"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.BarCodeRecognition.XDimensionMode enum. Barkodun minimum öğe matris hücresi veya çubuğu için boyutu 1'den sonsuza kadar ayarlayan tanıma modu"
type: docs
weight: 400
url: /tr/net/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enumeration

Barkodun en küçük öğesinin (matris hücresi veya çubuk) boyutunu (1'den sonsuza) belirleyen tanıma modu.

```csharp
public enum XDimensionMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Auto | `0` | XDimension değeri AI (SVM) tarafından algılanır. Şu anda Normal ile aynı |
| Small | `1` | BarcodeQuality kalitesine sahip, 1 piksel veya daha fazla küçük XDimension içeren barkodları algılar |
| Normal | `2` | BarcodeQuality kalitesine veya yüksek kalite barkodlara sahip, 2 piksel veya daha fazla klasik XDimension içeren barkodları algılar. |
| Large | `3` | Yüksek çözünürlüklü kameralarla yakalanan, BarcodeQuality kalitesine sahip büyük XDimension içeren barkodları algılar. |
| UseMinimalXDimension | `4` | MinimalXDimension içinde ayarlanan boyuttan, BarcodeQuality kalitesine sahip barkodları algılar |

## Örnekler

Bu örnek, XDimension modunun nasıl kullanılacağını gösterir

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


