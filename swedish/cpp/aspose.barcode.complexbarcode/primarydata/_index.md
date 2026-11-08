---
title: "Aspose::BarCode::ComplexBarcode::PrimaryData klass"
linktitle: "PrimaryData"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::PrimaryData klass. Klass för lagring av HIBC LIC primärdata i C++."
type: docs
weight: 2500
url: /sv/cpp/aspose.barcode.complexbarcode/primarydata/
---
## PrimaryData class


Klass för lagring av HIBC LIC primärdata.

```cpp
class PrimaryData : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [PrimaryData](./)-värde. |
| [get_LabelerIdentificationCode](./get_labeleridentificationcode/)() const | Identifierar datum för etikettens identifieringskod. Identifieringskoden måste vara en alfanumerisk sträng med 4 tecken, där det första tecknet alltid är alfabetiskt. |
| [get_ProductOrCatalogNumber](./get_productorcatalognumber/)() const | Identifierar produkt- eller katalognummer. Produkt- eller katalognumret måste vara en alfanumerisk sträng med upp till 18 tecken. |
| [get_UnitOfMeasureID](./get_unitofmeasureid/)() const | Identifierar enhetens måttenhet-ID. Måttenhet-ID måste vara ett heltal mellan 0 och 9. |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [ParseFromString](./parsefromstring/)(System::String) | Instansierar primärdata från strängformat enligt HIBC LIC-specifikationen. |
| [PrimaryData](./primarydata/)() |  |
| [set_LabelerIdentificationCode](./set_labeleridentificationcode/)(System::String) | Identifierar datum för etikettens identifieringskod. Identifieringskoden måste vara en alfanumerisk sträng med 4 tecken, där det första tecknet alltid är alfabetiskt. |
| [set_ProductOrCatalogNumber](./set_productorcatalognumber/)(System::String) | Identifierar produkt- eller katalognummer. Produkt- eller katalognumret måste vara en alfanumerisk sträng med upp till 18 tecken. |
| [set_UnitOfMeasureID](./set_unitofmeasureid/)(int32_t) | Identifierar enhetens måttenhet-ID. Måttenhet-ID måste vara ett heltal mellan 0 och 9. |
| [ToString](./tostring/)() const override | Konverterar data till strängformat enligt HIBC LIC-specifikationen. |
## Se även

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
