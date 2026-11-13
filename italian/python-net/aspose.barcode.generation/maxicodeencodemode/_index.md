---
title: "MaxiCodeEncodeMode"
second_title: "Riferimento API Aspose.Sildes per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.generation/maxicodeencodemode/
---

## MaxiCodeEncodeMode enumeration

Modalità di codifica per i codici a barre MaxiCode.

## Members
| Nome membro | Descrizione |
| :- | :- |
| AUTO | In modalità Auto, il CodeText viene codificato con la massima compattezza dei dati. <br/>            I caratteri Unicode vengono ricodificati nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI.<br/>            Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene generata un'eccezione. |
| EXTENDED |  |
| BINARY | In modalità Binary, il CodeText viene codificato con la massima compattezza dei dati. <br/>            Se viene trovato un carattere Unicode, viene generata un'eccezione. |
| ECI | In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI.<br/>            Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene generata un'eccezione.<br/>            Si prega di notare che alcuni scanner vecchi (pre 2006) potrebbero non supportare questa modalità. |

### Vedi anche

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

