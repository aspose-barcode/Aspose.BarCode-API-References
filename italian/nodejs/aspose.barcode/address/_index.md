---
title: "Indirizzo"
linktitle: "Indirizzo"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Indirizzo del creditore o del debitore."
type: docs
weight: 10
url: /it/nodejs/aspose.barcode/address/
---

## Address class

Indirizzo del creditore o del debitore. È possibile impostare la via, il numero civico, il codice postale e la città (tipo indirizzo strutturato) oppure la linea di indirizzo 1 e 2 (tipo elementi di indirizzo combinati). Il tipo viene impostato automaticamente non appena uno di questi campi è impostato. Prima di impostare i campi, il tipo di indirizzo è indeterminato. Se i campi di entrambi i tipi sono impostati, il tipo di indirizzo diventa conflittuale. Il nome e il codice paese devono sempre essere impostati a meno che tutti i campi siano vuoti.

```js
new Address()
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [clear()](#clear) | Cancella tutti i campi e imposta il tipo su AddressType.UNDETERMINED. |
| [equals(obj)](#equals) | Determina se l'oggetto specificato è uguale all'oggetto corrente. |
| [getAddressLine1()](#getaddressline1) | Restituisce la linea di indirizzo 1. La linea di indirizzo 1 contiene il nome della via, il numero civico o la casella postale. Impostare questo campo imposta l'indir |
| [getAddressLine2()](#getaddressline2) | Restituisce la linea di indirizzo 2. La linea di indirizzo 2 contiene il codice postale e la città. Impostare questo campo imposta il tipo di indirizzo su Addre |
| [getCountryCode()](#getcountrycode) | Restituisce il codice ISO del paese a due lettere. Il codice paese è obbligatorio a meno che l'intero indirizzo contenga valori null o vuoti |
| [getHouseNo()](#gethouseno) | Restituisce il numero civico. Impostare questo campo imposta il tipo di indirizzo su AddressType.STRUCTURED a meno che sia già AddressTyp |
| [getName()](#getname) | Restituisce il nome, sia il nome e cognome di una persona fisica sia la ragione sociale di una persona giuridica. |
| [getPostalCode()](#getpostalcode) | Restituisce il codice postale. Impostare questo campo imposta il tipo di indirizzo su AddressType.STRUCTURED a meno che sia già AddressType |
| [getStreet()](#getstreet) | Restituisce la via. La via deve essere specificata senza numero civico. Impostare questo campo imposta il tipo di indirizzo su AddressT |
| [getTown()](#gettown) | Restituisce la città o il comune. Impostare questo campo imposta il tipo di indirizzo su AddressType.STRUCTURED a meno che sia già AddressTyp |
| [getType()](#gettype) | Restituisce il tipo di indirizzo. Il tipo di indirizzo è impostato automaticamente impostando la via / numero civico o la linea di indirizzo 1 a |
| [hashCode()](#hashcode) | Ottiene il codice hash per questa istanza. |
| [setAddressLine1(value:)](#setaddressline1) | Imposta la linea di indirizzo 1. La linea di indirizzo 1 contiene il nome della via, il numero civico o la casella postale. Impostare questo campo imposta l'indir |
| [setAddressLine2(value:)](#setaddressline2) | Imposta la seconda riga dell'indirizzo. La seconda riga dell'indirizzo contiene il codice postale e la città. L'impostazione di questo campo imposta il tipo di indirizzo su Addre |
| [setCountryCode(value)](#setcountrycode) | Imposta il codice paese ISO a due lettere. Il codice paese è obbligatorio a meno che l'intero indirizzo contenga valori null o vuoti val |
| [setHouseNo(value:)](#sethouseno) | Imposta il numero civico. L'impostazione di questo campo imposta il tipo di indirizzo su AddressType.STRUCTURED a meno che non sia già AddressTyp |
| [setName(value:)](#setname) | Imposta il nome, sia il nome e cognome di una persona fisica sia il nome dell'azienda di una persona giuridica. |
| [setPostalCode(value)](#setpostalcode) | Imposta il codice postale. L'impostazione di questo campo imposta il tipo di indirizzo su AddressType.STRUCTURED a meno che non sia già AddressType |
| [setStreet(value:)](#setstreet) | Imposta la via. La via deve essere specificata senza numero civico. L'impostazione di questo campo imposta il tipo di indirizzo su AddressT |
| [setTown(value)](#settown) | Imposta la città o il comune. L'impostazione di questo campo imposta il tipo di indirizzo su AddressType.STRUCTURED a meno che non sia già AddressTyp |

### clear() {#clear}

Cancella tutti i campi e imposta il tipo su AddressType.UNDETERMINED.

### equals(obj) {#equals}

Determina se l'oggetto specificato è uguale all'oggetto corrente.

| Parametro | Descrizione |
| --- | --- |
| obj | L'oggetto da confrontare con l'oggetto corrente. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAddressLine1() {#getaddressline1}

Restituisce la prima riga dell'indirizzo. La prima riga dell'indirizzo contiene il nome della via, il numero civico o la casella postale. L'impostazione di questo campo imposta il tipo di indirizzo su AddressType.COMBINED_ELEMENTS a meno che non sia già AddressType.STRUCTURED, nel qual caso diventa AddressType.CONFLICTING. Questo campo è usato solo per gli indirizzi a elementi combinati ed è opzionale.

**Returns:** The address line 1.

### getAddressLine2() {#getaddressline2}

Restituisce la seconda riga dell'indirizzo. La seconda riga dell'indirizzo contiene il codice postale e la città. L'impostazione di questo campo imposta il tipo di indirizzo su AddressType.COMBINED_ELEMENTS a meno che non sia già AddressType.STRUCTURED, nel qual caso diventa AddressType.CONFLICTING. Questo campo è usato solo per gli indirizzi a elementi combinati. Per questo tipo, è obbligatorio.

**Returns:** The address line 2.

### getCountryCode() {#getcountrycode}

Restituisce il codice paese ISO a due lettere. Il codice paese è obbligatorio a meno che l'intero indirizzo contenga valori null o vuoti.

**Returns:** The ISO country code.

### getHouseNo() {#gethouseno}

Restituisce il numero civico. L'impostazione di questo campo imposta il tipo di indirizzo su AddressType.STRUCTURED a meno che non sia già AddressType.COMBINED_ELEMENTS, nel qual caso diventa AddressType.CONFLICTING. Questo campo è usato solo per gli indirizzi strutturati ed è opzionale.

**Returns:** The house number.

### getName() {#getname}

Restituisce il nome, sia il nome e cognome di una persona fisica sia la ragione sociale di una persona giuridica.

**Returns:** The name.

### getPostalCode() {#getpostalcode}

Restituisce il codice postale. L'impostazione di questo campo imposta il tipo di indirizzo su AddressType.STRUCTURED a meno che non sia già AddressType.COMBINED_ELEMENTS, nel qual caso diventa AddressType.CONFLICTING. Questo campo è usato solo per gli indirizzi strutturati. Per questo tipo, è obbligatorio.

**Returns:** The postal code.

### getStreet() {#getstreet}

Restituisce la via. La via deve essere specificata senza numero civico. L'impostazione di questo campo imposta il tipo di indirizzo su AddressType.STRUCTURED a meno che non sia già AddressType.COMBINED_ELEMENTS, nel qual caso diventa AddressType.CONFLICTING. Questo campo è usato solo per gli indirizzi strutturati ed è opzionale.

**Returns:** The street.

### getTown() {#gettown}

Restituisce la città o il comune. L'impostazione di questo campo imposta il tipo di indirizzo su AddressType.STRUCTURED a meno che non sia già AddressType.COMBINED_ELEMENTS, nel qual caso diventa AddressType.CONFLICTING. Questo campo è usato solo per gli indirizzi strutturati. Per questo tipo, è obbligatorio.

**Returns:** The town or city.

### getType() {#gettype}

Restituisce il tipo di indirizzo. Il tipo di indirizzo è impostato automaticamente impostando la via / numero civico o le righe di indirizzo 1 e 2. Prima di impostare i campi, il tipo di indirizzo è Undetermined. Se i campi di entrambi i tipi sono impostati, il tipo di indirizzo diventa Conflicting.

**Returns:** The address type.

### hashCode() {#hashcode}

Ottiene il codice hash per questa istanza.

**Returns:** A hash code for the current object .

### setAddressLine1(value:) {#setaddressline1}

Imposta la prima riga dell'indirizzo. La prima riga dell'indirizzo contiene il nome della via, il numero civico o la casella postale. L'impostazione di questo campo imposta il tipo di indirizzo su AddressType.COMBINED_ELEMENTS a meno che non sia già AddressType.STRUCTURED, nel qual caso diventa AddressType.CONFLICTING. Questo campo è usato solo per gli indirizzi a elementi combinati ed è opzionale.

| Parametro | Descrizione |
| --- | --- |
| valore: | La prima riga dell'indirizzo. |

### setAddressLine2(value:) {#setaddressline2}

Imposta la seconda riga dell'indirizzo. La seconda riga dell'indirizzo contiene il codice postale e la città. L'impostazione di questo campo imposta il tipo di indirizzo su AddressType.COMBINED_ELEMENTS a meno che non sia già AddressType.STRUCTURED, nel qual caso diventa AddressType.CONFLICTING. Questo campo è usato solo per gli indirizzi a elementi combinati. Per questo tipo, è obbligatorio.

| Parametro | Descrizione |
| --- | --- |
| valore: | La seconda riga dell'indirizzo. |

### setCountryCode(value) {#setcountrycode}

Imposta il codice paese ISO a due lettere. Il codice paese è obbligatorio a meno che l'intero indirizzo contenga valori null o vuoti.

| Parametro | Descrizione |
| --- | --- |
| valore | Il codice paese ISO. |

### setHouseNo(value:) {#sethouseno}

Imposta il numero civico. L'impostazione di questo campo imposta il tipo di indirizzo su AddressType.STRUCTURED a meno che non sia già AddressType.COMBINED_ELEMENTS, nel qual caso diventa AddressType.CONFLICTING. Questo campo è utilizzato solo per indirizzi strutturati ed è opzionale.

| Parametro | Descrizione |
| --- | --- |
| valore: | Il numero civico. |

### setName(value:) {#setname}

Imposta il nome, sia il nome e cognome di una persona fisica sia il nome dell'azienda di una persona giuridica.

| Parametro | Descrizione |
| --- | --- |
| valore: | Il nome. |

### setPostalCode(value) {#setpostalcode}

Imposta il codice postale. L'impostazione di questo campo imposta il tipo di indirizzo su AddressType.STRUCTURED a meno che non sia già AddressType.COMBINED_ELEMENTS, nel qual caso diventa AddressType.CONFLICTING. Questo campo è utilizzato solo per indirizzi strutturati. Per questo tipo, è obbligatorio.

| Parametro | Descrizione |
| --- | --- |
| valore | Il codice postale. |

### setStreet(value:) {#setstreet}

Imposta la via. La via deve essere specificata senza numero civico. L'impostazione di questo campo imposta il tipo di indirizzo su AddressType.STRUCTURED a meno che non sia già AddressType.COMBINED_ELEMENTS, nel qual caso diventa AddressType.CONFLICTING. Questo campo è utilizzato solo per indirizzi strutturati ed è opzionale.

| Parametro | Descrizione |
| --- | --- |
| valore: | La via. |

### setTown(value) {#settown}

Imposta la città o il comune. L'impostazione di questo campo imposta il tipo di indirizzo su AddressType.STRUCTURED a meno che non sia già AddressType.COMBINED_ELEMENTS, nel qual caso diventa AddressType.CONFLICTING. Questo campo è utilizzato solo per indirizzi strutturati. Per questo tipo, è obbligatorio.

| Parametro | Descrizione |
| --- | --- |
| valore | La città o il comune. |
