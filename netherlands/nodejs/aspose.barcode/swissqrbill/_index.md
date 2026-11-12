---
title: "SwissQRBill"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "SwissQR-factuurgegevens"
type: docs
weight: 920
url: /nl/nodejs/aspose.barcode/swissqrbill/
---

## SwissQRBill class

SwissQR-factuurgegevens

```js
new SwissQRBill()
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [createAndSetCreditorReference(rawReference)](#createandsetcreditorreference) | Maakt en stelt een ISO11649 crediteurreferentie in vanuit een ruwe tekenreeks door de String te prefixen met \"RF\" en de modulo 97 controle. |
| [equals(obj)](#equals) | Bepaalt of het opgegeven object gelijk is aan het huidige object. |
| [getAccount()](#getaccount) | Haalt het rekeningnummer van de crediteur op. Rekeningnummers moeten geldige IBAN's zijn van een bank in Zwitserland of Liechtenstein. Space |
| [getAlternativeSchemes()](#getalternativeschemes) | Haalt op of stelt de alternatieve betaalschema's in. Een maximum van twee schema's met parameters is toegestaan. |
| [getAmount()](#getamount) | Haalt het betalingsbedrag op. Geldige waarden liggen tussen 0.01 en 999,999,999.99. |
| [getBillInformation()](#getbillinformation) | Haalt de aanvullende gestructureerde factuurinformatie op. |
| [getCreditor()](#getcreditor) | Haalt het crediteuradres op. |
| [getCurrency()](#getcurrency) | Haalt de betalingsvaluta op. Geldige waarden zijn \"CHF\" en \"EUR\". |
| [getDebtor()](#getdebtor) | Haalt het debiteuradres op. De debiteur is optioneel. Indien weggelaten, zowel het veld op null zetten als een adres instellen. |
| [getReference()](#getreference) | Haalt de crediteurbetalingsreferentie op. De referentie is verplicht voor SwissQR-IBAN's, i.e. IBAN's in het bereik CHxx30000xxxxx. |
| [getUnstructuredMessage()](#getunstructuredmessage) | Haalt het aanvullende ongestructureerde bericht op. |
| [getVersion()](#getversion) | Haalt de versie van de SwissQR-factuurstandaard op. |
| [hashCode()](#hashcode) | Haalt de hashcode op voor deze instantie. |
| [setAccount(value:)](#setaccount) | Stelt het rekeningnummer van de crediteur in. Rekeningnummers moeten geldige IBAN's zijn van een bank in Zwitserland of Liechtenstein. Spatie. |
| [setAlternativeSchemes(value:)](#setalternativeschemes) | Haalt of stelt de alternatieve betaalschema's in. Een maximum van twee schema's met parameters is toegestaan. |
| [setAmount(value)](#setamount) | Stelt het betalingsbedrag in. Geldige waarden liggen tussen 0.01 en 999,999,999.99. |
| [setBillInformation(value:)](#setbillinformation) | Stelt de aanvullende gestructureerde factuurinformatie in. |
| [setCreditor(value:)](#setcreditor) | Stelt het crediteuradres in. |
| [setCurrency(value)](#setcurrency) | Stelt de betalingsvaluta in. |
| [setDebtor(value:)](#setdebtor) | Stelt het debiteuradres in. De debiteur is optioneel. Indien weggelaten, zowel het veld op null zetten als een adres instellen. |
| [setReference(value)](#setreference) | Stelt de crediteurbetalingsreferentie in. De referentie is verplicht voor SwissQR-IBAN's, i.e. IBAN's in het bereik CHxx30000xxxxx. |
| [setUnstructuredMessage(value:)](#setunstructuredmessage) | Stelt het aanvullende ongestructureerde bericht in. |
| [setVersion(value)](#setversion) | Stelt de versie van de SwissQR-factuurstandaard in. |

### createAndSetCreditorReference(rawReference) {#createandsetcreditorreference}

Maakt en stelt een ISO11649-crediteurreferentie in vanuit een ruwe string door de String te prefixen met "RF" en de modulo 97-controle. Witruimte wordt uit de referentie verwijderd.

| Parameter | Beschrijving |
| --- | --- |
| rawReference | De ruwe referentie. |

**Throws:** ArgumentException rawReference contains invalid characters.

### equals(obj) {#equals}

Bepaalt of het opgegeven object gelijk is aan het huidige object.

| Parameter | Beschrijving |
| --- | --- |
| obj | Het object om te vergelijken met het huidige object. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAccount() {#getaccount}

Haalt het rekeningnummer van de crediteur op. Rekeningnummers moeten geldige IBAN's zijn van een bank in Zwitserland of Liechtenstein. Spaties zijn toegestaan in het rekeningnummer.

**Returns:** The creditor account number.

### getAlternativeSchemes() {#getalternativeschemes}

Haalt op of stelt de alternatieve betaalschema's in. Een maximum van twee schema's met parameters is toegestaan.

**Returns:** The alternative payment schemes.

### getAmount() {#getamount}

Haalt het betalingsbedrag op. Geldige waarden liggen tussen 0.01 en 999,999,999.99.

**Returns:** The payment amount.

### getBillInformation() {#getbillinformation}

Haalt de aanvullende gestructureerde factuurinformatie op.

**Returns:** The structured bill information.

### getCreditor() {#getcreditor}

Haalt het crediteuradres op.

**Returns:** The creditor address.

### getCurrency() {#getcurrency}

Haalt de betalingsvaluta op. Geldige waarden zijn \"CHF\" en \"EUR\".

**Returns:** The payment currency.

### getDebtor() {#getdebtor}

Haalt het debiteuradres op. De debiteur is optioneel. Indien weggelaten, zowel het veld op null zetten als een adres instellen met alle waarden null of leeg is oké.

**Returns:** The debtor address.

### getReference() {#getreference}

Haalt de crediteurbetalingsreferentie op. De referentie is verplicht voor SwissQR-IBAN's, i.e. IBAN's in het bereik CHxx30000xxxxxx tot CHxx31999xxxxx. Indien gespecificeerd, moet de referentie ofwel een geldige SwissQR-referentie (overeenkomend met ISR-referentieformaat) of een geldige crediteurreferentie volgens ISO 11649 ("RFxxxx") zijn. Beide mogen spaties bevatten voor opmaak.

**Returns:** The creditor payment reference.

### getUnstructuredMessage() {#getunstructuredmessage}

Haalt het aanvullende ongestructureerde bericht op.

**Returns:** The unstructured message.

### getVersion() {#getversion}

Haalt de versie van de SwissQR-factuurstandaard op.

**Returns:** The SwissQR bill standard version.

### hashCode() {#hashcode}

Haalt de hashcode op voor deze instantie.

**Returns:** A hash code for the current object.

### setAccount(value:) {#setaccount}

Stelt het rekeningnummer van de crediteur in. Rekeningnummers moeten geldige IBAN's zijn van een bank in Zwitserland of Liechtenstein. Spaties zijn toegestaan in het rekeningnummer.

| Parameter | Beschrijving |
| --- | --- |
| waarde: | Het crediteurrekeningnummer. |

### setAlternativeSchemes(value:) {#setalternativeschemes}

Haalt of stelt de alternatieve betaalschema's in. Een maximum van twee schema's met parameters is toegestaan.

| Parameter | Beschrijving |
| --- | --- |
| waarde: | De alternatieve betaalschema's. |

### setAmount(value) {#setamount}

Stelt het betalingsbedrag in. Geldige waarden liggen tussen 0.01 en 999,999,999.99.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Het betalingsbedrag. |

### setBillInformation(value:) {#setbillinformation}

Stelt de aanvullende gestructureerde factuurinformatie in.

| Parameter | Beschrijving |
| --- | --- |
| waarde: | De gestructureerde factuurinformatie. |

### setCreditor(value:) {#setcreditor}

Stelt het crediteuradres in.

| Parameter | Beschrijving |
| --- | --- |
| waarde: | Het crediteuradres. |

### setCurrency(value) {#setcurrency}

Stelt de betalingsvaluta in.

| Parameter | Beschrijving |
| --- | --- |
| waarde | Geldige waarden zijn "CHF" en "EUR". |

### setDebtor(value:) {#setdebtor}

Stelt het debiteuradres in. De debiteur is optioneel. Als deze wordt weggelaten, is zowel het instellen van dit veld op null als het instellen van een adres met alle null- of lege waarden acceptabel.

| Parameter | Beschrijving |
| --- | --- |
| waarde: | Het debiteuradres. |

### setReference(value) {#setreference}

Stelt de betalingsreferentie van de crediteur in. De referentie is verplicht voor SwissQR-IBAN's, d.w.z. IBAN's in het bereik CHxx30000xxxxxx tot CHxx31999xxxxx. Indien gespecificeerd, moet de referentie ofwel een geldige SwissQR-referentie (overeenkomstig het ISR-referentieformulier) of een geldige crediteurreferentie volgens ISO 11649 ("RFxxxx") zijn. Beide mogen spaties bevatten voor opmaak.

| Parameter | Beschrijving |
| --- | --- |
| waarde | De crediteurbetalingsreferentie. |

### setUnstructuredMessage(value:) {#setunstructuredmessage}

Stelt het aanvullende ongestructureerde bericht in.

| Parameter | Beschrijving |
| --- | --- |
| waarde: | Het ongestructureerde bericht. |

### setVersion(value) {#setversion}

Stelt de versie van de SwissQR-factuurstandaard in.

| Parameter | Beschrijving |
| --- | --- |
| waarde | De SwissQR-factuurstandaardversie. |
