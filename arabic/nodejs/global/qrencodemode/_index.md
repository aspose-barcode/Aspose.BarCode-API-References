---
title: "QREncodeMode"
linktitle: "QREncodeMode"
second_title: "مرجع API لـ Aspose.BarCode لـ Node.js عبر Java"
description: "وضع الترميز لباركودات QR."
type: docs
weight: 480
url: /ar/nodejs/global/qrencodemode/
---

## QREncodeMode

وضع الترميز لباركودات QR. مثال على كيفية استخدام ترميز ECI generator = new BarcodeGenerator(EncodeTypes.QR, "12345TEXT"); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ECI_ENCODING); generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8); generator.save("test.png", BarcodeImageFormat.PNG); مثال على كيفية استخدام FNC1 في الموضع الأول في الوضع الموسع textBuilder = new QrExtCodetextBuilder(); textBuilder.addPlainCodetext("000%89%%0"); textBuilder.addFNC1GroupSeparator(); textBuilder.addPlainCodetext("12345<FNC1>"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); يوضح هذا المثال كيفية استخدام FNC1 في الموضع الثاني في الوضع الموسع. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addFNC1SecondPosition("12"); textBuilder.addPlainCodetext("TRUE3456"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG); يوضح هذا المثال كيفية استخدام وضع ECI المتعدد في الوضع الموسع. //create codetext textBuilder = new QrExtCodetextBuilder(); textBuilder.addECICodetext(ECIEncodings.Win1251, "Will"); textBuilder.addECICodetext(ECIEncodings.UTF8, "Right"); textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power"); textBuilder.addPlainCodetext("t\e\\st"); //generate barcode generator = new BarcodeGenerator(EncodeTypes.QR); generator.setCodeText(textBuilder.getExtended()); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.EXTENDED_CODETEXT); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("d:/test.png", BarcodeImageFormat.PNG);

## القيم

| اسم | الوصف |
| --- | --- |
| AUTO | الوضع يبدأ التفاوض على نسخة الباركود من MicroQR V1 |
| FORCE_QR | الوضع يبدأ التفاوض على نسخة الباركود من QR V1 |
| FORCE_MICRO_QR | يبدأ الوضع التفاوض على إصدارات الباركود من MicroQR V1 إلى V4. إذا تعذر ترميز البيانات إلى MicroQR، يتم إلقاء استثناء. |
