---
title: "Clase Aspose::BarCode::BarCodeRecognition::LuminanceFrame"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: "Clase Aspose::BarCode::BarCodeRecognition::LuminanceFrame. Representa un cuadro de imagen en escala de grises de 8 bits. Cada píxel se representa con un byte que contiene su valor de luminancia en C++."
type: docs
weight: 2400
url: /es/cpp/aspose.barcode.barcoderecognition/luminanceframe/
---
## LuminanceFrame class


Representa un fotograma de imagen en escala de grises de 8 bits. Cada píxel se representa con un byte que contiene su valor de luminancia.

```cpp
class LuminanceFrame : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| [get_Data](./get_data/)() const | Obtiene los datos de luminancia. |
| [get_Height](./get_height/)() const | Obtiene la altura del cuadro en píxeles. |
| [get_RotationDegrees](./get_rotationdegrees/)() const | Obtiene el número de grados que el cuadro debe rotarse en sentido horario para tener la orientación correcta. |
| [get_RowStride](./get_rowstride/)() const | Obtiene la distancia en bytes entre los inicios de dos filas adyacentes. |
| [get_Width](./get_width/)() const | Obtiene el ancho del cuadro en píxeles. |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) | Inicializa una nueva instancia de la clase [LuminanceFrame](./) sin relleno entre filas. La distancia entre filas adyacentes es igual a *width*. |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) | Inicializa una nueva instancia de la clase [LuminanceFrame](./) con la distancia de fila especificada. |
## Ver también

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
