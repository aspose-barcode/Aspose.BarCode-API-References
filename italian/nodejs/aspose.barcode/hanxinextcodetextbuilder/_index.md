---
title: "HanXinExtCodetextBuilder"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Generatore di codetext esteso per Han Xin Code in modalità estesa di HanXinEncodeMode //Modalità codetext estesa //crea codetext let codeTextBuilder = new HanXinEx"
type: docs
weight: 500
url: /it/nodejs/aspose.barcode/hanxinextcodetextbuilder/
---

## HanXinExtCodetextBuilder class

Generatore di codetext esteso per Han Xin Code in modalità estesa di HanXinEncodeMode //Modalità codetext estesa //crea codetext let codeTextBuilder = new HanXinExtCodetextBuilder(); codeTextBuilder.addGB18030TwoByte("漄"); codeTextBuilder.addGB18030FourByte("㐁"); codeTextBuilder.addCommonChineseRegionOne("全"); codeTextBuilder.addCommonChineseRegionTwo("螅"); codeTextBuilder.addNumeric("123"); codeTextBuilder.addText("qwe"); codeTextBuilder.addUnicode("ıntəˈnæʃənəl"); codeTextBuilder.addECI("ΑΒΓΔΕ", 9); codeTextBuilder.addAuto("abc"); codeTextBuilder.addBinary("abc"); codeTextBuilder.addURI("backslashes_should_be_doubled\000555:test"); codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10"); let expectedStr = "漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10"; //genera codetext let str = codeTextBuilder.getExtendedCodetext(); //genera let bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str); bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED); let img = bg.generateBarCodeImage(BarcodeImageFormat.PNG); let r = new BarCodeReader(img, null, DecodeType.HAN_XIN)) let found = r.readBarCodes(); assert.assertEquals(1, found.length); assert.assertEquals(expectedStr, found[0].getCodeText());

```js
new HanXinExtCodetextBuilder()
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [addAuto(text)](#addauto) | Aggiunge frammento di codetext in modalità Auto |
| [addBinary(text)](#addbinary) | Aggiunge frammento di codetext in modalità Binaria |
| [addCommonChineseRegionOne(text)](#addcommonchineseregionone) | Aggiunge frammento di codetext in modalità Common Chinese Region One |
| [addCommonChineseRegionTwo(text)](#addcommonchineseregiontwo) | Aggiunge frammento di codetext in modalità Common Chinese Region Two |
| [addECI(text, encoding)](#addeci) | Aggiunge frammento di codetext in modalità ECI |
| [addGB18030FourByte(text)](#addgb18030fourbyte) | Aggiunge frammento di codetext in modalità GB18030 Four Byte |
| [addGB18030TwoByte(text)](#addgb18030twobyte) | Aggiunge frammento di codetext in modalità GB18030 Two Byte |
| [addGS1(text)](#addgs1) | Aggiunge frammento di codetext in modalità GS1 |
| [addNumeric(text)](#addnumeric) | Aggiunge frammento di codetext in modalità Numerica |
| [addText(text)](#addtext) | Aggiunge frammento di codetext in modalità Testo |
| [addUnicode(text)](#addunicode) | Aggiunge frammento di codetext in modalità Unicode |
| [addURI(text)](#adduri) | Aggiunge frammento di codetext in modalità URI |
| [getExtendedCodetext()](#getextendedcodetext) | Restituisce il codetext dal generatore di codetext in modalità Estesa |

### addAuto(text) {#addauto}

Aggiunge frammento di codetext in modalità Auto

| Parametro | Descrizione |
| --- | --- |
| testo | Stringa Codetext |

### addBinary(text) {#addbinary}

Aggiunge frammento di codetext in modalità Binaria

| Parametro | Descrizione |
| --- | --- |
| testo | Stringa Codetext |

### addCommonChineseRegionOne(text) {#addcommonchineseregionone}

Aggiunge frammento di codetext in modalità Common Chinese Region One

| Parametro | Descrizione |
| --- | --- |
| testo | Stringa Codetext |

### addCommonChineseRegionTwo(text) {#addcommonchineseregiontwo}

Aggiunge frammento di codetext in modalità Common Chinese Region Two

| Parametro | Descrizione |
| --- | --- |
| testo | Stringa Codetext |

### addECI(text, encoding) {#addeci}

Aggiunge frammento di codetext in modalità ECI

| Parametro | Descrizione |
| --- | --- |
| testo | Stringa Codetext |
| codifica | Codifica ECI in formato numerico |

### addGB18030FourByte(text) {#addgb18030fourbyte}

Aggiunge frammento di codetext in modalità GB18030 Four Byte

| Parametro | Descrizione |
| --- | --- |
| testo | Stringa Codetext |

### addGB18030TwoByte(text) {#addgb18030twobyte}

Aggiunge frammento di codetext in modalità GB18030 Two Byte

| Parametro | Descrizione |
| --- | --- |
| testo | Stringa Codetext |

### addGS1(text) {#addgs1}

Aggiunge frammento di codetext in modalità GS1

| Parametro | Descrizione |
| --- | --- |
| testo | Stringa Codetext |

### addNumeric(text) {#addnumeric}

Aggiunge frammento di codetext in modalità Numerica

| Parametro | Descrizione |
| --- | --- |
| testo | Stringa Codetext |

### addText(text) {#addtext}

Aggiunge frammento di codetext in modalità Testo

| Parametro | Descrizione |
| --- | --- |
| testo | Stringa Codetext |

### addUnicode(text) {#addunicode}

Aggiunge frammento di codetext in modalità Unicode

| Parametro | Descrizione |
| --- | --- |
| testo | Stringa Codetext |

### addURI(text) {#adduri}

Aggiunge frammento di codetext in modalità URI

| Parametro | Descrizione |
| --- | --- |
| testo | Stringa Codetext |

### getExtendedCodetext() {#getextendedcodetext}

Restituisce il codetext dal generatore di codetext in modalità Estesa

**Returns:** Codetext in Extended mode
