---
title: "Methode"
linktitle: "set_Town"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Setzt die Stadt oder Gemeinde in C++."
type: docs
weight: 1500
url: /de/cpp/aspose.barcode.complexbarcode/address/set_town/
---
## Address::set_Town method


Setzt die Stadt oder Gemeinde.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_Town(System::String value)
```

## Hinweise


Das Setzen dieses Feldes legt den Adresstyp auf [AddressType::Structured](../../addresstype/) fest, es sei denn, er ist bereits [AddressType::CombinedElements](../../addresstype/); in diesem Fall wird er zu [AddressType::Conflicting](../../addresstype/).

Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es obligatorisch.

Die Stadt oder Gemeinde.
## Siehe auch

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
