---
title: "method"
linktitle: "set_Street"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Устанавливает улицу в C++."
type: docs
weight: 900
url: /ru/cpp/aspose.barcode.complexbarcode/address/set_street/
---
## Address::set_Street method


Устанавливает улицу.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_Street(System::String value)
```

## Примечания


Улица должна быть указана без номера дома.

Установка этого поля задаёт тип адреса как [AddressType::Structured](../../addresstype/), если он ещё не [AddressType::CombinedElements](../../addresstype/), в противном случае он становится [AddressType::Conflicting](../../addresstype/).

Это поле используется только для структурированных адресов и является необязательным.

Улица.
## См. также

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
