---
title: "constructor"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "constructor. Initialiseert een nieuw exemplaar van de LuminanceFrame-klasse zonder opvulling tussen rijen. De afstand tussen aangrenzende rijen is gelijk aan width in C++."
type: docs
weight: 600
url: /nl/cpp/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) constructor


Initialiseert een nieuw exemplaar van de [LuminanceFrame](../)-klasse zonder opvulling tussen rijen. De afstand tussen aangrenzende rijen is gelijk aan *width*.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rotationDegrees=0)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | De luminancedata die één byte per pixel bevat. |
| width | int32_t | De breedte van het frame in pixels. |
| height | int32_t | De hoogte van het frame in pixels. |
| rotationDegrees | int32_t | De met de klok mee rotatie die nodig is om het frame rechtop weer te geven. Ondersteunde waarden zijn 0, 90, 180 en 270. De standaardwaarde is 0. |

## Zie ook

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) constructor


Initialiseert een nieuw exemplaar van de [LuminanceFrame](../)-klasse met de opgegeven rijstap.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rowStride, int32_t rotationDegrees)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | De luminancedata die één byte per pixel bevat. |
| width | int32_t | De breedte van het frame in pixels. |
| height | int32_t | De hoogte van het frame in pixels. |
| rowStride | int32_t | De afstand in bytes tussen het begin van twee aangrenzende rijen. De waarde mag niet kleiner zijn dan *width*. |
| rotationDegrees | int32_t | De met de klok mee rotatie die nodig is om het frame rechtop weer te geven. Ondersteunde waarden zijn 0, 90, 180 en 270. |

## Zie ook

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
