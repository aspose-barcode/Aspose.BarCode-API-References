---
title: "method"
linktitle: "set_AddressLine2"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Устанавливает вторую строку адреса в C++."
type: docs
weight: 700
url: /ru/cpp/aspose.barcode.complexbarcode/address/set_addressline2/
---
## Address::set_AddressLine2 method


Устанавливает вторую строку адреса.

```cpp
void Aspose::BarCode::ComplexBarcode::Address::set_AddressLine2(System::String value)
```

## Примечания


[Address](../) line 2 contains postal code and town. 

Установка этого поля задаёт тип адреса как [AddressType::CombinedElements](../../addresstype/), если он ещё не [AddressType::Structured](../../addresstype/), в противном случае он становится [AddressType::Conflicting](../../addresstype/).

Это поле используется только для адресов с комбинированными элементами. Для этого типа оно обязательно.

Вторая строка адреса.
## См. также

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
