---
title: "Methode"
linktitle: "get_Street"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " method. Liefert die Straße in C++."
type: docs
weight: 800
url: /de/cpp/aspose.barcode.complexbarcode/address/get_street/
---
## Address::get_Street method


Liefert die Straße.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_Street() const
```

## Hinweise


Die Straße muss ohne Hausnummer angegeben werden.

Das Setzen dieses Feldes legt den Adresstyp auf [AddressType::Structured](../../addresstype/) fest, es sei denn, er ist bereits [AddressType::CombinedElements](../../addresstype/); in diesem Fall wird er zu [AddressType::Conflicting](../../addresstype/).

Dieses Feld wird nur für strukturierte Adressen verwendet und ist optional.

Die Straße.
## Siehe auch

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
