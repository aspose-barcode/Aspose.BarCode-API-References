---
title: "Aspose::BarCode::Generation::DotCodeParameters class"
linktitle: "DotCodeParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::DotCodeParameters class. DotCode‑Parameter in C++."
type: docs
weight: 2200
url: /de/cpp/aspose.barcode.generation/dotcodeparameters/
---
## DotCodeParameters class


DotCode-Parameter.

```cpp
class DotCodeParameters : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Höhe/Breite-Verhältnis des 2D [BarCode](../../aspose.barcode/) Moduls. |
| [get_Columns](./get_columns/)() const | Identifiziert die Spaltenanzahl. Die Summe aus der Anzahl der Zeilen und der Anzahl der Spalten eines DotCode‑Symbols muss ungerade sein. Die Spaltenanzahl muss mindestens 5 betragen. Standardwert: -1 |
| [get_ECIEncoding](./get_eciencoding/)() const | Identifiziert die ECI‑Kodierung. Wird verwendet, wenn DotCodeEncodeMode auf Auto gesetzt ist. Standardwert: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Identifiziert den DotCode‑Kodierungsmodus. Standardwert: Auto. |
| [get_IsReaderInitialization](./get_isreaderinitialization/)() const | Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neuprogrammierung des Barcodelesers zu interpretieren. Standardwert ist false. |
| [get_Rows](./get_rows/)() const | Identifiziert die Zeilenanzahl. Die Summe aus der Anzahl der Zeilen und der Anzahl der Spalten eines DotCode‑Symbols muss ungerade sein. Die Zeilenanzahl muss mindestens 5 betragen. Standardwert: -1 |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Identifiziert die ID des DotCode‑Structured‑Append‑Modus‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. Standardwert ist -1. |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Identifiziert die Anzahl der Barcodes im DotCode‑Structured‑Append‑Modus. Standardwert ist -1. Die Anzahl muss ein Wert von 1 bis 35 sein. |
| [set_AspectRatio](./set_aspectratio/)(float) | Höhe/Breite-Verhältnis des 2D [BarCode](../../aspose.barcode/) Moduls. |
| [set_Columns](./set_columns/)(int32_t) | Identifiziert die Spaltenanzahl. Die Summe aus der Anzahl der Zeilen und der Anzahl der Spalten eines DotCode‑Symbols muss ungerade sein. Die Spaltenanzahl muss mindestens 5 betragen. Standardwert: -1 |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Identifiziert die ECI‑Kodierung. Wird verwendet, wenn DotCodeEncodeMode auf Auto gesetzt ist. Standardwert: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DotCodeEncodeMode) | Identifiziert den DotCode‑Kodierungsmodus. Standardwert: Auto. |
| [set_IsReaderInitialization](./set_isreaderinitialization/)(bool) | Gibt an, ob der Code verwendet wird, um den Leser anzuweisen, die folgenden Daten als Anweisungen für die Initialisierung oder Neuprogrammierung des Barcodelesers zu interpretieren. Standardwert ist false. |
| [set_Rows](./set_rows/)(int32_t) | Identifiziert die Zeilenanzahl. Die Summe aus der Anzahl der Zeilen und der Anzahl der Spalten eines DotCode‑Symbols muss ungerade sein. Die Zeilenanzahl muss mindestens 5 betragen. Standardwert: -1 |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | Identifiziert die ID des DotCode‑Structured‑Append‑Modus‑Barcodes. Die ID beginnt bei 1 und muss kleiner oder gleich der Barcode‑Anzahl sein. Standardwert ist -1. |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | Identifiziert die Anzahl der Barcodes im DotCode‑Structured‑Append‑Modus. Standardwert ist -1. Die Anzahl muss ein Wert von 1 bis 35 sein. |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [DotCodeParameters](./) zurück. |
## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
