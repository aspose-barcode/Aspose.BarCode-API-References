---
title: "Mailmark2DCodetext"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

Класс для кодирования и декодирования текста, встроенного в код Royal Mail 2D Mailmark.

Тип Mailmark2DCodetext раскрывает следующие члены:
## Конструкторы
| Name | Описание |
| :- | :- |
| Mailmark2DCodetext() | Инициализирует новый экземпляр класса Mailmark2DCodetext |
## Properties
| Name | Описание |
| :- | :- |
| upu_country_id | Определяет идентификатор страны UPU. Максимальная длина: 4 символа. |
| information_type_id | Определяет полезную нагрузку штрих‑кода Royal Mail Mailmark для каждого типа продукта. |
| version_id | Определяет версию штрих‑кода, соответствующую каждому идентификатору типа информации. |
| klass | Определяет класс элемента. |
| supply_chain_id | Определяет уникальную группу клиентов, участвующих в рассылке.<br/>            Максимальное значение: 9999999. |
| item_id | Определяет уникальный элемент в рамках идентификатора цепочки поставок.<br/>            Каждый штрих‑код Mailmark должен содержать идентификатор<br/>            чтобы его можно было уникально идентифицировать минимум 90 дней.<br/>            Максимальное значение: 99999999. |
| destination_post_code_and_dps | Содержит почтовый индекс адреса доставки с DPS<br/>            Если внутри страны, почтовый индекс/DP содержит следующее количество символов.<br/>            Область (1 или 2 символа) Район (1 или 2 символа)<br/>            Сектор (1 символ) Подразделение (2 символа) DPS (2 символа).<br/>            Почтовый индекс и DPS должны соответствовать действительному формату PAF®. |
| rts_flag | Флаг, указывающий, какой уровень услуги возврата отправителю запрашивается. |
| return_to_sender_post_code | Содержит почтовый код возврата отправителю, но без DPS.<br/>            Почтовый код (без DPS) должен соответствовать формату PAF®. |
| customer_content | Необязательное пространство для использования клиентом. |
| customer_content_encode_mode | Режим кодирования штрих‑кода Datamatrix.<br/>            Значение по умолчанию: EncodeMode.C40. |
| data_matrix_type | Тип 2D Mailmark определяет размер штрих‑кода Data Matrix. |
## Methods
| Name | Описание |
| :- | :- |
| get_constructed_codetext() | Сформировать codetext из данных Mailmark. |
| init_from_string(constructed_codetext) | Инициализирует данные Mailmark из сформированного codetext. |
| get_barcode_type() | Получает тип штрихкода. |

### See Also

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

