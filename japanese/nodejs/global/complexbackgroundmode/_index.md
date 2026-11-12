---
title: "ComplexBackgroundMode"
linktitle: "ComplexBackgroundMode"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "カラー画像上のカラーバーコードの追加認識を有効または無効にするモード。"
type: docs
weight: 160
url: /ja/nodejs/global/complexbackgroundmode/
---

## ComplexBackgroundMode

カラー画像上のカラーバーコードの追加認識を有効または無効にするモードです。このサンプルは ComplexBackground モードの使用方法を示します let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## 値

| 名前 | 説明 |
| --- | --- |
| C_TABLE | C_TABLE を使用して顧客情報を解釈します。A..Z、a..z、1..9、スペース、および # 記号を許可します。 |
| N_TABLE | N_TABLE を使用して顧客情報を解釈します。数字を許可します。 |
| OTHER | 顧客情報を解釈しません。0、1、2、または 3 記号のみを許可します。 |
