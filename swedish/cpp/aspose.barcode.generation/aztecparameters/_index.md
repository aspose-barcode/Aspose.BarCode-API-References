---
title: "Aspose::BarCode::Generation::AztecParameters klass"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::AztecParameters klass. Aztec‑parametrar i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class


Aztec-parametrar.

```cpp
class AztecParameters : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Höjd/bredd‑förhållande för 2D‑[BarCode](../../aspose.barcode/)-modulen. |
| [get_ECIEncoding](./get_eciencoding/)() const | Hämtar ECI‑kodning. Används när AztecEncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Hämtar ett Aztec‑kodningsläge. Standardvärde: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Nivå för felkorrigering av Aztec-typer av streckkod. Värdet bör vara mellan 5 och 95. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering. |
| [get_LayersCount](./get_layerscount/)() const | Hämtar lagerantalet för Aztec-symbolen. Lagerantalet bör ligga i intervallet 1 till 3 för kompakt läge och i intervallet 1 till 32 för fullt intervallsläge. Standardvärde: 0 (auto). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Streckkod-ID för Structured Append-läge för Aztec-streckkod. Streckkod-ID bör ligga i intervallet 1 till antalet streckkoder. Standardvärde: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Antal streckkoder för Structured Append-läge för Aztec-streckkod. Antalet streckkoder bör ligga i intervallet 1 till 26. Standardvärde: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Fil-ID för Structured Append-läge för Aztec-streckkod (valfritt fält). Fil-ID får inte innehålla mellanslag. Standardvärde: tom sträng |
| [get_SymbolMode](./get_symbolmode/)() const | Hämtar ett Aztec Symbol-läge. Standardvärde: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Höjd/bredd‑förhållande för 2D‑[BarCode](../../aspose.barcode/)-modulen. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Ställer in ECI-kodning. Används när AztecEncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(AztecEncodeMode) | Ställer in ett Aztec-kodningsläge. Standardvärde: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(int32_t) | Nivå för felkorrigering av Aztec-typer av streckkod. Värdet bör vara mellan 5 och 95. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering. |
| [set_LayersCount](./set_layerscount/)(int32_t) | Ställer in lagerantalet för Aztec-symbolen. Lagerantalet bör ligga i intervallet 1 till 3 för kompakt läge och i intervallet 1 till 32 för fullt intervallsläge. Standardvärde: 0 (auto). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Streckkod-ID för Structured Append-läge för Aztec-streckkod. Streckkod-ID bör ligga i intervallet 1 till antalet streckkoder. Standardvärde: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Antal streckkoder för Structured Append-läge för Aztec-streckkod. Antalet streckkoder bör ligga i intervallet 1 till 26. Standardvärde: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(System::String) | Fil-ID för Structured Append-läge för Aztec-streckkod (valfritt fält). Fil-ID får inte innehålla mellanslag. Standardvärde: tom sträng |
| [set_SymbolMode](./set_symbolmode/)(AztecSymbolMode) | Ställer in ett Aztec Symbol-läge. Standardvärde: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [AztecParameters](./). |
## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
