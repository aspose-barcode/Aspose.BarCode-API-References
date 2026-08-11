---
title: "HanXinExtCodetextBuilder"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "Extended codetext generator for Han Xin Code for Extended Mode of HanXinEncodeMode //Extended codetext mode //create codetext let codeTextBuilder = new HanXinEx"
type: docs
weight: 500
url: /nodejs/aspose.barcode/hanxinextcodetextbuilder/
---

## HanXinExtCodetextBuilder class

Extended codetext generator for Han Xin Code for Extended Mode of HanXinEncodeMode //Extended codetext mode //create codetext let codeTextBuilder = new HanXinExtCodetextBuilder(); codeTextBuilder.addGB18030TwoByte("漄"); codeTextBuilder.addGB18030FourByte("㐁"); codeTextBuilder.addCommonChineseRegionOne("全"); codeTextBuilder.addCommonChineseRegionTwo("螅"); codeTextBuilder.addNumeric("123"); codeTextBuilder.addText("qwe"); codeTextBuilder.addUnicode("ıntəˈnæʃənəl"); codeTextBuilder.addECI("ΑΒΓΔΕ", 9); codeTextBuilder.addAuto("abc"); codeTextBuilder.addBinary("abc"); codeTextBuilder.addURI("backslashes_should_be_doubled\000555:test"); codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10"); let expectedStr = "漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10"; //generate codetext let str = codeTextBuilder.getExtendedCodetext(); //generate let bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str); bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED); let img = bg.generateBarCodeImage(BarcodeImageFormat.PNG); let r = new BarCodeReader(img, null, DecodeType.HAN_XIN)) let found = r.readBarCodes(); assert.assertEquals(1, found.length); assert.assertEquals(expectedStr, found[0].getCodeText());

```js
new HanXinExtCodetextBuilder()
```

## Methods

| Name | Description |
| --- | --- |
| [addAuto(text)](#addauto) | Adds codetext fragment in Auto mode |
| [addBinary(text)](#addbinary) | Adds codetext fragment in Binary mode |
| [addCommonChineseRegionOne(text)](#addcommonchineseregionone) | Adds codetext fragment in Common Chinese Region One mode |
| [addCommonChineseRegionTwo(text)](#addcommonchineseregiontwo) | Adds codetext fragment in Common Chinese Region Two mode |
| [addECI(text, encoding)](#addeci) | Adds codetext fragment in ECI mode |
| [addGB18030FourByte(text)](#addgb18030fourbyte) | Adds codetext fragment in GB18030 Four Byte mode |
| [addGB18030TwoByte(text)](#addgb18030twobyte) | Adds codetext fragment in GB18030 Two Byte mode |
| [addGS1(text)](#addgs1) | Adds codetext fragment in GS1 mode |
| [addNumeric(text)](#addnumeric) | Adds codetext fragment in Numeric mode |
| [addText(text)](#addtext) | Adds codetext fragment in Text mode |
| [addUnicode(text)](#addunicode) | Adds codetext fragment in Unicode mode |
| [addURI(text)](#adduri) | Adds codetext fragment in URI mode |
| [getExtendedCodetext()](#getextendedcodetext) | Returns codetext from Extended mode codetext builder |

### addAuto(text) {#addauto}

Adds codetext fragment in Auto mode

| Parameter | Description |
| --- | --- |
| text | Codetext string |

### addBinary(text) {#addbinary}

Adds codetext fragment in Binary mode

| Parameter | Description |
| --- | --- |
| text | Codetext string |

### addCommonChineseRegionOne(text) {#addcommonchineseregionone}

Adds codetext fragment in Common Chinese Region One mode

| Parameter | Description |
| --- | --- |
| text | Codetext string |

### addCommonChineseRegionTwo(text) {#addcommonchineseregiontwo}

Adds codetext fragment in Common Chinese Region Two mode

| Parameter | Description |
| --- | --- |
| text | Codetext string |

### addECI(text, encoding) {#addeci}

Adds codetext fragment in ECI mode

| Parameter | Description |
| --- | --- |
| text | Codetext string |
| encoding | ECI encoding in number format |

### addGB18030FourByte(text) {#addgb18030fourbyte}

Adds codetext fragment in GB18030 Four Byte mode

| Parameter | Description |
| --- | --- |
| text | Codetext string |

### addGB18030TwoByte(text) {#addgb18030twobyte}

Adds codetext fragment in GB18030 Two Byte mode

| Parameter | Description |
| --- | --- |
| text | Codetext string |

### addGS1(text) {#addgs1}

Adds codetext fragment in GS1 mode

| Parameter | Description |
| --- | --- |
| text | Codetext string |

### addNumeric(text) {#addnumeric}

Adds codetext fragment in Numeric mode

| Parameter | Description |
| --- | --- |
| text | Codetext string |

### addText(text) {#addtext}

Adds codetext fragment in Text mode

| Parameter | Description |
| --- | --- |
| text | Codetext string |

### addUnicode(text) {#addunicode}

Adds codetext fragment in Unicode mode

| Parameter | Description |
| --- | --- |
| text | Codetext string |

### addURI(text) {#adduri}

Adds codetext fragment in URI mode

| Parameter | Description |
| --- | --- |
| text | Codetext string |

### getExtendedCodetext() {#getextendedcodetext}

Returns codetext from Extended mode codetext builder

**Returns:** Codetext in Extended mode
