---
title: RecognitionAreaSettings
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: 
type: docs
weight: 21
url: /es/androidjava/com.aspose.barcode.component.barcodescanner/recognitionareasettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionAreaSettings implements Parcelable
```
## Campos

| Campo | Descripción |
| --- | --- |
| [CREATOR](#CREATOR) |  |
| [DEFAULT_1D_RECOGNITION_AREA_SETTINGS](#DEFAULT-1D-RECOGNITION-AREA-SETTINGS) |  |
| [DEFAULT_2D_RECOGNITION_AREA_SETTINGS](#DEFAULT-2D-RECOGNITION-AREA-SETTINGS) |  |
## Methods

| Method | Descripción |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFrameColor()](#getFrameColor--) | Obtiene el color de pintura del marco del escáner de códigos de barras |
| [getMaxAreaHeight()](#getMaxAreaHeight--) | Obtiene la altura máxima del área de reconocimiento |
| [getMaxAreaWidth()](#getMaxAreaWidth--) | Obtiene el ancho máximo del área de reconocimiento |
| [getOneDAreaBarcodeLineStyle()](#getOneDAreaBarcodeLineStyle--) | Obtiene el estilo de la línea del área de código de barras 1D |
| [getOneDLineColor()](#getOneDLineColor--) | Obtiene el color del marcador de reconocimiento 1D |
| [getOneDLineWidth()](#getOneDLineWidth--) | Obtiene el ancho de la línea del borde del área 1D |
| [getRecognitionAreaColor()](#getRecognitionAreaColor--) | Obtiene el color de pintura del área de reconocimiento de códigos de barras |
| [getTopOffset()](#getTopOffset--) | Obtiene el desplazamiento del área de reconocimiento desde la parte superior de la pantalla TODO en porcentajes |
| [getTwoDAreaBarcodeLineStyle()](#getTwoDAreaBarcodeLineStyle--) | Obtiene el estilo de la línea del área de código de barras 2D |
| [getTwoDAreaCornerRadius()](#getTwoDAreaCornerRadius--) | Devuelve el radio de la esquina redondeada |
| [getTwoDAreaStyle()](#getTwoDAreaStyle--) | Obtiene el estilo del borde del área de código de barras 2D |
| [getTwoDLineColor()](#getTwoDLineColor--) | Obtiene el color del marcador de reconocimiento 2D |
| [getTwoDLineWidth()](#getTwoDLineWidth--) | Obtiene el ancho de la línea del borde del área 2D |
| [getWidthHeightAreaRatio()](#getWidthHeightAreaRatio--) | Obtiene la proporción entre el ancho y la altura del área de reconocimiento |
| [hashCode()](#hashCode--) |  |
| [isRecognizeOnlyInRecognitionArea()](#isRecognizeOnlyInRecognitionArea--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFrameColor(int frameColor)](#setFrameColor-int-) | establece el color de pintura del marco del escáner de códigos de barras |
| [setMaxAreaHeight(float maxAreaHeight)](#setMaxAreaHeight-float-) | Establece la altura máxima del área de reconocimiento |
| [setMaxAreaWidth(float maxAreaWidth)](#setMaxAreaWidth-float-) | Establece el ancho máximo del área de reconocimiento |
| [setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)](#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Establece el estilo de la línea de BarcodeArea 1D |
| [setOneDLineColor(int oneDLineColor)](#setOneDLineColor-int-) | Establece el color del marcador de reconocimiento 1D |
| [setOneDLineWidth(float oneDLineWidth)](#setOneDLineWidth-float-) | Establece el ancho de la línea del borde del área 1D |
| [setRecognitionAreaColor(int recognitionAreaColor)](#setRecognitionAreaColor-int-) | Establece el color de pintura del área de reconocimiento de código de barras |
| [setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)](#setRecognizeOnlyInRecognitionArea-boolean-) |  |
| [setTopOffset(float topOffset)](#setTopOffset-float-) | Establece el desplazamiento del área de reconocimiento desde la parte superior de la pantalla |
| [setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)](#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-) | Establece el estilo de la línea de BarcodeArea 2D |
| [setTwoDAreaCornerRadius(float twoDAreaCornerRadius)](#setTwoDAreaCornerRadius-float-) | Devuelve el radio de la esquina redondeada |
| [setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)](#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-) | Establece el estilo del borde de BarcodeArea 2D |
| [setTwoDLineColor(int twoDLineColor)](#setTwoDLineColor-int-) | Establece el color del marcador de reconocimiento 1D |
| [setTwoDLineWidth(float twoDLineWidth)](#setTwoDLineWidth-float-) | Establece el ancho de la línea del borde del área 2D |
| [setWidthHeightAreaRatio(float areaRatio)](#setWidthHeightAreaRatio-float-) | Establece la proporción entre el ancho y la altura del área de reconocimiento |
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
| Parameter | Type | Descripción |
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


Obtiene el color de pintura del marco del escáner de códigos de barras

**Returns:**
int -
### getMaxAreaHeight() {#getMaxAreaHeight--}
```
public float getMaxAreaHeight()
```


Obtiene la altura máxima del área de reconocimiento

**Returns:**
float - la altura máxima del área de reconocimiento
### getMaxAreaWidth() {#getMaxAreaWidth--}
```
public float getMaxAreaWidth()
```


Obtiene el ancho máximo del área de reconocimiento

**Returns:**
float - el ancho máximo del área de reconocimiento
### getOneDAreaBarcodeLineStyle() {#getOneDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getOneDAreaBarcodeLineStyle()
```


