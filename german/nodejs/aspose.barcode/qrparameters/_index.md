---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "Aspose.BarCode für Node.js über Java API-Referenz"
description: "QR-Parameter."
type: docs
weight: 830
url: /de/nodejs/aspose.barcode/qrparameters/
---

## QrParameters class

QR-Parameter.

```js
new QrParameters()
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Höhen-/Breitenverhältnis des 2D-Barcode-Moduls. |
| [getECIEncoding()](#geteciencoding) | Erweiterte Kanalinterpretations-Identifikatoren. Sie werden verwendet, um dem Barcode-Leser Details über die verwendeten Referenzen für |
| [getEncodeGS1SeparatorInByteMode()](#getencodegs1separatorinbytemode) | Gibt einen Wert zurück oder legt ihn fest, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Strichcode codiert werden sollen |
| [getEncodeMode()](#getencodemode) | QR‑Symboltyp des Kodierungsmodus von BarCode. Standardwert: QREncodeMode.Auto. |
| [getErrorLevel()](#geterrorlevel) | Stufe der Reed‑Solomon‑Fehlerkorrektur für QR‑, MicroQR‑ und RectMicroQR‑Strichcode. Von niedrig nach hoch: LevelL, LevelM, LevelQ |
| [getMicroQRVersion()](#getmicroqrversion) | Version des MicroQR‑Codes. Von Version M1 bis Version M4. Standardwert ist MicroQRVersion.Auto. |
| [getQrECIEncoding()](#getqreciencoding) ~~(deprecated)~~ | Erweiterte Kanalinterpretations-Identifikatoren. Sie werden verwendet, um dem Barcode-Leser Details über die verwendeten Referenzen für |
| [getQrEncodeMode()](#getqrencodemode) | QR‑Symboltyp des Kodierungsmodus von BarCode. Standardwert: QREncodeMode.AUTO. |
| [getQrEncodeType()](#getqrencodetype) ~~(deprecated)~~ | QR‑/MicroQR‑Auswahlmodus. Wählen Sie ForceQR für Standard‑QR‑Symbole, Auto für MicroQR. |
| [getQrErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Stufe der Reed‑Solomon‑Fehlerkorrektur für QR‑Strichcode. Von niedrig nach hoch: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. siehe QRError |
| [getQrVersion()](#getqrversion) ~~(deprecated)~~ | Version des QR‑Codes. Von Version1 bis Version40 für QR‑Code und von M1 bis M4 für MicroQr. Standardwert ist QRVersion.AUT |
| [getRectMicroQrVersion()](#getrectmicroqrversion) | Version des RectMicroQR‑Codes. Von Version R7x59 bis Version R17x139. Standardwert ist RectMicroQRVersion.Auto. |
| [getStructuredAppend()](#getstructuredappend) | QR Structured‑Append-Parameter. |
| [getVersion()](#getversion) | Version des QR‑Codes. Von Version1 bis Version40. Standardwert ist QRVersion.Auto. |
| [setAspectRatio()](#setaspectratio) | Höhen-/Breitenverhältnis des 2D-Barcode-Moduls. |
| [setECIEncoding()](#seteciencoding) | Erweiterte Kanalinterpretations-Identifikatoren. Sie werden verwendet, um dem Barcode-Leser Details über die verwendeten Referenzen für |
| [setEncodeGS1SeparatorInByteMode(value)](#setencodegs1separatorinbytemode) | Gibt einen Wert zurück oder legt ihn fest, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Strichcode codiert werden sollen |
| [setEncodeMode()](#setencodemode) | QR‑Symboltyp des Kodierungsmodus von BarCode. Standardwert: QREncodeMode.Auto. |
| [setErrorLevel()](#seterrorlevel) | Stufe der Reed‑Solomon‑Fehlerkorrektur für QR‑, MicroQR‑ und RectMicroQR‑Strichcode. Von niedrig nach hoch: LevelL, LevelM, LevelQ |
| [setMicroQRVersion()](#setmicroqrversion) | Version des MicroQR‑Codes. Von Version M1 bis Version M4. Standardwert ist MicroQRVersion.Auto. |
| [setQrECIEncoding()](#setqreciencoding) ~~(deprecated)~~ | Erweiterte Kanalinterpretations-Identifikatoren. Sie werden verwendet, um dem Barcode-Leser Details über die verwendeten Referenzen für |
| [setQrEncodeMode()](#setqrencodemode) ~~(deprecated)~~ | QR‑Symboltyp des Kodierungsmodus von BarCode. Standardwert: QREncodeMode.AUTO. |
| [setQrEncodeType()](#setqrencodetype) ~~(deprecated)~~ | QR‑/MicroQR‑Auswahlmodus. Wählen Sie ForceQR für Standard‑QR‑Symbole, Auto für MicroQR. |
| [setQrErrorLevel()](#setqrerrorlevel) ~~(deprecated)~~ | Stufe der Reed‑Solomon‑Fehlerkorrektur für QR‑Strichcode. Von niedrig nach hoch: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. siehe QRError |
| [setQrVersion()](#setqrversion) ~~(deprecated)~~ | Version des QR‑Codes. Von Version1 bis Version40 für QR‑Code und von M1 bis M4 für MicroQr. Standardwert ist QRVersion.AUT |
| [setRectMicroQrVersion()](#setrectmicroqrversion) | Version des RectMicroQR‑Codes. Von Version R7x59 bis Version R17x139. Standardwert ist RectMicroQRVersion.Auto. |
| [setStructuredAppend()](#setstructuredappend) | QR Structured‑Append-Parameter. |
| [setVersion()](#setversion) | Version des QR‑Codes. Von Version1 bis Version40. Standardwert ist QRVersion.Auto. |
| [toString()](#tostring) | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieser QrParameters zurück. |

### getAspectRatio() {#getaspectratio}

Höhen-/Breitenverhältnis des 2D-Barcode-Moduls.

### getECIEncoding() {#geteciencoding}

Extended Channel Interpretation‑Bezeichner. Sie werden verwendet, um dem Barcode‑Leser Details über die verwendeten Referenzen zur Datenkodierung im Symbol mitzuteilen. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen. Nicht unterstützt von MicroQR.

### getEncodeGS1SeparatorInByteMode() {#getencodegs1separatorinbytemode}

Gibt einen Wert zurück oder legt ihn fest, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Strichcodes codiert werden sollen. Wenn false, können GS1‑Trennzeichen gemäß QR‑Spezifikation im alphanumerischen Modus als '%' codiert werden. Wenn true, werden GS1‑Gruppentrennzeichen im Byte‑Modus als das Zeichen 0x1D codiert, und '%'‑Zeichen werden ebenfalls im Byte‑Modus codiert, um sie als Daten zu erhalten. Diese Option kann die Kompatibilität mit Decodern verbessern, die byte‑level GS1‑Gruppentrennzeichen erwarten, und verhindert, dass '%'‑Datenzeichen als GS1‑Trennzeichen interpretiert werden.

**Returns:** a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

### getEncodeMode() {#getencodemode}

QR‑Symboltyp des Kodierungsmodus von BarCode. Standardwert: QREncodeMode.Auto.

### getErrorLevel() {#geterrorlevel}

Stufe der Reed‑Solomon‑Fehlerkorrektur für QR‑, MicroQR‑ und RectMicroQR‑Strichcode. Von niedrig nach hoch: LevelL, LevelM, LevelQ, LevelH. Siehe QRErrorLevel.

### getMicroQRVersion() {#getmicroqrversion}

Version des MicroQR‑Codes. Von Version M1 bis Version M4. Standardwert ist MicroQRVersion.Auto.

### getQrECIEncoding() {#getqreciencoding}

> **Deprecated.** See method description for replacement.

Erweiterte Channel‑Interpretations‑Identifikatoren. Sie werden verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Die aktuelle Implementierung besteht aus allen bekannten Zeichensatzkodierungen.

### getQrEncodeMode() {#getqrencodemode}

QR‑Symboltyp des Kodierungsmodus von BarCode. Standardwert: QREncodeMode.AUTO.

### getQrEncodeType() {#getqrencodetype}

> **Deprecated.** See method description for replacement.

QR‑/MicroQR‑Auswahlmodus. Wählen Sie ForceQR für Standard‑QR‑Symbole, Auto für MicroQR.

### getQrErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Stufe der Reed‑Solomon‑Fehlerkorrektur für QR‑Strichcode. Von niedrig nach hoch: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. siehe QRErrorLevel.

### getQrVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Version des QR‑Codes. Von Version1 bis Version40 für QR‑Code und von M1 bis M4 für MicroQr. Standardwert ist QRVersion.AUTO.

### getRectMicroQrVersion() {#getrectmicroqrversion}

Version des RectMicroQR‑Codes. Von Version R7x59 bis Version R17x139. Standardwert ist RectMicroQRVersion.Auto.

### getStructuredAppend() {#getstructuredappend}

QR Structured‑Append-Parameter.

### getVersion() {#getversion}

Version des QR‑Codes. Von Version1 bis Version40. Standardwert ist QRVersion.Auto.

### setAspectRatio() {#setaspectratio}

Höhen-/Breitenverhältnis des 2D-Barcode-Moduls.

### setECIEncoding() {#seteciencoding}

Extended Channel Interpretation‑Bezeichner. Sie werden verwendet, um dem Barcode‑Leser Details über die verwendeten Referenzen zur Datenkodierung im Symbol mitzuteilen. Die aktuelle Implementierung enthält alle bekannten Zeichensatzkodierungen. Nicht unterstützt von MicroQR.

### setEncodeGS1SeparatorInByteMode(value) {#setencodegs1separatorinbytemode}

Gibt einen Wert zurück oder legt ihn fest, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Strichcodes codiert werden sollen. Wenn false, können GS1‑Trennzeichen gemäß QR‑Spezifikation im alphanumerischen Modus als '%' codiert werden. Wenn true, werden GS1‑Gruppentrennzeichen im Byte‑Modus als das Zeichen 0x1D codiert, und '%'‑Zeichen werden ebenfalls im Byte‑Modus codiert, um sie als Daten zu erhalten. Diese Option kann die Kompatibilität mit Decodern verbessern, die byte‑level GS1‑Gruppentrennzeichen erwarten, und verhindert, dass '%'‑Datenzeichen als GS1‑Trennzeichen interpretiert werden.

| Parameter | Beschreibung |
| --- | --- |
| Wert | ein Wert, der angibt, ob GS1‑Sonderzeichen im Byte‑Modus für QR‑ und RectMicroQR‑Strichcodes codiert werden sollen. |

### setEncodeMode() {#setencodemode}

QR‑Symboltyp des Kodierungsmodus von BarCode. Standardwert: QREncodeMode.Auto.

### setErrorLevel() {#seterrorlevel}

Stufe der Reed‑Solomon‑Fehlerkorrektur für QR‑, MicroQR‑ und RectMicroQR‑Strichcode. Von niedrig nach hoch: LevelL, LevelM, LevelQ, LevelH. Siehe QRErrorLevel.

### setMicroQRVersion() {#setmicroqrversion}

Version des MicroQR‑Codes. Von Version M1 bis Version M4. Standardwert ist MicroQRVersion.Auto.

### setQrECIEncoding() {#setqreciencoding}

> **Deprecated.** See method description for replacement.

Erweiterte Channel‑Interpretations‑Identifikatoren. Sie werden verwendet, um dem Barcode‑Leser Details zu den verwendeten Referenzen für die Kodierung der Daten im Symbol mitzuteilen. Die aktuelle Implementierung besteht aus allen bekannten Zeichensatzkodierungen.

### setQrEncodeMode() {#setqrencodemode}

> **Deprecated.** See method description for replacement.

QR‑Symboltyp des Kodierungsmodus von BarCode. Standardwert: QREncodeMode.AUTO.

### setQrEncodeType() {#setqrencodetype}

> **Deprecated.** See method description for replacement.

QR‑/MicroQR‑Auswahlmodus. Wählen Sie ForceQR für Standard‑QR‑Symbole, Auto für MicroQR.

### setQrErrorLevel() {#setqrerrorlevel}

> **Deprecated.** See method description for replacement.

Stufe der Reed‑Solomon‑Fehlerkorrektur für QR‑Strichcode. Von niedrig nach hoch: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. siehe QRErrorLevel.

### setQrVersion() {#setqrversion}

> **Deprecated.** See method description for replacement.

Version des QR‑Codes. Von Version1 bis Version40 für QR‑Code und von M1 bis M4 für MicroQr. Standardwert ist QRVersion.AUTO.

### setRectMicroQrVersion() {#setrectmicroqrversion}

Version des RectMicroQR‑Codes. Von Version R7x59 bis Version R17x139. Standardwert ist RectMicroQRVersion.Auto.

### setStructuredAppend() {#setstructuredappend}

QR Structured‑Append-Parameter.

### setVersion() {#setversion}

Version des QR‑Codes. Von Version1 bis Version40. Standardwert ist QRVersion.Auto.

### toString() {#tostring}

Gibt eine menschenlesbare Zeichenkettenrepräsentation dieser QrParameters zurück.

**Returns:** A string that represents this QrParameters.
