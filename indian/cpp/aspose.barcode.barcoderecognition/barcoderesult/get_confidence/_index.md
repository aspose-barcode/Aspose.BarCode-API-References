---
title: "विधि"
linktitle: "get_Confidence"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " method. C++ में मान्यता प्राप्त बारकोड के पहचान विश्वास स्तर को प्राप्त करता है।"
type: docs
weight: 200
url: /hi/cpp/aspose.barcode.barcoderecognition/barcoderesult/get_confidence/
---
## BarCodeResult::get_Confidence method


मान्यता प्राप्त बारकोड का पहचान विश्वसनीयता स्तर प्राप्त करता है

```cpp
BarCodeConfidence Aspose::BarCode::BarCodeRecognition::BarCodeResult::get_Confidence() const
```

## टिप्पणियाँ


[BarCodeConfidence::Strong](../../barcodeconfidence/) does not have fakes or misrecognitions, [BarCodeConfidence::Moderate](../../barcodeconfidence/) could sometimes have fakes or incorrect codetext because this confidence level for barcodews with weak cheksum or even without it, [BarCodeConfidence::None](../../barcodeconfidence/) always has incorrect codetext and could be fake recognitions
## और देखें

* Enum [BarCodeConfidence](../../barcodeconfidence/)
* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
