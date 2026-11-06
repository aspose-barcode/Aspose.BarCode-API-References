---
title: "RecognitionAreaSettings"
second_title: "Aspose.BarCode för Android via Java API-referens"
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
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | Hämtar färgen på streckkodsskannerens ram |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | Hämtar den maximala höjden för igenkänningsområdet |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | Hämtar den maximala bredden för igenkänningsområdet |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | Hämtar stil för 1D BarcodeArea-linje |
| [getOneDLineColor()](#getOneDLineColor--) | Hämtar färgen på 1D-igenkänningsmarkören |
| [getOneDLineWidth()](#getOneDLineWidth--) | Hämtar bredden på 1D-områdets kantlinje |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | Hämtar färgen på målning av streckkodsgenskapsområdet |
| [getTopOffset()](#getTopOffset--) | Hämtar förskjutningen för igenkänningsområdet från skärmens topp TODO i procent |
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
| [setFrameColor(int frameColor)](#setFrameColor-int-) | sätter färgen på streckkodsskannerens ram |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | Sätter den maximala höjden för igenkänningsområdet |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | Sätter den maximala bredden för igenkänningsområdet |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Ställer in stil för 1D BarcodeArea-linje |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | Ställer in färgen för 1D igenkänningsmarkör |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | Ställer in bredden på 1D områdesramlinje |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | Ställer in målarfärgen för streckkodens igenkänningsområde |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | Ställer in förskjutningen för igenkänningsområdet från skärmens topp |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Ställer in stil för 2D BarcodeArea-linje |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | Returnerar radien för rundade hörn |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | Ställer in stil för 2D BarcodeArea-ram |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | Ställer in färgen för 1D igenkänningsmarkör |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | Ställer in bredden på 2D områdesramlinje |
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
| Parameter | Typ | Beskrivning |
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


Hämtar färgen på streckkodsskannerens ram

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
int - färgen för 1D igenkänningsmarkör
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


Hämtar bredden på 1D-områdets kantlinje

**Returns:**
float - bredden på 1D områdesramlinje
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


Hämtar färgen på målning av streckkodsgenskapsområdet

**Returns:**
int -
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


Hämtar förskjutningen för igenkänningsområdet från skärmens topp TODO i procent

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
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - stil för 2D BarcodeArea-ram
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


Hämtar färgen på 2D-igenkänningsmarkören

**Returns:**
int - färgen för 1D igenkänningsmarkör
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


Hämtar bredden på 2D-områdets kantlinje

**Returns:**
float - bredden på 2D områdesramlinje
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
boolean - synlighet för igenkänningsområdet
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


sätter färgen på streckkodsskannerens ram

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


Sätter den maximala höjden för igenkänningsområdet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| maxAreaHeight | float | den maximala höjden för igenkänningsområdet |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


Sätter den maximala bredden för igenkänningsområdet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| maxAreaWidth | float | den maximala bredden för igenkänningsområdet |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


Ställer in stil för 1D BarcodeArea-linje

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | stil för 1D BarcodeArea-linje |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


Ställer in färgen för 1D igenkänningsmarkör

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oneDLineColor | int | färgen på 1D igenkänningsmarkör |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


Ställer in bredden på 1D områdesramlinje

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oneDLineWidth | float | bredden på 1D-områdets kantlinje |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


Ställer in målarfärgen för streckkodens igenkänningsområde

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recognitionAreaColor | int | färg på barcode recognition area. Om färgen inte är transparent blir barcode recognition area inte transparent |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | Synlighet för recognition area |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


Ställer in förskjutningen för igenkänningsområdet från skärmens topp

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| topOffset | float | offset för recognition area från skärmens topp |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


Ställer in stil för 2D BarcodeArea-linje

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | stil för 2D BarcodeArea-linje |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


Returnerar radien för rundade hörn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| twoDAreaCornerRadius | float | radie för rundade hörn |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


Ställer in stil för 2D BarcodeArea-ram

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | stil för 2D BarcodeArea-kant |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


Ställer in färgen för 1D igenkänningsmarkör

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| twoDLineColor | int | färgen på 1D igenkänningsmarkör |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


Ställer in bredden på 2D områdesramlinje

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| twoDLineWidth | float | bredden på 2D area border line |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


Ställer in förhållandet mellan bredd och höjd för igenkänningsområdet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| areaRatio | float | förhållandet mellan bredd och höjd för recognition area |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

