---
title: "Mailmark2DCodetext"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Clase para codificar y decodificar el texto incrustado en el código Royal Mail 2D Mailmark.

El tipo Mailmark2DCodetext expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| Mailmark2DCodetext() | Inicializa una nueva instancia de la clase Mailmark2DCodetext |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| upu_country_id | Identifica el ID de país UPU. Longitud máxima: 4 caracteres. |
| information_type_id | Identifica la carga útil del código de barras Mailmark de Royal Mail para cada tipo de producto. |
| version_id | Identifica la versión del código de barras según corresponda a cada ID de tipo de información. |
| klass | Identifica la clase del artículo. |
| supply_chain_id | Identifica el grupo único de clientes involucrados en el envío.<br/>            Valor máximo: 9999999. |
| item_id | Identifica el artículo único dentro del ID de la cadena de suministro.<br/>            Cada código de barras Mailmark debe llevar un ID<br/>            para que pueda ser identificado de forma única durante al menos 90 días.<br/>            Valor máximo: 99999999. |
| destination_post_code_and_dps | Contiene el código postal de la dirección de entrega con DPS<br/>            Si es interior, el código postal/DP contiene el siguiente número de caracteres.<br/>            Área (1 o 2 caracteres) Distrito (1 o 2 caracteres)<br/>            Sector (1 carácter) Unidad (2 caracteres) DPS (2 caracteres).<br/>            El código postal y el DPS deben cumplir con un formato PAF® válido. |
| rts_flag | Indicador que indica qué nivel del servicio de devolución al remitente se está solicitando. |
| return_to_sender_post_code | Contiene el código postal de devolución al remitente pero sin DPS.<br/>            El CP (sin DPS) debe cumplir con un formato PAF®. |
| customer_content | Espacio opcional para uso del cliente. |
| customer_content_encode_mode | Modo de codificación del código de barras Datamatrix.<br/>            Valor predeterminado: EncodeMode.C40. |
| data_matrix_type | El tipo Mailmark 2D define el tamaño del código de barras Data Matrix. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| get_constructed_codetext() | Construye el texto de código a partir de los datos Mailmark. |
| init_from_string(constructed_codetext) | Inicializa los datos Mailmark a partir del texto de código construido. |
| get_barcode_type() | Obtiene el tipo de código de barras. |

### Ver también

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

