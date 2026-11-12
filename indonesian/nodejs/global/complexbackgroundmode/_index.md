---
title: "ComplexBackgroundMode"
linktitle: "ComplexBackgroundMode"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode berwarna pada gambar berwarna."
type: docs
weight: 160
url: /id/nodejs/global/complexbackgroundmode/
---

## ComplexBackgroundMode

Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan kode batang berwarna pada gambar berwarna. Contoh ini menunjukkan cara menggunakan mode ComplexBackground let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setComplexBackground(ComplexBackgroundMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Nilai

| Nama | Deskripsi |
| --- | --- |
| C_TABLE | Gunakan C_TABLE untuk menginterpretasikan informasi pelanggan. Mengizinkan A..Z, a..z, 1..9, spasi, dan simbol #. |
| N_TABLE | Gunakan N_TABLE untuk menginterpretasikan informasi pelanggan. Mengizinkan digit. |
| OTHER | Jangan menginterpretasikan informasi pelanggan. Hanya mengizinkan simbol 0, 1, 2, atau 3. |
