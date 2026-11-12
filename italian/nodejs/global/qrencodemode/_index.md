---
title: "QREncodeMode"
linktitle: "QREncodeMode"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Modalità di codifica per i codici QR."
type: docs
weight: 480
url: /it/nodejs/global/qrencodemode/
---

## QREncodeMode

Modalità di codifica per i codici QR. Esempio di utilizzo della codifica ECI generator = new BarcodeGenerator(EncodeTypes.QR, "12345TEXT"); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ECI_ENCODING); generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8); generator.save("test.png", BarcodeImageFormat.PNG); Esempio di utilizzo di FNC1 nella prima posizione in Modalità Estesa textBuilder = new QrExtCodetextBuilder(); textBuilder.addPlainCodetext("000%89%%0"); textBuilder.addFNC1GroupSeparator(); textBuilder.addPlainCodetext("12345<FNC1>"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); Questo esempio mostra come utilizzare FNC1 nella seconda posizione in Modalità Estesa. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addFNC1SecondPosition("12"); textBuilder.addPlainCodetext("TRUE3456"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); Questo esempio mostra come utilizzare la modalità multi ECI in Modalità Estesa. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addECICodetext(ECIEncodings.Win1251, "Will"); textBuilder.addECICodetext(ECIEncodings.UTF8, "Right"); textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power"); textBuilder.addPlainCodetext("t\e\\st"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG);

## Valori

| Nome | Descrizione |
| --- | --- |
| AUTO | La modalità avvia la negoziazione della versione del codice a barre da MicroQR V1 |
| FORCE_QR | La modalità avvia la negoziazione della versione del codice a barre da QR V1 |
| FORCE_MICRO_QR | La modalità avvia la negoziazione della versione del codice a barre da MicroQR V1 a V4. Se i dati non possono essere codificati in MicroQR, viene generata un'eccezione. |
