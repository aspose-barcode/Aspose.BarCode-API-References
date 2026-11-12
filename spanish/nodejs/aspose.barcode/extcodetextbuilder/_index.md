---
title: "ExtCodetextBuilder"
linktitle: "ExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Clase auxiliar para la generación automática de codetexto del Extended Codetext Mode"
type: docs
weight: 400
url: /es/nodejs/aspose.barcode/extcodetextbuilder/
---

## ExtCodetextBuilder class

Clase auxiliar para la generación automática de codetexto del Extended Codetext Mode

```js
new ExtCodetextBuilder()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addECICodetext(ECIEncoding, codetext)](#addecicodetext) | Agrega codetext con Extended Channel Identifier |
| [addPlainCodetext(codetext)](#addplaincodetext) | Agrega codetext plano a los elementos de codetext extendido |
| [clear()](#clear) | Borra los elementos de codetext extendido |
| [getExtendedCodetext()](#getextendedcodetext) | Genera codetext extendido a partir de la lista de elementos de generación |

### addECICodetext(ECIEncoding, codetext) {#addecicodetext}

Agrega codetext con Extended Channel Identifier

| Parámetro | Descripción |
| --- | --- |
| ECIEncoding | Identificador de Canal Extendido |
| codetext | Codetext en unicode para agregar como elemento de codetext extendido con Extended Channel Identifier |

### addPlainCodetext(codetext) {#addplaincodetext}

Agrega codetext plano a los elementos de codetext extendido

| Parámetro | Descripción |
| --- | --- |
| codetext | Codetext en Unicode para agregar como elemento de codetext extendido |

### clear() {#clear}

Borra los elementos de codetext extendido

### getExtendedCodetext() {#getextendedcodetext}

Genera codetext extendido a partir de la lista de elementos de generación

**Returns:** Return string of extended codetext
