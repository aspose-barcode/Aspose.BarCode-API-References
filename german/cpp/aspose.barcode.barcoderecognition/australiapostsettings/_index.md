---
title: "Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings Klasse"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings Klasse. AustraliaPost-Dekodierungsparameter. Enthält Parameter, die Einfluss auf die erkannten Daten der AustraliaPost‑Symbolik in C++ haben."
type: docs
weight: 200
url: /de/cpp/aspose.barcode.barcoderecognition/australiapostsettings/
---
## AustraliaPostSettings class


AustraliaPost-Dekodierungsparameter. Enthält Parameter, die Einfluss auf die erkannten Daten der AustraliaPost-Symbologie haben.

```cpp
class AustraliaPostSettings : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_CustomerInformationDecoder](./get_customerinformationdecoder/)() const | Öffentliche Schnittstelle für die Dekodierung des Customer Information Field, das in der AustraliaPost‑Symbolik verwendet wird. |
| [get_CustomerInformationInterpretingType](./get_customerinformationinterpretingtype/)() const | Liefert den Interpretationstyp für die Kundendaten von AustralianPost. [BarCode.Default](../checksumvalidation/) ist [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/). |
| [get_IgnoreEndingFillingPatternsForCTable](./get_ignoreendingfillingpatternsforctable/)() const | Das Flag, das den AustraliaPost‑Decoder zwingt, die letzten Füllmuster im Customer Information Field während der Dekodierung nach der CTable‑Methode zu ignorieren. Die CTable‑Kodierungsmethode hat keine Lücken in der Kodierungstabelle und die Sequenz \"333\" der Füllmuster wird als Buchstabe \"z\" dekodiert. |
| [set_CustomerInformationDecoder](./set_customerinformationdecoder/)(System::SharedPtr\<AustraliaPostCustomerInformationDecoder\>) | Öffentliche Schnittstelle für die Dekodierung des Customer Information Field, das in der AustraliaPost‑Symbolik verwendet wird. |
| [set_CustomerInformationInterpretingType](./set_customerinformationinterpretingtype/)(Aspose::BarCode::CustomerInformationInterpretingType) | Setzt den Interpretationstyp für die Kundendaten von AustralianPost. [BarCode.Default](../checksumvalidation/) ist [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/). |
| [set_IgnoreEndingFillingPatternsForCTable](./set_ignoreendingfillingpatternsforctable/)(bool) | Das Flag, das den AustraliaPost‑Decoder zwingt, die letzten Füllmuster im Customer Information Field während der Dekodierung nach der CTable‑Methode zu ignorieren. Die CTable‑Kodierungsmethode hat keine Lücken in der Kodierungstabelle und die Sequenz \"333\" der Füllmuster wird als Buchstabe \"z\" dekodiert. |
## Siehe auch

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
