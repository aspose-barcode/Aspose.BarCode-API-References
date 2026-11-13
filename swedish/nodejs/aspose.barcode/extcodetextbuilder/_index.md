---
title: "ExtCodetextBuilder"
linktitle: "ExtCodetextBuilder"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Hjälparklass för automatisk generering av kodtext för det utökade kodtextläget"
type: docs
weight: 400
url: /sv/nodejs/aspose.barcode/extcodetextbuilder/
---

## ExtCodetextBuilder class

Hjälparklass för automatisk generering av kodtext för det utökade kodtextläget

```js
new ExtCodetextBuilder()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addECICodetext(ECIEncoding, codetext)](#addecicodetext) | Lägger till kodtext med Extended Channel Identifier |
| [addPlainCodetext(codetext)](#addplaincodetext) | Lägger till vanlig kodtext till de utökade kodtextobjekten |
| [clear()](#clear) | Rensar utökade kodtextobjekt |
| [getExtendedCodetext()](#getextendedcodetext) | Generera utökad kodtext från listan med genereringsobjekt |

### addECICodetext(ECIEncoding, codetext) {#addecicodetext}

Lägger till kodtext med Extended Channel Identifier

| Parameter | Beskrivning |
| --- | --- |
| ECIEncoding | Extended Channel Identifier |
| codetext | Kodtext i unicode att lägga till som utökad kodtextpost med Extended Channel Identifier |

### addPlainCodetext(codetext) {#addplaincodetext}

Lägger till vanlig kodtext till de utökade kodtextobjekten

| Parameter | Beskrivning |
| --- | --- |
| codetext | Kodtext i Unicode att lägga till som utökat kodtextobjekt |

### clear() {#clear}

Rensar utökade kodtextobjekt

### getExtendedCodetext() {#getextendedcodetext}

Generera utökad kodtext från listan med genereringsobjekt

**Returns:** Return string of extended codetext
