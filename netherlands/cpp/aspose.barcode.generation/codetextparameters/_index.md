---
title: "Aspose::BarCode::Generation::CodetextParameters class"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::Generation::CodetextParameters class. Codetext‑parameters in C++."
type: docs
weight: 1500
url: /nl/cpp/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class


Codetext-parameters.

```cpp
class CodetextParameters : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Alignment](./get_alignment/)() const | Haalt de uitlijning van de codetekst op. Standaardwaarde: [StringAlignment.Center](../textalignment/). |
| [get_Color](./get_color/)() const | Specificeer de weergavekleur van de CodeText. Standaardwaarde: Color.Black. |
| [get_Font](./get_font/)() const | Specificeer het lettertype van de weergegeven CodeText. Standaardwaarde: Arial 5pt regular. Genegeerd als FontMode is ingesteld op [FontMode.Auto](../aztecencodemode/). |
| [get_FontMode](./get_fontmode/)() const | Specificeer FontMode. Als FontMode is ingesteld op Auto, wordt de lettergrootte automatisch berekend op basis van de xDimension-waarde. Het wordt aanbevolen om [FontMode.Auto](../aztecencodemode/) te gebruiken, vooral in [AutoSizeMode.Nearest](../autosizemode/) of [AutoSizeMode.Interpolation](../autosizemode/). Standaardwaarde: [FontMode.Auto](../aztecencodemode/). |
| [get_Location](./get_location/)() const | Specificeer de weergave‑locatie van CodeText, stel in op [CodeLocation.None](../codelocation/) om CodeText te verbergen. Standaardwaarde: [CodeLocation.Below](../codelocation/) voor 1D‑barcodes en [CodeLocation.None](../codelocation/) voor 2D‑barcodes. |
| [get_NoWrap](./get_nowrap/)() const | Specificeer woordomslag (regeleinden) binnen de tekst. Standaardwaarde: false. |
| [get_Space](./get_space/)() const | Ruimte tussen de CodeText en de [BarCode](../../aspose.barcode/) in [Unit ](../unit/)-waarde. Standaardwaarde: 2pt. Genegeerd voor EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [get_TwoDDisplayText](./get_twoddisplaytext/)() const | Tekst die wordt weergegeven in plaats van codetext in 2D‑barcodes. Gebruikt voor: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [set_Alignment](./set_alignment/)(TextAlignment) | Stelt de uitlijning van de code‑tekst in. Standaardwaarde: [StringAlignment.Center](../textalignment/). |
| [set_Color](./set_color/)(System::Drawing::Color) | Specificeer de weergavekleur van de CodeText. Standaardwaarde: Color.Black. |
| [set_FontMode](./set_fontmode/)(Aspose::BarCode::Generation::FontMode) | Specificeer FontMode. Als FontMode is ingesteld op Auto, wordt de lettergrootte automatisch berekend op basis van de xDimension-waarde. Het wordt aanbevolen om [FontMode.Auto](../aztecencodemode/) te gebruiken, vooral in [AutoSizeMode.Nearest](../autosizemode/) of [AutoSizeMode.Interpolation](../autosizemode/). Standaardwaarde: [FontMode.Auto](../aztecencodemode/). |
| [set_Location](./set_location/)(CodeLocation) | Specificeer de weergave‑locatie van CodeText, stel in op [CodeLocation.None](../codelocation/) om CodeText te verbergen. Standaardwaarde: [CodeLocation.Below](../codelocation/) voor 1D‑barcodes en [CodeLocation.None](../codelocation/) voor 2D‑barcodes. |
| [set_NoWrap](./set_nowrap/)(bool) | Specificeer woordomslag (regeleinden) binnen de tekst. Standaardwaarde: false. |
| [set_Space](./set_space/)(System::SharedPtr\<Unit\>) | Ruimte tussen de CodeText en de [BarCode](../../aspose.barcode/) in [Unit ](../unit/)-waarde. Standaardwaarde: 2pt. Genegeerd voor EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [set_TwoDDisplayText](./set_twoddisplaytext/)(System::String) | Tekst die wordt weergegeven in plaats van codetext in 2D‑barcodes. Gebruikt voor: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [ToString](./tostring/)() const override | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [CodetextParameters](./). |
## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
