---
title: "BarcodeParameters"
second_title: "Aspose.BarCode für Python über .NET API-Referenz"
description: 
type: docs
url: /de/python-net/aspose.barcode.generation/barcodeparameters/
---

## BarcodeParameters class

Parameter zur Barcode‑Erzeugung.

Der BarcodeParameters-Typ stellt die folgenden Mitglieder bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| x_dimension | x-dimension ist die kleinste Breite der Einheit von BarCode‑Balken oder -Lücken.<br/>            Eine Erhöhung davon vergrößert die gesamte Barcode‑Bildbreite.<br/>            Ignoriert, wenn die [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/)‑Eigenschaft auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist. |
| bar_height | Höhe der Balken von 1D‑Barcodes im [Unit](/barcode/python-net/aspose.barcode.generation/unit/)-Wert.<br/>            Ignoriert, wenn die [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/)‑Eigenschaft auf AutoSizeMode.Nearest oder AutoSizeMode.Interpolation gesetzt ist. |
| bar_color | Farbe der Balken.<br/>            Standardwert: Color.Black. |
| padding | Barcode‑Abstände.<br/>            Standardwert: 5pt 5pt 5pt 5pt. |
| checksum_always_show | Checksum‑Ziffer immer im menschenlesbaren Text für Code128‑ und GS1Code128‑Barcodes anzeigen. |
| is_checksum_enabled |  |
| throw_exception_when_code_text_incorrect | Nur für 1D‑Barcodes.<br/>            Wenn der Codetext inkorrekt ist und der Wert auf true gesetzt ist, wird eine Ausnahme ausgelöst. Andernfalls wird der Codetext korrigiert, um der Barcode‑Spezifikation zu entsprechen.<br/>            Eine Ausnahme wird immer ausgelöst für: Databar‑Symbol, wenn der Codetext inkorrekt ist.<br/>            Eine Ausnahme wird niemals ausgelöst für: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128‑Symbol, wenn der Codetext inkorrekt ist. |
| wide_narrow_ratio | Verhältnis von breiten zu schmalen Balken.<br/>            Standardwert: 3, das heißt, breite Balken sind dreimal so breit wie schmale Balken.<br/>            Verwendet für ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| code_text_parameters | Codetext‑Parameter. |
| filled_bars | Ruft den Wert ab oder legt ihn fest, der angibt, ob Balken gefüllt sind.<br/>            Nur für 1D‑Barcodes.<br/>            Standardwert: true. |
| bar_width_reduction | Ruft den Reduktionswert für Balken ab oder legt ihn fest, der verwendet wird, um die Tintenausbreitung beim Drucken auszugleichen.<br/>            Standardwert: 0 |
| postal | Post-Parameter. Verwendet für Postnet, Planet. |
| patch_code | PatchCode-Parameter. |
| australian_post | AustralianPost‑Barcode‑Parameter. |
| data_bar | Databar‑Parameter. |
| gs1_composite_bar | GS1 Composite Bar Parameter. |
| codablock | Codablock‑Parameter. |
| data_matrix | DataMatrix‑Parameter. |
| code_16k | Code16K‑Parameter. |
| dot_code | DotCode‑Parameter. |
| itf | ITF‑Parameter. |
| pdf417 | PDF417 Parameter. |
| qr | QR, MicroQR und RectMicroQR Parameter. |
| supplement | Ergänzungsparameter. Verwendet für Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| maxi_code | MaxiCode-Parameter. |
| aztec | Aztec-Parameter. |
| code128 | Code128‑Parameter. |
| codabar | Codabar‑Parameter. |
| coupon | Coupon‑Parameter. Verwendet für UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| han_xin | HanXin Parameter. |
| gs1 | GS1‑Parameter. |

### Siehe auch

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

