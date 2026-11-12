---
title: "SecondaryAndAdditionalData"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Klasse zum Speichern sekundärer und zusätzlicher HIBC‑LIC-Daten."
type: docs
weight: 880
url: /de/nodejs/aspose.barcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

Klasse zum Speichern sekundärer und zusätzlicher HIBC‑LIC-Daten.

```js
new SecondaryAndAdditionalData()
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [equals(obj)](#equals) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `SecondaryAndAdditionalData`‑Wert entspricht. |
| [getDateOfManufacture()](#getdateofmanufacture) | Identifiziert das Herstellungsdatum. Das Herstellungsdatum kann auf DateTime.MinValue gesetzt werden, um dieses Feld nicht zu verwenden. Defa |
| [getExpiryDate()](#getexpirydate) | Identifiziert das Verfallsdatum. Wird verwendet, wenn ExpiryDateFormat nicht auf None gesetzt ist. |
| [getExpiryDateFormat()](#getexpirydateformat) | Identifiziert das Verfallsdatumsformat. |
| [getLotNumber()](#getlotnumber) | Identifiziert Los- oder Chargennummer. Los/Chargennummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein. . |
| [getQuantity()](#getquantity) | Identifiziert die Menge, muss ein ganzzahliger Wert von 0 bis 500 sein. Menge kann auf -1 gesetzt werden, um dieses Feld nicht zu verwenden. Defa |
| [getSerialNumber()](#getserialnumber) | Identifiziert die Seriennummer. Seriennummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein. |
| [hashCode()](#hashcode) | Gibt den Hashcode für diese Instanz zurück. |
| [parseFromString(secondaryDataCodetext)](#parsefromstring) | Instanziiert sekundäre und zusätzliche Ergänzungsdaten aus dem Zeichenkettenformat gemäß der HIBC LIC-Spezifikation. |
| [setDateOfManufacture()](#setdateofmanufacture) | Identifiziert das Herstellungsdatum. Das Herstellungsdatum kann auf DateTime.MinValue gesetzt werden, um dieses Feld nicht zu verwenden. Defa |
| [setExpiryDate()](#setexpirydate) | Identifiziert das Verfallsdatum. Wird verwendet, wenn ExpiryDateFormat nicht auf None gesetzt ist. |
| [setExpiryDateFormat()](#setexpirydateformat) | Identifiziert das Verfallsdatumsformat. |
| [setLotNumber()](#setlotnumber) | Identifiziert Los- oder Chargennummer. Los/Chargennummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein. . |
| [setQuantity()](#setquantity) | Identifiziert die Menge, muss ein ganzzahliger Wert von 0 bis 500 sein. Menge kann auf -1 gesetzt werden, um dieses Feld nicht zu verwenden. Defa |
| [setSerialNumber()](#setserialnumber) | Identifiziert die Seriennummer. Seriennummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein. |
| [toString()](#tostring) | Konvertiert Daten in das Zeichenkettenformat gemäß der HIBC LIC-Spezifikation. |

### equals(obj) {#equals}

Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen `SecondaryAndAdditionalData`‑Wert entspricht.

| Parameter | Beschreibung |
| --- | --- |
| obj | Ein `SecondaryAndAdditionalData`-Wert zum Vergleich mit dieser Instanz. |

**Returns:** `true ` if obj has the same value as this instance; otherwise, `false `.

### getDateOfManufacture() {#getdateofmanufacture}

Identifiziert das Herstellungsdatum. Das Herstellungsdatum kann auf DateTime.MinValue gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: DateTime.MinValue

### getExpiryDate() {#getexpirydate}

Identifiziert das Verfallsdatum. Wird verwendet, wenn ExpiryDateFormat nicht auf None gesetzt ist.

### getExpiryDateFormat() {#getexpirydateformat}

Identifiziert das Verfallsdatumsformat.

### getLotNumber() {#getlotnumber}

Identifiziert Los- oder Chargennummer. Los/Chargennummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein. .

### getQuantity() {#getquantity}

Identifiziert die Menge, muss ein ganzzahliger Wert von 0 bis 500 sein. Menge kann auf -1 gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: -1

### getSerialNumber() {#getserialnumber}

Identifiziert die Seriennummer. Seriennummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein.

### hashCode() {#hashcode}

Gibt den Hashcode für diese Instanz zurück.

**Returns:** A 32-bit signed integer hash code.

### parseFromString(secondaryDataCodetext) {#parsefromstring}

Instanziiert sekundäre und zusätzliche Ergänzungsdaten aus dem Zeichenkettenformat gemäß der HIBC LIC-Spezifikation.

| Parameter | Beschreibung |
| --- | --- |
| secondaryDataCodetext | Formatierte Zeichenkette. |

### setDateOfManufacture() {#setdateofmanufacture}

Identifiziert das Herstellungsdatum. Das Herstellungsdatum kann auf DateTime.MinValue gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: DateTime.MinValue

### setExpiryDate() {#setexpirydate}

Identifiziert das Verfallsdatum. Wird verwendet, wenn ExpiryDateFormat nicht auf None gesetzt ist.

### setExpiryDateFormat() {#setexpirydateformat}

Identifiziert das Verfallsdatumsformat.

### setLotNumber() {#setlotnumber}

Identifiziert Los- oder Chargennummer. Los/Chargennummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein. .

### setQuantity() {#setquantity}

Identifiziert die Menge, muss ein ganzzahliger Wert von 0 bis 500 sein. Menge kann auf -1 gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: -1

### setSerialNumber() {#setserialnumber}

Identifiziert die Seriennummer. Seriennummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein.

### toString() {#tostring}

Konvertiert Daten in das Zeichenkettenformat gemäß der HIBC LIC-Spezifikation.

**Returns:** Formatted string.
