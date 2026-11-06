---
title: "Aspose::BarCode::Generation::BorderParameters class"
linktitle: "BorderParameters"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Generation::BorderParameters class. C++ 中的条形码图像边框参数。"
type: docs
weight: 800
url: /zh/cpp/aspose.barcode.generation/borderparameters/
---
## BorderParameters class


条形码图像边框参数

```cpp
class BorderParameters : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Color](./get_color/)() const | 边框颜色。默认值：Color.Black。 |
| [get_DashStyle](./get_dashstyle/)() const | 边框虚线样式。默认值：[BorderDashStyle.Solid](../borderdashstyle/)。 |
| [get_Visible](./get_visible/)() const | 边框可见性。如果为 false，则参数 Width 始终被忽略 (0)。默认值：false。 |
| [get_Width](./get_width/)() const | 边框宽度。默认值：0。如果 Visible 设置为 false，则被忽略。 |
| [set_Color](./set_color/)(System::Drawing::Color) | 边框颜色。默认值：Color.Black。 |
| [set_DashStyle](./set_dashstyle/)(BorderDashStyle) | 边框虚线样式。默认值：[BorderDashStyle.Solid](../borderdashstyle/)。 |
| [set_Visible](./set_visible/)(bool) | 边框可见性。如果为 false，则参数 Width 始终被忽略 (0)。默认值：false。 |
| [set_Width](./set_width/)(System::SharedPtr\<Unit\>) | 边框宽度。默认值：0。如果 Visible 设置为 false，则被忽略。 |
| [ToString](./tostring/)() const override | 返回此 [BorderParameters](./) 的人类可读字符串表示。 |
## 另见

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
