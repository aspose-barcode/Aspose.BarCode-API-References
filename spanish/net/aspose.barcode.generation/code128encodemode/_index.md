---
title: "Enumeración Code128EncodeMode"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Enumeración Aspose.BarCode.Generation.Code128EncodeMode. Modo de codificación para códigos de barras Code128. Especificación Code 128"
type: docs
weight: 1120
url: /es/net/aspose.barcode.generation/code128encodemode/
---
## Code128EncodeMode enumeration

Modo de codificación para códigos de barras Code128. Especificación [Code 128](https://en.wikipedia.org/wiki/Code_128).

```csharp
public enum Code128EncodeMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | `0` | Codificar el texto del código en modo clásico ISO 15417. El modo debe usarse en todos los casos ordinarios. |
| CodeA | `1` | Codificar el texto del código solo en el conjunto de códigos 128A. |
| CodeB | `2` | Codificar el texto del código solo en el conjunto de códigos 128B. |
| CodeC | `4` | Codificar el texto del código solo en el conjunto de códigos 128C. |
| CodeAB | `3` | Codificar el texto del código solo en los conjuntos de códigos 128A y 128B. |
| CodeAC | `5` | Codificar el texto del código solo en los conjuntos de códigos 128A y 128C. |
| CodeBC | `6` | Codificar el texto del código solo en los conjuntos de códigos 128B y 128C. |

## Ejemplos

Este código demuestra cómo generar código 128 con diferentes codificaciones

```csharp
[C#]
//Generar código 128 con codificación ISO 15417
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.Auto;
generator.Save(@"d:\save\rec\code128Auto.png", BarCodeImageFormat.Png);

//Generar código 128 solo con codificación del conjunto de códigos A
BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "ABCD1234567890");
generator.Parameters.Barcode.Code128.Code128EncodeMode = Code128EncodeMode.CodeA;
generator.Save(@"d:\save\rec\code128CodeA.png", BarCodeImageFormat.Png);
```

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


