---
title: "SwissQRBill"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "SwissQR-fakturadata"
type: docs
weight: 920
url: /sv/nodejs/aspose.barcode/swissqrbill/
---

## SwissQRBill class

SwissQR-fakturadata

```js
new SwissQRBill()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [createAndSetCreditorReference(rawReference)](#createandsetcreditorreference) | Skapar och sätter en ISO11649 borgenärreferens från en rå sträng genom att prefixa strängen med "RF" och modulo 97‑kontrollen |
| [equals(obj)](#equals) | Bestämmer om det angivna objektet är lika med det aktuella objektet. |
| [getAccount()](#getaccount) | Hämtar borgenärens kontonummer. Kontonummer måste vara giltiga IBAN‑nummer från en bank i Schweiz eller Liechtenstein. Mellanslag |
| [getAlternativeSchemes()](#getalternativeschemes) | Hämtar eller sätter de alternativa betalningsschemana. Högst två scheman med parametrar är tillåtna. |
| [getAmount()](#getamount) | Hämtar betalningsbeloppet. Giltiga värden är mellan 0,01 och 999 999 999,99. |
| [getBillInformation()](#getbillinformation) | Hämtar den ytterligare strukturerade fakturainformationen. |
| [getCreditor()](#getcreditor) | Hämtar borgenärens adress. |
| [getCurrency()](#getcurrency) | Hämtar betalningsvalutan. Giltiga värden är "CHF" och "EUR". |
| [getDebtor()](#getdebtor) | Hämtar gäldenärens adress. Gäldenären är valfri. Om den utelämnas kan fältet sättas till null eller en adress anges. |
| [getReference()](#getreference) | Hämtar borgenärens betalningsreferens. Referensen är obligatorisk för SwissQR‑IBAN‑nummer, d.v.s. IBAN‑nummer i intervallet CHxx30000xxxxx. |
| [getUnstructuredMessage()](#getunstructuredmessage) | Hämtar det ytterligare ostrukturerade meddelandet. |
| [getVersion()](#getversion) | Hämtar versionen av SwissQR‑fakturastandarden. |
| [hashCode()](#hashcode) | Hämtar hash‑koden för detta objekt. |
| [setAccount(value:)](#setaccount) | Sätter borgenärens kontonummer. Kontonummer måste vara giltiga IBAN‑nummer från en bank i Schweiz eller Liechtenstein. Mellanslag |
| [setAlternativeSchemes(value:)](#setalternativeschemes) | Hämtar eller sätter de alternativa betalningsschemana. Högst två scheman med parametrar är tillåtna. |
| [setAmount(value)](#setamount) | Sätter betalningsbeloppet. Giltiga värden är mellan 0,01 och 999 999 999,99. |
| [setBillInformation(value:)](#setbillinformation) | Sätter den ytterligare strukturerade fakturainformationen. |
| [setCreditor(value:)](#setcreditor) | Sätter borgenärens adress. |
| [setCurrency(value)](#setcurrency) | Sätter betalningsvalutan. |
| [setDebtor(value:)](#setdebtor) | Sätter gäldenärens adress. Gäldenären är valfri. Om den utelämnas kan fältet sättas till null eller en adress anges. |
| [setReference(value)](#setreference) | Sätter borgenärens betalningsreferens. Referensen är obligatorisk för SwissQR‑IBAN‑nummer, d.v.s. IBAN‑nummer i intervallet CHxx30000xxxxx. |
| [setUnstructuredMessage(value:)](#setunstructuredmessage) | Ställer in det ytterligare ostrukturerade meddelandet. |
| [setVersion(value)](#setversion) | Ställer in versionen av SwissQR-fakturastandarden. |

### createAndSetCreditorReference(rawReference) {#createandsetcreditorreference}

Skapar och ställer in en ISO11649‑kreditorreferens från en rå sträng genom att prefixa Strängen med "RF" och modulo‑97‑kontrollen. Blanksteg tas bort från referensen

| Parameter | Beskrivning |
| --- | --- |
| rawReference | Den råa referensen. |

**Throws:** ArgumentException rawReference contains invalid characters.

### equals(obj) {#equals}

Bestämmer om det angivna objektet är lika med det aktuella objektet.

| Parameter | Beskrivning |
| --- | --- |
| obj | Objektet att jämföra med det aktuella objektet. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAccount() {#getaccount}

Hämtar kreditorns kontonummer. Kontonummer måste vara giltiga IBAN‑nummer från en bank i Schweiz eller Liechtenstein. Mellanslag är tillåtna i kontonumret.

**Returns:** The creditor account number.

### getAlternativeSchemes() {#getalternativeschemes}

Hämtar eller sätter de alternativa betalningsschemana. Högst två scheman med parametrar är tillåtna.

**Returns:** The alternative payment schemes.

### getAmount() {#getamount}

Hämtar betalningsbeloppet. Giltiga värden är mellan 0,01 och 999 999 999,99.

**Returns:** The payment amount.

### getBillInformation() {#getbillinformation}

Hämtar den ytterligare strukturerade fakturainformationen.

**Returns:** The structured bill information.

### getCreditor() {#getcreditor}

Hämtar borgenärens adress.

**Returns:** The creditor address.

### getCurrency() {#getcurrency}

Hämtar betalningsvalutan. Giltiga värden är "CHF" och "EUR".

**Returns:** The payment currency.

### getDebtor() {#getdebtor}

Hämtar gäldenärens adress. Gäldenären är valfri. Om den utelämnas är både att sätta detta fält till null eller att ange en adress med alla null‑ eller tomma värden acceptabelt.

**Returns:** The debtor address.

### getReference() {#getreference}

Hämtar kreditorns betalningsreferens. Referensen är obligatorisk för SwissQR‑IBAN‑nummer, d.v.s. IBAN‑nummer i intervallet CHxx30000xxxxxx till CHxx31999xxxxx. Om den anges måste referensen vara antingen en giltig SwissQR‑referens (motsvarande ISR‑referensform) eller en giltig kreditorreferens enligt ISO 11649 ("RFxxxx"). Båda kan innehålla mellanslag för formatering.

**Returns:** The creditor payment reference.

### getUnstructuredMessage() {#getunstructuredmessage}

Hämtar det ytterligare ostrukturerade meddelandet.

**Returns:** The unstructured message.

### getVersion() {#getversion}

Hämtar versionen av SwissQR‑fakturastandarden.

**Returns:** The SwissQR bill standard version.

### hashCode() {#hashcode}

Hämtar hash‑koden för detta objekt.

**Returns:** A hash code for the current object.

### setAccount(value:) {#setaccount}

Ställer in kreditorns kontonummer. Kontonummer måste vara giltiga IBAN‑nummer från en bank i Schweiz eller Liechtenstein. Mellanslag är tillåtna i kontonumret.

| Parameter | Beskrivning |
| --- | --- |
| värde: | Kreditorns kontonummer. |

### setAlternativeSchemes(value:) {#setalternativeschemes}

Hämtar eller sätter de alternativa betalningsschemana. Högst två scheman med parametrar är tillåtna.

| Parameter | Beskrivning |
| --- | --- |
| värde: | De alternativa betalningsschemana. |

### setAmount(value) {#setamount}

Sätter betalningsbeloppet. Giltiga värden är mellan 0,01 och 999 999 999,99.

| Parameter | Beskrivning |
| --- | --- |
| värde | Betalningsbeloppet. |

### setBillInformation(value:) {#setbillinformation}

Sätter den ytterligare strukturerade fakturainformationen.

| Parameter | Beskrivning |
| --- | --- |
| värde: | Den strukturerade fakturainformationen. |

### setCreditor(value:) {#setcreditor}

Sätter borgenärens adress.

| Parameter | Beskrivning |
| --- | --- |
| värde: | Kreditorns adress. |

### setCurrency(value) {#setcurrency}

Sätter betalningsvalutan.

| Parameter | Beskrivning |
| --- | --- |
| värde | Giltiga värden är "CHF" och "EUR". |

### setDebtor(value:) {#setdebtor}

Ställer in gäldenärens adress. Gäldenären är valfri. Om den utelämnas är både att sätta detta fält till null eller att ange en adress med alla null‑ eller tomma värden acceptabelt.

| Parameter | Beskrivning |
| --- | --- |
| värde: | Gäldenärens adress. |

### setReference(value) {#setreference}

Ställer in kreditorns betalningsreferens. Referensen är obligatorisk för SwissQR‑IBAN‑nummer, d.v.s. IBAN‑nummer i intervallet CHxx30000xxxxxx till CHxx31999xxxxx. Om den anges måste referensen vara antingen en giltig SwissQR‑referens (motsvarande ISR‑referensform) eller en giltig kreditorreferens enligt ISO 11649 ("RFxxxx"). Båda kan innehålla mellanslag för formatering.

| Parameter | Beskrivning |
| --- | --- |
| värde | Kreditorns betalningsreferens. |

### setUnstructuredMessage(value:) {#setunstructuredmessage}

Ställer in det ytterligare ostrukturerade meddelandet.

| Parameter | Beskrivning |
| --- | --- |
| värde: | Det ostrukturerade meddelandet. |

### setVersion(value) {#setversion}

Ställer in versionen av SwissQR-fakturastandarden.

| Parameter | Beskrivning |
| --- | --- |
| värde | Versionen av SwissQR‑fakturastandarden. |
