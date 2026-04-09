---
title: RecognitionAreaSettings
second_title: Aspose.BarCode for Android via Java API-referens
description: 
type: docs
weight: 21
url: /sv/androidjava/com.aspose.barcode.component.barcodescanner/recognitionareasettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionAreaSettings implements Parcelable
```
## Fält

| Fält | Beskrivning |
| --- | --- |
| [CREATOR](#CREATOR) |  |
| [DEFAULT_1D_RECOGNITION_AREA_SETTINGS](#DEFAULT-1D-RECOGNITION-AREA-SETTINGS) |  |
| [DEFAULT_2D_RECOGNITION_AREA_SETTINGS](#DEFAULT-2D-RECOGNITION-AREA-SETTINGS) |  |
## Methods

| Method | Beskrivning |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | Hämtar färgen på streckkodsskannerns ram |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | Hämtar den maximala höjden för igenkänningsområdet |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | Hämtar den maximala bredden för igenkänningsområdet |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | Hämtar stil för 1D BarcodeArea-linje |
| [getOneDLineColor()](#getOneDLineColor--) | Hämtar färgen på 1D-igenkänningsmarkören |
| [getOneDLineWidth()](#getOneDLineWidth--) | Hämtar bredden på 1D-områdets kantlinje |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | Hämtar färgen på streckkodens igenkänningsområde |
| [getTopOffset()](#getTopOffset--) | Hämtar förskjutningen för igenkänningsområdet från skärmens topp (TODO i procent) |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | Hämtar stil för 2D BarcodeArea-linje |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | Returnerar radien för rundade hörn |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | Hämtar stil för 2D BarcodeArea-kant |
| [getTwoDLineColor()](#getTwoDLineColor--) | Hämtar färgen på 2D-igenkänningsmarkören |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | Hämtar bredden på 2D-områdets kantlinje |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | Hämtar förhållandet mellan bredd och höjd för igenkänningsområdet |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | sätter färgen på streckkodsskannerns ram |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | Sätter den maximala höjden för igenkänningsområdet |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | Ställer in den maximala bredden för igenkänningsområdet |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Ställer in stil för 1D BarcodeArea-linje |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | Ställer in färgen på 1D-igenkänningsmarkören |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | Ställer in bredden på 1D-områdets kantlinje |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | Ställer in målningens färg för barcode-igenkänningsområdet |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | Ställer in förskjutningen för igenkänningsområdet från skärmens topp |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Ställer in stil för 2D BarcodeArea-linje |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | Returnerar radien för rundade hörn |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | Ställer in stil för 2D BarcodeArea-kant |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | Ställer in färgen på 1D-igenkänningsmarkören |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | Ställer in bredden på 2D-områdets kantlinje |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | Ställer in förhållandet mellan bredd och höjd för igenkänningsområdet |
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
| Parameter | Type | Beskrivning |
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


Hämtar färgen på streckkodsskannerns ram

**Returns:**
int -
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


Hämtar den maximala höjden för igenkänningsområdet

**Returns:**
float - den maximala höjden för igenkänningsområdet
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


Hämtar den maximala bredden för igenkänningsområdet

**Returns:**
float - den maximala bredden för igenkänningsområdet
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


Hämtar stil för 1D BarcodeArea-linje

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


Hämtar färgen på 1D-igenkänningsmarkören

**Returns:**
int - färgen på 1D-igenkänningsmarkören
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


Hämtar bredden på 1D-områdets kantlinje

**Returns:**
float - bredden på 1D-områdets kantlinje
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


Hämtar färgen på streckkodens igenkänningsområde

**Returns:**
int -
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


Hämtar förskjutningen för igenkänningsområdet från skärmens topp (TODO i procent)

**Returns:**
float - förskjutningen för igenkänningsområdet från skärmens topp
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


Hämtar stil för 2D BarcodeArea-linje

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 2D BarcodeArea line
### getTwoDAreaCornerRadius() {#getTwoDAreaCornerRadius--}
```
public float getTwoDAreaCornerRadius()
```


Returnerar radien för rundade hörn

**Returns:**
float - radie för rundade hörn
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


Hämtar stil för 2D BarcodeArea-kant

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - stil för 2D BarcodeArea-kant
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


Hämtar färgen på 2D-igenkänningsmarkören

**Returns:**
int - färgen på 1D-igenkänningsmarkören
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


Hämtar bredden på 2D-områdets kantlinje

**Returns:**
float - bredden på 2D-områdets kantlinje
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


Hämtar förhållandet mellan bredd och höjd för igenkänningsområdet

**Returns:**
float - förhållandet mellan bredd och höjd för igenkänningsområdet
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
boolean - Synlighet för igenkänningsområdet
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


sätter färgen på streckkodsskannerns ram

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


Sätter den maximala höjden för igenkänningsområdet

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| maxAreaHeight | float | den maximala höjden för igenkänningsområdet |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


Ställer in den maximala bredden för igenkänningsområdet

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| maxAreaWidth | float | the recognition area max width |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


Ställer in stil för 1D BarcodeArea-linje

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | style of 1D BarcodeArea line |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


Ställer in färgen på 1D-igenkänningsmarkören

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| oneDLineColor | int | the color of 1D recognition marker |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


Ställer in bredden på 1D-områdets kantlinje

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| oneDLineWidth | float | the width of 1D area border line |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


Ställer in målningens färg för barcode-igenkänningsområdet

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| recognitionAreaColor | int | color of barcode recognition area. If color will not transparent, barcode recognition area will not transparent |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | Visibility of the recognition area |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


Ställer in förskjutningen för igenkänningsområdet från skärmens topp

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| topOffset | float | the recognition area offset from top of screen |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


Ställer in stil för 2D BarcodeArea-linje

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | style of 2D BarcodeArea line |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


Returnerar radien för rundade hörn

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| twoDAreaCornerRadius | float | rounded corner radius |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


Ställer in stil för 2D BarcodeArea-kant

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | style of 2D BarcodeArea border |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


Ställer in färgen på 1D-igenkänningsmarkören

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| twoDLineColor | int | the color of 1D recognition marker |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


Ställer in bredden på 2D-områdets kantlinje

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| twoDLineWidth | float | the width of 2D area border line |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


Ställer in förhållandet mellan bredd och höjd för igenkänningsområdet

**Parameters:**
| Parameter | Type | Beskrivning |
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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

