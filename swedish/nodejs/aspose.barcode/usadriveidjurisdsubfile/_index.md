---
title: "USADriveIdJurisdSubfile"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Klass för jurisdiktionsspecifika fält för USA:s körkort"
type: docs
weight: 950
url: /sv/nodejs/aspose.barcode/usadriveidjurisdsubfile/
---

## USADriveIdJurisdSubfile class

Klass för jurisdiktionsspecifika fält för USA:s körkort

```js
new USADriveIdJurisdSubfile()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addOrReplace(id, value)](#addorreplace) | Lägger till ett nytt DataElement med den angivna identifieraren och värdet, eller ersätter det befintliga elementet om en post med samma |
| [addOrReplaceNode(node)](#addorreplacenode) | Lägger till nytt DataElement eller ersätter det om ElementID redan finns. |
| [clear()](#clear) | Rensar alla dataelement |
| [findDataElement(id, isOpenOrCreate)](#finddataelement) | Söker efter dataelement med 3‑bokstavig ID |
| [get(indexOrId)](#get) | Hämtar ett dataelement efter dess index eller 3‑bokstavigt ID. |
| [insert(index, node)](#insert) | Infogar det angivna DataElementet på det givna indexet. Om ett DataElement med samma ElementID redan finns, kommer det att ... |
| [remove(indexOrId)](#remove) | Försöker ta bort ett element efter dess index eller 3‑bokstavigt ID. |
| [set(indexOrId, value)](#set) | Ställer in ett dataelement efter dess index eller 3‑bokstavigt ID. |
| [size()](#size) | Returnerar antalet dataelement |

### addOrReplace(id, value) {#addorreplace}

Lägger till ett nytt DataElement med den angivna identifieraren och värdet, eller ersätter det befintliga elementet om en post med samma ElementID redan finns.

| Parameter | Beskrivning |
| --- | --- |
| id | En 3‑bokstavig identifierare som unikt specificerar det jurisdiktionsrelaterade dataelementet. |
| värde | Textvärdet som tilldelas dataelementet; detta värde kommer att skriva över det befintliga om elementet redan finns. |

**Returns:** The DataElement instance that was added to the collection or updated in place.

### addOrReplaceNode(node) {#addorreplacenode}

Lägger till nytt DataElement eller ersätter det om ElementID redan finns.

| Parameter | Beskrivning |
| --- | --- |
| node | DataElement att lägga till |

**Returns:** Added/replaced data element

### clear() {#clear}

Rensar alla dataelement

### findDataElement(id, isOpenOrCreate) {#finddataelement}

Söker efter dataelement med 3‑bokstavig ID

| Parameter | Beskrivning |
| --- | --- |
| id | 3‑bokstavig ID |
| isOpenOrCreate | Om true, kommer det att skapas om det inte hittas. |

**Returns:** Found data element

### get(indexOrId) {#get}

Hämtar ett dataelement efter dess index eller 3‑bokstavigt ID.

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| indexOrId | number\ | string | Heltalsindex eller 3‑bokstavigt element‑ID. |

**Returns:** DataElement — Corresponding data element.

### insert(index, node) {#insert}

Infogar det angivna DataElementet på det givna indexet. Om ett DataElement med samma ElementID redan finns, kommer det att ersättas.

| Parameter | Beskrivning |
| --- | --- |
| index | Det nollbaserade indexet där elementet ska infogas. |
| node | DataElement‑instansen att infoga eller ersätta på målpositionen. |

**Returns:** The DataElement that was inserted or used to replace an existing entry.

### remove(indexOrId) {#remove}

Försöker ta bort ett element efter dess index eller 3‑bokstavigt ID.

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| indexOrId | number\ | string | Heltalsindex eller 3‑bokstavigt element‑ID. |

**Returns:** boolean — true if the element was removed; otherwise, false.

### set(indexOrId, value) {#set}

Ställer in ett dataelement efter dess index eller 3‑bokstavigt ID.

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| indexOrId | number\ | string | Heltalsindex eller 3‑bokstavigt element‑ID. |
| värde | DataElement | Dataelement att ställa in. |

### size() {#size}

Returnerar antalet dataelement
