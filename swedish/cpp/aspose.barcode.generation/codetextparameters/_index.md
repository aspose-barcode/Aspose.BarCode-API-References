---
title: "Aspose::BarCode::Generation::CodetextParameters klass"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::CodetextParameters klass. Kodtextparametrar i C++."
type: docs
weight: 1500
url: /sv/cpp/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class


Parametrar för kodtext.

```cpp
class CodetextParameters : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Alignment](./get_alignment/)() const | Hämtar justeringen av kodtexten. Standardvärde: [StringAlignment.Center](../textalignment/). |
| [get_Color](./get_color/)() const | Ange färgen för den visade kodtexten. Standardvärde: Color.Black. |
| [get_Font](./get_font/)() const | Ange teckensnittet för den visade CodeText. Standardvärde: Arial 5pt regular. Ignoreras om FontMode är inställt på [FontMode.Auto](../aztecencodemode/). |
| [get_FontMode](./get_fontmode/)() const | Ange FontMode. Om FontMode är inställt på Auto beräknas teckenstorleken automatiskt baserat på xDimension‑värdet. Det rekommenderas att använda [FontMode.Auto](../aztecencodemode/) särskilt i [AutoSizeMode.Nearest](../autosizemode/) eller [AutoSizeMode.Interpolation](../autosizemode/). Standardvärde: [FontMode.Auto](../aztecencodemode/). |
| [get_Location](./get_location/)() const | Ange platsen för den visade CodeText, sätt till [CodeLocation.None](../codelocation/) för att dölja CodeText. Standardvärde: [CodeLocation.Below](../codelocation/) för 1D‑streckkoder och [CodeLocation.None](../codelocation/) för 2D‑streckkoder. |
| [get_NoWrap](./get_nowrap/)() const | Ange radbrytningar (ordbrytningar) i texten. Standardvärde: false. |
| [get_Space](./get_space/)() const | Avståndet mellan CodeText och [BarCode](../../aspose.barcode/) i [Unit ](../unit/)-värde. Standardvärde: 2pt. Ignoreras för EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [get_TwoDDisplayText](./get_twoddisplaytext/)() const | Text som kommer att visas istället för codetext i 2D‑streckkoder. Används för: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [set_Alignment](./set_alignment/)(TextAlignment) | Ställer in justeringen av kodtexten. Standardvärde: [StringAlignment.Center](../textalignment/). |
| [set_Color](./set_color/)(System::Drawing::Color) | Ange färgen för den visade kodtexten. Standardvärde: Color.Black. |
| [set_FontMode](./set_fontmode/)(Aspose::BarCode::Generation::FontMode) | Ange FontMode. Om FontMode är inställt på Auto beräknas teckenstorleken automatiskt baserat på xDimension‑värdet. Det rekommenderas att använda [FontMode.Auto](../aztecencodemode/) särskilt i [AutoSizeMode.Nearest](../autosizemode/) eller [AutoSizeMode.Interpolation](../autosizemode/). Standardvärde: [FontMode.Auto](../aztecencodemode/). |
| [set_Location](./set_location/)(CodeLocation) | Ange platsen för den visade CodeText, sätt till [CodeLocation.None](../codelocation/) för att dölja CodeText. Standardvärde: [CodeLocation.Below](../codelocation/) för 1D‑streckkoder och [CodeLocation.None](../codelocation/) för 2D‑streckkoder. |
| [set_NoWrap](./set_nowrap/)(bool) | Ange radbrytningar (ordbrytningar) i texten. Standardvärde: false. |
| [set_Space](./set_space/)(System::SharedPtr\<Unit\>) | Avståndet mellan CodeText och [BarCode](../../aspose.barcode/) i [Unit ](../unit/)-värde. Standardvärde: 2pt. Ignoreras för EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [set_TwoDDisplayText](./set_twoddisplaytext/)(System::String) | Text som kommer att visas istället för codetext i 2D‑streckkoder. Används för: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [CodetextParameters](./). |
## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
