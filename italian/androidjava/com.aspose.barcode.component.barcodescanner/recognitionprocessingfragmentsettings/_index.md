---
title: RecognitionProcessingFragmentSettings
second_title: Aspose.BarCode per Android via Java API Reference
description: 
type: docs
weight: 27
url: /it/androidjava/com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionProcessingFragmentSettings implements Parcelable
```
## Campi

| Campo | Descrizione |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Descrizione |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundDuringRecognitionProcess()](#getBackgroundDuringRecognitionProcess--) | Ottiene lo sfondo che verrà renderizzato durante il processo di riconoscimento |
| [getClass()](#getClass--) |  |
| [getProgressBarColor()](#getProgressBarColor--) | Ottiene il colore della barra di avanzamento che viene renderizzata durante il riconoscimento |
| [getProgressBarSize()](#getProgressBarSize--) | Ottiene la dimensione della barra di avanzamento che viene renderizzata durante il riconoscimento |
| [getRecognitionCancelButtonRightOffset()](#getRecognitionCancelButtonRightOffset--) | Ottiene lo spostamento dal bordo destro del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento |
| [getRecognitionCancelButtonText()](#getRecognitionCancelButtonText--) | Ottiene il testo del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento |
| [getRecognitionCancelButtonTextColor()](#getRecognitionCancelButtonTextColor--) | Ottiene il colore del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento |
| [getRecognitionCancelButtonTextSize()](#getRecognitionCancelButtonTextSize--) | Ottiene la dimensione del testo del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento |
| [getRecognitionCancelButtonVisibility()](#getRecognitionCancelButtonVisibility--) | Ottiene la visibilità del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento |
| [getRecognitionProcessAboveLabelText()](#getRecognitionProcessAboveLabelText--) | Ottiene il testo della TextView che viene renderizzata sopra la barra di avanzamento durante il riconoscimento |
| [getRecognitionProcessAboveLabelTextColor()](#getRecognitionProcessAboveLabelTextColor--) | Ottiene il colore della TextView che viene renderizzata sopra la barra di avanzamento durante il riconoscimento |
| [getRecognitionProcessAboveLabelTextSize()](#getRecognitionProcessAboveLabelTextSize--) | Ottiene la dimensione del testo della TextView che viene renderizzata sopra la barra di avanzamento durante il riconoscimento |
| [getRecognitionProcessAboveLabelTextVisible()](#getRecognitionProcessAboveLabelTextVisible--) | Ottiene il colore della TextView che viene renderizzata sopra la barra di avanzamento durante il riconoscimento |
| [hashCode()](#hashCode--) |  |
| [importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)](#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-) | Importa le impostazioni |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)](#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-) | Imposta lo sfondo che verrà renderizzato durante il processo di riconoscimento |
| [setProgressBarColor(int progressBarColor)](#setProgressBarColor-int-) | Imposta il colore della barra di avanzamento che viene renderizzata durante il riconoscimento |
| [setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)](#setRecognitionCancelButtonRightOffset-int-) | Imposta lo spostamento dal bordo destro del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento |
| [setRecognitionCancelButtonText(String recognitionCancelButtonText)](#setRecognitionCancelButtonText-java.lang.String-) | Imposta il testo del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento |
| [setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)](#setRecognitionCancelButtonTextColor-int-) | Imposta il colore del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento |
| [setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)](#setRecognitionCancelButtonTextSize-float-) | Imposta la dimensione del testo del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento |
| [setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)](#setRecognitionCancelButtonVisibility-boolean-) | Imposta la visibilità del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento |
| [setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)](#setRecognitionProcessAboveLabelText-java.lang.String-) | Imposta il testo della TextView che viene renderizzata sopra la barra di avanzamento durante il riconoscimento |
| [setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)](#setRecognitionProcessAboveLabelTextColor-int-) | Imposta il colore della TextView che viene renderizzata sopra la barra di avanzamento durante il riconoscimento |
| [setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)](#setRecognitionProcessAboveLabelTextSize-int-) | Imposta la dimensione del testo della TextView che viene renderizzata sopra la barra di avanzamento durante il riconoscimento |
| [setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)](#setRecognitionProcessAboveLabelTextVisible-boolean-) | Imposta il colore della TextView che viene renderizzata sopra la barra di avanzamento durante il riconoscimento |
| [setRecognitionProgressBarSize(int progressBarSize)](#setRecognitionProgressBarSize-int-) | Imposta la dimensione della barra di avanzamento che viene renderizzata durante il riconoscimento |
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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBackgroundDuringRecognitionProcess() {#getBackgroundDuringRecognitionProcess--}
```
public RecognitionProcessFragmentBackground getBackgroundDuringRecognitionProcess()
```


Ottiene lo sfondo che verrà renderizzato durante il processo di riconoscimento

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground - lo sfondo che verrà renderizzato durante il processo di riconoscimento
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


Ottiene il colore della barra di avanzamento che viene renderizzata durante il riconoscimento

**Returns:**
int - colore della barra di avanzamento
### getProgressBarSize() {#getProgressBarSize--}
```
public int getProgressBarSize()
```


Ottiene la dimensione della barra di avanzamento che viene renderizzata durante il riconoscimento

**Returns:**
int - dimensione della barra di avanzamento
### getRecognitionCancelButtonRightOffset() {#getRecognitionCancelButtonRightOffset--}
```
public int getRecognitionCancelButtonRightOffset()
```


Ottiene lo spostamento dal bordo destro del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento

**Returns:**
int - offset dal bordo destro del pulsante "Cancel"
### getRecognitionCancelButtonText() {#getRecognitionCancelButtonText--}
```
public String getRecognitionCancelButtonText()
```


Ottiene il testo del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento

**Returns:**
java.lang.String - testo del pulsante "Cancel" che viene visualizzato sotto la barra di avanzamento
### getRecognitionCancelButtonTextColor() {#getRecognitionCancelButtonTextColor--}
```
public int getRecognitionCancelButtonTextColor()
```


Ottiene il colore del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento

**Returns:**
int - colore del pulsante "Cancel" che viene visualizzato sotto la barra di avanzamento
### getRecognitionCancelButtonTextSize() {#getRecognitionCancelButtonTextSize--}
```
public float getRecognitionCancelButtonTextSize()
```


Ottiene la dimensione del testo del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento

**Returns:**
float - dimensione del testo del pulsante "Cancel" che viene visualizzato sotto la barra di avanzamento
### getRecognitionCancelButtonVisibility() {#getRecognitionCancelButtonVisibility--}
```
public boolean getRecognitionCancelButtonVisibility()
```


Ottiene la visibilità del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento

**Returns:**
boolean - visibilità del pulsante "Cancel"
### getRecognitionProcessAboveLabelText() {#getRecognitionProcessAboveLabelText--}
```
public String getRecognitionProcessAboveLabelText()
```


Ottiene il testo della TextView che viene renderizzata sopra la barra di avanzamento durante il riconoscimento

**Returns:**
java.lang.String - testo del TextView che viene visualizzato sopra la barra di avanzamento
### getRecognitionProcessAboveLabelTextColor() {#getRecognitionProcessAboveLabelTextColor--}
```
public int getRecognitionProcessAboveLabelTextColor()
```


Ottiene il colore della TextView che viene renderizzata sopra la barra di avanzamento durante il riconoscimento

**Returns:**
int - colore del TextView che viene visualizzato sopra la barra di avanzamento
### getRecognitionProcessAboveLabelTextSize() {#getRecognitionProcessAboveLabelTextSize--}
```
public float getRecognitionProcessAboveLabelTextSize()
```


Ottiene la dimensione del testo della TextView che viene renderizzata sopra la barra di avanzamento durante il riconoscimento

**Returns:**
float - dimensione del testo del TextView che viene visualizzato sopra la barra di avanzamento
### getRecognitionProcessAboveLabelTextVisible() {#getRecognitionProcessAboveLabelTextVisible--}
```
public boolean getRecognitionProcessAboveLabelTextVisible()
```


Ottiene il colore della TextView che viene renderizzata sopra la barra di avanzamento durante il riconoscimento

**Returns:**
boolean - colore del TextView che viene visualizzato sopra la barra di avanzamento
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


Importa le impostazioni

**Parameters:**
| Parameter | Type | Descrizione |
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


Imposta lo sfondo che verrà renderizzato durante il processo di riconoscimento

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| backgroundImage | com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground | lo sfondo che verrà visualizzato durante il processo di riconoscimento |

### setProgressBarColor(int progressBarColor) {#setProgressBarColor-int-}
```
public void setProgressBarColor(int progressBarColor)
```


Imposta il colore della barra di avanzamento che viene renderizzata durante il riconoscimento

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| progressBarColor | int | colore della barra di avanzamento |

### setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset) {#setRecognitionCancelButtonRightOffset-int-}
```
public void setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)
```


Imposta lo spostamento dal bordo destro del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| recognitionCancelButtonRightOffset | int | offset dal bordo destro del pulsante "Cancel" |

### setRecognitionCancelButtonText(String recognitionCancelButtonText) {#setRecognitionCancelButtonText-java.lang.String-}
```
public void setRecognitionCancelButtonText(String recognitionCancelButtonText)
```


Imposta il testo del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| recognitionCancelButtonText | java.lang.String | testo del pulsante "Cancel" che viene visualizzato sotto la barra di avanzamento |

### setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor) {#setRecognitionCancelButtonTextColor-int-}
```
public void setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)
```


Imposta il colore del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| recognitionCancelButtonTextColor | int | colore del pulsante "Cancel" che viene visualizzato sotto la barra di avanzamento |

### setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize) {#setRecognitionCancelButtonTextSize-float-}
```
public void setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)
```


Imposta la dimensione del testo del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| recognitionCancelButtonTextSize | float | dimensione del testo del pulsante "Cancel" visualizzato sotto il progresso |

### setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible) {#setRecognitionCancelButtonVisibility-boolean-}
```
public void setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)
```


Imposta la visibilità del pulsante "Cancel" che viene renderizzato sotto la barra di avanzamento durante il riconoscimento

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| recognitionCancelButtonVisible | boolean | visibilità del pulsante "Cancel" |

### setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText) {#setRecognitionProcessAboveLabelText-java.lang.String-}
```
public void setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)
```


Imposta il testo della TextView che viene renderizzata sopra la barra di avanzamento durante il riconoscimento

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| recognitionProcessAboveLabelText | java.lang.String | testo della TextView visualizzata sopra la barra di avanzamento |

### setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor) {#setRecognitionProcessAboveLabelTextColor-int-}
```
public void setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)
```


Imposta il colore della TextView che viene renderizzata sopra la barra di avanzamento durante il riconoscimento

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| recognitionProcessAboveLabelTextColor | int | colore della TextView visualizzata sopra la barra di avanzamento |

### setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize) {#setRecognitionProcessAboveLabelTextSize-int-}
```
public void setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)
```


Imposta la dimensione del testo della TextView che viene renderizzata sopra la barra di avanzamento durante il riconoscimento

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| recognitionAboveLabelTextSize | int | dimensione del testo della TextView visualizzata sopra la barra di avanzamento |

### setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible) {#setRecognitionProcessAboveLabelTextVisible-boolean-}
```
public void setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)
```


Imposta il colore della TextView che viene renderizzata sopra la barra di avanzamento durante il riconoscimento

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| recognitionProcessAboveLabelTextVisible | boolean | colore della TextView visualizzata sopra la barra di avanzamento |

### setRecognitionProgressBarSize(int progressBarSize) {#setRecognitionProgressBarSize-int-}
```
public void setRecognitionProgressBarSize(int progressBarSize)
```


Imposta la dimensione della barra di avanzamento che viene renderizzata durante il riconoscimento

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| progressBarSize | int | dimensione della barra di avanzamento |

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

