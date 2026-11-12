---
title: "SubfileProperties"
linktitle: "SubfileProperties"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "USA‑DL-Unterdateieigenschaften, Offset und Länge werden automatisch gesetzt."
type: docs
weight: 890
url: /de/nodejs/aspose.barcode/subfileproperties/
---

## SubfileProperties class

USA‑DL-Unterdateieigenschaften, Offset und Länge werden automatisch gesetzt.

```js
new SubfileProperties()
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getLength()](#getlength) | 4 Diese Bytes enthalten einen 4-stelligen numerischen Wert, der die Länge der Subdatei in Bytes angibt. Der Segmentterminator m |
| [getOffset()](#getoffset) | 4-stelliger numerischer Wert, der die Anzahl der Bytes vom Kopf oder Beginn der Datei bis zu dem Ort angibt, an dem die Daten liegen. |
| [getType()](#gettype) | 2-Byte-Typ der Subdatei, z. B. "DL" |
| [setLength()](#setlength) | 4 Diese Bytes enthalten einen 4-stelligen numerischen Wert, der die Länge der Subdatei in Bytes angibt. Der Segmentterminator m |
| [setOffset()](#setoffset) | 4-stelliger numerischer Wert, der die Anzahl der Bytes vom Kopf oder Beginn der Datei bis zu dem Ort angibt, an dem die Daten liegen. |
| [setType()](#settype) | 2-Byte-Typ der Subdatei, z. B. "DL" |

### getLength() {#getlength}

4 Diese Bytes enthalten einen 4-stelligen numerischen Wert, der die Länge der Subdatei in Bytes angibt. Der Segmentterminator muss bei der Berechnung der Länge der Subdatei berücksichtigt werden. Ein Segmentterminator = 1. Jede Subdatei muss mit dem zweistelligen Subdatei-Typ beginnen und diese beiden Zeichen müssen ebenfalls in die Länge einbezogen werden.

### getOffset() {#getoffset}

4-stelliger numerischer Wert, der die Anzahl der Bytes vom Kopf oder Beginn der Datei bis zu dem Ort angibt, an dem die Daten der jeweiligen Subdatei gespeichert sind. Das erste Byte in der Datei befindet sich bei Offset 0.

### getType() {#gettype}

2-Byte-Typ der Subdatei, z. B. "DL"

### setLength() {#setlength}

4 Diese Bytes enthalten einen 4-stelligen numerischen Wert, der die Länge der Subdatei in Bytes angibt. Der Segmentterminator muss bei der Berechnung der Länge der Subdatei berücksichtigt werden. Ein Segmentterminator = 1. Jede Subdatei muss mit dem zweistelligen Subdatei-Typ beginnen und diese beiden Zeichen müssen ebenfalls in die Länge einbezogen werden.

### setOffset() {#setoffset}

4-stelliger numerischer Wert, der die Anzahl der Bytes vom Kopf oder Beginn der Datei bis zu dem Ort angibt, an dem die Daten der jeweiligen Subdatei gespeichert sind. Das erste Byte in der Datei befindet sich bei Offset 0.

### setType() {#settype}

2-Byte-Typ der Subdatei, z. B. "DL"
