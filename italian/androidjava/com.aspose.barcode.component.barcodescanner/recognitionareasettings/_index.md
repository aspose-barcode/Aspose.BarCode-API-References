---
title: RecognitionAreaSettings
second_title: Aspose.BarCode per Android via Java API Reference
description: 
type: docs
weight: 21
url: /it/androidjava/com.aspose.barcode.component.barcodescanner/recognitionareasettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionAreaSettings implements Parcelable
```
## Campi

| Campo | Descrizione |
| --- | --- |
| [CREATOR](#CREATOR) |  |
| [DEFAULT_1D_RECOGNITION_AREA_SETTINGS](#DEFAULT-1D-RECOGNITION-AREA-SETTINGS) |  |
| [DEFAULT_2D_RECOGNITION_AREA_SETTINGS](#DEFAULT-2D-RECOGNITION-AREA-SETTINGS) |  |
## Methods

| Method | Descrizione |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | Restituisce il colore di pittura della cornice dello scanner di codici a barre |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | Restituisce l'altezza massima dell'area di riconoscimento |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | Restituisce la larghezza massima dell'area di riconoscimento |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | Restituisce lo stile della linea di 1D BarcodeArea |
| [getOneDLineColor()](#getOneDLineColor--) | Restituisce il colore del marcatore di riconoscimento 1D |
| [getOneDLineWidth()](#getOneDLineWidth--) | Restituisce la larghezza della linea del bordo dell'area 1D |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | Restituisce il colore di pittura dell'area di riconoscimento del codice a barre |
| [getTopOffset()](#getTopOffset--) | Restituisce lo spostamento dell'area di riconoscimento dall'alto dello schermo TODO in percentuale |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | Restituisce lo stile della linea di 2D BarcodeArea |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | Restituisce il raggio degli angoli arrotondati |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | Restituisce lo stile del bordo di 2D BarcodeArea |
| [getTwoDLineColor()](#getTwoDLineColor--) | Restituisce il colore del marcatore di riconoscimento 2D |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | Restituisce la larghezza della linea del bordo dell'area 2D |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | Restituisce il rapporto tra larghezza e altezza dell'area di riconoscimento |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | Imposta il colore di pittura della cornice dello scanner di codici a barre |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | Imposta l'altezza massima dell'area di riconoscimento |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | Imposta la larghezza massima dell'area di riconoscimento |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Imposta lo stile della linea dell'area BarcodeArea 1D |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | Imposta il colore del marcatore di riconoscimento 1D |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | Imposta la larghezza della linea del bordo dell'area 1D |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | Imposta il colore di pittura dell'area di riconoscimento del codice a barre |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | Imposta lo spostamento dell'area di riconoscimento dalla parte superiore dello schermo |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Imposta lo stile della linea dell'area BarcodeArea 2D |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | Restituisce il raggio degli angoli arrotondati |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | Imposta lo stile del bordo dell'area BarcodeArea 2D |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | Imposta il colore del marcatore di riconoscimento 1D |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | Imposta la larghezza della linea del bordo dell'area 2D |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | Imposta il rapporto tra larghezza e altezza dell'area di riconoscimento |
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
| Parameter | Type | Descrizione |
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


Restituisce il colore di pittura della cornice dello scanner di codici a barre

**Returns:**
int -
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


Restituisce l'altezza massima dell'area di riconoscimento

**Returns:**
float - l'altezza massima dell'area di riconoscimento
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


Restituisce la larghezza massima dell'area di riconoscimento

**Returns:**
float - la larghezza massima dell'area di riconoscimento
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


Restituisce lo stile della linea di 1D BarcodeArea

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


Restituisce il colore del marcatore di riconoscimento 1D

**Returns:**
int - il colore del marcatore di riconoscimento 1D
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


Restituisce la larghezza della linea del bordo dell'area 1D

**Returns:**
float - la larghezza della linea del bordo dell'area 1D
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


Restituisce il colore di pittura dell'area di riconoscimento del codice a barre

**Returns:**
int -
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


Restituisce lo spostamento dell'area di riconoscimento dall'alto dello schermo TODO in percentuale

**Returns:**
float - lo spostamento dell'area di riconoscimento dalla parte superiore dello schermo
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


Restituisce lo stile della linea di 2D BarcodeArea

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 2D BarcodeArea line
### getTwoDAreaCornerRadius() {#getTwoDAreaCornerRadius--}
```
public float getTwoDAreaCornerRadius()
```


Restituisce il raggio degli angoli arrotondati

**Returns:**
float - raggio dell'angolo arrotondato
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


Restituisce lo stile del bordo di 2D BarcodeArea

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - stile del bordo dell'area BarcodeArea 2D
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


Restituisce il colore del marcatore di riconoscimento 2D

**Returns:**
int - il colore del marcatore di riconoscimento 1D
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


Restituisce la larghezza della linea del bordo dell'area 2D

**Returns:**
float - la larghezza della linea del bordo dell'area 2D
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


Restituisce il rapporto tra larghezza e altezza dell'area di riconoscimento

**Returns:**
float - rapporto tra larghezza e altezza dell'area di riconoscimento
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
boolean - Visibilità dell'area di riconoscimento
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


Imposta il colore di pittura della cornice dello scanner di codici a barre

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


Imposta l'altezza massima dell'area di riconoscimento

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| maxAreaHeight | float | l'altezza massima dell'area di riconoscimento |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


Imposta la larghezza massima dell'area di riconoscimento

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| maxAreaWidth | float | la larghezza massima dell'area di riconoscimento |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


Imposta lo stile della linea dell'area BarcodeArea 1D

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | stile della linea dell'area codice a barre 1D |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


Imposta il colore del marcatore di riconoscimento 1D

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| oneDLineColor | int | il colore del marcatore di riconoscimento 1D |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


Imposta la larghezza della linea del bordo dell'area 1D

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| oneDLineWidth | float | la larghezza della linea del bordo dell'area 1D |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


Imposta il colore di pittura dell'area di riconoscimento del codice a barre

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| recognitionAreaColor | int | colore dell'area di riconoscimento del codice a barre. Se il colore non è trasparente, l'area di riconoscimento del codice a barre non sarà trasparente |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | Visibilità dell'area di riconoscimento |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


Imposta lo spostamento dell'area di riconoscimento dalla parte superiore dello schermo

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| topOffset | float | l'offset dell'area di riconoscimento dalla parte superiore dello schermo |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


Imposta lo stile della linea dell'area BarcodeArea 2D

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | stile della linea dell'area codice a barre 2D |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


Restituisce il raggio degli angoli arrotondati

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| twoDAreaCornerRadius | float | raggio dell'angolo arrotondato |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


Imposta lo stile del bordo dell'area BarcodeArea 2D

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | stile del bordo dell'area codice a barre 2D |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


Imposta il colore del marcatore di riconoscimento 1D

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| twoDLineColor | int | il colore del marcatore di riconoscimento 1D |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


Imposta la larghezza della linea del bordo dell'area 2D

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| twoDLineWidth | float | la larghezza della linea del bordo dell'area 2D |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


Imposta il rapporto tra larghezza e altezza dell'area di riconoscimento

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| areaRatio | float | rapporto tra larghezza e altezza dell'area di riconoscimento |

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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

