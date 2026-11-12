---
title: "HanXinExtCodetextBuilder"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Εκτεταμένος δημιουργός κώδικα κειμένου για τον κώδικα Han Xin σε Εκτεταμένη Λειτουργία του HanXinEncodeMode //Λειτουργία εκτεταμένου κώδικα κειμένου //δημιουργία κώδικα κειμένου let codeTextBuilder = new HanXinEx"
type: docs
weight: 500
url: /el/nodejs/aspose.barcode/hanxinextcodetextbuilder/
---

## HanXinExtCodetextBuilder class

Εκτεταμένος δημιουργός κώδικα κειμένου για τον κώδικα Han Xin σε Εκτεταμένη Λειτουργία του HanXinEncodeMode //Λειτουργία εκτεταμένου κώδικα κειμένου //δημιουργία κώδικα κειμένου let codeTextBuilder = new HanXinExtCodetextBuilder(); codeTextBuilder.addGB18030TwoByte("漄"); codeTextBuilder.addGB18030FourByte("㐁"); codeTextBuilder.addCommonChineseRegionOne("全"); codeTextBuilder.addCommonChineseRegionTwo("螅"); codeTextBuilder.addNumeric("123"); codeTextBuilder.addText("qwe"); codeTextBuilder.addUnicode("ıntəˈnæʃənəl"); codeTextBuilder.addECI("ΑΒΓΔΕ", 9); codeTextBuilder.addAuto("abc"); codeTextBuilder.addBinary("abc"); codeTextBuilder.addURI("backslashes_should_be_doubled\000555:test"); codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10"); let expectedStr = "漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10"; //δημιουργία κώδικα κειμένου let str = codeTextBuilder.getExtendedCodetext(); //δημιουργία let bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str); bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED); let img = bg.generateBarCodeImage(BarcodeImageFormat.PNG); let r = new BarCodeReader(img, null, DecodeType.HAN_XIN)) let found = r.readBarCodes(); assert.assertEquals(1, found.length); assert.assertEquals(expectedStr, found[0].getCodeText());

```js
new HanXinExtCodetextBuilder()
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addAuto(text)](#addauto) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Auto |
| [addBinary(text)](#addbinary) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Binary |
| [addCommonChineseRegionOne(text)](#addcommonchineseregionone) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Common Chinese Region One |
| [addCommonChineseRegionTwo(text)](#addcommonchineseregiontwo) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Common Chinese Region Two |
| [addECI(text, encoding)](#addeci) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία ECI |
| [addGB18030FourByte(text)](#addgb18030fourbyte) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία GB18030 Four Byte |
| [addGB18030TwoByte(text)](#addgb18030twobyte) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία GB18030 Two Byte |
| [addGS1(text)](#addgs1) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία GS1 |
| [addNumeric(text)](#addnumeric) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Numeric |
| [addText(text)](#addtext) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Text |
| [addUnicode(text)](#addunicode) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Unicode |
| [addURI(text)](#adduri) | Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία URI |
| [getExtendedCodetext()](#getextendedcodetext) | Επιστρέφει κώδικα κειμένου από τον δημιουργό κώδικα κειμένου σε λειτουργία Extended |

### addAuto(text) {#addauto}

Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Auto

| Παράμετρος | Περιγραφή |
| --- | --- |
| κείμενο | Συμβολοσειρά Codetext |

### addBinary(text) {#addbinary}

Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Binary

| Παράμετρος | Περιγραφή |
| --- | --- |
| κείμενο | Συμβολοσειρά Codetext |

### addCommonChineseRegionOne(text) {#addcommonchineseregionone}

Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Common Chinese Region One

| Παράμετρος | Περιγραφή |
| --- | --- |
| κείμενο | Συμβολοσειρά Codetext |

### addCommonChineseRegionTwo(text) {#addcommonchineseregiontwo}

Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Common Chinese Region Two

| Παράμετρος | Περιγραφή |
| --- | --- |
| κείμενο | Συμβολοσειρά Codetext |

### addECI(text, encoding) {#addeci}

Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία ECI

| Παράμετρος | Περιγραφή |
| --- | --- |
| κείμενο | Συμβολοσειρά Codetext |
| κωδικοποίηση | Κωδικοποίηση ECI σε αριθμητική μορφή |

### addGB18030FourByte(text) {#addgb18030fourbyte}

Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία GB18030 Four Byte

| Παράμετρος | Περιγραφή |
| --- | --- |
| κείμενο | Συμβολοσειρά Codetext |

### addGB18030TwoByte(text) {#addgb18030twobyte}

Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία GB18030 Two Byte

| Παράμετρος | Περιγραφή |
| --- | --- |
| κείμενο | Συμβολοσειρά Codetext |

### addGS1(text) {#addgs1}

Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία GS1

| Παράμετρος | Περιγραφή |
| --- | --- |
| κείμενο | Συμβολοσειρά Codetext |

### addNumeric(text) {#addnumeric}

Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Numeric

| Παράμετρος | Περιγραφή |
| --- | --- |
| κείμενο | Συμβολοσειρά Codetext |

### addText(text) {#addtext}

Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Text

| Παράμετρος | Περιγραφή |
| --- | --- |
| κείμενο | Συμβολοσειρά Codetext |

### addUnicode(text) {#addunicode}

Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία Unicode

| Παράμετρος | Περιγραφή |
| --- | --- |
| κείμενο | Συμβολοσειρά Codetext |

### addURI(text) {#adduri}

Προσθέτει τμήμα κώδικα κειμένου σε λειτουργία URI

| Παράμετρος | Περιγραφή |
| --- | --- |
| κείμενο | Συμβολοσειρά Codetext |

### getExtendedCodetext() {#getextendedcodetext}

Επιστρέφει κώδικα κειμένου από τον δημιουργό κώδικα κειμένου σε λειτουργία Extended

**Returns:** Codetext in Extended mode
