---
title: "طريقة"
linktitle: "get_Confidence"
second_title: "Aspose.BarCode للـ C++ مرجع API"
description: " طريقة. يحصل على مستوى ثقة التعرف للباركود المعترف به في C++."
type: docs
weight: 200
url: /ar/cpp/aspose.barcode.barcoderecognition/barcoderesult/get_confidence/
---
## BarCodeResult::get_Confidence method


يحصل على مستوى ثقة التعرف للباركود الذي تم التعرف عليه

```cpp
BarCodeConfidence Aspose::BarCode::BarCodeRecognition::BarCodeResult::get_Confidence() const
```

## ملاحظات


[BarCodeConfidence::Strong](../../barcodeconfidence/) does not have fakes or misrecognitions, [BarCodeConfidence::Moderate](../../barcodeconfidence/) could sometimes have fakes or incorrect codetext because this confidence level for barcodews with weak cheksum or even without it, [BarCodeConfidence::None](../../barcodeconfidence/) always has incorrect codetext and could be fake recognitions
## انظر أيضًا

* Enum [BarCodeConfidence](../../barcodeconfidence/)
* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
