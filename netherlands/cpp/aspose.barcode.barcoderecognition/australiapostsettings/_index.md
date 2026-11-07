---
title: "Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings klasse"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::BarCodeRecognition::AustraliaPostSettings klasse. AustraliaPost-decodeerparameters. Bevat parameters die invloed hebben op herkende gegevens van de AustraliaPost-symbologie in C++."
type: docs
weight: 200
url: /nl/cpp/aspose.barcode.barcoderecognition/australiapostsettings/
---
## AustraliaPostSettings class


AustraliaPost-decodering parameters. Bevat parameters die invloed hebben op de herkende gegevens van AustraliaPost-symbologie.

```cpp
class AustraliaPostSettings : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_CustomerInformationDecoder](./get_customerinformationdecoder/)() const | Publieke interface voor het decoderen van het Customer Information Field dat wordt gebruikt in de AustraliaPost-symbologie. |
| [get_CustomerInformationInterpretingType](./get_customerinformationinterpretingtype/)() const | Haalt het Interpreting Type op voor de Customer Information van AustralianPost. [BarCode.Default](../checksumvalidation/) is [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/). |
| [get_IgnoreEndingFillingPatternsForCTable](./get_ignoreendingfillingpatternsforctable/)() const | De vlag die de AustraliaPost-decoder dwingt om de laatste vulpatronen in het Customer Information Field te negeren tijdens decodering volgens de CTable-methode. De CTable-coderingsmethode heeft geen gaten in de coderingstabel en de reeks "333" van vulpatronen wordt gedecodeerd als de letter "z". |
| [set_CustomerInformationDecoder](./set_customerinformationdecoder/)(System::SharedPtr\<AustraliaPostCustomerInformationDecoder\>) | Publieke interface voor het decoderen van het Customer Information Field dat wordt gebruikt in de AustraliaPost-symbologie. |
| [set_CustomerInformationInterpretingType](./set_customerinformationinterpretingtype/)(Aspose::BarCode::CustomerInformationInterpretingType) | Stelt het Interpreting Type in voor de Customer Information van AustralianPost. [BarCode.Default](../checksumvalidation/) is [CustomerInformationInterpretingType.Other](../../aspose.barcode/customerinformationinterpretingtype/). |
| [set_IgnoreEndingFillingPatternsForCTable](./set_ignoreendingfillingpatternsforctable/)(bool) | De vlag die de AustraliaPost-decoder dwingt om de laatste vulpatronen in het Customer Information Field te negeren tijdens decodering volgens de CTable-methode. De CTable-coderingsmethode heeft geen gaten in de coderingstabel en de reeks "333" van vulpatronen wordt gedecodeerd als de letter "z". |
## Zie ook

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
