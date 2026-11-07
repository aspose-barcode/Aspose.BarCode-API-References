---
title: "method"
linktitle: "get_AddressLine1"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Получает первую строку адреса в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.barcode.complexbarcode/address/get_addressline1/
---
## Address::get_AddressLine1 method


Получает первую строку адреса.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_AddressLine1() const
```

## Примечания


[Address](../) line 1 contains street name, house number or P.O. box. 

Установка этого поля задаёт тип адреса как [AddressType::CombinedElements](../../addresstype/), если он ещё не [AddressType::Structured](../../addresstype/), в противном случае он становится [AddressType::Conflicting](../../addresstype/).

Это поле используется только для адресов с комбинированными элементами и является необязательным.

Первая строка адреса.
## См. также

* Class [Address](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
