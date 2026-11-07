---
title: "Konstruktor"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Konstruktor. Initialisiert eine neue Instanz der LuminanceFrame-Klasse ohne Abstand zwischen den Zeilen. Der Abstand zwischen benachbarten Zeilen entspricht der Breite in C++."
type: docs
weight: 600
url: /de/cpp/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) constructor


Initialisiert eine neue Instanz der [LuminanceFrame](../)-Klasse ohne Abstand zwischen den Zeilen. Der Abstand zwischen benachbarten Zeilen entspricht *width*.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rotationDegrees=0)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Die Luminanzdaten, die ein Byte pro Pixel enthalten. |
| width | int32_t | Die Bildbreite in Pixeln. |
| height | int32_t | Die Bildhöhe in Pixeln. |
| rotationDegrees | int32_t | Die im Uhrzeigersinn erforderliche Drehung, um das Bild aufrecht darzustellen. Unterstützte Werte sind 0, 90, 180 und 270. Der Standardwert ist 0. |

## Siehe auch

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) constructor


Initialisiert eine neue Instanz der Klasse [LuminanceFrame](../) mit dem angegebenen Zeilenabstand.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rowStride, int32_t rotationDegrees)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Die Luminanzdaten, die ein Byte pro Pixel enthalten. |
| width | int32_t | Die Bildbreite in Pixeln. |
| height | int32_t | Die Bildhöhe in Pixeln. |
| rowStride | int32_t | Der Abstand in Bytes zwischen den Beginn von zwei benachbarten Zeilen. Der Wert darf nicht kleiner sein als *width*. |
| rotationDegrees | int32_t | Die im Uhrzeigersinn erforderliche Drehung, um das Bild aufrecht darzustellen. Unterstützte Werte sind 0, 90, 180 und 270. |

## Siehe auch

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
