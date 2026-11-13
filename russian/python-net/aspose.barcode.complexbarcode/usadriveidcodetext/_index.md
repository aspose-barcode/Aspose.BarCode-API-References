---
title: "USADriveIdCodetext"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

Класс для кодирования и декодирования текста, встроенного в код PDF417 водительского удостоверения США.

Тип USADriveIdCodetext раскрывает следующие члены:
## Конструкторы
| Name | Описание |
| :- | :- |
| USADriveIdCodetext() | Инициализирует новый экземпляр класса USADriveIdCodetext |
## Properties
| Name | Описание |
| :- | :- |
| issuer_identification_number | Этот номер уникально идентифицирует <br/>            юрисдикцию-эмитент и может быть получен путем обращения к ISO<br/>            Органу выдачи (AAMVA). Полный 6-значный IIN должен быть закодирован. |
| aamva_version_number | Номер версии AAMVA 00-99 |
| jurisdiction_version_number | Номер версии юрисдикции 00-99 |
| number_of_entries | Число 00-99 подпфайлов |
| subfile_designator | Содержит информацию о следующих подпфайлах, типах, смещениях и длинах. <br/>            Важно: задайте только тип, смещение и длину, остальные будут установлены автоматически. |
| mandatory_elements | Обязательные элементы (поля) карты |
| optional_elements | Опциональные элементы (поля) карты |
| jurisdiction_specific_subfile | Поля, специфичные для юрисдикции |
## Methods
| Name | Описание |
| :- | :- |
| get_constructed_codetext() | Создать кодовый текст из данных водительского удостоверения США |
| init_from_string(constructed_codetext) | Инициализировать объект водительского удостоверения США из кодового текста |
| get_barcode_type() | Возвращает тип штрихкода водительского удостоверения США (Pdf417) |
| save_to_xml(stream) | Сохраняет в XML |

### See Also

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

