---
title: "Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings klass"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings klass. AustraliaPost-avkodningsparametrar. Innehåller parametrar som påverkar den igenkända datan för AustraliaPost-symbologi i C++."
type: docs
weight: 200
url: /sv/cpp/aspose.barcode.barcoderecognition/australiapostsettings/
---
## AustraliaPostSettings class


AustraliaPost-avkodningsparametrar. Innehåller parametrar som påverkar den avkodade datan för AustraliaPost-symbologi.

```cpp
class AustraliaPostSettings : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_CustomerInformationDecoder](./get_customerinformationdecoder/)() const | Offentligt gränssnitt för avkodning av Customer Information Field som används i AustraliaPost-symbologi. |
| [get_CustomerInformationInterpretingType](./get_customerinformationinterpretingtype/)() const | Hämtar tolknings‑typen för Customer Information i AustralianPost [BarCode.Default](../checksumvalidation/) är [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/). |
| [get_IgnoreEndingFillingPatternsForCTable](./get_ignoreendingfillingpatternsforctable/)() const | Flaggan som tvingar AustraliaPost-avkodaren att ignorera de sista fyllningsmönstren i Customer Information Field under avkodning som CTable-metod. CTable-kodningsmetoden har inga luckor i kodningstabellen och sekvensen "333" av fyllningsmönster avkodas som bokstaven "z". |
| [set_CustomerInformationDecoder](./set_customerinformationdecoder/)(System::SharedPtr\<AustraliaPostCustomerInformationDecoder\>) | Offentligt gränssnitt för avkodning av Customer Information Field som används i AustraliaPost-symbologi. |
| [set_CustomerInformationInterpretingType](./set_customerinformationinterpretingtype/)(Aspose::BarCode::CustomerInformationInterpretingType) | Ställer in tolknings‑typen för Customer Information i AustralianPost [BarCode.Default](../checksumvalidation/) är [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/). |
| [set_IgnoreEndingFillingPatternsForCTable](./set_ignoreendingfillingpatternsforctable/)(bool) | Flaggan som tvingar AustraliaPost-avkodaren att ignorera de sista fyllningsmönstren i Customer Information Field under avkodning som CTable-metod. CTable-kodningsmetoden har inga luckor i kodningstabellen och sekvensen "333" av fyllningsmönster avkodas som bokstaven "z". |
## Se även

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
