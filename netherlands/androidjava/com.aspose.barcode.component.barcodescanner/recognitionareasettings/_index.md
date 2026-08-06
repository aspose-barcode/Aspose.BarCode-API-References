---
title: RecognitionAreaSettings
second_title: Aspose.BarCode for Android via Java API-referentie
description: 
type: docs
weight: 21
url: /nl/androidjava/com.aspose.barcode.component.barcodescanner/recognitionareasettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionAreaSettings implements Parcelable
```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [CREATOR](#CREATOR) |  |
| [DEFAULT_1D_RECOGNITION_AREA_SETTINGS](#DEFAULT-1D-RECOGNITION-AREA-SETTINGS) |  |
| [DEFAULT_2D_RECOGNITION_AREA_SETTINGS](#DEFAULT-2D-RECOGNITION-AREA-SETTINGS) |  |
## Methods

| Method | Beschrijving |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | Haalt de verfkleur van het barcode-scannerframe op |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | Haalt de maximale hoogte van het herkenningsgebied op |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | Haalt de maximale breedte van het herkenningsgebied op |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | Haalt de stijl van de 1D-BarcodeArea-lijn op |
| [getOneDLineColor()](#getOneDLineColor--) | Haalt de kleur van de 1D-herkenningsmarker op |
| [getOneDLineWidth()](#getOneDLineWidth--) | Haalt de breedte van de 1D-gebiedsrandlijn op |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | Haalt de verfkleur van het barcode-herkenningsgebied op |
| [getTopOffset()](#getTopOffset--) | Haalt de offset van het herkenningsgebied ten opzichte van de bovenkant van het scherm op (TODO in procenten) |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | Haalt de stijl van de 2D-BarcodeArea-lijn op |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | Retourneert de radius van afgeronde hoeken |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | Haalt de stijl van de 2D-BarcodeArea-rand op |
| [getTwoDLineColor()](#getTwoDLineColor--) | Haalt de kleur van de 2D-herkenningsmarker op |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | Haalt de breedte van de 2D-gebiedsrandlijn op |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | Haalt de verhouding tussen breedte en hoogte van het herkenningsgebied op |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | Stelt de verfkleur van het barcode-scannerframe in |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | Stelt de maximale hoogte van het herkenningsgebied in |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | Stelt de maximale breedte van het herkenningsgebied in |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Stelt de stijl van de 1D BarcodeArea-lijn in |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | Stelt de kleur van de 1D herkenningsmarkering in |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | Stelt de breedte van de 1D gebiedsrandlijn in |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | Stelt de verfkleur van het barcode-herkenningsgebied in |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | Stelt de offset van het herkenningsgebied vanaf de bovenkant van het scherm in |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Stelt de stijl van de 2D BarcodeArea-lijn in |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | Retourneert de radius van afgeronde hoeken |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | Stelt de stijl van de 2D BarcodeArea-rand in |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | Stelt de kleur van de 1D herkenningsmarkering in |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | Stelt de breedte van de 2D gebiedsrandlijn in |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | Stelt de verhouding tussen breedte en hoogte van het herkenningsgebied in |
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
| Parameter | Type | Beschrijving |
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


Haalt de verfkleur van het barcode-scannerframe op

**Returns:**
int -
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


Haalt de maximale hoogte van het herkenningsgebied op

**Returns:**
float - de maximale hoogte van het herkenningsgebied
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


Haalt de maximale breedte van het herkenningsgebied op

**Returns:**
float - de maximale breedte van het herkenningsgebied
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


Haalt de stijl van de 1D-BarcodeArea-lijn op

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


Haalt de kleur van de 1D-herkenningsmarker op

**Returns:**
int - de kleur van de 1D herkenningsmarkering
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


Haalt de breedte van de 1D-gebiedsrandlijn op

**Returns:**
float - de breedte van de 1D gebiedsrandlijn
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


Haalt de verfkleur van het barcode-herkenningsgebied op

**Returns:**
int -
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


Haalt de offset van het herkenningsgebied ten opzichte van de bovenkant van het scherm op (TODO in procenten)

**Returns:**
float - de offset van het herkenningsgebied vanaf de bovenkant van het scherm
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


Haalt de stijl van de 2D-BarcodeArea-lijn op

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 2D BarcodeArea line
### getTwoDAreaCornerRadius() {#getTwoDAreaCornerRadius--}
```
public float getTwoDAreaCornerRadius()
```


Retourneert de radius van afgeronde hoeken

**Returns:**
float - afgeronde hoekstraal
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


Haalt de stijl van de 2D-BarcodeArea-rand op

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - stijl van de 2D BarcodeArea-rand
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


Haalt de kleur van de 2D-herkenningsmarker op

**Returns:**
int - de kleur van de 1D herkenningsmarkering
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


Haalt de breedte van de 2D-gebiedsrandlijn op

**Returns:**
float - de breedte van de 2D gebiedsrandlijn
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


Haalt de verhouding tussen breedte en hoogte van het herkenningsgebied op

**Returns:**
float - verhouding tussen breedte en hoogte van het herkenningsgebied
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
boolean - Zichtbaarheid van het herkenningsgebied
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


Stelt de verfkleur van het barcode-scannerframe in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


Stelt de maximale hoogte van het herkenningsgebied in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxAreaHeight | float | de maximale hoogte van het herkenningsgebied |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


Stelt de maximale breedte van het herkenningsgebied in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxAreaWidth | float | de maximale breedte van het herkenningsgebied |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


Stelt de stijl van de 1D BarcodeArea-lijn in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | stijl van 1D BarcodeArea-lijn |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


Stelt de kleur van de 1D herkenningsmarkering in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oneDLineColor | int | de kleur van de 1D herkenningsmarkering |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


Stelt de breedte van de 1D gebiedsrandlijn in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oneDLineWidth | float | de breedte van de 1D gebiedsrandlijn |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


Stelt de verfkleur van het barcode-herkenningsgebied in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionAreaColor | int | kleur van het barcode-herkenningsgebied. Als de kleur niet transparant is, zal het barcode-herkenningsgebied niet transparant zijn |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | Zichtbaarheid van het herkenningsgebied |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


Stelt de offset van het herkenningsgebied vanaf de bovenkant van het scherm in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| topOffset | float | de offset van het herkenningsgebied vanaf de bovenkant van het scherm |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


Stelt de stijl van de 2D BarcodeArea-lijn in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | stijl van 2D BarcodeArea-lijn |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


Retourneert de radius van afgeronde hoeken

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| twoDAreaCornerRadius | float | radius van afgeronde hoek |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


Stelt de stijl van de 2D BarcodeArea-rand in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | stijl van 2D BarcodeArea-rand |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


Stelt de kleur van de 1D herkenningsmarkering in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| twoDLineColor | int | de kleur van de 1D herkenningsmarkering |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


Stelt de breedte van de 2D gebiedsrandlijn in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| twoDLineWidth | float | de breedte van de 2D gebiedsrandlijn |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


Stelt de verhouding tussen breedte en hoogte van het herkenningsgebied in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| areaRatio | float | verhouding tussen breedte en hoogte van het herkenningsgebied |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

