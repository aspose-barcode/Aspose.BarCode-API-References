---
title: "QREncodeMode"
linktitle: "QREncodeMode"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Λειτουργία κωδικοποίησης για QR barcode. Παράδειγμα χρήσης κωδικοποίησης ECI generator = new BarcodeGenerator(EncodeTypes.QR, \"12345TEXT\"); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ECI_ENCODING); generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8); generator.save(\"test.png\", BarcodeImageFormat.PNG); Παράδειγμα χρήσης FNC1 στην πρώτη θέση σε λειτουργία Extended textBuilder = new QrExtCodetextBuilder(); textBuilder.addPlainCodetext(\"000%89%%0\"); textBuilder.addFNC1GroupSeparator(); textBuilder.addPlainCodetext(\"12345<FNC1>\"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText(\"My Text\"); generator.save(\"d:/test.png\", BarcodeImageFormat.PNG); Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το FNC1 στη δεύτερη θέση σε λειτουργία Extended. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addFNC1SecondPosition(\"12\"); textBuilder.addPlainCodetext(\"TRUE3456\"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText(\"My Text\"); generator.save(\"d:/test.png\", BarcodeImageFormat.PNG); Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία multi ECI σε λειτουργία Extended. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addECICodetext(ECIEncodings.Win1251, \"Will\"); textBuilder.addECICodetext(ECIEncodings.UTF8, \"Right\"); textBuilder.addECICodetext(ECIEncodings.UTF16BE, \"Power\"); textBuilder.addPlainCodetext(\"t\\e\\\\st\"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText(\"My Text\"); generator.save(\"d:/test.png\", BarcodeImageFormat.PNG);"
type: docs
weight: 480
url: /el/nodejs/global/qrencodemode/
---

## QREncodeMode

EncodeTypes

## Τιμές

| Όνομα | Περιγραφή |
| --- | --- |
| AUTO | Η λειτουργία ξεκινά τη διαπραγμάτευση έκδοσης barcode από το MicroQR V1 |
| FORCE_QR | Η λειτουργία ξεκινά τη διαπραγμάτευση έκδοσης barcode από το QR V1 |
| FORCE_MICRO_QR | Η λειτουργία ξεκινά τη διαπραγμάτευση έκδοσης barcode από το MicroQR V1 έως το V4. Εάν τα δεδομένα δεν μπορούν να κωδικοποιηθούν σε MicroQR, ρίχνεται εξαίρεση. |
