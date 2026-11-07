---
title: "Aspose::BarCode::BarCodeRecognition::LuminanceFrame класс"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode для C++ справочник API"
description: "Aspose::BarCode::BarCodeRecognition::LuminanceFrame класс. Представляет 8‑битный кадр изображения в градациях серого. Каждый пиксель представлен одним байтом, содержащим его значение яркости в C++."
type: docs
weight: 2400
url: /ru/cpp/aspose.barcode.barcoderecognition/luminanceframe/
---
## LuminanceFrame class


Представляет 8‑битный кадр изображения в градациях серого. Каждый пиксель представлен одним байтом, содержащим значение его яркости.

```cpp
class LuminanceFrame : public System::Object
```

## Methods

| Method | Описание |
| --- | --- |
| [get_Data](./get_data/)() const | Получает данные яркости. |
| [get_Height](./get_height/)() const | Получает высоту кадра в пикселях. |
| [get_RotationDegrees](./get_rotationdegrees/)() const | Получает количество градусов, на которое кадр должен быть повернут по часовой стрелке для получения правильной ориентации. |
| [get_RowStride](./get_rowstride/)() const | Получает расстояние в байтах между начала двух соседних строк. |
| [get_Width](./get_width/)() const | Получает ширину кадра в пикселях. |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) | Инициализирует новый экземпляр класса [LuminanceFrame](./) без заполнения между строками. Расстояние между соседними строками равно *width*. |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) | Инициализирует новый экземпляр класса [LuminanceFrame](./) с указанным шагом строки. |
## См. также

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
