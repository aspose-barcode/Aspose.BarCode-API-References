---
title: "CodetextParameters"
second_title: "Riferimento API Aspose.BarCode per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.generation/codetextparameters/
---

## CodetextParameters class

Parametri Codetext.

Il tipo CodetextParameters espone i seguenti membri:
## Proprietà
| Nome | Descrizione |
| :- | :- |
| two_d_display_text | Testo che verrà visualizzato al posto del codetext nei codici a barre 2D.<br/>            Utilizzato per: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode |
| font_mode | Specifica FontMode. Se FontMode è impostato su Auto, la dimensione del carattere verrà calcolata automaticamente in base al valore xDimension.<br/>            Si consiglia di utilizzare FontMode.Auto soprattutto in AutoSizeMode.Nearest o AutoSizeMode.Interpolation.<br/>            Valore predefinito: FontMode.Auto. |
| font | Specifica il carattere del CodeText visualizzato.<br/>            Valore predefinito: Arial 5pt regular.<br/>            Ignorato se FontMode è impostato su FontMode.Auto. |
| space | Spazio tra il CodeText e il BarCode nel valore [Unit](/barcode/python-net/aspose.barcode.generation/unit/).<br/>            Valore predefinito: 2pt.<br/>            Ignorato per EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon. |
| allineamento | Ottiene o imposta l'allineamento del testo del codice.<br/>            Valore predefinito: StringAlignment.Center. |
| colore | Specifica il colore del CodeText visualizzato.<br/>            Valore predefinito: Color.Black. |
| posizione | Specifica la posizione del CodeText visualizzato, impostare su CodeLocation.None per nascondere il CodeText.<br/>            Valore predefinito: CodeLocation.Below per codici a barre 1D e CodeLocation.None per codici a barre 2D. |
| no_wrap | Specifica le interruzioni di riga (a capo) all'interno del testo.<br/>            Valore predefinito: false. |

### Vedi anche

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

