---
title: "AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Paramètres de décodage AustraliaPost."
type: docs
weight: 30
url: /fr/nodejs/aspose.barcode/australiapostsettings/
---

## AustraliaPostSettings class

Paramètres de décodage AustraliaPost. Contient des paramètres qui influencent les données reconnues de la symbologie AustraliaPost.

```js
new AustraliaPostSettings()
```

Constructeur AustraliaPostSettings

## Méthodes

| Nom | Description |
| --- | --- |
| [getCustomerInformationInterpretingType()](#getcustomerinformationinterpretingtype) | Obtient le type d'interprétation pour les informations client du code-barres AustralianPost. DEFAULT est CustomerInformationInterpre |
| [getIgnoreEndingFillingPatternsForCTable()](#getignoreendingfillingpatternsforctable) | Le drapeau qui force le décodeur AustraliaPost à ignorer les derniers motifs de remplissage dans le champ d'informations client lors du décodage |
| [setCustomerInformationInterpretingType(value)](#setcustomerinformationinterpretingtype) | Définit le type d'interprétation pour les informations client du code-barres AustralianPost. DEFAULT est CustomerInformationInterpre |
| [setIgnoreEndingFillingPatternsForCTable()](#setignoreendingfillingpatternsforctable) | Le drapeau qui force le décodeur AustraliaPost à ignorer les derniers motifs de remplissage dans le champ d'informations client lors du décodage |

### getCustomerInformationInterpretingType() {#getcustomerinformationinterpretingtype}

Obtient le type d'interprétation pour les informations client du code-barres AustralianPost. DEFAULT est CustomerInformationInterpretingType.OTHER.

**Returns:** The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode

### getIgnoreEndingFillingPatternsForCTable() {#getignoreendingfillingpatternsforctable}

Le drapeau qui force le décodeur AustraliaPost à ignorer les derniers motifs de remplissage dans le champ d'informations client lors du décodage selon la méthode CTable. La méthode d'encodage CTable ne comporte aucun vide dans la table d'encodage et la séquence \"333\" de motifs de remplissage est décodée comme la lettre \"z\".

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeType());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setCustomerInformationInterpretingType(value) {#setcustomerinformationinterpretingtype}

Définit le type d'interprétation pour les informations client du code-barres AustralianPost. DEFAULT est CustomerInformationInterpretingType.OTHER.

| Paramètre | Description |
| --- | --- |
| valeur | Le type d'interprétation (CTable, NTable ou Other) des informations client pour le code-barres AustralianPost |

### setIgnoreEndingFillingPatternsForCTable() {#setignoreendingfillingpatternsforctable}

Le drapeau qui force le décodeur AustraliaPost à ignorer les derniers motifs de remplissage dans le champ d'informations client lors du décodage selon la méthode CTable. La méthode d'encodage CTable ne comporte aucun vide dans la table d'encodage et la séquence \"333\" de motifs de remplissage est décodée comme la lettre \"z\".

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeType());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```
