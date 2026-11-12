---
title: "HanXinExtCodetextBuilder"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Erweiterter Codetext-Generator für Han Xin Code für den erweiterten Modus von HanXinEncodeMode //Erweiterter Codetext-Modus //Codetext erstellen let codeTextBuilder = new HanXinEx"
type: docs
weight: 500
url: /de/nodejs/aspose.barcode/hanxinextcodetextbuilder/
---

## HanXinExtCodetextBuilder class

Erweiterter Codetext-Generator für Han Xin Code für den erweiterten Modus von HanXinEncodeMode //Erweiterter Codetext-Modus //Codetext erstellen let codeTextBuilder = new HanXinExtCodetextBuilder(); codeTextBuilder.addGB18030TwoByte("漄"); codeTextBuilder.addGB18030FourByte("㐁"); codeTextBuilder.addCommonChineseRegionOne("全"); codeTextBuilder.addCommonChineseRegionTwo("螅"); codeTextBuilder.addNumeric("123"); codeTextBuilder.addText("qwe"); codeTextBuilder.addUnicode("ıntəˈnæʃənəl"); codeTextBuilder.addECI("ΑΒΓΔΕ", 9); codeTextBuilder.addAuto("abc"); codeTextBuilder.addBinary("abc"); codeTextBuilder.addURI("backslashes_should_be_doubled\000555:test"); codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10"); let expectedStr = "漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10"; //Codetext generieren let str = codeTextBuilder.getExtendedCodetext(); //generieren let bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str); bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED); let img = bg.generateBarCodeImage(BarcodeImageFormat.PNG); let r = new BarCodeReader(img, null, DecodeType.HAN_XIN)) let found = r.readBarCodes(); assert.assertEquals(1, found.length); assert.assertEquals(expectedStr, found[0].getCodeText());

```js
new HanXinExtCodetextBuilder()
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [addAuto(text)](#addauto) | Fügt Codetext-Fragment im Auto‑Modus hinzu |
| [addBinary(text)](#addbinary) | Fügt Codetext-Fragment im Binär‑Modus hinzu |
| [addCommonChineseRegionOne(text)](#addcommonchineseregionone) | Fügt Codetext-Fragment im Modus Gemeinsame Chinesische Region Eins hinzu |
| [addCommonChineseRegionTwo(text)](#addcommonchineseregiontwo) | Fügt Codetext-Fragment im Modus Gemeinsame Chinesische Region Zwei hinzu |
| [addECI(text, encoding)](#addeci) | Fügt Codetext-Fragment im ECI‑Modus hinzu |
| [addGB18030FourByte(text)](#addgb18030fourbyte) | Fügt Codetext-Fragment im GB18030‑Vier‑Byte‑Modus hinzu |
| [addGB18030TwoByte(text)](#addgb18030twobyte) | Fügt Codetext-Fragment im GB18030‑Zwei‑Byte‑Modus hinzu |
| [addGS1(text)](#addgs1) | Fügt Codetext-Fragment im GS1‑Modus hinzu |
| [addNumeric(text)](#addnumeric) | Fügt Codetext-Fragment im Numerisch‑Modus hinzu |
| [addText(text)](#addtext) | Fügt Codetext-Fragment im Text‑Modus hinzu |
| [addUnicode(text)](#addunicode) | Fügt Codetext-Fragment im Unicode‑Modus hinzu |
| [addURI(text)](#adduri) | Fügt Codetext-Fragment im URI‑Modus hinzu |
| [getExtendedCodetext()](#getextendedcodetext) | Gibt den Codetext vom erweiterten Modus‑Codetext‑Builder zurück |

### addAuto(text) {#addauto}

Fügt Codetext-Fragment im Auto‑Modus hinzu

| Parameter | Beschreibung |
| --- | --- |
| Text | Codetext Zeichenkette |

### addBinary(text) {#addbinary}

Fügt Codetext-Fragment im Binär‑Modus hinzu

| Parameter | Beschreibung |
| --- | --- |
| Text | Codetext Zeichenkette |

### addCommonChineseRegionOne(text) {#addcommonchineseregionone}

Fügt Codetext-Fragment im Modus Gemeinsame Chinesische Region Eins hinzu

| Parameter | Beschreibung |
| --- | --- |
| Text | Codetext Zeichenkette |

### addCommonChineseRegionTwo(text) {#addcommonchineseregiontwo}

Fügt Codetext-Fragment im Modus Gemeinsame Chinesische Region Zwei hinzu

| Parameter | Beschreibung |
| --- | --- |
| Text | Codetext Zeichenkette |

### addECI(text, encoding) {#addeci}

Fügt Codetext-Fragment im ECI‑Modus hinzu

| Parameter | Beschreibung |
| --- | --- |
| Text | Codetext Zeichenkette |
| Kodierung | ECI-Kodierung im Zahlenformat |

### addGB18030FourByte(text) {#addgb18030fourbyte}

Fügt Codetext-Fragment im GB18030‑Vier‑Byte‑Modus hinzu

| Parameter | Beschreibung |
| --- | --- |
| Text | Codetext Zeichenkette |

### addGB18030TwoByte(text) {#addgb18030twobyte}

Fügt Codetext-Fragment im GB18030‑Zwei‑Byte‑Modus hinzu

| Parameter | Beschreibung |
| --- | --- |
| Text | Codetext Zeichenkette |

### addGS1(text) {#addgs1}

Fügt Codetext-Fragment im GS1‑Modus hinzu

| Parameter | Beschreibung |
| --- | --- |
| Text | Codetext Zeichenkette |

### addNumeric(text) {#addnumeric}

Fügt Codetext-Fragment im Numerisch‑Modus hinzu

| Parameter | Beschreibung |
| --- | --- |
| Text | Codetext Zeichenkette |

### addText(text) {#addtext}

Fügt Codetext-Fragment im Text‑Modus hinzu

| Parameter | Beschreibung |
| --- | --- |
| Text | Codetext Zeichenkette |

### addUnicode(text) {#addunicode}

Fügt Codetext-Fragment im Unicode‑Modus hinzu

| Parameter | Beschreibung |
| --- | --- |
| Text | Codetext Zeichenkette |

### addURI(text) {#adduri}

Fügt Codetext-Fragment im URI‑Modus hinzu

| Parameter | Beschreibung |
| --- | --- |
| Text | Codetext Zeichenkette |

### getExtendedCodetext() {#getextendedcodetext}

Gibt den Codetext vom erweiterten Modus‑Codetext‑Builder zurück

**Returns:** Codetext in Extended mode
