---
title: "Aspose::BarCode::Generation::BorderParameters clase"
linktitle: "BorderParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::Generation::BorderParameters clase. Parámetros del borde de la imagen de código de barras en C++."
type: docs
weight: 800
url: /es/cpp/aspose.barcode.generation/borderparameters/
---
## BorderParameters class


Parámetros del borde de la imagen del código de barras

```cpp
class BorderParameters : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Color](./get_color/)() const | Color del borde. Valor predeterminado: Color.Black. |
| [get_DashStyle](./get_dashstyle/)() const | Estilo de guión del borde. Valor predeterminado: [BorderDashStyle.Solid](../borderdashstyle/). |
| [get_Visible](./get_visible/)() const | Visibilidad del borde. Si es false, entonces el parámetro Width siempre se ignora (0). Valor predeterminado: false. |
| [get_Width](./get_width/)() const | Ancho del borde. Valor predeterminado: 0. Ignorado si Visible se establece en false. |
| [set_Color](./set_color/)(System::Drawing::Color) | Color del borde. Valor predeterminado: Color.Black. |
| [set_DashStyle](./set_dashstyle/)(BorderDashStyle) | Estilo de guión del borde. Valor predeterminado: [BorderDashStyle.Solid](../borderdashstyle/). |
| [set_Visible](./set_visible/)(bool) | Visibilidad del borde. Si es false, entonces el parámetro Width siempre se ignora (0). Valor predeterminado: false. |
| [set_Width](./set_width/)(System::SharedPtr\<Unit\>) | Ancho del borde. Valor predeterminado: 0. Ignorado si Visible se establece en false. |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [BorderParameters](./). |
## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
