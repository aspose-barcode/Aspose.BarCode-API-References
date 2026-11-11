---
title: "Clase DataMatrixParameters"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Aspose.BarCode.Generation.DataMatrixParameters clase. Parámetros DataMatrix"
type: docs
weight: 1220
url: /es/net/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class

Parámetros de DataMatrix.

```csharp
public class DataMatrixParameters
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AspectRatio](../../aspose.barcode.generation/datamatrixparameters/aspectratio/) { get; set; } | Relación altura/ancho del módulo de código de barras 2D. |
| [EccType](../../aspose.barcode.generation/datamatrixparameters/ecctype/) { get; set; } | Obtiene o establece un tipo ECC de Datamatrix. Valor predeterminado: DataMatrixEccType.Ecc200. |
| [ECIEncoding](../../aspose.barcode.generation/datamatrixparameters/eciencoding/) { get; set; } | Obtiene o establece la codificación ECI. Se usa cuando EncodeMode es Auto. Valor predeterminado: ISO-8859-1 |
| [EncodeMode](../../aspose.barcode.generation/datamatrixparameters/encodemode/) { get; set; } | Modo de codificación del código de barras Datamatrix. Valor predeterminado: EncodeMode.Auto. |
| [IsReaderProgramming](../../aspose.barcode.generation/datamatrixparameters/isreaderprogramming/) { get; set; } | Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo como programación para la inicialización del lector. Valor predeterminado: false |
| [MacroCharacters](../../aspose.barcode.generation/datamatrixparameters/macrocharacters/) { get; set; } | Los valores de los caracteres macro 05 y 06 se usan para obtener una codificación más compacta en modos especiales. Solo se pueden usar con DataMatrixEccType.Ecc200 o DataMatrixEccType.EccAuto. No se pueden usar con EncodeTypes.GS1DataMatrix Valor predeterminado: MacroCharacters.None. |
| [StructuredAppendBarcodeId](../../aspose.barcode.generation/datamatrixparameters/structuredappendbarcodeid/) { get; set; } | ID de código de barras para el modo Structured Append del código de barras Datamatrix. Valor predeterminado: 0 |
| [StructuredAppendBarcodesCount](../../aspose.barcode.generation/datamatrixparameters/structuredappendbarcodescount/) { get; set; } | Recuento de códigos de barras para el modo Structured Append del código de barras Datamatrix. Valor predeterminado: 0 |
| [StructuredAppendFileId](../../aspose.barcode.generation/datamatrixparameters/structuredappendfileid/) { get; set; } | ID de archivo para el modo Structured Append del código de barras Datamatrix. Valor predeterminado: 0 |
| [Version](../../aspose.barcode.generation/datamatrixparameters/version/) { get; set; } | Obtiene o establece el tamaño del símbolo Datamatrix. Valor predeterminado: Version.Auto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.barcode.generation/datamatrixparameters/tostring/)() | Devuelve una representación de cadena legible por humanos de este `DataMatrixParameters`. |

### Ver también

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


