---
title: LuminanceFrame.LuminanceFrame
second_title: Aspose.BarCode for .NET API Reference
description: LuminanceFrame constructor. Initializes a new instance of the LuminanceFrame class without padding between rows. The distance between adjacent rows is equal to width
type: docs
weight: 10
url: /net/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame(byte[], int, int, int) {#constructor}

Initializes a new instance of the [`LuminanceFrame`](../) class without padding between rows. The distance between adjacent rows is equal to *width*.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rotationDegrees = 0)
```

| Parameter | Type | Description |
| --- | --- | --- |
| data | Byte[] | The luminance data containing one byte per pixel. |
| width | Int32 | The frame width in pixels. |
| height | Int32 | The frame height in pixels. |
| rotationDegrees | Int32 | The clockwise rotation required to display the frame upright. Supported values are 0, 90, 180 and 270. The default value is 0. |

### See Also

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)

---

## LuminanceFrame(byte[], int, int, int, int) {#constructor_1}

Initializes a new instance of the [`LuminanceFrame`](../) class with the specified row stride.

```csharp
public LuminanceFrame(byte[] data, int width, int height, int rowStride, int rotationDegrees)
```

| Parameter | Type | Description |
| --- | --- | --- |
| data | Byte[] | The luminance data containing one byte per pixel. |
| width | Int32 | The frame width in pixels. |
| height | Int32 | The frame height in pixels. |
| rowStride | Int32 | The distance in bytes between the beginnings of two adjacent rows. The value cannot be less than *width*. |
| rotationDegrees | Int32 | The clockwise rotation required to display the frame upright. Supported values are 0, 90, 180 and 270. |

### See Also

* class [LuminanceFrame](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


