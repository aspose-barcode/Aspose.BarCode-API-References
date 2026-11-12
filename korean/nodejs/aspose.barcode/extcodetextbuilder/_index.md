---
title: "ExtCodetextBuilder"
linktitle: "ExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "Extended Codetext Mode의 자동 코드텍스트 생성을 위한 도우미 클래스"
type: docs
weight: 400
url: /ko/nodejs/aspose.barcode/extcodetextbuilder/
---

## ExtCodetextBuilder class

Extended Codetext Mode의 자동 코드텍스트 생성을 위한 도우미 클래스

```js
new ExtCodetextBuilder()
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [addECICodetext(ECIEncoding, codetext)](#addecicodetext) | Extended Channel Identifier와 함께 코드 텍스트를 추가합니다 |
| [addPlainCodetext(codetext)](#addplaincodetext) | 확장 코드 텍스트 항목에 일반 코드 텍스트를 추가합니다 |
| [clear()](#clear) | 확장 코드 텍스트 항목을 지웁니다 |
| [getExtendedCodetext()](#getextendedcodetext) | 생성 항목 목록에서 확장 코드 텍스트를 생성합니다 |

### addECICodetext(ECIEncoding, codetext) {#addecicodetext}

Extended Channel Identifier와 함께 코드 텍스트를 추가합니다

| 매개변수 | 설명 |
| --- | --- |
| ECIEncoding | 확장 채널 식별자 |
| codetext | Extended Channel Identifier와 함께 확장 코드 텍스트 항목으로 추가할 유니코드 코드 텍스트 |

### addPlainCodetext(codetext) {#addplaincodetext}

확장 코드 텍스트 항목에 일반 코드 텍스트를 추가합니다

| 매개변수 | 설명 |
| --- | --- |
| codetext | 확장 코드텍스트 항목으로 추가할 유니코드 코드텍스트 |

### clear() {#clear}

확장 코드 텍스트 항목을 지웁니다

### getExtendedCodetext() {#getextendedcodetext}

생성 항목 목록에서 확장 코드 텍스트를 생성합니다

**Returns:** Return string of extended codetext
