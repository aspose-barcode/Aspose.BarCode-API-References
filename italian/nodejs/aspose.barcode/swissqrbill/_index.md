---
title: "SwissQRBill"
linktitle: "SwissQRBill"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Dati della fattura SwissQR"
type: docs
weight: 920
url: /it/nodejs/aspose.barcode/swissqrbill/
---

## SwissQRBill class

Dati della fattura SwissQR

```js
new SwissQRBill()
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [createAndSetCreditorReference(rawReference)](#createandsetcreditorreference) | Crea e imposta un riferimento creditore ISO11649 da una stringa grezza aggiungendo il prefisso "RF" e il modulo 97 che |
| [equals(obj)](#equals) | Determina se l'oggetto specificato è uguale all'oggetto corrente. |
| [getAccount()](#getaccount) | Restituisce il numero di conto del creditore. I numeri di conto devono essere IBAN validi di una banca della Svizzera o del Liechtenstein. Spazio |
| [getAlternativeSchemes()](#getalternativeschemes) | Restituisce o imposta gli schemi di pagamento alternativi. È consentito un massimo di due schemi con parametri. |
| [getAmount()](#getamount) | Restituisce l'importo del pagamento. I valori validi sono compresi tra 0,01 e 999.999.999,99. |
| [getBillInformation()](#getbillinformation) | Restituisce le informazioni aggiuntive strutturate della fattura. |
| [getCreditor()](#getcreditor) | Restituisce l'indirizzo del creditore. |
| [getCurrency()](#getcurrency) | Restituisce la valuta del pagamento. I valori validi sono "CHF" e "EUR". |
| [getDebtor()](#getdebtor) | Ottiene l'indirizzo del debitore. Il debitore è opzionale. Se viene omesso, sia impostare questo campo a null che impostare un indirizzo |
| [getReference()](#getreference) | Ottiene il riferimento di pagamento del creditore. Il riferimento è obbligatorio per gli IBAN SwissQR, cioè IBAN nel range CHxx30000xxxxx |
| [getUnstructuredMessage()](#getunstructuredmessage) | Ottiene il messaggio non strutturato aggiuntivo. |
| [getVersion()](#getversion) | Ottiene la versione dello standard di fatturazione SwissQR. |
| [hashCode()](#hashcode) | Ottiene il codice hash per questa istanza. |
| [setAccount(value:)](#setaccount) | Imposta il numero di conto del creditore. I numeri di conto devono essere IBAN validi di una banca della Svizzera o del Liechtenstein. Spazio |
| [setAlternativeSchemes(value:)](#setalternativeschemes) | Ottiene o imposta gli schemi di pagamento alternativi. È consentito un massimo di due schemi con parametri. |
| [setAmount(value)](#setamount) | Imposta l'importo del pagamento. I valori validi sono compresi tra 0,01 e 999.999.999,99. |
| [setBillInformation(value:)](#setbillinformation) | Imposta le informazioni di fattura strutturate aggiuntive. |
| [setCreditor(value:)](#setcreditor) | Imposta l'indirizzo del creditore. |
| [setCurrency(value)](#setcurrency) | Imposta la valuta del pagamento. |
| [setDebtor(value:)](#setdebtor) | Imposta l'indirizzo del debitore. Il debitore è opzionale. Se viene omesso, sia impostare questo campo a null che impostare un indirizzo |
| [setReference(value)](#setreference) | Imposta il riferimento di pagamento del creditore. Il riferimento è obbligatorio per gli IBAN SwissQR, cioè IBAN nel range CHxx30000xxxxx |
| [setUnstructuredMessage(value:)](#setunstructuredmessage) | Imposta il messaggio non strutturato aggiuntivo. |
| [setVersion(value)](#setversion) | Imposta la versione dello standard di fatturazione SwissQR. |

### createAndSetCreditorReference(rawReference) {#createandsetcreditorreference}

Crea e imposta un riferimento creditore ISO11649 da una stringa grezza aggiungendo il prefisso "RF" e il checksum modulo 97. Gli spazi bianchi vengono rimossi dal riferimento

| Parametro | Descrizione |
| --- | --- |
| rawReference | Il riferimento grezzo. |

**Throws:** ArgumentException rawReference contains invalid characters.

### equals(obj) {#equals}

Determina se l'oggetto specificato è uguale all'oggetto corrente.

| Parametro | Descrizione |
| --- | --- |
| obj | L'oggetto da confrontare con l'oggetto corrente. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAccount() {#getaccount}

Ottiene il numero di conto del creditore. I numeri di conto devono essere IBAN validi di una banca della Svizzera o del Liechtenstein. Gli spazi sono consentiti nel numero di conto.

**Returns:** The creditor account number.

### getAlternativeSchemes() {#getalternativeschemes}

Restituisce o imposta gli schemi di pagamento alternativi. È consentito un massimo di due schemi con parametri.

**Returns:** The alternative payment schemes.

### getAmount() {#getamount}

Restituisce l'importo del pagamento. I valori validi sono compresi tra 0,01 e 999.999.999,99.

**Returns:** The payment amount.

### getBillInformation() {#getbillinformation}

Restituisce le informazioni aggiuntive strutturate della fattura.

**Returns:** The structured bill information.

### getCreditor() {#getcreditor}

Restituisce l'indirizzo del creditore.

**Returns:** The creditor address.

### getCurrency() {#getcurrency}

Restituisce la valuta del pagamento. I valori validi sono "CHF" e "EUR".

**Returns:** The payment currency.

### getDebtor() {#getdebtor}

Ottiene l'indirizzo del debitore. Il debitore è opzionale. Se viene omesso, sia impostare questo campo a null che impostare un indirizzo con tutti i valori null o vuoti è accettabile.

**Returns:** The debtor address.

### getReference() {#getreference}

Ottiene il riferimento di pagamento del creditore. Il riferimento è obbligatorio per gli IBAN SwissQR, cioè IBAN nel range CHxx30000xxxxxx fino a CHxx31999xxxxx. Se specificato, il riferimento deve essere o un riferimento SwissQR valido (corrispondente al modulo di riferimento ISR) o un riferimento creditore valido secondo ISO 11649 ("RFxxxx"). Entrambi possono contenere spazi per la formattazione.

**Returns:** The creditor payment reference.

### getUnstructuredMessage() {#getunstructuredmessage}

Ottiene il messaggio non strutturato aggiuntivo.

**Returns:** The unstructured message.

### getVersion() {#getversion}

Ottiene la versione dello standard di fatturazione SwissQR.

**Returns:** The SwissQR bill standard version.

### hashCode() {#hashcode}

Ottiene il codice hash per questa istanza.

**Returns:** A hash code for the current object.

### setAccount(value:) {#setaccount}

Imposta il numero di conto del creditore. I numeri di conto devono essere IBAN validi di una banca della Svizzera o del Liechtenstein. Gli spazi sono consentiti nel numero di conto.

| Parametro | Descrizione |
| --- | --- |
| valore: | Il numero di conto del creditore. |

### setAlternativeSchemes(value:) {#setalternativeschemes}

Ottiene o imposta gli schemi di pagamento alternativi. È consentito un massimo di due schemi con parametri.

| Parametro | Descrizione |
| --- | --- |
| valore: | Gli schemi di pagamento alternativi. |

### setAmount(value) {#setamount}

Imposta l'importo del pagamento. I valori validi sono compresi tra 0,01 e 999.999.999,99.

| Parametro | Descrizione |
| --- | --- |
| valore | L'importo del pagamento. |

### setBillInformation(value:) {#setbillinformation}

Imposta le informazioni di fattura strutturate aggiuntive.

| Parametro | Descrizione |
| --- | --- |
| valore: | Le informazioni di fattura strutturate. |

### setCreditor(value:) {#setcreditor}

Imposta l'indirizzo del creditore.

| Parametro | Descrizione |
| --- | --- |
| valore: | L'indirizzo del creditore. |

### setCurrency(value) {#setcurrency}

Imposta la valuta del pagamento.

| Parametro | Descrizione |
| --- | --- |
| valore | I valori validi sono "CHF" e "EUR". |

### setDebtor(value:) {#setdebtor}

Imposta l'indirizzo del debitore. Il debitore è opzionale. Se viene omesso, sia impostare questo campo a null sia impostare un indirizzo con tutti i valori null o vuoti è accettabile.

| Parametro | Descrizione |
| --- | --- |
| valore: | L'indirizzo del debitore. |

### setReference(value) {#setreference}

Imposta il riferimento di pagamento del creditore. Il riferimento è obbligatorio per gli IBAN SwissQR, cioè gli IBAN nell'intervallo CHxx30000xxxxxx fino a CHxx31999xxxxx. Se specificato, il riferimento deve essere o un riferimento SwissQR valido (corrispondente al modulo di riferimento ISR) o un riferimento del creditore valido secondo ISO 11649 ("RFxxxx"). Entrambi possono contenere spazi per la formattazione.

| Parametro | Descrizione |
| --- | --- |
| valore | Il riferimento di pagamento del creditore. |

### setUnstructuredMessage(value:) {#setunstructuredmessage}

Imposta il messaggio non strutturato aggiuntivo.

| Parametro | Descrizione |
| --- | --- |
| valore: | Il messaggio non strutturato. |

### setVersion(value) {#setversion}

Imposta la versione dello standard di fatturazione SwissQR.

| Parametro | Descrizione |
| --- | --- |
| valore | La versione standard della fattura SwissQR. |
