---
title: "ComplexBackgroundMode"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "컬러 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드."
type: docs
weight: 160
url: /ko/nodejs/global/complexbackgroundmode/
---

## ComplexBackgroundMode

색상 이미지에서 컬러 바코드의 추가 인식을 활성화하거나 비활성화하는 모드입니다. 이 샘플은 ComplexBackground 모드를 사용하는 방법을 보여줍니다 let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## 값

| 이름 | 설명 |
| --- | --- |
| C_TABLE | C_TABLE을 사용하여 고객 정보를 해석합니다. A..Z, a..z, 1..9, 공백 및 # 기호를 허용합니다. |
| N_TABLE | N_TABLE을 사용하여 고객 정보를 해석합니다. 숫자를 허용합니다. |
| OTHER | 고객 정보를 해석하지 않습니다. 0, 1, 2 또는 3 기호만 허용합니다. |
