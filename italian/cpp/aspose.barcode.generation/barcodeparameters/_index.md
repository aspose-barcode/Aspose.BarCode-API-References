---
title: "Aspose::BarCode::Generation::BarcodeParameters classe"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::Generation::BarcodeParameters classe. Parametri di generazione del codice a barre in C++."
type: docs
weight: 500
url: /it/cpp/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class


Parametri di generazione del codice a barre.

```cpp
class BarcodeParameters : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_AustralianPost](./get_australianpost/)() const | Parametri del codice a barre AustralianPost. |
| [get_Aztec](./get_aztec/)() const | Parametri Aztec. |
| [get_BarColor](./get_barcolor/)() const | Colore delle barre. Valore predefinito: Color.Black. |
| [get_BarHeight](./get_barheight/)() const | Altezza delle barre dei codici a barre 1D in valore [Unit](../unit/). Ignorata se la proprietà [BaseGenerationParameters::AutoSizeMode](../) è impostata su [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). |
| [get_BarWidthReduction](./get_barwidthreduction/)() const | Ottiene o imposta il valore di riduzione delle barre utilizzato per compensare la diffusione dell'inchiostro durante la stampa. Valore predefinito: 0 |
| [get_ChecksumAlwaysShow](./get_checksumalwaysshow/)() const | Mostra sempre la cifra di checksum nel testo leggibile dall'uomo per i codici a barre Code128 e GS1Code128. |
| [get_Codabar](./get_codabar/)() const | Parametri Codabar. |
| [get_Codablock](./get_codablock/)() const | Parametri Codablock. |
| [get_Code128](./get_code128/)() const | Parametri Code128. |
| [get_Code16K](./get_code16k/)() const | Parametri Code16K. |
| [get_CodeTextParameters](./get_codetextparameters/)() const | Parametri Codetext. |
| [get_Coupon](./get_coupon/)() const | Parametri Coupon. Utilizzati per UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [get_DataBar](./get_databar/)() const | Parametri Databar. |
| [get_DataMatrix](./get_datamatrix/)() const | Parametri DataMatrix. |
| [get_DotCode](./get_dotcode/)() const | Parametri DotCode. |
| [get_FilledBars](./get_filledbars/)() const | Restituisce un valore che indica se le barre sono riempite. Solo per i codici a barre 1D. Valore predefinito: true. |
| [get_GS1](./get_gs1/)() const | Parametri GS1. |
| [get_GS1CompositeBar](./get_gs1compositebar/)() const | Parametri del GS1 Composite Bar. |
| [get_HanXin](./get_hanxin/)() const | Parametri HanXin. |
| [get_IsChecksumEnabled](./get_ischecksumenabled/)() const |  |
| [get_ITF](./get_itf/)() const | Parametri ITF. |
| [get_MaxiCode](./get_maxicode/)() const | Parametri MaxiCode. |
| [get_Padding](./get_padding/)() const | Spaziatura del codice a barre. Valore predefinito: 5pt 5pt 5pt 5pt. |
| [get_PatchCode](./get_patchcode/)() const | Parametri PatchCode. |
| [get_Pdf417](./get_pdf417/)() const | Parametri PDF417. |
| [get_Postal](./get_postal/)() const | Parametri postali. Utilizzati per Postnet, Planet. |
| [get_QR](./get_qr/)() const | Parametri QR, MicroQR e RectMicroQR. |
| [get_Supplement](./get_supplement/)() const | Parametri supplementari. Utilizzati per Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [get_ThrowExceptionWhenCodeTextIncorrect](./get_throwexceptionwhencodetextincorrect/)() const | Solo per i codici a barre 1D. Se il codetext è errato e il valore è impostato su true, verrà generata un'eccezione. Altrimenti il codetext verrà corretto per conformarsi alla specifica del codice a barre. L'eccezione verrà sempre generata per: la simbologia Databar se il codetext è errato. L'eccezione non verrà mai generata per: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, la simbologia Code128 se il codetext è errato. |
| [get_WideNarrowRatio](./get_widenarrowratio/)() const | Rapporto tra barre larghe e barre strette. Valore predefinito: 3, cioè le barre larghe sono 3 volte più larghe delle barre strette. Utilizzato per ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [get_XDimension](./get_xdimension/)() const | La x-dimension è la larghezza minima dell'unità delle barre o spazi di [BarCode](../../aspose.barcode/). Incrementare questo aumenterà la larghezza dell'intera immagine del codice a barre. Ignorato se la proprietà [BaseGenerationParameters::AutoSizeMode](../) è impostata su [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarColor](./set_barcolor/)(System::Drawing::Color) | Colore delle barre. Valore predefinito: Color.Black. |
| [set_BarHeight](./set_barheight/)(System::SharedPtr\<Unit\>) | Altezza delle barre dei codici a barre 1D in valore [Unit](../unit/). Ignorata se la proprietà [BaseGenerationParameters::AutoSizeMode](../) è impostata su [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). |
| [set_BarWidthReduction](./set_barwidthreduction/)(System::SharedPtr\<Unit\>) | Ottiene o imposta il valore di riduzione delle barre utilizzato per compensare la diffusione dell'inchiostro durante la stampa. Valore predefinito: 0 |
| [set_ChecksumAlwaysShow](./set_checksumalwaysshow/)(bool) | Mostra sempre la cifra di checksum nel testo leggibile dall'uomo per i codici a barre Code128 e GS1Code128. |
| [set_FilledBars](./set_filledbars/)(bool) | Imposta un valore che indica se le barre sono riempite. Solo per i codici a barre 1D. Valore predefinito: true. |
| [set_GS1CompositeBar](./set_gs1compositebar/)(System::SharedPtr\<GS1CompositeBarParameters\>) | Parametri del GS1 Composite Bar. |
| [set_IsChecksumEnabled](./set_ischecksumenabled/)(EnableChecksum) |  |
| [set_ThrowExceptionWhenCodeTextIncorrect](./set_throwexceptionwhencodetextincorrect/)(bool) | Solo per i codici a barre 1D. Se il codetext è errato e il valore è impostato su true, verrà generata un'eccezione. Altrimenti il codetext verrà corretto per conformarsi alla specifica del codice a barre. L'eccezione verrà sempre generata per: la simbologia Databar se il codetext è errato. L'eccezione non verrà mai generata per: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, la simbologia Code128 se il codetext è errato. |
| [set_WideNarrowRatio](./set_widenarrowratio/)(float) | Rapporto tra barre larghe e barre strette. Valore predefinito: 3, cioè le barre larghe sono 3 volte più larghe delle barre strette. Utilizzato per ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII. |
| [set_XDimension](./set_xdimension/)(System::SharedPtr\<Unit\>) | La x-dimension è la larghezza minima dell'unità delle barre o spazi di [BarCode](../../aspose.barcode/). Incrementare questo aumenterà la larghezza dell'intera immagine del codice a barre. Ignorato se la proprietà [BaseGenerationParameters::AutoSizeMode](../) è impostata su [AutoSizeMode.Nearest](../autosizemode/) o [AutoSizeMode.Interpolation](../autosizemode/). |
## Vedi anche

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
