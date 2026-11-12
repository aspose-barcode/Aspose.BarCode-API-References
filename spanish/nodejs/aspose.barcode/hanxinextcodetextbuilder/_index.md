---
title: "HanXinExtCodetextBuilder"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Generador de codetexto extendido para Han Xin Code en el Modo Extendido de HanXinEncodeMode //Modo de codetexto extendido //crear codetexto let codeTextBuilder = new HanXinEx"
type: docs
weight: 500
url: /es/nodejs/aspose.barcode/hanxinextcodetextbuilder/
---

## HanXinExtCodetextBuilder class

Generador de codetexto extendido para Han Xin Code en el Modo Extendido de HanXinEncodeMode //Modo de codetexto extendido //crear codetexto let codeTextBuilder = new HanXinExtCodetextBuilder(); codeTextBuilder.addGB18030TwoByte("漄"); codeTextBuilder.addGB18030FourByte("㐁"); codeTextBuilder.addCommonChineseRegionOne("全"); codeTextBuilder.addCommonChineseRegionTwo("螅"); codeTextBuilder.addNumeric("123"); codeTextBuilder.addText("qwe"); codeTextBuilder.addUnicode("ıntəˈnæʃənəl"); codeTextBuilder.addECI("ΑΒΓΔΕ", 9); codeTextBuilder.addAuto("abc"); codeTextBuilder.addBinary("abc"); codeTextBuilder.addURI("backslashes_should_be_doubled\000555:test"); codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10"); let expectedStr = "漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10"; //generar codetexto let str = codeTextBuilder.getExtendedCodetext(); //generar let bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str); bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED); let img = bg.generateBarCodeImage(BarcodeImageFormat.PNG); let r = new BarCodeReader(img, null, DecodeType.HAN_XIN)) let found = r.readBarCodes(); assert.assertEquals(1, found.length); assert.assertEquals(expectedStr, found[0].getCodeText());

```js
new HanXinExtCodetextBuilder()
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addAuto(text)](#addauto) | Añade fragmento de codetexto en modo Auto |
| [addBinary(text)](#addbinary) | Añade fragmento de codetexto en modo Binario |
| [addCommonChineseRegionOne(text)](#addcommonchineseregionone) | Añade fragmento de codetexto en modo Región China Común Uno |
| [addCommonChineseRegionTwo(text)](#addcommonchineseregiontwo) | Añade fragmento de codetexto en modo Región China Común Dos |
| [addECI(text, encoding)](#addeci) | Añade fragmento de codetexto en modo ECI |
| [addGB18030FourByte(text)](#addgb18030fourbyte) | Añade fragmento de codetexto en modo GB18030 de Cuatro Bytes |
| [addGB18030TwoByte(text)](#addgb18030twobyte) | Añade fragmento de codetexto en modo GB18030 de Dos Bytes |
| [addGS1(text)](#addgs1) | Añade fragmento de codetexto en modo GS1 |
| [addNumeric(text)](#addnumeric) | Añade fragmento de codetexto en modo Numérico |
| [addText(text)](#addtext) | Añade fragmento de codetexto en modo Texto |
| [addUnicode(text)](#addunicode) | Añade fragmento de codetexto en modo Unicode |
| [addURI(text)](#adduri) | Añade fragmento de codetexto en modo URI |
| [getExtendedCodetext()](#getextendedcodetext) | Devuelve el codetexto del generador de codetexto en modo Extendido |

### addAuto(text) {#addauto}

Añade fragmento de codetexto en modo Auto

| Parámetro | Descripción |
| --- | --- |
| texto | Cadena de Codetext |

### addBinary(text) {#addbinary}

Añade fragmento de codetexto en modo Binario

| Parámetro | Descripción |
| --- | --- |
| texto | Cadena de Codetext |

### addCommonChineseRegionOne(text) {#addcommonchineseregionone}

Añade fragmento de codetexto en modo Región China Común Uno

| Parámetro | Descripción |
| --- | --- |
| texto | Cadena de Codetext |

### addCommonChineseRegionTwo(text) {#addcommonchineseregiontwo}

Añade fragmento de codetexto en modo Región China Común Dos

| Parámetro | Descripción |
| --- | --- |
| texto | Cadena de Codetext |

### addECI(text, encoding) {#addeci}

Añade fragmento de codetexto en modo ECI

| Parámetro | Descripción |
| --- | --- |
| texto | Cadena de Codetext |
| codificación | Codificación ECI en formato numérico |

### addGB18030FourByte(text) {#addgb18030fourbyte}

Añade fragmento de codetexto en modo GB18030 de Cuatro Bytes

| Parámetro | Descripción |
| --- | --- |
| texto | Cadena de Codetext |

### addGB18030TwoByte(text) {#addgb18030twobyte}

Añade fragmento de codetexto en modo GB18030 de Dos Bytes

| Parámetro | Descripción |
| --- | --- |
| texto | Cadena de Codetext |

### addGS1(text) {#addgs1}

Añade fragmento de codetexto en modo GS1

| Parámetro | Descripción |
| --- | --- |
| texto | Cadena de Codetext |

### addNumeric(text) {#addnumeric}

Añade fragmento de codetexto en modo Numérico

| Parámetro | Descripción |
| --- | --- |
| texto | Cadena de Codetext |

### addText(text) {#addtext}

Añade fragmento de codetexto en modo Texto

| Parámetro | Descripción |
| --- | --- |
| texto | Cadena de Codetext |

### addUnicode(text) {#addunicode}

Añade fragmento de codetexto en modo Unicode

| Parámetro | Descripción |
| --- | --- |
| texto | Cadena de Codetext |

### addURI(text) {#adduri}

Añade fragmento de codetexto en modo URI

| Parámetro | Descripción |
| --- | --- |
| texto | Cadena de Codetext |

### getExtendedCodetext() {#getextendedcodetext}

Devuelve el codetexto del generador de codetexto en modo Extendido

**Returns:** Codetext in Extended mode
