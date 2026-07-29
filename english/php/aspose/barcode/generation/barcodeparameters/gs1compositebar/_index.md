---
title: "BarcodeParameters.GS1CompositeBar"
linktitle: "GS1CompositeBar"
articleTitle: "GS1CompositeBar"
second_title: "Aspose.BarCode for PHP via Java"
description: "GS1 Composite Bar parameters. This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '/' $codetext = \\"(01)03212345678906/(21)"
type: docs
weight: 10
url: /php/aspose/barcode/generation/barcodeparameters/gs1compositebar/
---

## BarcodeParameters.GS1CompositeBar

**Access:** Read/Write


**Returns:** GS1CompositeBarParameters GS1 Composite Bar parameters.


### Get

GS1 Composite Bar parameters. This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '/' $codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8"; $generator = new BarcodeGenerator(EncodeTypes::GS_1_COMPOSITE_BAR, $codetext); $generator->getParameters()->getBarcode()->getGS1CompositeBar()->setLinearComponentType(EncodeTypes::GS_1_CODE_128); $generator->getParameters()->getBarcode()->getGS1CompositeBar()->setTwoDComponentType(TwoDComponentType::CC_A); // Aspect ratio of 2D component $generator->getParameters()->getBarcode()->getPdf417()->setAspectRatio(3); // X-Dimension of 1D and 2D components $generator->getParameters()->getBarcode()->getXDimension()->setPixels(3); /// // Height of 1D component $generator->getParameters()->getBarcode()->getBarHeight()->setPixels(100); /// $generator->save("test.png", BarcodeImageFormat::PNG);


### Set

GS1 Composite Bar parameters. This sample shows how to create and save a GS1 Composite Bar image. Note that 1D codetext and 2D codetext are separated by symbol '/' $codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8"; $generator = new BarcodeGenerator(EncodeTypes::GS_1_COMPOSITE_BAR, $codetext); $generator->getParameters()->getBarcode()->getGS1CompositeBar()->setLinearComponentType(EncodeTypes::GS_1_CODE_128); $generator->getParameters()->getBarcode()->getGS1CompositeBar()->setTwoDComponentType(TwoDComponentType::CC_A); // Aspect ratio of 2D component $generator->getParameters()->getBarcode()->getPdf417()->setAspectRatio(3); // X-Dimension of 1D and 2D components $generator->getParameters()->getBarcode()->getXDimension()->setPixels(3); /// // Height of 1D component $generator->getParameters()->getBarcode()->getBarHeight()->setPixels(100); /// $generator->save("test.png", BarcodeImageFormat::PNG);


| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `GS1CompositeBarParameters` |  |
