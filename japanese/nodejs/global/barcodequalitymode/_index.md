---
title: "BarcodeQualityMode"
linktitle: "BarcodeQualityMode"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "選択された品質でバーコード要素を認識するメソッドを有効にするモード。"
type: docs
weight: 80
url: /ja/nodejs/global/barcodequalitymode/
---

## BarcodeQualityMode

選択された品質でバーコード要素を認識するメソッドを有効にするモードです。品質が低いバーコード要素は、より多くの高度なメソッドが必要となり、認識が遅くなります。このサンプルは BarcodeQuality モードの使用方法を示します。let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## 値

| 名前 | 説明 |
| --- | --- |
| SOLID | 実線を指定します。 |
| DASH | 破線で構成された線を指定します。 |
| DOT | 点線で構成された線を指定します。 |
| DASH_DOT | 破線と点の繰り返しパターンで構成された線を指定します。 |
| DASH_DOT_DOT | 破線と点点の繰り返しパターンで構成された線を指定します。 |
