---
title: "USADriveIdJurisdSubfile"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Klasse voor jurisdictiespecifieke velden voor USA-DL"
type: docs
weight: 950
url: /nl/nodejs/aspose.barcode/usadriveidjurisdsubfile/
---

## USADriveIdJurisdSubfile class

Klasse voor jurisdictiespecifieke velden voor USA-DL

```js
new USADriveIdJurisdSubfile()
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addOrReplace(id, value)](#addorreplace) | Voegt een nieuw DataElement toe met de opgegeven identifier en waarde, of vervangt het bestaande element als er een invoer is met de sa |
| [addOrReplaceNode(node)](#addorreplacenode) | Voegt een nieuw DataElement toe of vervangt het als ElementID al bestaat. |
| [clear()](#clear) | Wis alle data-elementen |
| [findDataElement(id, isOpenOrCreate)](#finddataelement) | Zoekt naar data-element op 3-letterige id |
| [get(indexOrId)](#get) | Haalt een data-element op via zijn index of 3-letterige ID. |
| [insert(index, node)](#insert) | Voegt het opgegeven DataElement in op de opgegeven index. Als een DataElement met dezelfde ElementID al bestaat, zal het b |
| [remove(indexOrId)](#remove) | Probeert een element te verwijderen via zijn index of 3-letterige ID. |
| [set(indexOrId, value)](#set) | Stelt een data-element in via zijn index of 3-letterige ID. |
| [size()](#size) | Retourneert het aantal data-elementen |

### addOrReplace(id, value) {#addorreplace}

Voegt een nieuw DataElement toe met de opgegeven identifier en waarde, of vervangt het bestaande element als er al een invoer is met dezelfde ElementID.

| Parameter | Beschrijving |
| --- | --- |
| id | Een 3-letterige identifier die het jurisdictiegerelateerde data-element uniek specificeert. |
| waarde | De tekstwaarde die aan het data-element is toegewezen; deze waarde zal de bestaande overschrijven als het element al bestaat. |

**Returns:** The DataElement instance that was added to the collection or updated in place.

### addOrReplaceNode(node) {#addorreplacenode}

Voegt een nieuw DataElement toe of vervangt het als ElementID al bestaat.

| Parameter | Beschrijving |
| --- | --- |
| node | DataElement om toe te voegen |

**Returns:** Added/replaced data element

### clear() {#clear}

Wis alle data-elementen

### findDataElement(id, isOpenOrCreate) {#finddataelement}

Zoekt naar data-element op 3-letterige id

| Parameter | Beschrijving |
| --- | --- |
| id | 3-letterige id |
| isOpenOrCreate | Indien true, wordt het aangemaakt als het niet wordt gevonden |

**Returns:** Found data element

### get(indexOrId) {#get}

Haalt een data-element op via zijn index of 3-letterige ID.

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| indexOrId | number\ | string | Geheel getal index of 3-letterig element-ID. |

**Returns:** DataElement — Corresponding data element.

### insert(index, node) {#insert}

Voegt het opgegeven DataElement in op de opgegeven index. Als een DataElement met dezelfde ElementID al bestaat, wordt het vervangen.

| Parameter | Beschrijving |
| --- | --- |
| index | De nulgebaseerde index waarop het element moet worden ingevoegd. |
| node | De DataElement-instantie om in te voegen of te vervangen op de doelpositie. |

**Returns:** The DataElement that was inserted or used to replace an existing entry.

### remove(indexOrId) {#remove}

Probeert een element te verwijderen via zijn index of 3-letterige ID.

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| indexOrId | number\ | string | Geheel getal index of 3-letterig element-ID. |

**Returns:** boolean — true if the element was removed; otherwise, false.

### set(indexOrId, value) {#set}

Stelt een data-element in via zijn index of 3-letterige ID.

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| indexOrId | number\ | string | Geheel getal index of 3-letterig element-ID. |
| waarde | DataElement | Data‑element om in te stellen. |

### size() {#size}

Retourneert het aantal data-elementen
