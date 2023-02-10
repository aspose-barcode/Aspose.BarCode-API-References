---
title: IPen
second_title: Aspose.BarCode for Java API Reference
description: Represents generic solid pen for barcode generation drawing.
type: docs
weight: 35
url: /java/com.aspose.barcode.drawing/ipen/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public interface IPen extends System.IDisposable
```

Represents generic solid pen for barcode generation drawing.
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Gets solid color of pen. |
| [getDashStyle()](#getDashStyle--) | Gets dash style of pen. |
| [getThickness()](#getThickness--) | Gets thickness of pen in pixels. |
| [setDashStyle(PenDashStyle value)](#setDashStyle-com.aspose.barcode.drawing.PenDashStyle-) | Sets dash style of pen. |
### getColor() {#getColor--}
```
public abstract System.Drawing.Color getColor()
```


Gets solid color of pen.

**Returns:**
com.aspose.ms.System.Drawing.Color - Color of pen.
### getDashStyle() {#getDashStyle--}
```
public abstract PenDashStyle getDashStyle()
```


Gets dash style of pen.

**Returns:**
[PenDashStyle](../../com.aspose.barcode.drawing/pendashstyle) - Dash style
### getThickness() {#getThickness--}
```
public abstract float getThickness()
```


Gets thickness of pen in pixels.

**Returns:**
float - Thickness of pen
### setDashStyle(PenDashStyle value) {#setDashStyle-com.aspose.barcode.drawing.PenDashStyle-}
```
public abstract void setDashStyle(PenDashStyle value)
```


Sets dash style of pen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PenDashStyle](../../com.aspose.barcode.drawing/pendashstyle) | The dash style |

