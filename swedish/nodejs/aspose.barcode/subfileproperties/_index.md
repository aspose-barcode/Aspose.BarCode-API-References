---
title: "SubfileProperties"
linktitle: "SubfileProperties"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "USA DL‑underfilsegenskaper, offset och längd sätts automatiskt."
type: docs
weight: 890
url: /sv/nodejs/aspose.barcode/subfileproperties/
---

## SubfileProperties class

USA DL‑underfilsegenskaper, offset och längd sätts automatiskt.

```js
new SubfileProperties()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getLength()](#getlength) | 4 Dessa byte innehåller ett 4‑siffrigt numeriskt värde som specificerar längden på delfilen i byte. Segmentavslutaren m |
| [getOffset()](#getoffset) | 4‑siffrigt numeriskt värde som specificerar antalet byte från filens början till där data relaterar. |
| [getType()](#gettype) | 2‑byte typ av delfil, till exempel "DL" |
| [setLength()](#setlength) | 4 Dessa byte innehåller ett 4‑siffrigt numeriskt värde som specificerar längden på delfilen i byte. Segmentavslutaren m |
| [setOffset()](#setoffset) | 4‑siffrigt numeriskt värde som specificerar antalet byte från filens början till där data relaterar. |
| [setType()](#settype) | 2‑byte typ av delfil, till exempel "DL" |

### getLength() {#getlength}

4 Dessa byte innehåller ett 4‑siffrigt numeriskt värde som specificerar längden på delfilen i byte. Segmentavslutaren måste inkluderas vid beräkning av delfilens längd. En segmentavslutare = 1. Varje delfil måste börja med den tvåtecken långa Subfile‑typen och dessa två tecken måste också räknas med i längden.

### getOffset() {#getoffset}

4‑siffrigt numeriskt värde som specificerar antalet byte från filens början till där data som hör till den specifika delfilen är placerade. Den första byten i filen ligger på offset 0.

### getType() {#gettype}

2‑byte typ av delfil, till exempel "DL"

### setLength() {#setlength}

4 Dessa byte innehåller ett 4‑siffrigt numeriskt värde som specificerar längden på delfilen i byte. Segmentavslutaren måste inkluderas vid beräkning av delfilens längd. En segmentavslutare = 1. Varje delfil måste börja med den tvåtecken långa Subfile‑typen och dessa två tecken måste också räknas med i längden.

### setOffset() {#setoffset}

4‑siffrigt numeriskt värde som specificerar antalet byte från filens början till där data som hör till den specifika delfilen är placerade. Den första byten i filen ligger på offset 0.

### setType() {#settype}

2‑byte typ av delfil, till exempel "DL"
