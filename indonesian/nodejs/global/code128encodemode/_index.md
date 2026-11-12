---
title: "Code128EncodeMode"
linktitle: "Code128EncodeMode"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Mode enkoding untuk barcode Code128."
type: docs
weight: 130
url: /id/nodejs/global/code128encodemode/
---

## Code128EncodeMode

Mode enkoding untuk barcode Code128. Spesifikasi `Code 128`. Kode ini menunjukkan cara menghasilkan code 128 dengan enkoding yang berbeda //Hasilkan code 128 dengan enkoding ISO 15417 let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.AUTO); generator.save("d:\\code128Auto.png", BarCodeImageFormat.PNG); //Hasilkan code 128 hanya dengan enkoding Codeset A let generator = new BarcodeGenerator(EncodeTypes.CODE_128, "ABCD1234567890"); generator.getParameters().getBarcode().getCode128().setCode128EncodeMode(Code128EncodeMode.CODE_A); generator.save("d:\\code128CodeA.png", BarCodeImageFormat.PNG);

## Nilai

| Nama | Deskripsi |
| --- | --- |
| CODE_SET_A | Karakter ASCII 00 hingga 95 (0–9, A–Z dan kode kontrol), karakter khusus, dan FNC 1–4 /// |
| CODE_SET_B | Karakter ASCII 32 hingga 127 (0–9, A–Z, a–z), karakter khusus, dan FNC 1–4 /// |
| CODE_SET_C | 00–99 (mengkodekan dua digit dengan satu titik kode) dan FNC1 /// |
