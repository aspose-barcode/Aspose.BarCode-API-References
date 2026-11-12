---
title: "InverseImageMode"
linktitle: "InverseImageMode"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "反転色（輝度）の画像上でバーコードの追加認識を有効または無効にするモード。"
type: docs
weight: 370
url: /ja/nodejs/global/inverseimagemode/
---

## InverseImageMode

反転色（輝度）の画像上でバーコードの追加認識を有効または無効にするモードです。 このサンプルは InverseImage モードの使用方法を示します let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## 値

| 名前 | 説明 |
| --- | --- |
| なし | バーコードを囲む境界がありません |
| FRAME | バーコードを囲むフレーム |
| バー | バーコードを囲む2本の水平バー |
| FRAME_OUT | バーコードを囲むフレーム |
| BAR_OUT | バーコードを囲む2本の水平バー |
