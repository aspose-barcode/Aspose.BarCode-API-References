---
title: "枚举"
linktitle: "XDimensionMode"
second_title: "Aspose.BarCode for C++ API 参考"
description: "如何在 C++ 中使用枚举。"
type: docs
weight: 4000
url: /zh/cpp/aspose.barcode.barcoderecognition/xdimensionmode/
---
## XDimensionMode enum




```cpp
enum class XDimensionMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| 自动 | 0 | XDimension 的值由 AI（SVM）检测。目前与 Normal 相同 |
| 小 | 1 | 检测 XDimension 较小（1 像素或以上）的条形码，质量来自 BarcodeQuality |
| Normal | 2 | 检测 XDimension 为经典（2 像素或以上）的条形码，质量来自 BarcodeQuality 或高质量条形码。 |
| 大 | 3 | 检测 XDimension 较大的条形码，质量来自使用高分辨率相机捕获的 BarcodeQuality。 |
| UseMinimalXDimension | 4 | 检测条形码，使用在 MinimalXDimension 中设置的尺寸以及来自 BarcodeQuality 的质量 |

## 备注


[Recognition](../../aspose.barcode.barcoderecognition.recognition/) mode which sets size (from 1 to infinity) of barcode minimal element: matrix cell or bar. 

此示例展示如何使用 XDimension 模式
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.XDimension = XDimensionMode.Small;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 另见

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
