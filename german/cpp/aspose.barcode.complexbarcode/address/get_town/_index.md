---
title: "Methode"
linktitle: "get_Town"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. Liefert die Stadt oder Gemeinde in C++."
type: docs
weight: 1400
url: /de/cpp/aspose.barcode.complexbarcode/address/get_town/
---
## Address::get_Town method


Liefert die Stadt oder Gemeinde.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_Town() const
```

## Hinweise


Das Setzen dieses Feldes legt den Adresstyp auf [AddressType::Structured](../../addresstype/) fest, es sei denn, er ist bereits [AddressType::CombinedElements](../../addresstype/); in diesem Fall wird er zu [AddressType::Conflicting](../../addresstype/).

Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es obligatorisch.

Die Stadt oder Gemeinde.
## Siehe auch

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
