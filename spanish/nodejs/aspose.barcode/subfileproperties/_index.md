---
title: "SubfileProperties"
linktitle: "SubfileProperties"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Las propiedades del subarchivo USA DL, desplazamiento y longitud se establecen automáticamente."
type: docs
weight: 890
url: /es/nodejs/aspose.barcode/subfileproperties/
---

## SubfileProperties class

Las propiedades del subarchivo USA DL, desplazamiento y longitud se establecen automáticamente.

```js
new SubfileProperties()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getLength()](#getlength) | 4 Estos bytes contienen un valor numérico de 4 dígitos que especifica la longitud del Subfile en bytes. El terminador de segmento m |
| [getOffset()](#getoffset) | Valor numérico de 4 dígitos que especifica la cantidad de bytes desde el inicio o comienzo del archivo hasta donde se relacionan los datos |
| [getType()](#gettype) | Tipo de subfile de 2 bytes, como "DL" |
| [setLength()](#setlength) | 4 Estos bytes contienen un valor numérico de 4 dígitos que especifica la longitud del Subfile en bytes. El terminador de segmento m |
| [setOffset()](#setoffset) | Valor numérico de 4 dígitos que especifica la cantidad de bytes desde el inicio o comienzo del archivo hasta donde se relacionan los datos |
| [setType()](#settype) | Tipo de subfile de 2 bytes, como "DL" |

### getLength() {#getlength}

4 Estos bytes contienen un valor numérico de 4 dígitos que especifica la longitud del Subfile en bytes. El terminador de segmento debe incluirse al calcular la longitud del subfile. Un terminador de segmento = 1. Cada subfile debe comenzar con el Tipo de Subfile de dos caracteres y estos dos caracteres también deben incluirse en la longitud.

### getOffset() {#getoffset}

Valor numérico de 4 dígitos que especifica la cantidad de bytes desde el inicio o comienzo del archivo hasta donde se encuentran los datos relacionados con el sub-file particular. El primer byte del archivo está ubicado en el desplazamiento 0.

### getType() {#gettype}

Tipo de subfile de 2 bytes, como "DL"

### setLength() {#setlength}

4 Estos bytes contienen un valor numérico de 4 dígitos que especifica la longitud del Subfile en bytes. El terminador de segmento debe incluirse al calcular la longitud del subfile. Un terminador de segmento = 1. Cada subfile debe comenzar con el Tipo de Subfile de dos caracteres y estos dos caracteres también deben incluirse en la longitud.

### setOffset() {#setoffset}

Valor numérico de 4 dígitos que especifica la cantidad de bytes desde el inicio o comienzo del archivo hasta donde se encuentran los datos relacionados con el sub-file particular. El primer byte del archivo está ubicado en el desplazamiento 0.

### setType() {#settype}

Tipo de subfile de 2 bytes, como "DL"
