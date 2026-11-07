---
title: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class. Klasse voor het opslaan van HIBC LIC secundaire en aanvullende gegevens in C++."
type: docs
weight: 2600
url: /nl/cpp/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class


Klasse voor het opslaan van HIBC LIC secundaire en aanvullende gegevens.

```cpp
class SecondaryAndAdditionalData : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een gespecificeerde [SecondaryAndAdditionalData](./) waarde. |
| [get_DateOfManufacture](./get_dateofmanufacture/)() const | Identificeert productiedatum. Productiedatum kan worden ingesteld op DateTime.MinValue om dit veld niet te gebruiken. Standaardwaarde: DateTime.MinValue |
| [get_ExpiryDate](./get_expirydate/)() const | Identificeert vervaldatum. Wordt gebruikt als ExpiryDateFormat niet is ingesteld op None. |
| [get_ExpiryDateFormat](./get_expirydateformat/)() const | Identificeert het formaat van de vervaldatum. |
| [get_LotNumber](./get_lotnumber/)() const | Identificeert lot- of batchnummer. Lot/batchnummer moet een alfanumerieke tekenreeks zijn met een maximale lengte van 18 tekens. |
| [get_Quantity](./get_quantity/)() const | Identificeert hoeveelheid, moet een geheel getal zijn van 0 tot 500. Hoeveelheid kan worden ingesteld op -1 om dit veld niet te gebruiken. Standaardwaarde: -1 |
| [get_SerialNumber](./get_serialnumber/)() const | Identificeert serienummer. Serienummer moet een alfanumerieke tekenreeks zijn van maximaal 18 tekens. |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [ParseFromString](./parsefromstring/)(System::String) | Instantieert secundaire en aanvullende data vanuit tekenreeksformaat volgens de HIBC LIC-specificatie. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/)() |  |
| [set_DateOfManufacture](./set_dateofmanufacture/)(System::DateTime) | Identificeert productiedatum. Productiedatum kan worden ingesteld op DateTime.MinValue om dit veld niet te gebruiken. Standaardwaarde: DateTime.MinValue |
| [set_ExpiryDate](./set_expirydate/)(System::DateTime) | Identificeert vervaldatum. Wordt gebruikt als ExpiryDateFormat niet is ingesteld op None. |
| [set_ExpiryDateFormat](./set_expirydateformat/)(HIBCLICDateFormat) | Identificeert het formaat van de vervaldatum. |
| [set_LotNumber](./set_lotnumber/)(System::String) | Identificeert lot- of batchnummer. Lot/batchnummer moet een alfanumerieke tekenreeks zijn met een maximale lengte van 18 tekens. |
| [set_Quantity](./set_quantity/)(int32_t) | Identificeert hoeveelheid, moet een geheel getal zijn van 0 tot 500. Hoeveelheid kan worden ingesteld op -1 om dit veld niet te gebruiken. Standaardwaarde: -1 |
| [set_SerialNumber](./set_serialnumber/)(System::String) | Identificeert serienummer. Serienummer moet een alfanumerieke tekenreeks zijn van maximaal 18 tekens. |
| [ToString](./tostring/)() const override | Converteert gegevens naar tekenreeksformaat volgens de HIBC LIC-specificatie. |
## Zie ook

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
