---
title: "Aspose::BarCode::Generation::DataMatrixParameters-klass"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::DataMatrixParameters-klass. DataMatrix-parametrar i C++."
type: docs
weight: 2000
url: /sv/cpp/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class


Parametrar för DataMatrix.

```cpp
class DataMatrixParameters : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Höjd/bredd‑förhållande för 2D‑[BarCode](../../aspose.barcode/)-modulen. |
| [get_EccType](./get_ecctype/)() const | Hämtar en Datamatrix ECC-typ. Standardvärde: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [get_ECIEncoding](./get_eciencoding/)() const | Hämtar ECI-kodning. Används när EncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Kodningsläge för Datamatrix-streckkod. Standardvärde: [EncodeMode.Auto](../aztecencodemode/). |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering. Standardvärde: false |
| [get_MacroCharacters](./get_macrocharacters/)() const | Makrotecken 05 och 06 används för att få en mer kompakt kodning i speciella lägen. Kan endast användas med [DataMatrixEccType.Ecc200](../datamatrixecctype/) eller [DataMatrixEccType.EccAuto](../datamatrixecctype/). Kan inte användas med [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) Standardvärde: [MacroCharacters.None](../barcodeclassifications/). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Streckkod-ID för strukturerat tilläggsläge för Datamatrix-streckkod. Standardvärde: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Antal streckkoder för strukturerat tilläggsläge för Datamatrix-streckkod. Standardvärde: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Fil-ID för Structured Append-läge för Datamatrix-streckkod. Standardvärde: 0 |
| [get_Version](./get_version/)() const | Hämtar en Datamatrix-symbolstorlek. Standardvärde: [Version.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Höjd/bredd‑förhållande för 2D‑[BarCode](../../aspose.barcode/)-modulen. |
| [set_EccType](./set_ecctype/)(DataMatrixEccType) | Ställer in en Datamatrix ECC-typ. Standardvärde: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Ställer in ECI-kodning. Används när EncodeMode är Auto. Standardvärde: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DataMatrixEncodeMode) | Kodningsläge för Datamatrix-streckkod. Standardvärde: [EncodeMode.Auto](../aztecencodemode/). |
| [set_IsReaderProgramming](./set_isreaderprogramming/)(bool) | Används för att instruera läsaren att tolka data som finns i symbolen som programmering för läsarinitialisering. Standardvärde: false |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Makrotecken 05 och 06 används för att få en mer kompakt kodning i speciella lägen. Kan endast användas med [DataMatrixEccType.Ecc200](../datamatrixecctype/) eller [DataMatrixEccType.EccAuto](../datamatrixecctype/). Kan inte användas med [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) Standardvärde: [MacroCharacters.None](../barcodeclassifications/). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Streckkod-ID för strukturerat tilläggsläge för Datamatrix-streckkod. Standardvärde: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Antal streckkoder för strukturerat tilläggsläge för Datamatrix-streckkod. Standardvärde: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(int32_t) | Fil-ID för Structured Append-läge för Datamatrix-streckkod. Standardvärde: 0 |
| [set_Version](./set_version/)(DataMatrixVersion) | Ställer in en Datamatrix-symbolstorlek. Standardvärde: [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Returnerar en människoläsbar strängrepresentation av detta [DataMatrixParameters](./). |
## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
