---
title: Aspose::BarCode::BarCodeRecognition::LuminanceFrame class
linktitle: LuminanceFrame
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::LuminanceFrame class. Represents an 8-bit grayscale image frame. Each pixel is represented by one byte containing its luminance value in C++.'
type: docs
weight: 2200
url: /cpp/aspose.barcode.barcoderecognition/luminanceframe/
---
## LuminanceFrame class


Represents an 8-bit grayscale image frame. Each pixel is represented by one byte containing its luminance value.

```cpp
class LuminanceFrame : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Data](./get_data/)() const | Gets the luminance data. |
| [get_Height](./get_height/)() const | Gets the frame height in pixels. |
| [get_RotationDegrees](./get_rotationdegrees/)() const | Gets the number of degrees the frame must be rotated clockwise to have the correct orientation. |
| [get_RowStride](./get_rowstride/)() const | Gets the distance in bytes between the beginnings of two adjacent rows. |
| [get_Width](./get_width/)() const | Gets the frame width in pixels. |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) | Initializes a new instance of the [LuminanceFrame](./) class without padding between rows. The distance between adjacent rows is equal to *width* . |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) | Initializes a new instance of the [LuminanceFrame](./) class with the specified row stride. |
## See Also

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
