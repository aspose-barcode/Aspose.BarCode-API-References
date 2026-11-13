---
title: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

Базовый класс для кодирования и декодирования текста, встроенного в код MaxiCode для режимов 2 и 3.

Тип MaxiCodeStructuredCodetext раскрывает следующие члены:
## Properties
| Name | Описание |
| :- | :- |
| encode_mode | Получает или задает режим кодирования MaxiCode. <br/>            Значение по умолчанию: Auto. |
| eci_encoding | Получает или задает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto.<br/>            Значение по умолчанию: ISO-8859-1 |
| postal_code | Определяет почтовый индекс. Должен быть 9 цифр в режиме 2 или <br/>            6 буквенно-цифровых символов в режиме 3. |
| country_code | Определяет 3-значный код страны. |
| service_category | Определяет 3-значную категорию сервиса. |
| second_message | Определяет второе сообщение штрих-кода. |
## Methods
| Name | Описание |
| :- | :- |
| get_mode() | Получает режим MaxiCode. |
| get_constructed_codetext() | Создаёт кодовый текст |
| init_from_string(constructed_codetext) | Инициализирует экземпляр из построенного кодового текста. |
| get_barcode_type() | Получает тип штрихкода. |

### See Also

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

