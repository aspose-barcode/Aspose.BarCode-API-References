---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Paramètres QR."
type: docs
weight: 830
url: /fr/nodejs/aspose.barcode/qrparameters/
---

## QrParameters class

Paramètres QR.

```js
new QrParameters()
```

## Méthodes

| Nom | Description |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Ratio hauteur/largeur du module de code-barres 2D. |
| [getECIEncoding()](#geteciencoding) | Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails sur les références utilisées pour |
| [getEncodeGS1SeparatorInByteMode()](#getencodegs1separatorinbytemode) | Obtient ou définit une valeur indiquant si les caractères spéciaux GS1 doivent être encodés en mode Octet pour les codes QR et RectMicroQR. |
| [getEncodeMode()](#getencodemode) | Type de symbologie QR du mode d'encodage du code-barres. Valeur par défaut : QREncodeMode.Auto. |
| [getErrorLevel()](#geterrorlevel) | Niveau de correction d'erreurs Reed‑Solomon pour les codes QR, MicroQR et RectMicroQR. Du plus bas au plus haut : LevelL, LevelM, LevelQ. |
| [getMicroQRVersion()](#getmicroqrversion) | Version du code MicroQR. De la version M1 à la version M4. Valeur par défaut : MicroQRVersion.Auto. |
| [getQrECIEncoding()](#getqreciencoding) ~~(deprecated)~~ | Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails sur les références utilisées pour |
| [getQrEncodeMode()](#getqrencodemode) | Type de symbologie QR du mode d'encodage du code-barres. Valeur par défaut : QREncodeMode.AUTO. |
| [getQrEncodeType()](#getqrencodetype) ~~(deprecated)~~ | Mode de sélection QR / MicroQR. Sélectionnez ForceQR pour les symboles QR standards, Auto pour MicroQR. |
| [getQrErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Niveau de correction d'erreurs Reed‑Solomon pour le code QR. Du plus bas au plus haut : LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. voir QRError. |
| [getQrVersion()](#getqrversion) ~~(deprecated)~~ | Version du code QR. De Version1 à Version40 pour le code QR et de M1 à M4 pour MicroQr. Valeur par défaut : QRVersion.AUT |
| [getRectMicroQrVersion()](#getrectmicroqrversion) | Version du code RectMicroQR. De la version R7x59 à la version R17x139. Valeur par défaut : RectMicroQRVersion.Auto. |
| [getStructuredAppend()](#getstructuredappend) | Paramètres QR Structured Append. |
| [getVersion()](#getversion) | Version du code QR. De Version1 à Version40. Valeur par défaut : QRVersion.Auto. |
| [setAspectRatio()](#setaspectratio) | Ratio hauteur/largeur du module de code-barres 2D. |
| [setECIEncoding()](#seteciencoding) | Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails sur les références utilisées pour |
| [setEncodeGS1SeparatorInByteMode(value)](#setencodegs1separatorinbytemode) | Obtient ou définit une valeur indiquant si les caractères spéciaux GS1 doivent être encodés en mode Octet pour les codes QR et RectMicroQR. |
| [setEncodeMode()](#setencodemode) | Type de symbologie QR du mode d'encodage du code-barres. Valeur par défaut : QREncodeMode.Auto. |
| [setErrorLevel()](#seterrorlevel) | Niveau de correction d'erreurs Reed‑Solomon pour les codes QR, MicroQR et RectMicroQR. Du plus bas au plus haut : LevelL, LevelM, LevelQ. |
| [setMicroQRVersion()](#setmicroqrversion) | Version du code MicroQR. De la version M1 à la version M4. Valeur par défaut : MicroQRVersion.Auto. |
| [setQrECIEncoding()](#setqreciencoding) ~~(deprecated)~~ | Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails sur les références utilisées pour |
| [setQrEncodeMode()](#setqrencodemode) ~~(deprecated)~~ | Type de symbologie QR du mode d'encodage du code-barres. Valeur par défaut : QREncodeMode.AUTO. |
| [setQrEncodeType()](#setqrencodetype) ~~(deprecated)~~ | Mode de sélection QR / MicroQR. Sélectionnez ForceQR pour les symboles QR standards, Auto pour MicroQR. |
| [setQrErrorLevel()](#setqrerrorlevel) ~~(deprecated)~~ | Niveau de correction d'erreurs Reed‑Solomon pour le code QR. Du plus bas au plus haut : LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. voir QRError. |
| [setQrVersion()](#setqrversion) ~~(deprecated)~~ | Version du code QR. De Version1 à Version40 pour le code QR et de M1 à M4 pour MicroQr. Valeur par défaut : QRVersion.AUT |
| [setRectMicroQrVersion()](#setrectmicroqrversion) | Version du code RectMicroQR. De la version R7x59 à la version R17x139. Valeur par défaut : RectMicroQRVersion.Auto. |
| [setStructuredAppend()](#setstructuredappend) | Paramètres QR Structured Append. |
| [setVersion()](#setversion) | Version du code QR. De Version1 à Version40. Valeur par défaut : QRVersion.Auto. |
| [toString()](#tostring) | Renvoie une représentation sous forme de chaîne lisible par l'homme de ces QrParameters. |

### getAspectRatio() {#getaspectratio}

Ratio hauteur/largeur du module de code-barres 2D.

### getECIEncoding() {#geteciencoding}

Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour encoder les données dans le symbole. L'implémentation actuelle comprend tous les encodages de jeux de caractères connus. Non pris en charge par MicroQR.

### getEncodeGS1SeparatorInByteMode() {#getencodegs1separatorinbytemode}

Obtient ou définit une valeur indiquant si les caractères spéciaux GS1 doivent être encodés en mode Octet pour les codes QR et RectMicroQR. Si false, les séparateurs GS1 peuvent être encodés comme '%' en mode Alphanumérique selon la spécification QR. Si true, les séparateurs de groupe GS1 sont encodés en mode Octet comme le caractère 0x1D, et les caractères '%' sont également encodés en mode Octet pour les préserver en tant que données. Cette option peut améliorer la compatibilité avec les décodeurs qui attendent des séparateurs de groupe GS1 au niveau octet et empêche les caractères de données '%' d'être interprétés comme des séparateurs GS1.

**Returns:** a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

### getEncodeMode() {#getencodemode}

Type de symbologie QR du mode d'encodage du code-barres. Valeur par défaut : QREncodeMode.Auto.

### getErrorLevel() {#geterrorlevel}

Niveau de correction d'erreurs Reed‑Solomon pour les codes QR, MicroQR et RectMicroQR. Du plus bas au plus haut : LevelL, LevelM, LevelQ, LevelH. Voir QRErrorLevel.

### getMicroQRVersion() {#getmicroqrversion}

Version du code MicroQR. De la version M1 à la version M4. Valeur par défaut : MicroQRVersion.Auto.

### getQrECIEncoding() {#getqreciencoding}

> **Deprecated.** See method description for replacement.

Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour l'encodage des données dans le symbole. L'implémentation actuelle comprend tous les encodages de jeux de caractères bien connus.

### getQrEncodeMode() {#getqrencodemode}

Type de symbologie QR du mode d'encodage du code-barres. Valeur par défaut : QREncodeMode.AUTO.

### getQrEncodeType() {#getqrencodetype}

> **Deprecated.** See method description for replacement.

Mode de sélection QR / MicroQR. Sélectionnez ForceQR pour les symboles QR standards, Auto pour MicroQR.

### getQrErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Niveau de correction d'erreurs Reed‑Solomon pour le code QR. Du plus bas au plus haut : LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. voir QRErrorLevel.

### getQrVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Version du code QR. De Version1 à Version40 pour le code QR et de M1 à M4 pour MicroQr. Valeur par défaut : QRVersion.AUTO.

### getRectMicroQrVersion() {#getrectmicroqrversion}

Version du code RectMicroQR. De la version R7x59 à la version R17x139. Valeur par défaut : RectMicroQRVersion.Auto.

### getStructuredAppend() {#getstructuredappend}

Paramètres QR Structured Append.

### getVersion() {#getversion}

Version du code QR. De Version1 à Version40. Valeur par défaut : QRVersion.Auto.

### setAspectRatio() {#setaspectratio}

Ratio hauteur/largeur du module de code-barres 2D.

### setECIEncoding() {#seteciencoding}

Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour encoder les données dans le symbole. L'implémentation actuelle comprend tous les encodages de jeux de caractères connus. Non pris en charge par MicroQR.

### setEncodeGS1SeparatorInByteMode(value) {#setencodegs1separatorinbytemode}

Obtient ou définit une valeur indiquant si les caractères spéciaux GS1 doivent être encodés en mode Octet pour les codes QR et RectMicroQR. Si false, les séparateurs GS1 peuvent être encodés comme '%' en mode Alphanumérique selon la spécification QR. Si true, les séparateurs de groupe GS1 sont encodés en mode Octet comme le caractère 0x1D, et les caractères '%' sont également encodés en mode Octet pour les préserver en tant que données. Cette option peut améliorer la compatibilité avec les décodeurs qui attendent des séparateurs de groupe GS1 au niveau octet et empêche les caractères de données '%' d'être interprétés comme des séparateurs GS1.

| Paramètre | Description |
| --- | --- |
| valeur | une valeur indiquant si les caractères spéciaux GS1 doivent être encodés en mode Octet pour les codes QR et RectMicroQR. |

### setEncodeMode() {#setencodemode}

Type de symbologie QR du mode d'encodage du code-barres. Valeur par défaut : QREncodeMode.Auto.

### setErrorLevel() {#seterrorlevel}

Niveau de correction d'erreurs Reed‑Solomon pour les codes QR, MicroQR et RectMicroQR. Du plus bas au plus haut : LevelL, LevelM, LevelQ, LevelH. Voir QRErrorLevel.

### setMicroQRVersion() {#setmicroqrversion}

Version du code MicroQR. De la version M1 à la version M4. Valeur par défaut : MicroQRVersion.Auto.

### setQrECIEncoding() {#setqreciencoding}

> **Deprecated.** See method description for replacement.

Identifiants d'Interprétation de Canal Étendu. Ils sont utilisés pour indiquer au lecteur de code-barres les détails concernant les références utilisées pour l'encodage des données dans le symbole. L'implémentation actuelle comprend tous les encodages de jeux de caractères bien connus.

### setQrEncodeMode() {#setqrencodemode}

> **Deprecated.** See method description for replacement.

Type de symbologie QR du mode d'encodage du code-barres. Valeur par défaut : QREncodeMode.AUTO.

### setQrEncodeType() {#setqrencodetype}

> **Deprecated.** See method description for replacement.

Mode de sélection QR / MicroQR. Sélectionnez ForceQR pour les symboles QR standards, Auto pour MicroQR.

### setQrErrorLevel() {#setqrerrorlevel}

> **Deprecated.** See method description for replacement.

Niveau de correction d'erreurs Reed‑Solomon pour le code QR. Du plus bas au plus haut : LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. voir QRErrorLevel.

### setQrVersion() {#setqrversion}

> **Deprecated.** See method description for replacement.

Version du code QR. De Version1 à Version40 pour le code QR et de M1 à M4 pour MicroQr. Valeur par défaut : QRVersion.AUTO.

### setRectMicroQrVersion() {#setrectmicroqrversion}

Version du code RectMicroQR. De la version R7x59 à la version R17x139. Valeur par défaut : RectMicroQRVersion.Auto.

### setStructuredAppend() {#setstructuredappend}

Paramètres QR Structured Append.

### setVersion() {#setversion}

Version du code QR. De Version1 à Version40. Valeur par défaut : QRVersion.Auto.

### toString() {#tostring}

Renvoie une représentation sous forme de chaîne lisible par l'homme de ces QrParameters.

**Returns:** A string that represents this QrParameters.
