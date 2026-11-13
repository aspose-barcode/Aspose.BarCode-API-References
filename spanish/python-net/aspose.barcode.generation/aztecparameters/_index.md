---
title: "AztecParameters"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.generation/aztecparameters/
---

## AztecParameters class

Parámetros de Aztec.

El tipo AztecParameters expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| encode_mode | Obtiene o establece un modo de codificación Aztec. <br/>            Valor predeterminado: Auto. |
| eci_encoding | Obtiene o establece la codificación ECI. Se usa cuando AztecEncodeMode es Auto.<br/>            Valor predeterminado: ISO-8859-1 |
| structured_append_barcode_id | ID de código de barras para el modo Structured Append del código Aztec. El ID de código de barras debe estar en el rango de 1 al número de códigos de barras.<br/>            Valor predeterminado: 0 |
| structured_append_barcodes_count | Recuento de códigos de barras para el modo Structured Append del código Aztec. El recuento de códigos de barras debe estar en el rango de 1 a 26.<br/>            Valor predeterminado: 0 |
| structured_append_file_id | ID de archivo para el modo Structured Append del código Aztec (campo opcional). El ID de archivo no debe contener espacios.<br/>            Valor predeterminado: cadena vacía |
| error_level | Nivel de corrección de errores de los tipos de código Aztec.<br/>            El valor debe estar entre 5 y 95. |
| symbol_mode | Obtiene o establece un modo de símbolo Aztec.<br/>            Valor predeterminado: AztecSymbolMode.Auto. |
| layers_count | Obtiene o establece el recuento de capas del símbolo Aztec. El recuento de capas debe estar en el rango de 1 a 3 para el modo Compacto y<br/>            en el rango de 1 a 32 para el modo de Rango Completo.<br/>            Valor predeterminado: 0 (auto). |
| is_reader_initialization | Se utiliza para indicar al lector que interprete los datos contenidos dentro del símbolo<br/>            como programación para la inicialización del lector. |
| aspect_ratio | Relación altura/ancho del módulo de código de barras 2D. |

### Ver también

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

