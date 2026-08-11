---
title: "ExtCodetextBuilder"
linktitle: "ExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Helper class for automatic codetext generation of the Extended Codetext Mode"
type: docs
weight: 400
url: /nodejs/aspose.barcode/extcodetextbuilder/
---

## ExtCodetextBuilder class

Helper class for automatic codetext generation of the Extended Codetext Mode

```js
new ExtCodetextBuilder()
```

## Methods

| Name | Description |
| --- | --- |
| [addECICodetext(ECIEncoding, codetext)](#addecicodetext) | Adds codetext with Extended Channel Identifier |
| [addPlainCodetext(codetext)](#addplaincodetext) | Adds plain codetext to the extended codetext items |
| [clear()](#clear) | Clears extended codetext items |
| [getExtendedCodetext()](#getextendedcodetext) | Generate extended codetext from generation items list |

### addECICodetext(ECIEncoding, codetext) {#addecicodetext}

Adds codetext with Extended Channel Identifier

| Parameter | Description |
| --- | --- |
| ECIEncoding | Extended Channel Identifier |
| codetext | Codetext in unicode to add as extended codetext item with Extended Channel Identifier |

### addPlainCodetext(codetext) {#addplaincodetext}

Adds plain codetext to the extended codetext items

| Parameter | Description |
| --- | --- |
| codetext | Codetext in unicode to add as extended codetext item |

### clear() {#clear}

Clears extended codetext items

### getExtendedCodetext() {#getextendedcodetext}

Generate extended codetext from generation items list

**Returns:** Return string of extended codetext
