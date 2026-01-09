---
title: Aspose::BarCode::Generation::BorderParameters class
linktitle: BorderParameters
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::BorderParameters class. Barcode image border parameters in C++.'
type: docs
weight: 800
url: /cpp/aspose.barcode.generation/borderparameters/
---
## BorderParameters class


Barcode image border parameters

```cpp
class BorderParameters : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Color](./get_color/)() const | Border color. Default value: Color.Black. |
| [get_DashStyle](./get_dashstyle/)() const | Border dash style. Default value: [BorderDashStyle.Solid](../borderdashstyle/). |
| [get_Visible](./get_visible/)() const | Border visibility. If false than parameter Width is always ignored (0). Default value: false. |
| [get_Width](./get_width/)() const | Border width. Default value: 0. Ignored if Visible is set to false. |
| [set_Color](./set_color/)(System::Drawing::Color) | Border color. Default value: Color.Black. |
| [set_DashStyle](./set_dashstyle/)(BorderDashStyle) | Border dash style. Default value: [BorderDashStyle.Solid](../borderdashstyle/). |
| [set_Visible](./set_visible/)(bool) | Border visibility. If false than parameter Width is always ignored (0). Default value: false. |
| [set_Width](./set_width/)(System::SharedPtr\<Unit\>) | Border width. Default value: 0. Ignored if Visible is set to false. |
| [ToString](./tostring/)() const override | Returns a human-readable string representation of this [BorderParameters](./). |
## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
