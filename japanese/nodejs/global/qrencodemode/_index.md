---
title: "QREncodeMode"
linktitle: "QREncodeMode"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "QR バーコードのエンコードモード。ECI エンコーディングの使用例 generator = new BarcodeGenerator(EncodeTypes.QR, \\\"12345TEXT\\\"); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ECI_ENCODING); generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8); generator.save(\\\"test.png\\\", BarcodeImageFormat.PNG); 拡張モードでの FNC1 の先頭位置の使用例 textBuilder = new QrExtCodetextBuilder(); textBuilder.addPlainCodetext(\\\"000%89%%0\\\"); textBuilder.addFNC1GroupSeparator(); textBuilder.addPlainCodetext(\\\"12345<FNC1>\\\"); // バーコード生成 generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText(\\\"My Text\\\"); generator.save(\\\"d:/test.png\\\", BarcodeImageFormat.PNG); このサンプルは拡張モードでの FNC1 の第2位置の使用方法を示します。 // コードテキスト作成 textBuilder = new QrExtCodetextBuilder(); textBuilder.addFNC1SecondPosition(\\\"12\\\"); textBuilder.addPlainCodetext(\\\"TRUE3456\\\"); // バーコード生成 generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText(\\\"My Text\\\"); generator.save(\\\"d:/test.png\\\", BarcodeImageFormat.PNG); このサンプルは拡張モードでのマルチ ECI モードの使用方法を示します。 // コードテキスト作成 textBuilder = new QrExtCodetextBuilder(); textBuilder.addECICodetext(ECIEncodings.Win1251, \\\"Will\\\"); textBuilder.addECICodetext(ECIEncodings.UTF8, \\\"Right\\\"); textBuilder.addECICodetext(ECIEncodings.UTF16BE, \\\"Power\\\"); textBuilder.addPlainCodetext(\\\"t\\\\e\\\\\\\\st\\\"); // バーコード生成 generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText(\\\"My Text\\\"); generator.save(\\\"d:/test.png\\\", BarcodeImageFormat.PNG);"
type: docs
weight: 480
url: /ja/nodejs/global/qrencodemode/
---

## QREncodeMode

EncodeTypes

## 値

| 名前 | 説明 |
| --- | --- |
| AUTO | モードは MicroQR V1 からバーコードバージョン交渉を開始します。 |
| FORCE_QR | モードは QR V1 からバーコードバージョン交渉を開始します。 |
| FORCE_MICRO_QR | モードは MicroQR V1 から V4 までのバーコードバージョン交渉を開始します。データが MicroQR にエンコードできない場合、例外がスローされます。 |
