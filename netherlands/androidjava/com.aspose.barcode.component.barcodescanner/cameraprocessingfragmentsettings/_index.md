---
title: "CameraProcessingFragmentSettings"
second_title: "Aspose.BarCode voor Android via Java API-referentie"
description: "Instellingen voor CameraProcessingFragment"
type: docs
weight: 20
url: /nl/androidjava/com.aspose.barcode.component.barcodescanner/cameraprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class CameraProcessingFragmentSettings implements Parcelable
```

Instellingen voor CameraProcessingFragment
## Velden

| Veld | Beschrijving |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraProcessingMode()](#getCameraProcessingMode--) | Haalt de modus van cameragebruik op. |
| [getCameraResolution()](#getCameraResolution--) | Haalt de huidige cameraresolutie op. Standaard is de minimale resolutie |
| [getClass()](#getClass--) |  |
| [getPreferencesButtonContentDescriptionText()](#getPreferencesButtonContentDescriptionText--) | Haalt ContentDescriptionText van PreferencesButtonContent op |
| [getRecognitionAreaSettings()](#getRecognitionAreaSettings--) | Haalt instelling gerelateerd aan herkenningsgebiedmarker op |
| [getRecognitionButtonContentDescriptionText()](#getRecognitionButtonContentDescriptionText--) | Haalt ContentDescriptionText van RecognitionButton op |
| [getRecognizeButtonSize()](#getRecognizeButtonSize--) | Haalt grootte van RecognizeButton op |
| [getScannerPreferencesButtonSize()](#getScannerPreferencesButtonSize--) | Haalt grootte van PreferencesButton op |
| [hashCode()](#hashCode--) |  |
| [isFlashEnabled()](#isFlashEnabled--) | Retourneert true, als flits is ingeschakeld. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraProcessingMode(CameraMode cameraProcessingMode)](#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-) | TODO toevoegen aan eigenschappen? Stelt modus van cameragebruik in. |
| [setCameraResolution(Size cameraResolution)](#setCameraResolution-android.util.Size-) | Stelt cameraresolutie in. Standaard is de minimale resolutie |
| [setFlashEnabled(boolean flashEnabled)](#setFlashEnabled-boolean-) | Stelt inschakelen van flitslicht in. Alleen geschikt met CameraMode.PHOTO. Standaard is true |
| [setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)](#setPreferencesButtonContentDescriptionText-java.lang.String-) | Stelt ContentDescriptionText van PreferencesButtonContent in |
| [setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)](#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-) | Stelt instelling gerelateerd aan herkenningsgebiedmarker in |
| [setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)](#setRecognitionButtonContentDescriptionText-java.lang.String-) | Stelt ContentDescriptionText van RecognitionButton in |
| [setRecognizeButtonSize(int recognizeImageButtonSize)](#setRecognizeButtonSize-int-) | Stelt grootte van RecognizeButton in |
| [setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)](#setScannerPreferencesButtonSize-int-) | Stelt grootte van PreferencesButton in |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel parcel, int i)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<CameraProcessingFragmentSettings> CREATOR
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
### getCameraProcessingMode() {#getCameraProcessingMode--}
```
public CameraMode getCameraProcessingMode()
```


Haalt modus van cameragebruik op. Huidig ondersteunt twee modi = PHOTO en SNAPSHOT

**Returns:**
[CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) - mode of camera usage
### getCameraResolution() {#getCameraResolution--}
```
public Size getCameraResolution()
```


Haalt de huidige cameraresolutie op. Standaard is de minimale resolutie

**Returns:**
android.util.Size -
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPreferencesButtonContentDescriptionText() {#getPreferencesButtonContentDescriptionText--}
```
public String getPreferencesButtonContentDescriptionText()
```


Haalt ContentDescriptionText van PreferencesButtonContent op

**Returns:**
java.lang.String - ContentDescriptionText van PreferencesButtonContent
### getRecognitionAreaSettings() {#getRecognitionAreaSettings--}
```
public RecognitionAreaSettings getRecognitionAreaSettings()
```


Haalt instelling gerelateerd aan herkenningsgebiedmarker op

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings
### getRecognitionButtonContentDescriptionText() {#getRecognitionButtonContentDescriptionText--}
```
public String getRecognitionButtonContentDescriptionText()
```


Haalt ContentDescriptionText van RecognitionButton op

**Returns:**
java.lang.String - ContentDescriptionText van RecognitionButton
### getRecognizeButtonSize() {#getRecognizeButtonSize--}
```
public int getRecognizeButtonSize()
```


Haalt grootte van RecognizeButton op

**Returns:**
int - grootte van RecognizeButton
### getScannerPreferencesButtonSize() {#getScannerPreferencesButtonSize--}
```
public int getScannerPreferencesButtonSize()
```


Haalt grootte van PreferencesButton op

**Returns:**
int - grootte van PreferencesButton
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFlashEnabled() {#isFlashEnabled--}
```
public boolean isFlashEnabled()
```


Retourneert true, als flits ingeschakeld is. Alleen geschikt met CameraMode.PHOTO Standaard is true

**Returns:**
boolean -
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCameraProcessingMode(CameraMode cameraProcessingMode) {#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-}
```
public void setCameraProcessingMode(CameraMode cameraProcessingMode)
```


TODO toevoegen aan eigenschappen? Stelt de modus van cameragebruik in. Momenteel ondersteunt twee modi = PHOTO en SNAPSHOT

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cameraProcessingMode | [CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) |  |

### setCameraResolution(Size cameraResolution) {#setCameraResolution-android.util.Size-}
```
public void setCameraResolution(Size cameraResolution)
```


Stelt cameraresolutie in. Standaard is de minimale resolutie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cameraResolution | android.util.Size |  |

### setFlashEnabled(boolean flashEnabled) {#setFlashEnabled-boolean-}
```
public void setFlashEnabled(boolean flashEnabled)
```


Stelt inschakelen van flitslicht in. Alleen geschikt met CameraMode.PHOTO. Standaard is true

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| flashEnabled | boolean |  |

### setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText) {#setPreferencesButtonContentDescriptionText-java.lang.String-}
```
public void setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)
```


Stelt ContentDescriptionText van PreferencesButtonContent in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| preferencesButtonContentDescriptionText | java.lang.String | ContentDescriptionText van PreferencesButtonContent |

### setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings) {#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-}
```
public void setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)
```


Stelt instelling gerelateerd aan herkenningsgebiedmarker in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionAreaSettings | com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings |  |

### setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText) {#setRecognitionButtonContentDescriptionText-java.lang.String-}
```
public void setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)
```


Stelt ContentDescriptionText van RecognitionButton in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionButtonContentDescriptionText | java.lang.String | ContentDescriptionText van RecognitionButton |

### setRecognizeButtonSize(int recognizeImageButtonSize) {#setRecognizeButtonSize-int-}
```
public void setRecognizeButtonSize(int recognizeImageButtonSize)
```


Stelt grootte van RecognizeButton in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognizeImageButtonSize | int | grootte van RecognizeButton |

### setScannerPreferencesButtonSize(int scannerPreferencesButtonSize) {#setScannerPreferencesButtonSize-int-}
```
public void setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)
```


Stelt grootte van PreferencesButton in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scannerPreferencesButtonSize | int | grootte van PreferencesButton |

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

### writeToParcel(Parcel parcel, int i) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel parcel, int i)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parcel | android.os.Parcel |  |
| i | int |  |

