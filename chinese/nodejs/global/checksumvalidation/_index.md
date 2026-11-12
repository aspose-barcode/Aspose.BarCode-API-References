---
title: "ChecksumValidation"
linktitle: "ChecksumValidation"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "在一维条码识别期间启用校验和验证。"
type: docs
weight: 100
url: /zh/nodejs/global/checksumvalidation/
---

## ChecksumValidation

在一维条码识别期间启用校验和验证。默认情况下，对于必须包含校验和的符号系统视为“是”，对于仅可能包含校验和的视为“否”。从不使用校验和的：Codabar。可能使用校验和的：Code39 Standard/Extended、Standard2of5、Interleaved2of5、Matrix2of5、ItalianPost25、DeutschePostIdentcode、DeutschePostLeitcode、VIN。始终使用校验和的：其余符号系统。本示例展示了 ChecksumValidation 对识别质量和结果的影响。\code generator = BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128") generator.save("test.png", BarCodeImageFormat.PNG) reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum disabled reader.setChecksumValidation(ChecksumValidation.OFF) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode \code reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum enabled reader.setChecksumValidation(ChecksumValidation.ON) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode

## 值

| 名称 | 描述 |
| --- | --- |
| MOD_10 | 指定 Codabar 的 Mod 10 算法。 |
| MOD_16 | 指定 Codabar 的 Mod 16 算法（推荐 AIIM）。 |
