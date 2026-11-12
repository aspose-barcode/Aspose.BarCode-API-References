---
title: "ChecksumValidation"
linktitle: "ChecksumValidation"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Aktifkan validasi checksum selama pengenalan untuk barcode 1D."
type: docs
weight: 100
url: /id/nodejs/global/checksumvalidation/
---

## ChecksumValidation

Aktifkan validasi checksum selama pengenalan untuk barcode 1D. Default diperlakukan sebagai Ya untuk simbol yang harus mengandung checksum, sebagai Tidak dimana checksum hanya mungkin. Checksum tidak pernah digunakan: Codabar. Checksum mungkin: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN. Checksum selalu digunakan: Simbol lainnya. Contoh ini menunjukkan pengaruh ChecksumValidation pada kualitas dan hasil pengenalan \code generator = BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128") generator.save("test.png", BarCodeImageFormat.PNG) reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum disabled reader.setChecksumValidation(ChecksumValidation.OFF) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode \code reader = Recognition.BarCodeReader("test.png", None, DecodeType.EAN_13) #checksum enabled reader.setChecksumValidation(ChecksumValidation.ON) for result in reader.readBarCodes(): print("BarCode CodeText: " + result.getCodeText()) print("BarCode Value: " + result.getExtended().getOneD().getValue()) print("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum()) \endcode

## Nilai

| Nama | Deskripsi |
| --- | --- |
| MOD_10 | Menentukan algoritma Mod 10 untuk Codabar. |
| MOD_16 | Menentukan algoritma Mod 16 untuk Codabar (direkomendasikan AIIM). |
