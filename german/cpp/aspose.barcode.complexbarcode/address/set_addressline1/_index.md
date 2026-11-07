---
title: "Methode"
linktitle: "set_AddressLine1"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Setzt die Adresszeile 1 in C++."
type: docs
weight: 500
url: /de/cpp/aspose.barcode.complexbarcode/address/set_addressline1/
---
## Address::set_AddressLine1 method


Setzt die Adresszeile 1.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine1(System::String value)
```

## Hinweise


[Address](../) line 1 contains street name, house number or P.O. box. 

Das Setzen dieses Feldes legt den Adresstyp auf [AddressType::CombinedElements](../../addresstype/) fest, es sei denn, er ist bereits [AddressType::Structured](../../addresstype/); in diesem Fall wird er zu [AddressType::Conflicting](../../addresstype/).

Dieses Feld wird nur für Adressen mit kombinierten Elementen verwendet und ist optional.

Die Adresszeile 1.
## Siehe auch

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
