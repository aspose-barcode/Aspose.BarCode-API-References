---
title: "Aspose::BarCode::Metered класс"
linktitle: "Счётный"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::Metered класс. Предоставляет методы для установки счётного ключа в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.barcode/metered/
---
## Metered class


Предоставляет методы для установки измеряемого ключа.

```cpp
class Metered : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | Получает кредит потребления |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | Получает размер файла потребления |
| [GetProductName](./getproductname/)() | Получает название лицензированного продукта |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | Проверьте, лицензирован ли счётный |
| [Metered](./metered/)() | Инициализирует новый экземпляр этого класса. |
| [SetMeteredKey](./setmeteredkey/)(System::String, System::String) | Устанавливает публичный и приватный счётный ключ. Если вы покупаете счётную лицензию, при запуске приложения этот API должен быть вызван, обычно этого достаточно. Однако, если постоянно не удаётся загрузить данные потребления и прошло более 24 часов, лицензия будет переведена в статус оценки; чтобы избежать этого, следует регулярно проверять статус лицензии, и если он находится в статусе оценки, вызвать этот API снова. |
## Примечания


В этом примере будет предпринята попытка установить публичный и приватный счётный ключ

<ms>
```cpp
[C#]
@verbatim
Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
@endverbatim
```
</ms>

<java> файл jar компонента:
```cpp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```
</java>
## См. также

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
