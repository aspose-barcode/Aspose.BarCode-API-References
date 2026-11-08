---
title: "enum"
linktitle: "XDimensionMode"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "C++'da enum nasıl kullanılır?"
type: docs
weight: 4000
url: /tr/cpp/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enum




```cpp
enum class XDimensionMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Otomatik | 0 | XDimension değeri AI (SVM) tarafından tespit edilir. Şu anda Normal ile aynı |
| Small | 1 | BarcodeQuality kalitesinden 1 piksel veya daha fazla küçük XDimension'a sahip barkodları algılar |
| Normal | 2 | BarcodeQuality kalitesinden veya yüksek kalite barkodlardan 2 piksel veya daha fazla klasik XDimension'a sahip barkodları algılar. |
| Large | 3 | Yüksek çözünürlüklü kameralarla yakalanan BarcodeQuality kalitesinden büyük XDimension'a sahip barkodları algılar. |
| UseMinimalXDimension | 4 | MinimalXDimension içinde ayarlanan boyuttan barkodları BarcodeQuality kalitesiyle algılar |

## Açıklamalar


[Recognition](../../aspose.barcode.barcoderecognition.recognition/) mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. 

Bu örnek XDimension modunun nasıl kullanılacağını gösterir
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
