---
title: "LuminanceFrame.LuminanceFrame"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "LuminanceFrame 构造函数。初始化 LuminanceFrame 类的新实例，行之间没有填充。相邻行之间的距离等于 width"
type: docs
weight: 10
url: /zh/net/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame(byte[], int, int, int) {#constructor}

初始化 [`LuminanceFrame`](../) 类的新实例，行之间没有填充。相邻行之间的距离等于 *width*。

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rotationDegrees = 0)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | Byte[] | 包含每像素一个字节的亮度数据。 |
| width | Int32 | 帧的宽度（像素）。 |
| height | Int32 | 帧的高度（像素）。 |
| rotationDegrees | Int32 | 显示帧正立所需的顺时针旋转。支持的值为 0、90、180 和 270。默认值为 0。 |

### 另见

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## LuminanceFrame(byte[], int, int, int, int) {#constructor_1}

使用指定的 row stride 初始化 [`LuminanceFrame`](../) 类的新实例。

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rowStride, int rotationDegrees)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| data | Byte[] | 包含每像素一个字节的亮度数据。 |
| width | Int32 | 帧的宽度（像素）。 |
| height | Int32 | 帧的高度（像素）。 |
| rowStride | Int32 | 相邻两行起始位置之间的字节距离。该值不能小于 *width*。 |
| rotationDegrees | Int32 | 显示帧正立所需的顺时针旋转角度。支持的值为 0、90、180 和 270。 |

### 另见

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


