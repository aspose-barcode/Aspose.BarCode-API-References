---
title: "Aspose::BarCode::Generation::MaxiCodeParameters класс"
linktitle: "MaxiCodeParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::Generation::MaxiCodeParameters класс. Параметры MaxiCode в C++."
type: docs
weight: 3600
url: /ru/cpp/aspose.barcode.generation/maxicodeparameters/
---
## MaxiCodeParameters class


Параметры MaxiCode.

```cpp
class MaxiCodeParameters : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Соотношение высоты к ширине 2D модуля [BarCode](../../aspose.barcode/). |
| [get_ECIEncoding](./get_eciencoding/)() const | Получает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [get_EncodeMode](./get_encodemode/)() const | Получает режим кодирования MaxiCode. Значение по умолчанию: Auto. |
| [get_Mode](./get_mode/)() const | Получает режим кодирования MaxiCode. |
| [get_StructuredAppendModeBarcodeId](./get_structuredappendmodebarcodeid/)() const | Получает идентификатор штрих‑кода MaxiCode в режиме структурного добавления. ID должно быть значением от 1 до 8. Значение по умолчанию: 0 |
| [get_StructuredAppendModeBarcodesCount](./get_structuredappendmodebarcodescount/)() const | Получает количество штрих‑кодов MaxiCode в режиме структурного добавления. Число должно быть значением от 2 до 8 (максимальное количество штрих‑кодов). Значение по умолчанию: -1 |
| [set_AspectRatio](./set_aspectratio/)(float) | Соотношение высоты к ширине 2D модуля [BarCode](../../aspose.barcode/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Устанавливает кодировку ECI. Используется, когда MaxiCodeEncodeMode установлен в Auto. Значение по умолчанию: ISO-8859-1 |
| [set_EncodeMode](./set_encodemode/)(MaxiCodeEncodeMode) | Устанавливает режим кодирования MaxiCode. Значение по умолчанию: Auto. |
| [set_Mode](./set_mode/)(MaxiCodeMode) | Устанавливает режим кодирования MaxiCode. |
| [set_StructuredAppendModeBarcodeId](./set_structuredappendmodebarcodeid/)(int32_t) | Устанавливает идентификатор штрих‑кода MaxiCode в режиме структурного добавления. ID должно быть значением от 1 до 8. Значение по умолчанию: 0 |
| [set_StructuredAppendModeBarcodesCount](./set_structuredappendmodebarcodescount/)(int32_t) | Устанавливает количество штрих‑кодов MaxiCode в режиме структурного добавления. Число должно быть значением от 2 до 8 (максимальное количество штрих‑кодов). Значение по умолчанию: -1 |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [MaxiCodeParameters](./). |
## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
