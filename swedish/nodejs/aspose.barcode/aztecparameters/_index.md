---
title: "AztecParameters"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode för Node.js via Java API-referens"
description: "Aztec‑parametrar."
type: docs
weight: 70
url: /sv/nodejs/aspose.barcode/aztecparameters/
---

## AztecParameters class

Aztec‑parametrar.

```js
new AztecParameters()
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Höjd/bredd-förhållande för 2D-streckkodmodul. |
| [getAztecEncodeMode()](#getaztecencodemode) ~~(deprecated)~~ | Hämtar ett Aztec-kodningsläge. Standardvärde: Auto. |
| [getAztecErrorLevel()](#getaztecerrorlevel) ~~(deprecated)~~ | Nivå för felkorrigering av Aztec-typ av streckkod. Värdet bör vara mellan 5 och 95. |
| [getAztecSymbolMode()](#getaztecsymbolmode) ~~(deprecated)~~ | Hämtar ett Aztec-symbolläge. Standardvärde: AztecSymbolMode.Auto. |
| [getECIEncoding()](#geteciencoding) | Hämtar ECI-kodning. Används när AztecEncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Hämtar ett Aztec-kodningsläge. Standardvärde: Auto. |
| [getErrorLevel()](#geterrorlevel) | Nivå för felkorrigering av Aztec-typ av streckkod. Värdet bör vara mellan 5 och 95. |
| [getLayersCount()](#getlayerscount) | Hämtar antalet lager för Aztec-symbolen. Lagerantalet bör ligga i intervallet 1 till 3 för kompaktläge och i intervallet 1 till 3 |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Streckkod-ID för Structured Append-läge i Aztec-streckkod. Streckkod-ID bör ligga i intervallet 1 till antalet streckkoder. Standard |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Antal streckkoder för Structured Append-läge för Aztec-streckkod. Antalet streckkoder bör vara i intervallet 1 till 26. Standardvärde |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Fil-ID för Structured Append-läge för Aztec-streckkod (valfritt fält). Fil-ID får inte innehålla mellanslag. Standardvärde: |
| [getSymbolMode()](#getsymbolmode) | Hämtar ett Aztec-symbolläge. Standardvärde: AztecSymbolMode.Auto. |
| [isReaderInitialization()](#isreaderinitialization) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering. |
| [setAspectRatio()](#setaspectratio) | Höjd/bredd-förhållande för 2D-streckkodmodul. |
| [setAztecEncodeMode()](#setaztecencodemode) ~~(deprecated)~~ | Ställer in ett Aztec-kodningsläge. Standardvärde: Auto. |
| [setAztecErrorLevel()](#setaztecerrorlevel) ~~(deprecated)~~ | Nivå för felkorrigering av Aztec-typ av streckkod. Värdet bör vara mellan 5 och 95. |
| [setAztecSymbolMode()](#setaztecsymbolmode) ~~(deprecated)~~ | Ställer in ett Aztec-symbolläge. Standardvärde: AztecSymbolMode.Auto. |
| [setECIEncoding()](#seteciencoding) | Ställer in ECI-kodning. Används när AztecEncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [setEncodeMode(value)](#setencodemode) | Ställer in ett Aztec-kodningsläge. Standardvärde: Auto. |
| [setErrorLevel()](#seterrorlevel) | Nivå för felkorrigering av Aztec-typ av streckkod. Värdet bör vara mellan 5 och 95. |
| [setLayersCount()](#setlayerscount) | Ställer in lagerantal för Aztec-symbol. Lagerantalet bör vara i intervallet 1 till 3 för Compact-läge och i intervallet 1 till 3 |
| [setReaderInitialization()](#setreaderinitialization) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering. |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | Streckkod-ID för Structured Append-läge i Aztec-streckkod. Streckkod-ID bör ligga i intervallet 1 till antalet streckkoder. Standard |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | Antal streckkoder för Structured Append-läge för Aztec-streckkod. Antalet streckkoder bör vara i intervallet 1 till 26. Standardvärde |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | Fil-ID för Structured Append-läge för Aztec-streckkod (valfritt fält). Fil-ID får inte innehålla mellanslag. Standardvärde: |
| [setSymbolMode(value)](#setsymbolmode) | Ställer in ett Aztec-symbolläge. Standardvärde: AztecSymbolMode.Auto. |
| [toString()](#tostring) | Returnerar en människoläsbar strängrepresentation av detta `AztecParameters`. |

### getAspectRatio() {#getaspectratio}

Höjd/bredd-förhållande för 2D-streckkodmodul.

### getAztecEncodeMode() {#getaztecencodemode}

> **Deprecated.** See method description for replacement.

Hämtar ett Aztec-kodningsläge. Standardvärde: Auto.

### getAztecErrorLevel() {#getaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Nivå för felkorrigering av Aztec-typ av streckkod. Värdet bör vara mellan 5 och 95.

### getAztecSymbolMode() {#getaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Hämtar ett Aztec-symbolläge. Standardvärde: AztecSymbolMode.Auto.

### getECIEncoding() {#geteciencoding}

Hämtar ECI-kodning. Används när AztecEncodeMode är Auto. Standardvärde: ISO-8859-1

### getEncodeMode() {#getencodemode}

Hämtar ett Aztec-kodningsläge. Standardvärde: Auto.

**Returns:** a Aztec encode mode.

### getErrorLevel() {#geterrorlevel}

Nivå för felkorrigering av Aztec-typ av streckkod. Värdet bör vara mellan 5 och 95.

### getLayersCount() {#getlayerscount}

Hämtar lagerantal för Aztec-symbol. Lagerantalet bör vara i intervallet 1 till 3 för Compact-läge och i intervallet 1 till 32 för Full Range-läge. Standardvärde: 0 (auto).

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Streckkod-ID för Structured Append-läge för Aztec-streckkod. Streckkod-ID bör vara i intervallet 1 till antalet streckkoder. Standardvärde: 0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Antal streckkoder för Structured Append-läge för Aztec-streckkod. Antalet streckkoder bör vara i intervallet 1 till 26. Standardvärde: 0

### getStructuredAppendFileId() {#getstructuredappendfileid}

Fil-ID för Structured Append-läge för Aztec-streckkod (valfritt fält). Fil-ID får inte innehålla mellanslag. Standardvärde: tom sträng

### getSymbolMode() {#getsymbolmode}

Hämtar ett Aztec-symbolläge. Standardvärde: AztecSymbolMode.Auto.

**Returns:** a Aztec Symbol mode.

### isReaderInitialization() {#isreaderinitialization}

Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering.

### setAspectRatio() {#setaspectratio}

Höjd/bredd-förhållande för 2D-streckkodmodul.

### setAztecEncodeMode() {#setaztecencodemode}

> **Deprecated.** See method description for replacement.

Ställer in ett Aztec-kodningsläge. Standardvärde: Auto.

### setAztecErrorLevel() {#setaztecerrorlevel}

> **Deprecated.** See method description for replacement.

Nivå för felkorrigering av Aztec-typ av streckkod. Värdet bör vara mellan 5 och 95.

### setAztecSymbolMode() {#setaztecsymbolmode}

> **Deprecated.** See method description for replacement.

Ställer in ett Aztec-symbolläge. Standardvärde: AztecSymbolMode.Auto.

### setECIEncoding() {#seteciencoding}

Ställer in ECI-kodning. Används när AztecEncodeMode är Auto. Standardvärde: ISO-8859-1

### setEncodeMode(value) {#setencodemode}

Ställer in ett Aztec-kodningsläge. Standardvärde: Auto.

| Parameter | Beskrivning |
| --- | --- |
| värde | ett Aztec-kodningsläge. |

### setErrorLevel() {#seterrorlevel}

Nivå för felkorrigering av Aztec-typ av streckkod. Värdet bör vara mellan 5 och 95.

### setLayersCount() {#setlayerscount}

Ställer in lagerantal för Aztec-symbol. Lagerantalet bör vara i intervallet 1 till 3 för Compact-läge och i intervallet 1 till 32 för Full Range-läge. Standardvärde: 0 (auto).

### setReaderInitialization() {#setreaderinitialization}

Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering.

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

Streckkod-ID för Structured Append-läge för Aztec-streckkod. Streckkod-ID bör vara i intervallet 1 till antalet streckkoder. Standardvärde: 0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

Antal streckkoder för Structured Append-läge för Aztec-streckkod. Antalet streckkoder bör vara i intervallet 1 till 26. Standardvärde: 0

### setStructuredAppendFileId() {#setstructuredappendfileid}

Fil-ID för Structured Append-läge för Aztec-streckkod (valfritt fält). Fil-ID får inte innehålla mellanslag. Standardvärde: tom sträng

### setSymbolMode(value) {#setsymbolmode}

Ställer in ett Aztec-symbolläge. Standardvärde: AztecSymbolMode.Auto.

| Parameter | Beskrivning |
| --- | --- |
| värde | ett Aztec-symbolläge. |

### toString() {#tostring}

Returnerar en människoläsbar strängrepresentation av detta `AztecParameters`.

**Returns:** A string that represents this `AztecParameters`.
