---
title: "DotCodeParameters"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.generation/dotcodeparameters/
---

## DotCodeParameters class

Parámetros de DotCode.

El tipo DotCodeParameters expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| aspect_ratio | Relación altura/ancho del módulo de código de barras 2D. |
| encode_mode | Identifica el modo de codificación DotCode. <br/>            Valor predeterminado: Auto. |
| is_reader_initialization | Indica si el código se usa para instruir al lector a interpretar los datos siguientes como instrucciones para la inicialización o reprogramación del lector de códigos de barras.<br/>            El valor predeterminado es false. |
| structured_append_mode_barcode_id | Identifica el ID del código de barras de modo de anexado estructurado DotCode. El ID comienza en 1 y debe ser menor o igual al recuento de códigos de barras. El valor predeterminado es -1. |
| structured_append_mode_barcodes_count | Identifica el recuento de códigos de barras del modo de anexado estructurado DotCode. El valor predeterminado es -1. El recuento debe ser un valor de 1 a 35. |
| eci_encoding | Identifica la codificación ECI. Se usa cuando DotCodeEncodeMode es Auto.<br/>            Valor predeterminado: ISO-8859-1 |
| filas | Identifica el recuento de filas. La suma del número de filas más el número de columnas de un símbolo DotCode debe ser impar. El número de filas debe ser al menos 5.<br/>            Valor predeterminado: -1 |
| columnas | Identifica el recuento de columnas. La suma del número de filas más el número de columnas de un símbolo DotCode debe ser impar. El número de columnas debe ser al menos 5.<br/>            Valor predeterminado: -1 |

### Ver también

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

