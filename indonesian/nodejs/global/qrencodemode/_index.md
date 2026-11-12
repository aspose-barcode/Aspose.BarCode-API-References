---
title: "QREncodeMode"
linktitle: "QREncodeMode"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Mode enkoding untuk barcode QR."
type: docs
weight: 480
url: /id/nodejs/global/qrencodemode/
---

## QREncodeMode

Mode enkoding untuk barcode QR. Contoh cara menggunakan enkoding ECI generator = new BarcodeGenerator(EncodeTypes.QR, "12345TEXT"); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ECI_ENCODING); generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8); generator.save("test.png", BarcodeImageFormat.PNG); Contoh cara menggunakan FNC1 pada posisi pertama dalam Mode Extended textBuilder = new QrExtCodetextBuilder(); textBuilder.addPlainCodetext("000%89%%0"); textBuilder.addFNC1GroupSeparator(); textBuilder.addPlainCodetext("12345<FNC1>"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); Contoh ini menunjukkan cara menggunakan FNC1 pada posisi kedua dalam Mode Extended. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addFNC1SecondPosition("12"); textBuilder.addPlainCodetext("TRUE3456"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); Contoh ini menunjukkan cara menggunakan mode ECI multi dalam Mode Extended. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addECICodetext(ECIEncodings.Win1251, "Will"); textBuilder.addECICodetext(ECIEncodings.UTF8, "Right"); textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power"); textBuilder.addPlainCodetext("t\e\\st"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG);

## Nilai

| Nama | Deskripsi |
| --- | --- |
| AUTO | Mode memulai negosiasi versi kode batang dari MicroQR V1 |
| FORCE_QR | Mode memulai negosiasi versi kode batang dari QR V1 |
| FORCE_MICRO_QR | Mode memulai negosiasi versi barcode dari MicroQR V1 hingga V4. Jika data tidak dapat dienkode ke MicroQR, pengecualian akan dilempar. |
