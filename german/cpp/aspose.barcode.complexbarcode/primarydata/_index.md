---
title: "Aspose::BarCode::ComplexBarcode::PrimaryData Klasse"
linktitle: "PrimaryData"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::PrimaryData Klasse. Klasse zum Speichern von HIBC LIC Primärdaten in C++."
type: docs
weight: 2500
url: /de/cpp/aspose.barcode.complexbarcode/primarydata/
---
## PrimaryData class


Klasse zum Speichern der primären HIBC‑LIC‑Daten.

```cpp
class PrimaryData : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [PrimaryData](./)-Wert entspricht. |
| [get_LabelerIdentificationCode](./get_labeleridentificationcode/)() const | Identifiziert das Datum des Kennzeichners‑Identifikationscodes. Der Kennzeichners‑Identifikationscode muss eine alphanumerische Zeichenkette aus 4 Symbolen sein, wobei das erste Zeichen immer alphabetisch sein muss. |
| [get_ProductOrCatalogNumber](./get_productorcatalognumber/)() const | Identifiziert Produkt‑ oder Katalognummer. Produkt‑ oder Katalognummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein. |
| [get_UnitOfMeasureID](./get_unitofmeasureid/)() const | Identifiziert die Einheit‑der‑Messung‑ID. Die Einheit‑der‑Messung‑ID muss ein ganzzahliger Wert von 0 bis 9 sein. |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [ParseFromString](./parsefromstring/)(System::String) | Instanziiert Primärdaten aus dem String-Format gemäß HIBC LIC-Spezifikation. |
| [PrimaryData](./primarydata/)() |  |
| [set_LabelerIdentificationCode](./set_labeleridentificationcode/)(System::String) | Identifiziert das Datum des Kennzeichners‑Identifikationscodes. Der Kennzeichners‑Identifikationscode muss eine alphanumerische Zeichenkette aus 4 Symbolen sein, wobei das erste Zeichen immer alphabetisch sein muss. |
| [set_ProductOrCatalogNumber](./set_productorcatalognumber/)(System::String) | Identifiziert Produkt‑ oder Katalognummer. Produkt‑ oder Katalognummer muss eine alphanumerische Zeichenkette mit einer Länge von bis zu 18 Symbolen sein. |
| [set_UnitOfMeasureID](./set_unitofmeasureid/)(int32_t) | Identifiziert die Einheit‑der‑Messung‑ID. Die Einheit‑der‑Messung‑ID muss ein ganzzahliger Wert von 0 bis 9 sein. |
| [ToString](./tostring/)() const override | Konvertiert Daten in das String-Format gemäß HIBC LIC-Spezifikation. |
## Siehe auch

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
