---
title: "constructor"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ API 参考"
description: "构造函数。初始化 LuminanceFrame 类的新实例，行之间没有填充。相邻行之间的距离等于宽度（C++）。"
type: docs
weight: 600
url: /zh/cpp/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) constructor


初始化 [LuminanceFrame](../) 类的新实例，行之间没有填充。相邻行之间的距离等于 *width*。

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rotationDegrees=0)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | 每像素包含一个字节的亮度数据。 |
| width | int32_t | 帧的宽度（像素）。 |
| height | int32_t | 帧的高度（像素）。 |
| rotationDegrees | int32_t | 显示帧正立所需的顺时针旋转角度。支持的值为 0、90、180 和 270。默认值为 0。 |

## 另见

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) constructor


使用指定的行跨度初始化 [LuminanceFrame](../) 类的新实例。

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rowStride, int32_t rotationDegrees)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | 每像素包含一个字节的亮度数据。 |
| width | int32_t | 帧的宽度（像素）。 |
| height | int32_t | 帧的高度（像素）。 |
| rowStride | int32_t | 两个相邻行起始位置之间的字节距离。该值不能小于 *width* 。 |
| rotationDegrees | int32_t | 显示帧时所需的顺时针旋转角度。支持的值为 0、90、180 和 270。 |

## 另见

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
