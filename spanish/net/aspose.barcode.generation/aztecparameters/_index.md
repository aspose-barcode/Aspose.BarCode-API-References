---
title: "Clase AztecParameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Generation.AztecParameters. Parámetros Aztec"
type: docs
weight: 960
url: /es/net/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class

Parámetros de Aztec.

```csharp
public class AztecParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/aztecparameters/aspectratio/) { get; set; } | Relación altura/ancho del módulo de código de barras 2D. |
| [ECIEncoding](../../aspose.barcode.generation/aztecparameters/eciencoding/) { get; set; } | Obtiene o establece la codificación ECI. Se usa cuando AztecEncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.generation/aztecparameters/encodemode/) { get; set; } | Obtiene o establece un modo de codificación Aztec. Valor predeterminado: Auto. |
| [ErrorLevel](../../aspose.barcode.generation/aztecparameters/errorlevel/) { get; set; } | Nivel de corrección de errores de los tipos de código de barras Aztec. El valor debe estar entre 5 y 95. |
| [IsReaderInitialization](../../aspose.barcode.generation/aztecparameters/isreaderinitialization/) { get; set; } | Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo como programación para la inicialización del lector. |
| [LayersCount](../../aspose.barcode.generation/aztecparameters/layerscount/) { get; set; } | Obtiene o establece la cantidad de capas del símbolo Aztec. La cantidad de capas debe estar en el rango de 1 a 3 para el modo Compact y en el rango de 1 a 32 para el modo Full Range. Valor predeterminado: 0 (auto). |
| [StructuredAppendBarcodeId](../../aspose.barcode.generation/aztecparameters/structuredappendbarcodeid/) { get; set; } | Identificador de código de barras para el modo Structured Append del código de barras Aztec. El identificador debe estar en el rango de 1 al número de códigos de barras. Valor predeterminado: 0 |
| [StructuredAppendBarcodesCount](../../aspose.barcode.generation/aztecparameters/structuredappendbarcodescount/) { get; set; } | Recuento de códigos de barras para el modo Structured Append del código Aztec. El recuento de códigos de barras debe estar en el rango de 1 a 26. Valor predeterminado: 0 |
| [StructuredAppendFileId](../../aspose.barcode.generation/aztecparameters/structuredappendfileid/) { get; set; } | ID de archivo para el modo Structured Append del código Aztec (campo opcional). El ID de archivo no debe contener espacios. Valor predeterminado: cadena vacía |
| [SymbolMode](../../aspose.barcode.generation/aztecparameters/symbolmode/) { get; set; } | Obtiene o establece un modo de símbolo Aztec. Valor predeterminado: AztecSymbolMode.Auto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/aztecparameters/tostring/)() | Devuelve una representación de cadena legible por humanos de este `AztecParameters`. |

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


