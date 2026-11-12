---
title: "ChecksumValidation"
linktitle: "ChecksumValidation"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "1D 바코드 인식 중 체크섬 검증을 활성화합니다."
type: docs
weight: 100
url: /ko/nodejs/global/checksumvalidation/
---

## ChecksumValidation

1D 바코드 인식 중 체크섬 검증을 활성화합니다. 기본값은 체크섬이 반드시 포함되어야 하는 심볼에 대해서는 Yes로, 체크섬이 선택적인 경우는 No로 처리됩니다. 체크섬이 사용되지 않는 경우: Codabar 체크섬이 가능한 경우: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN 체크섬이 항상 사용되는 경우: 나머지 심볼 이 샘플은 ChecksumValidation이 인식 품질 및 결과에 미치는 영향을 보여줍니다 \code generator = BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128") generator.save("test.png", BarCodeImageFormat.PNG) reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum disabled reader.setChecksumValidation(ChecksumValidation.OFF) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode \code reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum enabled reader.setChecksumValidation(ChecksumValidation.ON) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode

## 값

| 이름 | 설명 |
| --- | --- |
| MOD_10 | Codabar에 대한 Mod 10 알고리즘을 지정합니다. |
| MOD_16 | Codabar에 대한 Mod 16 알고리즘을 지정합니다(권장 AIIM). |
