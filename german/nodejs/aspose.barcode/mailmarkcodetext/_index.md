---
title: "MailmarkCodetext"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "Klasse zum Kodieren und Dekodieren des in den 4‑State‑Royal‑Mailmark‑Code eingebetteten Textes."
type: docs
weight: 580
url: /de/nodejs/aspose.barcode/mailmarkcodetext/
---

## MailmarkCodetext class

Klasse zum Kodieren und Dekodieren des in den 4‑State‑Royal‑Mailmark‑Code eingebetteten Textes.

```js
new MailmarkCodetext()
```

Initialisiert eine neue Instanz der `MailmarkCodetext`‑Klasse.

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getBarcodeType()](#getbarcodetype) | Ermittelt den Barcode-Typ. |
| [getClass_()](#getclass-) | "0" - Null oder Test "1" - 1C (Einzelhandel) "2" - 2C (Einzelhandel) "3" - 3C (Einzelhandel) "4" - Premium (RetailPublishing Mail) (für pote |
| [getConstructedCodetext()](#getconstructedcodetext) | Erstellt Codetext aus Mailmark-Daten. |
| [getDestinationPostCodePlusDPS()](#getdestinationpostcodeplusdps) | Der PC und DP müssen dem PAF-Format entsprechen. Neun‑zeichen‑lange Zeichenkette, die das internationale "XY11 " bezeichnet (beachten Sie die 5 nachfolgenden s |
| [getFormat()](#getformat) | "0" – Null oder Test "1" – Buchstabe "2" – Großbuchstabe |
| [getItemID()](#getitemid) | Der Maximalwert beträgt 99999999. |
| [getSupplychainID()](#getsupplychainid) | Die Maximalwerte sind 99 für Barcode C und 999999 für Barcode L. |
| [getVersionID()](#getversionid) | Derzeit "1" – Für Mailmark-Barcode (0 und 2 bis 9 sowie A bis Z sind für zukünftige Verwendung reserviert) |
| [initFromString(constructedCodetext)](#initfromstring) | Initialisiert Mailmark-Daten aus dem erstellten Codetext. |
| [setClass_()](#setclass-) | "0" - Null oder Test "1" - 1C (Einzelhandel) "2" - 2C (Einzelhandel) "3" - 3C (Einzelhandel) "4" - Premium (RetailPublishing Mail) (für pote |
| [setDestinationPostCodePlusDPS()](#setdestinationpostcodeplusdps) | Der PC und DP müssen dem PAF-Format entsprechen. Neun‑zeichen‑lange Zeichenkette, die das internationale "XY11 " bezeichnet (beachten Sie die 5 nachfolgenden s |
| [setFormat()](#setformat) | "0" – Null oder Test "1" – BuchstabeN "2" – Großbuchstabe |
| [setItemID()](#setitemid) | Der Maximalwert beträgt 99999999. |
| [setSupplychainID()](#setsupplychainid) | Die Maximalwerte sind 99 für Barcode C und 999999 für Barcode L. |
| [setVersionID()](#setversionid) | Derzeit "1" – Für Mailmark-Barcode (0 und 2 bis 9 sowie A bis Z sind für zukünftige Verwendung reserviert) |

### getBarcodeType() {#getbarcodetype}

Ermittelt den Barcode-Typ.

**Returns:** Barcode type.

### getClass_() {#getclass-}

"0" - Null oder Test "1" - 1C (Einzelhandel) "2" - 2C (Einzelhandel) "3" - 3C (Einzelhandel) "4" - Premium (RetailPublishing Mail) (für potenzielle zukünftige Nutzung) "5" - Deferred (Einzelhandel) "6" - Air (Einzelhandel) (für potenzielle zukünftige Nutzung) "7" - Surface (Einzelhandel) (für potenzielle zukünftige Nutzung) "8" - Premium (Netzwerkzugriff) "9" - Standard (Netzwerkzugriff)

### getConstructedCodetext() {#getconstructedcodetext}

Erstellt Codetext aus Mailmark-Daten.

**Returns:** Constructed codetext

### getDestinationPostCodePlusDPS() {#getdestinationpostcodeplusdps}

Der PC und DP müssen dem PAF-Format entsprechen. Neun‑zeichen‑lange Zeichenkette, die das internationale "XY11 " bezeichnet (beachten Sie die 5 nachfolgenden Leerzeichen) oder ein Muster von Zeichen, das einen inländischen Sortiercode bezeichnet. Ein inländischer Sortiercode besteht aus einer Außen-Postleitzahl, einer Innen-Postleitzahl und einem Delivery‑Point‑Suffix.

### getFormat() {#getformat}

"0" – Null oder Test "1" – Buchstabe "2" – Großbuchstabe

### getItemID() {#getitemid}

Der Maximalwert beträgt 99999999.

### getSupplychainID() {#getsupplychainid}

Die Maximalwerte sind 99 für Barcode C und 999999 für Barcode L.

### getVersionID() {#getversionid}

Derzeit "1" – Für Mailmark-Barcode (0 und 2 bis 9 sowie A bis Z sind für zukünftige Verwendung reserviert)

### initFromString(constructedCodetext) {#initfromstring}

Initialisiert Mailmark-Daten aus dem erstellten Codetext.

| Parameter | Beschreibung |
| --- | --- |
| constructedCodetext | Erstellter Codetext. |

### setClass_() {#setclass-}

"0" - Null oder Test "1" - 1C (Einzelhandel) "2" - 2C (Einzelhandel) "3" - 3C (Einzelhandel) "4" - Premium (RetailPublishing Mail) (für potenzielle zukünftige Nutzung) "5" - Deferred (Einzelhandel) "6" - Air (Einzelhandel) (für potenzielle zukünftige Nutzung) "7" - Surface (Einzelhandel) (für potenzielle zukünftige Nutzung) "8" - Premium (Netzwerkzugriff) "9" - Standard (Netzwerkzugriff)

### setDestinationPostCodePlusDPS() {#setdestinationpostcodeplusdps}

Der PC und DP müssen dem PAF-Format entsprechen. Neun‑zeichen‑lange Zeichenkette, die das internationale "XY11 " bezeichnet (beachten Sie die 5 nachfolgenden Leerzeichen) oder ein Muster von Zeichen, das einen inländischen Sortiercode bezeichnet. Ein inländischer Sortiercode besteht aus einer Außen-Postleitzahl, einer Innen-Postleitzahl und einem Delivery‑Point‑Suffix.

### setFormat() {#setformat}

"0" – Null oder Test "1" – BuchstabeN "2" – Großbuchstabe

### setItemID() {#setitemid}

Der Maximalwert beträgt 99999999.

### setSupplychainID() {#setsupplychainid}

Die Maximalwerte sind 99 für Barcode C und 999999 für Barcode L.

### setVersionID() {#setversionid}

Derzeit "1" – Für Mailmark-Barcode (0 und 2 bis 9 sowie A bis Z sind für zukünftige Verwendung reserviert)
