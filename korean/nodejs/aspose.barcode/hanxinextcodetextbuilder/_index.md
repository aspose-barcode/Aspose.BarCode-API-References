---
title: "HanXinExtCodetextBuilder"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "Han Xin Code의 확장 모드인 HanXinEncodeMode용 확장 코드텍스트 생성기 //Extended codetext mode //create codetext let codeTextBuilder = new HanXinEx"
type: docs
weight: 500
url: /ko/nodejs/aspose.barcode/hanxinextcodetextbuilder/
---

## HanXinExtCodetextBuilder class

Han Xin Code의 확장 모드인 HanXinEncodeMode용 확장 코드텍스트 생성기 //Extended codetext mode //create codetext let codeTextBuilder = new HanXinExtCodetextBuilder(); codeTextBuilder.addGB18030TwoByte("漄"); codeTextBuilder.addGB18030FourByte("㐁"); codeTextBuilder.addCommonChineseRegionOne("全"); codeTextBuilder.addCommonChineseRegionTwo("螅"); codeTextBuilder.addNumeric("123"); codeTextBuilder.addText("qwe"); codeTextBuilder.addUnicode("ıntəˈnæʃənəl"); codeTextBuilder.addECI("ΑΒΓΔΕ", 9); codeTextBuilder.addAuto("abc"); codeTextBuilder.addBinary("abc"); codeTextBuilder.addURI("backslashes_should_be_doubled\000555:test"); codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10"); let expectedStr = "漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10"; //generate codetext let str = codeTextBuilder.getExtendedCodetext(); //generate let bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str); bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED); let img = bg.generateBarCodeImage(BarcodeImageFormat.PNG); let r = new BarCodeReader(img, null, DecodeType.HAN_XIN)) let found = r.readBarCodes(); assert.assertEquals(1, found.length); assert.assertEquals(expectedStr, found[0].getCodeText());

```js
new HanXinExtCodetextBuilder()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addAuto(text)](#addauto) | 자동 모드에서 코드텍스트 조각을 추가합니다 |
| [addBinary(text)](#addbinary) | 이진 모드에서 코드텍스트 조각을 추가합니다 |
| [addCommonChineseRegionOne(text)](#addcommonchineseregionone) | 공통 중국 지역 1 모드에서 코드텍스트 조각을 추가합니다 |
| [addCommonChineseRegionTwo(text)](#addcommonchineseregiontwo) | 공통 중국 지역 2 모드에서 코드텍스트 조각을 추가합니다 |
| [addECI(text, encoding)](#addeci) | ECI 모드에서 코드텍스트 조각을 추가합니다 |
| [addGB18030FourByte(text)](#addgb18030fourbyte) | GB18030 4바이트 모드에서 코드텍스트 조각을 추가합니다 |
| [addGB18030TwoByte(text)](#addgb18030twobyte) | GB18030 2바이트 모드에서 코드텍스트 조각을 추가합니다 |
| [addGS1(text)](#addgs1) | GS1 모드에서 코드텍스트 조각을 추가합니다 |
| [addNumeric(text)](#addnumeric) | 숫자 모드에서 코드텍스트 조각을 추가합니다 |
| [addText(text)](#addtext) | 텍스트 모드에서 코드텍스트 조각을 추가합니다 |
| [addUnicode(text)](#addunicode) | 유니코드 모드에서 코드텍스트 조각을 추가합니다 |
| [addURI(text)](#adduri) | URI 모드에서 코드텍스트 조각을 추가합니다 |
| [getExtendedCodetext()](#getextendedcodetext) | 확장 모드 코드텍스트 빌더에서 코드텍스트를 반환합니다 |

### addAuto(text) {#addauto}

자동 모드에서 코드텍스트 조각을 추가합니다

| 매개변수 | 설명 |
| --- | --- |
| 텍스트 | 코드텍스트 문자열 |

### addBinary(text) {#addbinary}

이진 모드에서 코드텍스트 조각을 추가합니다

| 매개변수 | 설명 |
| --- | --- |
| 텍스트 | 코드텍스트 문자열 |

### addCommonChineseRegionOne(text) {#addcommonchineseregionone}

공통 중국 지역 1 모드에서 코드텍스트 조각을 추가합니다

| 매개변수 | 설명 |
| --- | --- |
| 텍스트 | 코드텍스트 문자열 |

### addCommonChineseRegionTwo(text) {#addcommonchineseregiontwo}

공통 중국 지역 2 모드에서 코드텍스트 조각을 추가합니다

| 매개변수 | 설명 |
| --- | --- |
| 텍스트 | 코드텍스트 문자열 |

### addECI(text, encoding) {#addeci}

ECI 모드에서 코드텍스트 조각을 추가합니다

| 매개변수 | 설명 |
| --- | --- |
| 텍스트 | 코드텍스트 문자열 |
| 인코딩 | 숫자 형식의 ECI 인코딩 |

### addGB18030FourByte(text) {#addgb18030fourbyte}

GB18030 4바이트 모드에서 코드텍스트 조각을 추가합니다

| 매개변수 | 설명 |
| --- | --- |
| 텍스트 | 코드텍스트 문자열 |

### addGB18030TwoByte(text) {#addgb18030twobyte}

GB18030 2바이트 모드에서 코드텍스트 조각을 추가합니다

| 매개변수 | 설명 |
| --- | --- |
| 텍스트 | 코드텍스트 문자열 |

### addGS1(text) {#addgs1}

GS1 모드에서 코드텍스트 조각을 추가합니다

| 매개변수 | 설명 |
| --- | --- |
| 텍스트 | 코드텍스트 문자열 |

### addNumeric(text) {#addnumeric}

숫자 모드에서 코드텍스트 조각을 추가합니다

| 매개변수 | 설명 |
| --- | --- |
| 텍스트 | 코드텍스트 문자열 |

### addText(text) {#addtext}

텍스트 모드에서 코드텍스트 조각을 추가합니다

| 매개변수 | 설명 |
| --- | --- |
| 텍스트 | 코드텍스트 문자열 |

### addUnicode(text) {#addunicode}

유니코드 모드에서 코드텍스트 조각을 추가합니다

| 매개변수 | 설명 |
| --- | --- |
| 텍스트 | 코드텍스트 문자열 |

### addURI(text) {#adduri}

URI 모드에서 코드텍스트 조각을 추가합니다

| 매개변수 | 설명 |
| --- | --- |
| 텍스트 | 코드텍스트 문자열 |

### getExtendedCodetext() {#getextendedcodetext}

확장 모드 코드텍스트 빌더에서 코드텍스트를 반환합니다

**Returns:** Codetext in Extended mode
