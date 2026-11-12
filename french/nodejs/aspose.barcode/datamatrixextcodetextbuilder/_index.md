---
title: "DataMatrixExtCodetextBuilder"
linktitle: "DataMatrixExtCodetextBuilder"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Générateur de codetext étendu pour les codes-barres DataMatrix 2D pour le mode ExtendedCodetext de DataMatrixEncodeMode //Extended codetext mode //create codetext let textBuil"
type: docs
weight: 340
url: /fr/nodejs/aspose.barcode/datamatrixextcodetextbuilder/
---

## DataMatrixExtCodetextBuilder class

Générateur de codetext étendu pour les codes-barres DataMatrix 2D pour le mode ExtendedCodetext de DataMatrixEncodeMode //Extended codetext mode //create codetext let textBuilder = new DataMatrixExtCodetextBuilder(); codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251, DataMatrixEncodeMode.BYTES, "World"); codetextBuilder.addPlainCodetext("Will"); codetextBuilder.addECICodetext(ECIEncodings.UTF_8, "犬Right狗"); codetextBuilder.addCodetextWithEncodeMode(DataMatrixEncodeMode.C_40, "ABCDE"); //generate codetext let codetext = textBuilder.getExtendedCodetext(); //generate let generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, null, codetext); generator.getParameters().getBarcode().getDataMatrix().setDataMatrixEncodeMode(DataMatrixEncodeMode.EXTENDED_CODETEXT); generator.save("test.bmp", BarcodeImageFormat.BMP);

```js
new DataMatrixExtCodetextBuilder()
```

## Méthodes

| Nom | Description |
| --- | --- |
| [addCodetextWithEncodeMode(encodeMode, codetext)](#addcodetextwithencodemode) | Ajoute du codetext avec le mode d'encodage défini aux éléments de codetext étendu |
| [addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext)](#addecicodetextwithencodemode) | Ajoute du codetext avec un Identifiant de Canal Étendu avec le mode d'encodage défini |
| [getExtendedCodetext()](#getextendedcodetext) | Génère le codetext étendu à partir de la liste de codetext étendu. |

### addCodetextWithEncodeMode(encodeMode, codetext) {#addcodetextwithencodemode}

Ajoute du codetext avec le mode d'encodage défini aux éléments de codetext étendu

| Paramètre | Description |
| --- | --- |
| encodeMode | Valeur du mode d'encodage |
| codetext | Codetext en Unicode à ajouter en tant qu'élément de codetext étendu |

### addECICodetextWithEncodeMode(ECIEncoding, encodeMode, codetext) {#addecicodetextwithencodemode}

Ajoute du codetext avec un Identifiant de Canal Étendu avec le mode d'encodage défini

| Paramètre | Description |
| --- | --- |
| ECIEncoding | Identifiant de Canal Étendu |
| encodeMode | Valeur du mode d'encodage |
| codetext | Codetext en Unicode à ajouter en tant qu'élément de codetext étendu avec Identifiant de Canal Étendu avec le mode d'encodage défini |

### getExtendedCodetext() {#getextendedcodetext}

Génère le codetext étendu à partir de la liste de codetext étendu.

**Returns:** Extended codetext as string
