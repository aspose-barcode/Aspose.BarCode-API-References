---
title: "Aspose::BarCode::Generation::AztecParameters Klasse"
linktitle: "AztecParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::AztecParameters Klasse. Aztec-Parameter in C++."
type: docs
weight: 300
url: /de/cpp/aspose.barcode.generation/aztecparameters/
---
## AztecParameters class


Aztec-Parameter.

```cpp
class AztecParameters : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Höhe/Breite-Verhältnis des 2D [BarCode](../../aspose.barcode/) Moduls. |
| [get_ECIEncoding](./get_eciencoding/)() const | Ermittelt die ECI-Codierung. Wird verwendet, wenn AztecEncodeMode auf Auto steht. Standardwert: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Ermittelt einen Aztec‑Kodiermodus. Standardwert: Auto. |
| [get_ErrorLevel](./get_errorlevel/)() const | Fehlerkorrekturstufe der Aztec‑Barcode‑Typen. Der Wert sollte zwischen 5 und 95 liegen. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [get_LayersCount](./get_layerscount/)() const | Ermittelt die Ebenenzahl des Aztec‑Symbols. Die Ebenenzahl sollte im Bereich von 1 bis 3 für den kompakten Modus und im Bereich von 1 bis 32 für den Vollbereichsmodus liegen. Standardwert: 0 (auto). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Barcode‑ID für den Structured‑Append‑Modus des Aztec‑Barcodes. Die Barcode‑ID sollte im Bereich von 1 bis zur Anzahl der Barcodes liegen. Standardwert: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Anzahl der Barcodes für den Structured‑Append‑Modus des Aztec‑Barcodes. Die Barcode‑Anzahl sollte im Bereich von 1 bis 26 liegen. Standardwert: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Datei‑ID für den Structured‑Append‑Modus des Aztec‑Barcodes (optional). Die Datei‑ID darf keine Leerzeichen enthalten. Standardwert: leerer String |
| [get_SymbolMode](./get_symbolmode/)() const | Ermittelt einen Aztec‑Symbol‑Modus. Standardwert: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Höhe/Breite-Verhältnis des 2D [BarCode](../../aspose.barcode/) Moduls. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Legt die ECI‑Kodierung fest. Wird verwendet, wenn AztecEncodeMode auf Auto steht. Standardwert: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(AztecEncodeMode) | Legt einen Aztec‑Kodiermodus fest. Standardwert: Auto. |
| [set_ErrorLevel](./set_errorlevel/)(int32_t) | Fehlerkorrekturstufe der Aztec‑Barcode‑Typen. Der Wert sollte zwischen 5 und 95 liegen. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. |
| [set_LayersCount](./set_layerscount/)(int32_t) | Legt die Ebenenzahl des Aztec‑Symbols fest. Die Ebenenzahl sollte im Bereich von 1 bis 3 für den kompakten Modus und im Bereich von 1 bis 32 für den Vollbereichsmodus liegen. Standardwert: 0 (auto). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Barcode‑ID für den Structured‑Append‑Modus des Aztec‑Barcodes. Die Barcode‑ID sollte im Bereich von 1 bis zur Anzahl der Barcodes liegen. Standardwert: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Anzahl der Barcodes für den Structured‑Append‑Modus des Aztec‑Barcodes. Die Barcode‑Anzahl sollte im Bereich von 1 bis 26 liegen. Standardwert: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(System::String) | Datei‑ID für den Structured‑Append‑Modus des Aztec‑Barcodes (optional). Die Datei‑ID darf keine Leerzeichen enthalten. Standardwert: leerer String |
| [set_SymbolMode](./set_symbolmode/)(AztecSymbolMode) | Legt einen Aztec‑Symbol‑Modus fest. Standardwert: [AztecSymbolMode.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [AztecParameters](./) zurück. |
## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
