---
title: "BarcodeQualityMode"
linktitle: "BarcodeQualityMode"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Mode yang mengaktifkan metode untuk mengenali elemen barcode dengan kualitas yang dipilih."
type: docs
weight: 80
url: /id/nodejs/global/barcodequalitymode/
---

## BarcodeQualityMode

Mode yang memungkinkan metode mengenali elemen kode batang dengan kualitas yang dipilih. Elemen kode batang dengan kualitas lebih rendah memerlukan metode yang lebih berat yang memperlambat proses pengenalan. Contoh ini menunjukkan cara menggunakan mode BarcodeQuality let reader = new BarCodeReader("test.png", null, [DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128]); reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode CodeText: " + result.getCodeText()); }

## Nilai

| Nama | Deskripsi |
| --- | --- |
| SOLID | Menentukan garis padat. |
| DASH | Menentukan garis yang terdiri dari tanda hubung. |
| DOT | Menentukan garis yang terdiri dari titik. |
| DASH_DOT | Menentukan garis yang terdiri dari pola berulang dash-dot. |
| DASH_DOT_DOT | Menentukan garis yang terdiri dari pola berulang dash-dot-dot. |
