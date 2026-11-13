---
title: "GS1DigitalLink"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.complexbarcode/gs1digitallink/
---

## GS1DigitalLink class

Representa el texto de código GS1 Digital Link para codificar y decodificar como una secuencia ordenada de<br/>            elementos de Identificador de Aplicación. El orden de origen y los Identificadores de Aplicación repetidos se conservan.<br/>            El texto de código construido es un URI GS1 Digital Link sin comprimir.<br/>            Los parámetros de consulta y fragmentos de URI que no son GS1 se ignoran al analizar.

El tipo GS1DigitalLink expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| GS1DigitalLink(uri_stem) | Inicializa una nueva instancia de la clase GS1DigitalLink |
| GS1DigitalLink(uri_stem, primary_application_identifier) | Inicializa una nueva instancia de la clase GS1DigitalLink |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| uri_stem | Obtiene el prefijo URI absoluto antes del segmento de ruta de la clave primaria GS1.<br/>            El stem no contiene una cadena de consulta ni fragmento. |
| primary_application_identifier | Obtiene el Identificador de Aplicación utilizado como clave primaria del Digital Link.<br/>            Null significa que la clave primaria se selecciona automáticamente cuando se construye el URI. |
| barcode_type | Obtiene o establece el tipo de código de barras utilizado para codificar este GS1 Digital Link.<br/>            Los tipos compatibles son QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF y Code128.<br/>            El valor predeterminado es QR. |
| conteo | Obtiene el número de elementos del Identificador de Aplicación. |
| elementos | Obtiene una copia de todos los elementos en el orden de origen. |
## Indexer
| Nombre | Descripción |
| :- | :- |
| [index] | Obtiene un elemento por su posición en la secuencia ordenada. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| create(uri_stem, codetext) | Crea un GS1 Digital Link copiando todos los elementos del codetext de GS1 y seleccionando<br/>            la única clave primaria disponible. |
| create(uri_stem, codetext, primary_application_identifier) | Crea un GS1 Digital Link copiando todos los elementos del codetext de GS1 y seleccionando<br/>            la única clave primaria disponible. |
| get_first(application_identifier) | Obtiene el primer valor para un Identificador de Aplicación. |
| get_all(application_identifier) | Obtiene todos los valores para un Identificador de Aplicación en el orden de origen. |
| add(application_identifier, value) | Añade un elemento de Identificador de Aplicación validado. |
| validate(value) | Valida una URI de GS1 Digital Link sin comprimir sin construir un objeto. |
| parse(value) | Analiza una URI de GS1 Digital Link sin comprimir. |
| try_parse(value, result, validation_result) | Intenta analizar una URI de GS1 Digital Link sin comprimir y devuelve errores de validación estructurados. |
| to_gs1_codetext() | Crea un codetext GS1 independiente que contiene los elementos GS1 actuales.<br/>            La información solo de URI no está incluida. |
| to_uri_string() | Formatea el estado actual del objeto como una URI de GS1 Digital Link sin comprimir. |
| get_constructed_codetext() | Construye la URI de GS1 Digital Link sin comprimir. |
| init_from_string(constructed_codetext) | Inicializa esta instancia a partir de una URI de GS1 Digital Link sin comprimir.<br/>            El estado existente se reemplaza solo después de que la URI proporcionada se haya analizado con éxito.<br/>            El tipo de código de barras seleccionado se conserva. |
| get_barcode_type() | Obtiene el tipo de código de barras utilizado para codificar este GS1 Digital Link. |

### Ver también

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

