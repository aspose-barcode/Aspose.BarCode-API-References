---
title: "EnableChecksum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "1Dバーコードの生成時にチェックサムを有効にします。"
type: docs
weight: 250
url: /ja/nodejs/global/enablechecksum/
---

## EnableChecksum

1Dバーコードの生成時にチェックサムを有効にします。デフォルトは、チェックサムが必須のシンボロジーでは「はい」とみなされ、チェックサムが任意の場合は「いいえ」とみなされます。チェックサムが使用されないシンボロジー：Codabar。チェックサムが可能なシンボロジー：Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN。チェックサムが常に使用されるシンボロジー：残りのシンボロジー

## 値

| 名前 | 説明 |
| --- | --- |
| DEFAULT | 仕様でチェックサムが必要とされる場合は、付加されます。 |
| YES | 可能な限り常にチェックサムを使用します。 |
| NO | チェックサムは使用しないでください。 |
