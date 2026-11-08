---
title: "método"
linktitle: "get_Confidence"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Obtiene el nivel de confianza del reconocimiento del código de barras reconocido en C++."
type: docs
weight: 200
url: /es/cpp/aspose.barcode.barcoderecognition/barcoderesult/get_confidence/
---
## BarCodeResult::get_Confidence method


Obtiene el nivel de confianza del reconocimiento del código de barras reconocido

```cpp
BarCodeConfidence Aspose::BarCode::BarCodeRecognition::BarCodeResult::get_Confidence() const
```

## Observaciones


[BarCodeConfidence::Strong](../../barcodeconfidence/) does not have fakes or misrecognitions, [BarCodeConfidence::Moderate](../../barcodeconfidence/) could sometimes have fakes or incorrect codetext because this confidence level for barcodews with weak cheksum or even without it, [BarCodeConfidence::None](../../barcodeconfidence/) always has incorrect codetext and could be fake recognitions
## Ver también

* Enum [BarCodeConfidence](../../barcodeconfidence/)
* Class [BarCodeResult](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
