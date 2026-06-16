---
title: CameraProcessingFragmentSettings
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Pengaturan untuk CameraProcessingFragment
type: docs
weight: 20
url: /id/androidjava/com.aspose.barcode.component.barcodescanner/cameraprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class CameraProcessingFragmentSettings implements Parcelable
```

Pengaturan untuk CameraProcessingFragment
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Deskripsi |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraProcessingMode()](#getCameraProcessingMode--) | Mendapatkan mode penggunaan kamera. |
| [getCameraResolution()](#getCameraResolution--) | Mendapatkan resolusi kamera saat ini Default adalah resolusi minimal |
| [getClass()](#getClass--) |  |
| [getPreferencesButtonContentDescriptionText()](#getPreferencesButtonContentDescriptionText--) | Mendapatkan ContentDescriptionText dari PreferencesButtonContent |
| [getRecognitionAreaSettings()](#getRecognitionAreaSettings--) | Mendapatkan pengaturan yang terkait dengan penanda area pengenalan |
| [getRecognitionButtonContentDescriptionText()](#getRecognitionButtonContentDescriptionText--) | Mendapatkan ContentDescriptionText dari RecognitionButton |
| [getRecognizeButtonSize()](#getRecognizeButtonSize--) | Mendapatkan ukuran RecognizeButton |
| [getScannerPreferencesButtonSize()](#getScannerPreferencesButtonSize--) | Mendapatkan ukuran PreferencesButton |
| [hashCode()](#hashCode--) |  |
| [isFlashEnabled()](#isFlashEnabled--) | Mengembalikan true, jika flash diaktifkan. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraProcessingMode(CameraMode cameraProcessingMode)](#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-) | TODO Tambahkan ke properti? Mengatur mode penggunaan kamera. |
| [setCameraResolution(Size cameraResolution)](#setCameraResolution-android.util.Size-) | Mengatur resolusi kamera Default adalah resolusi minimal |
| [setFlashEnabled(boolean flashEnabled)](#setFlashEnabled-boolean-) | Mengatur lampu flash aktif. Hanya cocok dengan CameraMode.PHOTO. Default adalah true |
| [setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)](#setPreferencesButtonContentDescriptionText-java.lang.String-) | Mengatur ContentDescriptionText dari PreferencesButtonContent |
| [setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)](#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-) | Mengatur pengaturan yang terkait dengan penanda area pengenalan |
| [setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)](#setRecognitionButtonContentDescriptionText-java.lang.String-) | Mengatur ContentDescriptionText dari RecognitionButton |
| [setRecognizeButtonSize(int recognizeImageButtonSize)](#setRecognizeButtonSize-int-) | Mengatur ukuran RecognizeButton |
| [setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)](#setScannerPreferencesButtonSize-int-) | Mengatur ukuran PreferencesButton |
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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCameraProcessingMode() {#getCameraProcessingMode--}
```
public CameraMode getCameraProcessingMode()
```


Mendapatkan mode penggunaan kamera. Saat ini mendukung dua mode = PHOTO dan SNAPSHOT

**Returns:**
[CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) - mode of camera usage
### getCameraResolution() {#getCameraResolution--}
```
public Size getCameraResolution()
```


Mendapatkan resolusi kamera saat ini Default adalah resolusi minimal

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


Mendapatkan ContentDescriptionText dari PreferencesButtonContent

**Returns:**
java.lang.String - ContentDescriptionText dari PreferencesButtonContent
### getRecognitionAreaSettings() {#getRecognitionAreaSettings--}
```
public RecognitionAreaSettings getRecognitionAreaSettings()
```


Mendapatkan pengaturan yang terkait dengan penanda area pengenalan

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings
### getRecognitionButtonContentDescriptionText() {#getRecognitionButtonContentDescriptionText--}
```
public String getRecognitionButtonContentDescriptionText()
```


Mendapatkan ContentDescriptionText dari RecognitionButton

**Returns:**
java.lang.String - ContentDescriptionText dari RecognitionButton
### getRecognizeButtonSize() {#getRecognizeButtonSize--}
```
public int getRecognizeButtonSize()
```


Mendapatkan ukuran RecognizeButton

**Returns:**
int - ukuran RecognizeButton
### getScannerPreferencesButtonSize() {#getScannerPreferencesButtonSize--}
```
public int getScannerPreferencesButtonSize()
```


Mendapatkan ukuran PreferencesButton

**Returns:**
int - ukuran PreferencesButton
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


Mengembalikan true, jika flash diaktifkan. Hanya cocok dengan CameraMode.PHOTO. Defaultnya true

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


TODO Tambahkan ke properti? Mengatur mode penggunaan kamera. Saat ini mendukung dua mode = PHOTO dan SNAPSHOT

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| cameraProcessingMode | [CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) |  |

### setCameraResolution(Size cameraResolution) {#setCameraResolution-android.util.Size-}
```
public void setCameraResolution(Size cameraResolution)
```


Mengatur resolusi kamera Default adalah resolusi minimal

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| cameraResolution | android.util.Size |  |

### setFlashEnabled(boolean flashEnabled) {#setFlashEnabled-boolean-}
```
public void setFlashEnabled(boolean flashEnabled)
```


Mengatur lampu flash aktif. Hanya cocok dengan CameraMode.PHOTO. Default adalah true

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| flashEnabled | boolean |  |

### setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText) {#setPreferencesButtonContentDescriptionText-java.lang.String-}
```
public void setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)
```


Mengatur ContentDescriptionText dari PreferencesButtonContent

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| preferencesButtonContentDescriptionText | java.lang.String | ContentDescriptionText dari PreferencesButtonContent |

### setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings) {#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-}
```
public void setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)
```


Mengatur pengaturan yang terkait dengan penanda area pengenalan

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| recognitionAreaSettings | com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings |  |

### setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText) {#setRecognitionButtonContentDescriptionText-java.lang.String-}
```
public void setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)
```


Mengatur ContentDescriptionText dari RecognitionButton

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| recognitionButtonContentDescriptionText | java.lang.String | ContentDescriptionText dari RecognitionButton |

### setRecognizeButtonSize(int recognizeImageButtonSize) {#setRecognizeButtonSize-int-}
```
public void setRecognizeButtonSize(int recognizeImageButtonSize)
```


Mengatur ukuran RecognizeButton

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| recognizeImageButtonSize | int | ukuran RecognizeButton |

### setScannerPreferencesButtonSize(int scannerPreferencesButtonSize) {#setScannerPreferencesButtonSize-int-}
```
public void setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)
```


Mengatur ukuran PreferencesButton

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| scannerPreferencesButtonSize | int | ukuran PreferencesButton |

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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel parcel, int i) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel parcel, int i)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| parcel | android.os.Parcel |  |
| i | int |  |

