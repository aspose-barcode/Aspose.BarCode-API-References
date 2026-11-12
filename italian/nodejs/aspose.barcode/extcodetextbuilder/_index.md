---
title: "ExtCodetextBuilder"
linktitle: "ExtCodetextBuilder"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Classe di supporto per la generazione automatica di codetext della Extended Codetext Mode"
type: docs
weight: 400
url: /it/nodejs/aspose.barcode/extcodetextbuilder/
---

## ExtCodetextBuilder class

Classe di supporto per la generazione automatica di codetext della Extended Codetext Mode

```js
new ExtCodetextBuilder()
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addECICodetext(ECIEncoding, codetext)](#addecicodetext) | Aggiunge il testo del codice con Identificatore di Canale Esteso |
| [addPlainCodetext(codetext)](#addplaincodetext) | Aggiunge testo del codice semplice agli elementi di testo del codice esteso |
| [clear()](#clear) | Cancella gli elementi di testo del codice esteso |
| [getExtendedCodetext()](#getextendedcodetext) | Genera testo del codice esteso dall'elenco degli elementi di generazione |

### addECICodetext(ECIEncoding, codetext) {#addecicodetext}

Aggiunge il testo del codice con Identificatore di Canale Esteso

| Parametro | Descrizione |
| --- | --- |
| ECIEncoding | Identificatore di Canale Esteso |
| codetext | Testo del codice in Unicode da aggiungere come elemento di testo del codice esteso con Identificatore di Canale Esteso |

### addPlainCodetext(codetext) {#addplaincodetext}

Aggiunge testo del codice semplice agli elementi di testo del codice esteso

| Parametro | Descrizione |
| --- | --- |
| codetext | Codetext in Unicode da aggiungere come elemento di codetext esteso |

### clear() {#clear}

Cancella gli elementi di testo del codice esteso

### getExtendedCodetext() {#getextendedcodetext}

Genera testo del codice esteso dall'elenco degli elementi di generazione

**Returns:** Return string of extended codetext
