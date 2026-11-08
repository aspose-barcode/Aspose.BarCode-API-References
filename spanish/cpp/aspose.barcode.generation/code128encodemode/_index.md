---
title: "enum"
linktitle: "Code128EncodeMode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " enum. Modo de codificación para códigos de barras Code128. Especificación Code 128 en C++."
type: docs
weight: 5900
url: /es/cpp/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enum


Modo de codificación para códigos de barras Code128. Code 128

especificación.

```cpp
enum class Code128EncodeMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Automático | 0 | Codifique el texto del código en modo clásico ISO 15417. El modo debe usarse en todos los casos ordinarios. |
| CodeA | 1 | Codifique el texto del código solo en el conjunto de códigos 128A. |
| CodeB | 2 | Codifique el texto del código solo en el conjunto de códigos 128B. |
| CodeC | 4 | Codifique el texto del código solo en el conjunto de códigos 128C. |
| CodeAB | 3 | Codifique el texto del código solo en los conjuntos de códigos 128A y 128B. |
| CodeAC | 5 | Codifique el texto del código solo en los conjuntos de códigos 128A y 128C. |
| CodeBC | 6 | Codifique el texto del código solo en los conjuntos de códigos 128B y 128C. |

## Observaciones


Este código demuestra cómo generar código 128 con diferentes codificaciones
```cpp
[C#]
//Generar código 128 con codificación ISO 15417
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Generar código 128 solo con la codificación Codeset A
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

## Ver también

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
