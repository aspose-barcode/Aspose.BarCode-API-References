---
title: "HanXinExtCodetextBuilder"
linktitle: "HanXinExtCodetextBuilder"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "مولد نص شفري موسع لرمز Han Xin للوضع الموسع من HanXinEncodeMode //وضع نص شفري موسع //إنشاء نص شفري let codeTextBuilder = new HanXinEx"
type: docs
weight: 500
url: /ar/nodejs/aspose.barcode/hanxinextcodetextbuilder/
---

## HanXinExtCodetextBuilder class

مولد نص شفري موسع لرمز Han Xin للوضع الموسع من HanXinEncodeMode //وضع نص شفري موسع //إنشاء نص شفري let codeTextBuilder = new HanXinExtCodetextBuilder(); codeTextBuilder.addGB18030TwoByte("漄"); codeTextBuilder.addGB18030FourByte("㐁"); codeTextBuilder.addCommonChineseRegionOne("全"); codeTextBuilder.addCommonChineseRegionTwo("螅"); codeTextBuilder.addNumeric("123"); codeTextBuilder.addText("qwe"); codeTextBuilder.addUnicode("ıntəˈnæʃənəl"); codeTextBuilder.addECI("ΑΒΓΔΕ", 9); codeTextBuilder.addAuto("abc"); codeTextBuilder.addBinary("abc"); codeTextBuilder.addURI("backslashes_should_be_doubled\000555:test"); codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10"); let expectedStr = "漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10"; //توليد نص شفري let str = codeTextBuilder.getExtendedCodetext(); //توليد let bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str); bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED); let img = bg.generateBarCodeImage(BarcodeImageFormat.PNG); let r = new BarCodeReader(img, null, DecodeType.HAN_XIN)) let found = r.readBarCodes(); assert.assertEquals(1, found.length); assert.assertEquals(expectedStr, found[0].getCodeText());

```js
new HanXinExtCodetextBuilder()
```

## طرق

| اسم | الوصف |
| --- | --- |
| [addAuto(text)](#addauto) | يضيف جزء نص شفري في وضع Auto |
| [addBinary(text)](#addbinary) | يضيف جزء نص شفري في وضع Binary |
| [addCommonChineseRegionOne(text)](#addcommonchineseregionone) | يضيف جزء نص شفري في وضع Common Chinese Region One |
| [addCommonChineseRegionTwo(text)](#addcommonchineseregiontwo) | يضيف جزء نص شفري في وضع Common Chinese Region Two |
| [addECI(text, encoding)](#addeci) | يضيف جزء نص شفري في وضع ECI |
| [addGB18030FourByte(text)](#addgb18030fourbyte) | يضيف جزء نص شفري في وضع GB18030 Four Byte |
| [addGB18030TwoByte(text)](#addgb18030twobyte) | يضيف جزء نص شفري في وضع GB18030 Two Byte |
| [addGS1(text)](#addgs1) | يضيف جزء نص شفري في وضع GS1 |
| [addNumeric(text)](#addnumeric) | يضيف جزء نص شفري في وضع Numeric |
| [addText(text)](#addtext) | يضيف جزء نص شفري في وضع Text |
| [addUnicode(text)](#addunicode) | يضيف جزء نص شفري في وضع Unicode |
| [addURI(text)](#adduri) | يضيف جزء نص شفري في وضع URI |
| [getExtendedCodetext()](#getextendedcodetext) | يعيد نص شفري من مُنشئ نص شفري الوضع الموسع |

### addAuto(text) {#addauto}

يضيف جزء نص شفري في وضع Auto

| معامل | الوصف |
| --- | --- |
| نص | نص كود |

### addBinary(text) {#addbinary}

يضيف جزء نص شفري في وضع Binary

| معامل | الوصف |
| --- | --- |
| نص | نص كود |

### addCommonChineseRegionOne(text) {#addcommonchineseregionone}

يضيف جزء نص شفري في وضع Common Chinese Region One

| معامل | الوصف |
| --- | --- |
| نص | نص كود |

### addCommonChineseRegionTwo(text) {#addcommonchineseregiontwo}

يضيف جزء نص شفري في وضع Common Chinese Region Two

| معامل | الوصف |
| --- | --- |
| نص | نص كود |

### addECI(text, encoding) {#addeci}

يضيف جزء نص شفري في وضع ECI

| معامل | الوصف |
| --- | --- |
| نص | نص كود |
| الترميز | ترميز ECI بصيغة رقمية |

### addGB18030FourByte(text) {#addgb18030fourbyte}

يضيف جزء نص شفري في وضع GB18030 Four Byte

| معامل | الوصف |
| --- | --- |
| نص | نص كود |

### addGB18030TwoByte(text) {#addgb18030twobyte}

يضيف جزء نص شفري في وضع GB18030 Two Byte

| معامل | الوصف |
| --- | --- |
| نص | نص كود |

### addGS1(text) {#addgs1}

يضيف جزء نص شفري في وضع GS1

| معامل | الوصف |
| --- | --- |
| نص | نص كود |

### addNumeric(text) {#addnumeric}

يضيف جزء نص شفري في وضع Numeric

| معامل | الوصف |
| --- | --- |
| نص | نص كود |

### addText(text) {#addtext}

يضيف جزء نص شفري في وضع Text

| معامل | الوصف |
| --- | --- |
| نص | نص كود |

### addUnicode(text) {#addunicode}

يضيف جزء نص شفري في وضع Unicode

| معامل | الوصف |
| --- | --- |
| نص | نص كود |

### addURI(text) {#adduri}

يضيف جزء نص شفري في وضع URI

| معامل | الوصف |
| --- | --- |
| نص | نص كود |

### getExtendedCodetext() {#getextendedcodetext}

يعيد نص شفري من مُنشئ نص شفري الوضع الموسع

**Returns:** Codetext in Extended mode
