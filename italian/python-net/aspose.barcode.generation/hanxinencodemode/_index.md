---
title: "HanXinEncodeMode"
second_title: "Riferimento API Aspose.Sildes per Python via .NET"
description: 
type: docs
url: /it/python-net/aspose.barcode.generation/hanxinencodemode/
---

## HanXinEncodeMode enumeration

Modalità di codifica Han Xin Code. Si consiglia di utilizzare Auto con caratteri ASCII / Cinesi o Unicode per i caratteri Unicode.

## Members
| Nome membro | Descrizione |
| :- | :- |
| AUTO | In modalità Auto, il CodeText è codificato con la massima compattezza dei dati. <br/>            I caratteri Unicode sono codificati usando la codifica GB18030 secondo la specifica del codice a barre HanXin. |
| BINARY | In modalità Binary, il CodeText viene codificato con la massima compattezza dei dati. <br/>            Se viene trovato un carattere Unicode, viene generata un'eccezione. |
| ECI | In modalità ECI, l'intero messaggio viene ricodificato nella codifica specificata da ECIEncoding con l'inserimento di un identificatore ECI.<br/>            Se viene trovato un carattere non supportato dalla codifica ECI selezionata, viene generata un'eccezione.<br/>            Si prega di notare che alcuni scanner vecchi (pre 2006) potrebbero non supportare questa modalità. |
| UNICODE | La modalità Unicode definisce un modo per rappresentare qualsiasi dato testuale facendo riferimento alla codifica/carattere UTF8 nel codice Han Xin. |
| URI | La modalità URI indica che i dati rappresentati nel codice Han Xin sono Uniform Resource Identifier (URI)<br/>            riferimento a RFC 3986. |
| EXTENDED | La modalità Extended consente combinazioni di modalità interne: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One,<br/>            Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte.<br/>            Il Codetext può essere costruito manualmente con prefissi e doppi backslash, ad esempio: @"\\auto:abc\\000009:ΑΒΓΔΕ\\auto:ab\\\\c" o utilizzando il HanXinExtCodetextBuilder.<br/>            Se il codetext contiene un frammento ECI, solo le seguenti modalità possono essere presenti in quel codetext dopo il frammento ECI:<br/>            Auto, Binary, Text, Numeric, URI, ECI. |

### Vedi anche

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

