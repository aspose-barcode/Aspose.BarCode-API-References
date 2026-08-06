---
title: RecognitionProcessingFragmentSettings
second_title: Aspose.BarCode für Android via Java API-Referenz
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
## Methods

| Method | Beschreibung |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundDuringRecognitionProcess()](#getBackgroundDuringRecognitionProcess--) | Ermittelt den Hintergrund, der während des recogntion-Prozesses gerendert wird |
| [getClass()](#getClass--) |  |
| [getProgressBarColor()](#getProgressBarColor--) | Ermittelt die Farbe der Fortschrittsleiste, die während der Erkennung gerendert wird |
| [getProgressBarSize()](#getProgressBarSize--) | Ermittelt die Größe der Fortschrittsleiste, die während der Erkennung gerendert wird |
| [getRecognitionCancelButtonRightOffset()](#getRecognitionCancelButtonRightOffset--) | Ermittelt den Abstand vom rechten Rand des \"Cancel\"-Buttons, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird |
| [getRecognitionCancelButtonText()](#getRecognitionCancelButtonText--) | Ermittelt den Text des \"Cancel\"-Buttons, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird |
| [getRecognitionCancelButtonTextColor()](#getRecognitionCancelButtonTextColor--) | Ermittelt die Farbe des \"Cancel\"-Buttons, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird |
| [getRecognitionCancelButtonTextSize()](#getRecognitionCancelButtonTextSize--) | Ermittelt die Textgröße des \"Cancel\"-Buttons, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird |
| [getRecognitionCancelButtonVisibility()](#getRecognitionCancelButtonVisibility--) | Ermittelt die Sichtbarkeit des \"Cancel\"-Buttons, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird |
| [getRecognitionProcessAboveLabelText()](#getRecognitionProcessAboveLabelText--) | Ermittelt den Text der TextView, die über der Fortschrittsleiste während der Erkennung gerendert wird |
| [getRecognitionProcessAboveLabelTextColor()](#getRecognitionProcessAboveLabelTextColor--) | Ermittelt die Farbe der TextView, die über der Fortschrittsleiste während der Erkennung gerendert wird |
| [getRecognitionProcessAboveLabelTextSize()](#getRecognitionProcessAboveLabelTextSize--) | Ermittelt die Textgröße der TextView, die über der Fortschrittsleiste während der Erkennung gerendert wird |
| [getRecognitionProcessAboveLabelTextVisible()](#getRecognitionProcessAboveLabelTextVisible--) | Ermittelt die Farbe der TextView, die über der Fortschrittsleiste während der Erkennung gerendert wird |
| [hashCode()](#hashCode--) |  |
| [importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)](#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-) | Importiert die Einstellungen |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)](#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-) | Legt den Hintergrund fest, der während des recogntion-Prozesses gerendert wird |
| [setProgressBarColor(int progressBarColor)](#setProgressBarColor-int-) | Legt die Farbe der Fortschrittsleiste fest, die während der Erkennung gerendert wird |
| [setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)](#setRecognitionCancelButtonRightOffset-int-) | Legt den Abstand vom rechten Rand des \"Cancel\"-Buttons fest, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird |
| [setRecognitionCancelButtonText(String recognitionCancelButtonText)](#setRecognitionCancelButtonText-java.lang.String-) | Legt den Text des \"Cancel\"-Buttons fest, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird |
| [setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)](#setRecognitionCancelButtonTextColor-int-) | Legt die Farbe des \"Cancel\"-Buttons fest, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird |
| [setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)](#setRecognitionCancelButtonTextSize-float-) | Legt die Textgröße des \"Cancel\"-Buttons fest, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird |
| [setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)](#setRecognitionCancelButtonVisibility-boolean-) | Legt die Sichtbarkeit des \"Cancel\"-Buttons fest, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird |
| [setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)](#setRecognitionProcessAboveLabelText-java.lang.String-) | Legt den Text der TextView fest, die über der Fortschrittsleiste während der Erkennung gerendert wird |
| [setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)](#setRecognitionProcessAboveLabelTextColor-int-) | Legt die Farbe der TextView fest, die über der Fortschrittsleiste während der Erkennung gerendert wird |
| [setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)](#setRecognitionProcessAboveLabelTextSize-int-) | Legt die Textgröße der TextView fest, die über der Fortschrittsleiste während der Erkennung gerendert wird |
| [setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)](#setRecognitionProcessAboveLabelTextVisible-boolean-) | Legt die Farbe der TextView fest, die über der Fortschrittsleiste während der Erkennung gerendert wird |
| [setRecognitionProgressBarSize(int progressBarSize)](#setRecognitionProgressBarSize-int-) | Legt die Größe der Fortschrittsleiste fest, die während der Erkennung gerendert wird |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBackgroundDuringRecognitionProcess() {#getBackgroundDuringRecognitionProcess--}
```
public RecognitionProcessFragmentBackground getBackgroundDuringRecognitionProcess()
```


Ermittelt den Hintergrund, der während des recogntion-Prozesses gerendert wird

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground - der Hintergrund, der während des recogntion-Prozesses gerendert wird
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


Ermittelt die Farbe der Fortschrittsleiste, die während der Erkennung gerendert wird

**Returns:**
int - Farbe der Fortschrittsleiste
### getProgressBarSize() {#getProgressBarSize--}
```
public int getProgressBarSize()
```


Ermittelt die Größe der Fortschrittsleiste, die während der Erkennung gerendert wird

**Returns:**
int - Größe der Fortschrittsleiste
### getRecognitionCancelButtonRightOffset() {#getRecognitionCancelButtonRightOffset--}
```
public int getRecognitionCancelButtonRightOffset()
```


Ermittelt den Abstand vom rechten Rand des \"Cancel\"-Buttons, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird

**Returns:**
int - Abstand vom rechten Rand der "Cancel"-Schaltfläche
### getRecognitionCancelButtonText() {#getRecognitionCancelButtonText--}
```
public String getRecognitionCancelButtonText()
```


Ermittelt den Text des \"Cancel\"-Buttons, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird

**Returns:**
java.lang.String - Text der "Cancel"-Schaltfläche, die unter der Fortschrittsleiste angezeigt wird
### getRecognitionCancelButtonTextColor() {#getRecognitionCancelButtonTextColor--}
```
public int getRecognitionCancelButtonTextColor()
```


Ermittelt die Farbe des \"Cancel\"-Buttons, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird

**Returns:**
int - Farbe der "Cancel"-Schaltfläche, die unter der Fortschrittsleiste angezeigt wird
### getRecognitionCancelButtonTextSize() {#getRecognitionCancelButtonTextSize--}
```
public float getRecognitionCancelButtonTextSize()
```


Ermittelt die Textgröße des \"Cancel\"-Buttons, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird

**Returns:**
float - Textgröße der "Cancel"-Schaltfläche, die unter dem Fortschritt angezeigt wird
### getRecognitionCancelButtonVisibility() {#getRecognitionCancelButtonVisibility--}
```
public boolean getRecognitionCancelButtonVisibility()
```


Ermittelt die Sichtbarkeit des \"Cancel\"-Buttons, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird

**Returns:**
boolean - Sichtbarkeit der "Cancel"-Schaltfläche
### getRecognitionProcessAboveLabelText() {#getRecognitionProcessAboveLabelText--}
```
public String getRecognitionProcessAboveLabelText()
```


Ermittelt den Text der TextView, die über der Fortschrittsleiste während der Erkennung gerendert wird

**Returns:**
java.lang.String - Text der TextView, die über der Fortschrittsleiste angezeigt wird
### getRecognitionProcessAboveLabelTextColor() {#getRecognitionProcessAboveLabelTextColor--}
```
public int getRecognitionProcessAboveLabelTextColor()
```


Ermittelt die Farbe der TextView, die über der Fortschrittsleiste während der Erkennung gerendert wird

**Returns:**
int - Farbe der TextView, die über der Fortschrittsleiste angezeigt wird
### getRecognitionProcessAboveLabelTextSize() {#getRecognitionProcessAboveLabelTextSize--}
```
public float getRecognitionProcessAboveLabelTextSize()
```


Ermittelt die Textgröße der TextView, die über der Fortschrittsleiste während der Erkennung gerendert wird

**Returns:**
float - Textgröße der TextView, die über der Fortschrittsleiste angezeigt wird
### getRecognitionProcessAboveLabelTextVisible() {#getRecognitionProcessAboveLabelTextVisible--}
```
public boolean getRecognitionProcessAboveLabelTextVisible()
```


Ermittelt die Farbe der TextView, die über der Fortschrittsleiste während der Erkennung gerendert wird

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
| Parameter | Type | Beschreibung |
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


Legt den Hintergrund fest, der während des recogntion-Prozesses gerendert wird

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| backgroundImage | com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground | Der Hintergrund, der während des Erkennungsprozesses gerendert wird |

### setProgressBarColor(int progressBarColor) {#setProgressBarColor-int-}
```
public void setProgressBarColor(int progressBarColor)
```


Legt die Farbe der Fortschrittsleiste fest, die während der Erkennung gerendert wird

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| progressBarColor | int | Farbe der Fortschrittsleiste |

### setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset) {#setRecognitionCancelButtonRightOffset-int-}
```
public void setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)
```


Legt den Abstand vom rechten Rand des \"Cancel\"-Buttons fest, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| recognitionCancelButtonRightOffset | int | Abstand vom rechten Rand der "Cancel"-Schaltfläche |

### setRecognitionCancelButtonText(String recognitionCancelButtonText) {#setRecognitionCancelButtonText-java.lang.String-}
```
public void setRecognitionCancelButtonText(String recognitionCancelButtonText)
```


Legt den Text des \"Cancel\"-Buttons fest, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| recognitionCancelButtonText | java.lang.String | Text der "Cancel"-Schaltfläche, die unter der Fortschrittsleiste angezeigt wird |

### setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor) {#setRecognitionCancelButtonTextColor-int-}
```
public void setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)
```


Legt die Farbe des \"Cancel\"-Buttons fest, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| recognitionCancelButtonTextColor | int | Farbe der "Cancel"-Schaltfläche, die unter der Fortschrittsleiste angezeigt wird |

### setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize) {#setRecognitionCancelButtonTextSize-float-}
```
public void setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)
```


Legt die Textgröße des \"Cancel\"-Buttons fest, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| recognitionCancelButtonTextSize | float | Textgröße der "Cancel"-Schaltfläche, die unter dem Fortschritt gerendert wird |

### setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible) {#setRecognitionCancelButtonVisibility-boolean-}
```
public void setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)
```


Legt die Sichtbarkeit des \"Cancel\"-Buttons fest, der unterhalb der Fortschrittsleiste während der Erkennung gerendert wird

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| recognitionCancelButtonVisible | boolean | Sichtbarkeit der "Cancel"-Schaltfläche |

### setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText) {#setRecognitionProcessAboveLabelText-java.lang.String-}
```
public void setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)
```


Legt den Text der TextView fest, die über der Fortschrittsleiste während der Erkennung gerendert wird

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| recognitionProcessAboveLabelText | java.lang.String | Text der TextView, die über der Fortschrittsleiste gerendert wird |

### setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor) {#setRecognitionProcessAboveLabelTextColor-int-}
```
public void setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)
```


Legt die Farbe der TextView fest, die über der Fortschrittsleiste während der Erkennung gerendert wird

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| recognitionProcessAboveLabelTextColor | int | Farbe der TextView, die über der Fortschrittsleiste gerendert wird |

### setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize) {#setRecognitionProcessAboveLabelTextSize-int-}
```
public void setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)
```


Legt die Textgröße der TextView fest, die über der Fortschrittsleiste während der Erkennung gerendert wird

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| recognitionAboveLabelTextSize | int | Textgröße der TextView, die über der Fortschrittsleiste gerendert wird |

### setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible) {#setRecognitionProcessAboveLabelTextVisible-boolean-}
```
public void setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)
```


Legt die Farbe der TextView fest, die über der Fortschrittsleiste während der Erkennung gerendert wird

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| recognitionProcessAboveLabelTextVisible | boolean | Farbe der TextView, die über der Fortschrittsleiste gerendert wird |

### setRecognitionProgressBarSize(int progressBarSize) {#setRecognitionProgressBarSize-int-}
```
public void setRecognitionProgressBarSize(int progressBarSize)
```


Legt die Größe der Fortschrittsleiste fest, die während der Erkennung gerendert wird

**Parameters:**
| Parameter | Type | Beschreibung |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

