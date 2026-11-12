---
title: "ChecksumValidation"
linktitle: "ChecksumValidation"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "1D バーコードの認識時にチェックサム検証を有効にします。"
type: docs
weight: 100
url: /ja/nodejs/global/checksumvalidation/
---

## ChecksumValidation

1D バーコードの認識時にチェックサム検証を有効にします。 デフォルトでは、チェックサムが必須のシンボロジーでは「はい」とみなされ、チェックサムが任意の場合は「いいえ」とみなされます。 チェックサムが使用されない: Codabar チェックサムが使用可能: Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN チェックサムが常に使用される: その他のシンボロジー このサンプルは ChecksumValidation が認識品質と結果に与える影響を示します \code generator = BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128") generator.save("test.png", BarCodeImageFormat.PNG) reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum disabled reader.setChecksumValidation(ChecksumValidation.OFF) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode \code reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum enabled reader.setChecksumValidation(ChecksumValidation.ON) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode

## 値

| 名前 | 説明 |
| --- | --- |
| MOD_10 | Codabar 用の Mod 10 アルゴリズムを指定します。 |
| MOD_16 | Codabar 用の Mod 16 アルゴリズムを指定します（推奨 AIIM）。 |
