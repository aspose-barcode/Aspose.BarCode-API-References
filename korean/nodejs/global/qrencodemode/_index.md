---
title: "QREncodeMode"
linktitle: "QREncodeMode"
second_title: "Aspose.BarCode for Node.js via Java API 레퍼런스"
description: "QR 바코드의 인코딩 모드."
type: docs
weight: 480
url: /ko/nodejs/global/qrencodemode/
---

## QREncodeMode

QR 바코드의 인코딩 모드. ECI 인코딩 사용 예시 generator = new BarcodeGenerator(EncodeTypes.QR, "12345TEXT"); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ECI_ENCODING); generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8); generator.save("test.png", BarcodeImageFormat.PNG); Extended Mode에서 FNC1 첫 번째 위치를 사용하는 예시 textBuilder = new QrExtCodetextBuilder(); textBuilder.addPlainCodetext("000%89%%0"); textBuilder.addFNC1GroupSeparator(); textBuilder.addPlainCodetext("12345<FNC1>"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); 이 샘플은 Extended Mode에서 FNC1 두 번째 위치를 사용하는 방법을 보여줍니다. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addFNC1SecondPosition("12"); textBuilder.addPlainCodetext("TRUE3456"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); 이 샘플은 Extended Mode에서 다중 ECI 모드를 사용하는 방법을 보여줍니다. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addECICodetext(ECIEncodings.Win1251, "Will"); textBuilder.addECICodetext(ECIEncodings.UTF8, "Right"); textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power"); textBuilder.addPlainCodetext("t\e\\st"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG);

## 값

| 이름 | 설명 |
| --- | --- |
| AUTO | Mode starts barcode version negotiation from MicroQR V1 |
| FORCE_QR | Mode starts barcode version negotiation from QR V1 |
| FORCE_MICRO_QR | 모드가 MicroQR V1부터 V4까지 바코드 버전 협상을 시작합니다. 데이터가 MicroQR에 인코딩될 수 없으면 예외가 발생합니다. |
