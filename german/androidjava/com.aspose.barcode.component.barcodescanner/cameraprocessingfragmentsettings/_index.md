---
title: CameraProcessingFragmentSettings
second_title: Aspose.BarCode für Android via Java API-Referenz
description: Einstellungen für CameraProcessingFragment
type: docs
weight: 20
url: /de/androidjava/com.aspose.barcode.component.barcodescanner/cameraprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class CameraProcessingFragmentSettings implements Parcelable
```

Einstellungen für CameraProcessingFragment
## Felder

| Feld | Beschreibung |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Beschreibung |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraProcessingMode()](#getCameraProcessingMode--) | Ermittelt den Modus der Kameranutzung. |
| [getCameraResolution()](#getCameraResolution--) | Ermittelt die aktuelle Kameraauflösung. Standard ist minimale Auflösung. |
| [getClass()](#getClass--) |  |
| [getPreferencesButtonContentDescriptionText()](#getPreferencesButtonContentDescriptionText--) | Ermittelt den ContentDescriptionText von PreferencesButtonContent |
| [getRecognitionAreaSettings()](#getRecognitionAreaSettings--) | Ermittelt die Einstellung im Zusammenhang mit dem Erkennungsbereichsmarker |
| [getRecognitionButtonContentDescriptionText()](#getRecognitionButtonContentDescriptionText--) | Ermittelt den ContentDescriptionText von RecognitionButton |
| [getRecognizeButtonSize()](#getRecognizeButtonSize--) | Ermittelt die Größe von RecognizeButton |
| [getScannerPreferencesButtonSize()](#getScannerPreferencesButtonSize--) | Ermittelt die Größe von PreferencesButton |
| [hashCode()](#hashCode--) |  |
| [isFlashEnabled()](#isFlashEnabled--) | Gibt true zurück, wenn der Blitz aktiviert ist. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraProcessingMode(CameraMode cameraProcessingMode)](#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-) | TODO zu Eigenschaften hinzufügen? Legt den Modus der Kameranutzung fest. |
| [setCameraResolution(Size cameraResolution)](#setCameraResolution-android.util.Size-) | Legt die Kameraauflösung fest. Standard ist minimale Auflösung. |
| [setFlashEnabled(boolean flashEnabled)](#setFlashEnabled-boolean-) | Aktiviert das Blitzlicht. Nur geeignet mit CameraMode.PHOTO. Standard ist true. |
| [setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)](#setPreferencesButtonContentDescriptionText-java.lang.String-) | Legt den ContentDescriptionText von PreferencesButtonContent fest. |
| [setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)](#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-) | Legt die Einstellung im Zusammenhang mit dem Erkennungsbereichsmarker fest. |
| [setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)](#setRecognitionButtonContentDescriptionText-java.lang.String-) | Legt den ContentDescriptionText von RecognitionButton fest. |
| [setRecognizeButtonSize(int recognizeImageButtonSize)](#setRecognizeButtonSize-int-) | Legt die Größe von RecognizeButton fest. |
| [setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)](#setScannerPreferencesButtonSize-int-) | Legt die Größe von PreferencesButton fest. |
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
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCameraProcessingMode() {#getCameraProcessingMode--}
```
public CameraMode getCameraProcessingMode()
```


Ermittelt den Modus der Kameranutzung. Derzeit werden zwei Modi unterstützt = PHOTO und SNAPSHOT

**Returns:**
[CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) - mode of camera usage
### getCameraResolution() {#getCameraResolution--}
```
public Size getCameraResolution()
```


Ermittelt die aktuelle Kameraauflösung. Standard ist minimale Auflösung.

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


Ermittelt den ContentDescriptionText von PreferencesButtonContent

**Returns:**
java.lang.String - ContentDescriptionText von PreferencesButtonContent
### getRecognitionAreaSettings() {#getRecognitionAreaSettings--}
```
public RecognitionAreaSettings getRecognitionAreaSettings()
```


Ermittelt die Einstellung im Zusammenhang mit dem Erkennungsbereichsmarker

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings
### getRecognitionButtonContentDescriptionText() {#getRecognitionButtonContentDescriptionText--}
```
public String getRecognitionButtonContentDescriptionText()
```


Ermittelt den ContentDescriptionText von RecognitionButton

**Returns:**
java.lang.String - ContentDescriptionText von RecognitionButton
### getRecognizeButtonSize() {#getRecognizeButtonSize--}
```
public int getRecognizeButtonSize()
```


Ermittelt die Größe von RecognizeButton

**Returns:**
int - Größe von RecognizeButton
### getScannerPreferencesButtonSize() {#getScannerPreferencesButtonSize--}
```
public int getScannerPreferencesButtonSize()
```


Ermittelt die Größe von PreferencesButton

**Returns:**
int - Größe von PreferencesButton
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


Gibt true zurück, wenn der Blitz aktiviert ist. Nur geeignet mit CameraMode.PHOTO. Standard ist true

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


TODO zu Eigenschaften hinzufügen? Legt den Modus der Kameranutzung fest. Derzeit werden zwei Modi unterstützt = PHOTO und SNAPSHOT

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| cameraProcessingMode | [CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) |  |

### setCameraResolution(Size cameraResolution) {#setCameraResolution-android.util.Size-}
```
public void setCameraResolution(Size cameraResolution)
```


Legt die Kameraauflösung fest. Standard ist minimale Auflösung.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| cameraResolution | android.util.Size |  |

### setFlashEnabled(boolean flashEnabled) {#setFlashEnabled-boolean-}
```
public void setFlashEnabled(boolean flashEnabled)
```


Aktiviert das Blitzlicht. Nur geeignet mit CameraMode.PHOTO. Standard ist true.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| flashEnabled | boolean |  |

### setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText) {#setPreferencesButtonContentDescriptionText-java.lang.String-}
```
public void setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)
```


Legt den ContentDescriptionText von PreferencesButtonContent fest.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| preferencesButtonContentDescriptionText | java.lang.String | ContentDescriptionText von PreferencesButtonContent |

### setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings) {#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-}
```
public void setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)
```


Legt die Einstellung im Zusammenhang mit dem Erkennungsbereichsmarker fest.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| recognitionAreaSettings | com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings |  |

### setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText) {#setRecognitionButtonContentDescriptionText-java.lang.String-}
```
public void setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)
```


Legt den ContentDescriptionText von RecognitionButton fest.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| recognitionButtonContentDescriptionText | java.lang.String | ContentDescriptionText von RecognitionButton |

### setRecognizeButtonSize(int recognizeImageButtonSize) {#setRecognizeButtonSize-int-}
```
public void setRecognizeButtonSize(int recognizeImageButtonSize)
```


Legt die Größe von RecognizeButton fest.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| recognizeImageButtonSize | int | Größe von RecognizeButton |

### setScannerPreferencesButtonSize(int scannerPreferencesButtonSize) {#setScannerPreferencesButtonSize-int-}
```
public void setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)
```


Legt die Größe von PreferencesButton fest.

**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| scannerPreferencesButtonSize | int | Größe von PreferencesButton |

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

### writeToParcel(Parcel parcel, int i) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel parcel, int i)
```




**Parameters:**
| Parameter | Type | Beschreibung |
| --- | --- | --- |
| parcel | android.os.Parcel |  |
| i | int |  |

