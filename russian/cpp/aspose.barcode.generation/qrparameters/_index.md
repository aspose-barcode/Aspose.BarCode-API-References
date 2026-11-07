---
title: "Aspose::BarCode::Generation::QrParameters класс"
linktitle: "QrParameters"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::Generation::QrParameters класс. Параметры QR в C++."
type: docs
weight: 4400
url: /ru/cpp/aspose.barcode.generation/qrparameters/
---
## QrParameters class


Параметры QR.

```cpp
class QrParameters : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_AspectRatio](./get_aspectratio/)() const | Соотношение высоты к ширине 2D модуля [BarCode](../../aspose.barcode/). |
| [get_ECIEncoding](./get_eciencoding/)() const | Идентификаторы расширенной интерпретации каналов. Они используются для передачи считывателю штрих‑кода деталей о используемых ссылках для кодирования данных в символе. Текущая реализация включает все известные кодировки наборов символов. Не поддерживается MicroQR. |
| [get_EncodeGS1SeparatorInByteMode](./get_encodegs1separatorinbytemode/)() const |  |
| [get_EncodeMode](./get_encodemode/)() const | Тип символьной системы QR в режиме кодирования [BarCode](../../aspose.barcode/). Значение по умолчанию: [QREncodeMode.Auto](../aztecencodemode/). |
| [get_ErrorLevel](./get_errorlevel/)() const | Уровень коррекции ошибок Рида‑Соломона для штрих‑кодов QR, MicroQR и RectMicroQR. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH. См. QRErrorLevel. |
| [get_MicroQRVersion](./get_microqrversion/)() const | Версия MicroQR Code. От версии M1 до версии M4. Значение по умолчанию: [MicroQRVersion.Auto](../aztecencodemode/). |
| [get_RectMicroQrVersion](./get_rectmicroqrversion/)() const | Версия RectMicroQR Code. От версии R7x59 до версии R17x139. Значение по умолчанию: [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [get_StructuredAppend](./get_structuredappend/)() const | Параметры структурного добавления QR. Режим структурного добавления не поддерживается штрих‑кодами MicroQR и RectMicroQR. |
| [get_Version](./get_version/)() const | Версия QR Code. От Version1 до Version40. Значение по умолчанию: [QRVersion.Auto](../aztecencodemode/). |
| [set_AspectRatio](./set_aspectratio/)(float) | Соотношение высоты к ширине 2D модуля [BarCode](../../aspose.barcode/). |
| [set_ECIEncoding](./set_eciencoding/)(ECIEncodings) | Идентификаторы расширенной интерпретации каналов. Они используются для передачи считывателю штрих‑кода деталей о используемых ссылках для кодирования данных в символе. Текущая реализация включает все известные кодировки наборов символов. Не поддерживается MicroQR. |
| [set_EncodeGS1SeparatorInByteMode](./set_encodegs1separatorinbytemode/)(bool) |  |
| [set_EncodeMode](./set_encodemode/)(QREncodeMode) | Тип символьной системы QR в режиме кодирования [BarCode](../../aspose.barcode/). Значение по умолчанию: [QREncodeMode.Auto](../aztecencodemode/). |
| [set_ErrorLevel](./set_errorlevel/)(QRErrorLevel) | Уровень коррекции ошибок Рида‑Соломона для штрих‑кодов QR, MicroQR и RectMicroQR. От низкого к высокому: LevelL, LevelM, LevelQ, LevelH. См. QRErrorLevel. |
| [set_MicroQRVersion](./set_microqrversion/)(Aspose::BarCode::Generation::MicroQRVersion) | Версия MicroQR Code. От версии M1 до версии M4. Значение по умолчанию: [MicroQRVersion.Auto](../aztecencodemode/). |
| [set_RectMicroQrVersion](./set_rectmicroqrversion/)(RectMicroQRVersion) | Версия RectMicroQR Code. От версии R7x59 до версии R17x139. Значение по умолчанию: [RectMicroQRVersion.Auto](../aztecencodemode/). |
| [set_StructuredAppend](./set_structuredappend/)(System::SharedPtr\<QrStructuredAppendParameters\>) | Параметры структурного добавления QR. Режим структурного добавления не поддерживается штрих‑кодами MicroQR и RectMicroQR. |
| [set_Version](./set_version/)(QRVersion) | Версия QR Code. От Version1 до Version40. Значение по умолчанию: [QRVersion.Auto](../aztecencodemode/). |
| [ToString](./tostring/)() const override | Возвращает человекочитаемое строковое представление этого объекта [QrParameters](./). |
## См. также

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