Obtiene el estilo de la línea del área de código de barras 1D

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 1D BarcodeArea line
### getOneDLineColor() {#getOneDLineColor--}
```
public int getOneDLineColor()
```


Obtiene el color del marcador de reconocimiento 1D

**Returns:**
int - el color del marcador de reconocimiento 1D
### getOneDLineWidth() {#getOneDLineWidth--}
```
public float getOneDLineWidth()
```


Obtiene el ancho de la línea del borde del área 1D

**Returns:**
float - el ancho de la línea del borde del área 1D
### getRecognitionAreaColor() {#getRecognitionAreaColor--}
```
public int getRecognitionAreaColor()
```


Obtiene el color de pintura del área de reconocimiento de códigos de barras

**Returns:**
int -
### getTopOffset() {#getTopOffset--}
```
public float getTopOffset()
```


Obtiene el desplazamiento del área de reconocimiento desde la parte superior de la pantalla TODO en porcentajes

**Returns:**
float - el desplazamiento del área de reconocimiento desde la parte superior de la pantalla
### getTwoDAreaBarcodeLineStyle() {#getTwoDAreaBarcodeLineStyle--}
```
public BarcodeAreaLineStyle getTwoDAreaBarcodeLineStyle()
```


Obtiene el estilo de la línea del área de código de barras 2D

**Returns:**
[BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) - style of 2D BarcodeArea line
### getTwoDAreaCornerRadius() {#getTwoDAreaCornerRadius--}
```
public float getTwoDAreaCornerRadius()
```


Devuelve el radio de la esquina redondeada

**Returns:**
float - radio de esquina redondeada
### getTwoDAreaStyle() {#getTwoDAreaStyle--}
```
public TwoDAreaStyle getTwoDAreaStyle()
```


Obtiene el estilo del borde del área de código de barras 2D

**Returns:**
com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle - estilo del borde de BarcodeArea 2D
### getTwoDLineColor() {#getTwoDLineColor--}
```
public int getTwoDLineColor()
```


Obtiene el color del marcador de reconocimiento 2D

**Returns:**
int - el color del marcador de reconocimiento 1D
### getTwoDLineWidth() {#getTwoDLineWidth--}
```
public float getTwoDLineWidth()
```


Obtiene el ancho de la línea del borde del área 2D

**Returns:**
float - el ancho de la línea del borde del área 2D
### getWidthHeightAreaRatio() {#getWidthHeightAreaRatio--}
```
public float getWidthHeightAreaRatio()
```


Obtiene la proporción entre el ancho y la altura del área de reconocimiento

**Returns:**
float - proporción entre el ancho y la altura del área de reconocimiento
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
boolean - Visibilidad del área de reconocimiento
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


establece el color de pintura del marco del escáner de códigos de barras

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| frameColor | int |  |

### setMaxAreaHeight(float maxAreaHeight) {#setMaxAreaHeight-float-}
```
public void setMaxAreaHeight(float maxAreaHeight)
```


Establece la altura máxima del área de reconocimiento

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| maxAreaHeight | float | la altura máxima del área de reconocimiento |

