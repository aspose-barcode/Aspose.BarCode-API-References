---
title: RecognitionAreaSettings
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: 
type: docs
weight: 21
url: /fr/androidjava/com.aspose.barcode.component.barcodescanner/recognitionareasettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionAreaSettings implements Parcelable
```
## Champs

| Champ | Description |
| --- | --- |
| [CREATOR](#CREATOR) |  |
| [DEFAULT_1D_RECOGNITION_AREA_SETTINGS](#DEFAULT-1D-RECOGNITION-AREA-SETTINGS) |  |
| [DEFAULT_2D_RECOGNITION_AREA_SETTINGS](#DEFAULT-2D-RECOGNITION-AREA-SETTINGS) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | Obtient la couleur de peinture du cadre du scanner de code-barres |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | Obtient la hauteur maximale de la zone de reconnaissance |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | Obtient la largeur maximale de la zone de reconnaissance |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | Obtient le style de la ligne de la zone de code-barres 1D |
| [getOneDLineColor()](#getOneDLineColor--) | Obtient la couleur du marqueur de reconnaissance 1D |
| [getOneDLineWidth()](#getOneDLineWidth--) | Obtient la largeur de la ligne de bordure de la zone 1D |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | Obtient la couleur de peinture de la zone de reconnaissance de code-barres |
| [getTopOffset()](#getTopOffset--) | Obtient le décalage de la zone de reconnaissance depuis le haut de l'écran TODO en pourcentages |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | Obtient le style de la ligne de la zone de code-barres 2D |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | Renvoie le rayon des coins arrondis |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | Obtient le style de la bordure de la zone de code-barres 2D |
| [getTwoDLineColor()](#getTwoDLineColor--) | Obtient la couleur du marqueur de reconnaissance 2D |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | Obtient la largeur de la ligne de bordure de la zone 2D |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | Obtient le rapport entre la largeur et la hauteur de la zone de reconnaissance |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | définit la couleur de peinture du cadre du scanner de code-barres |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | Définit la hauteur maximale de la zone de reconnaissance |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | Définit la largeur maximale de la zone de reconnaissance |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Définit le style de la ligne de la zone de code-barres 1D |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | Définit la couleur du marqueur de reconnaissance 1D |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | Définit la largeur de la ligne de bordure de la zone 1D |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | Définit la couleur de peinture de la zone de reconnaissance du code-barres |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | Définit le décalage de la zone de reconnaissance depuis le haut de l'écran |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Définit le style de la ligne de la zone de code-barres 2D |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | Renvoie le rayon des coins arrondis |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | Définit le style de la bordure de la zone de code-barres 2D |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | Définit la couleur du marqueur de reconnaissance 1D |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | Définit la largeur de la ligne de bordure de la zone 2D |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | Définit le ratio entre la largeur et la hauteur de la zone de reconnaissance |
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
| Paramètre | Type | Description |
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


Obtient la couleur de peinture du cadre du scanner de code-barres

**Returns:**
int -
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


Obtient la hauteur maximale de la zone de reconnaissance

**Returns:**
float - la hauteur maximale de la zone de reconnaissance
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


Obtient la largeur maximale de la zone de reconnaissance

**Returns:**
float - la largeur maximale de la zone de reconnaissance
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


Obtient le style de la ligne de la zone de code-barres 1D

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


Obtient la couleur du marqueur de reconnaissance 1D

**Returns:**
int - la couleur du marqueur de reconnaissance 1D
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


Obtient la largeur de la ligne de bordure de la zone 1D

**Returns:**
float - la largeur de la ligne de bordure de la zone 1D
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


Obtient la couleur de peinture de la zone de reconnaissance de code-barres

**Returns:**
int -
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


Obtient le décalage de la zone de reconnaissance depuis le haut de l'écran TODO en pourcentages

**Returns:**
float - le décalage de la zone de reconnaissance depuis le haut de l'écran
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


Obtient le style de la ligne de la zone de code-barres 2D

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 2D BarcodeArea line
### getTwoDAreaCornerRadius() {#getTwoDAreaCornerRadius--}
```
public float getTwoDAreaCornerRadius()
```


Renvoie le rayon des coins arrondis

**Returns:**
float - rayon des coins arrondis
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


Obtient le style de la bordure de la zone de code-barres 2D

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - style de la bordure de la zone de code-barres 2D
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


Obtient la couleur du marqueur de reconnaissance 2D

**Returns:**
int - la couleur du marqueur de reconnaissance 1D
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


Obtient la largeur de la ligne de bordure de la zone 2D

**Returns:**
float - la largeur de la ligne de bordure de la zone 2D
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


Obtient le rapport entre la largeur et la hauteur de la zone de reconnaissance

**Returns:**
float - ratio entre la largeur et la hauteur de la zone de reconnaissance
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
boolean - visibilité de la zone de reconnaissance
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


définit la couleur de peinture du cadre du scanner de code-barres

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


Définit la hauteur maximale de la zone de reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| maxAreaHeight | float | la hauteur maximale de la zone de reconnaissance |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


Définit la largeur maximale de la zone de reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| maxAreaWidth | float | la largeur maximale de la zone de reconnaissance |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


Définit le style de la ligne de la zone de code-barres 1D

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | style de la ligne de la zone de code-barres 1D |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


Définit la couleur du marqueur de reconnaissance 1D

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| oneDLineColor | int | la couleur du marqueur de reconnaissance 1D |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


Définit la largeur de la ligne de bordure de la zone 1D

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| oneDLineWidth | float | la largeur de la ligne de bordure de la zone 1D |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


Définit la couleur de peinture de la zone de reconnaissance du code-barres

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognitionAreaColor | int | couleur de la zone de reconnaissance du code-barres. Si la couleur n'est pas transparente, la zone de reconnaissance du code-barres ne sera pas transparente |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | Visibilité de la zone de reconnaissance |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


Définit le décalage de la zone de reconnaissance depuis le haut de l'écran

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| topOffset | float | le décalage de la zone de reconnaissance depuis le haut de l'écran |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


Définit le style de la ligne de la zone de code-barres 2D

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | style de la ligne de la zone de code-barres 2D |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


Renvoie le rayon des coins arrondis

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| twoDAreaCornerRadius | float | rayon des coins arrondis |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


Définit le style de la bordure de la zone de code-barres 2D

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | style de la bordure de la zone de code-barres 2D |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


Définit la couleur du marqueur de reconnaissance 1D

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| twoDLineColor | int | la couleur du marqueur de reconnaissance 1D |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


Définit la largeur de la ligne de bordure de la zone 2D

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| twoDLineWidth | float | la largeur de la ligne de bordure de la zone 2D |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


Définit le ratio entre la largeur et la hauteur de la zone de reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| areaRatio | float | ratio entre la largeur et la hauteur de la zone de reconnaissance |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

