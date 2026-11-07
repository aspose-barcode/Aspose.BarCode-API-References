---
title: "Aspose::BarCode::Generation::BorderParameters класс"
linktitle: "BorderParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::Generation::BorderParameters класс. Параметры границы изображения штрих‑кода в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.barcode.generation/borderparameters/
---
## BorderParameters class


Параметры границы изображения штрихкода

```cpp
class BorderParameters : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_Color](./get_color/)() const | Цвет границы. Значение по умолчанию: Color.Black. |
| [get_DashStyle](./get_dashstyle/)() const | Стиль штриха границы. Значение по умолчанию: [BorderDashStyle.Solid](../borderdashstyle/). |
| [get_Visible](./get_visible/)() const | Видимость границы. Если false, то параметр Width всегда игнорируется (0). Значение по умолчанию: false. |
| [get_Width](./get_width/)() const | Ширина границы. Значение по умолчанию: 0. Игнорируется, если Visible установлено в false. |
| [set_Color](./set_color/)(System::Drawing::Color) | Цвет границы. Значение по умолчанию: Color.Black. |
| [set_DashStyle](./set_dashstyle/)(BorderDashStyle) | Стиль штриха границы. Значение по умолчанию: [BorderDashStyle.Solid](../borderdashstyle/). |
| [set_Visible](./set_visible/)(bool) | Видимость границы. Если false, то параметр Width всегда игнорируется (0). Значение по умолчанию: false. |
| [set_Width](./set_width/)(System::SharedPtr\<Unit\>) | Ширина границы. Значение по умолчанию: 0. Игнорируется, если Visible установлено в false. |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [BorderParameters](./). |
## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
