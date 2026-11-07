---
title: "конструктор"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode для C++ справочник API"
description: " конструктор. Инициализирует новый экземпляр класса LuminanceFrame без отступов между строками. Расстояние между соседними строками равно ширине в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) constructor


Инициализирует новый экземпляр класса [LuminanceFrame](../) без отступов между строками. Расстояние между соседними строками равно *width* .

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rotationDegrees=0)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Данные яркости, содержащие один байт на пиксель. |
| width | int32_t | Ширина кадра в пикселях. |
| height | int32_t | Высота кадра в пикселях. |
| rotationDegrees | int32_t | Поворот по часовой стрелке, необходимый для отображения кадра в вертикальном положении. Поддерживаемые значения: 0, 90, 180 и 270. Значение по умолчанию: 0. |

## См. также

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) constructor


Инициализирует новый экземпляр класса [LuminanceFrame](../) с указанным шагом строки.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rowStride, int32_t rotationDegrees)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Данные яркости, содержащие один байт на пиксель. |
| width | int32_t | Ширина кадра в пикселях. |
| height | int32_t | Высота кадра в пикселях. |
| rowStride | int32_t | Расстояние в байтах между началами двух соседних строк. Значение не может быть меньше *width* . |
| rotationDegrees | int32_t | По часовой стрелке вращение, необходимое для отображения кадра в вертикальном положении. Поддерживаемые значения: 0, 90, 180 и 270. |

## См. также

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
