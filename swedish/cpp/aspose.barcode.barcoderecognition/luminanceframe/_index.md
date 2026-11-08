---
title: "Aspose::BarCode::BarCodeRecognition::LuminanceFrame klass"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::LuminanceFrame klass. Representerar en 8-bitars gråskalebildram. Varje pixel representeras av en byte som innehåller dess luminansvärde i C++."
type: docs
weight: 2400
url: /sv/cpp/aspose.barcode.barcoderecognition/luminanceframe/
---
## LuminanceFrame class


Representerar en 8-bitars gråskalebildram. Varje pixel representeras av en byte som innehåller dess luminansvärde.

```cpp
class LuminanceFrame : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Data](./get_data/)() const | Hämtar luminansdata. |
| [get_Height](./get_height/)() const | Hämtar ramens höjd i pixlar. |
| [get_RotationDegrees](./get_rotationdegrees/)() const | Hämtar antalet grader som ramen måste roteras medurs för att ha korrekt orientering. |
| [get_RowStride](./get_rowstride/)() const | Hämtar avståndet i byte mellan början av två intilliggande rader. |
| [get_Width](./get_width/)() const | Hämtar ramens bredd i pixlar. |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) | Initierar en ny instans av klassen [LuminanceFrame](./) utan utfyllnad mellan rader. Avståndet mellan intilliggande rader är lika med *width* . |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) | Initierar en ny instans av klassen [LuminanceFrame](./) med den specificerade radsteg. |
## Se även

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
