---
title: "Aspose::BarCode::Generation::MaxiCodeParameters Klasse"
linktitle: "MaxiCodeParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::MaxiCodeParameters Klasse. MaxiCode-Parameter in C++."
type: docs
weight: 3600
url: /de/cpp/aspose.barcode.generation/maxicodeparameters/
---
## MaxiCodeParameters class


MaxiCode-Parameter.

```cpp
class MaxiCodeParameters : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Höhe/Breite-Verhältnis des 2D [BarCode](../../aspose.barcode/) Moduls. |
| [get_ECIEncoding](./get_eciencoding/)() const | Ruft die ECI-Codierung ab. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto gesetzt ist. Standardwert: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Ruft einen MaxiCode-Codierungsmodus ab. Standardwert: Auto. |
| [get_Mode](./get_mode/)() const | Ruft den MaxiCode-Codierungsmodus ab. |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Ruft die MaxiCode-Barcode-ID im strukturierten Anfügemodus ab. Die ID muss ein Wert zwischen 1 und 8 sein. Standardwert: 0 |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Ruft die Anzahl der MaxiCode-Barcodes im strukturierten Anfügemodus ab. Die Zählerzahl muss ein Wert zwischen 2 und 8 (maximale Barcode-Anzahl) sein. Standardwert: -1 |
| [set_AspectRatio](./set_aspectratio/)(float) | Höhe/Breite-Verhältnis des 2D [BarCode](../../aspose.barcode/) Moduls. |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Setzt die ECI-Codierung. Wird verwendet, wenn MaxiCodeEncodeMode auf Auto gesetzt ist. Standardwert: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(MaxiCodeEncodeMode) | Setzt einen MaxiCode-Codierungsmodus. Standardwert: Auto. |
| [set_Mode](./set_mode/)(MaxiCodeMode) | Setzt einen MaxiCode-Codierungsmodus. |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | Setzt die MaxiCode-Barcode-ID im strukturierten Anfügemodus. Die ID muss ein Wert zwischen 1 und 8 sein. Standardwert: 0 |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | Setzt die Anzahl der MaxiCode-Barcodes im strukturierten Anfügemodus. Die Zählerzahl muss ein Wert zwischen 2 und 8 (maximale Barcode-Anzahl) sein. Standardwert: -1 |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [MaxiCodeParameters](./) zurück. |
## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
