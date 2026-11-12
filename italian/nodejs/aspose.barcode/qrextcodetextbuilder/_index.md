---
title: "QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Generatore di codetext esteso per codici QR 2D per la modalità ExtendedCodetext di QREncodeMode. Usa la proprietà Display2DText di BarCodeBuilder per impostare il testo visibile a rem"
type: docs
weight: 820
url: /it/nodejs/aspose.barcode/qrextcodetextbuilder/
---

## QrExtCodetextBuilder class

Generatore di codetext esteso per codici QR 2D per la modalità ExtendedCodetext di QREncodeMode. Usa la proprietà Display2DText di BarCodeBuilder per impostare il testo visibile rimuovendo i caratteri di gestione.

```js
new QrExtCodetextBuilder()
```

**Example:**

```js
//Example how to generate FNC1 first position for Extended Mode
 //create codetext
 const lTextBuilder = new QrExtCodetextBuilder();
 lTextBuilder.addFNC1FirstPosition();
 lTextBuilder.addPlainCodetext("000%89%%0");
 lTextBuilder.addFNC1GroupSeparator();
 lTextBuilder.addPlainCodetext("12345&lt;FNC1&gt;");
 //generate codetext
 const lCodetext = lTextBuilder.getExtendedCodetext();
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addCodetextWithCompactionMode(mode, codetext)](#addcodetextwithcompactionmode) | Aggiunge il codetext con la modalità di compattazione QR specificata agli elementi di codetext esteso. |
| [addFNC1FirstPosition()](#addfnc1firstposition) | Aggiunge FNC1 nella prima posizione agli elementi di codetext esteso |
| [addFNC1GroupSeparator()](#addfnc1groupseparator) | Aggiunge il Separatore di Gruppo (GS - '\\u001D') agli elementi di codetext esteso |
| [addFNC1SecondPosition(codetext)](#addfnc1secondposition) | Aggiunge FNC1 nella seconda posizione agli elementi di codetext esteso |
| [clear()](#clear) | Cancella gli elementi di testo del codice esteso |
| [getExtendedCodetext()](#getextendedcodetext) | Genera il codetext esteso dall'elenco di codetext esteso. |

### addCodetextWithCompactionMode(mode, codetext) {#addcodetextwithcompactionmode}

Aggiunge il codetext con la modalità di compattazione QR specificata agli elementi di codetext esteso.

| Parametro | Descrizione |
| --- | --- |
| modalità | Modalità di compattazione QR per il codetext. |
| codetext | Codetext in Unicode da aggiungere come elemento di codetext esteso. |

**Throws:** IllegalArgumentException The specified codetext cannot be encoded in the selected QR compaction mode.

### addFNC1FirstPosition() {#addfnc1firstposition}

Aggiunge FNC1 nella prima posizione agli elementi di codetext esteso

### addFNC1GroupSeparator() {#addfnc1groupseparator}

Aggiunge il Separatore di Gruppo (GS - '\\u001D') agli elementi di codetext esteso

### addFNC1SecondPosition(codetext) {#addfnc1secondposition}

Aggiunge FNC1 nella seconda posizione agli elementi di codetext esteso

| Parametro | Descrizione |
| --- | --- |
| codetext | Valore di FNC1 nella seconda posizione |

### clear() {#clear}

Cancella gli elementi di testo del codice esteso

### getExtendedCodetext() {#getextendedcodetext}

Genera il codetext esteso dall'elenco di codetext esteso.

**Returns:** Extended codetext as string
