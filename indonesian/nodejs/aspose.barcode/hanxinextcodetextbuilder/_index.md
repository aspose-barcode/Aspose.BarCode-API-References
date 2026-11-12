---
title: "HanXinExtCodetextBuilder"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Generator kode teks yang diperluas untuk Han Xin Code dalam Mode Diperluas HanXinEncodeMode //Mode kode teks diperluas //buat kode teks let codeTextBuilder = new HanXinEx"
type: docs
weight: 500
url: /id/nodejs/aspose.barcode/hanxinextcodetextbuilder/
---

## HanXinExtCodetextBuilder class

Generator kode teks yang diperluas untuk Han Xin Code dalam Mode Diperluas HanXinEncodeMode //Mode kode teks diperluas //buat kode teks let codeTextBuilder = new HanXinExtCodetextBuilder(); codeTextBuilder.addGB18030TwoByte("漄"); codeTextBuilder.addGB18030FourByte("㐁"); codeTextBuilder.addCommonChineseRegionOne("全"); codeTextBuilder.addCommonChineseRegionTwo("螅"); codeTextBuilder.addNumeric("123"); codeTextBuilder.addText("qwe"); codeTextBuilder.addUnicode("ıntəˈnæʃənəl"); codeTextBuilder.addECI("ΑΒΓΔΕ", 9); codeTextBuilder.addAuto("abc"); codeTextBuilder.addBinary("abc"); codeTextBuilder.addURI("backslashes_should_be_doubled\000555:test"); codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10"); let expectedStr = "漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10"; //generate codetext let str = codeTextBuilder.getExtendedCodetext(); //generate let bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str); bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED); let img = bg.generateBarCodeImage(BarcodeImageFormat.PNG); let r = new BarCodeReader(img, null, DecodeType.HAN_XIN)) let found = r.readBarCodes(); assert.assertEquals(1, found.length); assert.assertEquals(expectedStr, found[0].getCodeText());

```js
new HanXinExtCodetextBuilder()
```

## Metode

| Nama | Deskripsi |
| --- | --- |
| [addAuto(text)](#addauto) | Menambahkan fragmen kode teks dalam mode Auto |
| [addBinary(text)](#addbinary) | Menambahkan fragmen kode teks dalam mode Biner |
| [addCommonChineseRegionOne(text)](#addcommonchineseregionone) | Menambahkan fragmen kode teks dalam mode Common Chinese Region One |
| [addCommonChineseRegionTwo(text)](#addcommonchineseregiontwo) | Menambahkan fragmen kode teks dalam mode Common Chinese Region Two |
| [addECI(text, encoding)](#addeci) | Menambahkan fragmen kode teks dalam mode ECI |
| [addGB18030FourByte(text)](#addgb18030fourbyte) | Menambahkan fragmen kode teks dalam mode GB18030 Four Byte |
| [addGB18030TwoByte(text)](#addgb18030twobyte) | Menambahkan fragmen kode teks dalam mode GB18030 Two Byte |
| [addGS1(text)](#addgs1) | Menambahkan fragmen kode teks dalam mode GS1 |
| [addNumeric(text)](#addnumeric) | Menambahkan fragmen kode teks dalam mode Numerik |
| [addText(text)](#addtext) | Menambahkan fragmen kode teks dalam mode Teks |
| [addUnicode(text)](#addunicode) | Menambahkan fragmen kode teks dalam mode Unicode |
| [addURI(text)](#adduri) | Menambahkan fragmen kode teks dalam mode URI |
| [getExtendedCodetext()](#getextendedcodetext) | Mengembalikan kode teks dari pembuat kode teks mode Diperluas |

### addAuto(text) {#addauto}

Menambahkan fragmen kode teks dalam mode Auto

| Parameter | Deskripsi |
| --- | --- |
| teks | String Codetext |

### addBinary(text) {#addbinary}

Menambahkan fragmen kode teks dalam mode Biner

| Parameter | Deskripsi |
| --- | --- |
| teks | String Codetext |

### addCommonChineseRegionOne(text) {#addcommonchineseregionone}

Menambahkan fragmen kode teks dalam mode Common Chinese Region One

| Parameter | Deskripsi |
| --- | --- |
| teks | String Codetext |

### addCommonChineseRegionTwo(text) {#addcommonchineseregiontwo}

Menambahkan fragmen kode teks dalam mode Common Chinese Region Two

| Parameter | Deskripsi |
| --- | --- |
| teks | String Codetext |

### addECI(text, encoding) {#addeci}

Menambahkan fragmen kode teks dalam mode ECI

| Parameter | Deskripsi |
| --- | --- |
| teks | String Codetext |
| enkoding | Enkoding ECI dalam format angka |

### addGB18030FourByte(text) {#addgb18030fourbyte}

Menambahkan fragmen kode teks dalam mode GB18030 Four Byte

| Parameter | Deskripsi |
| --- | --- |
| teks | String Codetext |

### addGB18030TwoByte(text) {#addgb18030twobyte}

Menambahkan fragmen kode teks dalam mode GB18030 Two Byte

| Parameter | Deskripsi |
| --- | --- |
| teks | String Codetext |

### addGS1(text) {#addgs1}

Menambahkan fragmen kode teks dalam mode GS1

| Parameter | Deskripsi |
| --- | --- |
| teks | String Codetext |

### addNumeric(text) {#addnumeric}

Menambahkan fragmen kode teks dalam mode Numerik

| Parameter | Deskripsi |
| --- | --- |
| teks | String Codetext |

### addText(text) {#addtext}

Menambahkan fragmen kode teks dalam mode Teks

| Parameter | Deskripsi |
| --- | --- |
| teks | String Codetext |

### addUnicode(text) {#addunicode}

Menambahkan fragmen kode teks dalam mode Unicode

| Parameter | Deskripsi |
| --- | --- |
| teks | String Codetext |

### addURI(text) {#adduri}

Menambahkan fragmen kode teks dalam mode URI

| Parameter | Deskripsi |
| --- | --- |
| teks | String Codetext |

### getExtendedCodetext() {#getextendedcodetext}

Mengembalikan kode teks dari pembuat kode teks mode Diperluas

**Returns:** Codetext in Extended mode
