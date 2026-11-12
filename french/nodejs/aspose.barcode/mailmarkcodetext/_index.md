---
title: "MailmarkCodetext"
linktitle: "MailmarkCodetext"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Classe pour l'encodage et le décodage du texte intégré dans le code Royal Mailmark à 4 états."
type: docs
weight: 580
url: /fr/nodejs/aspose.barcode/mailmarkcodetext/
---

## MailmarkCodetext class

Classe pour l'encodage et le décodage du texte intégré dans le code Royal Mailmark à 4 états.

```js
new MailmarkCodetext()
```

Initialise une nouvelle instance de la classe `MailmarkCodetext`.

## Méthodes

| Nom | Description |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Obtient le type de code-barres. |
| [getClass_()](#getclass-) | "0" - Nul ou Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (pour pote |
| [getConstructedCodetext()](#getconstructedcodetext) | Construire le codetext à partir des données Mailmark. |
| [getDestinationPostCodePlusDPS()](#getdestinationpostcodeplusdps) | Le PC et le DP doivent respecter le format PAF. Chaîne de neuf caractères désignant l'international "XY11 " (note les 5 espaces de fin s |
| [getFormat()](#getformat) | "0" – Nul ou Test "1" – Lettre "2" – Grande Lettre |
| [getItemID()](#getitemid) | La valeur maximale est 99999999. |
| [getSupplychainID()](#getsupplychainid) | Les valeurs maximales sont 99 pour Barcode C et 999999 pour Barcode L. |
| [getVersionID()](#getversionid) | Actuellement "1" – Pour le code-barres Mailmark (0 et 2 à 9 ainsi que A à Z réservés pour une utilisation future) |
| [initFromString(constructedCodetext)](#initfromstring) | Initialise les données Mailmark à partir du codetext construit. |
| [setClass_()](#setclass-) | "0" - Nul ou Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (pour pote |
| [setDestinationPostCodePlusDPS()](#setdestinationpostcodeplusdps) | Le PC et le DP doivent respecter le format PAF. Chaîne de neuf caractères désignant l'international "XY11 " (note les 5 espaces de fin s |
| [setFormat()](#setformat) | "0" – Nul ou Test "1" – LettreN "2" – Grande Lettre |
| [setItemID()](#setitemid) | La valeur maximale est 99999999. |
| [setSupplychainID()](#setsupplychainid) | Les valeurs maximales sont 99 pour Barcode C et 999999 pour Barcode L. |
| [setVersionID()](#setversionid) | Actuellement "1" – Pour le code-barres Mailmark (0 et 2 à 9 ainsi que A à Z réservés pour une utilisation future) |

### getBarcodeType() {#getbarcodetype}

Obtient le type de code-barres.

**Returns:** Barcode type.

### getClass_() {#getclass-}

"0" - Nul ou Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (pour une utilisation future potentielle) "5" - Différé (Retail) "6" - Air (Retail) (pour une utilisation future potentielle) "7" - Surface (Retail) (pour une utilisation future potentielle) "8" - Premium (Network Access) "9" - Standard (Network Access)

### getConstructedCodetext() {#getconstructedcodetext}

Construire le codetext à partir des données Mailmark.

**Returns:** Constructed codetext

### getDestinationPostCodePlusDPS() {#getdestinationpostcodeplusdps}

Le PC et le DP doivent respecter le format PAF. Chaîne de neuf caractères désignant l'international "XY11 " (note les 5 espaces de fin) ou un motif de caractères désignant un code de tri domestique. Un code de tri domestique se compose d'un code postal sortant, d'un code postal entrant et d'un suffixe de point de livraison.

### getFormat() {#getformat}

"0" – Nul ou Test "1" – Lettre "2" – Grande Lettre

### getItemID() {#getitemid}

La valeur maximale est 99999999.

### getSupplychainID() {#getsupplychainid}

Les valeurs maximales sont 99 pour Barcode C et 999999 pour Barcode L.

### getVersionID() {#getversionid}

Actuellement "1" – Pour le code-barres Mailmark (0 et 2 à 9 ainsi que A à Z réservés pour une utilisation future)

### initFromString(constructedCodetext) {#initfromstring}

Initialise les données Mailmark à partir du codetext construit.

| Paramètre | Description |
| --- | --- |
| constructedCodetext | Codetext construit. |

### setClass_() {#setclass-}

"0" - Nul ou Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (pour une utilisation future potentielle) "5" - Différé (Retail) "6" - Air (Retail) (pour une utilisation future potentielle) "7" - Surface (Retail) (pour une utilisation future potentielle) "8" - Premium (Network Access) "9" - Standard (Network Access)

### setDestinationPostCodePlusDPS() {#setdestinationpostcodeplusdps}

Le PC et le DP doivent respecter le format PAF. Chaîne de neuf caractères désignant l'international "XY11 " (note les 5 espaces de fin) ou un motif de caractères désignant un code de tri domestique. Un code de tri domestique se compose d'un code postal sortant, d'un code postal entrant et d'un suffixe de point de livraison.

### setFormat() {#setformat}

"0" – Nul ou Test "1" – LettreN "2" – Grande Lettre

### setItemID() {#setitemid}

La valeur maximale est 99999999.

### setSupplychainID() {#setsupplychainid}

Les valeurs maximales sont 99 pour Barcode C et 999999 pour Barcode L.

### setVersionID() {#setversionid}

Actuellement "1" – Pour le code-barres Mailmark (0 et 2 à 9 ainsi que A à Z réservés pour une utilisation future)
