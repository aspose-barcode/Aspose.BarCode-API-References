---
title: "QREncodeMode"
linktitle: "QREncodeMode"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Режим кодирования для QR‑штрихкодов."
type: docs
weight: 480
url: /ru/nodejs/global/qrencodemode/
---

## QREncodeMode

Режим кодирования для QR‑штрихкодов. Пример использования кодирования ECI generator = new BarcodeGenerator(EncodeTypes.QR, \"12345TEXT\"); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ECI_ENCODING); generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8); generator.save(\"test.png\", BarcodeImageFormat.PNG); Пример использования FNC1 в первой позиции в режиме Extended Mode textBuilder = new QrExtCodetextBuilder(); textBuilder.addPlainCodetext(\"000%89%%0\"); textBuilder.addFNC1GroupSeparator(); textBuilder.addPlainCodetext(\"12345<FNC1>\"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText(\"My Text\"); generator.save(\"d:/test.png\", BarcodeImageFormat.PNG); Этот пример показывает, как использовать FNC1 во второй позиции в режиме Extended Mode. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addFNC1SecondPosition(\"12\"); textBuilder.addPlainCodetext(\"TRUE3456\"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText(\"My Text\"); generator.save(\"d:/test.png\", BarcodeImageFormat.PNG); Этот пример показывает, как использовать многократный режим ECI в режиме Extended Mode. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addECICodetext(ECIEncodings.Win1251, \"Will\"); textBuilder.addECICodetext(ECIEncodings.UTF8, \"Right\"); textBuilder.addECICodetext(ECIEncodings.UTF16BE, \"Power\"); textBuilder.addPlainCodetext(\"t\\\\e\\\\\\\\st\"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText(\"My Text\"); generator.save(\"d:/test.png\", BarcodeImageFormat.PNG);

## Значения

| Имя | Описание |
| --- | --- |
| AUTO | Режим начинает переговоры о версии штрихкода с MicroQR V1 |
| FORCE_QR | Режим начинает переговоры о версии штрихкода с QR V1 |
| FORCE_MICRO_QR | Режим начинает согласование версии штрихкода от MicroQR V1 до V4. Если данные нельзя закодировать в MicroQR, генерируется исключение. |
