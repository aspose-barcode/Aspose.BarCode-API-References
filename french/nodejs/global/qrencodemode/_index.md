---
title: "QREncodeMode"
linktitle: "QREncodeMode"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "Mode d'encodage pour les codes-barres QR. Exemple d'utilisation du codage ECI generator = new BarcodeGenerator(EncodeTypes.QR, \"12345TEXT\"); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ECI_ENCODING); generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8); generator.save(\"test.png\", BarcodeImageFormat.PNG); Exemple d'utilisation de FNC1 en première position en mode étendu textBuilder = new QrExtCodetextBuilder(); textBuilder.addPlainCodetext(\"000%89%%0\"); textBuilder.addFNC1GroupSeparator(); textBuilder.addPlainCodetext(\"12345<FNC1>\"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText(\"My Text\"); generator.save(\"d:/test.png\", BarcodeImageFormat.PNG); Cet exemple montre comment utiliser FNC1 en deuxième position en mode étendu. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addFNC1SecondPosition(\"12\"); textBuilder.addPlainCodetext(\"TRUE3456\"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText(\"My Text\"); generator.save(\"d:/test.png\", BarcodeImageFormat.PNG); Cet exemple montre comment utiliser le mode ECI multiple en mode étendu. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addECICodetext(ECIEncodings.Win1251, \"Will\"); textBuilder.addECICodetext(ECIEncodings.UTF8, \"Right\"); textBuilder.addECICodetext(ECIEncodings.UTF16BE, \"Power\"); textBuilder.addPlainCodetext(\"t\\\\e\\\\\\\\st\"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText(\"My Text\"); generator.save(\"d:/test.png\", BarcodeImageFormat.PNG);"
type: docs
weight: 480
url: /fr/nodejs/global/qrencodemode/
---

## QREncodeMode

EncodeTypes

## Valeurs

| Nom | Description |
| --- | --- |
| AUTO | Le mode démarre la négociation de version du code-barres à partir de MicroQR V1 |
| FORCE_QR | Le mode démarre la négociation de version du code-barres à partir de QR V1 |
| FORCE_MICRO_QR | Le mode démarre la négociation de version du code-barres de MicroQR V1 à V4. Si les données ne peuvent pas être encodées en MicroQR, une exception est levée. |
