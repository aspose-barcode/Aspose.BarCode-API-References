---
title: "RecognitionAreaSettings"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: 
type: docs
weight: 21
url: /de/androidjava/com.aspose.barcode.component.barcodescanner/recognitionareasettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionAreaSettings implements Parcelable
```
## Felder

| Feld | Beschreibung |
| --- | --- |
| [CREATOR](#CREATOR) |  |
| [DEFAULT_1D_RECOGNITION_AREA_SETTINGS](#DEFAULT-1D-RECOGNITION-AREA-SETTINGS) |  |
| [DEFAULT_2D_RECOGNITION_AREA_SETTINGS](#DEFAULT-2D-RECOGNITION-AREA-SETTINGS) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | Ermittelt die Farbe des Barcode-Scanner-Rahmens |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | Ermittelt die maximale Höhe des Erkennungsbereichs |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | Ermittelt die maximale Breite des Erkennungsbereichs |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | Ermittelt den Stil der 1D BarcodeArea-Linie |
| [getOneDLineColor()](#getOneDLineColor--) | Ermittelt die Farbe des 1D-Erkennungsmarkers |
| [getOneDLineWidth()](#getOneDLineWidth--) | Ermittelt die Breite der 1D-Bereichsrandlinie |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | Ermittelt die Farbe des Barcode-Erkennungsbereichs |
| [getTopOffset()](#getTopOffset--) | Ermittelt den Versatz des Erkennungsbereichs vom oberen Bildschirmrand (TODO in Prozent) |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | Ermittelt den Stil der 2D BarcodeArea-Linie |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | Gibt den Radius der abgerundeten Ecken zurück |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | Ermittelt den Stil der 2D BarcodeArea-Grenze |
| [getTwoDLineColor()](#getTwoDLineColor--) | Ermittelt die Farbe des 2D-Erkennungsmarkers |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | Ermittelt die Breite der 2D-Bereichsrandlinie |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | Ermittelt das Verhältnis zwischen Breite und Höhe des Erkennungsbereichs |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | setzt die Farbe des Barcode-Scanner-Rahmens |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | Setzt die maximale Höhe des Erkennungsbereichs |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | Setzt die maximale Breite des Erkennungsbereichs |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Legt den Stil der 1D-BarcodeArea-Linie fest |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | Legt die Farbe des 1D-Erkennungsmarkers fest |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | Legt die Breite der 1D-Flächenrandlinie fest |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | Legt die Farbe des Barcode-Erkennungsbereichs fest |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | Legt den Versatz des Erkennungsbereichs vom oberen Bildschirmrand fest |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Legt den Stil der 2D-BarcodeArea-Linie fest |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | Gibt den Radius der abgerundeten Ecken zurück |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | Legt den Stil des 2D-BarcodeArea-Rands fest |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | Legt die Farbe des 1D-Erkennungsmarkers fest |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | Legt die Breite der 2D-Flächenrandlinie fest |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | Legt das Verhältnis zwischen Breite und Höhe des Erkennungsbereichs fest |
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
| Parameter | Typ | Beschreibung |
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


Ermittelt die Farbe des Barcode-Scanner-Rahmens

**Returns:**
int -
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


Ermittelt die maximale Höhe des Erkennungsbereichs

**Returns:**
float - die maximale Höhe des Erkennungsbereichs
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


Ermittelt die maximale Breite des Erkennungsbereichs

**Returns:**
float - die maximale Breite des Erkennungsbereichs
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


Ermittelt den Stil der 1D BarcodeArea-Linie

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


Ermittelt die Farbe des 1D-Erkennungsmarkers

**Returns:**
int - die Farbe des 1D-Erkennungsmarkers
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


Ermittelt die Breite der 1D-Bereichsrandlinie

**Returns:**
float - die Breite der 1D-Flächenrandlinie
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


Ermittelt die Farbe des Barcode-Erkennungsbereichs

**Returns:**
int -
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


Ermittelt den Versatz des Erkennungsbereichs vom oberen Bildschirmrand (TODO in Prozent)

**Returns:**
float - der Versatz des Erkennungsbereichs vom oberen Bildschirmrand
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


Ermittelt den Stil der 2D BarcodeArea-Linie

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 2D BarcodeArea line
### getTwoDAreaCornerRadius() {#getTwoDAreaCornerRadius--}
```
public float getTwoDAreaCornerRadius()
```


Gibt den Radius der abgerundeten Ecken zurück

**Returns:**
float - Radius der abgerundeten Ecke
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


Ermittelt den Stil der 2D BarcodeArea-Grenze

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - Stil des 2D-BarcodeArea-Rands
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


Ermittelt die Farbe des 2D-Erkennungsmarkers

**Returns:**
int - die Farbe des 1D-Erkennungsmarkers
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


Ermittelt die Breite der 2D-Bereichsrandlinie

**Returns:**
float - die Breite der 2D-Flächenrandlinie
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


Ermittelt das Verhältnis zwischen Breite und Höhe des Erkennungsbereichs

**Returns:**
float - Verhältnis zwischen Breite und Höhe des Erkennungsbereichs
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
boolean - Sichtbarkeit des Erkennungsbereichs
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


setzt die Farbe des Barcode-Scanner-Rahmens

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


Setzt die maximale Höhe des Erkennungsbereichs

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxAreaHeight | float | die maximale Höhe des Erkennungsbereichs |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


Setzt die maximale Breite des Erkennungsbereichs

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| maxAreaWidth | float | die maximale Breite des Erkennungsbereichs |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


Legt den Stil der 1D-BarcodeArea-Linie fest

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | Stil der 1D BarcodeArea Linie |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


Legt die Farbe des 1D-Erkennungsmarkers fest

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oneDLineColor | int | die Farbe des 1D Erkennungsmarkers |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


Legt die Breite der 1D-Flächenrandlinie fest

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oneDLineWidth | float | die Breite der 1D Bereichsrandlinie |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


Legt die Farbe des Barcode-Erkennungsbereichs fest

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recognitionAreaColor | int | Farbe des Barcode-Erkennungsbereichs. Wenn die Farbe nicht transparent ist, wird der Barcode-Erkennungsbereich nicht transparent sein. |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | Sichtbarkeit des Erkennungsbereichs |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


Legt den Versatz des Erkennungsbereichs vom oberen Bildschirmrand fest

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| topOffset | float | der Erkennungsbereichsversatz vom oberen Bildschirmrand |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


Legt den Stil der 2D-BarcodeArea-Linie fest

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | Stil der 2D BarcodeArea Linie |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


Gibt den Radius der abgerundeten Ecken zurück

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| twoDAreaCornerRadius | float | Radius der abgerundeten Ecke |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


Legt den Stil des 2D-BarcodeArea-Rands fest

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | Stil des 2D BarcodeArea Randes |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


Legt die Farbe des 1D-Erkennungsmarkers fest

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| twoDLineColor | int | die Farbe des 1D Erkennungsmarkers |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


Legt die Breite der 2D-Flächenrandlinie fest

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| twoDLineWidth | float | die Breite der 2D Bereichsrandlinie |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


Legt das Verhältnis zwischen Breite und Höhe des Erkennungsbereichs fest

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| areaRatio | float | Verhältnis zwischen Breite und Höhe des Erkennungsbereichs |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

