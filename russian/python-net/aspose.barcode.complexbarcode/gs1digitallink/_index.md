---
title: "GS1DigitalLink"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode.complexbarcode/gs1digitallink/
---

## GS1DigitalLink class

Представляет кодовый текст GS1 Digital Link для кодирования и декодирования в виде упорядоченной последовательности<br/>            элементов идентификатора приложения. Порядок источника и повторяющиеся идентификаторы приложения сохраняются.<br/>            Сформированный кодовый текст представляет собой несжатый URI GS1 Digital Link.<br/>            При разборе игнорируются параметры запроса и фрагменты URI, не относящиеся к GS1.

Тип GS1DigitalLink раскрывает следующие члены:
## Конструкторы
| Name | Описание |
| :- | :- |
| GS1DigitalLink(uri_stem) | Инициализирует новый экземпляр класса GS1DigitalLink |
| GS1DigitalLink(uri_stem, primary_application_identifier) | Инициализирует новый экземпляр класса GS1DigitalLink |
## Properties
| Name | Описание |
| :- | :- |
| uri_stem | Получает абсолютный префикс URI перед сегментом пути первичного ключа GS1.<br/>            Стебель не содержит строку запроса или фрагмент. |
| primary_application_identifier | Получает идентификатор приложения, используемый в качестве первичного ключа Digital Link.<br/>            Null означает, что первичный ключ выбирается автоматически при построении URI. |
| barcode_type | Получает или задает тип штрихкода, используемый для кодирования этой GS1 Digital Link.<br/>            Поддерживаемые типы: QR, DataMatrix, Aztec, Pdf417, MicroPdf417, DotCode, HanXin, CodablockF и Code128.<br/>            Значение по умолчанию — QR. |
| количество | Получает количество элементов идентификатора приложения. |
| элементы | Получает копию всех элементов в исходном порядке. |
## Indexer
| Name | Описание |
| :- | :- |
| [index] | Получает элемент по его позиции в упорядоченной последовательности. |
## Methods
| Name | Описание |
| :- | :- |
| create(uri_stem, codetext) | Создаёт GS1 Digital Link, копируя все элементы из GS1 codetext и выбирая<br/>            единственный доступный основной ключ. |
| create(uri_stem, codetext, primary_application_identifier) | Создаёт GS1 Digital Link, копируя все элементы из GS1 codetext и выбирая<br/>            единственный доступный основной ключ. |
| get_first(application_identifier) | Получает первое значение для идентификатора приложения. |
| get_all(application_identifier) | Получает все значения для идентификатора приложения в исходном порядке. |
| add(application_identifier, value) | Добавляет проверенный элемент идентификатора приложения. |
| validate(value) | Проверяет несжатый GS1 Digital Link URI без создания объекта. |
| parse(value) | Разбирает несжатый GS1 Digital Link URI. |
| try_parse(value, result, validation_result) | Пытается разобрать несжатый GS1 Digital Link URI и возвращает структурированные ошибки проверки. |
| to_gs1_codetext() | Создаёт независимый GS1 codetext, содержащий текущие элементы GS1.<br/>            Информация только о URI не включена. |
| to_uri_string() | Форматирует текущее состояние объекта как несжатый GS1 Digital Link URI. |
| get_constructed_codetext() | Создаёт несжатый GS1 Digital Link URI. |
| init_from_string(constructed_codetext) | Инициализирует этот экземпляр из несжатого GS1 Digital Link URI.<br/>            Существующее состояние заменяется только после успешного разбора предоставленного URI.<br/>            Выбранный тип штрих‑кода сохраняется. |
| get_barcode_type() | Получает тип штрих‑кода, используемый для кодирования этого GS1 Digital Link. |

### See Also

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

