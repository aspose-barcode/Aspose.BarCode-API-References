---
title: "Methode"
linktitle: "get_Confidence"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Gibt das Erkennungs‑Vertrauensniveau des erkannten Barcodes in C++ zurück."
type: docs
weight: 200
url: /de/cpp/aspose.barcode.barcoderecognition/barcoderesult/get_confidence/
---
## BarCodeResult::get_Confidence method


Liefert das Erkennungs‑Vertrauensniveau des erkannten Barcodes.

```cpp
BarCodeConfidence Aspose::BarCode::BarCodeRecognition::BarCodeResult::get_Confidence() const
```

## Hinweise


[BarCodeConfidence::Strong](../../barcodeconfidence/) does not have fakes or misrecognitions, [BarCodeConfidence::Moderate](../../barcodeconfidence/) could sometimes have fakes or incorrect codetext because this confidence level for barcodews with weak cheksum or even without it, [BarCodeConfidence::None](../../barcodeconfidence/) always has incorrect codetext and could be fake recognitions
## Siehe auch

* Enum [BarCodeConfidence](../../barcodeconfidence/)
* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
