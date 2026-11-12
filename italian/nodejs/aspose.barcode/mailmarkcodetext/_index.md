---
title: "MailmarkCodetext"
linktitle: "MailmarkCodetext"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Classe per la codifica e decodifica del testo incorporato nel codice Royal Mailmark a 4 stati."
type: docs
weight: 580
url: /it/nodejs/aspose.barcode/mailmarkcodetext/
---

## MailmarkCodetext class

Classe per la codifica e decodifica del testo incorporato nel codice Royal Mailmark a 4 stati.

```js
new MailmarkCodetext()
```

Inizializza una nuova istanza della classe `MailmarkCodetext`.

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Ottiene il tipo di codice a barre. |
| [getClass_()](#getclass-) | "0" - Null o Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (per pote |
| [getConstructedCodetext()](#getconstructedcodetext) | Costruisci il codetext dai dati Mailmark. |
| [getDestinationPostCodePlusDPS()](#getdestinationpostcodeplusdps) | Il PC e il DP devono rispettare un formato PAF. Stringa di nove caratteri che indica l'internazionale "XY11 " (nota i 5 spazi finali s |
| [getFormat()](#getformat) | "0" – Null o Test "1" – Lettera "2" – Lettera Grande |
| [getItemID()](#getitemid) | Il valore massimo è 99999999. |
| [getSupplychainID()](#getsupplychainid) | I valori massimi sono 99 per Barcode C e 999999 per Barcode L. |
| [getVersionID()](#getversionid) | Attualmente "1" – Per il codice a barre Mailmark (0 e da 2 a 9 e da A a Z riservati per uso futuro) |
| [initFromString(constructedCodetext)](#initfromstring) | Inizializza i dati Mailmark dal codetext costruito. |
| [setClass_()](#setclass-) | "0" - Null o Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (per pote |
| [setDestinationPostCodePlusDPS()](#setdestinationpostcodeplusdps) | Il PC e il DP devono rispettare un formato PAF. Stringa di nove caratteri che indica l'internazionale "XY11 " (nota i 5 spazi finali s |
| [setFormat()](#setformat) | "0" – Null o Test "1" – LetterN "2" – Lettera Grande |
| [setItemID()](#setitemid) | Il valore massimo è 99999999. |
| [setSupplychainID()](#setsupplychainid) | I valori massimi sono 99 per Barcode C e 999999 per Barcode L. |
| [setVersionID()](#setversionid) | Attualmente "1" – Per il codice a barre Mailmark (0 e da 2 a 9 e da A a Z riservati per uso futuro) |

### getBarcodeType() {#getbarcodetype}

Ottiene il tipo di codice a barre.

**Returns:** Barcode type.

### getClass_() {#getclass-}

"0" - Null o Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (per uso futuro potenziale) "5" - Deferred (Retail) "6" - Air (Retail) (per uso futuro potenziale) "7" - Surface (Retail) (per uso futuro potenziale) "8" - Premium (Network Access) "9" - Standard (Network Access)

### getConstructedCodetext() {#getconstructedcodetext}

Costruisci il codetext dai dati Mailmark.

**Returns:** Constructed codetext

### getDestinationPostCodePlusDPS() {#getdestinationpostcodeplusdps}

Il PC e il DP devono rispettare un formato PAF. Stringa di nove caratteri che indica l'internazionale "XY11 " (nota i 5 spazi finali) o un modello di caratteri che indica un codice di smistamento domestico. Un codice di smistamento domestico è composto da un codice postale esterno, un codice postale interno e un suffisso del punto di consegna.

### getFormat() {#getformat}

"0" – Null o Test "1" – Lettera "2" – Lettera Grande

### getItemID() {#getitemid}

Il valore massimo è 99999999.

### getSupplychainID() {#getsupplychainid}

I valori massimi sono 99 per Barcode C e 999999 per Barcode L.

### getVersionID() {#getversionid}

Attualmente "1" – Per il codice a barre Mailmark (0 e da 2 a 9 e da A a Z riservati per uso futuro)

### initFromString(constructedCodetext) {#initfromstring}

Inizializza i dati Mailmark dal codetext costruito.

| Parametro | Descrizione |
| --- | --- |
| constructedCodetext | Codetext costruito. |

### setClass_() {#setclass-}

"0" - Null o Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (per uso futuro potenziale) "5" - Deferred (Retail) "6" - Air (Retail) (per uso futuro potenziale) "7" - Surface (Retail) (per uso futuro potenziale) "8" - Premium (Network Access) "9" - Standard (Network Access)

### setDestinationPostCodePlusDPS() {#setdestinationpostcodeplusdps}

Il PC e il DP devono rispettare un formato PAF. Stringa di nove caratteri che indica l'internazionale "XY11 " (nota i 5 spazi finali) o un modello di caratteri che indica un codice di smistamento domestico. Un codice di smistamento domestico è composto da un codice postale esterno, un codice postale interno e un suffisso del punto di consegna.

### setFormat() {#setformat}

"0" – Null o Test "1" – LetterN "2" – Lettera Grande

### setItemID() {#setitemid}

Il valore massimo è 99999999.

### setSupplychainID() {#setsupplychainid}

I valori massimi sono 99 per Barcode C e 999999 per Barcode L.

### setVersionID() {#setversionid}

Attualmente "1" – Per il codice a barre Mailmark (0 e da 2 a 9 e da A a Z riservati per uso futuro)
