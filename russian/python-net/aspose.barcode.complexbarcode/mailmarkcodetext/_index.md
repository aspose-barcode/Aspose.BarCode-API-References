---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode.complexbarcode/mailmarkcodetext/
---

## MailmarkCodetext class

Класс для кодирования и декодирования текста, встроенного в 4‑состояний код Royal Mailmark.

Тип MailmarkCodetext раскрывает следующие члены:
## Конструкторы
| Name | Описание |
| :- | :- |
| MailmarkCodetext() | Инициализирует новый экземпляр класса MailmarkCodetext |
## Properties
| Name | Описание |
| :- | :- |
| format | \"0\" – Пусто или Тест<br/>            \"1\" – Буква<br/>            \"2\" – Большая буква |
| version_id | В настоящее время \"1\" – Для штрих‑кода Mailmark (0 и 2‑9 и A‑Z зарезервированы для будущего использования) |
| klass | \"0\" - Пусто или Тест<br/>            \"1\" - 1C (Розница)<br/>            \"2\" - 2C (Розница)<br/>            \"3\" - 3C (Розница)<br/>            \"4\" - Premium (RetailPublishing Mail) (для потенциального будущего использования)<br/>            \"5\" - Deferred (Розница)<br/>            \"6\" - Air (Розница) (для потенциального будущего использования)<br/>            \"7\" - Surface (Розница) (для потенциального будущего использования)<br/>            \"8\" - Premium (Сетевой доступ)<br/>            \"9\" - Standard (Сетевой доступ) |
| supply_chain_id | Максимальные значения: 99 для Barcode C и 999999 для Barcode L. |
| item_id | Максимальное значение: 99999999. |
| destination_post_code_and_dps | PC и DP должны соответствовать формату PAF.<br/>            Девятисимвольная строка, обозначающая международный \"XY11     \" (обратите внимание на 5 завершающих пробелов) или шаблон<br/>            символов, обозначающих внутренний код сортировки.<br/>            Внутренний код сортировки состоит из внешнего почтового индекса, внутреннего почтового индекса и суффикса точки доставки. |
## Methods
| Name | Описание |
| :- | :- |
| get_constructed_codetext() | Сформировать codetext из данных Mailmark. |
| init_from_string(constructed_codetext) | Инициализирует данные Mailmark из сформированного codetext. |
| get_barcode_type() | Получает тип штрихкода. |

### See Also

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

