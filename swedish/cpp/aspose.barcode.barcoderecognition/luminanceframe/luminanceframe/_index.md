---
title: "konstruktor"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ API-referens"
description: " constructor. Initierar en ny instans av LuminanceFrame-klassen utan utfyllnad mellan rader. Avståndet mellan intilliggande rader är lika med width i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) constructor


Initierar en ny instans av [LuminanceFrame](../)-klassen utan utfyllnad mellan rader. Avståndet mellan intilliggande rader är lika med *width*.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rotationDegrees=0)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Luminansdata som innehåller en byte per pixel. |
| width | int32_t | Ramens bredd i pixlar. |
| height | int32_t | Ramens höjd i pixlar. |
| rotationDegrees | int32_t | Den medursrotation som krävs för att visa ramen upprätt. Stödda värden är 0, 90, 180 och 270. Standardvärdet är 0. |

## Se även

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) constructor


Initierar en ny instans av klassen [LuminanceFrame](../) med den angivna radsteg.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rowStride, int32_t rotationDegrees)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Luminansdata som innehåller en byte per pixel. |
| width | int32_t | Ramens bredd i pixlar. |
| height | int32_t | Ramens höjd i pixlar. |
| rowStride | int32_t | Avståndet i byte mellan början av två intilliggande rader. Värdet kan inte vara mindre än *width*. |
| rotationDegrees | int32_t | Den medursrotation som krävs för att visa ramen upprätt. Stödda värden är 0, 90, 180 och 270. |

## Se även

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
