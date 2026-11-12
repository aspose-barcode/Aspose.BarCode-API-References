---
title: "ExtCodetextBuilder"
linktitle: "ExtCodetextBuilder"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Hilfsklasse für die automatische Codetext-Generierung des Extended Codetext Mode"
type: docs
weight: 400
url: /de/nodejs/aspose.barcode/extcodetextbuilder/
---

## ExtCodetextBuilder class

Hilfsklasse für die automatische Codetext-Generierung des Extended Codetext Mode

```js
new ExtCodetextBuilder()
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addECICodetext(ECIEncoding, codetext)](#addecicodetext) | Fügt Codetext mit erweitertem Kanalbezeichner hinzu |
| [addPlainCodetext(codetext)](#addplaincodetext) | Fügt einfachen Codetext zu den erweiterten Codetext-Elementen hinzu |
| [clear()](#clear) | Löscht erweiterte Codetext-Elemente |
| [getExtendedCodetext()](#getextendedcodetext) | Erstellt erweiterten Codetext aus der Liste der Generierungselemente |

### addECICodetext(ECIEncoding, codetext) {#addecicodetext}

Fügt Codetext mit erweitertem Kanalbezeichner hinzu

| Parameter | Beschreibung |
| --- | --- |
| ECIEncoding | Erweiterter Kanalbezeichner |
| codetext | Codetext in Unicode, der als erweitertes Codetext-Element mit erweitertem Kanalbezeichner hinzugefügt wird |

### addPlainCodetext(codetext) {#addplaincodetext}

Fügt einfachen Codetext zu den erweiterten Codetext-Elementen hinzu

| Parameter | Beschreibung |
| --- | --- |
| codetext | Codetext in Unicode, der als erweitertes Codetext-Element hinzugefügt wird |

### clear() {#clear}

Löscht erweiterte Codetext-Elemente

### getExtendedCodetext() {#getextendedcodetext}

Erstellt erweiterten Codetext aus der Liste der Generierungselemente

**Returns:** Return string of extended codetext
