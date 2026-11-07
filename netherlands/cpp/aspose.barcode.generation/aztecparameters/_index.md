---
title: "Aspose::BarCode::Generation::AztecParameters klasse"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::Generation::AztecParameters klasse. Aztec‑parameters in C++."
type: docs
weight: 300
url: /nl/cpp/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class


Aztec-parameters.

```cpp
class AztecParameters : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Hoogte/breedte‑verhouding van 2D [BarCode](../../aspose.barcode/) module. |
| [get_ECIEncoding](./get_eciencoding/)() const | Haalt ECI‑codering op. Wordt gebruikt wanneer AztecEncodeMode Auto is. Standaardwaarde: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Haalt een Aztec‑encode‑modus op. Standaardwaarde: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Niveau van foutcorrectie van Aztec-type barcodes. Waarde moet tussen 5 en 95 liggen. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. |
| [get_LayersCount](./get_layerscount/)() const | Haalt het aantal lagen van het Aztec-symbool op. Aantal lagen moet liggen tussen 1 en 3 voor Compact-modus en tussen 1 en 32 voor Full Range-modus. Standaardwaarde: 0 (auto). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Barcode-ID voor Structured Append-modus van Aztec-barcode. Barcode-ID moet liggen tussen 1 en het aantal barcodes. Standaardwaarde: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Aantal barcodes voor Structured Append-modus van Aztec-barcode. Aantal barcodes moet liggen tussen 1 en 26. Standaardwaarde: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Bestands-ID voor Structured Append-modus van Aztec-barcode (optioneel veld). Bestands-ID mag geen spaties bevatten. Standaardwaarde: lege tekenreeks |
| [get_SymbolMode](./get_symbolmode/)() const | Haalt een Aztec Symbol-modus op. Standaardwaarde: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Hoogte/breedte‑verhouding van 2D [BarCode](../../aspose.barcode/) module. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Stelt ECI-codering in. Wordt gebruikt wanneer AztecEncodeMode Auto is. Standaardwaarde: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(AztecEncodeMode) | Stelt een Aztec-coderingmodus in. Standaardwaarde: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(int32_t) | Niveau van foutcorrectie van Aztec-type barcodes. Waarde moet tussen 5 en 95 liggen. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Wordt gebruikt om de lezer te instrueren de gegevens in het symbool te interpreteren als programmering voor lezerinitialisatie. |
| [set_LayersCount](./set_layerscount/)(int32_t) | Stelt het aantal lagen van het Aztec-symbool in. Aantal lagen moet liggen tussen 1 en 3 voor Compact-modus en tussen 1 en 32 voor Full Range-modus. Standaardwaarde: 0 (auto). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Barcode-ID voor Structured Append-modus van Aztec-barcode. Barcode-ID moet liggen tussen 1 en het aantal barcodes. Standaardwaarde: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Aantal barcodes voor Structured Append-modus van Aztec-barcode. Aantal barcodes moet liggen tussen 1 en 26. Standaardwaarde: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(System::String) | Bestands-ID voor Structured Append-modus van Aztec-barcode (optioneel veld). Bestands-ID mag geen spaties bevatten. Standaardwaarde: lege tekenreeks |
| [set_SymbolMode](./set_symbolmode/)(AztecSymbolMode) | Stelt een Aztec Symbol-modus in. Standaardwaarde: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [AztecParameters](./). |
## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
