---
title: "USADriveIdJurisdSubfile"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Klasse für jurisdictionsspezifische Felder für USA DL"
type: docs
weight: 950
url: /de/nodejs/aspose.barcode/usadriveidjurisdsubfile/
---

## USADriveIdJurisdSubfile class

Klasse für jurisdictionsspezifische Felder für USA DL

```js
new USADriveIdJurisdSubfile()
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addOrReplace(id, value)](#addorreplace) | Fügt ein neues DataElement mit dem angegebenen Bezeichner und Wert hinzu oder ersetzt das vorhandene Element, wenn ein Eintrag mit dem sa |
| [addOrReplaceNode(node)](#addorreplacenode) | Fügt ein neues DataElement hinzu oder ersetzt es, wenn die ElementID bereits existiert. |
| [clear()](#clear) | Löscht alle DataElements |
| [findDataElement(id, isOpenOrCreate)](#finddataelement) | Sucht nach DataElement anhand einer 3‑Buchstaben‑ID. |
| [get(indexOrId)](#get) | Ruft ein DataElement anhand seines Index oder einer 3‑Buchstaben‑ID ab. |
| [insert(index, node)](#insert) | Fügt das angegebene DataElement an dem angegebenen Index ein. Wenn ein DataElement mit derselben ElementID bereits existiert, wird es b |
| [remove(indexOrId)](#remove) | Versucht, ein Element anhand seines Index oder einer 3‑Buchstaben‑ID zu entfernen. |
| [set(indexOrId, value)](#set) | Setzt ein DataElement anhand seines Index oder einer 3‑Buchstaben‑ID. |
| [size()](#size) | Gibt die Anzahl der DataElements zurück |

### addOrReplace(id, value) {#addorreplace}

Fügt ein neues DataElement mit dem angegebenen Bezeichner und Wert hinzu oder ersetzt das vorhandene Element, wenn ein Eintrag mit derselben ElementID bereits vorhanden ist.

| Parameter | Beschreibung |
| --- | --- |
| ID | Ein 3‑Buchstaben‑Bezeichner, der das jurisdictionsbezogene DataElement eindeutig spezifiziert. |
| Wert | Der Textwert, der dem DataElement zugewiesen wird; dieser Wert überschreibt den vorhandenen, wenn das Element bereits existiert. |

**Returns:** The DataElement instance that was added to the collection or updated in place.

### addOrReplaceNode(node) {#addorreplacenode}

Fügt ein neues DataElement hinzu oder ersetzt es, wenn die ElementID bereits existiert.

| Parameter | Beschreibung |
| --- | --- |
| Knoten | DataElement zum Hinzufügen |

**Returns:** Added/replaced data element

### clear() {#clear}

Löscht alle DataElements

### findDataElement(id, isOpenOrCreate) {#finddataelement}

Sucht nach DataElement anhand einer 3‑Buchstaben‑ID.

| Parameter | Beschreibung |
| --- | --- |
| ID | 3‑Buchstaben‑ID |
| isOpenOrCreate | Wenn true, wird es erstellt, falls es nicht gefunden wird. |

**Returns:** Found data element

### get(indexOrId) {#get}

Ruft ein DataElement anhand seines Index oder einer 3‑Buchstaben‑ID ab.

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| indexOrId | number\ | Zeichenkette | Ganzzahliger Index oder 3‑Buchstaben‑Element‑ID. |

**Returns:** DataElement — Corresponding data element.

### insert(index, node) {#insert}

Fügt das angegebene DataElement an dem angegebenen Index ein. Wenn ein DataElement mit derselben ElementID bereits existiert, wird es ersetzt.

| Parameter | Beschreibung |
| --- | --- |
| Index | Der nullbasierte Index, an dem das Element eingefügt werden soll. |
| Knoten | Die DataElement‑Instanz, die an der Zielposition eingefügt oder ersetzt werden soll. |

**Returns:** The DataElement that was inserted or used to replace an existing entry.

### remove(indexOrId) {#remove}

Versucht, ein Element anhand seines Index oder einer 3‑Buchstaben‑ID zu entfernen.

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| indexOrId | number\ | Zeichenkette | Ganzzahliger Index oder 3‑Buchstaben‑Element‑ID. |

**Returns:** boolean — true if the element was removed; otherwise, false.

### set(indexOrId, value) {#set}

Setzt ein DataElement anhand seines Index oder einer 3‑Buchstaben‑ID.

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| indexOrId | number\ | Zeichenkette | Ganzzahliger Index oder 3‑Buchstaben‑Element‑ID. |
| Wert | DataElement | Datenelement zum Festlegen. |

### size() {#size}

Gibt die Anzahl der DataElements zurück