### setMaxAreaWidth(float maxAreaWidth) {#setMaxAreaWidth-float-}
```
public void setMaxAreaWidth(float maxAreaWidth)
```


Establece el ancho máximo del área de reconocimiento

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| maxAreaWidth | float | el ancho máximo del área de reconocimiento |

### setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle) {#setOneDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setOneDAreaBarcodeLineStyle(BarcodeAreaLineStyle oneDAreaBarcodeLineStyle)
```


Establece el estilo de la línea de BarcodeArea 1D

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| oneDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | estilo de la línea del área de código de barras 1D |

### setOneDLineColor(int oneDLineColor) {#setOneDLineColor-int-}
```
public void setOneDLineColor(int oneDLineColor)
```


Establece el color del marcador de reconocimiento 1D

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| oneDLineColor | int | el color del marcador de reconocimiento 1D |

### setOneDLineWidth(float oneDLineWidth) {#setOneDLineWidth-float-}
```
public void setOneDLineWidth(float oneDLineWidth)
```


Establece el ancho de la línea del borde del área 1D

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| oneDLineWidth | float | el ancho de la línea del borde del área 1D |

### setRecognitionAreaColor(int recognitionAreaColor) {#setRecognitionAreaColor-int-}
```
public void setRecognitionAreaColor(int recognitionAreaColor)
```


Establece el color de pintura del área de reconocimiento de código de barras

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| recognitionAreaColor | int | color del área de reconocimiento de código de barras. Si el color no es transparente, el área de reconocimiento de código de barras no será transparente |

### setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea) {#setRecognizeOnlyInRecognitionArea-boolean-}
```
public void setRecognizeOnlyInRecognitionArea(boolean recognizeOnlyInRecognitionArea)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| recognizeOnlyInRecognitionArea | boolean | Visibilidad del área de reconocimiento |

### setTopOffset(float topOffset) {#setTopOffset-float-}
```
public void setTopOffset(float topOffset)
```


Establece el desplazamiento del área de reconocimiento desde la parte superior de la pantalla

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| topOffset | float | el desplazamiento del área de reconocimiento desde la parte superior de la pantalla |

### setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle) {#setTwoDAreaBarcodeLineStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.BarcodeAreaLineStyle-}
```
public void setTwoDAreaBarcodeLineStyle(BarcodeAreaLineStyle twoDAreaBarcodeLineStyle)
```


Establece el estilo de la línea de BarcodeArea 2D

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| twoDAreaBarcodeLineStyle | [BarcodeAreaLineStyle](../../com.aspose.barcode.component.barcodescanner.recognitionareaview/barcodearealinestyle) | estilo de la línea del área de código de barras 2D |

### setTwoDAreaCornerRadius(float twoDAreaCornerRadius) {#setTwoDAreaCornerRadius-float-}
```
public void setTwoDAreaCornerRadius(float twoDAreaCornerRadius)
```


Devuelve el radio de la esquina redondeada

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| twoDAreaCornerRadius | float | radio de esquina redondeada |

### setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle) {#setTwoDAreaStyle-com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle-}
```
public void setTwoDAreaStyle(TwoDAreaStyle twoDAreaStyle)
```


Establece el estilo del borde de BarcodeArea 2D

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| twoDAreaStyle | com.aspose.barcode.component.barcodescanner.recognitionareaview.TwoDAreaStyle | estilo del borde del área de código de barras 2D |

### setTwoDLineColor(int twoDLineColor) {#setTwoDLineColor-int-}
```
public void setTwoDLineColor(int twoDLineColor)
```


Establece el color del marcador de reconocimiento 1D

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| twoDLineColor | int | el color del marcador de reconocimiento 1D |

### setTwoDLineWidth(float twoDLineWidth) {#setTwoDLineWidth-float-}
```
public void setTwoDLineWidth(float twoDLineWidth)
```


Establece el ancho de la línea del borde del área 2D

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| twoDLineWidth | float | el ancho de la línea del borde del área 2D |

### setWidthHeightAreaRatio(float areaRatio) {#setWidthHeightAreaRatio-float-}
```
public void setWidthHeightAreaRatio(float areaRatio)
```


Establece la proporción entre el ancho y la altura del área de reconocimiento

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| areaRatio | float | relación entre el ancho y la altura del área de reconocimiento |

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
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| arg0 | largo |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

