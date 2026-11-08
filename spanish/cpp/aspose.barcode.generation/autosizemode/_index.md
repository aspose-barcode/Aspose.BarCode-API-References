---
title: "enum"
linktitle: "AutoSizeMode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " enum. Especifica los diferentes tipos de modos de dimensionado automático en C++."
type: docs
weight: 5200
url: /es/cpp/aspose.barcode.generation/autosizemode/
---
## AutoSizeMode enum


Especifica los diferentes tipos de modos de dimensionado automático.

```cpp
enum class AutoSizeMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Ninguno | 0 | El dimensionado automático está deshabilitado. |
| Nearest | 1 | Redimensiona el código de barras al tamaño más bajo posible más cercano especificado por las propiedades ImageWidth y ImageHeight. Preserva la relación de aspecto predeterminada. |
| Interpolación | 2 | Redimensiona el código de barras al tamaño especificado. El tamaño puede especificarse mediante las propiedades ImageWidth e ImageHeight. El código de barras generado puede ser inválido (no legible) después del escalado. |

## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
