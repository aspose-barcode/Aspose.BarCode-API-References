---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Parametri QR."
type: docs
weight: 830
url: /it/nodejs/aspose.barcode/qrparameters/
---

## QrParameters class

Parametri QR.

```js
new QrParameters()
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Rapporto Altezza/Larghezza del modulo BarCode 2D. |
| [getECIEncoding()](#geteciencoding) | Identificatori di Interpretazione Canale Esteso. Viene usato per fornire al lettore di codici a barre dettagli sui riferimenti utilizzati per |
| [getEncodeGS1SeparatorInByteMode()](#getencodegs1separatorinbytemode) | Ottiene o imposta un valore che indica se i caratteri speciali GS1 devono essere codificati in modalità Byte per i codici QR e RectMicroQR |
| [getEncodeMode()](#getencodemode) | Tipo di simbologia QR della modalità di codifica del BarCode. Valore predefinito: QREncodeMode.Auto. |
| [getErrorLevel()](#geterrorlevel) | Livello di correzione errori Reed-Solomon per i codici QR, MicroQR e RectMicroQR. Dal più basso al più alto: LevelL, LevelM, LevelQ |
| [getMicroQRVersion()](#getmicroqrversion) | Versione del codice MicroQR. Dalla versione M1 alla versione M4. Il valore predefinito è MicroQRVersion.Auto. |
| [getQrECIEncoding()](#getqreciencoding) ~~(deprecated)~~ | Identificatori di Interpretazione Canale Esteso. Viene usato per fornire al lettore di codici a barre dettagli sui riferimenti utilizzati per |
| [getQrEncodeMode()](#getqrencodemode) | Tipo di simbologia QR della modalità di codifica del BarCode. Valore predefinito: QREncodeMode.AUTO. |
| [getQrEncodeType()](#getqrencodetype) ~~(deprecated)~~ | Modalità di selezione QR / MicroQR. Seleziona ForceQR per i simboli QR standard, Auto per MicroQR. |
| [getQrErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Livello di correzione errori Reed-Solomon per il codice QR. Dal più basso al più alto: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. vedi QRError |
| [getQrVersion()](#getqrversion) ~~(deprecated)~~ | Versione del codice QR. Dalla Versione1 alla Versione40 per il codice QR e da M1 a M4 per MicroQr. Il valore predefinito è QRVersion.AUT. |
| [getRectMicroQrVersion()](#getrectmicroqrversion) | Versione del codice RectMicroQR. Dalla versione R7x59 alla versione R17x139. Il valore predefinito è RectMicroQRVersion.Auto. |
| [getStructuredAppend()](#getstructuredappend) | Parametri QR structured append. |
| [getVersion()](#getversion) | Versione del codice QR. Dalla Versione1 alla Versione40. Il valore predefinito è QRVersion.Auto. |
| [setAspectRatio()](#setaspectratio) | Rapporto Altezza/Larghezza del modulo BarCode 2D. |
| [setECIEncoding()](#seteciencoding) | Identificatori di Interpretazione Canale Esteso. Viene usato per fornire al lettore di codici a barre dettagli sui riferimenti utilizzati per |
| [setEncodeGS1SeparatorInByteMode(value)](#setencodegs1separatorinbytemode) | Ottiene o imposta un valore che indica se i caratteri speciali GS1 devono essere codificati in modalità Byte per i codici QR e RectMicroQR |
| [setEncodeMode()](#setencodemode) | Tipo di simbologia QR della modalità di codifica del BarCode. Valore predefinito: QREncodeMode.Auto. |
| [setErrorLevel()](#seterrorlevel) | Livello di correzione errori Reed-Solomon per i codici QR, MicroQR e RectMicroQR. Dal più basso al più alto: LevelL, LevelM, LevelQ |
| [setMicroQRVersion()](#setmicroqrversion) | Versione del codice MicroQR. Dalla versione M1 alla versione M4. Il valore predefinito è MicroQRVersion.Auto. |
| [setQrECIEncoding()](#setqreciencoding) ~~(deprecated)~~ | Identificatori di Interpretazione Canale Esteso. Viene usato per fornire al lettore di codici a barre dettagli sui riferimenti utilizzati per |
| [setQrEncodeMode()](#setqrencodemode) ~~(deprecated)~~ | Tipo di simbologia QR della modalità di codifica del BarCode. Valore predefinito: QREncodeMode.AUTO. |
| [setQrEncodeType()](#setqrencodetype) ~~(deprecated)~~ | Modalità di selezione QR / MicroQR. Seleziona ForceQR per i simboli QR standard, Auto per MicroQR. |
| [setQrErrorLevel()](#setqrerrorlevel) ~~(deprecated)~~ | Livello di correzione errori Reed-Solomon per il codice QR. Dal più basso al più alto: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. vedi QRError |
| [setQrVersion()](#setqrversion) ~~(deprecated)~~ | Versione del codice QR. Dalla Versione1 alla Versione40 per il codice QR e da M1 a M4 per MicroQr. Il valore predefinito è QRVersion.AUT. |
| [setRectMicroQrVersion()](#setrectmicroqrversion) | Versione del codice RectMicroQR. Dalla versione R7x59 alla versione R17x139. Il valore predefinito è RectMicroQRVersion.Auto. |
| [setStructuredAppend()](#setstructuredappend) | Parametri QR structured append. |
| [setVersion()](#setversion) | Versione del codice QR. Dalla Versione1 alla Versione40. Il valore predefinito è QRVersion.Auto. |
| [toString()](#tostring) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo QrParameters. |

### getAspectRatio() {#getaspectratio}

Rapporto Altezza/Larghezza del modulo BarCode 2D.

### getECIEncoding() {#geteciencoding}

Identificatori di Interpretazione del Canale Esteso. Vengono utilizzati per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. L'implementazione corrente comprende tutte le codifiche di set di caratteri conosciute. Non supportato da MicroQR.

### getEncodeGS1SeparatorInByteMode() {#getencodegs1separatorinbytemode}

Ottiene o imposta un valore che indica se i caratteri speciali GS1 devono essere codificati in modalità Byte per i codici QR e RectMicroQR. Se false, i separatori GS1 possono essere codificati come '%' in modalità Alfanumerica secondo la specifica QR. Se true, i separatori di gruppo GS1 sono codificati in modalità Byte come il carattere 0x1D, e i caratteri '%' sono anch'essi codificati in modalità Byte per preservarli come dati. Questa opzione può migliorare la compatibilità con i decoder che si aspettano separatori di gruppo GS1 a livello byte e impedisce che i caratteri dati '%' vengano interpretati come separatori GS1.

**Returns:** a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

### getEncodeMode() {#getencodemode}

Tipo di simbologia QR della modalità di codifica del BarCode. Valore predefinito: QREncodeMode.Auto.

### getErrorLevel() {#geterrorlevel}

Livello di correzione errori Reed-Solomon per i codici QR, MicroQR e RectMicroQR. Dal più basso al più alto: LevelL, LevelM, LevelQ, LevelH. Vedi QRErrorLevel.

### getMicroQRVersion() {#getmicroqrversion}

Versione del codice MicroQR. Dalla versione M1 alla versione M4. Il valore predefinito è MicroQRVersion.Auto.

### getQrECIEncoding() {#getqreciencoding}

> **Deprecated.** See method description for replacement.

Identificatori di Interpretazione del Canale Esteso. Viene utilizzato per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. L'implementazione attuale consiste di tutte le codifiche di set di caratteri conosciute.

### getQrEncodeMode() {#getqrencodemode}

Tipo di simbologia QR della modalità di codifica del BarCode. Valore predefinito: QREncodeMode.AUTO.

### getQrEncodeType() {#getqrencodetype}

> **Deprecated.** See method description for replacement.

Modalità di selezione QR / MicroQR. Seleziona ForceQR per i simboli QR standard, Auto per MicroQR.

### getQrErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Livello di correzione errori Reed-Solomon per il codice QR. Dal più basso al più alto: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. vedi QRErrorLevel.

### getQrVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Versione del codice QR. Dalla Versione1 alla Versione40 per il codice QR e da M1 a M4 per MicroQr. Il valore predefinito è QRVersion.AUTO.

### getRectMicroQrVersion() {#getrectmicroqrversion}

Versione del codice RectMicroQR. Dalla versione R7x59 alla versione R17x139. Il valore predefinito è RectMicroQRVersion.Auto.

### getStructuredAppend() {#getstructuredappend}

Parametri QR structured append.

### getVersion() {#getversion}

Versione del codice QR. Dalla Versione1 alla Versione40. Il valore predefinito è QRVersion.Auto.

### setAspectRatio() {#setaspectratio}

Rapporto Altezza/Larghezza del modulo BarCode 2D.

### setECIEncoding() {#seteciencoding}

Identificatori di Interpretazione del Canale Esteso. Vengono utilizzati per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. L'implementazione corrente comprende tutte le codifiche di set di caratteri conosciute. Non supportato da MicroQR.

### setEncodeGS1SeparatorInByteMode(value) {#setencodegs1separatorinbytemode}

Ottiene o imposta un valore che indica se i caratteri speciali GS1 devono essere codificati in modalità Byte per i codici QR e RectMicroQR. Se false, i separatori GS1 possono essere codificati come '%' in modalità Alfanumerica secondo la specifica QR. Se true, i separatori di gruppo GS1 sono codificati in modalità Byte come il carattere 0x1D, e i caratteri '%' sono anch'essi codificati in modalità Byte per preservarli come dati. Questa opzione può migliorare la compatibilità con i decoder che si aspettano separatori di gruppo GS1 a livello byte e impedisce che i caratteri dati '%' vengano interpretati come separatori GS1.

| Parametro | Descrizione |
| --- | --- |
| valore | un valore che indica se i caratteri speciali GS1 devono essere codificati in modalità Byte per i codici QR e RectMicroQR. |

### setEncodeMode() {#setencodemode}

Tipo di simbologia QR della modalità di codifica del BarCode. Valore predefinito: QREncodeMode.Auto.

### setErrorLevel() {#seterrorlevel}

Livello di correzione errori Reed-Solomon per i codici QR, MicroQR e RectMicroQR. Dal più basso al più alto: LevelL, LevelM, LevelQ, LevelH. Vedi QRErrorLevel.

### setMicroQRVersion() {#setmicroqrversion}

Versione del codice MicroQR. Dalla versione M1 alla versione M4. Il valore predefinito è MicroQRVersion.Auto.

### setQrECIEncoding() {#setqreciencoding}

> **Deprecated.** See method description for replacement.

Identificatori di Interpretazione del Canale Esteso. Viene utilizzato per fornire al lettore di codici a barre dettagli sui riferimenti usati per codificare i dati nel simbolo. L'implementazione attuale consiste di tutte le codifiche di set di caratteri conosciute.

### setQrEncodeMode() {#setqrencodemode}

> **Deprecated.** See method description for replacement.

Tipo di simbologia QR della modalità di codifica del BarCode. Valore predefinito: QREncodeMode.AUTO.

### setQrEncodeType() {#setqrencodetype}

> **Deprecated.** See method description for replacement.

Modalità di selezione QR / MicroQR. Seleziona ForceQR per i simboli QR standard, Auto per MicroQR.

### setQrErrorLevel() {#setqrerrorlevel}

> **Deprecated.** See method description for replacement.

Livello di correzione errori Reed-Solomon per il codice QR. Dal più basso al più alto: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. vedi QRErrorLevel.

### setQrVersion() {#setqrversion}

> **Deprecated.** See method description for replacement.

Versione del codice QR. Dalla Versione1 alla Versione40 per il codice QR e da M1 a M4 per MicroQr. Il valore predefinito è QRVersion.AUTO.

### setRectMicroQrVersion() {#setrectmicroqrversion}

Versione del codice RectMicroQR. Dalla versione R7x59 alla versione R17x139. Il valore predefinito è RectMicroQRVersion.Auto.

### setStructuredAppend() {#setstructuredappend}

Parametri QR structured append.

### setVersion() {#setversion}

Versione del codice QR. Dalla Versione1 alla Versione40. Il valore predefinito è QRVersion.Auto.

### toString() {#tostring}

Restituisce una rappresentazione stringa leggibile dall'uomo di questo QrParameters.

**Returns:** A string that represents this QrParameters.
