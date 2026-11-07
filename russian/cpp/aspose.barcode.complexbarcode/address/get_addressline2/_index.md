---
title: "method"
linktitle: "get_AddressLine2"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Получает вторую строку адреса в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.barcode.complexbarcode/address/get_addressline2/
---
## Address::get_AddressLine2 method


Получает вторую строку адреса.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_AddressLine2() const
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
