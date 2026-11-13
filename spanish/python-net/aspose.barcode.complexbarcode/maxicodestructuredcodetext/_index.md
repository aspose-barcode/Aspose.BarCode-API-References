---
title: "MaxiCodeStructuredCodetext"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

Clase base para codificar y decodificar el texto incrustado en el código MaxiCode para los modos 2 y 3.

El tipo MaxiCodeStructuredCodetext expone los siguientes miembros:
## Propiedades
| Nombre | Descripción |
| :- | :- |
| encode_mode | Obtiene o establece un modo de codificación MaxiCode. <br/>            Valor predeterminado: Auto. |
| eci_encoding | Obtiene o establece la codificación ECI. Se usa cuando MaxiCodeEncodeMode es Auto.<br/>            Valor predeterminado: ISO-8859-1 |
| postal_code | Identifica el código postal. Debe ser de 9 dígitos en el modo 2 o <br/>            6 símbolos alfanuméricos en el modo 3. |
| country_code | Identifica el código de país de 3 dígitos. |
| service_category | Identifica la categoría de servicio de 3 dígitos. |
| second_message | Identifica el segundo mensaje del código de barras. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| get_mode() | Obtiene el modo MaxiCode. |
| get_constructed_codetext() | Construye codetext |
| init_from_string(constructed_codetext) | Inicializa la instancia a partir del codetext construido. |
| get_barcode_type() | Obtiene el tipo de código de barras. |

### Ver también

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

