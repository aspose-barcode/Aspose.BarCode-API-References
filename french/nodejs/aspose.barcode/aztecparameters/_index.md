---
title: "AztecParameters"
linktitle: "AztecParameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Paramètres Aztec."
type: docs
weight: 70
url: /fr/nodejs/aspose.barcode/aztecparameters/
---

## AztecParameters class

Paramètres Aztec.

```js
new AztecParameters()
```

## Méthodes

| Nom | Description |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Ratio hauteur/largeur du module de code-barres 2D. |
| [getAztecEncodeMode()](#getaztecencodemode) ~~(deprecated)~~ | Obtient un mode d'encodage Aztec. Valeur par défaut : Auto. |
| [getAztecErrorLevel()](#getaztecerrorlevel) ~~(deprecated)~~ | Niveau de correction d'erreurs des types de code-barres Aztec. La valeur doit être comprise entre 5 et 95. |
| [getAztecSymbolMode()](#getaztecsymbolmode) ~~(deprecated)~~ | Obtient un mode de symbole Aztec. Valeur par défaut : AztecSymbolMode.Auto. |
| [getECIEncoding()](#geteciencoding) | Obtient l'encodage ECI. Utilisé lorsque AztecEncodeMode est Auto. Valeur par défaut : ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Obtient un mode d'encodage Aztec. Valeur par défaut : Auto. |
| [getErrorLevel()](#geterrorlevel) | Niveau de correction d'erreurs des types de code-barres Aztec. La valeur doit être comprise entre 5 et 95. |
| [getLayersCount()](#getlayerscount) | Obtient le nombre de couches du symbole Aztec. Le nombre de couches doit être compris entre 1 et 3 pour le mode Compact et entre 1 et 3. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | ID de code-barres pour le mode Structured Append du code-barres Aztec. L'ID de code-barres doit être compris entre 1 et le nombre de codes-barres. Valeur par défaut |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Nombre de codes-barres pour le mode Structured Append du code Aztec. Le nombre de codes-barres doit être compris entre 1 et 26. Valeur par défaut |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Identifiant de fichier pour le mode Structured Append du code Aztec (champ optionnel). L'identifiant de fichier ne doit pas contenir d'espaces. Valeur par défaut : |
| [getSymbolMode()](#getsymbolmode) | Obtient un mode de symbole Aztec. Valeur par défaut : AztecSymbolMode.Auto. |
| [isReaderInitialization()](#isreaderinitialization) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [setAspectRatio()](#setaspectratio) | Ratio hauteur/largeur du module de code-barres 2D. |
| [setAztecEncodeMode()](#setaztecencodemode) ~~(deprecated)~~ | Définit un mode d'encodage Aztec. Valeur par défaut : Auto. |
| [setAztecErrorLevel()](#setaztecerrorlevel) ~~(deprecated)~~ | Niveau de correction d'erreurs des types de code-barres Aztec. La valeur doit être comprise entre 5 et 95. |
| [setAztecSymbolMode()](#setaztecsymbolmode) ~~(deprecated)~~ | Définit un mode de symbole Aztec. Valeur par défaut : AztecSymbolMode.Auto. |
| [setECIEncoding()](#seteciencoding) | Définit l'encodage ECI. Utilisé lorsque AztecEncodeMode est Auto. Valeur par défaut : ISO-8859-1 |
| [setEncodeMode(value)](#setencodemode) | Définit un mode d'encodage Aztec. Valeur par défaut : Auto. |
| [setErrorLevel()](#seterrorlevel) | Niveau de correction d'erreurs des types de code-barres Aztec. La valeur doit être comprise entre 5 et 95. |
| [setLayersCount()](#setlayerscount) | Définit le nombre de couches du symbole Aztec. Le nombre de couches doit être compris entre 1 et 3 pour le mode Compact et entre 1 et 3 |
| [setReaderInitialization()](#setreaderinitialization) | Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur. |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | ID de code-barres pour le mode Structured Append du code-barres Aztec. L'ID de code-barres doit être compris entre 1 et le nombre de codes-barres. Valeur par défaut |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | Nombre de codes-barres pour le mode Structured Append du code Aztec. Le nombre de codes-barres doit être compris entre 1 et 26. Valeur par défaut |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | Identifiant de fichier pour le mode Structured Append du code Aztec (champ optionnel). L'identifiant de fichier ne doit pas contenir d'espaces. Valeur par défaut : |
| [setSymbolMode(value)](#setsymbolmode) | Définit un mode de symbole Aztec. Valeur par défaut : AztecSymbolMode.Auto. |
| [toString()](#tostring) | Renvoie une représentation sous forme de chaîne lisible par l'homme de cet `AztecParameters`. |

### getAspectRatio() {#getaspectratio}

Ratio hauteur/largeur du module de code-barres 2D.

### getAztecEncodeMode() {#getaztecencodemode}

> **Deprecated.** See method description for replacement.

Obtient un mode d'encodage Aztec. Valeur par défaut : Auto.

### getAztecErrorLevel() {#getaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Niveau de correction d'erreurs des types de code-barres Aztec. La valeur doit être comprise entre 5 et 95.

### getAztecSymbolMode() {#getaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Obtient un mode de symbole Aztec. Valeur par défaut : AztecSymbolMode.Auto.

### getECIEncoding() {#geteciencoding}

Obtient l'encodage ECI. Utilisé lorsque AztecEncodeMode est Auto. Valeur par défaut : ISO-8859-1

### getEncodeMode() {#getencodemode}

Obtient un mode d'encodage Aztec. Valeur par défaut : Auto.

**Returns:** a Aztec encode mode.

### getErrorLevel() {#geterrorlevel}

Niveau de correction d'erreurs des types de code-barres Aztec. La valeur doit être comprise entre 5 et 95.

### getLayersCount() {#getlayerscount}

Obtient le nombre de couches du symbole Aztec. Le nombre de couches doit être compris entre 1 et 3 pour le mode Compact et entre 1 et 32 pour le mode Full Range. Valeur par défaut : 0 (auto).

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Identifiant du code-barres pour le mode Structured Append du code Aztec. L'identifiant du code-barres doit être compris entre 1 et le nombre de codes-barres. Valeur par défaut : 0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Nombre de codes-barres pour le mode Structured Append du code Aztec. Le nombre de codes-barres doit être compris entre 1 et 26. Valeur par défaut : 0

### getStructuredAppendFileId() {#getstructuredappendfileid}

Identifiant de fichier pour le mode Structured Append du code Aztec (champ optionnel). L'identifiant de fichier ne doit pas contenir d'espaces. Valeur par défaut : chaîne vide

### getSymbolMode() {#getsymbolmode}

Obtient un mode de symbole Aztec. Valeur par défaut : AztecSymbolMode.Auto.

**Returns:** a Aztec Symbol mode.

### isReaderInitialization() {#isreaderinitialization}

Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur.

### setAspectRatio() {#setaspectratio}

Ratio hauteur/largeur du module de code-barres 2D.

### setAztecEncodeMode() {#setaztecencodemode}

> **Deprecated.** See method description for replacement.

Définit un mode d'encodage Aztec. Valeur par défaut : Auto.

### setAztecErrorLevel() {#setaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Niveau de correction d'erreurs des types de code-barres Aztec. La valeur doit être comprise entre 5 et 95.

### setAztecSymbolMode() {#setaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Définit un mode de symbole Aztec. Valeur par défaut : AztecSymbolMode.Auto.

### setECIEncoding() {#seteciencoding}

Définit l'encodage ECI. Utilisé lorsque AztecEncodeMode est Auto. Valeur par défaut : ISO-8859-1

### setEncodeMode(value) {#setencodemode}

Définit un mode d'encodage Aztec. Valeur par défaut : Auto.

| Paramètre | Description |
| --- | --- |
| valeur | un mode d'encodage Aztec. |

### setErrorLevel() {#seterrorlevel}

Niveau de correction d'erreurs des types de code-barres Aztec. La valeur doit être comprise entre 5 et 95.

### setLayersCount() {#setlayerscount}

Définit le nombre de couches du symbole Aztec. Le nombre de couches doit être compris entre 1 et 3 pour le mode Compact et entre 1 et 32 pour le mode Full Range. Valeur par défaut : 0 (auto).

### setReaderInitialization() {#setreaderinitialization}

Utilisé pour indiquer au lecteur d'interpréter les données contenues dans le symbole comme une programmation pour l'initialisation du lecteur.

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

Identifiant du code-barres pour le mode Structured Append du code Aztec. L'identifiant du code-barres doit être compris entre 1 et le nombre de codes-barres. Valeur par défaut : 0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

Nombre de codes-barres pour le mode Structured Append du code Aztec. Le nombre de codes-barres doit être compris entre 1 et 26. Valeur par défaut : 0

### setStructuredAppendFileId() {#setstructuredappendfileid}

Identifiant de fichier pour le mode Structured Append du code Aztec (champ optionnel). L'identifiant de fichier ne doit pas contenir d'espaces. Valeur par défaut : chaîne vide

### setSymbolMode(value) {#setsymbolmode}

Définit un mode de symbole Aztec. Valeur par défaut : AztecSymbolMode.Auto.

| Paramètre | Description |
| --- | --- |
| valeur | un mode de symbole Aztec. |

### toString() {#tostring}

Renvoie une représentation sous forme de chaîne lisible par l'homme de cet `AztecParameters`.

**Returns:** A string that represents this `AztecParameters`.
