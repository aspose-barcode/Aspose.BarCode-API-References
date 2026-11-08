---
title: "Aspose::BarCode::Generation::ITFParameters class"
linktitle: "ITFParameters"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Aspose::BarCode::Generation::ITFParameters class. Parámetros ITF en C++."
type: docs
weight: 3300
url: /es/cpp/aspose.barcode.generation/itfparameters/
---
## ITFParameters class


Parámetros de ITF.

```cpp
class ITFParameters : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_BorderThickness](./get_borderthickness/)() const | Obtiene el grosor de un borde ITF (barra portadora) en unidades [Unit](../unit/). Valor predeterminado: 12pt. |
| [get_BorderType](./get_bordertype/)() const | Tipo de borde del código de barras ITF. Valor predeterminado: [ITF14BorderType.Bar](../itf14bordertype/). |
| [get_QuietZoneCoef](./get_quietzonecoef/)() const | Tamaño de las zonas silenciosas en xDimension. Valor predeterminado: 10, lo que significa que si xDimension = 2px, las zonas silenciosas serán 20px. |
| [set_BorderThickness](./set_borderthickness/)(System::SharedPtr\<Unit\>) | Establece un grosor del borde ITF (barra portadora) en valor de [Unit](../unit/) . Valor predeterminado: 12pt. |
| [set_BorderType](./set_bordertype/)(ITF14BorderType) | Tipo de borde del código de barras ITF. Valor predeterminado: [ITF14BorderType.Bar](../itf14bordertype/). |
| [set_QuietZoneCoef](./set_quietzonecoef/)(int32_t) | Tamaño de las zonas silenciosas en xDimension. Valor predeterminado: 10, lo que significa que si xDimension = 2px, las zonas silenciosas serán 20px. |
| [ToString](./tostring/)() const override | Devuelve una representación de cadena legible por humanos de este [ITFParameters](./). |
## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
