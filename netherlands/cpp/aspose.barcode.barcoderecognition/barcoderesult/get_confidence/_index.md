---
title: "methode"
linktitle: "get_Confidence"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " method. Haalt het herkenningsvertrouwensniveau op van de herkende barcode in C++."
type: docs
weight: 200
url: /nl/cpp/aspose.barcode.barcoderecognition/barcoderesult/get_confidence/
---
## BarCodeResult::get_Confidence method


Haalt het herkenningsvertrouwensniveau van de herkende barcode op.

```cpp
BarCodeConfidence Aspose::BarCode::BarCodeRecognition::BarCodeResult::get_Confidence() const
```

## Opmerkingen


[BarCodeConfidence::Strong](../../barcodeconfidence/) does not have fakes or misrecognitions, [BarCodeConfidence::Moderate](../../barcodeconfidence/) could sometimes have fakes or incorrect codetext because this confidence level for barcodews with weak cheksum or even without it, [BarCodeConfidence::None](../../barcodeconfidence/) always has incorrect codetext and could be fake recognitions
## Zie ook

* Enum [BarCodeConfidence](../../barcodeconfidence/)
* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
