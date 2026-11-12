---
title: "QREncodeMode"
linktitle: "QREncodeMode"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "QR 条码的编码模式。"
type: docs
weight: 480
url: /zh/nodejs/global/qrencodemode/
---

## QREncodeMode

QR 条码的编码模式。示例：如何使用 ECI 编码 generator = new BarcodeGenerator(EncodeTypes.QR, "12345TEXT"); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ECI_ENCODING); generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8); generator.save("test.png", BarcodeImageFormat.PNG); 示例：如何在扩展模式中使用 FNC1 首位 textBuilder = new QrExtCodetextBuilder(); textBuilder.addPlainCodetext("000%89%%0"); textBuilder.addFNC1GroupSeparator(); textBuilder.addPlainCodetext("12345<FNC1>"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); 此示例展示了在扩展模式中使用 FNC1 第二位置。 //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addFNC1SecondPosition("12"); textBuilder.addPlainCodetext("TRUE3456"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); 此示例展示了在扩展模式中使用多 ECI 模式。 //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addECICodetext(ECIEncodings.Win1251, "Will"); textBuilder.addECICodetext(ECIEncodings.UTF8, "Right"); textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power"); textBuilder.addPlainCodetext("t\\e\\\\st"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG);

## 值

| 名称 | 描述 |
| --- | --- |
| AUTO | 模式从 MicroQR V1 开始条码版本协商 |
| FORCE_QR | 模式从 QR V1 开始条码版本协商 |
| FORCE_MICRO_QR | 模式从 MicroQR V1 到 V4 开始条码版本协商。如果数据无法编码为 MicroQR，将抛出异常。 |
