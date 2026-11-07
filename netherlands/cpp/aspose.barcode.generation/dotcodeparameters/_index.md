---
title: "Aspose::BarCode::Generation::DotCodeParameters klasse"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::Generation::DotCodeParameters klasse. DotCode‑parameters in C++."
type: docs
weight: 2200
url: /nl/cpp/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class


DotCode-parameters.

```cpp
class DotCodeParameters : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Hoogte/breedte‑verhouding van 2D [BarCode](../../aspose.barcode/) module. |
| [get_Columns](./get_columns/)() const | Identificeert het aantal kolommen. De som van het aantal rijen plus het aantal kolommen van een DotCode‑symbool moet oneven zijn. Het aantal kolommen moet minimaal 5 zijn. Standaardwaarde: -1 |
| [get_ECIEncoding](./get_eciencoding/)() const | Identificeert de ECI‑codering. Wordt gebruikt wanneer DotCodeEncodeMode op Auto staat. Standaardwaarde: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Identificeert de DotCode‑codeermodus. Standaardwaarde: Auto. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Geeft aan of de code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false. |
| [get_Rows](./get_rows/)() const | Identificeert het aantal rijen. De som van het aantal rijen plus het aantal kolommen van een DotCode‑symbool moet oneven zijn. Het aantal rijen moet minimaal 5 zijn. Standaardwaarde: -1 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Identificeert de ID van de DotCode‑structured‑append‑modus barcode. De ID begint bij 1 en moet kleiner dan of gelijk aan het aantal barcodes zijn. Standaardwaarde is -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Identificeert het aantal barcodes in de DotCode‑structured‑append‑modus. Standaardwaarde is -1. Het aantal moet een waarde tussen 1 en 35 zijn. |
| [set_AspectRatio](./set_aspectratio/)(float) | Hoogte/breedte‑verhouding van 2D [BarCode](../../aspose.barcode/) module. |
| [set_Columns](./set_columns/)(int32_t) | Identificeert het aantal kolommen. De som van het aantal rijen plus het aantal kolommen van een DotCode‑symbool moet oneven zijn. Het aantal kolommen moet minimaal 5 zijn. Standaardwaarde: -1 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Identificeert de ECI‑codering. Wordt gebruikt wanneer DotCodeEncodeMode op Auto staat. Standaardwaarde: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DotCodeEncodeMode) | Identificeert de DotCode‑codeermodus. Standaardwaarde: Auto. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Geeft aan of de code wordt gebruikt om de lezer te instrueren de volgende gegevens te interpreteren als instructies voor initialisatie of herprogrammering van de barcodelezer. Standaardwaarde is false. |
| [set_Rows](./set_rows/)(int32_t) | Identificeert het aantal rijen. De som van het aantal rijen plus het aantal kolommen van een DotCode‑symbool moet oneven zijn. Het aantal rijen moet minimaal 5 zijn. Standaardwaarde: -1 |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | Identificeert de ID van de DotCode‑structured‑append‑modus barcode. De ID begint bij 1 en moet kleiner dan of gelijk aan het aantal barcodes zijn. Standaardwaarde is -1. |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | Identificeert het aantal barcodes in de DotCode‑structured‑append‑modus. Standaardwaarde is -1. Het aantal moet een waarde tussen 1 en 35 zijn. |
| [ToString](./tostring/)() const override | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze [DotCodeParameters](./). |
## Zie ook

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
