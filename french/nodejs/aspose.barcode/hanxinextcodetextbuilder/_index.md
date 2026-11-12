---
title: "HanXinExtCodetextBuilder"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Générateur de codetext étendu pour le code Han Xin en mode étendu de HanXinEncodeMode //Mode codetext étendu //créer le codetext let codeTextBuilder = new HanXinEx"
type: docs
weight: 500
url: /fr/nodejs/aspose.barcode/hanxinextcodetextbuilder/
---

## HanXinExtCodetextBuilder class

Générateur de codetext étendu pour le code Han Xin en mode étendu de HanXinEncodeMode //Mode codetext étendu //créer le codetext let codeTextBuilder = new HanXinExtCodetextBuilder(); codeTextBuilder.addGB18030TwoByte("漄"); codeTextBuilder.addGB18030FourByte("㐁"); codeTextBuilder.addCommonChineseRegionOne("全"); codeTextBuilder.addCommonChineseRegionTwo("螅"); codeTextBuilder.addNumeric("123"); codeTextBuilder.addText("qwe"); codeTextBuilder.addUnicode("ıntəˈnæʃənəl"); codeTextBuilder.addECI("ΑΒΓΔΕ", 9); codeTextBuilder.addAuto("abc"); codeTextBuilder.addBinary("abc"); codeTextBuilder.addURI("backslashes_should_be_doubled\\000555:test"); codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10"); let expectedStr = "漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10"; //generate codetext let str = codeTextBuilder.getExtendedCodetext(); //generate let bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str); bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED); let img = bg.generateBarCodeImage(BarcodeImageFormat.PNG); let r = new BarCodeReader(img, null, DecodeType.HAN_XIN)) let found = r.readBarCodes(); assert.assertEquals(1, found.length); assert.assertEquals(expectedStr, found[0].getCodeText());

```js
new HanXinExtCodetextBuilder()
```

## Méthodes

| Nom | Description |
| --- | --- |
| [addAuto(text)](#addauto) | Ajoute un fragment de codetext en mode Auto |
| [addBinary(text)](#addbinary) | Ajoute un fragment de codetext en mode Binaire |
| [addCommonChineseRegionOne(text)](#addcommonchineseregionone) | Ajoute un fragment de codetext en mode Région chinoise commune Un |
| [addCommonChineseRegionTwo(text)](#addcommonchineseregiontwo) | Ajoute un fragment de codetext en mode Région chinoise commune Deux |
| [addECI(text, encoding)](#addeci) | Ajoute un fragment de codetext en mode ECI |
| [addGB18030FourByte(text)](#addgb18030fourbyte) | Ajoute un fragment de codetext en mode GB18030 quatre octets |
| [addGB18030TwoByte(text)](#addgb18030twobyte) | Ajoute un fragment de codetext en mode GB18030 deux octets |
| [addGS1(text)](#addgs1) | Ajoute un fragment de codetext en mode GS1 |
| [addNumeric(text)](#addnumeric) | Ajoute un fragment de codetext en mode Numérique |
| [addText(text)](#addtext) | Ajoute un fragment de codetext en mode Texte |
| [addUnicode(text)](#addunicode) | Ajoute un fragment de codetext en mode Unicode |
| [addURI(text)](#adduri) | Ajoute un fragment de codetext en mode URI |
| [getExtendedCodetext()](#getextendedcodetext) | Renvoie le codetext du générateur de codetext en mode Étendu |

### addAuto(text) {#addauto}

Ajoute un fragment de codetext en mode Auto

| Paramètre | Description |
| --- | --- |
| texte | Chaîne Codetext |

### addBinary(text) {#addbinary}

Ajoute un fragment de codetext en mode Binaire

| Paramètre | Description |
| --- | --- |
| texte | Chaîne Codetext |

### addCommonChineseRegionOne(text) {#addcommonchineseregionone}

Ajoute un fragment de codetext en mode Région chinoise commune Un

| Paramètre | Description |
| --- | --- |
| texte | Chaîne Codetext |

### addCommonChineseRegionTwo(text) {#addcommonchineseregiontwo}

Ajoute un fragment de codetext en mode Région chinoise commune Deux

| Paramètre | Description |
| --- | --- |
| texte | Chaîne Codetext |

### addECI(text, encoding) {#addeci}

Ajoute un fragment de codetext en mode ECI

| Paramètre | Description |
| --- | --- |
| texte | Chaîne Codetext |
| encodage | Encodage ECI au format numérique |

### addGB18030FourByte(text) {#addgb18030fourbyte}

Ajoute un fragment de codetext en mode GB18030 quatre octets

| Paramètre | Description |
| --- | --- |
| texte | Chaîne Codetext |

### addGB18030TwoByte(text) {#addgb18030twobyte}

Ajoute un fragment de codetext en mode GB18030 deux octets

| Paramètre | Description |
| --- | --- |
| texte | Chaîne Codetext |

### addGS1(text) {#addgs1}

Ajoute un fragment de codetext en mode GS1

| Paramètre | Description |
| --- | --- |
| texte | Chaîne Codetext |

### addNumeric(text) {#addnumeric}

Ajoute un fragment de codetext en mode Numérique

| Paramètre | Description |
| --- | --- |
| texte | Chaîne Codetext |

### addText(text) {#addtext}

Ajoute un fragment de codetext en mode Texte

| Paramètre | Description |
| --- | --- |
| texte | Chaîne Codetext |

### addUnicode(text) {#addunicode}

Ajoute un fragment de codetext en mode Unicode

| Paramètre | Description |
| --- | --- |
| texte | Chaîne Codetext |

### addURI(text) {#adduri}

Ajoute un fragment de codetext en mode URI

| Paramètre | Description |
| --- | --- |
| texte | Chaîne Codetext |

### getExtendedCodetext() {#getextendedcodetext}

Renvoie le codetext du générateur de codetext en mode Étendu

**Returns:** Codetext in Extended mode
