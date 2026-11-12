---
title: "QREncodeMode"
linktitle: "QREncodeMode"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Kodierungsmodus für QR-Strichcodes."
type: docs
weight: 480
url: /de/nodejs/global/qrencodemode/
---

## QREncodeMode

Kodierungsmodus für QR-Barcodes. Beispiel, wie man die ECI-Kodierung verwendet generator = new BarcodeGenerator(EncodeTypes.QR, "12345TEXT"); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ECI_ENCODING); generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8); generator.save("test.png", BarcodeImageFormat.PNG); Beispiel, wie man FNC1 an der ersten Position im erweiterten Modus verwendet textBuilder = new QrExtCodetextBuilder(); textBuilder.addPlainCodetext("000%89%%0"); textBuilder.addFNC1GroupSeparator(); textBuilder.addPlainCodetext("12345<FNC1>"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); Dieses Beispiel zeigt, wie man FNC1 an der zweiten Position im erweiterten Modus verwendet. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addFNC1SecondPosition("12"); textBuilder.addPlainCodetext("TRUE3456"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); Dieses Beispiel zeigt, wie man den Multi-ECI-Modus im erweiterten Modus verwendet. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addECICodetext(ECIEncodings.Win1251, "Will"); textBuilder.addECICodetext(ECIEncodings.UTF8, "Right"); textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power"); textBuilder.addPlainCodetext("t\e\\st"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG);

## Werte

| Name | Beschreibung |
| --- | --- |
| AUTO | Modus startet die Barcode‑Versionsverhandlung ab MicroQR V1 |
| FORCE_QR | Modus startet die Barcode‑Versionsverhandlung ab QR V1 |
| FORCE_MICRO_QR | Modus startet die Barcode‑Versionsverhandlung von MicroQR V1 bis V4. Wenn Daten nicht in MicroQR kodiert werden können, wird eine Ausnahme ausgelöst. |
