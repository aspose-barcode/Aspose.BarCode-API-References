---
title: "HanXinExtCodetextBuilder"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "Han Xinコードの拡張モード（HanXinEncodeMode）用拡張コードテキストジェネレータ //拡張コードテキストモード //コードテキストを作成 let codeTextBuilder = new HanXinEx"
type: docs
weight: 500
url: /ja/nodejs/aspose.barcode/hanxinextcodetextbuilder/
---

## HanXinExtCodetextBuilder class

Han Xinコードの拡張モード（HanXinEncodeMode）用拡張コードテキストジェネレータ //拡張コードテキストモード //コードテキストを作成 let codeTextBuilder = new HanXinExtCodetextBuilder(); codeTextBuilder.addGB18030TwoByte("漄"); codeTextBuilder.addGB18030FourByte("㐁"); codeTextBuilder.addCommonChineseRegionOne("全"); codeTextBuilder.addCommonChineseRegionTwo("螅"); codeTextBuilder.addNumeric("123"); codeTextBuilder.addText("qwe"); codeTextBuilder.addUnicode("ıntəˈnæʃənəl"); codeTextBuilder.addECI("ΑΒΓΔΕ", 9); codeTextBuilder.addAuto("abc"); codeTextBuilder.addBinary("abc"); codeTextBuilder.addURI("backslashes_should_be_doubled\\000555:test"); codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10"); let expectedStr = "漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10"; //コードテキストを生成 let str = codeTextBuilder.getExtendedCodetext(); //生成 let bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str); bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED); let img = bg.generateBarCodeImage(BarcodeImageFormat.PNG); let r = new BarCodeReader(img, null, DecodeType.HAN_XIN)) let found = r.readBarCodes(); assert.assertEquals(1, found.length); assert.assertEquals(expectedStr, found[0].getCodeText());

```js
new HanXinExtCodetextBuilder()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addAuto(text)](#addauto) | Autoモードでコードテキストフラグメントを追加します |
| [addBinary(text)](#addbinary) | Binaryモードでコードテキストフラグメントを追加します |
| [addCommonChineseRegionOne(text)](#addcommonchineseregionone) | Common Chinese Region Oneモードでコードテキストフラグメントを追加します |
| [addCommonChineseRegionTwo(text)](#addcommonchineseregiontwo) | Common Chinese Region Twoモードでコードテキストフラグメントを追加します |
| [addECI(text, encoding)](#addeci) | ECIモードでコードテキストフラグメントを追加します |
| [addGB18030FourByte(text)](#addgb18030fourbyte) | GB18030 Four Byteモードでコードテキストフラグメントを追加します |
| [addGB18030TwoByte(text)](#addgb18030twobyte) | GB18030 Two Byteモードでコードテキストフラグメントを追加します |
| [addGS1(text)](#addgs1) | GS1モードでコードテキストフラグメントを追加します |
| [addNumeric(text)](#addnumeric) | Numericモードでコードテキストフラグメントを追加します |
| [addText(text)](#addtext) | Textモードでコードテキストフラグメントを追加します |
| [addUnicode(text)](#addunicode) | Unicodeモードでコードテキストフラグメントを追加します |
| [addURI(text)](#adduri) | URIモードでコードテキストフラグメントを追加します |
| [getExtendedCodetext()](#getextendedcodetext) | 拡張モードのコードテキストビルダーからコードテキストを返します |

### addAuto(text) {#addauto}

Autoモードでコードテキストフラグメントを追加します

| パラメータ | 説明 |
| --- | --- |
| テキスト | コードテキスト文字列 |

### addBinary(text) {#addbinary}

Binaryモードでコードテキストフラグメントを追加します

| パラメータ | 説明 |
| --- | --- |
| テキスト | コードテキスト文字列 |

### addCommonChineseRegionOne(text) {#addcommonchineseregionone}

Common Chinese Region Oneモードでコードテキストフラグメントを追加します

| パラメータ | 説明 |
| --- | --- |
| テキスト | コードテキスト文字列 |

### addCommonChineseRegionTwo(text) {#addcommonchineseregiontwo}

Common Chinese Region Twoモードでコードテキストフラグメントを追加します

| パラメータ | 説明 |
| --- | --- |
| テキスト | コードテキスト文字列 |

### addECI(text, encoding) {#addeci}

ECIモードでコードテキストフラグメントを追加します

| パラメータ | 説明 |
| --- | --- |
| テキスト | コードテキスト文字列 |
| エンコーディング | 数値形式のECIエンコーディング |

### addGB18030FourByte(text) {#addgb18030fourbyte}

GB18030 Four Byteモードでコードテキストフラグメントを追加します

| パラメータ | 説明 |
| --- | --- |
| テキスト | コードテキスト文字列 |

### addGB18030TwoByte(text) {#addgb18030twobyte}

GB18030 Two Byteモードでコードテキストフラグメントを追加します

| パラメータ | 説明 |
| --- | --- |
| テキスト | コードテキスト文字列 |

### addGS1(text) {#addgs1}

GS1モードでコードテキストフラグメントを追加します

| パラメータ | 説明 |
| --- | --- |
| テキスト | コードテキスト文字列 |

### addNumeric(text) {#addnumeric}

Numericモードでコードテキストフラグメントを追加します

| パラメータ | 説明 |
| --- | --- |
| テキスト | コードテキスト文字列 |

### addText(text) {#addtext}

Textモードでコードテキストフラグメントを追加します

| パラメータ | 説明 |
| --- | --- |
| テキスト | コードテキスト文字列 |

### addUnicode(text) {#addunicode}

Unicodeモードでコードテキストフラグメントを追加します

| パラメータ | 説明 |
| --- | --- |
| テキスト | コードテキスト文字列 |

### addURI(text) {#adduri}

URIモードでコードテキストフラグメントを追加します

| パラメータ | 説明 |
| --- | --- |
| テキスト | コードテキスト文字列 |

### getExtendedCodetext() {#getextendedcodetext}

拡張モードのコードテキストビルダーからコードテキストを返します

**Returns:** Codetext in Extended mode
