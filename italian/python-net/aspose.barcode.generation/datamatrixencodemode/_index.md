---
title: "DataMatrixEncodeMode"
second_title: "Riferimento API Aspose.Sildes per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.generation/datamatrixencodemode/
---

## DataMatrixEncodeMode enumeration

Modalità di codifica dell'encoder DataMatrix, predefinita su Auto

## Members
| Nome membro | Descrizione |
| :- | :- |
| AUTO | In modalità Auto, il CodeText viene codificato con la massima compattezza dei dati. <br/>            I caratteri Unicode vengono ricodificati nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI.<br/>            Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene generata un'eccezione. |
| ASCII | Codifica un carattere alfanumerico o due caratteri numerici per byte |
| C40 | Utilizza la codifica C40. Codifica alfanumerici maiuscoli, minuscoli e caratteri speciali |
| TEXT | Utilizza la codifica Text. Codifica alfanumerici minuscoli, maiuscoli e caratteri speciali |
| EDIFACT | Utilizza la codifica EDIFACT. Usa sei bit per carattere, codifica cifre, lettere maiuscole e molti segni di punteggiatura, ma non supporta le lettere minuscole. |
| ANSIX12 | Utilizza la codifica ANSI X12. |
| EXTENDED |  |
| BASE256 | Codifica valori a 8 bit |
| BINARY | In modalità Binary, il CodeText viene codificato con la massima compattezza dei dati. <br/>            Se viene trovato un carattere Unicode, viene generata un'eccezione. |
| ECI | In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI.<br/>            Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene generata un'eccezione.<br/>            Si prega di notare che alcuni scanner vecchi (pre 2006) potrebbero non supportare questa modalità. |

### Vedi anche

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

