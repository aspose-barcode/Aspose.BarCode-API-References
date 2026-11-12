---
title: "USADriveIdJurisdSubfile"
linktitle: "USADriveIdJurisdSubfile"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Clase para campos específicos de jurisdicción para USA DL"
type: docs
weight: 950
url: /es/nodejs/aspose.barcode/usadriveidjurisdsubfile/
---

## USADriveIdJurisdSubfile class

Clase para campos específicos de jurisdicción para USA DL

```js
new USADriveIdJurisdSubfile()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addOrReplace(id, value)](#addorreplace) | Agrega un nuevo DataElement con el identificador y valor especificados, o reemplaza el elemento existente si una entrada con el sa |
| [addOrReplaceNode(node)](#addorreplacenode) | Agrega un nuevo DataElement o lo reemplaza si ElementID ya existe. |
| [clear()](#clear) | Borra todos los elementos de datos |
| [findDataElement(id, isOpenOrCreate)](#finddataelement) | Busca el elemento de datos por id de 3 letras |
| [get(indexOrId)](#get) | Obtiene un elemento de datos por su índice o ID de 3 letras. |
| [insert(index, node)](#insert) | Inserta el DataElement especificado en el índice dado. Si ya existe un DataElement con el mismo ElementID, será b |
| [remove(indexOrId)](#remove) | Intenta eliminar un elemento por su índice o ID de 3 letras. |
| [set(indexOrId, value)](#set) | Establece un elemento de datos por su índice o ID de 3 letras. |
| [size()](#size) | Devuelve el número de elementos de datos |

### addOrReplace(id, value) {#addorreplace}

Agrega un nuevo DataElement con el identificador y valor especificados, o reemplaza el elemento existente si ya existe una entrada con el mismo ElementID.

| Parámetro | Descripción |
| --- | --- |
| id | Un identificador de 3 letras que especifica de forma única el elemento de datos relacionado con la jurisdicción. |
| valor | El valor de texto asignado al elemento de datos; este valor sobrescribirá el existente si el elemento ya existe. |

**Returns:** The DataElement instance that was added to the collection or updated in place.

### addOrReplaceNode(node) {#addorreplacenode}

Agrega un nuevo DataElement o lo reemplaza si ElementID ya existe.

| Parámetro | Descripción |
| --- | --- |
| node | DataElement a agregar |

**Returns:** Added/replaced data element

### clear() {#clear}

Borra todos los elementos de datos

### findDataElement(id, isOpenOrCreate) {#finddataelement}

Busca el elemento de datos por id de 3 letras

| Parámetro | Descripción |
| --- | --- |
| id | id de 3 letras |
| isOpenOrCreate | Si es verdadero, se creará si no se encuentra |

**Returns:** Found data element

### get(indexOrId) {#get}

Obtiene un elemento de datos por su índice o ID de 3 letras.

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| indexOrId | number\ | string | Índice entero o ID de elemento de 3 letras. |

**Returns:** DataElement — Corresponding data element.

### insert(index, node) {#insert}

Inserta el DataElement especificado en el índice dado. Si ya existe un DataElement con el mismo ElementID, será reemplazado.

| Parámetro | Descripción |
| --- | --- |
| índice | El índice basado en cero en el que se debe insertar el elemento. |
| node | La instancia de DataElement a insertar o reemplazar en la posición objetivo. |

**Returns:** The DataElement that was inserted or used to replace an existing entry.

### remove(indexOrId) {#remove}

Intenta eliminar un elemento por su índice o ID de 3 letras.

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| indexOrId | number\ | string | Índice entero o ID de elemento de 3 letras. |

**Returns:** boolean — true if the element was removed; otherwise, false.

### set(indexOrId, value) {#set}

Establece un elemento de datos por su índice o ID de 3 letras.

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| indexOrId | number\ | string | Índice entero o ID de elemento de 3 letras. |
| valor | DataElement | Elemento de datos para establecer. |

### size() {#size}

Devuelve el número de elementos de datos
