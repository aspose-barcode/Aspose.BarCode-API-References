---
title: "QREncodeMode"
linktitle: "QREncodeMode"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "QR बारकोड के लिए एन्कोडिंग मोड।"
type: docs
weight: 480
url: /hi/nodejs/global/qrencodemode/
---

## QREncodeMode

QR बारकोड के लिए एन्कोडिंग मोड। ECI एन्कोडिंग का उपयोग करने का उदाहरण generator = new BarcodeGenerator(EncodeTypes.QR, "12345TEXT"); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ECI_ENCODING); generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8); generator.save("test.png", BarcodeImageFormat.PNG); Extended Mode में FNC1 पहली स्थिति का उपयोग करने का उदाहरण textBuilder = new QrExtCodetextBuilder(); textBuilder.addPlainCodetext("000%89%%0"); textBuilder.addFNC1GroupSeparator(); textBuilder.addPlainCodetext("12345<FNC1>"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); यह नमूना दिखाता है कि Extended Mode में FNC1 दूसरी स्थिति का उपयोग कैसे किया जाता है। //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addFNC1SecondPosition("12"); textBuilder.addPlainCodetext("TRUE3456"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); यह नमूना दिखाता है कि Extended Mode में मल्टी ECI मोड का उपयोग कैसे किया जाता है। //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addECICodetext(ECIEncodings.Win1251, "Will"); textBuilder.addECICodetext(ECIEncodings.UTF8, "Right"); textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power"); textBuilder.addPlainCodetext("t\e\\st"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG);

## मान

| नाम | विवरण |
| --- | --- |
| AUTO | मोड MicroQR V1 से बारकोड संस्करण वार्ता शुरू करता है |
| FORCE_QR | मोड QR V1 से बारकोड संस्करण वार्ता शुरू करता है |
| FORCE_MICRO_QR | मोड माइक्रो QR V1 से V4 तक बारकोड संस्करण वार्ता शुरू करता है। यदि डेटा को माइक्रो QR में एन्कोड नहीं किया जा सकता, तो अपवाद फेंका जाता है। |
