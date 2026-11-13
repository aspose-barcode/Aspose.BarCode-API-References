---
title: "QrParameters"
linktitle: "QrParameters"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "QR-parametrar."
type: docs
weight: 830
url: /sv/nodejs/aspose.barcode/qrparameters/
---

## QrParameters class

QR-parametrar.

```js
new QrParameters()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Höjd/bredd-förhållande för 2D-streckkodmodul. |
| [getECIEncoding()](#geteciencoding) | Extended Channel Interpretation Identifierare. Det används för att informera streckkodsläsaren om detaljer kring de använda referenserna för |
| [getEncodeGS1SeparatorInByteMode()](#getencodegs1separatorinbytemode) | Hämtar eller anger ett värde som indikerar om GS1-specialtecken ska kodas i byte-läge för QR- och RectMicroQR-streckkod |
| [getEncodeMode()](#getencodemode) | QR-symbologi-typ för BarCode:s kodningsläge. Standardvärde: QREncodeMode.Auto. |
| [getErrorLevel()](#geterrorlevel) | Nivå för Reed-Solomon-felkorrigering för QR-, MicroQR- och RectMicroQR-streckkod. Från låg till hög: LevelL, LevelM, LevelQ |
| [getMicroQRVersion()](#getmicroqrversion) | Version av MicroQR-kod. Från version M1 till version M4. Standardvärde är MicroQRVersion.Auto. |
| [getQrECIEncoding()](#getqreciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifierare. Det används för att informera streckkodsläsaren om detaljer kring de använda referenserna för |
| [getQrEncodeMode()](#getqrencodemode) | QR-symbologi-typ för BarCode:s kodningsläge. Standardvärde: QREncodeMode.AUTO. |
| [getQrEncodeType()](#getqrencodetype) ~~(deprecated)~~ | QR / MicroQR-väljarläge. Välj ForceQR för standard QR-symboler, Auto för MicroQR. |
| [getQrErrorLevel()](#getqrerrorlevel) ~~(deprecated)~~ | Nivå för Reed-Solomon-felkorrigering för QR-streckkod. Från låg till hög: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. se QRError |
| [getQrVersion()](#getqrversion) ~~(deprecated)~~ | Version av QR-kod. Från Version1 till Version40 för QR-kod och från M1 till M4 för MicroQr. Standardvärde är QRVersion.AUT |
| [getRectMicroQrVersion()](#getrectmicroqrversion) | Version av RectMicroQR-kod. Från version R7x59 till version R17x139. Standardvärde är RectMicroQRVersion.Auto. |
| [getStructuredAppend()](#getstructuredappend) | QR Structured Append‑parametrar. |
| [getVersion()](#getversion) | Version av QR-kod. Från Version1 till Version40. Standardvärde är QRVersion.Auto. |
| [setAspectRatio()](#setaspectratio) | Höjd/bredd-förhållande för 2D-streckkodmodul. |
| [setECIEncoding()](#seteciencoding) | Extended Channel Interpretation Identifierare. Det används för att informera streckkodsläsaren om detaljer kring de använda referenserna för |
| [setEncodeGS1SeparatorInByteMode(value)](#setencodegs1separatorinbytemode) | Hämtar eller anger ett värde som indikerar om GS1-specialtecken ska kodas i byte-läge för QR- och RectMicroQR-streckkod |
| [setEncodeMode()](#setencodemode) | QR-symbologi-typ för BarCode:s kodningsläge. Standardvärde: QREncodeMode.Auto. |
| [setErrorLevel()](#seterrorlevel) | Nivå för Reed-Solomon-felkorrigering för QR-, MicroQR- och RectMicroQR-streckkod. Från låg till hög: LevelL, LevelM, LevelQ |
| [setMicroQRVersion()](#setmicroqrversion) | Version av MicroQR-kod. Från version M1 till version M4. Standardvärde är MicroQRVersion.Auto. |
| [setQrECIEncoding()](#setqreciencoding) ~~(deprecated)~~ | Extended Channel Interpretation Identifierare. Det används för att informera streckkodsläsaren om detaljer kring de använda referenserna för |
| [setQrEncodeMode()](#setqrencodemode) ~~(deprecated)~~ | QR-symbologi-typ för BarCode:s kodningsläge. Standardvärde: QREncodeMode.AUTO. |
| [setQrEncodeType()](#setqrencodetype) ~~(deprecated)~~ | QR / MicroQR-väljarläge. Välj ForceQR för standard QR-symboler, Auto för MicroQR. |
| [setQrErrorLevel()](#setqrerrorlevel) ~~(deprecated)~~ | Nivå för Reed-Solomon-felkorrigering för QR-streckkod. Från låg till hög: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. se QRError |
| [setQrVersion()](#setqrversion) ~~(deprecated)~~ | Version av QR-kod. Från Version1 till Version40 för QR-kod och från M1 till M4 för MicroQr. Standardvärde är QRVersion.AUT |
| [setRectMicroQrVersion()](#setrectmicroqrversion) | Version av RectMicroQR-kod. Från version R7x59 till version R17x139. Standardvärde är RectMicroQRVersion.Auto. |
| [setStructuredAppend()](#setstructuredappend) | QR Structured Append‑parametrar. |
| [setVersion()](#setversion) | Version av QR-kod. Från Version1 till Version40. Standardvärde är QRVersion.Auto. |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av denna QrParameters. |

### getAspectRatio() {#getaspectratio}

Höjd/bredd-förhållande för 2D-streckkodmodul.

### getECIEncoding() {#geteciencoding}

Utökade kanalinterpretationsidentifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Aktuell implementation består av alla välkända teckenkodningar. Stöds inte av MicroQR.

### getEncodeGS1SeparatorInByteMode() {#getencodegs1separatorinbytemode}

Hämtar eller anger ett värde som indikerar om GS1-specialtecken ska kodas i byte-läge för QR- och RectMicroQR-streckkoder. Om falskt kan GS1-separatorer kodas som '%' i alfanumeriskt läge enligt QR-specifikationen. Om sant kodas GS1-gruppseparatorer i byte-läge som tecknet 0x1D, och '%'‑tecken kodas också i byte-läge för att bevara dem som data. Detta alternativ kan förbättra kompatibiliteten med avkodare som förväntar sig byte-nivå GS1-gruppseparatorer och förhindrar att '%'‑datatecken tolkas som GS1-separatorer.

**Returns:** a value indicating whether GS1 special characters should be encoded in Byte mode for QR and RectMicroQR barcodes.

### getEncodeMode() {#getencodemode}

QR-symbologi-typ för BarCode:s kodningsläge. Standardvärde: QREncodeMode.Auto.

### getErrorLevel() {#geterrorlevel}

Nivå för Reed-Solomon-felkorrigering för QR-, MicroQR- och RectMicroQR-streckkod. Från låg till hög: LevelL, LevelM, LevelQ, LevelH. Se QRErrorLevel.

### getMicroQRVersion() {#getmicroqrversion}

Version av MicroQR-kod. Från version M1 till version M4. Standardvärde är MicroQRVersion.Auto.

### getQrECIEncoding() {#getqreciencoding}

> **Deprecated.** See method description for replacement.

Utökade kanalinterpretationsidentifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Nuvarande implementation består av alla välkända teckenkodningsuppsättningar.

### getQrEncodeMode() {#getqrencodemode}

QR-symbologi-typ för BarCode:s kodningsläge. Standardvärde: QREncodeMode.AUTO.

### getQrEncodeType() {#getqrencodetype}

> **Deprecated.** See method description for replacement.

QR / MicroQR-väljarläge. Välj ForceQR för standard QR-symboler, Auto för MicroQR.

### getQrErrorLevel() {#getqrerrorlevel}

> **Deprecated.** See method description for replacement.

Nivå för Reed-Solomon-felkorrigering för QR-streckkod. Från låg till hög: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. se QRErrorLevel.

### getQrVersion() {#getqrversion}

> **Deprecated.** See method description for replacement.

Version av QR-kod. Från Version1 till Version40 för QR-kod och från M1 till M4 för MicroQr. Standardvärde är QRVersion.AUTO.

### getRectMicroQrVersion() {#getrectmicroqrversion}

Version av RectMicroQR-kod. Från version R7x59 till version R17x139. Standardvärde är RectMicroQRVersion.Auto.

### getStructuredAppend() {#getstructuredappend}

QR Structured Append‑parametrar.

### getVersion() {#getversion}

Version av QR-kod. Från Version1 till Version40. Standardvärde är QRVersion.Auto.

### setAspectRatio() {#setaspectratio}

Höjd/bredd-förhållande för 2D-streckkodmodul.

### setECIEncoding() {#seteciencoding}

Utökade kanalinterpretationsidentifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Aktuell implementation består av alla välkända teckenkodningar. Stöds inte av MicroQR.

### setEncodeGS1SeparatorInByteMode(value) {#setencodegs1separatorinbytemode}

Hämtar eller anger ett värde som indikerar om GS1-specialtecken ska kodas i byte-läge för QR- och RectMicroQR-streckkoder. Om falskt kan GS1-separatorer kodas som '%' i alfanumeriskt läge enligt QR-specifikationen. Om sant kodas GS1-gruppseparatorer i byte-läge som tecknet 0x1D, och '%'‑tecken kodas också i byte-läge för att bevara dem som data. Detta alternativ kan förbättra kompatibiliteten med avkodare som förväntar sig byte-nivå GS1-gruppseparatorer och förhindrar att '%'‑datatecken tolkas som GS1-separatorer.

| Parameter | Beskrivning |
| --- | --- |
| värde | ett värde som indikerar om GS1-specialtecken ska kodas i byte-läge för QR- och RectMicroQR-streckkoder. |

### setEncodeMode() {#setencodemode}

QR-symbologi-typ för BarCode:s kodningsläge. Standardvärde: QREncodeMode.Auto.

### setErrorLevel() {#seterrorlevel}

Nivå för Reed-Solomon-felkorrigering för QR-, MicroQR- och RectMicroQR-streckkod. Från låg till hög: LevelL, LevelM, LevelQ, LevelH. Se QRErrorLevel.

### setMicroQRVersion() {#setmicroqrversion}

Version av MicroQR-kod. Från version M1 till version M4. Standardvärde är MicroQRVersion.Auto.

### setQrECIEncoding() {#setqreciencoding}

> **Deprecated.** See method description for replacement.

Utökade kanalinterpretationsidentifierare. Den används för att informera streckkodsläsaren om detaljer kring de använda referenserna för kodning av data i symbolen. Nuvarande implementation består av alla välkända teckenkodningsuppsättningar.

### setQrEncodeMode() {#setqrencodemode}

> **Deprecated.** See method description for replacement.

QR-symbologi-typ för BarCode:s kodningsläge. Standardvärde: QREncodeMode.AUTO.

### setQrEncodeType() {#setqrencodetype}

> **Deprecated.** See method description for replacement.

QR / MicroQR-väljarläge. Välj ForceQR för standard QR-symboler, Auto för MicroQR.

### setQrErrorLevel() {#setqrerrorlevel}

> **Deprecated.** See method description for replacement.

Nivå för Reed-Solomon-felkorrigering för QR-streckkod. Från låg till hög: LEVEL_L, LEVEL_M, LEVEL_Q, LEVEL_H. se QRErrorLevel.

### setQrVersion() {#setqrversion}

> **Deprecated.** See method description for replacement.

Version av QR-kod. Från Version1 till Version40 för QR-kod och från M1 till M4 för MicroQr. Standardvärde är QRVersion.AUTO.

### setRectMicroQrVersion() {#setrectmicroqrversion}

Version av RectMicroQR-kod. Från version R7x59 till version R17x139. Standardvärde är RectMicroQRVersion.Auto.

### setStructuredAppend() {#setstructuredappend}

QR Structured Append‑parametrar.

### setVersion() {#setversion}

Version av QR-kod. Från Version1 till Version40. Standardvärde är QRVersion.Auto.

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av denna QrParameters.

**Returns:** A string that represents this QrParameters.
