---
title: CameraProcessingFragmentSettings
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Paramètres pour CameraProcessingFragment
type: docs
weight: 20
url: /fr/androidjava/com.aspose.barcode.component.barcodescanner/cameraprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class CameraProcessingFragmentSettings implements Parcelable
```

Paramètres pour CameraProcessingFragment
## Champs

| Champ | Description |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraProcessingMode()](#getCameraProcessingMode--) | Obtient le mode d'utilisation de la caméra. |
| [getCameraResolution()](#getCameraResolution--) | Obtient la résolution actuelle de la caméra. La valeur par défaut est la résolution minimale. |
| [getClass()](#getClass--) |  |
| [getPreferencesButtonContentDescriptionText()](#getPreferencesButtonContentDescriptionText--) | Obtient le ContentDescriptionText de PreferencesButtonContent |
| [getRecognitionAreaSettings()](#getRecognitionAreaSettings--) | Obtient le paramètre lié au marqueur de zone de reconnaissance |
| [getRecognitionButtonContentDescriptionText()](#getRecognitionButtonContentDescriptionText--) | Obtient le ContentDescriptionText de RecognitionButton |
| [getRecognizeButtonSize()](#getRecognizeButtonSize--) | Obtient la taille de RecognizeButton |
| [getScannerPreferencesButtonSize()](#getScannerPreferencesButtonSize--) | Obtient la taille de PreferencesButton |
| [hashCode()](#hashCode--) |  |
| [isFlashEnabled()](#isFlashEnabled--) | Renvoie true si le flash est activé. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraProcessingMode(CameraMode cameraProcessingMode)](#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-) | TODO Ajouter aux propriétés ? Définit le mode d'utilisation de la caméra. |
| [setCameraResolution(Size cameraResolution)](#setCameraResolution-android.util.Size-) | Définit la résolution de la caméra. La valeur par défaut est la résolution minimale. |
| [setFlashEnabled(boolean flashEnabled)](#setFlashEnabled-boolean-) | Active le flash. Convient uniquement avec CameraMode.PHOTO. La valeur par défaut est true. |
| [setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)](#setPreferencesButtonContentDescriptionText-java.lang.String-) | Définit le ContentDescriptionText de PreferencesButtonContent |
| [setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)](#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-) | Définit le paramètre lié au marqueur de zone de reconnaissance |
| [setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)](#setRecognitionButtonContentDescriptionText-java.lang.String-) | Définit le ContentDescriptionText de RecognitionButton |
| [setRecognizeButtonSize(int recognizeImageButtonSize)](#setRecognizeButtonSize-int-) | Définit la taille de RecognizeButton |
| [setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)](#setScannerPreferencesButtonSize-int-) | Définit la taille de PreferencesButton |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCameraProcessingMode() {#getCameraProcessingMode--}
```
public CameraMode getCameraProcessingMode()
```


Obtient le mode d'utilisation de la caméra. Actuellement, deux modes sont pris en charge = PHOTO et SNAPSHOT

**Returns:**
[CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) - mode of camera usage
### getCameraResolution() {#getCameraResolution--}
```
public Size getCameraResolution()
```


Obtient la résolution actuelle de la caméra. La valeur par défaut est la résolution minimale.

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


Obtient le ContentDescriptionText de PreferencesButtonContent

**Returns:**
java.lang.String - Texte de description du contenu de PreferencesButtonContent
### getRecognitionAreaSettings() {#getRecognitionAreaSettings--}
```
public RecognitionAreaSettings getRecognitionAreaSettings()
```


Obtient le paramètre lié au marqueur de zone de reconnaissance

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings
### getRecognitionButtonContentDescriptionText() {#getRecognitionButtonContentDescriptionText--}
```
public String getRecognitionButtonContentDescriptionText()
```


Obtient le ContentDescriptionText de RecognitionButton

**Returns:**
java.lang.String - Texte de description du contenu de RecognitionButton
### getRecognizeButtonSize() {#getRecognizeButtonSize--}
```
public int getRecognizeButtonSize()
```


Obtient la taille de RecognizeButton

**Returns:**
int - taille de RecognizeButton
### getScannerPreferencesButtonSize() {#getScannerPreferencesButtonSize--}
```
public int getScannerPreferencesButtonSize()
```


Obtient la taille de PreferencesButton

**Returns:**
int - taille de PreferencesButton
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


Renvoie vrai si le flash est activé. Convient uniquement avec CameraMode.PHOTO. La valeur par défaut est vraie

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


TODO Ajouter aux propriétés ? Définit le mode d'utilisation de la caméra. Actuellement, deux modes sont pris en charge = PHOTO et SNAPSHOT

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cameraProcessingMode | [CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) |  |

### setCameraResolution(Size cameraResolution) {#setCameraResolution-android.util.Size-}
```
public void setCameraResolution(Size cameraResolution)
```


Définit la résolution de la caméra. La valeur par défaut est la résolution minimale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cameraResolution | android.util.Size |  |

### setFlashEnabled(boolean flashEnabled) {#setFlashEnabled-boolean-}
```
public void setFlashEnabled(boolean flashEnabled)
```


Active le flash. Convient uniquement avec CameraMode.PHOTO. La valeur par défaut est true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flashEnabled | boolean |  |

### setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText) {#setPreferencesButtonContentDescriptionText-java.lang.String-}
```
public void setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)
```


Définit le ContentDescriptionText de PreferencesButtonContent

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| preferencesButtonContentDescriptionText | java.lang.String | Texte de description du contenu de PreferencesButtonContent |

### setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings) {#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-}
```
public void setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)
```


Définit le paramètre lié au marqueur de zone de reconnaissance

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognitionAreaSettings | com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings |  |

### setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText) {#setRecognitionButtonContentDescriptionText-java.lang.String-}
```
public void setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)
```


Définit le ContentDescriptionText de RecognitionButton

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognitionButtonContentDescriptionText | java.lang.String | Texte de description du contenu de RecognitionButton |

### setRecognizeButtonSize(int recognizeImageButtonSize) {#setRecognizeButtonSize-int-}
```
public void setRecognizeButtonSize(int recognizeImageButtonSize)
```


Définit la taille de RecognizeButton

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognizeImageButtonSize | int | taille de RecognizeButton |

### setScannerPreferencesButtonSize(int scannerPreferencesButtonSize) {#setScannerPreferencesButtonSize-int-}
```
public void setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)
```


Définit la taille de PreferencesButton

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scannerPreferencesButtonSize | int | taille de PreferencesButton |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel parcel, int i) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel parcel, int i)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| parcel | android.os.Parcel |  |
| i | int |  |

