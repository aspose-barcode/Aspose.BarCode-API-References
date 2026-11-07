---
title: "method"
linktitle: "get_Street"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Получает улицу в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.barcode.complexbarcode/address/get_street/
---
## Address::get_Street method


Получает улицу.

```cpp
System::String Aspose::BarCode::ComplexBarcode::Address::get_Street() const
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
