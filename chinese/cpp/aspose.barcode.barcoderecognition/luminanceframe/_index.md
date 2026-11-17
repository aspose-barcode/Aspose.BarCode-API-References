---
title: "Aspose::BarCode::BarCodeRecognition::LuminanceFrame 类"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::LuminanceFrame 类。表示一个 8 位灰度图像帧。每个像素由一个字节表示，包含其在 C++ 中的亮度值。"
type: docs
weight: 2400
url: /zh/cpp/aspose.barcode.barcoderecognition/luminanceframe/
---
## LuminanceFrame class


表示一个 8 位灰度图像帧。每个像素由包含其亮度值的一个字节表示。

```cpp
class LuminanceFrame : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Data](./get_data/)() const | 获取亮度数据。 |
| [get_Height](./get_height/)() const | 获取帧的像素高度。 |
| [get_RotationDegrees](./get_rotationdegrees/)() const | 获取帧必须顺时针旋转的角度数，以获得正确的方向。 |
| [get_RowStride](./get_rowstride/)() const | 获取相邻两行起始位置之间的字节距离。 |
| [get_Width](./get_width/)() const | 获取帧的像素宽度。 |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) | 初始化一个没有行间填充的 [LuminanceFrame](./) 类的新实例。相邻行之间的距离等于 *width* 。 |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) | 使用指定的行跨距初始化 [LuminanceFrame](./) 类的新实例。 |
## 另见

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
