---
title: "枚举"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode for C++ API 参考"
description: "如何在 C++ 中使用枚举。"
type: docs
weight: 3900
url: /zh/cpp/aspose.barcode.barcoderecognition/inverseimagemode/
---
## InverseImageMode enum




```cpp
enum class InverseImageMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | 0 | 禁用对反向图像的条形码额外识别，适用于除 [QR](../../aspose.barcode.barcoderecognition.qr/) 码之外的所有条码类型。 |
| 已禁用 | 1 | 禁用对反向图像的条形码额外识别。 |
| 已启用 | 2 | 启用对反向图像的条形码额外识别 |

## 备注


此模式启用或禁用对颜色反转（亮度）图像中条码的额外识别。

此示例展示如何使用 InverseImage 模式
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Extended, DecodeType.Code128))
{
    reader.QualitySettings.InverseImage = InverseImageMode.Enabled;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine(result.CodeText);
}
```

## 另见

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
