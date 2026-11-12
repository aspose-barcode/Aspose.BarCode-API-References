---
title: "Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Classe pour l'encodage et le décodage du texte intégré dans le code Royal Mail 2D Mailmark."
type: docs
weight: 570
url: /fr/nodejs/aspose.barcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Classe pour l'encodage et le décodage du texte intégré dans le code Royal Mail 2D Mailmark.

```js
new Mailmark2DCodetext()
```

Crée une instance par défaut de la classe Mailmark2DCodetext.

## Méthodes

| Nom | Description |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Obtient le type de code-barres. |
| [getClass_()](#getclass-) | Identifie la classe de l'élément. Valeurs valides : '1' - 1C (Commerce de détail) '2' - 2C (Commerce de détail) '3' - Economy (Commerce de détail) '5' - Deffere |
| [getConstructedCodetext()](#getconstructedcodetext) | Construire le codetext à partir des données Mailmark. |
| [getCustomerContent()](#getcustomercontent) | Espace optionnel à l'usage du client. Longueur maximale par type : Type 7 : 6 caractères Type 9 : 45 caractères Type 29 : 25 caractères |
| [getCustomerContentEncodeMode()](#getcustomercontentencodemode) | Mode d'encodage du code-barres Datamatrix. Valeur par défaut : DataMatrixEncodeMode.C40. |
| [getDataMatrixType()](#getdatamatrixtype) | Le type Mailmark 2D définit la taille du code-barres Data Matrix. |
| [getDestinationPostCodeAndDPS()](#getdestinationpostcodeanddps) | Contient le code postal de l'adresse de livraison avec DPS. Si intérieur, le code postal/DP contient le nombre suivant de caractères |
| [getInformationTypeID()](#getinformationtypeid) | Identifie la charge utile du code-barres Royal Mail Mailmark pour chaque type de produit. Valeurs valides : '0' - Domestique trié et non trié |
| [getItemID()](#getitemid) | Identifie l'élément unique au sein de l'ID de la chaîne d'approvisionnement. Chaque code-barres Mailmark doit contenir un ID afin qu'il puisse être un |
| [getReturnToSenderPostCode()](#getreturntosenderpostcode) | Contient le code postal Retour à l'expéditeur mais sans DPS. Le CP (sans DPS) doit être conforme à un format PAF®. |
| [getRTSFlag()](#getrtsflag) | Indicateur qui indique le niveau de service Retour à l'expéditeur demandé. |
| [getSupplyChainID()](#getsupplychainid) | Identifie le groupe unique de clients impliqués dans l'envoi. Valeur maximale : 9999999. |
| [getUPUCountryID()](#getupucountryid) | Identifie l'ID de pays UPU. Longueur maximale : 4 caractères. |
| [getVersionID()](#getversionid) | Identifie la version du code-barres en fonction de chaque ID de type d'information. Valeurs valides : actuellement '1'. '0' & '2' à '9' an |
| [initFromString(constructedCodetext)](#initfromstring) | Initialise les données Mailmark à partir du codetext construit. |
| [setClass_(value)](#setclass-) | Identifie la classe de l'élément. Valeurs valides : '1' - 1C (Commerce de détail) '2' - 2C (Commerce de détail) '3' - Economy (Commerce de détail) '5' - Deffere |
| [setCustomerContent(value)](#setcustomercontent) | Espace optionnel à l'usage du client. Longueur maximale par type : Type 7 : 6 caractères Type 9 : 45 caractères Type 29 : 25 caractères |
| [setCustomerContentEncodeMode(value)](#setcustomercontentencodemode) | Mode d'encodage du code-barres Datamatrix. Valeur par défaut : DataMatrixEncodeMode.C40. |
| [setDataMatrixType(value)](#setdatamatrixtype) | Le type Mailmark 2D définit la taille du code-barres Data Matrix. |
| [setDestinationPostCodeAndDPS(value)](#setdestinationpostcodeanddps) | Contient le code postal de l'adresse de livraison avec DPS. Si intérieur, le code postal/DP contient le nombre suivant de caractères |
| [setInformationTypeID(value)](#setinformationtypeid) | Identifie la charge utile du code-barres Royal Mail Mailmark pour chaque type de produit. Valeurs valides : '0' - Domestique trié et non trié |
| [setItemID(value)](#setitemid) | Identifie l'élément unique au sein de l'ID de la chaîne d'approvisionnement. Chaque code-barres Mailmark doit contenir un ID afin qu'il puisse être un |
| [setReturnToSenderPostCode(value)](#setreturntosenderpostcode) | Contient le code postal Retour à l'expéditeur mais sans DPS. Le CP (sans DPS) doit être conforme à un format PAF®. |
| [setRTSFlag()](#setrtsflag) | Indicateur qui indique le niveau de service Retour à l'expéditeur demandé. |
| [setSupplyChainID(value)](#setsupplychainid) | Identifie le groupe unique de clients impliqués dans l'envoi. Valeur maximale : 9999999. |
| [setUPUCountryID(value)](#setupucountryid) | Identifie l'ID de pays UPU. Longueur maximale : 4 caractères. |
| [setVersionID(value)](#setversionid) | Identifie la version du code-barres en fonction de chaque ID de type d'information. Valeurs valides : actuellement '1'. '0' & '2' à '9' an |

### getBarcodeType() {#getbarcodetype}

Obtient le type de code-barres.

**Returns:** Barcode type.

### getClass_() {#getclass-}

Identifie la classe de l'élément. Valeurs valides : '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffered (Retail) '8' - Premium (Network Access) '9' - Standard (Network Access)

**Returns:** class of the item

### getConstructedCodetext() {#getconstructedcodetext}

Construire le codetext à partir des données Mailmark.

**Returns:** Constructed codetext

### getCustomerContent() {#getcustomercontent}

Espace optionnel à l'usage du client. Longueur maximale par type : Type 7 : 6 caractères Type 9 : 45 caractères Type 29 : 25 caractères

**Returns:** Customer content

### getCustomerContentEncodeMode() {#getcustomercontentencodemode}

Mode d'encodage du code-barres Datamatrix. Valeur par défaut : DataMatrixEncodeMode.C40.

**Returns:** Encode mode of Datamatrix barcode.

### getDataMatrixType() {#getdatamatrixtype}

Le type Mailmark 2D définit la taille du code-barres Data Matrix.

**Returns:** Size of Data Matrix barcode

### getDestinationPostCodeAndDPS() {#getdestinationpostcodeanddps}

Contient le code postal de l'adresse de livraison avec DPS. Si intérieur, le code postal/DP comporte le nombre de caractères suivant. Zone (1 ou 2 caractères) District (1 ou 2 caractères) Secteur (1 caractère) Unité (2 caractères) DPS (2 caractères). Le code postal et le DPS doivent être conformes à un format PAF® valide.

**Returns:** the Postcode of the Delivery Address with DPS

### getInformationTypeID() {#getinformationtypeid}

Identifie la charge utile du code-barres Mailmark de Royal Mail pour chaque type de produit. Valeurs valides : '0' - Domestique trié & non trié 'A' - Online Postage 'B' - Franking 'C' - Consolidation

**Returns:** Information type ID

### getItemID() {#getitemid}

Identifie l'élément unique au sein de l'ID de la chaîne d'approvisionnement. Chaque code-barres Mailmark doit contenir un ID afin qu'il puisse être identifié de façon unique pendant au moins 90 jours. Valeur maximale : 99999999.

**Returns:** item within the Supply Chain ID

### getReturnToSenderPostCode() {#getreturntosenderpostcode}

Contient le code postal Retour à l'expéditeur mais sans DPS. Le CP (sans DPS) doit être conforme à un format PAF®.

**Returns:** Return to Sender Post Code but no DPS

### getRTSFlag() {#getrtsflag}

Indicateur qui indique le niveau de service Retour à l'expéditeur demandé.

**Returns:** RTS Flag

### getSupplyChainID() {#getsupplychainid}

Identifie le groupe unique de clients impliqués dans l'envoi. Valeur maximale : 9999999.

**Returns:** Supply chain ID

### getUPUCountryID() {#getupucountryid}

Identifie l'ID de pays UPU. Longueur maximale : 4 caractères.

**Returns:** Country ID

### getVersionID() {#getversionid}

Identifie la version du code-barres en fonction de chaque ID de type d'information. Valeurs valides : actuellement '1'. '0' & '2' à '9' et 'A' à 'Z' réservés pour une utilisation future potentielle.

**Returns:** Version ID

### initFromString(constructedCodetext) {#initfromstring}

Initialise les données Mailmark à partir du codetext construit.

| Paramètre | Description |
| --- | --- |
| constructedCodetext | Codetext construit. |

### setClass_(value) {#setclass-}

Identifie la classe de l'élément. Valeurs valides : '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffered (Retail) '8' - Premium (Network Access) '9' - Standard (Network Access)

| Paramètre | Description |
| --- | --- |
| valeur | classe de l'élément |

### setCustomerContent(value) {#setcustomercontent}

Espace optionnel à l'usage du client. Longueur maximale par type : Type 7 : 6 caractères Type 9 : 45 caractères Type 29 : 25 caractères

| Paramètre | Description |
| --- | --- |
| valeur | Contenu client |

### setCustomerContentEncodeMode(value) {#setcustomercontentencodemode}

Mode d'encodage du code-barres Datamatrix. Valeur par défaut : DataMatrixEncodeMode.C40.

| Paramètre | Description |
| --- | --- |
| valeur | Mode d'encodage du code-barres Datamatrix. |

### setDataMatrixType(value) {#setdatamatrixtype}

Le type Mailmark 2D définit la taille du code-barres Data Matrix.

| Paramètre | Description |
| --- | --- |
| valeur | Taille du code-barres Data Matrix |

### setDestinationPostCodeAndDPS(value) {#setdestinationpostcodeanddps}

Contient le code postal de l'adresse de livraison avec DPS. Si intérieur, le code postal/DP comporte le nombre de caractères suivant. Zone (1 ou 2 caractères) District (1 ou 2 caractères) Secteur (1 caractère) Unité (2 caractères) DPS (2 caractères). Le code postal et le DPS doivent être conformes à un format PAF® valide.

| Paramètre | Description |
| --- | --- |
| valeur | le code postal de l'adresse de livraison avec DPS |

### setInformationTypeID(value) {#setinformationtypeid}

Identifie la charge utile du code-barres Mailmark de Royal Mail pour chaque type de produit. Valeurs valides : '0' - Domestique trié & non trié 'A' - Online Postage 'B' - Franking 'C' - Consolidation

| Paramètre | Description |
| --- | --- |
| valeur | ID du type d'information |

### setItemID(value) {#setitemid}

Identifie l'élément unique au sein de l'ID de la chaîne d'approvisionnement. Chaque code-barres Mailmark doit contenir un ID afin qu'il puisse être identifié de façon unique pendant au moins 90 jours. Valeur maximale : 99999999.

| Paramètre | Description |
| --- | --- |
| valeur | élément au sein de l'ID de la chaîne d'approvisionnement |

### setReturnToSenderPostCode(value) {#setreturntosenderpostcode}

Contient le code postal Retour à l'expéditeur mais sans DPS. Le CP (sans DPS) doit être conforme à un format PAF®.

| Paramètre | Description |
| --- | --- |
| valeur | Code postal Retour à l'expéditeur mais sans DPS |

### setRTSFlag() {#setrtsflag}

Indicateur qui indique le niveau de service Retour à l'expéditeur demandé.

**Returns:** RTS Flag

### setSupplyChainID(value) {#setsupplychainid}

Identifie le groupe unique de clients impliqués dans l'envoi. Valeur maximale : 9999999.

| Paramètre | Description |
| --- | --- |
| valeur | ID de la chaîne d'approvisionnement |

### setUPUCountryID(value) {#setupucountryid}

Identifie l'ID de pays UPU. Longueur maximale : 4 caractères.

| Paramètre | Description |
| --- | --- |
| valeur | ID du pays |

### setVersionID(value) {#setversionid}

Identifie la version du code-barres en fonction de chaque ID de type d'information. Valeurs valides : actuellement '1'. '0' & '2' à '9' et 'A' à 'Z' réservés pour une utilisation future potentielle.

| Paramètre | Description |
| --- | --- |
| valeur | ID de version |
