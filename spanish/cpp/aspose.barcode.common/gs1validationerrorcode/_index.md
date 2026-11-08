---
title: "enum"
linktitle: "GS1ValidationErrorCode"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " enum. Identifica una cadena de elemento GS1, URI de Digital Link o error de validación de valor en C++."
type: docs
weight: 600
url: /es/cpp/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enum


Identifica un error de validación de una cadena de elemento GS1, URI de Enlace Digital o valor.

```cpp
enum class GS1ValidationErrorCode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| EmptyElementString | 0 | La cadena de elemento GS1 proporcionada está vacía. |
| MissingOpeningParenthesis | 1 | Falta un paréntesis de apertura que debería iniciar un Identificador de Aplicación. |
| MissingClosingParenthesis | 2 | Un Identificador de Aplicación no tiene paréntesis de cierre. |
| InvalidApplicationIdentifier | 3 | Un Identificador de Aplicación no contiene de dos a cuatro dígitos ASCII. |
| UnknownApplicationIdentifier | 4 | El Identificador de Aplicación proporcionado no está definido en el Diccionario de Sintaxis GS1 compatible. |
| MissingValue | 5 | Hay un Identificador de Aplicación presente sin un valor. |
| InvalidEscapeSequence | 6 | Un valor contiene una secuencia de escape no compatible. Sólo ( está soportado. |
| ValueTooShort | 7 | Un valor es más corto que la longitud mínima definida para su Identificador de Aplicación. |
| ValueTooLong | 8 | Un valor es más largo que la longitud máxima definida para su Identificador de Aplicación. |
| InvalidCharacter | 9 | Un valor contiene un carácter fuera del conjunto de caracteres permitido para su componente. |
| InvalidChecksum | 10 | Una suma de verificación numérica o alfabética es inválida. |
| InvalidDate | 11 | Un componente de fecha no es una fecha significativa según las reglas definidas para su Identificador de Aplicación. |
| InvalidTime | 12 | Un componente de hora está fuera de su rango permitido o tiene una estructura inválida. |
| InvalidCodeListValue | 13 | El valor de un componente no está presente en su lista de códigos cerrada permitida. |
| InvalidComponentLength | 14 | Un componente no cumple con su estructura de longitud específica del componente. |
| TruncatedComponent | 15 | Un componente de longitud fija termina antes de que todos los caracteres requeridos estén presentes. |
| UnexpectedData | 16 | Quedan datos después de que se hayan consumido todos los componentes definidos para el Identificador de Aplicación. |
| InvalidValue | 17 | Un componente viola una regla de contenido que no tiene un código de error de validación más específico. |
| GcpPrefixTooShort | 18 | Un componente es demasiado corto para contener el prefijo estructural de la empresa GS1 de al menos cuatro dígitos. |
| InvalidGcpPrefix | 19 | El prefijo estructural de la empresa GS1 contiene un carácter que no es un dígito ASCII. |
| InvalidDigitalLinkUri | 20 | El valor suministrado no es una URI de Enlace Digital GS1 absoluta bien formada. |
| UnsupportedDigitalLinkScheme | 21 | Una URI de Enlace Digital GS1 utiliza un esquema distinto de HTTP o HTTPS. |
| MissingDigitalLinkPrimaryKey | 22 | La ruta de una URI de Enlace Digital GS1 no contiene una clave primaria compatible. |
| InvalidDigitalLinkPath | 23 | La ruta de una URI de Enlace Digital GS1 no consiste en pares válidos de AI y valor. |
| InvalidDigitalLinkQualifier | 24 | Un identificador de aplicación de ruta no es un calificador permitido en esa posición. |
| InvalidDigitalLinkQueryParameter | 25 | Un parámetro de consulta de GS1 Digital Link está mal formado. |
| ApplicationIdentifierNotAllowedInDigitalLink | 26 | Un Identificador de Aplicación no está permitido como atributo de datos de GS1 Digital Link. |
| InvalidPercentEncoding | 27 | Un componente de URI de GS1 Digital Link contiene una codificación de porcentaje mal formada. |
| MultipleDigitalLinkPrimaryKeys | 28 | Se podría seleccionar más de un elemento como clave primaria de GS1 Digital Link. |
| UnsupportedElementCombination | 29 | La combinación proporcionada de elementos GS1 no es compatible con la simbología o modo de codificación seleccionado. |

## Ver también

* Namespace [Aspose::BarCode::Common](../)
* Library [Aspose.BarCode for C++](../../)
