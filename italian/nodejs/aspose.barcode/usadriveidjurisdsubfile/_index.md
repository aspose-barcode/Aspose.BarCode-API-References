---
title: "USADriveIdJurisdSubfile"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Classe per i campi specifici della giurisdizione per la patente USA"
type: docs
weight: 950
url: /it/nodejs/aspose.barcode/usadriveidjurisdsubfile/
---

## USADriveIdJurisdSubfile class

Classe per i campi specifici della giurisdizione per la patente USA

```js
new USADriveIdJurisdSubfile()
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addOrReplace(id, value)](#addorreplace) | Aggiunge un nuovo DataElement con l'identificatore e il valore specificati, o sostituisce l'elemento esistente se una voce con il sa |
| [addOrReplaceNode(node)](#addorreplacenode) | Aggiunge un nuovo DataElement o lo sostituisce se ElementID esiste già. |
| [clear()](#clear) | Cancella tutti gli elementi dati |
| [findDataElement(id, isOpenOrCreate)](#finddataelement) | Cerca l'elemento dati per ID a 3 lettere |
| [get(indexOrId)](#get) | Ottiene un elemento dati per il suo indice o per l'ID a 3 lettere. |
| [insert(index, node)](#insert) | Inserisce il DataElement specificato all'indice indicato. Se un DataElement con lo stesso ElementID esiste già, verrà b |
| [remove(indexOrId)](#remove) | Prova a rimuovere un elemento per il suo indice o per l'ID a 3 lettere. |
| [set(indexOrId, value)](#set) | Imposta un elemento dati per il suo indice o per l'ID a 3 lettere. |
| [size()](#size) | Restituisce il numero di elementi dati |

### addOrReplace(id, value) {#addorreplace}

Aggiunge un nuovo DataElement con l'identificatore e il valore specificati, o sostituisce l'elemento esistente se una voce con lo stesso ElementID è già presente.

| Parametro | Descrizione |
| --- | --- |
| id | Un identificatore a 3 lettere che specifica in modo univoco l'elemento dati relativo alla giurisdizione. |
| valore | Il valore di testo assegnato all'elemento dati; questo valore sovrascriverà quello esistente se l'elemento è già presente. |

**Returns:** The DataElement instance that was added to the collection or updated in place.

### addOrReplaceNode(node) {#addorreplacenode}

Aggiunge un nuovo DataElement o lo sostituisce se ElementID esiste già.

| Parametro | Descrizione |
| --- | --- |
| node | DataElement da aggiungere |

**Returns:** Added/replaced data element

### clear() {#clear}

Cancella tutti gli elementi dati

### findDataElement(id, isOpenOrCreate) {#finddataelement}

Cerca l'elemento dati per ID a 3 lettere

| Parametro | Descrizione |
| --- | --- |
| id | ID a 3 lettere |
| isOpenOrCreate | Se true, verrà creato se non trovato. |

**Returns:** Found data element

### get(indexOrId) {#get}

Ottiene un elemento dati per il suo indice o per l'ID a 3 lettere.

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indexOrId | number\ | string | Indice intero o ID elemento a 3 lettere. |

**Returns:** DataElement — Corresponding data element.

### insert(index, node) {#insert}

Inserisce il DataElement specificato all'indice indicato. Se un DataElement con lo stesso ElementID esiste già, verrà sostituito.

| Parametro | Descrizione |
| --- | --- |
| index | L'indice basato su zero al quale l'elemento dovrebbe essere inserito. |
| node | L'istanza DataElement da inserire o sostituire nella posizione di destinazione. |

**Returns:** The DataElement that was inserted or used to replace an existing entry.

### remove(indexOrId) {#remove}

Prova a rimuovere un elemento per il suo indice o per l'ID a 3 lettere.

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indexOrId | number\ | string | Indice intero o ID elemento a 3 lettere. |

**Returns:** boolean — true if the element was removed; otherwise, false.

### set(indexOrId, value) {#set}

Imposta un elemento dati per il suo indice o per l'ID a 3 lettere.

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indexOrId | number\ | string | Indice intero o ID elemento a 3 lettere. |
| valore | DataElement | Elemento dati da impostare. |

### size() {#size}

Restituisce il numero di elementi dati
