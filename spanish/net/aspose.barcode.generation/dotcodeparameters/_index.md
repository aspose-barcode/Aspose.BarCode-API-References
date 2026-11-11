---
title: "Clase DotCodeParameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Clase Aspose.BarCode.Generation.DotCodeParameters. Parámetros DotCode"
type: docs
weight: 1260
url: /es/net/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class

Parámetros de DotCode.

```csharp
public class DotCodeParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/dotcodeparameters/aspectratio/) { get; set; } | Relación altura/ancho del módulo de código de barras 2D. |
| [Columns](../../aspose.barcode.generation/dotcodeparameters/columns/) { get; set; } | Identifica el recuento de columnas. La suma del número de filas más el número de columnas de un símbolo DotCode debe ser impar. El número de columnas debe ser al menos 5. Valor predeterminado: -1 |
| [ECIEncoding](../../aspose.barcode.generation/dotcodeparameters/eciencoding/) { get; set; } | Identifica la codificación ECI. Se usa cuando DotCodeEncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.generation/dotcodeparameters/encodemode/) { get; set; } | Identifica el modo de codificación DotCode. Valor predeterminado: Auto. |
| [IsReaderInitialization](../../aspose.barcode.generation/dotcodeparameters/isreaderinitialization/) { get; set; } | Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras. El valor predeterminado es false. |
| [Rows](../../aspose.barcode.generation/dotcodeparameters/rows/) { get; set; } | Identifica el recuento de filas. La suma del número de filas más el número de columnas de un símbolo DotCode debe ser impar. El número de filas debe ser al menos 5. Valor predeterminado: -1 |
| [StructuredAppendModeBarcodeId](../../aspose.barcode.generation/dotcodeparameters/structuredappendmodebarcodeid/) { get; set; } | Identifica el ID del código de barras en modo de anexado estructurado DotCode. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1. |
| [StructuredAppendModeBarcodesCount](../../aspose.barcode.generation/dotcodeparameters/structuredappendmodebarcodescount/) { get; set; } | Identifica el recuento de códigos de barras en modo de anexado estructurado DotCode. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/dotcodeparameters/tostring/)() | Devuelve una representación de cadena legible por humanos de este `DotCodeParameters`. |

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


