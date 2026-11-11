---
title: "LuminanceFrame.LuminanceFrame"
second_title: "Справочник API Aspose.BarCode для .NET"
description: "Конструктор LuminanceFrame. Инициализирует новый экземпляр класса LuminanceFrame без отступов между строками. Расстояние между соседними строками равно ширине."
type: docs
weight: 10
url: /ru/net/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame(byte[], int, int, int) {#constructor}

Инициализирует новый экземпляр класса [`LuminanceFrame`](../) без отступов между строками. Расстояние между соседними строками равно *width*.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rotationDegrees = 0)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | Byte[] | Данные яркости, содержащие один байт на пиксель. |
| width | Int32 | Ширина кадра в пикселях. |
| height | Int32 | Высота кадра в пикселях. |
| rotationDegrees | Int32 | Поворот по часовой стрелке, необходимый для отображения кадра в правильном положении. Поддерживаемые значения: 0, 90, 180 и 270. Значение по умолчанию — 0. |

### См. также

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## LuminanceFrame(byte[], int, int, int, int) {#constructor_1}

Инициализирует новый экземпляр класса [`LuminanceFrame`](../) с указанным шагом строки.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rowStride, int rotationDegrees)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| data | Byte[] | Данные яркости, содержащие один байт на пиксель. |
| width | Int32 | Ширина кадра в пикселях. |
| height | Int32 | Высота кадра в пикселях. |
| rowStride | Int32 | Расстояние в байтах между началом двух соседних строк. Значение не может быть меньше *width*. |
| rotationDegrees | Int32 | Поворот по часовой стрелке, необходимый для отображения кадра в правильном положении. Поддерживаемые значения: 0, 90, 180 и 270. |

### См. также

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


