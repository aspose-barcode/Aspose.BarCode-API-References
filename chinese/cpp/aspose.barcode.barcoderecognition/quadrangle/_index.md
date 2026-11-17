---
title: "Aspose::BarCode::BarCodeRecognition::Quadrangle 类"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::BarCodeRecognition::Quadrangle 类。存储一组四个 Points，表示 C++ 中的 Quadrangle 区域。"
type: docs
weight: 3000
url: /zh/cpp/aspose.barcode.barcoderecognition/quadrangle/
---
## Quadrangle class


存储一组四个 [Point](../)s，表示一个 [Quadrangle](./) 区域。

```cpp
class Quadrangle : public System::IEquatable<System::SharedPtr<Quadrangle>>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [Contains](./contains/)(System::Drawing::Point) | 确定指定的 [Point](../) 是否包含在此 [Quadrangle](./) 类中。 |
| [Contains](./contains/)(int32_t, int32_t) | 确定指定的点是否包含在此 [Quadrangle](./) 类中。 |
| [Contains](./contains/)(System::SharedPtr\<Quadrangle\>) | 确定指定的 [Quadrangle](./) 是否被包含或与此 [Quadrangle](./) 类相交。 |
| [Contains](./contains/)(System::Drawing::Rectangle) | 确定指定的 [Rectangle](../) 是否被包含或与此 [Quadrangle](./) 类相交。 |
| [Equals](./equals/)(System::SharedPtr\<Quadrangle\>) override | 返回一个值，指示此实例是否等于指定的 [Quadrangle](./) 值。 |
| [get_BoundingRectangle](./get_boundingrectangle/)() | 获取界定此 [Quadrangle](./) 的 [Rectangle](../)。 |
| [get_IsEmpty](./get_isempty/)() | **测试** 此 [Quadrangle](./) 的所有 [Point](../) 是否为零值。 |
| [get_LeftBottom](./get_leftbottom/)() const | 获取 [Quadrangle](./) 区域的左下角 [Point](../)。 |
| [get_LeftTop](./get_lefttop/)() const | 获取 [Quadrangle](./) 区域的左上角 [Point](../)。 |
| [get_RightBottom](./get_rightbottom/)() const | 获取 [Quadrangle](./) 区域的右下角 [Point](../)。 |
| [get_RightTop](./get_righttop/)() const | 获取 [Quadrangle](./) 区域的右上角 [Point](../)。 |
| [GetHashCode](./gethashcode/)() const override | 返回此实例的哈希码。 |
| [Quadrangle](./quadrangle/)() | 初始化一个新的空的 [Quadrangle](./) 类实例。 |
| [Quadrangle](./quadrangle/)(System::Drawing::Point, System::Drawing::Point, System::Drawing::Point, System::Drawing::Point) | 使用描述点初始化一个新的 [Quadrangle](./) 类实例。 |
| [set_LeftBottom](./set_leftbottom/)(System::Drawing::Point) | 获取 [Quadrangle](./) 区域的左下角 [Point](../)。 |
| [set_LeftTop](./set_lefttop/)(System::Drawing::Point) | 获取 [Quadrangle](./) 区域的左上角 [Point](../)。 |
| [set_RightBottom](./set_rightbottom/)(System::Drawing::Point) | 获取 [Quadrangle](./) 区域的右下角 [Point](../)。 |
| [set_RightTop](./set_righttop/)(System::Drawing::Point) | 获取 [Quadrangle](./) 区域的右上角 [Point](../)。 |
| [ToString](./tostring/)() const override | 返回此 [Quadrangle](./) 的人类可读字符串表示。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| static [Empty](./empty/) | 表示一个其属性未初始化的 [Quadrangle](./) 类。 |
## 另见

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
