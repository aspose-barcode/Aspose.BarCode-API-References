---
title: "Methode"
linktitle: "get_AddressLine1"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Ruft die Adresszeile 1 in C++ ab."
type: docs
weight: 400
url: /de/cpp/aspose.barcode.complexbarcode/address/get_addressline1/
---
## Address::get_AddressLine1 method


Liefert die Adresszeile 1.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_AddressLine1() const
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
