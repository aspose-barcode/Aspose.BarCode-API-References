---
title: RecognitionProcessingFragmentSettings
second_title: Aspose.BarCode for Android via Java API-referens
description: 
type: docs
weight: 27
url: /sv/androidjava/com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionProcessingFragmentSettings implements Parcelable
```
## Fält

| Fält | Beskrivning |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Beskrivning |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundDuringRecognitionProcess()](#getBackgroundDuringRecognitionProcess--) | Hämtar bakgrunden som kommer att renderas under igenkänningsprocessen |
| [getClass()](#getClass--) |  |
| [getProgressBarColor()](#getProgressBarColor--) | Hämtar färgen på förloppsindikatorn som renderas under igenkänning |
| [getProgressBarSize()](#getProgressBarSize--) | Hämtar storleken på förloppsindikatorn som renderas under igenkänning |
| [getRecognitionCancelButtonRightOffset()](#getRecognitionCancelButtonRightOffset--) | Hämtar förskjutningen från högra kanten på "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning |
| [getRecognitionCancelButtonText()](#getRecognitionCancelButtonText--) | Hämtar texten för "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning |
| [getRecognitionCancelButtonTextColor()](#getRecognitionCancelButtonTextColor--) | Hämtar färgen på "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning |
| [getRecognitionCancelButtonTextSize()](#getRecognitionCancelButtonTextSize--) | Hämtar textstorleken för "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning |
| [getRecognitionCancelButtonVisibility()](#getRecognitionCancelButtonVisibility--) | Hämtar synligheten för "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning |
| [getRecognitionProcessAboveLabelText()](#getRecognitionProcessAboveLabelText--) | Hämtar texten för TextView som renderas ovanför förloppsindikatorn under igenkänning |
| [getRecognitionProcessAboveLabelTextColor()](#getRecognitionProcessAboveLabelTextColor--) | Hämtar färgen på TextView som renderas ovanför förloppsindikatorn under igenkänning |
| [getRecognitionProcessAboveLabelTextSize()](#getRecognitionProcessAboveLabelTextSize--) | Hämtar textstorleken för TextView som renderas ovanför förloppsindikatorn under igenkänning |
| [getRecognitionProcessAboveLabelTextVisible()](#getRecognitionProcessAboveLabelTextVisible--) | Hämtar färgen på TextView som renderas ovanför förloppsindikatorn under igenkänning |
| [hashCode()](#hashCode--) |  |
| [importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)](#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-) | Importerar inställningarna |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)](#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-) | Ställer in bakgrunden som kommer att renderas under igenkänningsprocessen |
| [setProgressBarColor(int progressBarColor)](#setProgressBarColor-int-) | Ställer in färgen på förloppsindikatorn som renderas under igenkänning |
| [setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)](#setRecognitionCancelButtonRightOffset-int-) | Ställer in förskjutningen från högra kanten på "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning |
| [setRecognitionCancelButtonText(String recognitionCancelButtonText)](#setRecognitionCancelButtonText-java.lang.String-) | Ställer in texten för "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning |
| [setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)](#setRecognitionCancelButtonTextColor-int-) | Ställer in färgen på "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning |
| [setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)](#setRecognitionCancelButtonTextSize-float-) | Ställer in textstorleken för "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning |
| [setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)](#setRecognitionCancelButtonVisibility-boolean-) | Ställer in synligheten för "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning |
| [setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)](#setRecognitionProcessAboveLabelText-java.lang.String-) | Ställer in texten för TextView som renderas ovanför förloppsindikatorn under igenkänning |
| [setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)](#setRecognitionProcessAboveLabelTextColor-int-) | Ställer in färgen på TextView som renderas ovanför förloppsindikatorn under igenkänning |
| [setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)](#setRecognitionProcessAboveLabelTextSize-int-) | Ställer in textstorleken för TextView som renderas ovanför förloppsindikatorn under igenkänning |
| [setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)](#setRecognitionProcessAboveLabelTextVisible-boolean-) | Ställer in färgen på TextView som renderas ovanför förloppsindikatorn under igenkänning |
| [setRecognitionProgressBarSize(int progressBarSize)](#setRecognitionProgressBarSize-int-) | Ställer in storleken på förloppsindikatorn som renderas under igenkänning |
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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBackgroundDuringRecognitionProcess() {#getBackgroundDuringRecognitionProcess--}
```
public RecognitionProcessFragmentBackground getBackgroundDuringRecognitionProcess()
```


Hämtar bakgrunden som kommer att renderas under igenkänningsprocessen

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground - bakgrunden som kommer att renderas under igenkänningsprocessen
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


Hämtar färgen på förloppsindikatorn som renderas under igenkänning

**Returns:**
int - färg på förloppsfältet
### getProgressBarSize() {#getProgressBarSize--}
```
public int getProgressBarSize()
```


Hämtar storleken på förloppsindikatorn som renderas under igenkänning

**Returns:**
int - storlek på förloppsfältet
### getRecognitionCancelButtonRightOffset() {#getRecognitionCancelButtonRightOffset--}
```
public int getRecognitionCancelButtonRightOffset()
```


Hämtar förskjutningen från högra kanten på "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning

**Returns:**
int - avstånd från högra kanten av "Cancel"-knappen
### getRecognitionCancelButtonText() {#getRecognitionCancelButtonText--}
```
public String getRecognitionCancelButtonText()
```


Hämtar texten för "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning

**Returns:**
java.lang.String - text för "Cancel"-knappen som renderas under förloppsfältet
### getRecognitionCancelButtonTextColor() {#getRecognitionCancelButtonTextColor--}
```
public int getRecognitionCancelButtonTextColor()
```


Hämtar färgen på "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning

**Returns:**
int - färg på "Cancel"-knappen som renderas under förloppsfältet
### getRecognitionCancelButtonTextSize() {#getRecognitionCancelButtonTextSize--}
```
public float getRecognitionCancelButtonTextSize()
```


Hämtar textstorleken för "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning

**Returns:**
float - textstorlek för "Cancel"-knappen som renderas under förloppsfältet
### getRecognitionCancelButtonVisibility() {#getRecognitionCancelButtonVisibility--}
```
public boolean getRecognitionCancelButtonVisibility()
```


Hämtar synligheten för "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning

**Returns:**
boolean - synlighet för "Cancel"-knappen
### getRecognitionProcessAboveLabelText() {#getRecognitionProcessAboveLabelText--}
```
public String getRecognitionProcessAboveLabelText()
```


Hämtar texten för TextView som renderas ovanför förloppsindikatorn under igenkänning

**Returns:**
java.lang.String - text för TextView som renderas ovanför förloppsfältet
### getRecognitionProcessAboveLabelTextColor() {#getRecognitionProcessAboveLabelTextColor--}
```
public int getRecognitionProcessAboveLabelTextColor()
```


Hämtar färgen på TextView som renderas ovanför förloppsindikatorn under igenkänning

**Returns:**
int - färg på TextView som renderas ovanför förloppsfältet
### getRecognitionProcessAboveLabelTextSize() {#getRecognitionProcessAboveLabelTextSize--}
```
public float getRecognitionProcessAboveLabelTextSize()
```


Hämtar textstorleken för TextView som renderas ovanför förloppsindikatorn under igenkänning

**Returns:**
float - textstorlek för TextView som renderas ovanför förloppsfältet
### getRecognitionProcessAboveLabelTextVisible() {#getRecognitionProcessAboveLabelTextVisible--}
```
public boolean getRecognitionProcessAboveLabelTextVisible()
```


Hämtar färgen på TextView som renderas ovanför förloppsindikatorn under igenkänning

**Returns:**
boolean - färg på TextView som renderas ovanför förloppsfältet
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


Importerar inställningarna

**Parameters:**
| Parameter | Type | Beskrivning |
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


Ställer in bakgrunden som kommer att renderas under igenkänningsprocessen

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| backgroundImage | com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground | bakgrunden som kommer att renderas under igenkänningsprocessen |

### setProgressBarColor(int progressBarColor) {#setProgressBarColor-int-}
```
public void setProgressBarColor(int progressBarColor)
```


Ställer in färgen på förloppsindikatorn som renderas under igenkänning

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| progressBarColor | int | färg på förloppsfältet |

### setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset) {#setRecognitionCancelButtonRightOffset-int-}
```
public void setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)
```


Ställer in förskjutningen från högra kanten på "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| recognitionCancelButtonRightOffset | int | avstånd från högra kanten av "Cancel"-knappen |

### setRecognitionCancelButtonText(String recognitionCancelButtonText) {#setRecognitionCancelButtonText-java.lang.String-}
```
public void setRecognitionCancelButtonText(String recognitionCancelButtonText)
```


Ställer in texten för "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| recognitionCancelButtonText | java.lang.String | text för "Cancel"-knappen som renderas under förloppsfältet |

### setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor) {#setRecognitionCancelButtonTextColor-int-}
```
public void setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)
```


Ställer in färgen på "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| recognitionCancelButtonTextColor | int | färg på "Cancel"-knappen som renderas under förloppsfältet |

### setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize) {#setRecognitionCancelButtonTextSize-float-}
```
public void setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)
```


Ställer in textstorleken för "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| recognitionCancelButtonTextSize | float | textstorlek för "Cancel"-knappen som renderas under framsteg |

### setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible) {#setRecognitionCancelButtonVisibility-boolean-}
```
public void setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)
```


Ställer in synligheten för "Cancel"-knappen som renderas under förloppsindikatorn under igenkänning

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| recognitionCancelButtonVisible | boolean | synlighet för "Cancel"-knappen |

### setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText) {#setRecognitionProcessAboveLabelText-java.lang.String-}
```
public void setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)
```


Ställer in texten för TextView som renderas ovanför förloppsindikatorn under igenkänning

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| recognitionProcessAboveLabelText | java.lang.String | text för TextView som renderas ovanför förloppsindikatorn |

### setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor) {#setRecognitionProcessAboveLabelTextColor-int-}
```
public void setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)
```


Ställer in färgen på TextView som renderas ovanför förloppsindikatorn under igenkänning

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| recognitionProcessAboveLabelTextColor | int | färg för TextView som renderas ovanför förloppsindikatorn |

### setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize) {#setRecognitionProcessAboveLabelTextSize-int-}
```
public void setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)
```


Ställer in textstorleken för TextView som renderas ovanför förloppsindikatorn under igenkänning

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| recognitionAboveLabelTextSize | int | textstorlek för TextView som renderas ovanför förloppsindikatorn |

### setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible) {#setRecognitionProcessAboveLabelTextVisible-boolean-}
```
public void setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)
```


Ställer in färgen på TextView som renderas ovanför förloppsindikatorn under igenkänning

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| recognitionProcessAboveLabelTextVisible | boolean | färg för TextView som renderas ovanför förloppsindikatorn |

### setRecognitionProgressBarSize(int progressBarSize) {#setRecognitionProgressBarSize-int-}
```
public void setRecognitionProgressBarSize(int progressBarSize)
```


Ställer in storleken på förloppsindikatorn som renderas under igenkänning

**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| progressBarSize | int | storlek på förloppsindikatorn |

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
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

