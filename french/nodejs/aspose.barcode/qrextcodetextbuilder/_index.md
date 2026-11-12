---
title: "QrExtCodetextBuilder"
linktitle: "QrExtCodetextBuilder"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Générateur de texte étendu pour les codes-barres QR 2D en mode ExtendedCodetext de QREncodeMode. Utilisez la propriété Display2DText de BarCodeBuilder pour définir le texte visible à rem"
type: docs
weight: 820
url: /fr/nodejs/aspose.barcode/qrextcodetextbuilder/
---

## QrExtCodetextBuilder class

Générateur de texte étendu pour les codes-barres QR 2D en mode ExtendedCodetext de QREncodeMode. Utilisez la propriété Display2DText de BarCodeBuilder pour définir le texte visible en supprimant les caractères de gestion.

```js
new QrExtCodetextBuilder()
```

**Example:**

```js
//Example how to generate FNC1 first position for Extended Mode
 //create codetext
 const lTextBuilder = new QrExtCodetextBuilder();
 lTextBuilder.addFNC1FirstPosition();
 lTextBuilder.addPlainCodetext("000%89%%0");
 lTextBuilder.addFNC1GroupSeparator();
 lTextBuilder.addPlainCodetext("12345&lt;FNC1&gt;");
 //generate codetext
 const lCodetext = lTextBuilder.getExtendedCodetext();
```

## Méthodes

| Nom | Description |
| --- | --- |
| [addCodetextWithCompactionMode(mode, codetext)](#addcodetextwithcompactionmode) | Ajoute du texte de code avec le mode de compression QR spécifié aux éléments de texte de code étendu. |
| [addFNC1FirstPosition()](#addfnc1firstposition) | Ajoute FNC1 en première position aux éléments de texte de code étendu. |
| [addFNC1GroupSeparator()](#addfnc1groupseparator) | Ajoute le séparateur de groupe (GS - '\\u001D') aux éléments de texte de code étendu. |
| [addFNC1SecondPosition(codetext)](#addfnc1secondposition) | Ajoute FNC1 en deuxième position aux éléments de texte de code étendu. |
| [clear()](#clear) | Efface les éléments de texte de code étendu |
| [getExtendedCodetext()](#getextendedcodetext) | Génère le codetext étendu à partir de la liste de codetext étendu. |

### addCodetextWithCompactionMode(mode, codetext) {#addcodetextwithcompactionmode}

Ajoute du texte de code avec le mode de compression QR spécifié aux éléments de texte de code étendu.

| Paramètre | Description |
| --- | --- |
| mode | Mode de compression QR pour le texte de code. |
| codetext | Texte de code en Unicode à ajouter en tant qu'élément de texte de code étendu. |

**Throws:** IllegalArgumentException The specified codetext cannot be encoded in the selected QR compaction mode.

### addFNC1FirstPosition() {#addfnc1firstposition}

Ajoute FNC1 en première position aux éléments de texte de code étendu.

### addFNC1GroupSeparator() {#addfnc1groupseparator}

Ajoute le séparateur de groupe (GS - '\\u001D') aux éléments de texte de code étendu.

### addFNC1SecondPosition(codetext) {#addfnc1secondposition}

Ajoute FNC1 en deuxième position aux éléments de texte de code étendu.

| Paramètre | Description |
| --- | --- |
| codetext | Valeur du FNC1 en deuxième position |

### clear() {#clear}

Efface les éléments de texte de code étendu

### getExtendedCodetext() {#getextendedcodetext}

Génère le codetext étendu à partir de la liste de codetext étendu.

**Returns:** Extended codetext as string
