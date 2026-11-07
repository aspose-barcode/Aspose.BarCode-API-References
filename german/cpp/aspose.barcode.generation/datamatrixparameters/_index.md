---
title: "Aspose::BarCode::Generation::DataMatrixParameters Klasse"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::DataMatrixParameters Klasse. DataMatrix-Parameter in C++."
type: docs
weight: 2000
url: /de/cpp/aspose.barcode.generation/datamatrixparameters/
---
## DataMatrixParameters class


DataMatrix-Parameter.

```cpp
class DataMatrixParameters : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Höhe/Breite-Verhältnis des 2D [BarCode](../../aspose.barcode/) Moduls. |
| [get_EccType](./get_ecctype/)() const | Ruft einen DataMatrix ECC‑Typ ab. Standardwert: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [get_ECIEncoding](./get_eciencoding/)() const | Ruft die ECI‑Kodierung ab. Wird verwendet, wenn EncodeMode auf Auto steht. Standardwert: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Kodierungsmodus des DataMatrix‑Barcodes. Standardwert: [EncodeMode.Auto](../aztecencodemode/). |
| [get_IsReaderProgramming](./get_isreaderprogramming/)() const | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. Standardwert: false |
| [get_MacroCharacters](./get_macrocharacters/)() const | Die Werte der Makrozeichen 05 und 06 werden verwendet, um in Sondermodi eine kompaktere Kodierung zu erhalten. Können nur mit [DataMatrixEccType.Ecc200](../datamatrixecctype/) oder [DataMatrixEccType.EccAuto](../datamatrixecctype/) verwendet werden. Können nicht mit [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) verwendet werden. Standardwert: [MacroCharacters.None](../barcodeclassifications/). |
| [get_StructuredAppendBarcodeId](./get_structuredappendbarcodeid/)() const | Barcode‑ID für den Structured Append‑Modus des DataMatrix‑Barcodes. Standardwert: 0 |
| [get_StructuredAppendBarcodesCount](./get_structuredappendbarcodescount/)() const | Anzahl der Barcodes für den Structured Append‑Modus des Datamatrix‑Barcodes. Standardwert: 0 |
| [get_StructuredAppendFileId](./get_structuredappendfileid/)() const | Datei‑ID für den Structured Append‑Modus des Datamatrix‑Barcodes. Standardwert: 0 |
| [get_Version](./get_version/)() const | Ermittelt eine Datamatrix‑Symbolgröße. Standardwert: [Version.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Höhe/Breite-Verhältnis des 2D [BarCode](../../aspose.barcode/) Moduls. |
| [set_EccType](./set_ecctype/)(DataMatrixEccType) | Legt einen Datamatrix‑ECC‑Typ fest. Standardwert: [DataMatrixEccType.Ecc200](../datamatrixecctype/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Legt die ECI‑Kodierung fest. Wird verwendet, wenn EncodeMode auf Auto steht. Standardwert: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(DataMatrixEncodeMode) | Kodierungsmodus des DataMatrix‑Barcodes. Standardwert: [EncodeMode.Auto](../aztecencodemode/). |
| [set_IsReaderProgramming](./set_isreaderprogramming/)(bool) | Wird verwendet, um den Leser anzuweisen, die im Symbol enthaltenen Daten als Programmierung für die Leserinitialisierung zu interpretieren. Standardwert: false |
| [set_MacroCharacters](./set_macrocharacters/)(MacroCharacter) | Die Werte der Makrozeichen 05 und 06 werden verwendet, um in Sondermodi eine kompaktere Kodierung zu erhalten. Können nur mit [DataMatrixEccType.Ecc200](../datamatrixecctype/) oder [DataMatrixEccType.EccAuto](../datamatrixecctype/) verwendet werden. Können nicht mit [EncodeTypes.GS1DataMatrix](../encodetypes/gs1datamatrix/) verwendet werden. Standardwert: [MacroCharacters.None](../barcodeclassifications/). |
| [set_StructuredAppendBarcodeId](./set_structuredappendbarcodeid/)(int32_t) | Barcode‑ID für den Structured Append‑Modus des DataMatrix‑Barcodes. Standardwert: 0 |
| [set_StructuredAppendBarcodesCount](./set_structuredappendbarcodescount/)(int32_t) | Anzahl der Barcodes für den Structured Append‑Modus des Datamatrix‑Barcodes. Standardwert: 0 |
| [set_StructuredAppendFileId](./set_structuredappendfileid/)(int32_t) | Datei‑ID für den Structured Append‑Modus des Datamatrix‑Barcodes. Standardwert: 0 |
| [set_Version](./set_version/)(DataMatrixVersion) | Legt eine Datamatrix‑Symbolgröße fest. Standardwert: [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Gibt eine menschenlesbare Zeichenkettenrepräsentation dieses [DataMatrixParameters](./) zurück. |
## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
