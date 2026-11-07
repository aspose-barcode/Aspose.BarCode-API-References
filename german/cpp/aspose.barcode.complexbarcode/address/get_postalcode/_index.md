---
title: "Methode"
linktitle: "get_PostalCode"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Ruft die Postleitzahl in C++ ab."
type: docs
weight: 1200
url: /de/cpp/aspose.barcode.complexbarcode/address/get_postalcode/
---
## Address::get_PostalCode method


Liefert die Postleitzahl.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_PostalCode() const
```

## Hinweise


Das Setzen dieses Feldes legt den Adresstyp auf [AddressType::Structured](../../addresstype/) fest, es sei denn, er ist bereits [AddressType::CombinedElements](../../addresstype/); in diesem Fall wird er zu [AddressType::Conflicting](../../addresstype/).

Dieses Feld wird nur für strukturierte Adressen verwendet. Für diesen Typ ist es obligatorisch.

Die Postleitzahl.
## Siehe auch

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
