---
title: "HanXinExtCodetextBuilder"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Uitgebreide codetekstgenerator voor Han Xin Code voor Uitgebreide Modus van HanXinEncodeMode //Uitgebreide codetekstmodus //maak codetekst let codeTextBuilder = new HanXinEx"
type: docs
weight: 500
url: /nl/nodejs/aspose.barcode/hanxinextcodetextbuilder/
---

## HanXinExtCodetextBuilder class

Uitgebreide codetekstgenerator voor Han Xin Code voor Uitgebreide Modus van HanXinEncodeMode //Uitgebreide codetekstmodus //maak codetekst let codeTextBuilder = new HanXinExtCodetextBuilder(); codeTextBuilder.addGB18030TwoByte("漄"); codeTextBuilder.addGB18030FourByte("㐁"); codeTextBuilder.addCommonChineseRegionOne("全"); codeTextBuilder.addCommonChineseRegionTwo("螅"); codeTextBuilder.addNumeric("123"); codeTextBuilder.addText("qwe"); codeTextBuilder.addUnicode("ıntəˈnæʃənəl"); codeTextBuilder.addECI("ΑΒΓΔΕ", 9); codeTextBuilder.addAuto("abc"); codeTextBuilder.addBinary("abc"); codeTextBuilder.addURI("backslashes_should_be_doubled\\000555:test"); codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10"); let expectedStr = "漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10"; //genereer codetekst let str = codeTextBuilder.getExtendedCodetext(); //genereer let bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str); bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED); let img = bg.generateBarCodeImage(BarcodeImageFormat.PNG); let r = new BarCodeReader(img, null, DecodeType.HAN_XIN)) let found = r.readBarCodes(); assert.assertEquals(1, found.length); assert.assertEquals(expectedStr, found[0].getCodeText());

```js
new HanXinExtCodetextBuilder()
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [addAuto(text)](#addauto) | Voegt codetekstfragment toe in Auto-modus |
| [addBinary(text)](#addbinary) | Voegt codetekstfragment toe in Binaire modus |
| [addCommonChineseRegionOne(text)](#addcommonchineseregionone) | Voegt codetekstfragment toe in Gemeenschappelijke Chinese Regio Eén-modus |
| [addCommonChineseRegionTwo(text)](#addcommonchineseregiontwo) | Voegt codetekstfragment toe in Gemeenschappelijke Chinese Regio Twee-modus |
| [addECI(text, encoding)](#addeci) | Voegt codetekstfragment toe in ECI-modus |
| [addGB18030FourByte(text)](#addgb18030fourbyte) | Voegt codetekstfragment toe in GB18030 Vier-Byte-modus |
| [addGB18030TwoByte(text)](#addgb18030twobyte) | Voegt codetekstfragment toe in GB18030 Twee-Byte-modus |
| [addGS1(text)](#addgs1) | Voegt codetekstfragment toe in GS1-modus |
| [addNumeric(text)](#addnumeric) | Voegt codetekstfragment toe in Numerieke modus |
| [addText(text)](#addtext) | Voegt codetekstfragment toe in Tekstmodus |
| [addUnicode(text)](#addunicode) | Voegt codetekstfragment toe in Unicode-modus |
| [addURI(text)](#adduri) | Voegt codetekstfragment toe in URI-modus |
| [getExtendedCodetext()](#getextendedcodetext) | Retourneert codetekst van de Extended-modus codetekstbuilder |

### addAuto(text) {#addauto}

Voegt codetekstfragment toe in Auto-modus

| Parameter | Beschrijving |
| --- | --- |
| tekst | Codetext tekenreeks |

### addBinary(text) {#addbinary}

Voegt codetekstfragment toe in Binaire modus

| Parameter | Beschrijving |
| --- | --- |
| tekst | Codetext tekenreeks |

### addCommonChineseRegionOne(text) {#addcommonchineseregionone}

Voegt codetekstfragment toe in Gemeenschappelijke Chinese Regio Eén-modus

| Parameter | Beschrijving |
| --- | --- |
| tekst | Codetext tekenreeks |

### addCommonChineseRegionTwo(text) {#addcommonchineseregiontwo}

Voegt codetekstfragment toe in Gemeenschappelijke Chinese Regio Twee-modus

| Parameter | Beschrijving |
| --- | --- |
| tekst | Codetext tekenreeks |

### addECI(text, encoding) {#addeci}

Voegt codetekstfragment toe in ECI-modus

| Parameter | Beschrijving |
| --- | --- |
| tekst | Codetext tekenreeks |
| codering | ECI-codering in numeriek formaat |

### addGB18030FourByte(text) {#addgb18030fourbyte}

Voegt codetekstfragment toe in GB18030 Vier-Byte-modus

| Parameter | Beschrijving |
| --- | --- |
| tekst | Codetext tekenreeks |

### addGB18030TwoByte(text) {#addgb18030twobyte}

Voegt codetekstfragment toe in GB18030 Twee-Byte-modus

| Parameter | Beschrijving |
| --- | --- |
| tekst | Codetext tekenreeks |

### addGS1(text) {#addgs1}

Voegt codetekstfragment toe in GS1-modus

| Parameter | Beschrijving |
| --- | --- |
| tekst | Codetext tekenreeks |

### addNumeric(text) {#addnumeric}

Voegt codetekstfragment toe in Numerieke modus

| Parameter | Beschrijving |
| --- | --- |
| tekst | Codetext tekenreeks |

### addText(text) {#addtext}

Voegt codetekstfragment toe in Tekstmodus

| Parameter | Beschrijving |
| --- | --- |
| tekst | Codetext tekenreeks |

### addUnicode(text) {#addunicode}

Voegt codetekstfragment toe in Unicode-modus

| Parameter | Beschrijving |
| --- | --- |
| tekst | Codetext tekenreeks |

### addURI(text) {#adduri}

Voegt codetekstfragment toe in URI-modus

| Parameter | Beschrijving |
| --- | --- |
| tekst | Codetext tekenreeks |

### getExtendedCodetext() {#getextendedcodetext}

Retourneert codetekst van de Extended-modus codetekstbuilder

**Returns:** Codetext in Extended mode
