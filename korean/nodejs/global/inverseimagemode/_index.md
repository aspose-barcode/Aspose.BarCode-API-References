---
title: "InverseImageMode"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "역색(휘도) 이미지에서 바코드의 추가 인식을 활성화하거나 비활성화하는 모드."
type: docs
weight: 370
url: /ko/nodejs/global/inverseimagemode/
---

## InverseImageMode

역색(휘도) 이미지에서 바코드 추가 인식을 활성화하거나 비활성화하는 모드입니다. 이 샘플은 InverseImage 모드를 사용하는 방법을 보여줍니다 let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## 값

| 이름 | 설명 |
| --- | --- |
| NONE | 바코드를 둘러싼 경계가 없음 |
| FRAME | 바코드를 둘러싼 프레임 |
| BAR | 바코드를 둘러싸는 두 개의 수평 막대 |
| FRAME_OUT | 바코드를 둘러싼 프레임 |
| BAR_OUT | 바코드를 둘러싸는 두 개의 수평 막대 |
