---
title: "SubfileProperties"
linktitle: "SubfileProperties"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "USA DL-subbestandseigenschappen, offset en lengte worden automatisch ingesteld."
type: docs
weight: 890
url: /nl/nodejs/aspose.barcode/subfileproperties/
---

## SubfileProperties class

USA DL-subbestandseigenschappen, offset en lengte worden automatisch ingesteld.

```js
new SubfileProperties()
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getLength()](#getlength) | 4 Deze bytes bevatten een 4-cijferige numerieke waarde die de lengte van het Subfile in bytes specificeert. De segmentterminator m |
| [getOffset()](#getoffset) | 4-cijferige numerieke waarde die het aantal bytes vanaf het begin van het bestand aangeeft tot waar de gegevens betrekking hebben. |
| [getType()](#gettype) | 2-byte type van subfile, bijvoorbeeld "DL" |
| [setLength()](#setlength) | 4 Deze bytes bevatten een 4-cijferige numerieke waarde die de lengte van het Subfile in bytes specificeert. De segmentterminator m |
| [setOffset()](#setoffset) | 4-cijferige numerieke waarde die het aantal bytes vanaf het begin van het bestand aangeeft tot waar de gegevens betrekking hebben. |
| [setType()](#settype) | 2-byte type van subfile, bijvoorbeeld "DL" |

### getLength() {#getlength}

4 Deze bytes bevatten een 4-cijferige numerieke waarde die de lengte van het Subfile in bytes specificeert. De segmentterminator moet worden meegenomen bij het berekenen van de lengte van het subfile. Een segmentterminator = 1. Elk subfile moet beginnen met het twee‑karakter Subfile Type en deze twee karakters moeten ook worden meegenomen in de lengte.

### getOffset() {#getoffset}

4-cijferige numerieke waarde die het aantal bytes vanaf het begin van het bestand aangeeft tot waar de gegevens die betrekking hebben op het specifieke sub‑file zich bevinden. Het eerste byte in het bestand bevindt zich op offset 0.

### getType() {#gettype}

2-byte type van subfile, bijvoorbeeld "DL"

### setLength() {#setlength}

4 Deze bytes bevatten een 4-cijferige numerieke waarde die de lengte van het Subfile in bytes specificeert. De segmentterminator moet worden meegenomen bij het berekenen van de lengte van het subfile. Een segmentterminator = 1. Elk subfile moet beginnen met het twee‑karakter Subfile Type en deze twee karakters moeten ook worden meegenomen in de lengte.

### setOffset() {#setoffset}

4-cijferige numerieke waarde die het aantal bytes vanaf het begin van het bestand aangeeft tot waar de gegevens die betrekking hebben op het specifieke sub‑file zich bevinden. Het eerste byte in het bestand bevindt zich op offset 0.

### setType() {#settype}

2-byte type van subfile, bijvoorbeeld "DL"
