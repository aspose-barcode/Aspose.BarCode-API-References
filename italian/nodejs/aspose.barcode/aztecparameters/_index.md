---
title: "AztecParameters"
linktitle: "AztecParameters"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Parametri Aztec."
type: docs
weight: 70
url: /it/nodejs/aspose.barcode/aztecparameters/
---

## AztecParameters class

Parametri Aztec.

```js
new AztecParameters()
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Rapporto Altezza/Larghezza del modulo BarCode 2D. |
| [getAztecEncodeMode()](#getaztecencodemode) ~~(deprecated)~~ | Ottiene una modalità di codifica Aztec. Valore predefinito: Auto. |
| [getAztecErrorLevel()](#getaztecerrorlevel) ~~(deprecated)~~ | Livello di correzione errori dei tipi di codice a barre Aztec. Il valore dovrebbe essere tra 5 e 95. |
| [getAztecSymbolMode()](#getaztecsymbolmode) ~~(deprecated)~~ | Ottiene una modalità Simbolo Aztec. Valore predefinito: AztecSymbolMode.Auto. |
| [getECIEncoding()](#geteciencoding) | Ottiene la codifica ECI. Utilizzata quando AztecEncodeMode è Auto. Valore predefinito: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Ottiene una modalità di codifica Aztec. Valore predefinito: Auto. |
| [getErrorLevel()](#geterrorlevel) | Livello di correzione errori dei tipi di codice a barre Aztec. Il valore dovrebbe essere tra 5 e 95. |
| [getLayersCount()](#getlayerscount) | Ottiene il conteggio dei livelli del simbolo Aztec. Il conteggio dei livelli dovrebbe essere nell'intervallo da 1 a 3 per la modalità Compact e nell'intervallo da 1 a 3 |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | ID del codice a barre per la modalità Structured Append del codice a barre Aztec. L'ID del codice a barre dovrebbe essere nell'intervallo da 1 al numero di codici a barre. Predefinito |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Il conteggio dei codici a barre per la modalità Structured Append del codice a barre Aztec. Il conteggio dei codici a barre deve essere compreso tra 1 e 26. Valore predefinito |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | ID file per la modalità Structured Append del codice a barre Aztec (campo opzionale). L'ID file non deve contenere spazi. Valore predefinito: |
| [getSymbolMode()](#getsymbolmode) | Ottiene una modalità Simbolo Aztec. Valore predefinito: AztecSymbolMode.Auto. |
| [isReaderInitialization()](#isreaderinitialization) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [setAspectRatio()](#setaspectratio) | Rapporto Altezza/Larghezza del modulo BarCode 2D. |
| [setAztecEncodeMode()](#setaztecencodemode) ~~(deprecated)~~ | Imposta una modalità di codifica Aztec. Valore predefinito: Auto. |
| [setAztecErrorLevel()](#setaztecerrorlevel) ~~(deprecated)~~ | Livello di correzione errori dei tipi di codice a barre Aztec. Il valore dovrebbe essere tra 5 e 95. |
| [setAztecSymbolMode()](#setaztecsymbolmode) ~~(deprecated)~~ | Imposta una modalità di simbolo Aztec. Valore predefinito: AztecSymbolMode.Auto. |
| [setECIEncoding()](#seteciencoding) | Imposta la codifica ECI. Utilizzata quando AztecEncodeMode è Auto. Valore predefinito: ISO-8859-1 |
| [setEncodeMode(value)](#setencodemode) | Imposta una modalità di codifica Aztec. Valore predefinito: Auto. |
| [setErrorLevel()](#seterrorlevel) | Livello di correzione errori dei tipi di codice a barre Aztec. Il valore dovrebbe essere tra 5 e 95. |
| [setLayersCount()](#setlayerscount) | Imposta il conteggio dei livelli del simbolo Aztec. Il conteggio dei livelli deve essere compreso tra 1 e 3 per la modalità Compact e tra 1 e 3 |
| [setReaderInitialization()](#setreaderinitialization) | Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore. |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | ID del codice a barre per la modalità Structured Append del codice a barre Aztec. L'ID del codice a barre dovrebbe essere nell'intervallo da 1 al numero di codici a barre. Predefinito |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | Il conteggio dei codici a barre per la modalità Structured Append del codice a barre Aztec. Il conteggio dei codici a barre deve essere compreso tra 1 e 26. Valore predefinito |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | ID file per la modalità Structured Append del codice a barre Aztec (campo opzionale). L'ID file non deve contenere spazi. Valore predefinito: |
| [setSymbolMode(value)](#setsymbolmode) | Imposta una modalità di simbolo Aztec. Valore predefinito: AztecSymbolMode.Auto. |
| [toString()](#tostring) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo `AztecParameters`. |

### getAspectRatio() {#getaspectratio}

Rapporto Altezza/Larghezza del modulo BarCode 2D.

### getAztecEncodeMode() {#getaztecencodemode}

> **Deprecated.** See method description for replacement.

Ottiene una modalità di codifica Aztec. Valore predefinito: Auto.

### getAztecErrorLevel() {#getaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Livello di correzione errori dei tipi di codice a barre Aztec. Il valore dovrebbe essere tra 5 e 95.

### getAztecSymbolMode() {#getaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Ottiene una modalità Simbolo Aztec. Valore predefinito: AztecSymbolMode.Auto.

### getECIEncoding() {#geteciencoding}

Ottiene la codifica ECI. Utilizzata quando AztecEncodeMode è Auto. Valore predefinito: ISO-8859-1

### getEncodeMode() {#getencodemode}

Ottiene una modalità di codifica Aztec. Valore predefinito: Auto.

**Returns:** a Aztec encode mode.

### getErrorLevel() {#geterrorlevel}

Livello di correzione errori dei tipi di codice a barre Aztec. Il valore dovrebbe essere tra 5 e 95.

### getLayersCount() {#getlayerscount}

Ottiene il conteggio dei livelli del simbolo Aztec. Il conteggio dei livelli deve essere compreso tra 1 e 3 per la modalità Compact e tra 1 e 32 per la modalità Full Range. Valore predefinito: 0 (auto).

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

ID del codice a barre per la modalità Structured Append del codice a barre Aztec. L'ID del codice a barre deve essere compreso tra 1 e il conteggio dei codici a barre. Valore predefinito: 0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Conteggio dei codici a barre per la modalità Structured Append del codice a barre Aztec. Il conteggio dei codici a barre deve essere compreso tra 1 e 26. Valore predefinito: 0

### getStructuredAppendFileId() {#getstructuredappendfileid}

ID file per la modalità Structured Append del codice a barre Aztec (campo opzionale). L'ID file non deve contenere spazi. Valore predefinito: stringa vuota

### getSymbolMode() {#getsymbolmode}

Ottiene una modalità Simbolo Aztec. Valore predefinito: AztecSymbolMode.Auto.

**Returns:** a Aztec Symbol mode.

### isReaderInitialization() {#isreaderinitialization}

Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore.

### setAspectRatio() {#setaspectratio}

Rapporto Altezza/Larghezza del modulo BarCode 2D.

### setAztecEncodeMode() {#setaztecencodemode}

> **Deprecated.** See method description for replacement.

Imposta una modalità di codifica Aztec. Valore predefinito: Auto.

### setAztecErrorLevel() {#setaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Livello di correzione errori dei tipi di codice a barre Aztec. Il valore dovrebbe essere tra 5 e 95.

### setAztecSymbolMode() {#setaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Imposta una modalità di simbolo Aztec. Valore predefinito: AztecSymbolMode.Auto.

### setECIEncoding() {#seteciencoding}

Imposta la codifica ECI. Utilizzata quando AztecEncodeMode è Auto. Valore predefinito: ISO-8859-1

### setEncodeMode(value) {#setencodemode}

Imposta una modalità di codifica Aztec. Valore predefinito: Auto.

| Parametro | Descrizione |
| --- | --- |
| valore | una modalità di codifica Aztec. |

### setErrorLevel() {#seterrorlevel}

Livello di correzione errori dei tipi di codice a barre Aztec. Il valore dovrebbe essere tra 5 e 95.

### setLayersCount() {#setlayerscount}

Imposta il conteggio dei livelli del simbolo Aztec. Il conteggio dei livelli deve essere compreso tra 1 e 3 per la modalità Compact e tra 1 e 32 per la modalità Full Range. Valore predefinito: 0 (auto).

### setReaderInitialization() {#setreaderinitialization}

Utilizzato per istruire il lettore a interpretare i dati contenuti nel simbolo come programmazione per l'inizializzazione del lettore.

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

ID del codice a barre per la modalità Structured Append del codice a barre Aztec. L'ID del codice a barre deve essere compreso tra 1 e il conteggio dei codici a barre. Valore predefinito: 0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

Conteggio dei codici a barre per la modalità Structured Append del codice a barre Aztec. Il conteggio dei codici a barre deve essere compreso tra 1 e 26. Valore predefinito: 0

### setStructuredAppendFileId() {#setstructuredappendfileid}

ID file per la modalità Structured Append del codice a barre Aztec (campo opzionale). L'ID file non deve contenere spazi. Valore predefinito: stringa vuota

### setSymbolMode(value) {#setsymbolmode}

Imposta una modalità di simbolo Aztec. Valore predefinito: AztecSymbolMode.Auto.

| Parametro | Descrizione |
| --- | --- |
| valore | una modalità di simbolo Aztec. |

### toString() {#tostring}

Restituisce una rappresentazione stringa leggibile dall'uomo di questo `AztecParameters`.

**Returns:** A string that represents this `AztecParameters`.
