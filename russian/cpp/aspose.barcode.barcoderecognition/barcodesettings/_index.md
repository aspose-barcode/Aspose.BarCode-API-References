---
title: "Класс Aspose::BarCode::BarCodeRecognition::BarcodeSettings"
linktitle: "BarcodeSettings"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Класс Aspose::BarCode::BarCodeRecognition::BarcodeSettings. Основные параметры декодирования штрихкода. Содержит параметры, влияющие на распознанные данные в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.barcode.barcoderecognition/barcodesettings/
---
## BarcodeSettings class


Основные параметры декодирования [BarCode](../../aspose.barcode/). Содержит параметры, влияющие на распознанные данные.

```cpp
class BarcodeSettings : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_AustraliaPost](./get_australiapost/)() const | Получает параметры декодирования AustraliaPost |
| [get_CalculateSymbolQuality](./get_calculatesymbolquality/)() const | Получает значение, указывающее, следует ли вычислять качество символа штрихкода во время распознавания. |
| [get_ChecksumValidation](./get_checksumvalidation/)() const |  |
| [get_DetectEncoding](./get_detectencoding/)() const | Флаг, заставляющий движок определять кодировку текста кода для наборов Unicode. Значение по умолчанию — true. |
| [get_OnlyRequestedTypes](./get_onlyrequestedtypes/)() const | Возвращает только типы штрихкодов, явно указанные для распознавания. При включении распознанные штрихкоды других совместимых или эквивалентных типов отфильтровываются. Значение по умолчанию — false. |
| [get_StripFNC](./get_stripfnc/)() const | Удалять символы FNC1, FNC2, FNC3 из текста кода. Значение по умолчанию — false. |
| [set_CalculateSymbolQuality](./set_calculatesymbolquality/)(bool) | Устанавливает значение, указывающее, следует ли вычислять качество символа штрихкода во время распознавания. |
| [set_ChecksumValidation](./set_checksumvalidation/)(Aspose::BarCode::BarCodeRecognition::ChecksumValidation) |  |
| [set_DetectEncoding](./set_detectencoding/)(bool) | Флаг, заставляющий движок определять кодировку текста кода для наборов Unicode. Значение по умолчанию — true. |
| [set_OnlyRequestedTypes](./set_onlyrequestedtypes/)(bool) | Возвращает только типы штрихкодов, явно указанные для распознавания. При включении распознанные штрихкоды других совместимых или эквивалентных типов отфильтровываются. Значение по умолчанию — false. |
| [set_StripFNC](./set_stripfnc/)(bool) | Удалять символы FNC1, FNC2, FNC3 из текста кода. Значение по умолчанию — false. |
## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
