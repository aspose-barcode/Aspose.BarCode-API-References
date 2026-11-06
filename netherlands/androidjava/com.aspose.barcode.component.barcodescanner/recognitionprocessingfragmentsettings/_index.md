---
title: "RecognitionProcessingFragmentSettings"
second_title: "Aspose.BarCode voor Android via Java API-referentie"
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
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundDuringRecognitionProcess()](#getBackgroundDuringRecognitionProcess--) | Haalt de achtergrond op die wordt weergegeven tijdens recogntion process |
| [getClass()](#getClass--) |  |
| [getProgressBarColor()](#getProgressBarColor--) | Haalt de kleur op van de voortgangsbalk die wordt weergegeven tijdens herkenning |
| [getProgressBarSize()](#getProgressBarSize--) | Haalt de grootte op van de voortgangsbalk die wordt weergegeven tijdens herkenning |
| [getRecognitionCancelButtonRightOffset()](#getRecognitionCancelButtonRightOffset--) | Haalt de offset op vanaf de rechterrand van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning |
| [getRecognitionCancelButtonText()](#getRecognitionCancelButtonText--) | Haalt de tekst op van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning |
| [getRecognitionCancelButtonTextColor()](#getRecognitionCancelButtonTextColor--) | Haalt de kleur op van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning |
| [getRecognitionCancelButtonTextSize()](#getRecognitionCancelButtonTextSize--) | Haalt de tekstgrootte op van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning |
| [getRecognitionCancelButtonVisibility()](#getRecognitionCancelButtonVisibility--) | Haalt de zichtbaarheid op van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning |
| [getRecognitionProcessAboveLabelText()](#getRecognitionProcessAboveLabelText--) | Haalt de tekst op van TextView die boven de voortgangsbalk wordt weergegeven tijdens herkenning |
| [getRecognitionProcessAboveLabelTextColor()](#getRecognitionProcessAboveLabelTextColor--) | Haalt de kleur op van TextView die boven de voortgangsbalk wordt weergegeven tijdens herkenning |
| [getRecognitionProcessAboveLabelTextSize()](#getRecognitionProcessAboveLabelTextSize--) | Haalt de tekstgrootte op van TextView die boven de voortgangsbalk wordt weergegeven tijdens herkenning |
| [getRecognitionProcessAboveLabelTextVisible()](#getRecognitionProcessAboveLabelTextVisible--) | Haalt de kleur op van TextView die boven de voortgangsbalk wordt weergegeven tijdens herkenning |
| [hashCode()](#hashCode--) |  |
| [importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)](#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-) | Importeert de instellingen |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)](#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-) | Stelt de achtergrond in die wordt weergegeven tijdens recogntion process |
| [setProgressBarColor(int progressBarColor)](#setProgressBarColor-int-) | Stelt de kleur in van de voortgangsbalk die wordt weergegeven tijdens herkenning |
| [setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)](#setRecognitionCancelButtonRightOffset-int-) | Stelt de offset in vanaf de rechterrand van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning |
| [setRecognitionCancelButtonText(String recognitionCancelButtonText)](#setRecognitionCancelButtonText-java.lang.String-) | Stelt de tekst in van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning |
| [setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)](#setRecognitionCancelButtonTextColor-int-) | Stelt de kleur in van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning |
| [setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)](#setRecognitionCancelButtonTextSize-float-) | Stelt de tekstgrootte in van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning |
| [setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)](#setRecognitionCancelButtonVisibility-boolean-) | Stelt de zichtbaarheid in van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning |
| [setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)](#setRecognitionProcessAboveLabelText-java.lang.String-) | Stelt de tekst in van TextView die boven de voortgangsbalk wordt weergegeven tijdens herkenning |
| [setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)](#setRecognitionProcessAboveLabelTextColor-int-) | Stelt de kleur in van TextView die boven de voortgangsbalk wordt weergegeven tijdens herkenning |
| [setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)](#setRecognitionProcessAboveLabelTextSize-int-) | Stelt de tekstgrootte in van TextView die boven de voortgangsbalk wordt weergegeven tijdens herkenning |
| [setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)](#setRecognitionProcessAboveLabelTextVisible-boolean-) | Stelt de kleur in van TextView die boven de voortgangsbalk wordt weergegeven tijdens herkenning |
| [setRecognitionProgressBarSize(int progressBarSize)](#setRecognitionProgressBarSize-int-) | Stelt de grootte in van de voortgangsbalk die wordt weergegeven tijdens herkenning |
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


Haalt de achtergrond op die wordt weergegeven tijdens recogntion process

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground - de achtergrond die wordt weergegeven tijdens recogntion process
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


Haalt de kleur op van de voortgangsbalk die wordt weergegeven tijdens herkenning

**Returns:**
int - kleur van voortgangsbalk
### getProgressBarSize() {#getProgressBarSize--}
```
public int getProgressBarSize()
```


Haalt de grootte op van de voortgangsbalk die wordt weergegeven tijdens herkenning

**Returns:**
int - grootte van de voortgangsbalk
### getRecognitionCancelButtonRightOffset() {#getRecognitionCancelButtonRightOffset--}
```
public int getRecognitionCancelButtonRightOffset()
```


Haalt de offset op vanaf de rechterrand van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning

**Returns:**
int - offset vanaf de rechterrand van de "Cancel"-knop
### getRecognitionCancelButtonText() {#getRecognitionCancelButtonText--}
```
public String getRecognitionCancelButtonText()
```


Haalt de tekst op van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning

**Returns:**
java.lang.String - tekst van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven
### getRecognitionCancelButtonTextColor() {#getRecognitionCancelButtonTextColor--}
```
public int getRecognitionCancelButtonTextColor()
```


Haalt de kleur op van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning

**Returns:**
int - kleur van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven
### getRecognitionCancelButtonTextSize() {#getRecognitionCancelButtonTextSize--}
```
public float getRecognitionCancelButtonTextSize()
```


Haalt de tekstgrootte op van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning

**Returns:**
float - tekstgrootte van de "Cancel"-knop die onder de voortgang wordt weergegeven
### getRecognitionCancelButtonVisibility() {#getRecognitionCancelButtonVisibility--}
```
public boolean getRecognitionCancelButtonVisibility()
```


Haalt de zichtbaarheid op van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning

**Returns:**
boolean - zichtbaarheid van de "Cancel"-knop
### getRecognitionProcessAboveLabelText() {#getRecognitionProcessAboveLabelText--}
```
public String getRecognitionProcessAboveLabelText()
```


Haalt de tekst op van TextView die boven de voortgangsbalk wordt weergegeven tijdens herkenning

**Returns:**
java.lang.String - tekst van TextView die boven de voortgangsbalk wordt weergegeven
### getRecognitionProcessAboveLabelTextColor() {#getRecognitionProcessAboveLabelTextColor--}
```
public int getRecognitionProcessAboveLabelTextColor()
```


Haalt de kleur op van TextView die boven de voortgangsbalk wordt weergegeven tijdens herkenning

**Returns:**
int - kleur van TextView die boven de voortgangsbalk wordt weergegeven
### getRecognitionProcessAboveLabelTextSize() {#getRecognitionProcessAboveLabelTextSize--}
```
public float getRecognitionProcessAboveLabelTextSize()
```


Haalt de tekstgrootte op van TextView die boven de voortgangsbalk wordt weergegeven tijdens herkenning

**Returns:**
float - tekstgrootte van TextView die boven de voortgangsbalk wordt weergegeven
### getRecognitionProcessAboveLabelTextVisible() {#getRecognitionProcessAboveLabelTextVisible--}
```
public boolean getRecognitionProcessAboveLabelTextVisible()
```


Haalt de kleur op van TextView die boven de voortgangsbalk wordt weergegeven tijdens herkenning

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


Stelt de achtergrond in die wordt weergegeven tijdens recogntion process

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| backgroundImage | com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground | de achtergrond die tijdens het herkenningsproces wordt weergegeven |

### setProgressBarColor(int progressBarColor) {#setProgressBarColor-int-}
```
public void setProgressBarColor(int progressBarColor)
```


Stelt de kleur in van de voortgangsbalk die wordt weergegeven tijdens herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| progressBarColor | int | kleur van de voortgangsbalk |

### setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset) {#setRecognitionCancelButtonRightOffset-int-}
```
public void setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)
```


Stelt de offset in vanaf de rechterrand van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionCancelButtonRightOffset | int | offset vanaf de rechterrand van de "Cancel"-knop |

### setRecognitionCancelButtonText(String recognitionCancelButtonText) {#setRecognitionCancelButtonText-java.lang.String-}
```
public void setRecognitionCancelButtonText(String recognitionCancelButtonText)
```


Stelt de tekst in van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionCancelButtonText | java.lang.String | tekst van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven |

### setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor) {#setRecognitionCancelButtonTextColor-int-}
```
public void setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)
```


Stelt de kleur in van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionCancelButtonTextColor | int | kleur van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven |

### setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize) {#setRecognitionCancelButtonTextSize-float-}
```
public void setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)
```


Stelt de tekstgrootte in van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionCancelButtonTextSize | float | tekstgrootte van de "Cancel"-knop die onder de voortgang wordt weergegeven |

### setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible) {#setRecognitionCancelButtonVisibility-boolean-}
```
public void setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)
```


Stelt de zichtbaarheid in van de "Cancel"-knop die onder de voortgangsbalk wordt weergegeven tijdens herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionCancelButtonVisible | boolean | zichtbaarheid van "Cancel" knop |

### setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText) {#setRecognitionProcessAboveLabelText-java.lang.String-}
```
public void setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)
```


Stelt de tekst in van TextView die boven de voortgangsbalk wordt weergegeven tijdens herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionProcessAboveLabelText | java.lang.String | tekst van TextView die boven de voortgangsbalk wordt weergegeven |

### setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor) {#setRecognitionProcessAboveLabelTextColor-int-}
```
public void setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)
```


Stelt de kleur in van TextView die boven de voortgangsbalk wordt weergegeven tijdens herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionProcessAboveLabelTextColor | int | kleur van TextView die boven de voortgangsbalk wordt weergegeven |

### setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize) {#setRecognitionProcessAboveLabelTextSize-int-}
```
public void setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)
```


Stelt de tekstgrootte in van TextView die boven de voortgangsbalk wordt weergegeven tijdens herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionAboveLabelTextSize | int | tekstgrootte van TextView die boven de voortgangsbalk wordt weergegeven |

### setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible) {#setRecognitionProcessAboveLabelTextVisible-boolean-}
```
public void setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)
```


Stelt de kleur in van TextView die boven de voortgangsbalk wordt weergegeven tijdens herkenning

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionProcessAboveLabelTextVisible | boolean | kleur van TextView die boven de voortgangsbalk wordt weergegeven |

### setRecognitionProgressBarSize(int progressBarSize) {#setRecognitionProgressBarSize-int-}
```
public void setRecognitionProgressBarSize(int progressBarSize)
```


Stelt de grootte in van de voortgangsbalk die wordt weergegeven tijdens herkenning

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

