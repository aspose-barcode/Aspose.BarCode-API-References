---
title: "BarcodeGenerator"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode.generation/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator для генерации изображений штрихкодов на сервере.

Тип BarcodeGenerator раскрывает следующие члены:
## Конструкторы
| Name | Описание |
| :- | :- |
| BarcodeGenerator(type) | Инициализирует новый экземпляр класса BarcodeGenerator |
| BarcodeGenerator(type, code_text) | Инициализирует новый экземпляр класса BarcodeGenerator |
## Properties
| Name | Описание |
| :- | :- |
| параметры | Параметры генерации. |
| barcode_type | Тип символьного набора штрихкода. |
| code_text | Текст для кодирования. |
## Methods
| Name | Описание |
| :- | :- |
| set_code_text(code_bytes) | Устанавливает кодовый текст как последовательность байтов. |
| set_code_text(code_text, encoding) |  |
| set_code_text(code_text, encoding, insert_bom) |  |
| save(stream, format) | Сохраняет изображение штрихкода в поток в указанном формате. |
| save(filename, format) | Сохраняет изображение штрихкода в указанный файл в указанном формате. |
| save(filename) | Сохраняет изображение штрихкода в указанный файл в указанном формате. |
| export_to_xml(xml_file) | Экспортирует свойства BarCode в указанный xml‑файл |
| export_to_xml(xml) | Экспортирует свойства BarCode в указанный xml‑поток |
| import_from_xml(xml_file) | Импортирует свойства BarCode из указанного XML‑файла и создает экземпляр BarcodeGenerator. |
| import_from_xml(xml) | Импортирует свойства BarCode из указанного XML‑потока и создает экземпляр BarcodeGenerator. |
| generate_bar_code_image() | Создает изображение штрихкода с текущими настройками. |

### See Also

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

