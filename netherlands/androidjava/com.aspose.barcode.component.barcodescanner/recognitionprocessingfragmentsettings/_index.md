---
title: RecognitionProcessingFragmentSettings
second_title: Aspose.BarCode for Android via Java API-referentie
description: 
type: docs
weight: 27
url: /nl/androidjava/com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionProcessingFragmentSettings implements Parcelable
```
## Velden

| Veld | Beschrijving |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Beschrijving |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundDuringRecognitionProcess()](#getBackgroundDuringRecognitionProcess--) | Haalt de achtergrond op die tijdens het herkenningsproces wordt weergegeven |
| [getClass()](#getClass--) |  |
| [getProgressBarColor()](#getProgressBarColor--) | Haalt de kleur van de voortgangsbalk op die tijdens de herkenning wordt weergegeven |
| [getProgressBarSize()](#getProgressBarSize--) | Haalt de grootte van de voortgangsbalk op die tijdens de herkenning wordt weergegeven |
| [getRecognitionCancelButtonRightOffset()](#getRecognitionCancelButtonRightOffset--) | Haalt de offset van de rechterrand van de "Annuleren"-knop op die onder de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [getRecognitionCancelButtonText()](#getRecognitionCancelButtonText--) | Haalt de tekst van de "Annuleren"-knop op die onder de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [getRecognitionCancelButtonTextColor()](#getRecognitionCancelButtonTextColor--) | Haalt de kleur van de "Annuleren"-knop op die onder de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [getRecognitionCancelButtonTextSize()](#getRecognitionCancelButtonTextSize--) | Haalt de tekstgrootte van de "Annuleren"-knop op die onder de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [getRecognitionCancelButtonVisibility()](#getRecognitionCancelButtonVisibility--) | Haalt de zichtbaarheid van de "Annuleren"-knop op die onder de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [getRecognitionProcessAboveLabelText()](#getRecognitionProcessAboveLabelText--) | Haalt de tekst van de TextView op die boven de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [getRecognitionProcessAboveLabelTextColor()](#getRecognitionProcessAboveLabelTextColor--) | Haalt de kleur van de TextView op die boven de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [getRecognitionProcessAboveLabelTextSize()](#getRecognitionProcessAboveLabelTextSize--) | Haalt de tekstgrootte van de TextView op die boven de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [getRecognitionProcessAboveLabelTextVisible()](#getRecognitionProcessAboveLabelTextVisible--) | Haalt de kleur van de TextView op die boven de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [hashCode()](#hashCode--) |  |
| [importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)](#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-) | Importeert de instellingen |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)](#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-) | Stelt de achtergrond in die tijdens het herkenningsproces wordt weergegeven |
| [setProgressBarColor(int progressBarColor)](#setProgressBarColor-int-) | Stelt de kleur van de voortgangsbalk in die tijdens de herkenning wordt weergegeven |
| [setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)](#setRecognitionCancelButtonRightOffset-int-) | Stelt de offset van de rechterrand van de "Annuleren"-knop in die onder de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [setRecognitionCancelButtonText(String recognitionCancelButtonText)](#setRecognitionCancelButtonText-java.lang.String-) | Stelt de tekst van de "Annuleren"-knop in die onder de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)](#setRecognitionCancelButtonTextColor-int-) | Stelt de kleur van de "Annuleren"-knop in die onder de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)](#setRecognitionCancelButtonTextSize-float-) | Stelt de tekstgrootte van de "Annuleren"-knop in die onder de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)](#setRecognitionCancelButtonVisibility-boolean-) | Stelt de zichtbaarheid van de "Annuleren"-knop in die onder de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)](#setRecognitionProcessAboveLabelText-java.lang.String-) | Stelt de tekst van de TextView in die boven de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)](#setRecognitionProcessAboveLabelTextColor-int-) | Stelt de kleur van de TextView in die boven de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)](#setRecognitionProcessAboveLabelTextSize-int-) | Stelt de tekstgrootte van de TextView in die boven de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)](#setRecognitionProcessAboveLabelTextVisible-boolean-) | Stelt de kleur van de TextView in die boven de voortgangsbalk wordt weergegeven tijdens de herkenning |
| [setRecognitionProgressBarSize(int progressBarSize)](#setRecognitionProgressBarSize-int-) | Stelt de grootte van de voortgangsbalk in die tijdens de herkenning wordt weergegeven |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBackgroundDuringRecognitionProcess() {#getBackgroundDuringRecognitionProcess--}
```
public RecognitionProcessFragmentBackground getBackgroundDuringRecognitionProcess()
```


Haalt de achtergrond op die tijdens het herkenningsproces wordt weergegeven

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground - de achtergrond die tijdens het herkenningsproces wordt weergegeven
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


Haalt de kleur van de voortgangsbalk op die tijdens de herkenning wordt weergegeven

**Returns:**
int - kleur van voortgangsbalk
### getProgressBarSize() {#getProgressBarSize--}
```
public int getProgressBarSize()
```


Haalt de grootte van de voortgangsbalk op die tijdens de herkenning wordt weergegeven

**Returns:**
int - grootte van voortgangsbalk
### getRecognitionCancelButtonRightOffset() {#getRecognitionCancelButtonRightOffset--}
```
public int getRecognitionCancelButtonRightOffset()
```


Haalt de offset van de rechterrand van de "Annuleren"-knop op die onder de voortgangsbalk wordt weergegeven tijdens de herkenning

**Returns:**
int - offset vanaf rechterrand van \"Cancel\"-knop
### getRecognitionCancelButtonText() {#getRecognitionCancelButtonText--}
```
public String getRecognitionCancelButtonText()
```


Haalt de tekst van de "Annuleren"-knop op die onder de voortgangsbalk wordt weergegeven tijdens de herkenning

**Returns:**
java.lang.String - tekst van \"Cancel\"-knop die onder de voortgangsbalk wordt weergegeven
### getRecognitionCancelButtonTextColor() {#getRecognitionCancelButtonTextColor--}
```
public int getRecognitionCancelButtonTextColor()
```


Haalt de kleur van de "Annuleren"-knop op die onder de voortgangsbalk wordt weergegeven tijdens de herkenning

**Returns:**
int - kleur van \"Cancel\"-knop die onder de voortgangsbalk wordt weergegeven
### getRecognitionCancelButtonTextSize() {#getRecognitionCancelButtonTextSize--}
```
public float getRecognitionCancelButtonTextSize()
```


Haalt de tekstgrootte van de "Annuleren"-knop op die onder de voortgangsbalk wordt weergegeven tijdens de herkenning

**Returns:**
float - tekstgrootte van \"Cancel\"-knop die onder de voortgangsbalk wordt weergegeven
### getRecognitionCancelButtonVisibility() {#getRecognitionCancelButtonVisibility--}
```
public boolean getRecognitionCancelButtonVisibility()
```


Haalt de zichtbaarheid van de "Annuleren"-knop op die onder de voortgangsbalk wordt weergegeven tijdens de herkenning

**Returns:**
boolean - zichtbaarheid van \"Cancel\"-knop
### getRecognitionProcessAboveLabelText() {#getRecognitionProcessAboveLabelText--}
```
public String getRecognitionProcessAboveLabelText()
```


Haalt de tekst van de TextView op die boven de voortgangsbalk wordt weergegeven tijdens de herkenning

**Returns:**
java.lang.String - tekst van TextView die boven de voortgangsbalk wordt weergegeven
### getRecognitionProcessAboveLabelTextColor() {#getRecognitionProcessAboveLabelTextColor--}
```
public int getRecognitionProcessAboveLabelTextColor()
```


Haalt de kleur van de TextView op die boven de voortgangsbalk wordt weergegeven tijdens de herkenning

**Returns:**
int - kleur van TextView die boven de voortgangsbalk wordt weergegeven
### getRecognitionProcessAboveLabelTextSize() {#getRecognitionProcessAboveLabelTextSize--}
```
public float getRecognitionProcessAboveLabelTextSize()
```


Haalt de tekstgrootte van de TextView op die boven de voortgangsbalk wordt weergegeven tijdens de herkenning

**Returns:**
float - tekstgrootte van TextView die boven de voortgangsbalk wordt weergegeven
### getRecognitionProcessAboveLabelTextVisible() {#getRecognitionProcessAboveLabelTextVisible--}
```
public boolean getRecognitionProcessAboveLabelTextVisible()
```


Haalt de kleur van de TextView op die boven de voortgangsbalk wordt weergegeven tijdens de herkenning

**Returns:**
boolean - kleur van TextView die boven de voortgangsbalk wordt weergegeven
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


Importeert de instellingen

**Parameters:**
| Parameter | Type | Beschrijving |
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


Stelt de achtergrond in die tijdens het herkenningsproces wordt weergegeven

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| backgroundImage | com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground | de achtergrond die tijdens het herkenningsproces wordt weergegeven |

### setProgressBarColor(int progressBarColor) {#setProgressBarColor-int-}
```
public void setProgressBarColor(int progressBarColor)
```


Stelt de kleur van de voortgangsbalk in die tijdens de herkenning wordt weergegeven

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| progressBarColor | int | kleur van voortgangsbalk |

### setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset) {#setRecognitionCancelButtonRightOffset-int-}
```
public void setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)
```


Stelt de offset van de rechterrand van de "Annuleren"-knop in die onder de voortgangsbalk wordt weergegeven tijdens de herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionCancelButtonRightOffset | int | offset vanaf rechterrand van \"Cancel\"-knop |

### setRecognitionCancelButtonText(String recognitionCancelButtonText) {#setRecognitionCancelButtonText-java.lang.String-}
```
public void setRecognitionCancelButtonText(String recognitionCancelButtonText)
```


Stelt de tekst van de "Annuleren"-knop in die onder de voortgangsbalk wordt weergegeven tijdens de herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionCancelButtonText | java.lang.String | tekst van \"Cancel\"-knop die onder de voortgangsbalk wordt weergegeven |

### setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor) {#setRecognitionCancelButtonTextColor-int-}
```
public void setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)
```


Stelt de kleur van de "Annuleren"-knop in die onder de voortgangsbalk wordt weergegeven tijdens de herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionCancelButtonTextColor | int | kleur van \"Cancel\"-knop die onder de voortgangsbalk wordt weergegeven |

### setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize) {#setRecognitionCancelButtonTextSize-float-}
```
public void setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)
```


Stelt de tekstgrootte van de "Annuleren"-knop in die onder de voortgangsbalk wordt weergegeven tijdens de herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionCancelButtonTextSize | float | tekstgrootte van "Cancel" knop die onder de voortgang wordt weergegeven |

### setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible) {#setRecognitionCancelButtonVisibility-boolean-}
```
public void setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)
```


Stelt de zichtbaarheid van de "Annuleren"-knop in die onder de voortgangsbalk wordt weergegeven tijdens de herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionCancelButtonVisible | boolean | zichtbaarheid van "Cancel" knop |

### setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText) {#setRecognitionProcessAboveLabelText-java.lang.String-}
```
public void setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)
```


Stelt de tekst van de TextView in die boven de voortgangsbalk wordt weergegeven tijdens de herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionProcessAboveLabelText | java.lang.String | tekst van TextView die boven de voortgangsbalk wordt weergegeven |

### setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor) {#setRecognitionProcessAboveLabelTextColor-int-}
```
public void setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)
```


Stelt de kleur van de TextView in die boven de voortgangsbalk wordt weergegeven tijdens de herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionProcessAboveLabelTextColor | int | kleur van TextView die boven de voortgangsbalk wordt weergegeven |

### setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize) {#setRecognitionProcessAboveLabelTextSize-int-}
```
public void setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)
```


Stelt de tekstgrootte van de TextView in die boven de voortgangsbalk wordt weergegeven tijdens de herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionAboveLabelTextSize | int | tekstgrootte van TextView die boven de voortgangsbalk wordt weergegeven |

### setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible) {#setRecognitionProcessAboveLabelTextVisible-boolean-}
```
public void setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)
```


Stelt de kleur van de TextView in die boven de voortgangsbalk wordt weergegeven tijdens de herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionProcessAboveLabelTextVisible | boolean | kleur van TextView die boven de voortgangsbalk wordt weergegeven |

### setRecognitionProgressBarSize(int progressBarSize) {#setRecognitionProgressBarSize-int-}
```
public void setRecognitionProgressBarSize(int progressBarSize)
```


Stelt de grootte van de voortgangsbalk in die tijdens de herkenning wordt weergegeven

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| progressBarSize | int | grootte van voortgangsbalk |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

