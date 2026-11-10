---
title: "LuminanceFrame.LuminanceFrame"
second_title: "Aspose.BarCode für .NET API-Referenz"
description: "LuminanceFrame Konstruktor. Initialisiert eine neue Instanz der LuminanceFrame-Klasse ohne Abstand zwischen den Zeilen. Der Abstand zwischen benachbarten Zeilen entspricht der Breite"
type: docs
weight: 10
url: /de/net/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame(byte[], int, int, int) {#constructor}

Initialisiert eine neue Instanz der [`LuminanceFrame`](../)-Klasse ohne Abstand zwischen den Zeilen. Der Abstand zwischen benachbarten Zeilen entspricht *width*.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rotationDegrees = 0)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | Byte[] | Die Luminanzdaten, die ein Byte pro Pixel enthalten. |
| width | Int32 | Die Frame-Breite in Pixeln. |
| height | Int32 | Die Frame-Höhe in Pixeln. |
| rotationDegrees | Int32 | Die im Uhrzeigersinn erforderliche Drehung, um das Bild aufrecht anzuzeigen. Unterstützte Werte sind 0, 90, 180 und 270. Der Standardwert ist 0. |

### Siehe auch

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## LuminanceFrame(byte[], int, int, int, int) {#constructor_1}

Initialisiert eine neue Instanz der [`LuminanceFrame`](../)-Klasse mit dem angegebenen Zeilenabstand.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rowStride, int rotationDegrees)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | Byte[] | Die Luminanzdaten, die ein Byte pro Pixel enthalten. |
| width | Int32 | Die Frame-Breite in Pixeln. |
| height | Int32 | Die Frame-Höhe in Pixeln. |
| rowStride | Int32 | Der Abstand in Bytes zwischen den Anfängen zweier benachbarter Zeilen. Der Wert darf nicht kleiner sein als *width*. |
| rotationDegrees | Int32 | Die im Uhrzeigersinn erforderliche Drehung, um das Bild aufrecht anzuzeigen. Unterstützte Werte sind 0, 90, 180 und 270. |

### Siehe auch

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


