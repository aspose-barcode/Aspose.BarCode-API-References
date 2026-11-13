---
title: "SecondaryAndAdditionalData"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

Clase para almacenar los datos secundarios y adicionales HIBC LIC.

El tipo SecondaryAndAdditionalData expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| SecondaryAndAdditionalData() | Inicializa una nueva instancia de la clase SecondaryAndAdditionalData |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| expiry_date_format | Identifica el formato de fecha de vencimiento. |
| expiry_date | Identifica la fecha de vencimiento. Se usará si ExpiryDateFormat no está configurado a None. |
| lot_number | Identifica el número de lote o lote de producción. El número de lote/lote debe ser una cadena alfanumérica con una longitud de hasta 18 símbolos. |
| serial_number | Identifica el número de serie. El número de serie debe ser una cadena alfanumérica de hasta 18 símbolos. |
| date_of_manufacture | Identifica la fecha de fabricación.<br/>            La fecha de fabricación puede establecerse en DateTime.MinValue para no usar este campo.<br/>            Valor predeterminado: DateTime.MinValue |
| quantity | Identifica la cantidad, debe ser un valor entero de 0 a 500. <br/>            La cantidad puede establecerse en -1 para no usar este campo.<br/>            Valor predeterminado: -1 |
## Métodos
| Nombre | Descripción |
| :- | :- |
| parse_from_string(secondary_data_codetext) | Instancia datos suplementarios secundarios y adicionales a partir de una cadena según la especificación HIBC LIC. |

### Ver también

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

