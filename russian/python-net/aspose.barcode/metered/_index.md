---
title: "Metered"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode/metered/
---

## Metered class

Предоставляет методы для установки измеряемого ключа.

Тип Metered раскрывает следующие члены:
## Конструкторы
| Name | Описание |
| :- | :- |
| Metered() | Инициализирует новый экземпляр класса Metered |
## Methods
| Name | Описание |
| :- | :- |
| set_metered_key(public_key, private_key) | Устанавливает публичный и приватный ключ для измеряемой лицензии.<br/>            Если вы покупаете измеряемую лицензию, при запуске приложения этот API должен быть вызван, обычно этого достаточно.<br/>            Однако, если постоянно не удаётся загрузить данные о потреблении и прошло более 24 часов, лицензия будет переведена в статус оценки,<br/>            чтобы избежать такой ситуации, следует регулярно проверять статус лицензии; если он находится в статусе оценки, вызовите этот API снова. |
| get_consumption_quantity() | Получает размер файла потребления |
| get_consumption_credit() | Получает кредит потребления |
| get_product_name() | Получает название лицензированного продукта |
| is_metered_licensed() | Проверяет, лицензирован ли metered |

### See Also

* namespace [aspose.barcode](/barcode/python-net/aspose.barcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

