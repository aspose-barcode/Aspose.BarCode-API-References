---
title: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class"
linktitle: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class. Klasse zum Speichern von sekundären und zusätzlichen HIBC‑LIC‑Daten in C++."
type: docs
weight: 2600
url: /de/cpp/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class


Klasse zum Speichern der sekundären und zusätzlichen HIBC‑LIC‑Daten.

```cpp
class SecondaryAndAdditionalData : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [SecondaryAndAdditionalData](./)-Wert entspricht. |
| [get_DateOfManufacture](./get_dateofmanufacture/)() const | Identifiziert das Herstellungsdatum. Das Herstellungsdatum kann auf DateTime.MinValue gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: DateTime.MinValue |
| [get_ExpiryDate](./get_expirydate/)() const | Identifiziert das Ablaufdatum. Wird verwendet, wenn ExpiryDateFormat nicht auf None gesetzt ist. |
| [get_ExpiryDateFormat](./get_expirydateformat/)() const | Identifiziert das Ablaufdatumsformat. |
| [get_LotNumber](./get_lotnumber/)() const | Identifiziert Los- oder Chargennummer. Los-/Chargennummer muss eine alphanumerische Zeichenkette mit bis zu 18 Symbolen sein. |
| [get_Quantity](./get_quantity/)() const | Identifiziert die Menge, muss ein ganzzahliger Wert von 0 bis 500 sein. Menge kann auf -1 gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: -1 |
| [get_SerialNumber](./get_serialnumber/)() const | Identifiziert die Seriennummer. Seriennummer muss eine alphanumerische Zeichenkette mit bis zu 18 Symbolen sein. |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [ParseFromString](./parsefromstring/)(System::String) | Instanziiert sekundäre und zusätzliche Ergänzungsdaten aus dem Zeichenkettenformat gemäß HIBC‑LIC‑Spezifikation. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/)() |  |
| [set_DateOfManufacture](./set_dateofmanufacture/)(System::DateTime) | Identifiziert das Herstellungsdatum. Das Herstellungsdatum kann auf DateTime.MinValue gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: DateTime.MinValue |
| [set_ExpiryDate](./set_expirydate/)(System::DateTime) | Identifiziert das Ablaufdatum. Wird verwendet, wenn ExpiryDateFormat nicht auf None gesetzt ist. |
| [set_ExpiryDateFormat](./set_expirydateformat/)(HIBCLICDateFormat) | Identifiziert das Ablaufdatumsformat. |
| [set_LotNumber](./set_lotnumber/)(System::String) | Identifiziert Los- oder Chargennummer. Los-/Chargennummer muss eine alphanumerische Zeichenkette mit bis zu 18 Symbolen sein. |
| [set_Quantity](./set_quantity/)(int32_t) | Identifiziert die Menge, muss ein ganzzahliger Wert von 0 bis 500 sein. Menge kann auf -1 gesetzt werden, um dieses Feld nicht zu verwenden. Standardwert: -1 |
| [set_SerialNumber](./set_serialnumber/)(System::String) | Identifiziert die Seriennummer. Seriennummer muss eine alphanumerische Zeichenkette mit bis zu 18 Symbolen sein. |
| [ToString](./tostring/)() const override | Konvertiert Daten in das String-Format gemäß HIBC LIC-Spezifikation. |
## Siehe auch

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
