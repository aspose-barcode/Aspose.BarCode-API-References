---
title: "BarCodeReader"
second_title: "Aspose.BarCode для Python через .NET Справочник API"
description: 
type: docs
url: /ru/python-net/aspose.barcode.barcoderecognition/barcodereader/
---

## BarCodeReader class

BarCodeReader инкапсулирует изображение, которое может содержать один или несколько штрихкодов, после чего может выполнить операцию ReadBarCodes для их обнаружения.

Тип BarCodeReader раскрывает следующие члены:
## Конструкторы
| Name | Описание |
| :- | :- |
| BarCodeReader() | Инициализирует новый экземпляр класса [BarCodeReader](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/) со значениями по умолчанию.<br/>            Требуется установить изображение (SetBitmapImage()) перед вызовом метода ReadBarCodes(). |
| BarCodeReader(image) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(image, decode_types) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(image, type) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(image, area, decode_types) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(image, area, type) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(image, areas, decode_types) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(image, areas, type) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(filename) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(filename, decode_types) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(filename, type) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(stream) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(stream, type) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(stream, decode_types) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(frame, areas, type) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(frame, areas, decode_types) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(frame, area, type) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(frame, area, decode_types) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(frame, type) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(frame, decode_types) | Инициализирует новый экземпляр класса BarCodeReader |
| BarCodeReader(frame) | Инициализирует новый экземпляр класса BarCodeReader |
## Properties
| Name | Описание |
| :- | :- |
| processor_settings | Получает настройки использования ядер процессора. |
| timeout | Получает или задает тайм-аут процесса распознавания в миллисекундах. |
| found_bar_codes | Получает массив распознанных [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/) |
| found_count | Получает количество распознанных штрихкодов |
| quality_settings | QualitySettings позволяет вручную настраивать качество распознавания и скорость.<br/>            Вы можете быстро установить QualitySettings с помощью встроенных предустановок: HighPerformance, NormalQuality, <br/>            HighQuality, MaxBarCodes или вручную настроить отдельные параметры.<br/>            Значение по умолчанию для QualitySettings — NormalQuality. |
| barcode_settings | Основные параметры декодирования BarCode. Содержит параметры, влияющие на распознанные данные. |
| bar_code_read_type | Получает или задает тип декодирования штрихкода, используемый для распознавания.<br/>            Должен быть установлен до вызова [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
## Methods
| Name | Описание |
| :- | :- |
| set_bar_code_image(value) | Устанавливает растровое изображение для распознавания. <br/>            Должен вызываться до метода ReadBarCodes(). |
| set_bar_code_image(value, areas) | Устанавливает растровое изображение и области для распознавания. <br/>            Должен вызываться до метода ReadBarCodes(). |
| set_bar_code_image(value, area) | Устанавливает растровое изображение и области для распознавания. <br/>            Должен вызываться до метода ReadBarCodes(). |
| set_bar_code_image(filename) | Устанавливает файл изображения для распознавания. <br/>            Должен вызываться до метода ReadBarCodes(). |
| set_bar_code_image(stream) | Устанавливает поток изображения для распознавания. <br/>            Должен вызываться до метода ReadBarCodes(). |
| set_bar_code_image(frame, area) | Устанавливает кадр яркости и область для распознавания. Должен вызываться до метода [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| set_bar_code_image(frame, areas) | Устанавливает кадр яркости и области для распознавания. Должен вызываться до метода [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| set_bar_code_image(frame) | Устанавливает кадр яркости и область для распознавания. Должен вызываться до метода [None](/barcode/python-net/aspose.barcode.barcoderecognition/barcodereader/). |
| export_to_xml(xml_file) | Экспортирует свойства BarCode в указанный xml‑файл |
| export_to_xml(xml_stream) | Экспортирует свойства BarCode в указанный xml‑поток |
| import_from_xml(xml_file) | Импортирует свойства BarCode из указанного xml‑файла и применяет их к текущему экземпляру BarCodeReader. |
| import_from_xml(xml_stream) | Импортирует свойства BarCode из указанного xml‑потока и применяет их к текущему экземпляру BarCodeReader. |
| abort() | Функция запрашивает завершение текущей сессии распознавания из другого потока. Abort — метод, который нельзя заблокировать, и он возвращает управление сразу после вызова. <br/>            Метод следует использовать, когда процесс распознавания занимает слишком много времени. |
| read_bar_codes() | Читает [BarCodeResult](/barcode/python-net/aspose.barcode.barcoderecognition/barcoderesult/)s из изображения. |
| set_bar_code_read_type(barcode_types) | Устанавливает массив типа [SingleDecodeType](/barcode/python-net/aspose.barcode.barcoderecognition/singledecodetype/) для распознавания. <br/>            Должен быть вызван до метода ReadBarCodes(). |

### See Also

* namespace [aspose.barcode.barcoderecognition](/barcode/python-net/aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](/barcode/python-net/)

