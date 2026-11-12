---
title: "USADriveIdJurisdSubfile"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Classe pour les champs spécifiques à la juridiction pour le permis de conduire américain (USA DL)."
type: docs
weight: 950
url: /fr/nodejs/aspose.barcode/usadriveidjurisdsubfile/
---

## USADriveIdJurisdSubfile class

Classe pour les champs spécifiques à la juridiction pour le permis de conduire américain (USA DL).

```js
new USADriveIdJurisdSubfile()
```

## Méthodes

| Nom | Description |
| --- | --- |
| [addOrReplace(id, value)](#addorreplace) | Ajoute un nouveau DataElement avec l'identifiant et la valeur spécifiés, ou remplace l'élément existant si une entrée avec le sa |
| [addOrReplaceNode(node)](#addorreplacenode) | Ajoute un nouveau DataElement ou le remplace si ElementID existe déjà. |
| [clear()](#clear) | Efface tous les éléments de données |
| [findDataElement(id, isOpenOrCreate)](#finddataelement) | Recherche l'élément de données par identifiant de 3 lettres |
| [get(indexOrId)](#get) | Obtient un élément de données par son index ou son ID de 3 lettres. |
| [insert(index, node)](#insert) | Insère le DataElement spécifié à l'index donné. Si un DataElement avec le même ElementID existe déjà, il sera b |
| [remove(indexOrId)](#remove) | Essaie de supprimer un élément par son index ou son ID de 3 lettres. |
| [set(indexOrId, value)](#set) | Définit un élément de données par son index ou son ID de 3 lettres. |
| [size()](#size) | Retourne le nombre d'éléments de données |

### addOrReplace(id, value) {#addorreplace}

Ajoute un nouveau DataElement avec l'identifiant et la valeur spécifiés, ou remplace l'élément existant si une entrée avec le même ElementID est déjà présente.

| Paramètre | Description |
| --- | --- |
| id | Un identifiant de 3 lettres qui spécifie de manière unique l'élément de données lié à la juridiction. |
| valeur | La valeur texte assignée à l'élément de données ; cette valeur écrasera celle existante si l'élément existe déjà. |

**Returns:** The DataElement instance that was added to the collection or updated in place.

### addOrReplaceNode(node) {#addorreplacenode}

Ajoute un nouveau DataElement ou le remplace si ElementID existe déjà.

| Paramètre | Description |
| --- | --- |
| node | DataElement à ajouter |

**Returns:** Added/replaced data element

### clear() {#clear}

Efface tous les éléments de données

### findDataElement(id, isOpenOrCreate) {#finddataelement}

Recherche l'élément de données par identifiant de 3 lettres

| Paramètre | Description |
| --- | --- |
| id | id de 3 lettres |
| isOpenOrCreate | Si vrai, il sera créé s'il n'est pas trouvé |

**Returns:** Found data element

### get(indexOrId) {#get}

Obtient un élément de données par son index ou son ID de 3 lettres.

| Paramètre | Type | Description |
| --- | --- | --- |
| indexOrId | number\ | chaîne | Index entier ou ID d'élément de 3 lettres. |

**Returns:** DataElement — Corresponding data element.

### insert(index, node) {#insert}

Insère le DataElement spécifié à l'index donné. Si un DataElement avec le même ElementID existe déjà, il sera remplacé.

| Paramètre | Description |
| --- | --- |
| index | L'index basé sur zéro à laquelle l'élément doit être inséré. |
| node | L'instance DataElement à insérer ou remplacer à la position cible. |

**Returns:** The DataElement that was inserted or used to replace an existing entry.

### remove(indexOrId) {#remove}

Essaie de supprimer un élément par son index ou son ID de 3 lettres.

| Paramètre | Type | Description |
| --- | --- | --- |
| indexOrId | number\ | chaîne | Index entier ou ID d'élément de 3 lettres. |

**Returns:** boolean — true if the element was removed; otherwise, false.

### set(indexOrId, value) {#set}

Définit un élément de données par son index ou son ID de 3 lettres.

| Paramètre | Type | Description |
| --- | --- | --- |
| indexOrId | number\ | chaîne | Index entier ou ID d'élément de 3 lettres. |
| valeur | DataElement | Élément de données à définir. |

### size() {#size}

Retourne le nombre d'éléments de données
