---
title: BarCodeGeneratorControl
second_title: Riferimento all'API Aspose.BarCode per .NET
description: BarCode Windows Control vai al pannello della tua casella degli strumenti e aggiungi Aspose.BarCode.dll e vedrai apparire BarcodeGeneratorControl. Basta trascinarlo e rilasciarlo nel tuo modulo di Windows. vedi vedi
type: docs
weight: 1050
url: /it/net/aspose.barcode.windows.forms/barcodegeneratorcontrol/
---
## BarCodeGeneratorControl class

BarCode Windows Control, vai al pannello della tua casella degli strumenti e aggiungi Aspose.BarCode.dll, e vedrai apparire BarcodeGeneratorControl. Basta trascinarlo e rilasciarlo nel tuo modulo di Windows. vedi vedi

```csharp
public sealed class BarCodeGeneratorControl : Control, IBarCodeGeneratorControl
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [BarCodeGeneratorControl](barcodegeneratorcontrol)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoSizeMode](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/autosizemode) { get; set; } | Ottiene o imposta la modalità con cui il codice a barre viene ridimensionato automaticamente. Il valore predefinito è AutoSizeMode.None. |
| [BackgroundColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/backgroundcolor) { get; set; } | Colore di sfondo dell'immagine del codice a barre. |
| [BarCodeHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodeheight) { get; } | Altezza immagine codice a barre quando[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) la proprietà è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| [BarcodePaddings](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodepaddings) { get; } | Ottiene o imposta i parametri di riempimento del codice a barre[`Padding`](../../aspose.barcode.generation/padding) . |
| [BarcodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodetype) { get; set; } | Tipo di codifica di BarCode (simbologia). Usa[`EncodeTypes`](../../aspose.barcode.generation/encodetypes) per ottenere la simbologia corrente. |
| [BarCodeWidth](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcodewidth) { get; } | Larghezza immagine codice a barre quando[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) la proprietà è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| [BarColor](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barcolor) { get; set; } | Colore barre. |
| [BarHeight](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/barheight) { get; } | Altezza delle barre dei codici a barre 1D. Ignorato se[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) la proprietà è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| [Border](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/border) { get; } | Ottiene o imposta i parametri Border[`BorderParameters`](../../aspose.barcode.generation/borderparameters) . |
| [CaptionAbove](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionabove) { get; } | Didascalia sopra l'immagine del codice a barre. Vedere[`CaptionParameters`](../../aspose.barcode.generation/captionparameters) . |
| [CaptionBelow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/captionbelow) { get; } | Didascalia sotto l'immagine del codice a barre. Vedere[`CaptionParameters`](../../aspose.barcode.generation/captionparameters) . |
| [ChecksumAlwaysShow](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/checksumalwaysshow) { get; set; } | Visualizza sempre la cifra del checksum nel testo leggibile per i codici a barre Code128 e GS1Code128. |
| [CodeText](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetext) { get; set; } | Dati da codificare, diversi tipi di codici a barre possono avere restrizioni di lunghezza CodeText diverse. |
| [CodeTextParameters](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/codetextparameters) { get; } | Ottiene o imposta i parametri CodeText[`CodetextParameters`](../../aspose.barcode.generation/codetextparameters) . |
| [EnableEscape](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/enableescape) { get; set; } | Indica se spiega il carattere "\" come carattere di escape nella proprietà CodeText. Utilizzato solo per Pdf417, DataMatrix, Code128 Se EnableEscape è true, "\" verrà spiegato come un carattere di escape speciale. In caso contrario, "\" funge da normale carattere. Aspose.BarCode supporta l'immissione di codice ascii decimale e mnemonico per i caratteri del codice di controllo ASCII. Ad esempio, \013 e \\CR sta per CR. |
| [EncodeType](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/encodetype) { get; set; } | Tipo di codifica di BarCode (simbologia). Usa[`EncodeTypes`](../../aspose.barcode.generation/encodetypes) per ottenere la simbologia corrente. |
| [FilledBars](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/filledbars) { get; set; } | Ottiene o imposta un valore che indica se le barre sono state riempite. Solo per codici a barre 1D. |
| [IsChecksumEnabled](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/ischecksumenabled) { get; set; } | Abilita checksum durante la generazione di codici a barre 1D. |
| [Resolution](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/resolution) { get; set; } | Ottiene o imposta la risoluzione dell'immagine BarCode. Un valore per entrambe le dimensioni. Valore predefinito: 96 dpi. |
| [RotationAngle](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/rotationangle) { get; set; } | Angolo di rotazione dell'immagine BarCode, misurato in gradi, es. RotationAngle = 0 o RotationAngle = 360 significa nessuna rotazione. Se RotationAngle NON è uguale a 90, 180, 270 o 0, può aumentare la difficoltà per lo scanner di leggere l'immagine. |
| [Specific](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/specific) { get; } | Parametri specifici |
| [ThrowExceptionWhenCodeTextIncorrect](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/throwexceptionwhencodetextincorrect) { get; set; } | Solo per codici a barre 1D. Se il testo del codice non è corretto e il valore è impostato su true, verrà generata un'eccezione. Altrimenti il testo del codice verrà corretto in modo che corrisponda alle specifiche del codice a barre. Verrà sempre generata un'eccezione per: Simbologia della barra dati se il testo del codice non è corretto. L'eccezione non verrà sempre generata per: AustraliaPost, SingapurePost, Code39Extended, Code93Extended, Code16K, Simbologia del codice128 se il testo del codice non è corretto . |
| [WideNarrowRatio](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/widenarrowratio) { get; set; } | Rapporto tra barre larghe e barre strette. Valore predefinito: 3, ovvero le barre larghe sono 3 volte più larghe delle barre strette. Usato per ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost , OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard |
| [XDimension](../../aspose.barcode.windows.forms/barcodegeneratorcontrol/xdimension) { get; } | X-dimension è la larghezza più piccola dell'unità di barre o spazi del codice a barre. Aumentare questo aumenterà l'intera larghezza dell'immagine del codice a barre. Ignorato se[`AutoSizeMode`](../../aspose.barcode.generation/autosizemode) la proprietà è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |

### Guarda anche

* interface [IBarCodeGeneratorControl](../ibarcodegeneratorcontrol)
* spazio dei nomi [Aspose.BarCode.Windows.Forms](../../aspose.barcode.windows.forms)
* assemblea [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
