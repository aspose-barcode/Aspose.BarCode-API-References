---
title: "Methode"
linktitle: "set_Street"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Setzt die Straße in C++."
type: docs
weight: 900
url: /de/cpp/aspose.barcode.complexbarcode/address/set_street/
---
## Address::set_Street method


Setzt die Straße.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_Street(System::String value)
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
