---
title: "HanXinExtCodetextBuilder"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Utökad kodtextgenerator för Han Xin‑kod för Utökat läge av HanXinEncodeMode //Utökat kodtextläge //skapa kodtext let codeTextBuilder = new HanXinEx"
type: docs
weight: 500
url: /sv/nodejs/aspose.barcode/hanxinextcodetextbuilder/
---

## HanXinExtCodetextBuilder class

Utökad kodtextgenerator för Han Xin Code för Utökad Läge av HanXinEncodeMode //Utökad kodtextläge //skapa kodtext let codeTextBuilder = new HanXinExtCodetextBuilder(); codeTextBuilder.addGB18030TwoByte("漄"); codeTextBuilder.addGB18030FourByte("㐁"); codeTextBuilder.addCommonChineseRegionOne("全"); codeTextBuilder.addCommonChineseRegionTwo("螅"); codeTextBuilder.addNumeric("123"); codeTextBuilder.addText("qwe"); codeTextBuilder.addUnicode("ıntəˈnæʃənəl"); codeTextBuilder.addECI("ΑΒΓΔΕ", 9); codeTextBuilder.addAuto("abc"); codeTextBuilder.addBinary("abc"); codeTextBuilder.addURI("backslashes_should_be_doubled\000555:test"); codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10"); let expectedStr = "漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10"; //generera kodtext let str = codeTextBuilder.getExtendedCodetext(); //generera let bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str); bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED); let img = bg.generateBarCodeImage(BarcodeImageFormat.PNG); let r = new BarCodeReader(img, null, DecodeType.HAN_XIN)) let found = r.readBarCodes(); assert.assertEquals(1, found.length); assert.assertEquals(expectedStr, found[0].getCodeText());

```js
new HanXinExtCodetextBuilder()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addAuto(text)](#addauto) | Lägger till kodtextfragment i Auto-läge |
| [addBinary(text)](#addbinary) | Lägger till kodtextfragment i Binärt läge |
| [addCommonChineseRegionOne(text)](#addcommonchineseregionone) | Lägger till kodtextfragment i Common Chinese Region One-läge |
| [addCommonChineseRegionTwo(text)](#addcommonchineseregiontwo) | Lägger till kodtextfragment i Common Chinese Region Two-läge |
| [addECI(text, encoding)](#addeci) | Lägger till kodtextfragment i ECI-läge |
| [addGB18030FourByte(text)](#addgb18030fourbyte) | Lägger till kodtextfragment i GB18030 Four Byte-läge |
| [addGB18030TwoByte(text)](#addgb18030twobyte) | Lägger till kodtextfragment i GB18030 Two Byte-läge |
| [addGS1(text)](#addgs1) | Lägger till kodtextfragment i GS1-läge |
| [addNumeric(text)](#addnumeric) | Lägger till kodtextfragment i Numeriskt läge |
| [addText(text)](#addtext) | Lägger till kodtextfragment i Text-läge |
| [addUnicode(text)](#addunicode) | Lägger till kodtextfragment i Unicode-läge |
| [addURI(text)](#adduri) | Lägger till kodtextfragment i URI-läge |
| [getExtendedCodetext()](#getextendedcodetext) | Returnerar kodtext från Extended-läge kodtextbyggare |

### addAuto(text) {#addauto}

Lägger till kodtextfragment i Auto-läge

| Parameter | Beskrivning |
| --- | --- |
| text | Kodtextsträng |

### addBinary(text) {#addbinary}

Lägger till kodtextfragment i Binärt läge

| Parameter | Beskrivning |
| --- | --- |
| text | Kodtextsträng |

### addCommonChineseRegionOne(text) {#addcommonchineseregionone}

Lägger till kodtextfragment i Common Chinese Region One-läge

| Parameter | Beskrivning |
| --- | --- |
| text | Kodtextsträng |

### addCommonChineseRegionTwo(text) {#addcommonchineseregiontwo}

Lägger till kodtextfragment i Common Chinese Region Two-läge

| Parameter | Beskrivning |
| --- | --- |
| text | Kodtextsträng |

### addECI(text, encoding) {#addeci}

Lägger till kodtextfragment i ECI-läge

| Parameter | Beskrivning |
| --- | --- |
| text | Kodtextsträng |
| kodning | ECI-kodning i talformat |

### addGB18030FourByte(text) {#addgb18030fourbyte}

Lägger till kodtextfragment i GB18030 Four Byte-läge

| Parameter | Beskrivning |
| --- | --- |
| text | Kodtextsträng |

### addGB18030TwoByte(text) {#addgb18030twobyte}

Lägger till kodtextfragment i GB18030 Two Byte-läge

| Parameter | Beskrivning |
| --- | --- |
| text | Kodtextsträng |

### addGS1(text) {#addgs1}

Lägger till kodtextfragment i GS1-läge

| Parameter | Beskrivning |
| --- | --- |
| text | Kodtextsträng |

### addNumeric(text) {#addnumeric}

Lägger till kodtextfragment i Numeriskt läge

| Parameter | Beskrivning |
| --- | --- |
| text | Kodtextsträng |

### addText(text) {#addtext}

Lägger till kodtextfragment i Text-läge

| Parameter | Beskrivning |
| --- | --- |
| text | Kodtextsträng |

### addUnicode(text) {#addunicode}

Lägger till kodtextfragment i Unicode-läge

| Parameter | Beskrivning |
| --- | --- |
| text | Kodtextsträng |

### addURI(text) {#adduri}

Lägger till kodtextfragment i URI-läge

| Parameter | Beskrivning |
| --- | --- |
| text | Kodtextsträng |

### getExtendedCodetext() {#getextendedcodetext}

Returnerar kodtext från Extended-läge kodtextbyggare

**Returns:** Codetext in Extended mode
