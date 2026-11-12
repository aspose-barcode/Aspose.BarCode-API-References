---
title: "QREncodeMode"
linktitle: "QREncodeMode"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "Coderingsmodus voor QR-streepjescodes."
type: docs
weight: 480
url: /nl/nodejs/global/qrencodemode/
---

## QREncodeMode

Voorbeeld hoe ECI-codering te gebruiken generator = new BarcodeGenerator(EncodeTypes.QR, "12345TEXT"); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ECI_ENCODING); generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8); generator.save("test.png", BarcodeImageFormat.PNG); Voorbeeld hoe FNC1 eerste positie in Extended Mode te gebruiken textBuilder = new QrExtCodetextBuilder(); textBuilder.addPlainCodetext("000%89%%0"); textBuilder.addFNC1GroupSeparator(); textBuilder.addPlainCodetext("12345<FNC1>"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); Deze voorbeeld toont hoe FNC1 tweede positie in Extended Mode te gebruiken. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addFNC1SecondPosition("12"); textBuilder.addPlainCodetext("TRUE3456"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); Deze voorbeeld toont hoe multi ECI-modus in Extended Mode te gebruiken. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addECICodetext(ECIEncodings.Win1251, "Will"); textBuilder.addECICodetext(ECIEncodings.UTF8, "Right"); textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power"); textBuilder.addPlainCodetext("t\e\\st"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG);

## Waarden

| Naam | Beschrijving |
| --- | --- |
| AUTO | Modus start barcodeversie-onderhandeling vanaf MicroQR V1 |
| FORCE_QR | Modus start barcodeversie-onderhandeling vanaf QR V1 |
| FORCE_MICRO_QR | Modus start barcode versieonderhandeling van MicroQR V1 tot V4. Als gegevens niet kunnen worden gecodeerd naar MicroQR, wordt een uitzondering gegooid. |
