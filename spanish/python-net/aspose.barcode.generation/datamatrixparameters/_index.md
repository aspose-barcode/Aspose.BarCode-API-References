---
title: "DataMatrixParameters"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.generation/datamatrixparameters/
---

## DataMatrixParameters class

Parámetros de DataMatrix.

El tipo DataMatrixParameters expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| ecc_type | Obtiene o establece un tipo ECC de Datamatrix.<br/>            Valor predeterminado: DataMatrixEccType.Ecc200. |
| version | Obtiene o establece el tamaño del símbolo Datamatrix.<br/>            Valor predeterminado: Version.Auto. |
| encode_mode | Modo de codificación del código de barras Datamatrix.<br/>            Valor predeterminado: EncodeMode.Auto. |
| structured_append_barcode_id | ID del código de barras para el modo Structured Append del código de barras Datamatrix.<br/>            Valor predeterminado: 0 |
| structured_append_barcodes_count | Recuento de códigos de barras para el modo Structured Append del código de barras Datamatrix.<br/>            Valor predeterminado: 0 |
| structured_append_file_id | ID de archivo para el modo Structured Append del código de barras Datamatrix.<br/>            Valor predeterminado: 0 |
| is_reader_programming | Se utiliza para indicar al lector que interprete los datos contenidos en el símbolo<br/>            como programación para la inicialización del lector.<br/>            Valor predeterminado: false |
| macro_characters | Los valores de Macro Characters 05 y 06 se utilizan para obtener una codificación más compacta en modos especiales.<br/>            Solo se pueden usar con DataMatrixEccType.Ecc200 o DataMatrixEccType.EccAuto.<br/>            No se pueden usar con EncodeTypes.GS1DataMatrix<br/>            Valor predeterminado: MacroCharacters.None. |
| aspect_ratio | Relación altura/ancho del módulo de código de barras 2D. |
| eci_encoding | Obtiene o establece la codificación ECI. Se usa cuando EncodeMode es Auto.<br/>            Valor predeterminado: ISO-8859-1 |

### Ver también

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

