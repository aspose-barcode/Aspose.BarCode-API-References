---
title: "constructor"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " constructor. Inicializa una nueva instancia de la clase LuminanceFrame sin relleno entre filas. La distancia entre filas adyacentes es igual a width en C++."
type: docs
weight: 600
url: /es/cpp/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) constructor


Inicializa una nueva instancia de la clase [LuminanceFrame](../) sin relleno entre filas. La distancia entre filas adyacentes es igual a *width*.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rotationDegrees=0)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Los datos de luminancia que contienen un byte por píxel. |
| width | int32_t | El ancho del marco en píxeles. |
| height | int32_t | La altura del marco en píxeles. |
| rotationDegrees | int32_t | La rotación en sentido horario requerida para mostrar el marco en posición vertical. Los valores compatibles son 0, 90, 180 y 270. El valor predeterminado es 0. |

## Ver también

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) constructor


Inicializa una nueva instancia de la clase [LuminanceFrame](../) con el stride de fila especificado.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rowStride, int32_t rotationDegrees)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Los datos de luminancia que contienen un byte por píxel. |
| width | int32_t | El ancho del marco en píxeles. |
| height | int32_t | La altura del marco en píxeles. |
| rowStride | int32_t | La distancia en bytes entre los comienzos de dos filas adyacentes. El valor no puede ser menor que *width*. |
| rotationDegrees | int32_t | La rotación en sentido horario requerida para mostrar el marco en posición vertical. Los valores admitidos son 0, 90, 180 y 270. |

## Ver también

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
