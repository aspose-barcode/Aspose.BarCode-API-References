---
title: "Aspose::BarCode::Generation::CodetextParameters class"
linktitle: "CodetextParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::Generation::CodetextParameters class. Parametri di codetext in C++."
type: docs
weight: 1500
url: /it/cpp/aspose.barcode.generation/codetextparameters/
---
## CodetextParameters class


Parametri Codetext.

```cpp
class CodetextParameters : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Alignment](./get_alignment/)() const | Ottiene l'allineamento del testo del codice. Valore predefinito: [StringAlignment.Center](../textalignment/). |
| [get_Color](./get_color/)() const | Specifica il colore del CodeText visualizzato. Valore predefinito: Color.Black. |
| [get_Font](./get_font/)() const | Specifica il carattere del CodeText visualizzato. Valore predefinito: Arial 5pt regular. Ignorato se FontMode è impostato su [FontMode.Auto](../aztecencodemode/). |
| [get_FontMode](./get_fontmode/)() const | Specifica FontMode. Se FontMode è impostato su Auto, la dimensione del carattere verrà calcolata automaticamente in base al valore xDimension. Si consiglia di utilizzare [FontMode.Auto](../aztecencodemode/) soprattutto in [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). Valore predefinito: [FontMode.Auto](../aztecencodemode/). |
| [get_Location](./get_location/)() const | Specifica la posizione del CodeText visualizzato, imposta su [CodeLocation.None](../codelocation/) per nascondere il CodeText. Valore predefinito: [CodeLocation.Below](../codelocation/) per i codici a barre 1D e [CodeLocation.None](../codelocation/) per i codici a barre 2D. |
| [get_NoWrap](./get_nowrap/)() const | Specifica le interruzioni di riga (word wraps) nel testo. Valore predefinito: false. |
| [get_Space](./get_space/)() const | Spazio tra il CodeText e il [BarCode](../../aspose.barcode/) in valore [Unit ](../unit/). Valore predefinito: 2pt. Ignorato per EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [get_TwoDDisplayText](./get_twoddisplaytext/)() const | Testo che verrà visualizzato al posto del codetext nei codici a barre 2D. Utilizzato per: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [set_Alignment](./set_alignment/)(TextAlignment) | Imposta l'allineamento del testo del codice. Valore predefinito: [StringAlignment.Center](../textalignment/). |
| [set_Color](./set_color/)(System::Drawing::Color) | Specifica il colore del CodeText visualizzato. Valore predefinito: Color.Black. |
| [set_FontMode](./set_fontmode/)(Aspose::BarCode::Generation::FontMode) | Specifica FontMode. Se FontMode è impostato su Auto, la dimensione del carattere verrà calcolata automaticamente in base al valore xDimension. Si consiglia di utilizzare [FontMode.Auto](../aztecencodemode/) soprattutto in [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). Valore predefinito: [FontMode.Auto](../aztecencodemode/). |
| [set_Location](./set_location/)(CodeLocation) | Specifica la posizione del CodeText visualizzato, imposta su [CodeLocation.None](../codelocation/) per nascondere il CodeText. Valore predefinito: [CodeLocation.Below](../codelocation/) per i codici a barre 1D e [CodeLocation.None](../codelocation/) per i codici a barre 2D. |
| [set_NoWrap](./set_nowrap/)(bool) | Specifica le interruzioni di riga (word wraps) nel testo. Valore predefinito: false. |
| [set_Space](./set_space/)(System::SharedPtr\<Unit\>) | Spazio tra il CodeText e il [BarCode](../../aspose.barcode/) in valore [Unit ](../unit/). Valore predefinito: 2pt. Ignorato per EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| [set_TwoDDisplayText](./set_twoddisplaytext/)(System::String) | Testo che verrà visualizzato al posto del codetext nei codici a barre 2D. Utilizzato per: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| [ToString](./tostring/)() const override | Restituisce una rappresentazione stringa leggibile dall'uomo di questo [CodetextParameters](./). |
## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
