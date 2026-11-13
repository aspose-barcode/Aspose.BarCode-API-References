---
title: "MailmarkCodetext"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.complexbarcode/mailmarkcodetext/
---

## MailmarkCodetext class

Clase para codificar y decodificar el texto incrustado en el código Royal Mailmark de 4 estados.

El tipo MailmarkCodetext expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| MailmarkCodetext() | Inicializa una nueva instancia de la clase MailmarkCodetext |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| format | "0" – Nulo o Prueba<br/>            "1" – Carta<br/>            "2" – Carta Grande |
| version_id | Actualmente "1" – Para código de barras Mailmark (0 y 2 a 9 y A a Z reservados para uso futuro) |
| klass | "0" - Nulo o Prueba<br/>            "1" - 1C (Minorista)<br/>            "2" - 2C (Minorista)<br/>            "3" - 3C (Minorista)<br/>            "4" - Premium (Correo de Publicación Minorista) (para posible uso futuro)<br/>            "5" - Diferido (Minorista)<br/>            "6" - Aire (Minorista) (para posible uso futuro)<br/>            "7" - Superficie (Minorista) (para posible uso futuro)<br/>            "8" - Premium (Acceso a Red)<br/>            "9" - Estándar (Acceso a Red) |
| supply_chain_id | Los valores máximos son 99 para el código de barras C y 999999 para el código de barras L. |
| item_id | El valor máximo es 99999999. |
| destination_post_code_and_dps | El PC y DP deben cumplir con un formato PAF.<br/>            Cadena de nueve caracteres que indica internacional "XY11     " (note los 5 espacios finales) o un patrón<br/>            de caracteres que indica un código de clasificación doméstico.<br/>            Un código de clasificación doméstico consta de un código postal externo, un código postal interno y un sufijo de punto de entrega. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| get_constructed_codetext() | Construye el texto de código a partir de los datos Mailmark. |
| init_from_string(constructed_codetext) | Inicializa los datos Mailmark a partir del texto de código construido. |
| get_barcode_type() | Obtiene el tipo de código de barras. |

### Ver también

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

