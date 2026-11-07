---
title: "Aspose::BarCode::Generation::DataMatrixParameters class"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::Generation::DataMatrixParameters class. DataMatrix‑parameters in C++."
type: docs
weight: 2000
url: /nl/cpp/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class


DataMatrix-parameters.

```cpp
class DataMatrixParameters : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Hoogte/breedte‑verhouding van 2D [BarCode](../../aspose.barcode/) module. |
| [get_EccType](./get_ecctype/)() const | Haalt een Datamatrix ECC-type op. Standaardwaarde: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [get_ECIEncoding](./get_eciencoding/)() const | Haalt ECI-codering op. Wordt gebruikt wanneer EncodeMode Auto is. Standaardwaarde: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Coderingsmodus van Datamatrix‑barcode. Standaardwaarde: [EncodeMode.Auto](../aztecencodemode/). |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. Standaardwaarde: false |
| [get_MacroCharacters](./get_macrocharacters/)() const | Macro‑tekens 05 en 06 worden gebruikt om compactere codering te verkrijgen in speciale modi. Kan alleen worden gebruikt met [DataMatrixEccType.Ecc200](../datamatrixecctype/) of [DataMatrixEccType.EccAuto](../datamatrixecctype/). Kan niet worden gebruikt met [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/). Standaardwaarde: [MacroCharacters.None](../barcodeclassifications/). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Barcode‑ID voor gestructureerde-append-modus van Datamatrix‑barcode. Standaardwaarde: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Aantal barcodes voor gestructureerde-append-modus van Datamatrix‑barcode. Standaardwaarde: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Bestands-ID voor de Structured Append-modus van de Datamatrix-barcode. Standaardwaarde: 0 |
| [get_Version](./get_version/)() const | Haalt een Datamatrix-symboolgrootte op. Standaardwaarde: [Version.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Hoogte/breedte‑verhouding van 2D [BarCode](../../aspose.barcode/) module. |
| [set_EccType](./set_ecctype/)(DataMatrixEccType) | Stelt een Datamatrix ECC-type in. Standaardwaarde: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Stelt ECI-codering in. Wordt gebruikt wanneer EncodeMode Auto is. Standaardwaarde: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DataMatrixEncodeMode) | Coderingsmodus van Datamatrix‑barcode. Standaardwaarde: [EncodeMode.Auto](../aztecencodemode/). |
| [set_IsReaderProgramming](./set_isreaderprogramming/)(bool) | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. Standaardwaarde: false |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Macro‑tekens 05 en 06 worden gebruikt om compactere codering te verkrijgen in speciale modi. Kan alleen worden gebruikt met [DataMatrixEccType.Ecc200](../datamatrixecctype/) of [DataMatrixEccType.EccAuto](../datamatrixecctype/). Kan niet worden gebruikt met [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/). Standaardwaarde: [MacroCharacters.None](../barcodeclassifications/). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Barcode‑ID voor gestructureerde-append-modus van Datamatrix‑barcode. Standaardwaarde: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Aantal barcodes voor gestructureerde-append-modus van Datamatrix‑barcode. Standaardwaarde: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(int32_t) | Bestands-ID voor de Structured Append-modus van de Datamatrix-barcode. Standaardwaarde: 0 |
| [set_Version](./set_version/)(DataMatrixVersion) | Stelt een Datamatrix-symboolgrootte in. Standaardwaarde: [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [DataMatrixParameters](./). |
## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
