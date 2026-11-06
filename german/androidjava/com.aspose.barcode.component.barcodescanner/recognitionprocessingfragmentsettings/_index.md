---
title: "RecognitionProcessingFragmentSettings"
second_title: "Aspose.BarCode für Android via Java API-Referenz"
description: 
type: docs
weight: 27
url: /de/androidjava/com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionProcessingFragmentSettings implements Parcelable
```
## Felder

| Feld | Beschreibung |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundDuringRecognitionProcess()](#getBackgroundDuringRecognitionProcess--) | Ruft den Hintergrund ab, der während des Erkennungsprozesses gerendert wird |
| [getClass()](#getClass--) |  |
| [getProgressBarColor()](#getProgressBarColor--) | Ruft die Farbe des Fortschrittsbalkens ab, der während der Erkennung gerendert wird |
| [getProgressBarSize()](#getProgressBarSize--) | Ruft die Größe des Fortschrittsbalkens ab, der während der Erkennung gerendert wird |
| [getRecognitionCancelButtonRightOffset()](#getRecognitionCancelButtonRightOffset--) | Ruft den Abstand vom rechten Rand der Schaltfläche \"Cancel\" ab, die unter dem Fortschrittsbalken während der Erkennung gerendert wird |
| [getRecognitionCancelButtonText()](#getRecognitionCancelButtonText--) | Ruft den Text der Schaltfläche \"Cancel\" ab, die unter dem Fortschrittsbalken während der Erkennung gerendert wird |
| [getRecognitionCancelButtonTextColor()](#getRecognitionCancelButtonTextColor--) | Ruft die Farbe der Schaltfläche \"Cancel\" ab, die unter dem Fortschrittsbalken während der Erkennung gerendert wird |
| [getRecognitionCancelButtonTextSize()](#getRecognitionCancelButtonTextSize--) | Ruft die Textgröße der Schaltfläche \"Cancel\" ab, die unter dem Fortschrittsbalken während der Erkennung gerendert wird |
| [getRecognitionCancelButtonVisibility()](#getRecognitionCancelButtonVisibility--) | Ruft die Sichtbarkeit der Schaltfläche \"Cancel\" ab, die unter dem Fortschrittsbalken während der Erkennung gerendert wird |
| [getRecognitionProcessAboveLabelText()](#getRecognitionProcessAboveLabelText--) | Ruft den Text von TextView ab, das über dem Fortschrittsbalken während der Erkennung gerendert wird |
| [getRecognitionProcessAboveLabelTextColor()](#getRecognitionProcessAboveLabelTextColor--) | Ruft die Farbe von TextView ab, das über dem Fortschrittsbalken während der Erkennung gerendert wird |
| [getRecognitionProcessAboveLabelTextSize()](#getRecognitionProcessAboveLabelTextSize--) | Ruft die Textgröße von TextView ab, das über dem Fortschrittsbalken während der Erkennung gerendert wird |
| [getRecognitionProcessAboveLabelTextVisible()](#getRecognitionProcessAboveLabelTextVisible--) | Ruft die Farbe von TextView ab, das über dem Fortschrittsbalken während der Erkennung gerendert wird |
| [hashCode()](#hashCode--) |  |
| [importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)](#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-) | Importiert die Einstellungen |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)](#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-) | Setzt den Hintergrund, der während des Erkennungsprozesses gerendert wird |
| [setProgressBarColor(int progressBarColor)](#setProgressBarColor-int-) | Setzt die Farbe des Fortschrittsbalkens, der während der Erkennung gerendert wird |
| [setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)](#setRecognitionCancelButtonRightOffset-int-) | Setzt den Abstand vom rechten Rand der Schaltfläche \"Cancel\" fest, die unter dem Fortschrittsbalken während der Erkennung gerendert wird |
| [setRecognitionCancelButtonText(String recognitionCancelButtonText)](#setRecognitionCancelButtonText-java.lang.String-) | Setzt den Text der Schaltfläche \"Cancel\" fest, die unter dem Fortschrittsbalken während der Erkennung gerendert wird |
| [setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)](#setRecognitionCancelButtonTextColor-int-) | Setzt die Farbe der Schaltfläche \"Cancel\" fest, die unter dem Fortschrittsbalken während der Erkennung gerendert wird |
| [setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)](#setRecognitionCancelButtonTextSize-float-) | Setzt die Textgröße der Schaltfläche \"Cancel\" fest, die unter dem Fortschrittsbalken während der Erkennung gerendert wird |
| [setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)](#setRecognitionCancelButtonVisibility-boolean-) | Setzt die Sichtbarkeit der Schaltfläche \"Cancel\" fest, die unter dem Fortschrittsbalken während der Erkennung gerendert wird |
| [setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)](#setRecognitionProcessAboveLabelText-java.lang.String-) | Setzt den Text von TextView fest, das über dem Fortschrittsbalken während der Erkennung gerendert wird |
| [setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)](#setRecognitionProcessAboveLabelTextColor-int-) | Setzt die Farbe von TextView fest, das über dem Fortschrittsbalken während der Erkennung gerendert wird |
| [setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)](#setRecognitionProcessAboveLabelTextSize-int-) | Setzt die Textgröße von TextView fest, das über dem Fortschrittsbalken während der Erkennung gerendert wird |
| [setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)](#setRecognitionProcessAboveLabelTextVisible-boolean-) | Setzt die Farbe von TextView fest, das über dem Fortschrittsbalken während der Erkennung gerendert wird |
| [setRecognitionProgressBarSize(int progressBarSize)](#setRecognitionProgressBarSize-int-) | Setzt die Größe des Fortschrittsbalkens fest, der während der Erkennung gerendert wird |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBackgroundDuringRecognitionProcess() {#getBackgroundDuringRecognitionProcess--}
```
public RecognitionProcessFragmentBackground getBackgroundDuringRecognitionProcess()
```


Ruft den Hintergrund ab, der während des Erkennungsprozesses gerendert wird

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground - der Hintergrund, der während des Erkennungsprozesses gerendert wird
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


Ruft die Farbe des Fortschrittsbalkens ab, der während der Erkennung gerendert wird

**Returns:**
int - Farbe des Fortschrittsbalkens
### getProgressBarSize() {#getProgressBarSize--}
```
public int getProgressBarSize()
```


Ruft die Größe des Fortschrittsbalkens ab, der während der Erkennung gerendert wird

**Returns:**
int - Größe der Fortschrittsleiste
### getRecognitionCancelButtonRightOffset() {#getRecognitionCancelButtonRightOffset--}
```
public int getRecognitionCancelButtonRightOffset()
```


Ruft den Abstand vom rechten Rand der Schaltfläche \"Cancel\" ab, die unter dem Fortschrittsbalken während der Erkennung gerendert wird

**Returns:**
int - Abstand vom rechten Rand des "Cancel"-Buttons
### getRecognitionCancelButtonText() {#getRecognitionCancelButtonText--}
```
public String getRecognitionCancelButtonText()
```


Ruft den Text der Schaltfläche \"Cancel\" ab, die unter dem Fortschrittsbalken während der Erkennung gerendert wird

**Returns:**
java.lang.String - Text des "Cancel"-Buttons, der unter der Fortschrittsleiste angezeigt wird
### getRecognitionCancelButtonTextColor() {#getRecognitionCancelButtonTextColor--}
```
public int getRecognitionCancelButtonTextColor()
```


Ruft die Farbe der Schaltfläche \"Cancel\" ab, die unter dem Fortschrittsbalken während der Erkennung gerendert wird

**Returns:**
int - Farbe des "Cancel"-Buttons, der unter der Fortschrittsleiste angezeigt wird
### getRecognitionCancelButtonTextSize() {#getRecognitionCancelButtonTextSize--}
```
public float getRecognitionCancelButtonTextSize()
```


Ruft die Textgröße der Schaltfläche \"Cancel\" ab, die unter dem Fortschrittsbalken während der Erkennung gerendert wird

**Returns:**
float - Textgröße des "Cancel"-Buttons, der unter der Fortschrittsleiste angezeigt wird
### getRecognitionCancelButtonVisibility() {#getRecognitionCancelButtonVisibility--}
```
public boolean getRecognitionCancelButtonVisibility()
```


Ruft die Sichtbarkeit der Schaltfläche \"Cancel\" ab, die unter dem Fortschrittsbalken während der Erkennung gerendert wird

**Returns:**
boolean - Sichtbarkeit des "Cancel"-Buttons
### getRecognitionProcessAboveLabelText() {#getRecognitionProcessAboveLabelText--}
```
public String getRecognitionProcessAboveLabelText()
```


Ruft den Text von TextView ab, das über dem Fortschrittsbalken während der Erkennung gerendert wird

**Returns:**
java.lang.String - Text der TextView, die über der Fortschrittsleiste angezeigt wird
### getRecognitionProcessAboveLabelTextColor() {#getRecognitionProcessAboveLabelTextColor--}
```
public int getRecognitionProcessAboveLabelTextColor()
```


Ruft die Farbe von TextView ab, das über dem Fortschrittsbalken während der Erkennung gerendert wird

**Returns:**
int - Farbe der TextView, die über der Fortschrittsleiste angezeigt wird
### getRecognitionProcessAboveLabelTextSize() {#getRecognitionProcessAboveLabelTextSize--}
```
public float getRecognitionProcessAboveLabelTextSize()
```


Ruft die Textgröße von TextView ab, das über dem Fortschrittsbalken während der Erkennung gerendert wird

**Returns:**
float - Textgröße der TextView, die über der Fortschrittsleiste angezeigt wird
### getRecognitionProcessAboveLabelTextVisible() {#getRecognitionProcessAboveLabelTextVisible--}
```
public boolean getRecognitionProcessAboveLabelTextVisible()
```


Ruft die Farbe von TextView ab, das über dem Fortschrittsbalken während der Erkennung gerendert wird

**Returns:**
boolean - Farbe der TextView, die über der Fortschrittsleiste angezeigt wird
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


Importiert die Einstellungen

**Parameters:**
| Parameter | Typ | Beschreibung |
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


Setzt den Hintergrund, der während des Erkennungsprozesses gerendert wird

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| backgroundImage | com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground | der Hintergrund, der während des Erkennungsprozesses gerendert wird |

### setProgressBarColor(int progressBarColor) {#setProgressBarColor-int-}
```
public void setProgressBarColor(int progressBarColor)
```


Setzt die Farbe des Fortschrittsbalkens, der während der Erkennung gerendert wird

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| progressBarColor | int | Farbe der Fortschrittsleiste |

### setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset) {#setRecognitionCancelButtonRightOffset-int-}
```
public void setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)
```


Setzt den Abstand vom rechten Rand der Schaltfläche \"Cancel\" fest, die unter dem Fortschrittsbalken während der Erkennung gerendert wird

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recognitionCancelButtonRightOffset | int | Abstand vom rechten Rand des "Cancel"-Buttons |

### setRecognitionCancelButtonText(String recognitionCancelButtonText) {#setRecognitionCancelButtonText-java.lang.String-}
```
public void setRecognitionCancelButtonText(String recognitionCancelButtonText)
```


Setzt den Text der Schaltfläche \"Cancel\" fest, die unter dem Fortschrittsbalken während der Erkennung gerendert wird

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recognitionCancelButtonText | java.lang.String | Text des "Cancel"-Buttons, der unter der Fortschrittsleiste angezeigt wird |

### setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor) {#setRecognitionCancelButtonTextColor-int-}
```
public void setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)
```


Setzt die Farbe der Schaltfläche \"Cancel\" fest, die unter dem Fortschrittsbalken während der Erkennung gerendert wird

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recognitionCancelButtonTextColor | int | Farbe des "Cancel"-Buttons, der unter der Fortschrittsleiste angezeigt wird |

### setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize) {#setRecognitionCancelButtonTextSize-float-}
```
public void setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)
```


Setzt die Textgröße der Schaltfläche \"Cancel\" fest, die unter dem Fortschrittsbalken während der Erkennung gerendert wird

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recognitionCancelButtonTextSize | float | Textgröße des "Cancel"-Buttons, der unter der Fortschrittsleiste angezeigt wird |

### setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible) {#setRecognitionCancelButtonVisibility-boolean-}
```
public void setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)
```


Setzt die Sichtbarkeit der Schaltfläche \"Cancel\" fest, die unter dem Fortschrittsbalken während der Erkennung gerendert wird

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recognitionCancelButtonVisible | boolean | Sichtbarkeit des "Cancel"-Buttons |

### setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText) {#setRecognitionProcessAboveLabelText-java.lang.String-}
```
public void setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)
```


Setzt den Text von TextView fest, das über dem Fortschrittsbalken während der Erkennung gerendert wird

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recognitionProcessAboveLabelText | java.lang.String | Text der TextView, die über der Fortschrittsleiste gerendert wird |

### setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor) {#setRecognitionProcessAboveLabelTextColor-int-}
```
public void setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)
```


Setzt die Farbe von TextView fest, das über dem Fortschrittsbalken während der Erkennung gerendert wird

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recognitionProcessAboveLabelTextColor | int | Farbe der TextView, die über der Fortschrittsleiste gerendert wird |

### setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize) {#setRecognitionProcessAboveLabelTextSize-int-}
```
public void setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)
```


Setzt die Textgröße von TextView fest, das über dem Fortschrittsbalken während der Erkennung gerendert wird

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recognitionAboveLabelTextSize | int | Textgröße der TextView, die über der Fortschrittsleiste gerendert wird |

### setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible) {#setRecognitionProcessAboveLabelTextVisible-boolean-}
```
public void setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)
```


Setzt die Farbe von TextView fest, das über dem Fortschrittsbalken während der Erkennung gerendert wird

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recognitionProcessAboveLabelTextVisible | boolean | Farbe der TextView, die über der Fortschrittsleiste gerendert wird |

### setRecognitionProgressBarSize(int progressBarSize) {#setRecognitionProgressBarSize-int-}
```
public void setRecognitionProgressBarSize(int progressBarSize)
```


Setzt die Größe des Fortschrittsbalkens fest, der während der Erkennung gerendert wird

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| progressBarSize | int | Größe der Fortschrittsleiste |

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

