---
title: "GS1ValidationErrorCode"
second_title: "Referencia de API de Aspose.Sildes para Python vía .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.common/gs1validationerrorcode/
---

## GS1ValidationErrorCode enumeration

Identifica una cadena de elemento GS1, URI Digital Link o error de validación de valor.

## Members
| Nombre del miembro | Descripción |
| :- | :- |
| EMPTY_ELEMENT_STRING | La cadena de elemento GS1 proporcionada está vacía. |
| MISSING_OPENING_PARENTHESIS | Falta un paréntesis de apertura que debería iniciar un Application Identifier. |
| MISSING_CLOSING_PARENTHESIS | Un Application Identifier no tiene paréntesis de cierre. |
| INVALID_APPLICATION_IDENTIFIER | Un Application Identifier no contiene de dos a cuatro dígitos ASCII. |
| UNKNOWN_APPLICATION_IDENTIFIER | El Application Identifier proporcionado no está definido en el Diccionario de Sintaxis GS1 compatible. |
| MISSING_VALUE | Un Application Identifier está presente sin un valor. |
| INVALID_ESCAPE_SEQUENCE | Un valor contiene una secuencia de escape no compatible. Sólo \( está soportada. |
| VALUE_TOO_SHORT | Un valor es más corto que la longitud mínima definida para su Application Identifier. |
| VALUE_TOO_LONG | Un valor es más largo que la longitud máxima definida para su Application Identifier. |
| INVALID_CHARACTER | Un valor contiene un carácter fuera del conjunto de caracteres permitido para su componente. |
| INVALID_CHECKSUM | Una suma de verificación numérica o alfabética es inválida. |
| INVALID_DATE | Un componente de fecha no es una fecha válida según las reglas definidas para su Application Identifier. |
| INVALID_TIME | Un componente de tiempo está fuera de su rango permitido o tiene una estructura inválida. |
| INVALID_CODE_LIST_VALUE | El valor de un componente no está presente en su lista de códigos cerrada permitida. |
| INVALID_COMPONENT_LENGTH | Un componente no cumple con su estructura de longitud específica del componente. |
| TRUNCATED_COMPONENT | Un componente de longitud fija termina antes de que todos los caracteres requeridos estén presentes. |
| UNEXPECTED_DATA | Quedan datos después de que se hayan consumido todos los componentes definidos para el Identificador de Aplicación. |
| INVALID_VALUE | Un componente viola una regla de contenido que no tiene un código de error de validación más específico. |
| GCP_PREFIX_TOO_SHORT | Un componente es demasiado corto para contener el prefijo estructural de la empresa GS1 de al menos cuatro dígitos. |
| INVALID_GCP_PREFIX | El prefijo estructural de la empresa GS1 contiene un carácter que no es un dígito ASCII. |
| INVALID_DIGITAL_LINK_URI | El valor suministrado no es un URI de Enlace Digital GS1 absoluto bien formado. |
| UNSUPPORTED_DIGITAL_LINK_SCHEME | Un URI de Enlace Digital GS1 utiliza un esquema distinto de HTTP o HTTPS. |
| MISSING_DIGITAL_LINK_PRIMARY_KEY | La ruta de un URI de Enlace Digital GS1 no contiene una clave primaria compatible. |
| INVALID_DIGITAL_LINK_PATH | La ruta de un URI de Enlace Digital GS1 no consiste en pares válidos de AI y valor. |
| INVALID_DIGITAL_LINK_QUALIFIER | Un Identificador de Aplicación de ruta no es un calificador permitido en esa posición. |
| INVALID_DIGITAL_LINK_QUERY_PARAMETER | Un parámetro de consulta de GS1 Digital Link está mal formado. |
| APPLICATION_IDENTIFIER_NOT_ALLOWED_IN_DIGITAL_LINK | No se permite un Identificador de Aplicación como atributo de datos de GS1 Digital Link. |
| INVALID_PERCENT_ENCODING | Un componente de URI de GS1 Digital Link contiene una codificación de porcentaje mal formada. |
| MULTIPLE_DIGITAL_LINK_PRIMARY_KEYS | Se puede seleccionar más de un elemento como clave primaria de GS1 Digital Link. |
| UNSUPPORTED_ELEMENT_COMBINATION | La combinación proporcionada de elementos GS1 no es compatible con la simbología o modo de codificación seleccionados. |

### Ver también

* namespace [aspose.barcode.common](/barcode/python-net/aspose.barcode.common/)
* assembly [Aspose.BarCode](/barcode/python-net/)

