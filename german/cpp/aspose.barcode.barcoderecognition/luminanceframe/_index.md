---
title: "Aspose::BarCode::BarCodeRecognition::LuminanceFrame class"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::LuminanceFrame class. Stellt einen 8‑Bit Graustufen‑Bildrahmen dar. Jeder Pixel wird durch ein Byte repräsentiert, das seinen Luminanzwert in C++ enthält."
type: docs
weight: 2400
url: /de/cpp/aspose.barcode.barcoderecognition/luminanceframe/
---
## LuminanceFrame class


Stellt einen 8‑Bit‑Graustufen‑Bildrahmen dar. Jeder Pixel wird durch ein Byte repräsentiert, das seinen Luminanzwert enthält.

```cpp
class LuminanceFrame : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [get_Data](./get_data/)() const | Liefert die Luminanzdaten. |
| [get_Height](./get_height/)() const | Liefert die Rahmenhöhe in Pixeln. |
| [get_RotationDegrees](./get_rotationdegrees/)() const | Liefert die Anzahl der Grad, um die der Rahmen im Uhrzeigersinn gedreht werden muss, um die korrekte Ausrichtung zu erhalten. |
| [get_RowStride](./get_rowstride/)() const | Liefert den Abstand in Bytes zwischen den Anfängen zweier benachbarter Zeilen. |
| [get_Width](./get_width/)() const | Liefert die Rahmenbreite in Pixeln. |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) | Initialisiert eine neue Instanz der [LuminanceFrame](./)-Klasse ohne Auffüllung zwischen den Zeilen. Der Abstand zwischen benachbarten Zeilen ist gleich *width*. |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) | Initialisiert eine neue Instanz der [LuminanceFrame](./)-Klasse mit dem angegebenen Zeilenabstand. |
## Siehe auch

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
