---
title: "μέθοδος"
linktitle: "get_Confidence"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: " method. Λαμβάνει το επίπεδο εμπιστοσύνης αναγνώρισης του αναγνωρισμένου barcode σε C++."
type: docs
weight: 200
url: /el/cpp/aspose.barcode.barcoderecognition/barcoderesult/get_confidence/
---
## BarCodeResult::get_Confidence method


Λαμβάνει το επίπεδο εμπιστοσύνης αναγνώρισης του αναγνωρισμένου barcode.

```cpp
BarCodeConfidence Aspose::BarCode::BarCodeRecognition::BarCodeResult::get_Confidence() const
```

## Σχόλια


[BarCodeConfidence::Strong](../../barcodeconfidence/) does not have fakes or misrecognitions, [BarCodeConfidence::Moderate](../../barcodeconfidence/) could sometimes have fakes or incorrect codetext because this confidence level for barcodews with weak cheksum or even without it, [BarCodeConfidence::None](../../barcodeconfidence/) always has incorrect codetext and could be fake recognitions
## Δείτε επίσης

* Enum [BarCodeConfidence](../../barcodeconfidence/)
* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
