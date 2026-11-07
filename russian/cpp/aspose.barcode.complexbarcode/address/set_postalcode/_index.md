---
title: "method"
linktitle: "set_PostalCode"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Устанавливает почтовый индекс в C++."
type: docs
weight: 1300
url: /ru/cpp/aspose.barcode.complexbarcode/address/set_postalcode/
---
## Address::set_PostalCode method


Устанавливает почтовый индекс.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_PostalCode(System::String value)
```

## Примечания


Установка этого поля задаёт тип адреса как [AddressType::Structured](../../addresstype/), если он ещё не [AddressType::CombinedElements](../../addresstype/), в противном случае он становится [AddressType::Conflicting](../../addresstype/).

Это поле используется только для структурированных адресов. Для этого типа оно обязательно.

Почтовый индекс.
## См. также

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
