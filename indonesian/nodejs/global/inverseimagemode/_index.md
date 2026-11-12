---
title: "InverseImageMode"
linktitle: "InverseImageMode"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode pada gambar dengan warna terbalik (luminansi)."
type: docs
weight: 370
url: /id/nodejs/global/inverseimagemode/
---

## InverseImageMode

Mode yang mengaktifkan atau menonaktifkan pengenalan tambahan barcode pada gambar dengan warna terbalik (luminansi). Contoh ini menunjukkan cara menggunakan mode InverseImage let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setInverseImage(InverseImageMode.ENABLED); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Nilai

| Nama | Deskripsi |
| --- | --- |
| NONE | Tidak ada batas yang mengelilingi kode batang |
| FRAME | FRAME mengelilingi kode batang |
| BAR | Dua batang horizontal mengelilingi kode batang |
| FRAME_OUT | FRAME mengelilingi kode batang |
| BAR_OUT | Dua batang horizontal mengelilingi kode batang |
