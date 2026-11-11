---
title: "Enumeración GS1ValidationErrorCode"
second_title: "Referencia de API de Aspose.BarCode para .NET"
description: "Aspose.BarCode.Common.GS1ValidationErrorCode enum. Identifica un error de validación de una cadena de elemento GS1, URI Digital Link o valor"
type: docs
weight: 430
url: /es/net/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enumeration

Identifica una cadena de elemento GS1, URI de Digital Link o error de validación de valor.

```csharp
public enum GS1ValidationErrorCode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| EmptyElementString | `0` | La cadena de elemento GS1 proporcionada está vacía. |
| MissingOpeningParenthesis | `1` | Falta un paréntesis de apertura que debería iniciar un Identificador de Aplicación. |
| MissingClosingParenthesis | `2` | Un Identificador de Aplicación no tiene paréntesis de cierre. |
| InvalidApplicationIdentifier | `3` | Un Identificador de Aplicación no contiene de dos a cuatro dígitos ASCII. |
| UnknownApplicationIdentifier | `4` | El Identificador de Aplicación proporcionado no está definido en el Diccionario de Sintaxis GS1 compatible. |
| MissingValue | `5` | Un Identificador de Aplicación está presente sin un valor. |
| InvalidEscapeSequence | `6` | Un valor contiene una secuencia de escape no compatible. Sólo \( está soportada. |
| ValueTooShort | `7` | Un valor es más corto que la longitud mínima definida para su Identificador de Aplicación. |
| ValueTooLong | `8` | Un valor es más largo que la longitud máxima definida para su Identificador de Aplicación. |
| InvalidCharacter | `9` | Un valor contiene un carácter fuera del conjunto de caracteres permitido para su componente. |
| InvalidChecksum | `10` | Una suma de verificación numérica o alfabética no es válida. |
| InvalidDate | `11` | Un componente de fecha no es una fecha significativa según las reglas definidas para su Identificador de Aplicación. |
| InvalidTime | `12` | Un componente de hora está fuera de su rango permitido o tiene una estructura no válida. |
| InvalidCodeListValue | `13` | El valor de un componente no está presente en su lista de códigos cerrados permitida. |
| InvalidComponentLength | `14` | Un componente no cumple con su estructura de longitud específica. |
| TruncatedComponent | `15` | Un componente de longitud fija termina antes de que todos los caracteres requeridos estén presentes. |
| UnexpectedData | `16` | Quedan datos después de que se hayan consumido todos los componentes definidos para el Identificador de Aplicación. |
| InvalidValue | `17` | Un componente viola una regla de contenido que no tiene un código de error de validación más específico. |
| GcpPrefixTooShort | `18` | Un componente es demasiado corto para contener el Prefijo de Empresa GS1 estructural de al menos cuatro dígitos. |
| InvalidGcpPrefix | `19` | El prefijo estructural GS1 Company Prefix contiene un carácter que no es un dígito ASCII. |
| InvalidDigitalLinkUri | `20` | El valor suministrado no es un URI GS1 Digital Link absoluto bien formado. |
| UnsupportedDigitalLinkScheme | `21` | Un URI GS1 Digital Link utiliza un esquema distinto de HTTP o HTTPS. |
| MissingDigitalLinkPrimaryKey | `22` | La ruta de un URI GS1 Digital Link no contiene una clave primaria compatible. |
| InvalidDigitalLinkPath | `23` | La ruta de un URI GS1 Digital Link no está compuesta por pares válidos de AI y valor. |
| InvalidDigitalLinkQualifier | `24` | Un Application Identifier de ruta no es un calificador permitido en esa posición. |
| InvalidDigitalLinkQueryParameter | `25` | Un parámetro de consulta GS1 Digital Link está mal formado. |
| ApplicationIdentifierNotAllowedInDigitalLink | `26` | Un Application Identifier no está permitido como atributo de datos GS1 Digital Link. |
| InvalidPercentEncoding | `27` | Un componente del URI GS1 Digital Link contiene una codificación de porcentaje mal formada. |
| MultipleDigitalLinkPrimaryKeys | `28` | Más de un elemento podría seleccionarse como la clave primaria del GS1 Digital Link. |
| UnsupportedElementCombination | `29` | La combinación suministrada de elementos GS1 no es compatible con la simbología o modo de codificación seleccionado. |

### Ver también

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)


