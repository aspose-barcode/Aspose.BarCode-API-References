---
title: "Methode"
linktitle: "set_AddressLine2"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Setzt die Adresszeile 2 in C++."
type: docs
weight: 700
url: /de/cpp/aspose.barcode.complexbarcode/address/set_addressline2/
---
## Address::set_AddressLine2 method


Setzt die Adresszeile 2.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine2(System::String value)
```

## Hinweise


[Address](../) line 2 contains postal code and town. 

Das Setzen dieses Feldes legt den Adresstyp auf [AddressType::CombinedElements](../../addresstype/) fest, es sei denn, er ist bereits [AddressType::Structured](../../addresstype/); in diesem Fall wird er zu [AddressType::Conflicting](../../addresstype/).

Dieses Feld wird nur für Adressen mit kombinierten Elementen verwendet. Für diesen Typ ist es obligatorisch.

Die Adresszeile 2.
## Siehe auch

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
