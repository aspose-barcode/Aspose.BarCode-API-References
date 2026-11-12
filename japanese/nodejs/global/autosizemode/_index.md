---
title: "AutoSizeMode"
linktitle: "AutoSizeMode"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "自動サイズ調整モードのさまざまなタイプを指定します。"
type: docs
weight: 20
url: /ja/nodejs/global/autosizemode/
---

## AutoSizeMode

自動サイズモードのさまざまなタイプを指定します。デフォルト値は AutoSizeMode.NONE です。

## 値

| 名前 | 説明 |
| --- | --- |
| なし | 自動リサイズは無効です。既定値です。 |
| NEAREST | バーコードは、BarCodeWidth および BarCodeHeight プロパティで指定された、最も近い最小サイズにリサイズされます。 |
| INTERPOLATION | 指定されたサイズにバーコードを少し拡大縮小してリサイズしますが、補間によるスケーリングのため、場合によっては若干の損傷が生じることがあります。サイズは BarcodeGenerator.BarCodeWidth および BarcodeGenerator.BarCodeHeight プロパティで指定できます。 |
