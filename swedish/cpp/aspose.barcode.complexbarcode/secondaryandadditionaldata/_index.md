---
title: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class. Klass för lagring av HIBC LIC sekundära och ytterligare data i C++."
type: docs
weight: 2600
url: /sv/cpp/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class


Klass för lagring av HIBC LIC sekundär och ytterligare data.

```cpp
class SecondaryAndAdditionalData : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [SecondaryAndAdditionalData](./) värde. |
| [get_DateOfManufacture](./get_dateofmanufacture/)() const | Identifierar tillverkningsdatum. Tillverkningsdatum kan sättas till DateTime.MinValue för att inte använda detta fält. Standardvärde: DateTime.MinValue |
| [get_ExpiryDate](./get_expirydate/)() const | Identifierar utgångsdatum. Används om ExpiryDateFormat inte är satt till None. |
| [get_ExpiryDateFormat](./get_expirydateformat/)() const | Identifierar format för utgångsdatum. |
| [get_LotNumber](./get_lotnumber/)() const | Identifierar parti- eller batchnummer. Parti/batch‑nummer måste vara en alfanumerisk sträng med upp till 18 tecken. . |
| [get_Quantity](./get_quantity/)() const | Identifierar kvantitet, måste vara ett heltal mellan 0 och 500. Kvantitet kan sättas till -1 för att inte använda detta fält. Standardvärde: -1 |
| [get_SerialNumber](./get_serialnumber/)() const | Identifierar serienummer. Serienummer måste vara en alfanumerisk sträng med upp till 18 tecken. |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [ParseFromString](./parsefromstring/)(System::String) | Instansierar sekundära och ytterligare kompletterande data från strängformat enligt HIBC LIC‑specifikationen. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/)() |  |
| [set_DateOfManufacture](./set_dateofmanufacture/)(System::DateTime) | Identifierar tillverkningsdatum. Tillverkningsdatum kan sättas till DateTime.MinValue för att inte använda detta fält. Standardvärde: DateTime.MinValue |
| [set_ExpiryDate](./set_expirydate/)(System::DateTime) | Identifierar utgångsdatum. Används om ExpiryDateFormat inte är satt till None. |
| [set_ExpiryDateFormat](./set_expirydateformat/)(HIBCLICDateFormat) | Identifierar format för utgångsdatum. |
| [set_LotNumber](./set_lotnumber/)(System::String) | Identifierar parti- eller batchnummer. Parti/batch‑nummer måste vara en alfanumerisk sträng med upp till 18 tecken. . |
| [set_Quantity](./set_quantity/)(int32_t) | Identifierar kvantitet, måste vara ett heltal mellan 0 och 500. Kvantitet kan sättas till -1 för att inte använda detta fält. Standardvärde: -1 |
| [set_SerialNumber](./set_serialnumber/)(System::String) | Identifierar serienummer. Serienummer måste vara en alfanumerisk sträng med upp till 18 tecken. |
| [ToString](./tostring/)() const override | Konverterar data till strängformat enligt HIBC LIC-specifikationen. |
## Se även

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
