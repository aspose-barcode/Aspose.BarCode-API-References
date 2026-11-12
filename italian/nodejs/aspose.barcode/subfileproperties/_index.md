---
title: "SubfileProperties"
linktitle: "SubfileProperties"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Le proprietà del sottofile USA DL, offset e lunghezza, sono impostate automaticamente."
type: docs
weight: 890
url: /it/nodejs/aspose.barcode/subfileproperties/
---

## SubfileProperties class

Le proprietà del sottofile USA DL, offset e lunghezza, sono impostate automaticamente.

```js
new SubfileProperties()
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getLength()](#getlength) | 4 Questi byte contengono un valore numerico a 4 cifre che specifica la lunghezza del Subfile in byte. Il terminatore di segmento m |
| [getOffset()](#getoffset) | Valore numerico a 4 cifre che specifica il numero di byte dall'inizio del file fino al punto in cui i dati si riferiscono |
| [getType()](#gettype) | Tipo di subfile a 2 byte, come "DL" |
| [setLength()](#setlength) | 4 Questi byte contengono un valore numerico a 4 cifre che specifica la lunghezza del Subfile in byte. Il terminatore di segmento m |
| [setOffset()](#setoffset) | Valore numerico a 4 cifre che specifica il numero di byte dall'inizio del file fino al punto in cui i dati si riferiscono |
| [setType()](#settype) | Tipo di subfile a 2 byte, come "DL" |

### getLength() {#getlength}

4 Questi byte contengono un valore numerico a 4 cifre che specifica la lunghezza del Subfile in byte. Il terminatore di segmento deve essere incluso nel calcolo della lunghezza del subfile. Un terminatore di segmento = 1. Ogni subfile deve iniziare con il Tipo di Subfile a due caratteri e questi due caratteri devono essere inclusi nella lunghezza.

### getOffset() {#getoffset}

Valore numerico a 4 cifre che specifica il numero di byte dall'inizio del file fino al punto in cui i dati relativi al particolare sub-file sono situati. Il primo byte del file si trova all'offset 0.

### getType() {#gettype}

Tipo di subfile a 2 byte, come "DL"

### setLength() {#setlength}

4 Questi byte contengono un valore numerico a 4 cifre che specifica la lunghezza del Subfile in byte. Il terminatore di segmento deve essere incluso nel calcolo della lunghezza del subfile. Un terminatore di segmento = 1. Ogni subfile deve iniziare con il Tipo di Subfile a due caratteri e questi due caratteri devono essere inclusi nella lunghezza.

### setOffset() {#setoffset}

Valore numerico a 4 cifre che specifica il numero di byte dall'inizio del file fino al punto in cui i dati relativi al particolare sub-file sono situati. Il primo byte del file si trova all'offset 0.

### setType() {#settype}

Tipo di subfile a 2 byte, come "DL"
