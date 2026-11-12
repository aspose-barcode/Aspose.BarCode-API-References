---
title: "QREncodeMode"
linktitle: "QREncodeMode"
second_title: "Referencia de API de Aspose.BarCode para Node.js vía Java"
description: "Modo de codificación para códigos de barras QR."
type: docs
weight: 480
url: /es/nodejs/global/qrencodemode/
---

## QREncodeMode

Modo de codificación para códigos de barras QR. Ejemplo de cómo usar la codificación ECI generator = new BarcodeGenerator(EncodeTypes.QR, "12345TEXT"); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ECI_ENCODING); generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8); generator.save("test.png", BarcodeImageFormat.PNG); Ejemplo de cómo usar FNC1 en la primera posición en Modo Extendido textBuilder = new QrExtCodetextBuilder(); textBuilder.addPlainCodetext("000%89%%0"); textBuilder.addFNC1GroupSeparator(); textBuilder.addPlainCodetext("12345<FNC1>"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); Este ejemplo muestra cómo usar FNC1 en la segunda posición en Modo Extendido. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addFNC1SecondPosition("12"); textBuilder.addPlainCodetext("TRUE3456"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); Este ejemplo muestra cómo usar el modo ECI múltiple en Modo Extendido. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addECICodetext(ECIEncodings.Win1251, "Will"); textBuilder.addECICodetext(ECIEncodings.UTF8, "Right"); textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power"); textBuilder.addPlainCodetext("t\e\\st"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG);

## Valores

| Nombre | Descripción |
| --- | --- |
| AUTO | El modo inicia la negociación de versión de código de barras desde MicroQR V1 |
| FORCE_QR | El modo inicia la negociación de versión de código de barras desde QR V1 |
| FORCE_MICRO_QR | El modo inicia la negociación de versión del código de barras desde MicroQR V1 hasta V4. Si los datos no pueden codificarse en MicroQR, se lanza una excepción. |
