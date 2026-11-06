---
title: "RecognitionAreaSettings"
second_title: "Riferimento API di Aspose.BarCode per Android via Java"
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
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | Restituisce il colore di pittura del riquadro dello scanner di codici a barre |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | Restituisce l'altezza massima dell'area di riconoscimento |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | Restituisce la larghezza massima dell'area di riconoscimento |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | Restituisce lo stile della linea dell'area codice a barre 1D |
| [getOneDLineColor()](#getOneDLineColor--) | Restituisce il colore del marcatore di riconoscimento 1D |
| [getOneDLineWidth()](#getOneDLineWidth--) | Restituisce la larghezza della linea di bordo dell'area 1D |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | Restituisce il colore di pittura dell'area di riconoscimento del codice a barre |
| [getTopOffset()](#getTopOffset--) | Restituisce l'offset dell'area di riconoscimento dall'alto dello schermo (TODO in percentuali) |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | Restituisce lo stile della linea dell'area codice a barre 2D |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | Restituisce il raggio degli angoli arrotondati |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | Restituisce lo stile del bordo dell'area codice a barre 2D |
| [getTwoDLineColor()](#getTwoDLineColor--) | Restituisce il colore del marcatore di riconoscimento 2D |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | Restituisce la larghezza della linea di bordo dell'area 2D |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | Restituisce il rapporto tra larghezza e altezza dell'area di riconoscimento |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | imposta il colore di pittura del riquadro dello scanner di codici a barre |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | Imposta l'altezza massima dell'area di riconoscimento |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | Imposta la larghezza massima dell'area di riconoscimento |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Imposta lo stile della linea dell'area codice a barre 1D |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | Imposta il colore del marcatore di riconoscimento 1D |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | Imposta la larghezza della linea del bordo dell'area 1D |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | Imposta il colore di pittura dell'area di riconoscimento del codice a barre |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | Imposta lo spostamento dell'area di riconoscimento dall'alto dello schermo |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Imposta lo stile della linea dell'area codice a barre 2D |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | Restituisce il raggio degli angoli arrotondati |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | Imposta lo stile del bordo dell'area codice a barre 2D |
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
| Parametro | Tipo | Descrizione |
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


Restituisce il colore di pittura del riquadro dello scanner di codici a barre

**Returns:**
int -
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


Restituisce l'altezza massima dell'area di riconoscimento

**Returns:**
float - altezza massima dell'area di riconoscimento
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


Restituisce la larghezza massima dell'area di riconoscimento

**Returns:**
float - larghezza massima dell'area di riconoscimento
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


Restituisce lo stile della linea dell'area codice a barre 1D

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


Restituisce il colore del marcatore di riconoscimento 1D

**Returns:**
int - colore del marcatore di riconoscimento 1D
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


Restituisce la larghezza della linea di bordo dell'area 1D

**Returns:**
float - larghezza della linea del bordo dell'area 1D
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


Restituisce l'offset dell'area di riconoscimento dall'alto dello schermo (TODO in percentuali)

**Returns:**
float - spostamento dell'area di riconoscimento dall'alto dello schermo
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


Restituisce lo stile della linea dell'area codice a barre 2D

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


Restituisce lo stile del bordo dell'area codice a barre 2D

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - stile del bordo dell'area codice a barre 2D
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


Restituisce il colore del marcatore di riconoscimento 2D

**Returns:**
int - colore del marcatore di riconoscimento 1D
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


Restituisce la larghezza della linea di bordo dell'area 2D

**Returns:**
float - larghezza della linea del bordo dell'area 2D
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


imposta il colore di pittura del riquadro dello scanner di codici a barre

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


Imposta l'altezza massima dell'area di riconoscimento

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| maxAreaHeight | float | altezza massima dell'area di riconoscimento |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


Imposta la larghezza massima dell'area di riconoscimento

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| maxAreaWidth | float | larghezza massima dell'area di riconoscimento |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


Imposta lo stile della linea dell'area codice a barre 1D

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | stile della linea dell'area codice a barre 1D |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


Imposta il colore del marcatore di riconoscimento 1D

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oneDLineColor | int | il colore del marcatore di riconoscimento 1D |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


Imposta la larghezza della linea del bordo dell'area 1D

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oneDLineWidth | float | la larghezza della linea di bordo dell'area 1D |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


Imposta il colore di pittura dell'area di riconoscimento del codice a barre

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recognitionAreaColor | int | colore dell'area di riconoscimento del codice a barre. Se il colore non è trasparente, l'area di riconoscimento del codice a barre non sarà trasparente |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | Visibilità dell'area di riconoscimento |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


Imposta lo spostamento dell'area di riconoscimento dall'alto dello schermo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| topOffset | float | l'offset dell'area di riconoscimento dalla parte superiore dello schermo |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


Imposta lo stile della linea dell'area codice a barre 2D

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | stile della linea dell'area codice a barre 2D |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


Restituisce il raggio degli angoli arrotondati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| twoDAreaCornerRadius | float | raggio dell'angolo arrotondato |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


Imposta lo stile del bordo dell'area codice a barre 2D

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | stile del bordo dell'area codice a barre 2D |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


Imposta il colore del marcatore di riconoscimento 1D

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| twoDLineColor | int | il colore del marcatore di riconoscimento 1D |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


Imposta la larghezza della linea del bordo dell'area 2D

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| twoDLineWidth | float | la larghezza della linea di bordo dell'area 2D |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


Imposta il rapporto tra larghezza e altezza dell'area di riconoscimento

**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

