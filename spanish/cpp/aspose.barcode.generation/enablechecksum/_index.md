---
title: "enum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Cómo usar el enum en C++."
type: docs
weight: 6700
url: /es/cpp/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enum




```cpp
enum class EnableChecksum
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Predeterminado | 0 | Si se requiere el checksum según la especificación, se adjuntará. |
| Sí | 1 | Utilice siempre checksum si es posible. |
| No | 2 | No use checksum. |

## Observaciones


Habilite checksum durante la generación de códigos de barras 1D.

Predeterminado se trata como Sí para las simbologías que deben contener suma de verificación, y como No donde la suma de verificación solo es posible.

Checksum nunca usado: Codabar

Checksum es posible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Suma de verificación siempre usada: Resto de simbologías
## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
