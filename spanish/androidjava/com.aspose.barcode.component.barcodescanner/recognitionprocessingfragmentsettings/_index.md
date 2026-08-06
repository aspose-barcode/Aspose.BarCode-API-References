---
title: RecognitionProcessingFragmentSettings
second_title: Referencia de API de Aspose.BarCode para Android mediante Java
description: 
type: docs
weight: 27
url: /es/androidjava/com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionProcessingFragmentSettings implements Parcelable
```
## Campos

| Campo | Descripción |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Descripción |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundDuringRecognitionProcess()](#getBackgroundDuringRecognitionProcess--) | Obtiene el fondo que se renderizará durante el proceso de reconocimiento |
| [getClass()](#getClass--) |  |
| [getProgressBarColor()](#getProgressBarColor--) | Obtiene el color de la barra de progreso que se renderiza durante el reconocimiento |
| [getProgressBarSize()](#getProgressBarSize--) | Obtiene el tamaño de la barra de progreso que se renderiza durante el reconocimiento |
| [getRecognitionCancelButtonRightOffset()](#getRecognitionCancelButtonRightOffset--) | Obtiene el desplazamiento desde el borde derecho del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento |
| [getRecognitionCancelButtonText()](#getRecognitionCancelButtonText--) | Obtiene el texto del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento |
| [getRecognitionCancelButtonTextColor()](#getRecognitionCancelButtonTextColor--) | Obtiene el color del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento |
| [getRecognitionCancelButtonTextSize()](#getRecognitionCancelButtonTextSize--) | Obtiene el tamaño del texto del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento |
| [getRecognitionCancelButtonVisibility()](#getRecognitionCancelButtonVisibility--) | Obtiene la visibilidad del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento |
| [getRecognitionProcessAboveLabelText()](#getRecognitionProcessAboveLabelText--) | Obtiene el texto de TextView que se renderiza encima de la barra de progreso durante el reconocimiento |
| [getRecognitionProcessAboveLabelTextColor()](#getRecognitionProcessAboveLabelTextColor--) | Obtiene el color de TextView que se renderiza encima de la barra de progreso durante el reconocimiento |
| [getRecognitionProcessAboveLabelTextSize()](#getRecognitionProcessAboveLabelTextSize--) | Obtiene el tamaño del texto de TextView que se renderiza encima de la barra de progreso durante el reconocimiento |
| [getRecognitionProcessAboveLabelTextVisible()](#getRecognitionProcessAboveLabelTextVisible--) | Obtiene el color de TextView que se renderiza encima de la barra de progreso durante el reconocimiento |
| [hashCode()](#hashCode--) |  |
| [importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)](#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-) | Importa la configuración |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)](#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-) | Establece el fondo que se renderizará durante el proceso de reconocimiento |
| [setProgressBarColor(int progressBarColor)](#setProgressBarColor-int-) | Establece el color de la barra de progreso que se renderiza durante el reconocimiento |
| [setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)](#setRecognitionCancelButtonRightOffset-int-) | Establece el desplazamiento desde el borde derecho del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento |
| [setRecognitionCancelButtonText(String recognitionCancelButtonText)](#setRecognitionCancelButtonText-java.lang.String-) | Establece el texto del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento |
| [setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)](#setRecognitionCancelButtonTextColor-int-) | Establece el color del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento |
| [setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)](#setRecognitionCancelButtonTextSize-float-) | Establece el tamaño del texto del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento |
| [setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)](#setRecognitionCancelButtonVisibility-boolean-) | Establece la visibilidad del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento |
| [setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)](#setRecognitionProcessAboveLabelText-java.lang.String-) | Establece el texto de TextView que se renderiza encima de la barra de progreso durante el reconocimiento |
| [setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)](#setRecognitionProcessAboveLabelTextColor-int-) | Establece el color de TextView que se renderiza encima de la barra de progreso durante el reconocimiento |
| [setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)](#setRecognitionProcessAboveLabelTextSize-int-) | Establece el tamaño del texto de TextView que se renderiza encima de la barra de progreso durante el reconocimiento |
| [setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)](#setRecognitionProcessAboveLabelTextVisible-boolean-) | Establece el color de TextView que se renderiza encima de la barra de progreso durante el reconocimiento |
| [setRecognitionProgressBarSize(int progressBarSize)](#setRecognitionProgressBarSize-int-) | Establece el tamaño de la barra de progreso que se renderiza durante el reconocimiento |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<RecognitionProcessingFragmentSettings> CREATOR
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
### getBackgroundDuringRecognitionProcess() {#getBackgroundDuringRecognitionProcess--}
```
public RecognitionProcessFragmentBackground getBackgroundDuringRecognitionProcess()
```


Obtiene el fondo que se renderizará durante el proceso de reconocimiento

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground - el fondo que se renderizará durante el proceso de reconocimiento
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getProgressBarColor() {#getProgressBarColor--}
```
public int getProgressBarColor()
```


Obtiene el color de la barra de progreso que se renderiza durante el reconocimiento

**Returns:**
int - color de la barra de progreso
### getProgressBarSize() {#getProgressBarSize--}
```
public int getProgressBarSize()
```


Obtiene el tamaño de la barra de progreso que se renderiza durante el reconocimiento

**Returns:**
int - tamaño de la barra de progreso
### getRecognitionCancelButtonRightOffset() {#getRecognitionCancelButtonRightOffset--}
```
public int getRecognitionCancelButtonRightOffset()
```


Obtiene el desplazamiento desde el borde derecho del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento

**Returns:**
int - desplazamiento desde el borde derecho del botón "Cancel"
### getRecognitionCancelButtonText() {#getRecognitionCancelButtonText--}
```
public String getRecognitionCancelButtonText()
```


Obtiene el texto del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento

**Returns:**
java.lang.String - texto del botón "Cancel" que se muestra debajo de la barra de progreso
### getRecognitionCancelButtonTextColor() {#getRecognitionCancelButtonTextColor--}
```
public int getRecognitionCancelButtonTextColor()
```


Obtiene el color del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento

**Returns:**
int - color del botón "Cancel" que se muestra debajo de la barra de progreso
### getRecognitionCancelButtonTextSize() {#getRecognitionCancelButtonTextSize--}
```
public float getRecognitionCancelButtonTextSize()
```


Obtiene el tamaño del texto del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento

**Returns:**
float - tamaño del texto del botón "Cancel" que se muestra debajo de la barra de progreso
### getRecognitionCancelButtonVisibility() {#getRecognitionCancelButtonVisibility--}
```
public boolean getRecognitionCancelButtonVisibility()
```


Obtiene la visibilidad del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento

**Returns:**
boolean - visibilidad del botón "Cancel"
### getRecognitionProcessAboveLabelText() {#getRecognitionProcessAboveLabelText--}
```
public String getRecognitionProcessAboveLabelText()
```


Obtiene el texto de TextView que se renderiza encima de la barra de progreso durante el reconocimiento

**Returns:**
java.lang.String - texto del TextView que se muestra encima de la barra de progreso
### getRecognitionProcessAboveLabelTextColor() {#getRecognitionProcessAboveLabelTextColor--}
```
public int getRecognitionProcessAboveLabelTextColor()
```


Obtiene el color de TextView que se renderiza encima de la barra de progreso durante el reconocimiento

**Returns:**
int - color del TextView que se muestra encima de la barra de progreso
### getRecognitionProcessAboveLabelTextSize() {#getRecognitionProcessAboveLabelTextSize--}
```
public float getRecognitionProcessAboveLabelTextSize()
```


Obtiene el tamaño del texto de TextView que se renderiza encima de la barra de progreso durante el reconocimiento

**Returns:**
float - tamaño del texto del TextView que se muestra encima de la barra de progreso
### getRecognitionProcessAboveLabelTextVisible() {#getRecognitionProcessAboveLabelTextVisible--}
```
public boolean getRecognitionProcessAboveLabelTextVisible()
```


Obtiene el color de TextView que se renderiza encima de la barra de progreso durante el reconocimiento

**Returns:**
boolean - color del TextView que se muestra encima de la barra de progreso
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings) {#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-}
```
public void importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)
```


Importa la configuración

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| recognitionProcessingFragmentSettings | com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage) {#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-}
```
public void setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)
```


Establece el fondo que se renderizará durante el proceso de reconocimiento

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| backgroundImage | com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground | el fondo que se mostrará durante el proceso de reconocimiento |

### setProgressBarColor(int progressBarColor) {#setProgressBarColor-int-}
```
public void setProgressBarColor(int progressBarColor)
```


Establece el color de la barra de progreso que se renderiza durante el reconocimiento

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| progressBarColor | int | color de la barra de progreso |

### setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset) {#setRecognitionCancelButtonRightOffset-int-}
```
public void setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)
```


Establece el desplazamiento desde el borde derecho del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| recognitionCancelButtonRightOffset | int | desplazamiento desde el borde derecho del botón "Cancel" |

### setRecognitionCancelButtonText(String recognitionCancelButtonText) {#setRecognitionCancelButtonText-java.lang.String-}
```
public void setRecognitionCancelButtonText(String recognitionCancelButtonText)
```


Establece el texto del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| recognitionCancelButtonText | java.lang.String | texto del botón "Cancel" que se muestra debajo de la barra de progreso |

### setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor) {#setRecognitionCancelButtonTextColor-int-}
```
public void setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)
```


Establece el color del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| recognitionCancelButtonTextColor | int | color del botón "Cancel" que se muestra debajo de la barra de progreso |

### setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize) {#setRecognitionCancelButtonTextSize-float-}
```
public void setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)
```


Establece el tamaño del texto del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| recognitionCancelButtonTextSize | float | tamaño de texto del botón "Cancelar" que se muestra debajo del progreso |

### setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible) {#setRecognitionCancelButtonVisibility-boolean-}
```
public void setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)
```


Establece la visibilidad del botón "Cancelar" que se renderiza debajo de la barra de progreso durante el reconocimiento

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| recognitionCancelButtonVisible | boolean | visibilidad del botón "Cancelar" |

### setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText) {#setRecognitionProcessAboveLabelText-java.lang.String-}
```
public void setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)
```


Establece el texto de TextView que se renderiza encima de la barra de progreso durante el reconocimiento

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| recognitionProcessAboveLabelText | java.lang.String | texto del TextView que se muestra encima de la barra de progreso |

### setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor) {#setRecognitionProcessAboveLabelTextColor-int-}
```
public void setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)
```


Establece el color de TextView que se renderiza encima de la barra de progreso durante el reconocimiento

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| recognitionProcessAboveLabelTextColor | int | color del TextView que se muestra encima de la barra de progreso |

### setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize) {#setRecognitionProcessAboveLabelTextSize-int-}
```
public void setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)
```


Establece el tamaño del texto de TextView que se renderiza encima de la barra de progreso durante el reconocimiento

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| recognitionAboveLabelTextSize | int | tamaño de texto del TextView que se muestra encima de la barra de progreso |

### setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible) {#setRecognitionProcessAboveLabelTextVisible-boolean-}
```
public void setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)
```


Establece el color de TextView que se renderiza encima de la barra de progreso durante el reconocimiento

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| recognitionProcessAboveLabelTextVisible | boolean | color del TextView que se muestra encima de la barra de progreso |

### setRecognitionProgressBarSize(int progressBarSize) {#setRecognitionProgressBarSize-int-}
```
public void setRecognitionProgressBarSize(int progressBarSize)
```


Establece el tamaño de la barra de progreso que se renderiza durante el reconocimiento

**Parameters:**
| Parameter | Type | Descripción |
| --- | --- | --- |
| progressBarSize | int | tamaño de la barra de progreso |

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

