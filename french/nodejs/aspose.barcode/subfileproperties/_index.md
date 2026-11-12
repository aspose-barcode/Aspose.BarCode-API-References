---
title: "SubfileProperties"
linktitle: "SubfileProperties"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Les propriétés du sous‑fichier USA DL, le décalage et la longueur sont définis automatiquement."
type: docs
weight: 890
url: /fr/nodejs/aspose.barcode/subfileproperties/
---

## SubfileProperties class

Les propriétés du sous‑fichier USA DL, le décalage et la longueur sont définis automatiquement.

```js
new SubfileProperties()
```

## Méthodes

| Nom | Description |
| --- | --- |
| [getLength()](#getlength) | 4 Ces octets contiennent une valeur numérique à 4 chiffres qui spécifie la longueur du sous-fichier en octets.Le terminateur de segment m |
| [getOffset()](#getoffset) | Valeur numérique à 4 chiffres qui spécifie le nombre d'octets depuis le début du fichier jusqu'à l'endroit où les données se rapportent |
| [getType()](#gettype) | Type de sous-fichier de 2 octets, comme "DL" |
| [setLength()](#setlength) | 4 Ces octets contiennent une valeur numérique à 4 chiffres qui spécifie la longueur du sous-fichier en octets.Le terminateur de segment m |
| [setOffset()](#setoffset) | Valeur numérique à 4 chiffres qui spécifie le nombre d'octets depuis le début du fichier jusqu'à l'endroit où les données se rapportent |
| [setType()](#settype) | Type de sous-fichier de 2 octets, comme "DL" |

### getLength() {#getlength}

4 Ces octets contiennent une valeur numérique à 4 chiffres qui spécifie la longueur du sous-fichier en octets.Le terminateur de segment doit être inclus dans le calcul de la longueur du sous-fichier.Un terminateur de segment = 1. Chaque sous-fichier doit commencer par le type de sous-fichier à deux caractères et ces deux caractères doivent également être inclus dans la longueur.

### getOffset() {#getoffset}

Valeur numérique à 4 chiffres qui spécifie le nombre d'octets depuis le début du fichier jusqu'à l'endroit où les données liées au sous-fichier particulier sont situées.Le premier octet du fichier se trouve à l'offset 0.

### getType() {#gettype}

Type de sous-fichier de 2 octets, comme "DL"

### setLength() {#setlength}

4 Ces octets contiennent une valeur numérique à 4 chiffres qui spécifie la longueur du sous-fichier en octets.Le terminateur de segment doit être inclus dans le calcul de la longueur du sous-fichier.Un terminateur de segment = 1. Chaque sous-fichier doit commencer par le type de sous-fichier à deux caractères et ces deux caractères doivent également être inclus dans la longueur.

### setOffset() {#setoffset}

Valeur numérique à 4 chiffres qui spécifie le nombre d'octets depuis le début du fichier jusqu'à l'endroit où les données liées au sous-fichier particulier sont situées.Le premier octet du fichier se trouve à l'offset 0.

### setType() {#settype}

Type de sous-fichier de 2 octets, comme "DL"
