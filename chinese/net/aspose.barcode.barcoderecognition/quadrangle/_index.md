---
title: "类 Quadrangle"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.BarCodeRecognition.Quadrangle 类。存储一组表示 Quadrangle 区域的四个点"
type: docs
weight: 360
url: /zh/net/aspose.barcode.barcoderecognition/quadrangle/
---
## Quadrangle class

存储一组表示 `Quadrangle` 区域的四个点。

```csharp
public class Quadrangle : IEquatable<Quadrangle>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Quadrangle](quadrangle/#constructor)() | 初始化 `Quadrangle` 类的一个新的空实例。 |
| [Quadrangle](quadrangle/#constructor_1)(Point, Point, Point, Point) | 使用描述点初始化 `Quadrangle` 类的一个新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BoundingRectangle](../../aspose.barcode.barcoderecognition/quadrangle/boundingrectangle/) { get; } | 获取包围此 `Quadrangle` 的矩形 |
| [IsEmpty](../../aspose.barcode.barcoderecognition/quadrangle/isempty/) { get; } | 测试此 `Quadrangle` 的所有点是否全部为零值。 |
| [LeftBottom](../../aspose.barcode.barcoderecognition/quadrangle/leftbottom/) { get; set; } | 获取 `Quadrangle` 区域的左下角点 |
| [LeftTop](../../aspose.barcode.barcoderecognition/quadrangle/lefttop/) { get; set; } | 获取 `Quadrangle` 区域的左上角点 |
| [RightBottom](../../aspose.barcode.barcoderecognition/quadrangle/rightbottom/) { get; set; } | 获取 `Quadrangle` 区域的右下角点 |
| [RightTop](../../aspose.barcode.barcoderecognition/quadrangle/righttop/) { get; set; } | 获取 `Quadrangle` 区域的右上角点 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Contains](../../aspose.barcode.barcoderecognition/quadrangle/contains/#contains_2)(Point) | 确定指定的点是否位于此 `Quadrangle` 类中。 |
| [Contains](../../aspose.barcode.barcoderecognition/quadrangle/contains/#contains)(Quadrangle) | 确定指定的 `Quadrangle` 是否包含或与此 `Quadrangle` 类相交。 |
| [Contains](../../aspose.barcode.barcoderecognition/quadrangle/contains/#contains_3)(Rectangle) | 确定指定的矩形是否包含或与此 `Quadrangle` 类相交。 |
| [Contains](../../aspose.barcode.barcoderecognition/quadrangle/contains/#contains_1)(int, int) | 确定指定的点是否位于此 `Quadrangle` 类中。 |
| override [Equals](../../aspose.barcode.barcoderecognition/quadrangle/equals/#equals_1)(object) | 返回一个值，指示此实例是否等于指定的 `Quadrangle` 值。 |
| [Equals](../../aspose.barcode.barcoderecognition/quadrangle/equals/#equals)(Quadrangle) | 返回一个值，指示此实例是否等于指定的 `Quadrangle` 值。 |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/quadrangle/gethashcode/)() | 返回此实例的哈希码。 |
| override [ToString](../../aspose.barcode.barcoderecognition/quadrangle/tostring/)() | 返回此 `Quadrangle` 的可读字符串表示。 |
| [operator ==](../../aspose.barcode.barcoderecognition/quadrangle/op_equality/) | 返回一个值，指示第一个 `Quadrangle` 值是否等于第二个。 |
| [operator !=](../../aspose.barcode.barcoderecognition/quadrangle/op_inequality/) | 返回一个值，指示第一个 `Quadrangle` 值是否不同于第二个。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [Empty](../../aspose.barcode.barcoderecognition/quadrangle/empty/) | 表示一个 `Quadrangle` 类，其属性保持未初始化。 |

### 另见

* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


