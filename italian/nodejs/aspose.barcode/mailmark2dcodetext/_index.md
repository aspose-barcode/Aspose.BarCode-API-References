---
title: "Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Classe per la codifica e decodifica del testo incorporato nel codice Royal Mail 2D Mailmark."
type: docs
weight: 570
url: /it/nodejs/aspose.barcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Classe per la codifica e decodifica del testo incorporato nel codice Royal Mail 2D Mailmark.

```js
new Mailmark2DCodetext()
```

Crea un'istanza predefinita della classe Mailmark2DCodetext.

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Ottiene il tipo di codice a barre. |
| [getClass_()](#getclass-) | Identifica la classe dell'elemento. Valori validi: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffere |
| [getConstructedCodetext()](#getconstructedcodetext) | Costruisci il codetext dai dati Mailmark. |
| [getCustomerContent()](#getcustomercontent) | Spazio opzionale per l'uso del cliente. Lunghezza massima per Tipo: Tipo 7: 6 caratteri Tipo 9: 45 caratteri Tipo 29: 25 caratteri |
| [getCustomerContentEncodeMode()](#getcustomercontentencodemode) | Modalità di codifica del barcode Datamatrix. Valore predefinito: DataMatrixEncodeMode.C40. |
| [getDataMatrixType()](#getdatamatrixtype) | Il tipo 2D Mailmark definisce la dimensione del barcode Data Matrix. |
| [getDestinationPostCodeAndDPS()](#getdestinationpostcodeanddps) | Contiene il codice postale dell'indirizzo di consegna con DPS. Se interno, il codice postale/DP contiene il seguente numero di caratteri |
| [getInformationTypeID()](#getinformationtypeid) | Identifica il payload del barcode Royal Mail Mailmark per ogni tipo di prodotto. Valori validi: '0' - Domestic Sorted & Unsorted |
| [getItemID()](#getitemid) | Identifica l'elemento unico all'interno del Supply Chain ID. Ogni codice a barre Mailmark deve contenere un ID in modo che possa essere un |
| [getReturnToSenderPostCode()](#getreturntosenderpostcode) | Contiene il codice postale Return to Sender ma senza DPS. Il PC (senza DPS) deve conformarsi a un formato PAF®. |
| [getRTSFlag()](#getrtsflag) | Flag che indica quale livello di servizio Return to Sender è richiesto. |
| [getSupplyChainID()](#getsupplychainid) | Identifica il gruppo unico di clienti coinvolti nella spedizione. Valore massimo: 9999999. |
| [getUPUCountryID()](#getupucountryid) | Identifica l'ID paese UPU. Lunghezza massima: 4 caratteri. |
| [getVersionID()](#getversionid) | Identifica la versione del codice a barre in relazione a ciascun Information Type ID. Valori validi: Attualmente '1'. '0' & '2' a '9' an |
| [initFromString(constructedCodetext)](#initfromstring) | Inizializza i dati Mailmark dal codetext costruito. |
| [setClass_(value)](#setclass-) | Identifica la classe dell'elemento. Valori validi: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffere |
| [setCustomerContent(value)](#setcustomercontent) | Spazio opzionale per l'uso del cliente. Lunghezza massima per Tipo: Tipo 7: 6 caratteri Tipo 9: 45 caratteri Tipo 29: 25 caratteri |
| [setCustomerContentEncodeMode(value)](#setcustomercontentencodemode) | Modalità di codifica del barcode Datamatrix. Valore predefinito: DataMatrixEncodeMode.C40. |
| [setDataMatrixType(value)](#setdatamatrixtype) | Il tipo 2D Mailmark definisce la dimensione del barcode Data Matrix. |
| [setDestinationPostCodeAndDPS(value)](#setdestinationpostcodeanddps) | Contiene il codice postale dell'indirizzo di consegna con DPS. Se interno, il codice postale/DP contiene il seguente numero di caratteri |
| [setInformationTypeID(value)](#setinformationtypeid) | Identifica il payload del barcode Royal Mail Mailmark per ogni tipo di prodotto. Valori validi: '0' - Domestic Sorted & Unsorted |
| [setItemID(value)](#setitemid) | Identifica l'elemento unico all'interno del Supply Chain ID. Ogni codice a barre Mailmark deve contenere un ID in modo che possa essere un |
| [setReturnToSenderPostCode(value)](#setreturntosenderpostcode) | Contiene il codice postale Return to Sender ma senza DPS. Il PC (senza DPS) deve conformarsi a un formato PAF®. |
| [setRTSFlag()](#setrtsflag) | Flag che indica quale livello di servizio Return to Sender è richiesto. |
| [setSupplyChainID(value)](#setsupplychainid) | Identifica il gruppo unico di clienti coinvolti nella spedizione. Valore massimo: 9999999. |
| [setUPUCountryID(value)](#setupucountryid) | Identifica l'ID paese UPU. Lunghezza massima: 4 caratteri. |
| [setVersionID(value)](#setversionid) | Identifica la versione del codice a barre in relazione a ciascun Information Type ID. Valori validi: Attualmente '1'. '0' & '2' a '9' an |

### getBarcodeType() {#getbarcodetype}

Ottiene il tipo di codice a barre.

**Returns:** Barcode type.

### getClass_() {#getclass-}

Identifica la classe dell'elemento. Valori validi: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffered (Retail) '8' - Premium (Network Access) '9' - Standard (Network Access)

**Returns:** class of the item

### getConstructedCodetext() {#getconstructedcodetext}

Costruisci il codetext dai dati Mailmark.

**Returns:** Constructed codetext

### getCustomerContent() {#getcustomercontent}

Spazio opzionale per uso del cliente. Lunghezza massima per Tipo: Tipo 7: 6 caratteri Tipo 9: 45 caratteri Tipo 29: 25 caratteri.

**Returns:** Customer content

### getCustomerContentEncodeMode() {#getcustomercontentencodemode}

Modalità di codifica del barcode Datamatrix. Valore predefinito: DataMatrixEncodeMode.C40.

**Returns:** Encode mode of Datamatrix barcode.

### getDataMatrixType() {#getdatamatrixtype}

Il tipo 2D Mailmark definisce la dimensione del barcode Data Matrix.

**Returns:** Size of Data Matrix barcode

### getDestinationPostCodeAndDPS() {#getdestinationpostcodeanddps}

Contiene il codice postale dell'indirizzo di consegna con DPS. Se interno, il codice postale/DP contiene il seguente numero di caratteri. Area (1 o 2 caratteri) Distretto (1 o 2 caratteri) Settore (1 carattere) Unità (2 caratteri) DPS (2 caratteri). Il codice postale e il DPS devono conformarsi a un formato PAF® valido.

**Returns:** the Postcode of the Delivery Address with DPS

### getInformationTypeID() {#getinformationtypeid}

Identifica il payload del codice a barre Royal Mail Mailmark per ciascun tipo di prodotto. Valori validi: '0' - Domestic Sorted & Unsorted 'A' - Online Postage 'B' - Franking 'C' - Consolidation

**Returns:** Information type ID

### getItemID() {#getitemid}

Identifica l'elemento unico all'interno del Supply Chain ID. Ogni codice a barre Mailmark deve contenere un ID in modo che possa essere identificato univocamente per almeno 90 giorni. Valore massimo: 99999999.

**Returns:** item within the Supply Chain ID

### getReturnToSenderPostCode() {#getreturntosenderpostcode}

Contiene il codice postale Return to Sender ma senza DPS. Il PC (senza DPS) deve conformarsi a un formato PAF®.

**Returns:** Return to Sender Post Code but no DPS

### getRTSFlag() {#getrtsflag}

Flag che indica quale livello di servizio Return to Sender è richiesto.

**Returns:** RTS Flag

### getSupplyChainID() {#getsupplychainid}

Identifica il gruppo unico di clienti coinvolti nella spedizione. Valore massimo: 9999999.

**Returns:** Supply chain ID

### getUPUCountryID() {#getupucountryid}

Identifica l'ID paese UPU. Lunghezza massima: 4 caratteri.

**Returns:** Country ID

### getVersionID() {#getversionid}

Identifica la versione del codice a barre in relazione a ciascun Information Type ID. Valori validi: Attualmente '1'. '0' e '2' a '9' e 'A' a 'Z' riservati per potenziali usi futuri.

**Returns:** Version ID

### initFromString(constructedCodetext) {#initfromstring}

Inizializza i dati Mailmark dal codetext costruito.

| Parametro | Descrizione |
| --- | --- |
| constructedCodetext | Codetext costruito. |

### setClass_(value) {#setclass-}

Identifica la classe dell'elemento. Valori validi: '1' - 1C (Retail) '2' - 2C (Retail) '3' - Economy (Retail) '5' - Deffered (Retail) '8' - Premium (Network Access) '9' - Standard (Network Access)

| Parametro | Descrizione |
| --- | --- |
| valore | classe dell'elemento |

### setCustomerContent(value) {#setcustomercontent}

Spazio opzionale per uso del cliente. Lunghezza massima per Tipo: Tipo 7: 6 caratteri Tipo 9: 45 caratteri Tipo 29: 25 caratteri.

| Parametro | Descrizione |
| --- | --- |
| valore | Contenuto del cliente |

### setCustomerContentEncodeMode(value) {#setcustomercontentencodemode}

Modalità di codifica del barcode Datamatrix. Valore predefinito: DataMatrixEncodeMode.C40.

| Parametro | Descrizione |
| --- | --- |
| valore | Modalità di codifica del codice a barre Datamatrix. |

### setDataMatrixType(value) {#setdatamatrixtype}

Il tipo 2D Mailmark definisce la dimensione del barcode Data Matrix.

| Parametro | Descrizione |
| --- | --- |
| valore | Dimensione del codice a barre Data Matrix |

### setDestinationPostCodeAndDPS(value) {#setdestinationpostcodeanddps}

Contiene il codice postale dell'indirizzo di consegna con DPS. Se interno, il codice postale/DP contiene il seguente numero di caratteri. Area (1 o 2 caratteri) Distretto (1 o 2 caratteri) Settore (1 carattere) Unità (2 caratteri) DPS (2 caratteri). Il codice postale e il DPS devono conformarsi a un formato PAF® valido.

| Parametro | Descrizione |
| --- | --- |
| valore | il codice postale dell'indirizzo di consegna con DPS |

### setInformationTypeID(value) {#setinformationtypeid}

Identifica il payload del codice a barre Royal Mail Mailmark per ciascun tipo di prodotto. Valori validi: '0' - Domestic Sorted & Unsorted 'A' - Online Postage 'B' - Franking 'C' - Consolidation

| Parametro | Descrizione |
| --- | --- |
| valore | ID tipo di informazione |

### setItemID(value) {#setitemid}

Identifica l'elemento unico all'interno del Supply Chain ID. Ogni codice a barre Mailmark deve contenere un ID in modo che possa essere identificato univocamente per almeno 90 giorni. Valore massimo: 99999999.

| Parametro | Descrizione |
| --- | --- |
| valore | elemento all'interno del Supply Chain ID |

### setReturnToSenderPostCode(value) {#setreturntosenderpostcode}

Contiene il codice postale Return to Sender ma senza DPS. Il PC (senza DPS) deve conformarsi a un formato PAF®.

| Parametro | Descrizione |
| --- | --- |
| valore | Codice postale Return to Sender ma senza DPS |

### setRTSFlag() {#setrtsflag}

Flag che indica quale livello di servizio Return to Sender è richiesto.

**Returns:** RTS Flag

### setSupplyChainID(value) {#setsupplychainid}

Identifica il gruppo unico di clienti coinvolti nella spedizione. Valore massimo: 9999999.

| Parametro | Descrizione |
| --- | --- |
| valore | ID della catena di fornitura |

### setUPUCountryID(value) {#setupucountryid}

Identifica l'ID paese UPU. Lunghezza massima: 4 caratteri.

| Parametro | Descrizione |
| --- | --- |
| valore | ID paese |

### setVersionID(value) {#setversionid}

Identifica la versione del codice a barre in relazione a ciascun Information Type ID. Valori validi: Attualmente '1'. '0' e '2' a '9' e 'A' a 'Z' riservati per potenziali usi futuri.

| Parametro | Descrizione |
| --- | --- |
| valore | ID versione |
