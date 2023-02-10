---
title: EmfRecordType
second_title: Aspose.BarCode for Java API Reference
description: The RecordType enumeration defines values that uniquely identify EMF records.
type: docs
weight: 20
url: /java/com.aspose.barcode.drawing.emf._const/emfrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRecordType extends System.Enum
```

The RecordType enumeration defines values that uniquely identify EMF records. These values are provided in the Type field of each record.
## Fields

| Field | Description |
| --- | --- |
| [EmfAbortPath](#EmfAbortPath) | This record aborts a path bracket or discards the path from a closed path bracket. |
| [EmfAlphaBlend](#EmfAlphaBlend) | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, including alpha transparency data, according to a specified blending operation. |
| [EmfAngleArc](#EmfAngleArc) | This record defines a line segment of an arc. |
| [EmfArc](#EmfArc) | This record defines an elliptical arc. |
| [EmfArcTo](#EmfArcTo) | This record defines an elliptical arc. |
| [EmfBeginPath](#EmfBeginPath) | This record opens a path bracket in the playback device context. |
| [EmfBitBlt](#EmfBitBlt) | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation. |
| [EmfChord](#EmfChord) | This record defines a chord (a region bounded by the intersection of an ellipse and a line segment, called a secant). |
| [EmfCloseFigure](#EmfCloseFigure) | This record closes an open figure in a path. |
| [EmfColorCorrectPalette](#EmfColorCorrectPalette) | This record specifies how to correct the entries of a logical palette object using Windows Color System (WCS) 1.0 values |
| [EmfColorMatchToTargetW](#EmfColorMatchToTargetW) | This record specifies whether to perform color matching with a color profile that is specified in a file with a name consisting of Unicode characters. |
| [EmfComment](#EmfComment) | This record specifies arbitrary private data. |
| [EmfCreateBrushInDirect](#EmfCreateBrushInDirect) | This record defines a logical brush for figure filling in graphics operations. |
| [EmfCreateColorSpace](#EmfCreateColorSpace) | This record creates a logical color space object from a color profile with a name consisting of ASCII characters |
| [EmfCreateColorSpaceW](#EmfCreateColorSpaceW) | This record creates a logical color space object from a color profile with a name consisting of Unicode characters |
| [EmfCreateDibPatternBrushPt](#EmfCreateDibPatternBrushPt) | This record defines a logical brush that has the pattern specified by the DIB. |
| [EmfCreateMonoBrush](#EmfCreateMonoBrush) | This record defines a logical brush with the specified bitmap pattern. |
| [EmfCreatePalette](#EmfCreatePalette) | This record defines a LogPalette object. |
| [EmfCreatePen](#EmfCreatePen) | This record defines a logical pen that has the specified style, width, and color. |
| [EmfDeleteColorSpace](#EmfDeleteColorSpace) | This record deletes a logical color space object. |
| [EmfDeleteObject](#EmfDeleteObject) | This record deletes a graphics object, clearing its index in the EMF Object Table. |
| [EmfDrawEscape](#EmfDrawEscape) | This record passes arbitrary information to the driver. |
| [EmfEllipse](#EmfEllipse) | This record defines an ellipse. |
| [EmfEndPath](#EmfEndPath) | This record closes a path bracket and selects the path defined by the bracket into the playback device context. |
| [EmfEof](#EmfEof) | This record indicates the end of the metafile. |
| [EmfExcludeClipRect](#EmfExcludeClipRect) | This record defines a new clipping region that consists of the existing clipping region minus the specified rectangle. |
| [EmfExtCreateFontInDirectW](#EmfExtCreateFontInDirectW) | This record defines a logical font that has the specified characteristics. |
| [EmfExtCreatePen](#EmfExtCreatePen) | This record defines a logical cosmetic or geometric pen that has the specified style, width, and brush attributes. |
| [EmfExtEscape](#EmfExtEscape) | This record passes arbitrary information to the driver. |
| [EmfExtFloodFill](#EmfExtFloodFill) | This record fills an area of the display surface with the current brush. |
| [EmfExtSelectClipRgn](#EmfExtSelectClipRgn) | This record combines the specified region with the current clip region using the specified mode. |
| [EmfExtTextOutA](#EmfExtTextOutA) | This record draws an ASCII text string using the current font and text colors.Note EMR\_EXTTEXTOUTA SHOULD be emulated with an EMR\_EXTTEXTOUTW record (section 2.3.5.8). |
| [EmfExtTextOutW](#EmfExtTextOutW) | This record draws a Unicode text string using the current font and text colors. |
| [EmfFillPath](#EmfFillPath) | This record closes any open figures in the current path and fills the path's interior by using the current brush and polygon-filling mode. |
| [EmfFillRgn](#EmfFillRgn) | This record fills the specified region by using the specified brush. |
| [EmfFlattenPath](#EmfFlattenPath) | This record transforms any curve in the path that is selected into the playback device context, turning each curve into a sequence of lines. |
| [EmfForceUfiMapping](#EmfForceUfiMapping) | This record forces the font mapper to match fonts based on their UniversalFontId in preference to their LogFont information. |
| [EmfFrameRgn](#EmfFrameRgn) | This record draws a border around the specified region using the specified brush. |
| [EmfGlsBoundedRecord](#EmfGlsBoundedRecord) | This record specifies an OpenGL function with a bounding rectangle for output. |
| [EmfGlsRecord](#EmfGlsRecord) | This record specifies an OpenGL function. |
| [EmfGradientFill](#EmfGradientFill) | This record specifies filling rectangles or triangles with gradients of color |
| [EmfHeader](#EmfHeader) | This record defines the start of the metafile and specifies its characteristics; its contents, including the dimensions of the embedded image; the number of records in the metafile; and the resolution of the device on which the embedded image was created. |
| [EmfIntersectClipRect](#EmfIntersectClipRect) | This record defines a new clipping region from the intersection of the current clipping region and the specified rectangle. |
| [EmfInvertRgn](#EmfInvertRgn) | This record inverts the colors in the specified region. |
| [EmfLineTo](#EmfLineTo) | This record defines a line from the current position up to, but not including, the specified point. |
| [EmfMapMode](#EmfMapMode) | This record defines the mapping mode of the playback device context. |
| [EmfMaskBlt](#EmfMaskBlt) | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern and with the application of a color mask bitmap, according to specified foreground and background raster operations. |
| [EmfModifyWorldTransform](#EmfModifyWorldTransform) | This record redefines the world transformation for the playback device context using the specified mode. |
| [EmfMoveToEx](#EmfMoveToEx) | This record defines coordinates of the new current position, in logical units. |
| [EmfNamedEscape](#EmfNamedEscape) | This record passes arbitrary information to the given named driver. |
| [EmfNone](#EmfNone) | This is None record |
| [EmfOffsetClipRgn](#EmfOffsetClipRgn) | This record redefines the clipping region of the playback device context by the specified offsets. |
| [EmfPaintRgn](#EmfPaintRgn) | This record paints the specified region by using the brush currently selected into the playback device context. |
| [EmfPie](#EmfPie) | This record defines a pie-shaped wedge bounded by the intersection of an ellipse and two radials. |
| [EmfPixelFormat](#EmfPixelFormat) | This record specifies the pixel format to use for graphics operations |
| [EmfPlgBlt](#EmfPlgBlt) | This record specifies a block transfer of pixels from a source bitmap to a destination parallelogram, with the application of a color mask bitmap. |
| [EmfPolyBezier](#EmfPolyBezier) | This record defines one or more Bezier curves. |
| [EmfPolyBezier16](#EmfPolyBezier16) | This record defines one or more Bezier curves. |
| [EmfPolyBezierTo](#EmfPolyBezierTo) | This record defines one or more Bezier curves based upon the current position. |
| [EmfPolyBezierTo16](#EmfPolyBezierTo16) | This record defines one or more Bezier curves based on the current position. |
| [EmfPolyDraw](#EmfPolyDraw) | This record defines a set of line segments and Bezier curves. |
| [EmfPolyDraw16](#EmfPolyDraw16) | This record defines a set of line segments and Bezier curves. |
| [EmfPolyLine](#EmfPolyLine) | This record defines a series of line segments by connecting the points in the specified array. |
| [EmfPolyLine16](#EmfPolyLine16) | This record defines a series of line segments by connecting the points in the specified array. |
| [EmfPolyLineTo](#EmfPolyLineTo) | This record defines one or more straight lines based upon the current position. |
| [EmfPolyLineTo16](#EmfPolyLineTo16) | This record defines one or more straight lines based upon the current position. |
| [EmfPolyPolyLine](#EmfPolyPolyLine) | This record defines multiple series of connected line segments. |
| [EmfPolyPolyLine16](#EmfPolyPolyLine16) | This record defines multiple series of connected line segments. |
| [EmfPolyPolygon](#EmfPolyPolygon) | This record defines a series of closed polygons. |
| [EmfPolyPolygon16](#EmfPolyPolygon16) | This record defines a series of closed polygons. |
| [EmfPolyTextOutA](#EmfPolyTextOutA) | This record draws one or more ASCII text strings using the current font and text colors. |
| [EmfPolyTextOutW](#EmfPolyTextOutW) | This record draws one or more Unicode text strings using the current font and text colors. |
| [EmfPolygon](#EmfPolygon) | This record defines a polygon consisting of two or more vertexes connected by straight lines. |
| [EmfPolygon16](#EmfPolygon16) | This record defines a polygon consisting of two or more vertexes connected by straight lines. |
| [EmfRealizePalette](#EmfRealizePalette) | This record maps entries from the current logical palette to the system palette. |
| [EmfRectangle](#EmfRectangle) | This record defines a rectangle. |
| [EmfResizePalette](#EmfResizePalette) | This record increases or decreases the size of a logical palette. |
| [EmfRestoreDc](#EmfRestoreDc) | This record restores the playback device context to the specified saved state. |
| [EmfRoundRect](#EmfRoundRect) | This record defines a rectangle with rounded corners. |
| [EmfSaveDc](#EmfSaveDc) | This record saves the current state of the playback device context by copying data describing selected objects and graphic modes\\u2014including the bitmap, brush, palette, font, pen, region, drawing mode, and mapping mode\\u2014to a stack of saved device contexts. |
| [EmfScaleViewportExtEx](#EmfScaleViewportExtEx) | This record redefines the viewport for the playback device context using the ratios formed by the specified multiplicands and divisors. |
| [EmfScaleWindowExtEx](#EmfScaleWindowExtEx) | This record redefines the window for the playback device context using the ratios formed by the specified multiplicands and divisors. |
| [EmfSelectClipPath](#EmfSelectClipPath) | This record defines the current path as a clipping region for the playback device context, combining the new region with any existing clipping region using the specified mode. |
| [EmfSelectObject](#EmfSelectObject) | This record adds an object to the playback device context, identifying it by its index in the EMF Object Table (section 3.1.1.1). |
| [EmfSelectPalette](#EmfSelectPalette) | This record adds a LogPalette (section 2.2.17) object to the playback device context, identifying it by its index in the EMF Object Table. |
| [EmfSetArcDirection](#EmfSetArcDirection) | This record defines the drawing direction to be used for arc and rectangle operations. |
| [EmfSetBkColor](#EmfSetBkColor) | This record defines the background color. |
| [EmfSetBkMode](#EmfSetBkMode) | This record defines the background mix mode of the playback device context. |
| [EmfSetBrushOrgEx](#EmfSetBrushOrgEx) | This record defines the origin of the current brush. |
| [EmfSetColorAdjustment](#EmfSetColorAdjustment) | This record defines the color adjustment values for the playback device context using the specified values. |
| [EmfSetColorSpace](#EmfSetColorSpace) | This record defines the current logical color space object for graphics operations. |
| [EmfSetDiBitsToDevice](#EmfSetDiBitsToDevice) | This record specifies a block transfer of pixels from specified scan lines of a source bitmap to a destination rectangle. |
| [EmfSetIcmMode](#EmfSetIcmMode) | This record specifies the mode of Image Color Management (ICM) for graphics operations. |
| [EmfSetIcmProfileA](#EmfSetIcmProfileA) | This record specifies a color profile in a file with a name consisting of ASCII characters, for graphics output. |
| [EmfSetIcmProfileW](#EmfSetIcmProfileW) | This record specifies a color profile in a file with a name consisting of Unicode characters, for graphics output |
| [EmfSetLayout](#EmfSetLayout) | This record specifies the order in which text and graphics are drawn |
| [EmfSetLinkedUfis](#EmfSetLinkedUfis) | This record sets the UniversalFontIds of linked fonts to use during character lookup. |
| [EmfSetMapperFlags](#EmfSetMapperFlags) | This record specifies parameters of the process of matching logical fonts to physical fonts, which is performed by the font mapper. |
| [EmfSetMetaRgn](#EmfSetMetaRgn) | This record intersects the current clipping region for the playback device context with the current meta region and saves the combined region as the new meta region. |
| [EmfSetMiterLimit](#EmfSetMiterLimit) | This record defines the limit for the length of miter joins for the playback device context. |
| [EmfSetPaletteEntries](#EmfSetPaletteEntries) | This record defines RGB (red-green-blue) color values in a range of entries in a LogPalette object. |
| [EmfSetPixelV](#EmfSetPixelV) | This record defines the color of the pixel at the specified logical coordinates. |
| [EmfSetPolyFillMode](#EmfSetPolyFillMode) | This record defines polygon fill mode. |
| [EmfSetRop2](#EmfSetRop2) | This record defines binary raster operation mode. |
| [EmfSetStrechBltMode](#EmfSetStrechBltMode) | This record defines bitmap stretch mode. |
| [EmfSetTextAlign](#EmfSetTextAlign) | This record defines text alignment. |
| [EmfSetTextColor](#EmfSetTextColor) | This record defines the current text color. |
| [EmfSetTextJustification](#EmfSetTextJustification) | This record specifies the amount of extra space to add to break characters for justification purposes. |
| [EmfSetViewportExtEx](#EmfSetViewportExtEx) | This record defines the viewport extent. |
| [EmfSetViewportOrgEx](#EmfSetViewportOrgEx) | This record defines the viewport origin. |
| [EmfSetWindowExtEx](#EmfSetWindowExtEx) | This record defines the window extent. |
| [EmfSetWindowOrgEx](#EmfSetWindowOrgEx) | This record defines the window origin. |
| [EmfSetWorldTransform](#EmfSetWorldTransform) | This record defines a two-dimensional linear transformation between world space and page space (for more information, see [MSDN-WRLDPGSPC]) for the playback device context. |
| [EmfSmallTextOut](#EmfSmallTextOut) | This record outputs a string. |
| [EmfStretchBlt](#EmfStretchBlt) | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation, stretching or compressing the output to fit the dimensions of the destination, if necessary. |
| [EmfStretchDiBits](#EmfStretchDiBits) | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation, stretching or compressing the output to fit the dimensions of the destination, if necessary. |
| [EmfStrokeAndFillPath](#EmfStrokeAndFillPath) | This record closes any open figures in a path, strokes the outline of the path by using the current pen, and fills its interior by using the current brush. |
| [EmfStrokePath](#EmfStrokePath) | This record renders the specified path by using the current pen. |
| [EmfTransparentBlt](#EmfTransparentBlt) | This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, treating a specified color as transparent, stretching or compressing the output to fit the dimensions of the destination, if necessary |
| [EmfWidenPath](#EmfWidenPath) | This record redefines the current path as the area that would be painted if the path were stroked using the pen currently selected into the playback device context. |
| [EnumSeparatorCharArray](#EnumSeparatorCharArray) |  |
## Methods

| Method | Description |
| --- | --- |
| [Clone()](#Clone--) |  |
| [CloneTo(T arg0)](#CloneTo-T-) |  |
| [CloneTo(System.Enum arg0)](#CloneTo-com.aspose.ms.System.Enum-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [format(System.Type arg0, Object arg1, String arg2)](#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-) |  |
| [format(Class<?> arg0, long arg1, String arg2)](#format-java.lang.Class----long-java.lang.String-) |  |
| [getClass()](#getClass--) |  |
| [getName(System.Type arg0, Object arg1)](#getName-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [getName(Class<?> arg0, long arg1)](#getName-java.lang.Class----long-) |  |
| [getNames(System.Type arg0)](#getNames-com.aspose.ms.System.Type-) |  |
| [getNames(Class<?> arg0)](#getNames-java.lang.Class----) |  |
| [getUnderlyingType(System.Type arg0)](#getUnderlyingType-com.aspose.ms.System.Type-) |  |
| [getUnderlyingType(Class<?> arg0)](#getUnderlyingType-java.lang.Class----) |  |
| [getValue(Class<?> arg0, String arg1)](#getValue-java.lang.Class----java.lang.String-) |  |
| [getValues(System.Type arg0)](#getValues-com.aspose.ms.System.Type-) |  |
| [get_Value()](#get-Value--) |  |
| [hashCode()](#hashCode--) |  |
| [isDefined(System.Type arg0, Object arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [isDefined(System.Type arg0, String arg1)](#isDefined-com.aspose.ms.System.Type-java.lang.String-) |  |
| [isDefined(System.Type arg0, long arg1)](#isDefined-com.aspose.ms.System.Type-long-) |  |
| [isDefined(Class<?> arg0, long arg1)](#isDefined-java.lang.Class----long-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parse(System.Type arg0, String arg1)](#parse-com.aspose.ms.System.Type-java.lang.String-) |  |
| [parse(System.Type arg0, String arg1, Boolean arg2)](#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-) |  |
| [parse(Class<?> arg0, String arg1)](#parse-java.lang.Class----java.lang.String-) |  |
| [parse(Class<?> arg0, String arg1, Boolean arg2)](#parse-java.lang.Class----java.lang.String-java.lang.Boolean-) |  |
| [register(System.Enum.AbstractEnum arg0)](#register-com.aspose.ms.System.Enum.AbstractEnum-) |  |
| [toObject(System.Type arg0, Object arg1)](#toObject-com.aspose.ms.System.Type-java.lang.Object-) |  |
| [toString()](#toString--) |  |
| [toString(Class<?> arg0, long arg1)](#toString-java.lang.Class----long-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EmfAbortPath {#EmfAbortPath}
```
public static final long EmfAbortPath
```


This record aborts a path bracket or discards the path from a closed path bracket.

### EmfAlphaBlend {#EmfAlphaBlend}
```
public static final long EmfAlphaBlend
```


This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, including alpha transparency data, according to a specified blending operation.

### EmfAngleArc {#EmfAngleArc}
```
public static final long EmfAngleArc
```


This record defines a line segment of an arc. The line segment is drawn from the current position to the beginning of the arc. The arc is drawn along the perimeter of a circle with the given radius and center. The length of the arc is defined by the given start and sweep angles.

### EmfArc {#EmfArc}
```
public static final long EmfArc
```


This record defines an elliptical arc.

### EmfArcTo {#EmfArcTo}
```
public static final long EmfArcTo
```


This record defines an elliptical arc. It resets the current position to the end point of the arc.

### EmfBeginPath {#EmfBeginPath}
```
public static final long EmfBeginPath
```


This record opens a path bracket in the playback device context.

--------------------

After a path bracket is open, an application can begin processing records to define the points that lie in the path. An application MUST close an open path bracket by processing the EMR\_ENDPATH record. When an application processes the EMR\_BEGINPATH record, all previous paths MUST be discarded from the playback device context.

### EmfBitBlt {#EmfBitBlt}
```
public static final long EmfBitBlt
```


This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation.

### EmfChord {#EmfChord}
```
public static final long EmfChord
```


This record defines a chord (a region bounded by the intersection of an ellipse and a line segment, called a secant). The chord is outlined by using the current pen and filled by using the current brush.

### EmfCloseFigure {#EmfCloseFigure}
```
public static final long EmfCloseFigure
```


This record closes an open figure in a path.

--------------------

Processing the EMR\_CLOSEFIGURE record MUST close the figure by drawing a line from the current position to the first point of the figure, and then it MUST connect the lines by using the line join style. If a figure is closed by processing the EMR\_LINETO record instead of the EMR\_CLOSEFIGURE record, end caps are used to create the corner instead of a join. EMR\_LINETO is specified in section 2.3.5.13. The EMR\_CLOSEFIGURE record SHOULD only be used if there is an open path bracket in the playback device context. A figure in a path is open unless it is explicitly closed by processing this record. Note: A figure can be open even if the current point and the starting point of the figure are the same. After processing the EMR\_CLOSEFIGURE record, adding a line or curve to the path MUST start a new figure.

### EmfColorCorrectPalette {#EmfColorCorrectPalette}
```
public static final long EmfColorCorrectPalette
```


This record specifies how to correct the entries of a logical palette object using Windows Color System (WCS) 1.0 values

### EmfColorMatchToTargetW {#EmfColorMatchToTargetW}
```
public static final long EmfColorMatchToTargetW
```


This record specifies whether to perform color matching with a color profile that is specified in a file with a name consisting of Unicode characters.

### EmfComment {#EmfComment}
```
public static final long EmfComment
```


This record specifies arbitrary private data.

### EmfCreateBrushInDirect {#EmfCreateBrushInDirect}
```
public static final long EmfCreateBrushInDirect
```


This record defines a logical brush for figure filling in graphics operations.

### EmfCreateColorSpace {#EmfCreateColorSpace}
```
public static final long EmfCreateColorSpace
```


This record creates a logical color space object from a color profile with a name consisting of ASCII characters

### EmfCreateColorSpaceW {#EmfCreateColorSpaceW}
```
public static final long EmfCreateColorSpaceW
```


This record creates a logical color space object from a color profile with a name consisting of Unicode characters

### EmfCreateDibPatternBrushPt {#EmfCreateDibPatternBrushPt}
```
public static final long EmfCreateDibPatternBrushPt
```


This record defines a logical brush that has the pattern specified by the DIB.

### EmfCreateMonoBrush {#EmfCreateMonoBrush}
```
public static final long EmfCreateMonoBrush
```


This record defines a logical brush with the specified bitmap pattern. The bitmap can be a device-independent bitmap (DIB) section bitmap or it can be a device-dependent bitmap.

### EmfCreatePalette {#EmfCreatePalette}
```
public static final long EmfCreatePalette
```


This record defines a LogPalette object.

### EmfCreatePen {#EmfCreatePen}
```
public static final long EmfCreatePen
```


This record defines a logical pen that has the specified style, width, and color. The pen can subsequently be selected into the playback device context and used to draw lines and curves.

### EmfDeleteColorSpace {#EmfDeleteColorSpace}
```
public static final long EmfDeleteColorSpace
```


This record deletes a logical color space object. Note An EMR\_DELETEOBJECT record SHOULD be used instead of EMR\_DELETECOLORSPACE to delete a logical color space object

### EmfDeleteObject {#EmfDeleteObject}
```
public static final long EmfDeleteObject
```


This record deletes a graphics object, clearing its index in the EMF Object Table. If the deleted object is selected in the playback device context, the default object for that context property MUST be restored.

### EmfDrawEscape {#EmfDrawEscape}
```
public static final long EmfDrawEscape
```


This record passes arbitrary information to the driver. The intent is that the information will result in drawing being done.

### EmfEllipse {#EmfEllipse}
```
public static final long EmfEllipse
```


This record defines an ellipse. The center of the ellipse is the center of the specified bounding rectangle. The ellipse is outlined by using the current pen and is filled by using the current brush.

### EmfEndPath {#EmfEndPath}
```
public static final long EmfEndPath
```


This record closes a path bracket and selects the path defined by the bracket into the playback device context.

### EmfEof {#EmfEof}
```
public static final long EmfEof
```


This record indicates the end of the metafile.

### EmfExcludeClipRect {#EmfExcludeClipRect}
```
public static final long EmfExcludeClipRect
```


This record defines a new clipping region that consists of the existing clipping region minus the specified rectangle.

### EmfExtCreateFontInDirectW {#EmfExtCreateFontInDirectW}
```
public static final long EmfExtCreateFontInDirectW
```


This record defines a logical font that has the specified characteristics. The font can subsequently be selected as the current font for the playback device context.

### EmfExtCreatePen {#EmfExtCreatePen}
```
public static final long EmfExtCreatePen
```


This record defines a logical cosmetic or geometric pen that has the specified style, width, and brush attributes.

### EmfExtEscape {#EmfExtEscape}
```
public static final long EmfExtEscape
```


This record passes arbitrary information to the driver. The intent is that the information will not result in drawing being done.

### EmfExtFloodFill {#EmfExtFloodFill}
```
public static final long EmfExtFloodFill
```


This record fills an area of the display surface with the current brush.

### EmfExtSelectClipRgn {#EmfExtSelectClipRgn}
```
public static final long EmfExtSelectClipRgn
```


This record combines the specified region with the current clip region using the specified mode.

### EmfExtTextOutA {#EmfExtTextOutA}
```
public static final long EmfExtTextOutA
```


This record draws an ASCII text string using the current font and text colors.Note EMR\_EXTTEXTOUTA SHOULD be emulated with an EMR\_EXTTEXTOUTW record (section 2.3.5.8). This requires the ASCII text string in the EmrText object to be converted to Unicode UTF16-LE encoding.

### EmfExtTextOutW {#EmfExtTextOutW}
```
public static final long EmfExtTextOutW
```


This record draws a Unicode text string using the current font and text colors.

### EmfFillPath {#EmfFillPath}
```
public static final long EmfFillPath
```


This record closes any open figures in the current path and fills the path's interior by using the current brush and polygon-filling mode.

### EmfFillRgn {#EmfFillRgn}
```
public static final long EmfFillRgn
```


This record fills the specified region by using the specified brush.

### EmfFlattenPath {#EmfFlattenPath}
```
public static final long EmfFlattenPath
```


This record transforms any curve in the path that is selected into the playback device context, turning each curve into a sequence of lines.

### EmfForceUfiMapping {#EmfForceUfiMapping}
```
public static final long EmfForceUfiMapping
```


This record forces the font mapper to match fonts based on their UniversalFontId in preference to their LogFont information.

### EmfFrameRgn {#EmfFrameRgn}
```
public static final long EmfFrameRgn
```


This record draws a border around the specified region using the specified brush.

### EmfGlsBoundedRecord {#EmfGlsBoundedRecord}
```
public static final long EmfGlsBoundedRecord
```


This record specifies an OpenGL function with a bounding rectangle for output.

### EmfGlsRecord {#EmfGlsRecord}
```
public static final long EmfGlsRecord
```


This record specifies an OpenGL function.

### EmfGradientFill {#EmfGradientFill}
```
public static final long EmfGradientFill
```


This record specifies filling rectangles or triangles with gradients of color

### EmfHeader {#EmfHeader}
```
public static final long EmfHeader
```


This record defines the start of the metafile and specifies its characteristics; its contents, including the dimensions of the embedded image; the number of records in the metafile; and the resolution of the device on which the embedded image was created. These values make it possible for the metafile to be device-independent.

### EmfIntersectClipRect {#EmfIntersectClipRect}
```
public static final long EmfIntersectClipRect
```


This record defines a new clipping region from the intersection of the current clipping region and the specified rectangle.

### EmfInvertRgn {#EmfInvertRgn}
```
public static final long EmfInvertRgn
```


This record inverts the colors in the specified region.

### EmfLineTo {#EmfLineTo}
```
public static final long EmfLineTo
```


This record defines a line from the current position up to, but not including, the specified point. It resets the current position to the specified point.

### EmfMapMode {#EmfMapMode}
```
public static final long EmfMapMode
```


This record defines the mapping mode of the playback device context. The mapping mode defines the unit of measure used to transform page space units into device space units, and also defines the orientation of the device's x-axis and y-axis.

### EmfMaskBlt {#EmfMaskBlt}
```
public static final long EmfMaskBlt
```


This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern and with the application of a color mask bitmap, according to specified foreground and background raster operations.

### EmfModifyWorldTransform {#EmfModifyWorldTransform}
```
public static final long EmfModifyWorldTransform
```


This record redefines the world transformation for the playback device context using the specified mode.

### EmfMoveToEx {#EmfMoveToEx}
```
public static final long EmfMoveToEx
```


This record defines coordinates of the new current position, in logical units.

### EmfNamedEscape {#EmfNamedEscape}
```
public static final long EmfNamedEscape
```


This record passes arbitrary information to the given named driver.

### EmfNone {#EmfNone}
```
public static final long EmfNone
```


This is None record

### EmfOffsetClipRgn {#EmfOffsetClipRgn}
```
public static final long EmfOffsetClipRgn
```


This record redefines the clipping region of the playback device context by the specified offsets.

### EmfPaintRgn {#EmfPaintRgn}
```
public static final long EmfPaintRgn
```


This record paints the specified region by using the brush currently selected into the playback device context.

### EmfPie {#EmfPie}
```
public static final long EmfPie
```


This record defines a pie-shaped wedge bounded by the intersection of an ellipse and two radials. The pie is outlined by using the current pen and filled by using the current brush.

### EmfPixelFormat {#EmfPixelFormat}
```
public static final long EmfPixelFormat
```


This record specifies the pixel format to use for graphics operations

### EmfPlgBlt {#EmfPlgBlt}
```
public static final long EmfPlgBlt
```


This record specifies a block transfer of pixels from a source bitmap to a destination parallelogram, with the application of a color mask bitmap.

### EmfPolyBezier {#EmfPolyBezier}
```
public static final long EmfPolyBezier
```


This record defines one or more Bezier curves. Cubic Bezier curves are defined using specified endpoints and control points, and are stroked with the current pen.

### EmfPolyBezier16 {#EmfPolyBezier16}
```
public static final long EmfPolyBezier16
```


This record defines one or more Bezier curves. The curves are drawn using the current pen.

### EmfPolyBezierTo {#EmfPolyBezierTo}
```
public static final long EmfPolyBezierTo
```


This record defines one or more Bezier curves based upon the current position.

### EmfPolyBezierTo16 {#EmfPolyBezierTo16}
```
public static final long EmfPolyBezierTo16
```


This record defines one or more Bezier curves based on the current position.

### EmfPolyDraw {#EmfPolyDraw}
```
public static final long EmfPolyDraw
```


This record defines a set of line segments and Bezier curves.

### EmfPolyDraw16 {#EmfPolyDraw16}
```
public static final long EmfPolyDraw16
```


This record defines a set of line segments and Bezier curves.

### EmfPolyLine {#EmfPolyLine}
```
public static final long EmfPolyLine
```


This record defines a series of line segments by connecting the points in the specified array.

### EmfPolyLine16 {#EmfPolyLine16}
```
public static final long EmfPolyLine16
```


This record defines a series of line segments by connecting the points in the specified array.

### EmfPolyLineTo {#EmfPolyLineTo}
```
public static final long EmfPolyLineTo
```


This record defines one or more straight lines based upon the current position. A line is drawn from the current position to the first point specified by the points field by using the current pen. For each additional line, drawing is performed from the ending point of the previous line to the next point specified by points.

### EmfPolyLineTo16 {#EmfPolyLineTo16}
```
public static final long EmfPolyLineTo16
```


This record defines one or more straight lines based upon the current position. A line is drawn from the current position to the first point specified by the Points field by using the current pen. For each additional line, drawing is performed from the ending point of the previous line to the next point specified by Points.

### EmfPolyPolyLine {#EmfPolyPolyLine}
```
public static final long EmfPolyPolyLine
```


This record defines multiple series of connected line segments. The line segments are drawn by using the current pen. The figures formed by the segments are not filled. T he current position is neither used nor updated by this record.

### EmfPolyPolyLine16 {#EmfPolyPolyLine16}
```
public static final long EmfPolyPolyLine16
```


This record defines multiple series of connected line segments.

### EmfPolyPolygon {#EmfPolyPolygon}
```
public static final long EmfPolyPolygon
```


This record defines a series of closed polygons. Each polygon is outlined by using the current pen and filled by using the current brush and polygon fill mode. The polygons defined by this record can overlap.

### EmfPolyPolygon16 {#EmfPolyPolygon16}
```
public static final long EmfPolyPolygon16
```


This record defines a series of closed polygons. Each polygon is outlined by using the current pen and filled by using the current brush and polygon fill mode. The polygons specified by this record can overlap.

### EmfPolyTextOutA {#EmfPolyTextOutA}
```
public static final long EmfPolyTextOutA
```


This record draws one or more ASCII text strings using the current font and text colors. Note EMR\_POLYTEXTOUTA SHOULD be emulated with a series of EMR\_EXTTEXTOUTW records, one per string

### EmfPolyTextOutW {#EmfPolyTextOutW}
```
public static final long EmfPolyTextOutW
```


This record draws one or more Unicode text strings using the current font and text colors. Note EMR\_POLYTEXTOUTW SHOULD be emulated with a series of EMR\_EXTTEXTOUTW records, one per string

### EmfPolygon {#EmfPolygon}
```
public static final long EmfPolygon
```


This record defines a polygon consisting of two or more vertexes connected by straight lines. The polygon is outlined by using the current pen and filled by using the current brush and polygon fill mode. The polygon is closed automatically by drawing a line from the last vertex to the first.

### EmfPolygon16 {#EmfPolygon16}
```
public static final long EmfPolygon16
```


This record defines a polygon consisting of two or more vertexes connected by straight lines. The polygon is outlined by using the current pen and filled by using the current brush and polygon fill mode. The polygon is closed automatically by drawing a line from the last vertex to the first.

### EmfRealizePalette {#EmfRealizePalette}
```
public static final long EmfRealizePalette
```


This record maps entries from the current logical palette to the system palette.

### EmfRectangle {#EmfRectangle}
```
public static final long EmfRectangle
```


This record defines a rectangle. The rectangle is outlined by using the current pen and filled by using the current brush.

### EmfResizePalette {#EmfResizePalette}
```
public static final long EmfResizePalette
```


This record increases or decreases the size of a logical palette.

### EmfRestoreDc {#EmfRestoreDc}
```
public static final long EmfRestoreDc
```


This record restores the playback device context to the specified saved state. The playback device context is restored by popping state information off a stack of saved device contexts created by earlier EMR\_SAVEDC (section 2.3.11) records.

### EmfRoundRect {#EmfRoundRect}
```
public static final long EmfRoundRect
```


This record defines a rectangle with rounded corners. The rectangle is outlined by using the current pen and filled by using the current brush.

### EmfSaveDc {#EmfSaveDc}
```
public static final long EmfSaveDc
```


This record saves the current state of the playback device context by copying data describing selected objects and graphic modes\\u2014including the bitmap, brush, palette, font, pen, region, drawing mode, and mapping mode\\u2014to a stack of saved device contexts.

### EmfScaleViewportExtEx {#EmfScaleViewportExtEx}
```
public static final long EmfScaleViewportExtEx
```


This record redefines the viewport for the playback device context using the ratios formed by the specified multiplicands and divisors.

### EmfScaleWindowExtEx {#EmfScaleWindowExtEx}
```
public static final long EmfScaleWindowExtEx
```


This record redefines the window for the playback device context using the ratios formed by the specified multiplicands and divisors.

### EmfSelectClipPath {#EmfSelectClipPath}
```
public static final long EmfSelectClipPath
```


This record defines the current path as a clipping region for the playback device context, combining the new region with any existing clipping region using the specified mode.

### EmfSelectObject {#EmfSelectObject}
```
public static final long EmfSelectObject
```


This record adds an object to the playback device context, identifying it by its index in the EMF Object Table (section 3.1.1.1).

### EmfSelectPalette {#EmfSelectPalette}
```
public static final long EmfSelectPalette
```


This record adds a LogPalette (section 2.2.17) object to the playback device context, identifying it by its index in the EMF Object Table.

### EmfSetArcDirection {#EmfSetArcDirection}
```
public static final long EmfSetArcDirection
```


This record defines the drawing direction to be used for arc and rectangle operations.

### EmfSetBkColor {#EmfSetBkColor}
```
public static final long EmfSetBkColor
```


This record defines the background color.

### EmfSetBkMode {#EmfSetBkMode}
```
public static final long EmfSetBkMode
```


This record defines the background mix mode of the playback device context. The background mix mode is used with text, hatched brushes, and pen styles that are not solid lines.

### EmfSetBrushOrgEx {#EmfSetBrushOrgEx}
```
public static final long EmfSetBrushOrgEx
```


This record defines the origin of the current brush.

### EmfSetColorAdjustment {#EmfSetColorAdjustment}
```
public static final long EmfSetColorAdjustment
```


This record defines the color adjustment values for the playback device context using the specified values.

### EmfSetColorSpace {#EmfSetColorSpace}
```
public static final long EmfSetColorSpace
```


This record defines the current logical color space object for graphics operations.

### EmfSetDiBitsToDevice {#EmfSetDiBitsToDevice}
```
public static final long EmfSetDiBitsToDevice
```


This record specifies a block transfer of pixels from specified scan lines of a source bitmap to a destination rectangle.

### EmfSetIcmMode {#EmfSetIcmMode}
```
public static final long EmfSetIcmMode
```


This record specifies the mode of Image Color Management (ICM) for graphics operations.

### EmfSetIcmProfileA {#EmfSetIcmProfileA}
```
public static final long EmfSetIcmProfileA
```


This record specifies a color profile in a file with a name consisting of ASCII characters, for graphics output.

### EmfSetIcmProfileW {#EmfSetIcmProfileW}
```
public static final long EmfSetIcmProfileW
```


This record specifies a color profile in a file with a name consisting of Unicode characters, for graphics output

### EmfSetLayout {#EmfSetLayout}
```
public static final long EmfSetLayout
```


This record specifies the order in which text and graphics are drawn

### EmfSetLinkedUfis {#EmfSetLinkedUfis}
```
public static final long EmfSetLinkedUfis
```


This record sets the UniversalFontIds of linked fonts to use during character lookup.

### EmfSetMapperFlags {#EmfSetMapperFlags}
```
public static final long EmfSetMapperFlags
```


This record specifies parameters of the process of matching logical fonts to physical fonts, which is performed by the font mapper.

### EmfSetMetaRgn {#EmfSetMetaRgn}
```
public static final long EmfSetMetaRgn
```


This record intersects the current clipping region for the playback device context with the current meta region and saves the combined region as the new meta region. The clipping region is reset to a null region.

### EmfSetMiterLimit {#EmfSetMiterLimit}
```
public static final long EmfSetMiterLimit
```


This record defines the limit for the length of miter joins for the playback device context.

### EmfSetPaletteEntries {#EmfSetPaletteEntries}
```
public static final long EmfSetPaletteEntries
```


This record defines RGB (red-green-blue) color values in a range of entries in a LogPalette object.

### EmfSetPixelV {#EmfSetPixelV}
```
public static final long EmfSetPixelV
```


This record defines the color of the pixel at the specified logical coordinates.

### EmfSetPolyFillMode {#EmfSetPolyFillMode}
```
public static final long EmfSetPolyFillMode
```


This record defines polygon fill mode.

### EmfSetRop2 {#EmfSetRop2}
```
public static final long EmfSetRop2
```


This record defines binary raster operation mode.

### EmfSetStrechBltMode {#EmfSetStrechBltMode}
```
public static final long EmfSetStrechBltMode
```


This record defines bitmap stretch mode.

### EmfSetTextAlign {#EmfSetTextAlign}
```
public static final long EmfSetTextAlign
```


This record defines text alignment.

### EmfSetTextColor {#EmfSetTextColor}
```
public static final long EmfSetTextColor
```


This record defines the current text color.

### EmfSetTextJustification {#EmfSetTextJustification}
```
public static final long EmfSetTextJustification
```


This record specifies the amount of extra space to add to break characters for justification purposes.

### EmfSetViewportExtEx {#EmfSetViewportExtEx}
```
public static final long EmfSetViewportExtEx
```


This record defines the viewport extent.

### EmfSetViewportOrgEx {#EmfSetViewportOrgEx}
```
public static final long EmfSetViewportOrgEx
```


This record defines the viewport origin.

### EmfSetWindowExtEx {#EmfSetWindowExtEx}
```
public static final long EmfSetWindowExtEx
```


This record defines the window extent.

### EmfSetWindowOrgEx {#EmfSetWindowOrgEx}
```
public static final long EmfSetWindowOrgEx
```


This record defines the window origin.

### EmfSetWorldTransform {#EmfSetWorldTransform}
```
public static final long EmfSetWorldTransform
```


This record defines a two-dimensional linear transformation between world space and page space (for more information, see [MSDN-WRLDPGSPC]) for the playback device context. This transformation can be used to scale, rotate, shear, or translate graphics output.

### EmfSmallTextOut {#EmfSmallTextOut}
```
public static final long EmfSmallTextOut
```


This record outputs a string.

### EmfStretchBlt {#EmfStretchBlt}
```
public static final long EmfStretchBlt
```


This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

### EmfStretchDiBits {#EmfStretchDiBits}
```
public static final long EmfStretchDiBits
```


This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, optionally in combination with a brush pattern, according to a specified raster operation, stretching or compressing the output to fit the dimensions of the destination, if necessary.

### EmfStrokeAndFillPath {#EmfStrokeAndFillPath}
```
public static final long EmfStrokeAndFillPath
```


This record closes any open figures in a path, strokes the outline of the path by using the current pen, and fills its interior by using the current brush.

### EmfStrokePath {#EmfStrokePath}
```
public static final long EmfStrokePath
```


This record renders the specified path by using the current pen.

### EmfTransparentBlt {#EmfTransparentBlt}
```
public static final long EmfTransparentBlt
```


This record specifies a block transfer of pixels from a source bitmap to a destination rectangle, treating a specified color as transparent, stretching or compressing the output to fit the dimensions of the destination, if necessary

### EmfWidenPath {#EmfWidenPath}
```
public static final long EmfWidenPath
```


This record redefines the current path as the area that would be painted if the path were stroked using the pen currently selected into the playback device context.

### EnumSeparatorCharArray {#EnumSeparatorCharArray}
```
public static final char[] EnumSeparatorCharArray
```


### Clone() {#Clone--}
```
public System.Enum Clone()
```




**Returns:**
com.aspose.ms.System.Enum
### CloneTo(T arg0) {#CloneTo-T-}
```
public abstract void CloneTo(T arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | T |  |

### CloneTo(System.Enum arg0) {#CloneTo-com.aspose.ms.System.Enum-}
```
public void CloneTo(System.Enum arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### format(System.Type arg0, Object arg1, String arg2) {#format-com.aspose.ms.System.Type-java.lang.Object-java.lang.String-}
```
public static String format(System.Type arg0, Object arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### format(Class<?> arg0, long arg1, String arg2) {#format-java.lang.Class----long-java.lang.String-}
```
public static String format(Class<?> arg0, long arg1, String arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |
| arg2 | java.lang.String |  |

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getName(System.Type arg0, Object arg1) {#getName-com.aspose.ms.System.Type-java.lang.Object-}
```
public static String getName(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.String
### getName(Class<?> arg0, long arg1) {#getName-java.lang.Class----long-}
```
public static String getName(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### getNames(System.Type arg0) {#getNames-com.aspose.ms.System.Type-}
```
public static String[] getNames(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
java.lang.String[]
### getNames(Class<?> arg0) {#getNames-java.lang.Class----}
```
public static Collection<String> getNames(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.util.Collection<java.lang.String>
### getUnderlyingType(System.Type arg0) {#getUnderlyingType-com.aspose.ms.System.Type-}
```
public static System.Type getUnderlyingType(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Type
### getUnderlyingType(Class<?> arg0) {#getUnderlyingType-java.lang.Class----}
```
public static Class<? extends Number> getUnderlyingType(Class<?> arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |

**Returns:**
java.lang.Class<? extends java.lang.Number>
### getValue(Class<?> arg0, String arg1) {#getValue-java.lang.Class----java.lang.String-}
```
public static long getValue(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### getValues(System.Type arg0) {#getValues-com.aspose.ms.System.Type-}
```
public static System.Array getValues(System.Type arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |

**Returns:**
com.aspose.ms.System.Array
### get_Value() {#get-Value--}
```
public long get_Value()
```




**Returns:**
long
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefined(System.Type arg0, Object arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.Object-}
```
public static boolean isDefined(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
boolean
### isDefined(System.Type arg0, String arg1) {#isDefined-com.aspose.ms.System.Type-java.lang.String-}
```
public static boolean isDefined(System.Type arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
boolean
### isDefined(System.Type arg0, long arg1) {#isDefined-com.aspose.ms.System.Type-long-}
```
public static boolean isDefined(System.Type arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | long |  |

**Returns:**
boolean
### isDefined(Class<?> arg0, long arg1) {#isDefined-java.lang.Class----long-}
```
public static boolean isDefined(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parse(System.Type arg0, String arg1) {#parse-com.aspose.ms.System.Type-java.lang.String-}
```
public static long parse(System.Type arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(System.Type arg0, String arg1, Boolean arg2) {#parse-com.aspose.ms.System.Type-java.lang.String-java.lang.Boolean-}
```
public static long parse(System.Type arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1) {#parse-java.lang.Class----java.lang.String-}
```
public static long parse(Class<?> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |

**Returns:**
long
### parse(Class<?> arg0, String arg1, Boolean arg2) {#parse-java.lang.Class----java.lang.String-java.lang.Boolean-}
```
public static long parse(Class<?> arg0, String arg1, Boolean arg2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | java.lang.String |  |
| arg2 | java.lang.Boolean |  |

**Returns:**
long
### register(System.Enum.AbstractEnum arg0) {#register-com.aspose.ms.System.Enum.AbstractEnum-}
```
public static void register(System.Enum.AbstractEnum arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Enum.AbstractEnum |  |

### toObject(System.Type arg0, Object arg1) {#toObject-com.aspose.ms.System.Type-java.lang.Object-}
```
public static Object toObject(System.Type arg0, Object arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | com.aspose.ms.System.Type |  |
| arg1 | java.lang.Object |  |

**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(Class<?> arg0, long arg1) {#toString-java.lang.Class----long-}
```
public static String toString(Class<?> arg0, long arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Class<?> |  |
| arg1 | long |  |

**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

