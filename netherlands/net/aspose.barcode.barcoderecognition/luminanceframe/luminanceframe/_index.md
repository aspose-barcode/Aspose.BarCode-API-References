---
title: "LuminanceFrame.LuminanceFrame"
second_title: "Aspose.BarCode voor .NET API‑referentie"
description: "LuminanceFrame-constructor. Initialiseert een nieuwe instantie van de LuminanceFrame-klasse zonder opvulling tussen rijen. De afstand tussen aangrenzende rijen is gelijk aan width"
type: docs
weight: 10
url: /nl/net/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame(byte[], int, int, int) {#constructor}

Initialiseert een nieuwe instantie van de [`LuminanceFrame`](../) klasse zonder opvulling tussen rijen. De afstand tussen aangrenzende rijen is gelijk aan *width*.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rotationDegrees = 0)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | Byte[] | De luminantiegegevens die één byte per pixel bevatten. |
| width | Int32 | De breedte van het frame in pixels. |
| height | Int32 | De hoogte van het frame in pixels. |
| rotationDegrees | Int32 | De met de klok mee rotatie die nodig is om het frame rechtop weer te geven. Ondersteunde waarden zijn 0, 90, 180 en 270. De standaardwaarde is 0. |

### Zie ook

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## LuminanceFrame(byte[], int, int, int, int) {#constructor_1}

Initialiseert een nieuwe instantie van de [`LuminanceFrame`](../) klasse met de opgegeven row stride.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rowStride, int rotationDegrees)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| data | Byte[] | De luminantiegegevens die één byte per pixel bevatten. |
| width | Int32 | De breedte van het frame in pixels. |
| height | Int32 | De hoogte van het frame in pixels. |
| rowStride | Int32 | De afstand in bytes tussen het begin van twee aangrenzende rijen. De waarde mag niet kleiner zijn dan *width*. |
| rotationDegrees | Int32 | De met de klok mee rotatie die nodig is om het frame rechtop weer te geven. Ondersteunde waarden zijn 0, 90, 180 en 270. |

### Zie ook

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


