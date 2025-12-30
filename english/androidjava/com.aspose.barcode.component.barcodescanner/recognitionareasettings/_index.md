---
title: RecognitionAreaSettings
second_title: Aspose.BarCode for Android via Java API Reference
description: 
type: docs
weight: 21
url: /androidjava/com.aspose.barcode.component.barcodescanner/recognitionareasettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionAreaSettings implements Parcelable
```
## Fields

| Field | Description |
| --- | --- |
| [CREATOR](#CREATOR) |  |
| [DEFAULT_1D_RECOGNITION_AREA_SETTINGS](#DEFAULT-1D-RECOGNITION-AREA-SETTINGS) |  |
| [DEFAULT_2D_RECOGNITION_AREA_SETTINGS](#DEFAULT-2D-RECOGNITION-AREA-SETTINGS) |  |
## Methods

| Method | Description |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | Gets the paint color of barcode scanner frame |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | Gets the recognition area max height |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | Gets the recognition area max width |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | Gets style of 1D BarcodeArea line |
| [getOneDLineColor()](#getOneDLineColor--) | Gets the color of 1D recognition marker |
| [getOneDLineWidth()](#getOneDLineWidth--) | Gets the width of 1D area border line |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | Gets the paint color of barcode recognition area |
| [getTopOffset()](#getTopOffset--) | Gets the recognition area offset from top of screen TODO in percents |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | Gets style of 2D BarcodeArea line |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | Returns rounded corner radius |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | Gets style of 2D BarcodeArea border |
| [getTwoDLineColor()](#getTwoDLineColor--) | Gets the color of 2D recognition marker |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | Gets the width of 2D area border line |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | Gets ratio between width and height of the recognition area |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | sets the paint color of barcode scanner frame |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | Sets the recognition area max height |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | Sets the recognition area max width |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Sets style of 1D BarcodeArea line |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | Sets the color of 1D recognition marker |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | Sets the width of 1D area border line |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | Sets the paint color of barcode recognition area |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | Sets the recognition area offset from top of screen |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Sets style of 2D BarcodeArea line |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | Returns rounded corner radius |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | Sets style of 2D BarcodeArea border |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | Sets the color of 1D recognition marker |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | Sets the width of 2D area border line |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | Sets ratio between width and height of the recognition area |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<RecognitionAreaSettings> CREATOR
```


### DEFAULT_1D_RECOGNITION_AREA_SETTINGS {#DEFAULT-1D-RECOGNITION-AREA-SETTINGS}
```
public static final RecognitionAreaSettings DEFAULT_1D_RECOGNITION_AREA_SETTINGS
```


### DEFAULT_2D_RECOGNITION_AREA_SETTINGS {#DEFAULT-2D-RECOGNITION-AREA-SETTINGS}
```
public static final RecognitionAreaSettings DEFAULT_2D_RECOGNITION_AREA_SETTINGS
```


### describeContents() {#describeContents--}
```
public int describeContents()
```




**Returns:**
int
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFrameColor() {#getFrameColor--}
```
public int getFrameColor()
```


Gets the paint color of barcode scanner frame

**Returns:**
int - 
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


Gets the recognition area max height

**Returns:**
float - the recognition area max height
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


Gets the recognition area max width

**Returns:**
float - the recognition area max width
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


Gets style of 1D BarcodeArea line

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


Gets the color of 1D recognition marker

**Returns:**
int - the color of 1D recognition marker
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


Gets the width of 1D area border line

**Returns:**
float - the width of 1D area border line
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


Gets the paint color of barcode recognition area

**Returns:**
int - 
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


Gets the recognition area offset from top of screen TODO in percents

**Returns:**
float - the recognition area offset from top of screen
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


Gets style of 2D BarcodeArea line

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 2D BarcodeArea line
### getTwoDAreaCornerRadius() {#getTwoDAreaCornerRadius--}
```
public float getTwoDAreaCornerRadius()
```


Returns rounded corner radius

**Returns:**
float - rounded corner radius
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


Gets style of 2D BarcodeArea border

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - style of 2D BarcodeArea border
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


Gets the color of 2D recognition marker

**Returns:**
int - the color of 1D recognition marker
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


Gets the width of 2D area border line

**Returns:**
float - the width of 2D area border line
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


Gets ratio between width and height of the recognition area

**Returns:**
float - ratio between width and height of the recognition area
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isRecognizeOnlyInRecognitionArea() {#isRecognizeOnlyInRecognitionArea--}
```
public boolean isRecognizeOnlyInRecognitionArea()
```




**Returns:**
boolean - Visibility of the recognition area
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFrameColor(int frameColor) {#setFrameColor-int-}
```
public void setFrameColor(int frameColor)
```


sets the paint color of barcode scanner frame

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


Sets the recognition area max height

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxAreaHeight | float | the recognition area max height |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


Sets the recognition area max width

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxAreaWidth | float | the recognition area max width |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


Sets style of 1D BarcodeArea line

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | style of 1D BarcodeArea line |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


Sets the color of 1D recognition marker

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oneDLineColor | int | the color of 1D recognition marker |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


Sets the width of 1D area border line

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oneDLineWidth | float | the width of 1D area border line |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


Sets the paint color of barcode recognition area

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionAreaColor | int | color of barcode recognition area. If color will not transparent, barcode recognition area will not transparent |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | Visibility of the recognition area |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


Sets the recognition area offset from top of screen

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| topOffset | float | the recognition area offset from top of screen |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


Sets style of 2D BarcodeArea line

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | style of 2D BarcodeArea line |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


Returns rounded corner radius

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| twoDAreaCornerRadius | float | rounded corner radius |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


Sets style of 2D BarcodeArea border

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | style of 2D BarcodeArea border |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


Sets the color of 1D recognition marker

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| twoDLineColor | int | the color of 1D recognition marker |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


Sets the width of 2D area border line

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| twoDLineWidth | float | the width of 2D area border line |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


Sets ratio between width and height of the recognition area

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| areaRatio | float | ratio between width and height of the recognition area |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

