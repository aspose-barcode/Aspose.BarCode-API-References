---
title: "HanXinExtCodetextBuilder"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Генератор расширенного кодтекста для кода Han Xin в расширенном режиме HanXinEncodeMode //Extended codetext mode //create codetext let codeTextBuilder = new HanXinEx"
type: docs
weight: 500
url: /ru/nodejs/aspose.barcode/hanxinextcodetextbuilder/
---

## HanXinExtCodetextBuilder class

Генератор расширенного кодтекста для кода Han Xin в расширенном режиме HanXinEncodeMode //Extended codetext mode //create codetext let codeTextBuilder = new HanXinExtCodetextBuilder(); codeTextBuilder.addGB18030TwoByte("漄"); codeTextBuilder.addGB18030FourByte("㐁"); codeTextBuilder.addCommonChineseRegionOne("全"); codeTextBuilder.addCommonChineseRegionTwo("螅"); codeTextBuilder.addNumeric("123"); codeTextBuilder.addText("qwe"); codeTextBuilder.addUnicode("ıntəˈnæʃənəl"); codeTextBuilder.addECI("ΑΒΓΔΕ", 9); codeTextBuilder.addAuto("abc"); codeTextBuilder.addBinary("abc"); codeTextBuilder.addURI("backslashes_should_be_doubled\000555:test"); codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10"); let expectedStr = "漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10"; //generate codetext let str = codeTextBuilder.getExtendedCodetext(); //generate let bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str); bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED); let img = bg.generateBarCodeImage(BarcodeImageFormat.PNG); let r = new BarCodeReader(img, null, DecodeType.HAN_XIN)) let found = r.readBarCodes(); assert.assertEquals(1, found.length); assert.assertEquals(expectedStr, found[0].getCodeText());

```js
new HanXinExtCodetextBuilder()
```

## Методы

| Имя | Описание |
| --- | --- |
| [addAuto(text)](#addauto) | Добавляет фрагмент кодтекста в режиме Auto |
| [addBinary(text)](#addbinary) | Добавляет фрагмент кодтекста в режиме Binary |
| [addCommonChineseRegionOne(text)](#addcommonchineseregionone) | Добавляет фрагмент кодтекста в режиме Common Chinese Region One |
| [addCommonChineseRegionTwo(text)](#addcommonchineseregiontwo) | Добавляет фрагмент кодтекста в режиме Common Chinese Region Two |
| [addECI(text, encoding)](#addeci) | Добавляет фрагмент кодтекста в режиме ECI |
| [addGB18030FourByte(text)](#addgb18030fourbyte) | Добавляет фрагмент кодтекста в режиме GB18030 Four Byte |
| [addGB18030TwoByte(text)](#addgb18030twobyte) | Добавляет фрагмент кодтекста в режиме GB18030 Two Byte |
| [addGS1(text)](#addgs1) | Добавляет фрагмент кодтекста в режиме GS1 |
| [addNumeric(text)](#addnumeric) | Добавляет фрагмент кодтекста в режиме Numeric |
| [addText(text)](#addtext) | Добавляет фрагмент кодтекста в режиме Text |
| [addUnicode(text)](#addunicode) | Добавляет фрагмент кодтекста в режиме Unicode |
| [addURI(text)](#adduri) | Добавляет фрагмент кодтекста в режиме URI |
| [getExtendedCodetext()](#getextendedcodetext) | Возвращает кодтекст из билдера кодтекста в режиме Extended |

### addAuto(text) {#addauto}

Добавляет фрагмент кодтекста в режиме Auto

| Параметр | Описание |
| --- | --- |
| текст | Строка Codetext |

### addBinary(text) {#addbinary}

Добавляет фрагмент кодтекста в режиме Binary

| Параметр | Описание |
| --- | --- |
| текст | Строка Codetext |

### addCommonChineseRegionOne(text) {#addcommonchineseregionone}

Добавляет фрагмент кодтекста в режиме Common Chinese Region One

| Параметр | Описание |
| --- | --- |
| текст | Строка Codetext |

### addCommonChineseRegionTwo(text) {#addcommonchineseregiontwo}

Добавляет фрагмент кодтекста в режиме Common Chinese Region Two

| Параметр | Описание |
| --- | --- |
| текст | Строка Codetext |

### addECI(text, encoding) {#addeci}

Добавляет фрагмент кодтекста в режиме ECI

| Параметр | Описание |
| --- | --- |
| текст | Строка Codetext |
| кодировка | Кодировка ECI в числовом формате |

### addGB18030FourByte(text) {#addgb18030fourbyte}

Добавляет фрагмент кодтекста в режиме GB18030 Four Byte

| Параметр | Описание |
| --- | --- |
| текст | Строка Codetext |

### addGB18030TwoByte(text) {#addgb18030twobyte}

Добавляет фрагмент кодтекста в режиме GB18030 Two Byte

| Параметр | Описание |
| --- | --- |
| текст | Строка Codetext |

### addGS1(text) {#addgs1}

Добавляет фрагмент кодтекста в режиме GS1

| Параметр | Описание |
| --- | --- |
| текст | Строка Codetext |

### addNumeric(text) {#addnumeric}

Добавляет фрагмент кодтекста в режиме Numeric

| Параметр | Описание |
| --- | --- |
| текст | Строка Codetext |

### addText(text) {#addtext}

Добавляет фрагмент кодтекста в режиме Text

| Параметр | Описание |
| --- | --- |
| текст | Строка Codetext |

### addUnicode(text) {#addunicode}

Добавляет фрагмент кодтекста в режиме Unicode

| Параметр | Описание |
| --- | --- |
| текст | Строка Codetext |

### addURI(text) {#adduri}

Добавляет фрагмент кодтекста в режиме URI

| Параметр | Описание |
| --- | --- |
| текст | Строка Codetext |

### getExtendedCodetext() {#getextendedcodetext}

Возвращает кодтекст из билдера кодтекста в режиме Extended

**Returns:** Codetext in Extended mode
