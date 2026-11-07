---
title: "класс Aspose::BarCode::Generation::HanXinParameters"
linktitle: "HanXinParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "класс Aspose::BarCode::Generation::HanXinParameters. Параметры Han Xin на C++."
type: docs
weight: 2900
url: /ru/cpp/aspose.barcode.generation/hanxinparameters/
---
## HanXinParameters class


Параметры Han Xin.

```cpp
class HanXinParameters : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_ECIEncoding](./get_eciencoding/)() const | Идентификаторы расширенной интерпретации каналов. Они используются, чтобы сообщить считывателю штрихкода детали о используемых ссылках для кодирования данных в символе. Текущая реализация содержит все известные кодировки набора символов. |
| [get_EncodeMode](./get_encodemode/)() const | Режим кодирования HanXin. Значение по умолчанию: EncodeMode.Mixed. |
| [get_ErrorLevel](./get_errorlevel/)() const | Уровень коррекции ошибок Рида–Соломона для штрихкода Han Xin. От низкого к высокому: L1, L2, L3, L4. см. ErrorLevel. |
| [get_Version](./get_version/)() const | Версия кода HanXin. От Version01 до Version84 для кода Han Xin. Значение по умолчанию — [Version.Auto](../aztecencodemode/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Идентификаторы расширенной интерпретации каналов. Они используются, чтобы сообщить считывателю штрихкода детали о используемых ссылках для кодирования данных в символе. Текущая реализация содержит все известные кодировки набора символов. |
| [set_EncodeMode](./set_encodemode/)(HanXinEncodeMode) | Режим кодирования HanXin. Значение по умолчанию: EncodeMode.Mixed. |
| [set_ErrorLevel](./set_errorlevel/)(HanXinErrorLevel) | Уровень коррекции ошибок Рида–Соломона для штрихкода Han Xin. От низкого к высокому: L1, L2, L3, L4. см. ErrorLevel. |
| [set_Version](./set_version/)(HanXinVersion) | Версия кода HanXin. От Version01 до Version84 для кода Han Xin. Значение по умолчанию — [Version.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого [HanXinParameters](./). |
## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
