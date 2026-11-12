---
title: "HanXinExtCodetextBuilder"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "Han Xin Code 扩展模式的扩展码文本生成器（适用于 HanXinEncodeMode） //扩展码文本模式 //创建码文本 let codeTextBuilder = new HanXinEx"
type: docs
weight: 500
url: /zh/nodejs/aspose.barcode/hanxinextcodetextbuilder/
---

## HanXinExtCodetextBuilder class

Han Xin Code 扩展模式的扩展码文本生成器（适用于 HanXinEncodeMode） //扩展码文本模式 //创建码文本 let codeTextBuilder = new HanXinExtCodetextBuilder(); codeTextBuilder.addGB18030TwoByte("漄"); codeTextBuilder.addGB18030FourByte("㐁"); codeTextBuilder.addCommonChineseRegionOne("全"); codeTextBuilder.addCommonChineseRegionTwo("螅"); codeTextBuilder.addNumeric("123"); codeTextBuilder.addText("qwe"); codeTextBuilder.addUnicode("ıntəˈnæʃənəl"); codeTextBuilder.addECI("ΑΒΓΔΕ", 9); codeTextBuilder.addAuto("abc"); codeTextBuilder.addBinary("abc"); codeTextBuilder.addURI("backslashes_should_be_doubled\000555:test"); codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10"); let expectedStr = "漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10"; //generate codetext let str = codeTextBuilder.getExtendedCodetext(); //generate let bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str); bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED); let img = bg.generateBarCodeImage(BarcodeImageFormat.PNG); let r = new BarCodeReader(img, null, DecodeType.HAN_XIN)) let found = r.readBarCodes(); assert.assertEquals(1, found.length); assert.assertEquals(expectedStr, found[0].getCodeText());

```js
new HanXinExtCodetextBuilder()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [addAuto(text)](#addauto) | 在 Auto 模式下添加码文本片段 |
| [addBinary(text)](#addbinary) | 在 Binary 模式下添加码文本片段 |
| [addCommonChineseRegionOne(text)](#addcommonchineseregionone) | 在 Common Chinese Region One 模式下添加码文本片段 |
| [addCommonChineseRegionTwo(text)](#addcommonchineseregiontwo) | 在 Common Chinese Region Two 模式下添加码文本片段 |
| [addECI(text, encoding)](#addeci) | 在 ECI 模式下添加码文本片段 |
| [addGB18030FourByte(text)](#addgb18030fourbyte) | 在 GB18030 Four Byte 模式下添加码文本片段 |
| [addGB18030TwoByte(text)](#addgb18030twobyte) | 在 GB18030 Two Byte 模式下添加码文本片段 |
| [addGS1(text)](#addgs1) | 在 GS1 模式下添加码文本片段 |
| [addNumeric(text)](#addnumeric) | 在 Numeric 模式下添加码文本片段 |
| [addText(text)](#addtext) | 在 Text 模式下添加码文本片段 |
| [addUnicode(text)](#addunicode) | 在 Unicode 模式下添加码文本片段 |
| [addURI(text)](#adduri) | 在 URI 模式下添加码文本片段 |
| [getExtendedCodetext()](#getextendedcodetext) | 从扩展模式码文本构建器返回码文本 |

### addAuto(text) {#addauto}

在 Auto 模式下添加码文本片段

| 参数 | 描述 |
| --- | --- |
| 文本 | 码文本字符串 |

### addBinary(text) {#addbinary}

在 Binary 模式下添加码文本片段

| 参数 | 描述 |
| --- | --- |
| 文本 | 码文本字符串 |

### addCommonChineseRegionOne(text) {#addcommonchineseregionone}

在 Common Chinese Region One 模式下添加码文本片段

| 参数 | 描述 |
| --- | --- |
| 文本 | 码文本字符串 |

### addCommonChineseRegionTwo(text) {#addcommonchineseregiontwo}

在 Common Chinese Region Two 模式下添加码文本片段

| 参数 | 描述 |
| --- | --- |
| 文本 | 码文本字符串 |

### addECI(text, encoding) {#addeci}

在 ECI 模式下添加码文本片段

| 参数 | 描述 |
| --- | --- |
| 文本 | 码文本字符串 |
| 编码 | 数字格式的 ECI 编码 |

### addGB18030FourByte(text) {#addgb18030fourbyte}

在 GB18030 Four Byte 模式下添加码文本片段

| 参数 | 描述 |
| --- | --- |
| 文本 | 码文本字符串 |

### addGB18030TwoByte(text) {#addgb18030twobyte}

在 GB18030 Two Byte 模式下添加码文本片段

| 参数 | 描述 |
| --- | --- |
| 文本 | 码文本字符串 |

### addGS1(text) {#addgs1}

在 GS1 模式下添加码文本片段

| 参数 | 描述 |
| --- | --- |
| 文本 | 码文本字符串 |

### addNumeric(text) {#addnumeric}

在 Numeric 模式下添加码文本片段

| 参数 | 描述 |
| --- | --- |
| 文本 | 码文本字符串 |

### addText(text) {#addtext}

在 Text 模式下添加码文本片段

| 参数 | 描述 |
| --- | --- |
| 文本 | 码文本字符串 |

### addUnicode(text) {#addunicode}

在 Unicode 模式下添加码文本片段

| 参数 | 描述 |
| --- | --- |
| 文本 | 码文本字符串 |

### addURI(text) {#adduri}

在 URI 模式下添加码文本片段

| 参数 | 描述 |
| --- | --- |
| 文本 | 码文本字符串 |

### getExtendedCodetext() {#getextendedcodetext}

从扩展模式码文本构建器返回码文本

**Returns:** Codetext in Extended mode
