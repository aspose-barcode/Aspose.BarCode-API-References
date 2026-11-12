---
title: "BarcodeQualityMode"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "선택된 품질로 바코드 요소를 인식하는 메서드를 활성화하는 모드."
type: docs
weight: 80
url: /ko/nodejs/global/barcodequalitymode/
---

## BarcodeQualityMode

선택된 품질로 바코드 요소를 인식하도록 메서드를 활성화하는 모드입니다. 품질이 낮은 바코드 요소는 인식을 느리게 하는 더 많은 복잡한 메서드가 필요합니다. 이 샘플은 BarcodeQuality 모드를 사용하는 방법을 보여줍니다 let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## 값

| 이름 | 설명 |
| --- | --- |
| SOLID | 실선(단선)을 지정합니다. |
| DASH | 대시(-)로 구성된 선을 지정합니다. |
| DOT | 점(.)으로 구성된 선을 지정합니다. |
| DASH_DOT | 대시-점 패턴이 반복되는 선을 지정합니다. |
| DASH_DOT_DOT | 대시-점-점 패턴이 반복되는 선을 지정합니다. |
