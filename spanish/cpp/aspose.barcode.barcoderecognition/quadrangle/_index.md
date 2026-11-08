---
title: "Aspose::BarCode::BarCodeRecognition::Quadrangle clase"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::BarCodeRecognition::Quadrangle clase. Almacena un conjunto de cuatro Points que representan una región Quadrangle en C++."
type: docs
weight: 3000
url: /es/cpp/aspose.barcode.barcoderecognition/quadrangle/
---
## Quadrangle class


Almacena un conjunto de cuatro [Point](../)s que representan una región [Quadrangle](./).

```cpp
class Quadrangle : public System::IEquatable<System::SharedPtr<Quadrangle>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Contains](./contains/)(System::Drawing::Point) | Determina si el [Point](../) especificado está contenido dentro de esta clase [Quadrangle](./). |
| [Contains](./contains/)(int32_t, int32_t) | Determina si el punto especificado está contenido dentro de esta clase [Quadrangle](./). |
| [Contains](./contains/)(System::SharedPtr\<Quadrangle\>) | Determina si el [Quadrangle](./) especificado está contenido o intersecta esta clase [Quadrangle](./). |
| [Contains](./contains/)(System::Drawing::Rectangle) | Determina si el [Rectangle](../) especificado está contenido o intersecta esta clase [Quadrangle](./). |
| [Equals](./equals/)(System::SharedPtr\<Quadrangle\>) override | Devuelve un valor que indica si esta instancia es igual a un valor [Quadrangle](./) especificado. |
| [get_BoundingRectangle](./get_boundingrectangle/)() | Obtiene el [Rectangle](../) que delimita este [Quadrangle](./) |
| [get_IsEmpty](./get_isempty/)() | **Tests** si todos los [Point](../)s de este [Quadrangle](./) tienen valores cero. |
| [get_LeftBottom](./get_leftbottom/)() const | Obtiene el punto de la esquina inferior izquierda [Point](../) de la región [Quadrangle](./) |
| [get_LeftTop](./get_lefttop/)() const | Obtiene el punto de la esquina superior izquierda [Point](../) de la región [Quadrangle](./) |
| [get_RightBottom](./get_rightbottom/)() const | Obtiene el punto de la esquina inferior derecha [Point](../) de la región [Quadrangle](./) |
| [get_RightTop](./get_righttop/)() const | Obtiene el punto de la esquina superior derecha [Point](../) de la región [Quadrangle](./) |
| [GetHashCode](./gethashcode/)() const override | Devuelve el código hash de esta instancia. |
| [Quadrangle](./quadrangle/)() | Inicializa una nueva instancia vacía de la clase [Quadrangle](./). |
| [Quadrangle](./quadrangle/)(System::Drawing::Point, System::Drawing::Point, System::Drawing::Point, System::Drawing::Point) | Inicializa una nueva instancia de la clase [Quadrangle](./) con los puntos descriptivos. |
| [set_LeftBottom](./set_leftbottom/)(System::Drawing::Point) | Obtiene el punto de la esquina inferior izquierda [Point](../) de la región [Quadrangle](./) |
| [set_LeftTop](./set_lefttop/)(System::Drawing::Point) | Obtiene el punto de la esquina superior izquierda [Point](../) de la región [Quadrangle](./) |
| [set_RightBottom](./set_rightbottom/)(System::Drawing::Point) | Obtiene el punto de la esquina inferior derecha [Point](../) de la región [Quadrangle](./) |
| [set_RightTop](./set_righttop/)(System::Drawing::Point) | Obtiene el punto de la esquina superior derecha [Point](../) de la región [Quadrangle](./) |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [Quadrangle](./). |
## Campos

| Campo | Descripción |
| --- | --- |
| static [Empty](./empty/) | Representa una clase [Quadrangle](./) con sus propiedades sin inicializar. |
## Ver también

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
