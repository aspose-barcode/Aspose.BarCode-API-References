---
title: "LuminanceFrame.LuminanceFrame"
second_title: "Aspose.BarCode för .NET API-referens"
description: "LuminanceFrame konstruktor. Initierar en ny instans av LuminanceFrame‑klassen utan utfyllnad mellan rader. Avståndet mellan intilliggande rader är lika med width"
type: docs
weight: 10
url: /sv/net/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame(byte[], int, int, int) {#constructor}

Initierar en ny instans av [`LuminanceFrame`](../)‑klassen utan utfyllnad mellan rader. Avståndet mellan intilliggande rader är lika med *width*.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rotationDegrees = 0)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | Byte[] | Luminansdata som innehåller en byte per pixel. |
| width | Int32 | Ramens bredd i pixlar. |
| height | Int32 | Ramens höjd i pixlar. |
| rotationDegrees | Int32 | Den medursrotation som krävs för att visa ramen upprätt. Stödda värden är 0, 90, 180 och 270. Standardvärdet är 0. |

### Se även

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## LuminanceFrame(byte[], int, int, int, int) {#constructor_1}

Initierar en ny instans av klassen [`LuminanceFrame`](../) med den angivna radstegningen.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rowStride, int rotationDegrees)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | Byte[] | Luminansdata som innehåller en byte per pixel. |
| width | Int32 | Ramens bredd i pixlar. |
| height | Int32 | Ramens höjd i pixlar. |
| rowStride | Int32 | Avståndet i byte mellan början av två intilliggande rader. Värdet kan inte vara mindre än *width*. |
| rotationDegrees | Int32 | Den medursrotation som krävs för att visa ramen upprätt. Stödda värden är 0, 90, 180 och 270. |

### Se även

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


