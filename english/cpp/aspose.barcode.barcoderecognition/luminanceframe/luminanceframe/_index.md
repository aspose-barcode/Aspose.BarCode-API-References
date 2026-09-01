---
title:  constructor
linktitle: LuminanceFrame
second_title: Aspose.BarCode for C++ API Reference
description: ' constructor. Initializes a new instance of the LuminanceFrame class without padding between rows. The distance between adjacent rows is equal to width  in C++.'
type: docs
weight: 600
url: /cpp/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) constructor


Initializes a new instance of the [LuminanceFrame](../) class without padding between rows. The distance between adjacent rows is equal to *width* .

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rotationDegrees=0)
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | The luminance data containing one byte per pixel. |
| width | int32_t | The frame width in pixels. |
| height | int32_t | The frame height in pixels. |
| rotationDegrees | int32_t | The clockwise rotation required to display the frame upright. Supported values are 0, 90, 180 and 270. The default value is 0. |

## See Also

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) constructor


Initializes a new instance of the [LuminanceFrame](../) class with the specified row stride.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rowStride, int32_t rotationDegrees)
```


| Parameter | Type | Description |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | The luminance data containing one byte per pixel. |
| width | int32_t | The frame width in pixels. |
| height | int32_t | The frame height in pixels. |
| rowStride | int32_t | The distance in bytes between the beginnings of two adjacent rows. The value cannot be less than *width* . |
| rotationDegrees | int32_t | The clockwise rotation required to display the frame upright. Supported values are 0, 90, 180 and 270. |

## See Also

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
