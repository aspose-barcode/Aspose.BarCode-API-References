---
title: "Methode"
linktitle: "get_AddressLine2"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Ruft die Adresszeile 2 in C++ ab."
type: docs
weight: 600
url: /de/cpp/aspose.barcode.complexbarcode/address/get_addressline2/
---
## Address::get_AddressLine2 method


Liefert die Adresszeile 2.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_AddressLine2() const
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
