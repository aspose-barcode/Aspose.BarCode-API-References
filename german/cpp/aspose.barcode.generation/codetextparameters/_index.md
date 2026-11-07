---
title: "Aspose::BarCode::Generation::CodetextParameters class"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::CodetextParameters class. Codetext-Parameter in C++."
type: docs
weight: 1500
url: /de/cpp/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class


Codetext-Parameter.

```cpp
class CodetextParameters : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_Alignment](./get_alignment/)() const | Ermittelt die Ausrichtung des Codetextes. Standardwert: [StringAlignment.Center](../textalignment/). |
| [get_Color](./get_color/)() const | Geben Sie die Anzeigefarbe des CodeTextes an. Standardwert: Color.Black. |
| [get_Font](./get_font/)() const | Geben Sie die Schriftart des angezeigten CodeTextes an. Standardwert: Arial 5pt regular. Wird ignoriert, wenn FontMode auf [FontMode.Auto](../aztecencodemode/) gesetzt ist. |
| [get_FontMode](./get_fontmode/)() const | Geben Sie FontMode an. Wenn FontMode auf Auto gesetzt ist, wird die Schriftgröße automatisch basierend auf dem xDimension-Wert berechnet. Es wird empfohlen, [FontMode.Auto](../aztecencodemode/) zu verwenden, insbesondere in [AutoSizeMode.Nearest](../autosizemode/) oder [AutoSizeMode.Interpolation](../autosizemode/). Standardwert: [FontMode.Auto](../aztecencodemode/). |
| [get_Location](./get_location/)() const | Geben Sie den Anzeigestandort des CodeTextes an, setzen Sie ihn auf [CodeLocation.None](../codelocation/), um den CodeText auszublenden. Standardwert: [CodeLocation.Below](../codelocation/) für 1D-Barcodes und [CodeLocation.None](../codelocation/) für 2D-Barcodes. |
| [get_NoWrap](./get_nowrap/)() const | Geben Sie Zeilenumbrüche (Wortumbrüche) im Text an. Standardwert: false. |
| [get_Space](./get_space/)() const | Abstand zwischen dem CodeText und dem [BarCode](../../aspose.barcode/) im [Unit ](../unit/)-Wert. Standardwert: 2pt. Wird ignoriert für EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [get_TwoDDisplayText](./get_twoddisplaytext/)() const | Text, der anstelle des Codetextes in 2D-Barcodes angezeigt wird. Verwendet für: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [set_Alignment](./set_alignment/)(TextAlignment) | Legt die Ausrichtung des Code-Textes fest. Standardwert: [StringAlignment.Center](../textalignment/). |
| [set_Color](./set_color/)(System::Drawing::Color) | Geben Sie die Anzeigefarbe des CodeTextes an. Standardwert: Color.Black. |
| [set_FontMode](./set_fontmode/)(Aspose::BarCode::Generation::FontMode) | Geben Sie FontMode an. Wenn FontMode auf Auto gesetzt ist, wird die Schriftgröße automatisch basierend auf dem xDimension-Wert berechnet. Es wird empfohlen, [FontMode.Auto](../aztecencodemode/) zu verwenden, insbesondere in [AutoSizeMode.Nearest](../autosizemode/) oder [AutoSizeMode.Interpolation](../autosizemode/). Standardwert: [FontMode.Auto](../aztecencodemode/). |
| [set_Location](./set_location/)(CodeLocation) | Geben Sie den Anzeigestandort des CodeTextes an, setzen Sie ihn auf [CodeLocation.None](../codelocation/), um den CodeText auszublenden. Standardwert: [CodeLocation.Below](../codelocation/) für 1D-Barcodes und [CodeLocation.None](../codelocation/) für 2D-Barcodes. |
| [set_NoWrap](./set_nowrap/)(bool) | Geben Sie Zeilenumbrüche (Wortumbrüche) im Text an. Standardwert: false. |
| [set_Space](./set_space/)(System::SharedPtr\<Unit\>) | Abstand zwischen dem CodeText und dem [BarCode](../../aspose.barcode/) im [Unit ](../unit/)-Wert. Standardwert: 2pt. Wird ignoriert für EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [set_TwoDDisplayText](./set_twoddisplaytext/)(System::String) | Text, der anstelle des Codetextes in 2D-Barcodes angezeigt wird. Verwendet für: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieser [CodetextParameters](./) zurück. |
## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
