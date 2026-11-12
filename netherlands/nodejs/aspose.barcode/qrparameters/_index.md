---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "Aspose.BarCode voor Node.js via Java API-referentie"
description: "QR-parameters."
type: docs
weight: 830
url: /nl/nodejs/aspose.barcode/qrparameters/
---

## QrParameters class

QR-parameters.

```js
new QrParameters()
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [getECIEncoding()](#geteciencoding) | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor |
| [getEncodeGS1SeparatorInByteMode()](#getencodegs1separatorinbytemode) | Haalt een waarde op of stelt deze in die aangeeft of GS1‑speciale tekens moeten worden gecodeerd in byte‑modus voor QR‑ en RectMicroQR‑barcode |
| [getEncodeMode()](#getencodemode) | QR‑symbooltype van de coderingsmodus van BarCode. Standaardwaarde: QREncodeMode.Auto. |
| [getErrorLevel()](#geterrorlevel) | Niveau van Reed‑Solomon‑foutcorrectie voor QR‑, MicroQR‑ en RectMicroQR‑barcode. Van laag naar hoog: LevelL, LevelM, LevelQ |
| [getMicroQRVersion()](#getmicroqrversion) | Versie van MicroQR‑code. Van versie M1 tot versie M4. Standaardwaarde is MicroQRVersion.Auto. |
| [getQrECIEncoding()](#getqreciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor |
| [getQrEncodeMode()](#getqrencodemode) | QR‑symbooltype van de coderingsmodus van BarCode. Standaardwaarde: QREncodeMode.AUTO. |
| [getQrEncodeType()](#getqrencodetype) ~~(deprecated)~~ | QR‑/MicroQR‑selectiemodus. Selecteer ForceQR voor standaard QR‑symbolen, Auto voor MicroQR. |
| [getQrErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Niveau van Reed‑Solomon‑foutcorrectie voor QR‑barcode. Van laag naar hoog: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. zie QRError |
| [getQrVersion()](#getqrversion) ~~(deprecated)~~ | Versie van QR‑code. Van Version1 tot Version40 voor QR‑code en van M1 tot M4 voor MicroQr. Standaardwaarde is QRVersion.AUT. |
| [getRectMicroQrVersion()](#getrectmicroqrversion) | Versie van RectMicroQR‑code. Van versie R7x59 tot versie R17x139. Standaardwaarde is RectMicroQRVersion.Auto. |
| [getStructuredAppend()](#getstructuredappend) | QR gestructureerde append-parameters. |
| [getVersion()](#getversion) | Versie van QR‑code. Van Version1 tot Version40. Standaardwaarde is QRVersion.Auto. |
| [setAspectRatio()](#setaspectratio) | Hoogte/breedteverhouding van 2D BarCode-module. |
| [setECIEncoding()](#seteciencoding) | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor |
| [setEncodeGS1SeparatorInByteMode(value)](#setencodegs1separatorinbytemode) | Haalt een waarde op of stelt deze in die aangeeft of GS1‑speciale tekens moeten worden gecodeerd in byte‑modus voor QR‑ en RectMicroQR‑barcode |
| [setEncodeMode()](#setencodemode) | QR‑symbooltype van de coderingsmodus van BarCode. Standaardwaarde: QREncodeMode.Auto. |
| [setErrorLevel()](#seterrorlevel) | Niveau van Reed‑Solomon‑foutcorrectie voor QR‑, MicroQR‑ en RectMicroQR‑barcode. Van laag naar hoog: LevelL, LevelM, LevelQ |
| [setMicroQRVersion()](#setmicroqrversion) | Versie van MicroQR‑code. Van versie M1 tot versie M4. Standaardwaarde is MicroQRVersion.Auto. |
| [setQrECIEncoding()](#setqreciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor |
| [setQrEncodeMode()](#setqrencodemode) ~~(deprecated)~~ | QR‑symbooltype van de coderingsmodus van BarCode. Standaardwaarde: QREncodeMode.AUTO. |
| [setQrEncodeType()](#setqrencodetype) ~~(deprecated)~~ | QR‑/MicroQR‑selectiemodus. Selecteer ForceQR voor standaard QR‑symbolen, Auto voor MicroQR. |
| [setQrErrorLevel()](#setqrerrorlevel) ~~(deprecated)~~ | Niveau van Reed‑Solomon‑foutcorrectie voor QR‑barcode. Van laag naar hoog: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. zie QRError |
| [setQrVersion()](#setqrversion) ~~(deprecated)~~ | Versie van QR‑code. Van Version1 tot Version40 voor QR‑code en van M1 tot M4 voor MicroQr. Standaardwaarde is QRVersion.AUT. |
| [setRectMicroQrVersion()](#setrectmicroqrversion) | Versie van RectMicroQR‑code. Van versie R7x59 tot versie R17x139. Standaardwaarde is RectMicroQRVersion.Auto. |
| [setStructuredAppend()](#setstructuredappend) | QR gestructureerde append-parameters. |
| [setVersion()](#setversion) | Versie van QR‑code. Van Version1 tot Version40. Standaardwaarde is QRVersion.Auto. |
| [toString()](#tostring) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze QrParameters. |

### getAspectRatio() {#getaspectratio}

Hoogte/breedteverhouding van 2D BarCode-module.

### getECIEncoding() {#geteciencoding}

Extended Channel Interpretation‑identifiers. Wordt gebruikt om de barcode‑lezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bestaat uit alle bekende tekenset‑coderingen. Niet ondersteund door MicroQR.

### getEncodeGS1SeparatorInByteMode() {#getencodegs1separatorinbytemode}

Haalt een waarde op of stelt deze in die aangeeft of GS1‑speciale tekens moeten worden gecodeerd in byte‑modus voor QR‑ en RectMicroQR‑barcodes. Indien false, kunnen GS1‑scheidingstekens worden gecodeerd als '%' in alfanumerieke modus volgens de QR‑specificatie. Indien true, worden GS1‑groepscheidingstekens gecodeerd in byte‑modus als het teken 0x1D, en worden '%'‑tekens ook gecodeerd in byte‑modus om ze als gegevens te behouden. Deze optie kan de compatibiliteit verbeteren met decoders die byte‑niveau GS1‑groepscheidingstekens verwachten en voorkomt dat '%'‑datatekens worden geïnterpreteerd als GS1‑scheidingstekens.

**Returns:** a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

### getEncodeMode() {#getencodemode}

QR‑symbooltype van de coderingsmodus van BarCode. Standaardwaarde: QREncodeMode.Auto.

### getErrorLevel() {#geterrorlevel}

Niveau van Reed‑Solomon‑foutcorrectie voor QR‑, MicroQR‑ en RectMicroQR‑barcode. Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH. Zie QRErrorLevel.

### getMicroQRVersion() {#getmicroqrversion}

Versie van MicroQR‑code. Van versie M1 tot versie M4. Standaardwaarde is MicroQRVersion.Auto.

### getQrECIEncoding() {#getqreciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bestaat uit alle bekende charset-encoderingen.

### getQrEncodeMode() {#getqrencodemode}

QR‑symbooltype van de coderingsmodus van BarCode. Standaardwaarde: QREncodeMode.AUTO.

### getQrEncodeType() {#getqrencodetype}

> **Deprecated.** See method description for replacement.

QR‑/MicroQR‑selectiemodus. Selecteer ForceQR voor standaard QR‑symbolen, Auto voor MicroQR.

### getQrErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Niveau van Reed‑Solomon‑foutcorrectie voor QR‑barcode. Van laag naar hoog: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. zie QRErrorLevel.

### getQrVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Versie van QR‑code. Van Version1 tot Version40 voor QR‑code en van M1 tot M4 voor MicroQr. Standaardwaarde is QRVersion.AUTO.

### getRectMicroQrVersion() {#getrectmicroqrversion}

Versie van RectMicroQR‑code. Van versie R7x59 tot versie R17x139. Standaardwaarde is RectMicroQRVersion.Auto.

### getStructuredAppend() {#getstructuredappend}

QR gestructureerde append-parameters.

### getVersion() {#getversion}

Versie van QR‑code. Van Version1 tot Version40. Standaardwaarde is QRVersion.Auto.

### setAspectRatio() {#setaspectratio}

Hoogte/breedteverhouding van 2D BarCode-module.

### setECIEncoding() {#seteciencoding}

Extended Channel Interpretation‑identifiers. Wordt gebruikt om de barcode‑lezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bestaat uit alle bekende tekenset‑coderingen. Niet ondersteund door MicroQR.

### setEncodeGS1SeparatorInByteMode(value) {#setencodegs1separatorinbytemode}

Haalt een waarde op of stelt deze in die aangeeft of GS1‑speciale tekens moeten worden gecodeerd in byte‑modus voor QR‑ en RectMicroQR‑barcodes. Indien false, kunnen GS1‑scheidingstekens worden gecodeerd als '%' in alfanumerieke modus volgens de QR‑specificatie. Indien true, worden GS1‑groepscheidingstekens gecodeerd in byte‑modus als het teken 0x1D, en worden '%'‑tekens ook gecodeerd in byte‑modus om ze als gegevens te behouden. Deze optie kan de compatibiliteit verbeteren met decoders die byte‑niveau GS1‑groepscheidingstekens verwachten en voorkomt dat '%'‑datatekens worden geïnterpreteerd als GS1‑scheidingstekens.

| Parameter | Beschrijving |
| --- | --- |
| waarde | een waarde die aangeeft of GS1‑speciale tekens moeten worden gecodeerd in byte‑modus voor QR‑ en RectMicroQR‑barcodes. |

### setEncodeMode() {#setencodemode}

QR‑symbooltype van de coderingsmodus van BarCode. Standaardwaarde: QREncodeMode.Auto.

### setErrorLevel() {#seterrorlevel}

Niveau van Reed‑Solomon‑foutcorrectie voor QR‑, MicroQR‑ en RectMicroQR‑barcode. Van laag naar hoog: LevelL, LevelM, LevelQ, LevelH. Zie QRErrorLevel.

### setMicroQRVersion() {#setmicroqrversion}

Versie van MicroQR‑code. Van versie M1 tot versie M4. Standaardwaarde is MicroQRVersion.Auto.

### setQrECIEncoding() {#setqreciencoding}

> **Deprecated.** See method description for replacement.

Extended Channel Interpretation Identifiers. Het wordt gebruikt om de barcodelezer details te geven over de gebruikte referenties voor het coderen van de gegevens in het symbool. De huidige implementatie bestaat uit alle bekende charset-encoderingen.

### setQrEncodeMode() {#setqrencodemode}

> **Deprecated.** See method description for replacement.

QR‑symbooltype van de coderingsmodus van BarCode. Standaardwaarde: QREncodeMode.AUTO.

### setQrEncodeType() {#setqrencodetype}

> **Deprecated.** See method description for replacement.

QR‑/MicroQR‑selectiemodus. Selecteer ForceQR voor standaard QR‑symbolen, Auto voor MicroQR.

### setQrErrorLevel() {#setqrerrorlevel}

> **Deprecated.** See method description for replacement.

Niveau van Reed‑Solomon‑foutcorrectie voor QR‑barcode. Van laag naar hoog: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. zie QRErrorLevel.

### setQrVersion() {#setqrversion}

> **Deprecated.** See method description for replacement.

Versie van QR‑code. Van Version1 tot Version40 voor QR‑code en van M1 tot M4 voor MicroQr. Standaardwaarde is QRVersion.AUTO.

### setRectMicroQrVersion() {#setrectmicroqrversion}

Versie van RectMicroQR‑code. Van versie R7x59 tot versie R17x139. Standaardwaarde is RectMicroQRVersion.Auto.

### setStructuredAppend() {#setstructuredappend}

QR gestructureerde append-parameters.

### setVersion() {#setversion}

Versie van QR‑code. Van Version1 tot Version40. Standaardwaarde is QRVersion.Auto.

### toString() {#tostring}

Retourneert een menselijk leesbare tekenreeksrepresentatie van deze QrParameters.

**Returns:** A string that represents this QrParameters.
