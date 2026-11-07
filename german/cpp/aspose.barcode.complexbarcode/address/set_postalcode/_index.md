---
title: "Methode"
linktitle: "set_PostalCode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Setzt die Postleitzahl in C++."
type: docs
weight: 1300
url: /de/cpp/aspose.barcode.complexbarcode/address/set_postalcode/
---
## Address::set_PostalCode method


Setzt die Postleitzahl.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_PostalCode(System::String value)
```

## Hinweise


Das Setzen dieses Feldes legt den Adresstyp auf [AddressType::Structured](../../addresstype/) fest, es sei denn, er ist bereits [AddressType::CombinedElements](../../addresstype/); in diesem Fall wird er zu [AddressType::Conflicting](../../addresstype/).

Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es obligatorisch.

Die Postleitzahl.
## Siehe auch

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
