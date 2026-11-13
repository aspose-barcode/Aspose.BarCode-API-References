---
title: "QREncodeMode"
linktitle: "QREncodeMode"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Kodningsläge för QR-streckkoder."
type: docs
weight: 480
url: /sv/nodejs/global/qrencodemode/
---

## QREncodeMode

Kodningsläge för QR-streckkoder. Exempel på hur man använder ECI-kodning generator = new BarcodeGenerator(EncodeTypes.QR, "12345TEXT"); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ECI_ENCODING); generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8); generator.save("test.png", BarcodeImageFormat.PNG); Exempel på hur man använder FNC1 första position i Extended Mode textBuilder = new QrExtCodetextBuilder(); textBuilder.addPlainCodetext("000%89%%0"); textBuilder.addFNC1GroupSeparator(); textBuilder.addPlainCodetext("12345<FNC1>"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); Detta exempel visar hur man använder FNC1 andra position i Extended Mode. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addFNC1SecondPosition("12"); textBuilder.addPlainCodetext("TRUE3456"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); Detta exempel visar hur man använder multi-ECI-läge i Extended Mode. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addECICodetext(ECIEncodings.Win1251, "Will"); textBuilder.addECICodetext(ECIEncodings.UTF8, "Right"); textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power"); textBuilder.addPlainCodetext("t\e\\st"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG);

## Värden

| Namn | Beskrivning |
| --- | --- |
| AUTO | Läget startar streckkodsversionens förhandling från MicroQR V1. |
| FORCE_QR | Läget startar streckkodsversionens förhandling från QR V1. |
| FORCE_MICRO_QR | Läget startar streckkodsversionens förhandling från MicroQR V1 till V4. Om data inte kan kodas till MicroQR kastas ett undantag. |
