---
title: "GS1Codetext"
second_title: "Referencia de API de Aspose.BarCode para Python a través de .NET"
description: 
type: docs
url: /es/python-net/aspose.barcode.complexbarcode/gs1codetext/
---

## GS1Codetext class

Representa el texto de código GS1 para codificar y decodificar como una secuencia ordenada de<br/>            elementos de Identificador de Aplicación. El orden de origen y los Identificadores de Aplicación repetidos<br/>            se conservan. La representación entre corchetes tiene la forma (AI)valor(AI)valor.<br/>            Un paréntesis de apertura literal '(' dentro de un valor debe escribirse como \(; esta es la<br/>            única secuencia de escape admitida. Un paréntesis de cierre ')' dentro de un valor no<br/>            requiere escape.

El tipo GS1Codetext expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| GS1Codetext() | Inicializa una nueva instancia de la clase GS1Codetext |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| barcode_type | Obtiene o establece el tipo de código de barras utilizado para codificar este GS1 codetext.<br/>            Los tipos compatibles son GS1Aztec, GS1CodablockF, GS1Code128, GS1DataMatrix,<br/>            GS1DotCode, GS1HanXin, GS1MicroPdf417, GS1QR y los tipos GS1 DataBar.<br/>            El valor predeterminado es GS1Code128. |
| conteo | Obtiene el número de elementos del Identificador de Aplicación. |
| elementos | Obtiene una copia de todos los elementos en el orden de origen. |
## Indexer
| Nombre | Descripción |
| :- | :- |
| [index] | Obtiene un elemento por su posición en la secuencia ordenada. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| get_first(application_identifier) | Obtiene el primer valor para un Identificador de Aplicación. |
| get_all(application_identifier) | Obtiene todos los valores para un Identificador de Aplicación en el orden de origen. |
| add(application_identifier, value) | Añade un elemento de Identificador de Aplicación validado. |
| validate(value) | Valida una cadena de elemento GS1 entre corchetes en la forma (AI)valor(AI)valor sin<br/>            crear un objeto. Un '(' literal dentro de un valor debe escribirse como \(; no<br/>            se admite ninguna otra secuencia de escape, y ')' no requiere escape. |
| parse(value) | Analiza una cadena de elemento GS1 entre corchetes en la forma (AI)valor(AI)valor. Un '(' literal<br/>            dentro de un valor debe escribirse como \(; no se admite ninguna otra secuencia de escape,<br/>            y ')' no requiere escape. |
| try_parse(value, result, validation_result) | Intenta analizar una cadena de elemento GS1 entre corchetes en la forma (AI)valor(AI)valor<br/>            y devuelve errores de validación estructurados. Un '(' literal dentro de un valor debe<br/>            escribirse como \(; no se admite ninguna otra secuencia de escape, y ')' no requiere<br/>            escape. |
| get_constructed_codetext() | Construye el texto GS1 entre corchetes en la forma (AI)valor(AI)valor.<br/>            Los paréntesis de apertura literales en los valores se escapan como \(. |
| init_from_string(constructed_codetext) | Inicializa esta instancia a partir del texto GS1 entre corchetes en la forma (AI)valor(AI)valor.<br/>            Los elementos existentes se reemplazan solo después de que el texto proporcionado se haya analizado correctamente. |
| get_barcode_type() | Obtiene el tipo de código de barras utilizado para codificar este GS1 codetext. |

### Ver también

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

