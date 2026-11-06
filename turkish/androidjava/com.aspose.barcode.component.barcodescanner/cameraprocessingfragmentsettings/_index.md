---
title: "CameraProcessingFragmentSettings"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: "CameraProcessingFragment ayarları"
type: docs
weight: 20
url: /tr/androidjava/com.aspose.barcode.component.barcodescanner/cameraprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class CameraProcessingFragmentSettings implements Parcelable
```

CameraProcessingFragment ayarları
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraProcessingMode()](#getCameraProcessingMode--) | Kamera kullanım modunu alır. |
| [getCameraResolution()](#getCameraResolution--) | Mevcut kamera çözünürlüğünü alır. Varsayılan en düşük çözünürlüktür. |
| [getClass()](#getClass--) |  |
| [getPreferencesButtonContentDescriptionText()](#getPreferencesButtonContentDescriptionText--) | PreferencesButtonContent öğesinin ContentDescriptionText değerini alır. |
| [getRecognitionAreaSettings()](#getRecognitionAreaSettings--) | Tanıma alanı işaretleyicisiyle ilgili ayarı alır. |
| [getRecognitionButtonContentDescriptionText()](#getRecognitionButtonContentDescriptionText--) | RecognitionButton öğesinin ContentDescriptionText değerini alır. |
| [getRecognizeButtonSize()](#getRecognizeButtonSize--) | RecognizeButton boyutunu alır. |
| [getScannerPreferencesButtonSize()](#getScannerPreferencesButtonSize--) | PreferencesButton boyutunu alır. |
| [hashCode()](#hashCode--) |  |
| [isFlashEnabled()](#isFlashEnabled--) | Flaş etkinse true döndürür. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraProcessingMode(CameraMode cameraProcessingMode)](#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-) | TODO Özelliklere ekle? Kamera kullanım modunu ayarlar. |
| [setCameraResolution(Size cameraResolution)](#setCameraResolution-android.util.Size-) | Kamera çözünürlüğünü ayarlar. Varsayılan en düşük çözünürlüktür. |
| [setFlashEnabled(boolean flashEnabled)](#setFlashEnabled-boolean-) | Flaş ışığını etkinleştirir. Yalnızca CameraMode.PHOTO ile uygundur. Varsayılan true'tur. |
| [setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)](#setPreferencesButtonContentDescriptionText-java.lang.String-) | PreferencesButtonContent öğesinin ContentDescriptionText değerini ayarlar. |
| [setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)](#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-) | Tanıma alanı işaretleyicisiyle ilgili ayarı ayarlar. |
| [setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)](#setRecognitionButtonContentDescriptionText-java.lang.String-) | RecognitionButton öğesinin ContentDescriptionText değerini ayarlar. |
| [setRecognizeButtonSize(int recognizeImageButtonSize)](#setRecognizeButtonSize-int-) | RecognizeButton boyutunu ayarlar. |
| [setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)](#setScannerPreferencesButtonSize-int-) | PreferencesButton boyutunu ayarlar. |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCameraProcessingMode() {#getCameraProcessingMode--}
```
public CameraMode getCameraProcessingMode()
```


Kamera kullanım modunu alır. Şu anda iki mod desteklenir = PHOTO ve SNAPSHOT.

**Returns:**
[CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) - mode of camera usage
### getCameraResolution() {#getCameraResolution--}
```
public Size getCameraResolution()
```


Mevcut kamera çözünürlüğünü alır. Varsayılan en düşük çözünürlüktür.

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


PreferencesButtonContent öğesinin ContentDescriptionText değerini alır.

**Returns:**
java.lang.String - PreferencesButtonContent'in ContentDescriptionText
### getRecognitionAreaSettings() {#getRecognitionAreaSettings--}
```
public RecognitionAreaSettings getRecognitionAreaSettings()
```


Tanıma alanı işaretleyicisiyle ilgili ayarı alır.

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings
### getRecognitionButtonContentDescriptionText() {#getRecognitionButtonContentDescriptionText--}
```
public String getRecognitionButtonContentDescriptionText()
```


RecognitionButton öğesinin ContentDescriptionText değerini alır.

**Returns:**
java.lang.String - RecognitionButton'un ContentDescriptionText
### getRecognizeButtonSize() {#getRecognizeButtonSize--}
```
public int getRecognizeButtonSize()
```


RecognizeButton boyutunu alır.

**Returns:**
int - RecognizeButton'un boyutu
### getScannerPreferencesButtonSize() {#getScannerPreferencesButtonSize--}
```
public int getScannerPreferencesButtonSize()
```


PreferencesButton boyutunu alır.

**Returns:**
int - PreferencesButton'un boyutu
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


True döndürür, eğer flash etkinse. Yalnızca CameraMode.PHOTO ile uygundur. Varsayılan true'tur

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


TODO Özelliklere ekle? Kamera kullanım modunu ayarlar. Şu anda iki modu destekler = PHOTO ve SNAPSHOT

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cameraProcessingMode | [CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) |  |

### setCameraResolution(Size cameraResolution) {#setCameraResolution-android.util.Size-}
```
public void setCameraResolution(Size cameraResolution)
```


Kamera çözünürlüğünü ayarlar. Varsayılan en düşük çözünürlüktür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cameraResolution | android.util.Size |  |

### setFlashEnabled(boolean flashEnabled) {#setFlashEnabled-boolean-}
```
public void setFlashEnabled(boolean flashEnabled)
```


Flaş ışığını etkinleştirir. Yalnızca CameraMode.PHOTO ile uygundur. Varsayılan true'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| flashEnabled | boolean |  |

### setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText) {#setPreferencesButtonContentDescriptionText-java.lang.String-}
```
public void setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)
```


PreferencesButtonContent öğesinin ContentDescriptionText değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| preferencesButtonContentDescriptionText | java.lang.String | PreferencesButtonContent'in ContentDescriptionText |

### setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings) {#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-}
```
public void setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)
```


Tanıma alanı işaretleyicisiyle ilgili ayarı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognitionAreaSettings | com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings |  |

### setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText) {#setRecognitionButtonContentDescriptionText-java.lang.String-}
```
public void setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)
```


RecognitionButton öğesinin ContentDescriptionText değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognitionButtonContentDescriptionText | java.lang.String | RecognitionButton'un ContentDescriptionText |

### setRecognizeButtonSize(int recognizeImageButtonSize) {#setRecognizeButtonSize-int-}
```
public void setRecognizeButtonSize(int recognizeImageButtonSize)
```


RecognizeButton boyutunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| recognizeImageButtonSize | int | RecognizeButton'un boyutu |

### setScannerPreferencesButtonSize(int scannerPreferencesButtonSize) {#setScannerPreferencesButtonSize-int-}
```
public void setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)
```


PreferencesButton boyutunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scannerPreferencesButtonSize | int | PreferencesButton'un boyutu |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel parcel, int i) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel parcel, int i)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parcel | android.os.Parcel |  |
| i | int |  |

