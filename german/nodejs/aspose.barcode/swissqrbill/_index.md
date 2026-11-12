---
title: "SwissQRBill"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "SwissQR-Rechnungsdaten"
type: docs
weight: 920
url: /de/nodejs/aspose.barcode/swissqrbill/
---

## SwissQRBill class

SwissQR-Rechnungsdaten

```js
new SwissQRBill()
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [createAndSetCreditorReference(rawReference)](#createandsetcreditorreference) | Erstellt und setzt eine ISO11649 Gläubigerreferenz aus einem Rohstring, indem der String mit "RF" und dem Modulo‑97‑Check versehen wird. |
| [equals(obj)](#equals) | Bestimmt, ob das angegebene Objekt dem aktuellen Objekt gleich ist. |
| [getAccount()](#getaccount) | Ermittelt die Kontonummer des Gläubigers. Kontonummern müssen gültige IBANs einer Bank der Schweiz oder Liechtenstein sein. Space |
| [getAlternativeSchemes()](#getalternativeschemes) | Ermittelt oder setzt die alternativen Zahlungsschemata. Es sind maximal zwei Schemata mit Parametern zulässig. |
| [getAmount()](#getamount) | Ermittelt den Zahlungsbetrag. Gültige Werte liegen zwischen 0,01 und 999.999.999,99. |
| [getBillInformation()](#getbillinformation) | Ermittelt die zusätzlichen strukturierten Rechnungsinformationen. |
| [getCreditor()](#getcreditor) | Ermittelt die Gläubigeradresse. |
| [getCurrency()](#getcurrency) | Ermittelt die Zahlungswährung. Gültige Werte sind "CHF" und "EUR". |
| [getDebtor()](#getdebtor) | Liefert die Schuldneradresse. Der Schuldner ist optional. Wenn er weggelassen wird, ist sowohl das Setzen dieses Feldes auf null als auch das Setzen einer Adresse möglich. |
| [getReference()](#getreference) | Liefert die Gläubigerzahlungsreferenz. Die Referenz ist für SwissQR-IBANs verpflichtend, d.h. IBANs im Bereich CHxx30000xxxxx. |
| [getUnstructuredMessage()](#getunstructuredmessage) | Liefert die zusätzliche unstrukturierte Nachricht. |
| [getVersion()](#getversion) | Liefert die Version des SwissQR-Rechnungsstandards. |
| [hashCode()](#hashcode) | Liest den Hashcode für diese Instanz. |
| [setAccount(value:)](#setaccount) | Setzt die Kontonummer des Gläubigers. Kontonummern müssen gültige IBANs einer Bank der Schweiz oder Liechtenstein sein. Leerzeichen. |
| [setAlternativeSchemes(value:)](#setalternativeschemes) | Liefert oder setzt die alternativen Zahlungsschemata. Es sind maximal zwei Schemata mit Parametern erlaubt. |
| [setAmount(value)](#setamount) | Setzt den Zahlungsbetrag. Gültige Werte liegen zwischen 0,01 und 999.999.999,99. |
| [setBillInformation(value:)](#setbillinformation) | Setzt die zusätzlichen strukturierten Rechnungsinformationen. |
| [setCreditor(value:)](#setcreditor) | Setzt die Gläubigeradresse. |
| [setCurrency(value)](#setcurrency) | Setzt die Zahlungswährung. |
| [setDebtor(value:)](#setdebtor) | Setzt die Schuldneradresse. Der Schuldner ist optional. Wenn er weggelassen wird, ist sowohl das Setzen dieses Feldes auf null als auch das Setzen einer Adresse möglich. |
| [setReference(value)](#setreference) | Setzt die Gläubigerzahlungsreferenz. Die Referenz ist für SwissQR-IBANs verpflichtend, d.h. IBANs im Bereich CHxx30000xxxxx. |
| [setUnstructuredMessage(value:)](#setunstructuredmessage) | Setzt die zusätzliche unstrukturierte Nachricht. |
| [setVersion(value)](#setversion) | Setzt die Version des SwissQR-Rechnungsstandards. |

### createAndSetCreditorReference(rawReference) {#createandsetcreditorreference}

Erstellt und setzt eine ISO11649-Gläubigerreferenz aus einem Rohstring, indem der String mit "RF" und der Modulo‑97-Prüfsumme vorangestellt wird. Leerzeichen werden aus der Referenz entfernt.

| Parameter | Beschreibung |
| --- | --- |
| rawReference | Die Rohreferenz. |

**Throws:** ArgumentException rawReference contains invalid characters.

### equals(obj) {#equals}

Bestimmt, ob das angegebene Objekt dem aktuellen Objekt gleich ist.

| Parameter | Beschreibung |
| --- | --- |
| obj | Das Objekt, das mit dem aktuellen Objekt verglichen werden soll. |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAccount() {#getaccount}

Liefert die Kontonummer des Gläubigers. Kontonummern müssen gültige IBANs einer Bank der Schweiz oder Liechtenstein sein. Leerzeichen sind in der Kontonummer erlaubt.

**Returns:** The creditor account number.

### getAlternativeSchemes() {#getalternativeschemes}

Ermittelt oder setzt die alternativen Zahlungsschemata. Es sind maximal zwei Schemata mit Parametern zulässig.

**Returns:** The alternative payment schemes.

### getAmount() {#getamount}

Ermittelt den Zahlungsbetrag. Gültige Werte liegen zwischen 0,01 und 999.999.999,99.

**Returns:** The payment amount.

### getBillInformation() {#getbillinformation}

Ermittelt die zusätzlichen strukturierten Rechnungsinformationen.

**Returns:** The structured bill information.

### getCreditor() {#getcreditor}

Ermittelt die Gläubigeradresse.

**Returns:** The creditor address.

### getCurrency() {#getcurrency}

Ermittelt die Zahlungswährung. Gültige Werte sind "CHF" und "EUR".

**Returns:** The payment currency.

### getDebtor() {#getdebtor}

Liefert die Schuldneradresse. Der Schuldner ist optional. Wenn er weggelassen wird, ist sowohl das Setzen dieses Feldes auf null als auch das Setzen einer Adresse mit allen null- oder leeren Werten in Ordnung.

**Returns:** The debtor address.

### getReference() {#getreference}

Liefert die Gläubigerzahlungsreferenz. Die Referenz ist für SwissQR‑IBANs verpflichtend, d.h. IBANs im Bereich CHxx30000xxxxxx bis CHxx31999xxxxx. Falls angegeben, muss die Referenz entweder eine gültige SwissQR‑Referenz (entsprechend dem ISR‑Referenzformat) oder eine gültige Gläubigerreferenz gemäß ISO 11649 ("RFxxxx") sein. Beide dürfen zur Formatierung Leerzeichen enthalten.

**Returns:** The creditor payment reference.

### getUnstructuredMessage() {#getunstructuredmessage}

Liefert die zusätzliche unstrukturierte Nachricht.

**Returns:** The unstructured message.

### getVersion() {#getversion}

Liefert die Version des SwissQR-Rechnungsstandards.

**Returns:** The SwissQR bill standard version.

### hashCode() {#hashcode}

Liest den Hashcode für diese Instanz.

**Returns:** A hash code for the current object.

### setAccount(value:) {#setaccount}

Setzt die Kontonummer des Gläubigers. Kontonummern müssen gültige IBANs einer Bank der Schweiz oder Liechtenstein sein. Leerzeichen sind in der Kontonummer erlaubt.

| Parameter | Beschreibung |
| --- | --- |
| Wert: | Die Gläubigerkontonummer. |

### setAlternativeSchemes(value:) {#setalternativeschemes}

Liefert oder setzt die alternativen Zahlungsschemata. Es sind maximal zwei Schemata mit Parametern erlaubt.

| Parameter | Beschreibung |
| --- | --- |
| Wert: | Die alternativen Zahlungsschemata. |

### setAmount(value) {#setamount}

Setzt den Zahlungsbetrag. Gültige Werte liegen zwischen 0,01 und 999.999.999,99.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Der Zahlungsbetrag. |

### setBillInformation(value:) {#setbillinformation}

Setzt die zusätzlichen strukturierten Rechnungsinformationen.

| Parameter | Beschreibung |
| --- | --- |
| Wert: | Die strukturierten Rechnungsinformationen. |

### setCreditor(value:) {#setcreditor}

Setzt die Gläubigeradresse.

| Parameter | Beschreibung |
| --- | --- |
| Wert: | Die Gläubigeradresse. |

### setCurrency(value) {#setcurrency}

Setzt die Zahlungswährung.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Gültige Werte sind "CHF" und "EUR". |

### setDebtor(value:) {#setdebtor}

Setzt die Schuldneradresse. Der Schuldner ist optional. Wenn er weggelassen wird, ist sowohl das Setzen dieses Feldes auf null als auch das Setzen einer Adresse mit allen null- oder leeren Werten in Ordnung.

| Parameter | Beschreibung |
| --- | --- |
| Wert: | Die Schuldneradresse. |

### setReference(value) {#setreference}

Setzt die Zahlungsreferenz des Gläubigers. Die Referenz ist für SwissQR-IBANs verpflichtend, d.h. für IBANs im Bereich CHxx30000xxxxxx bis CHxx31999xxxxx. Wenn angegeben, muss die Referenz entweder eine gültige SwissQR-Referenz (entsprechend dem ISR-Referenzformular) oder eine gültige Gläubigerreferenz gemäß ISO 11649 ("RFxxxx") sein. Beide dürfen zur Formatierung Leerzeichen enthalten.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Die Zahlungsreferenz des Gläubigers. |

### setUnstructuredMessage(value:) {#setunstructuredmessage}

Setzt die zusätzliche unstrukturierte Nachricht.

| Parameter | Beschreibung |
| --- | --- |
| Wert: | Die unstrukturierte Nachricht. |

### setVersion(value) {#setversion}

Setzt die Version des SwissQR-Rechnungsstandards.

| Parameter | Beschreibung |
| --- | --- |
| Wert | Die SwissQR-Rechnungsstandardversion. |
