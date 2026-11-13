---
title: "BarcodeParameters"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.generation/barcodeparameters/
---

## BarcodeParameters class

Parametri di generazione del barcode.

Il tipo BarcodeParameters espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| x_dimension | x-dimension è la larghezza minima dell'unità delle barre o spazi del codice a barre.<br/>            Incrementare questo aumenterà l'intera larghezza dell'immagine del codice a barre.<br/>            Ignorato se la proprietà [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| bar_height | Altezza delle barre dei codici a barre 1D in valore [Unit](/barcode/python-net/aspose.barcode.generation/unit/).<br/>            Ignorato se la proprietà [auto_size_mode](/barcode/python-net/aspose.barcode.generation/basegenerationparameters/) è impostata su AutoSizeMode.Nearest o AutoSizeMode.Interpolation. |
| bar_color | Colore delle barre.<br/>            Valore predefinito: Color.Black. |
| padding | Spaziatura del codice a barre.<br/>            Valore predefinito: 5pt 5pt 5pt 5pt. |
| checksum_always_show | Mostra sempre la cifra di checksum nel testo leggibile dall'uomo per i codici a barre Code128 e GS1Code128. |
| is_checksum_enabled |  |
| throw_exception_when_code_text_incorrect | Solo per codici a barre 1D.<br/>            Se il testo del codice è errato e il valore è impostato su true - verrà sollevata un'eccezione. Altrimenti il testo del codice verrà corretto per conformarsi alla specifica del codice a barre.<br/>            L'eccezione verrà sempre sollevata per: simbologia Databar se il testo del codice è errato.<br/>            L'eccezione non verrà mai sollevata per: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, simbologia Code128 se il testo del codice è errato. |
| wide_narrow_ratio | Rapporto tra barre larghe e barre strette.<br/>            Valore predefinito: 3, cioè le barre larghe sono 3 volte più larghe delle barre strette.<br/>            Utilizzato per ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII |
| code_text_parameters | Parametri Codetext. |
| filled_bars | Ottiene o imposta un valore che indica se le barre sono riempite.<br/>            Solo per codici a barre 1D.<br/>            Valore predefinito: true. |
| bar_width_reduction | Ottiene o imposta il valore di riduzione delle barre usato per compensare la diffusione dell'inchiostro durante la stampa.<br/>            Valore predefinito: 0 |
| postal | Parametri postali. Utilizzati per Postnet, Planet. |
| patch_code | Parametri PatchCode. |
| australian_post | Parametri del codice a barre AustralianPost. |
| data_bar | Parametri Databar. |
| gs1_composite_bar | Parametri della barra composita GS1. |
| codablock | Parametri Codablock. |
| data_matrix | Parametri DataMatrix. |
| code_16k | Parametri Code16K. |
| dot_code | Parametri DotCode. |
| itf | Parametri ITF. |
| pdf417 | Parametri PDF417. |
| qr | Parametri QR, MicroQR e RectMicroQR. |
| supplement | Parametri supplementari. Utilizzati per Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| maxi_code | Parametri MaxiCode. |
| aztec | Parametri Aztec. |
| code128 | Parametri Code128. |
| codabar | Parametri Codabar. |
| coupon | Parametri Coupon. Utilizzati per UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| han_xin | Parametri HanXin. |
| gs1 | Parametri GS1. |

### Vedi anche

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

