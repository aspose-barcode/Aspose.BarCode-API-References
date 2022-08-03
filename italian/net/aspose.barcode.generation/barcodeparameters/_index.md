---
title: BarcodeParameters
second_title: Riferimento all'API Aspose.BarCode per .NET
description: Parametri di generazione del codice a barre.
type: docs
weight: 500
url: /it/net/aspose.barcode.generation/barcodeparameters/
---
## BarcodeParameters class

Parametri di generazione del codice a barre.

```csharp
public class BarcodeParameters
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AustralianPost](../../aspose.barcode.generation/barcodeparameters/australianpost) { get; } | Parametri del codice a barre AustralianPost. |
| [Aztec](../../aspose.barcode.generation/barcodeparameters/aztec) { get; } | parametri aztechi. |
| [BarColor](../../aspose.barcode.generation/barcodeparameters/barcolor) { get; set; } | Colore barre. Valore predefinito: Colore.Nero. |
| [BarHeight](../../aspose.barcode.generation/barcodeparameters/barheight) { get; set; } | Altezza delle barre dei codici a barre 1D in[`Unit`](../unit) value. Ignorato seAutoSizeMode la proprietà è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| [BarWidthReduction](../../aspose.barcode.generation/barcodeparameters/barwidthreduction) { get; set; } | Ottieni o imposta il valore di riduzione delle barre utilizzato per compensare la diffusione dell'inchiostro durante la stampa. Valore predefinito: 0 |
| [ChecksumAlwaysShow](../../aspose.barcode.generation/barcodeparameters/checksumalwaysshow) { get; set; } | Visualizza sempre la cifra del checksum nel testo leggibile per i codici a barre Code128 e GS1Code128. |
| [Codabar](../../aspose.barcode.generation/barcodeparameters/codabar) { get; } | Parametri Codabar. |
| [Codablock](../../aspose.barcode.generation/barcodeparameters/codablock) { get; } | Parametri blocco codice. |
| [Code16K](../../aspose.barcode.generation/barcodeparameters/code16k) { get; } | Code16K parametri. |
| [CodeTextParameters](../../aspose.barcode.generation/barcodeparameters/codetextparameters) { get; } | Parametri testo codice. |
| [Coupon](../../aspose.barcode.generation/barcodeparameters/coupon) { get; } | Parametri del buono. Utilizzato per UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBar](../../aspose.barcode.generation/barcodeparameters/databar) { get; } | Parametri della barra dati. |
| [DataMatrix](../../aspose.barcode.generation/barcodeparameters/datamatrix) { get; } | Parametri DataMatrix. |
| [DotCode](../../aspose.barcode.generation/barcodeparameters/dotcode) { get; } | Parametri DotCode. |
| [EnableEscape](../../aspose.barcode.generation/barcodeparameters/enableescape) { get; set; } | Indica se spiega il carattere "\" come carattere di escape nella proprietà CodeText. Utilizzato solo per Pdf417, DataMatrix, Code128 Se EnableEscape è true, "\" verrà spiegato come un carattere di escape speciale. In caso contrario, "\" funge da normale carattere. Aspose.BarCode supporta l'immissione di codice ascii decimale e mnemonico per i caratteri del codice di controllo ASCII. Ad esempio, \013 e \\CR sta per CR. |
| [FilledBars](../../aspose.barcode.generation/barcodeparameters/filledbars) { get; set; } | Ottiene o imposta un valore che indica se le barre sono state riempite. Solo per codici a barre 1D. Valore predefinito: true. |
| [GS1CompositeBar](../../aspose.barcode.generation/barcodeparameters/gs1compositebar) { get; set; } | Parametri della barra composita GS1. |
| [IsChecksumEnabled](../../aspose.barcode.generation/barcodeparameters/ischecksumenabled) { get; set; } | Abilita checksum durante la generazione di codici a barre 1D. |
| [ITF](../../aspose.barcode.generation/barcodeparameters/itf) { get; } | Parametri ITF. |
| [MaxiCode](../../aspose.barcode.generation/barcodeparameters/maxicode) { get; } | parametri MaxiCode. |
| [Padding](../../aspose.barcode.generation/barcodeparameters/padding) { get; } | Padding codici a barre. Valore predefinito: 5pt 5pt 5pt 5pt. |
| [PatchCode](../../aspose.barcode.generation/barcodeparameters/patchcode) { get; } | Parametri PatchCode. |
| [Pdf417](../../aspose.barcode.generation/barcodeparameters/pdf417) { get; } | Parametri PDF417. |
| [Postal](../../aspose.barcode.generation/barcodeparameters/postal) { get; } | Parametri postali. Usato per Postnet, Planet. |
| [QR](../../aspose.barcode.generation/barcodeparameters/qr) { get; } | Parametri QR. |
| [Supplement](../../aspose.barcode.generation/barcodeparameters/supplement) { get; } | Supplemento parametri. Utilizzato per Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.generation/barcodeparameters/throwexceptionwhencodetextincorrect) { get; set; } | Solo per codici a barre 1D. Se il testo del codice non è corretto e il valore è impostato su true, verrà generata un'eccezione. Altrimenti il testo del codice verrà corretto in modo che corrisponda alle specifiche del codice a barre. Verrà sempre generata un'eccezione per: Simbologia della barra dati se il testo del codice non è corretto. L'eccezione non verrà sempre generata per: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Simbologia del codice128 se il testo del codice non è corretto . |
| [WideNarrowRatio](../../aspose.barcode.generation/barcodeparameters/widenarrowratio) { get; set; } | Rapporto tra barre larghe e barre strette. Valore predefinito: 3, ovvero le barre larghe sono 3 volte più larghe delle barre strette. Usato per ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.generation/barcodeparameters/xdimension) { get; set; } | x-dimension è la larghezza più piccola dell'unità di barre o spazi del codice a barre. Aumenta questo aumenterà l'intera larghezza dell'immagine del codice a barre. Ignorato seAutoSizeMode la proprietà è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |

### Guarda anche

* spazio dei nomi [Aspose.BarCode.Generation](../../aspose.barcode.generation)
* assemblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
