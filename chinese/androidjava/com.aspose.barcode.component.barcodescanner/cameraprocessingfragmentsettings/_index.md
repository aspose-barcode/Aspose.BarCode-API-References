---
title: CameraProcessingFragmentSettings
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: CameraProcessingFragment 的设置
type: docs
weight: 20
url: /zh/androidjava/com.aspose.barcode.component.barcodescanner/cameraprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class CameraProcessingFragmentSettings implements Parcelable
```

CameraProcessingFragment 的设置
## 字段

| 字段 | 描述 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraProcessingMode()](#getCameraProcessingMode--) | 获取相机使用模式。 |
| [getCameraResolution()](#getCameraResolution--) | 获取当前相机分辨率，默认是最低分辨率。 |
| [getClass()](#getClass--) |  |
| [getPreferencesButtonContentDescriptionText()](#getPreferencesButtonContentDescriptionText--) | 获取 PreferencesButtonContent 的 ContentDescriptionText。 |
| [getRecognitionAreaSettings()](#getRecognitionAreaSettings--) | 获取与识别区域标记相关的设置。 |
| [getRecognitionButtonContentDescriptionText()](#getRecognitionButtonContentDescriptionText--) | 获取 RecognitionButton 的 ContentDescriptionText。 |
| [getRecognizeButtonSize()](#getRecognizeButtonSize--) | 获取 RecognizeButton 的大小。 |
| [getScannerPreferencesButtonSize()](#getScannerPreferencesButtonSize--) | 获取 PreferencesButton 的大小。 |
| [hashCode()](#hashCode--) |  |
| [isFlashEnabled()](#isFlashEnabled--) | 如果启用了闪光灯，则返回 true。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraProcessingMode(CameraMode cameraProcessingMode)](#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-) | TODO 添加到属性？设置相机使用模式。 |
| [setCameraResolution(Size cameraResolution)](#setCameraResolution-android.util.Size-) | 设置相机分辨率，默认是最低分辨率。 |
| [setFlashEnabled(boolean flashEnabled)](#setFlashEnabled-boolean-) | 设置启用闪光灯，仅适用于 CameraMode.PHOTO，默认值为 true。 |
| [setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)](#setPreferencesButtonContentDescriptionText-java.lang.String-) | 设置 PreferencesButtonContent 的 ContentDescriptionText。 |
| [setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)](#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-) | 设置与识别区域标记相关的设置。 |
| [setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)](#setRecognitionButtonContentDescriptionText-java.lang.String-) | 设置 RecognitionButton 的 ContentDescriptionText。 |
| [setRecognizeButtonSize(int recognizeImageButtonSize)](#setRecognizeButtonSize-int-) | 设置 RecognizeButton 的大小。 |
| [setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)](#setScannerPreferencesButtonSize-int-) | 设置 PreferencesButton 的大小。 |
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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCameraProcessingMode() {#getCameraProcessingMode--}
```
public CameraMode getCameraProcessingMode()
```


获取相机使用模式。当前支持两种模式 = PHOTO 和 SNAPSHOT

**Returns:**
[CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) - mode of camera usage
### getCameraResolution() {#getCameraResolution--}
```
public Size getCameraResolution()
```


获取当前相机分辨率，默认是最低分辨率。

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


获取 PreferencesButtonContent 的 ContentDescriptionText。

**Returns:**
java.lang.String - PreferencesButtonContent 的 ContentDescriptionText
### getRecognitionAreaSettings() {#getRecognitionAreaSettings--}
```
public RecognitionAreaSettings getRecognitionAreaSettings()
```


获取与识别区域标记相关的设置。

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings
### getRecognitionButtonContentDescriptionText() {#getRecognitionButtonContentDescriptionText--}
```
public String getRecognitionButtonContentDescriptionText()
```


获取 RecognitionButton 的 ContentDescriptionText。

**Returns:**
java.lang.String - RecognitionButton 的 ContentDescriptionText
### getRecognizeButtonSize() {#getRecognizeButtonSize--}
```
public int getRecognizeButtonSize()
```


获取 RecognizeButton 的大小。

**Returns:**
int - RecognizeButton 的大小
### getScannerPreferencesButtonSize() {#getScannerPreferencesButtonSize--}
```
public int getScannerPreferencesButtonSize()
```


获取 PreferencesButton 的大小。

**Returns:**
int - PreferencesButton 的大小
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


如果启用闪光灯则返回 true。仅适用于 CameraMode.PHOTO，默认值为 true

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


TODO 添加到属性？设置相机使用模式。当前支持两种模式 = PHOTO 和 SNAPSHOT

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cameraProcessingMode | [CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) |  |

### setCameraResolution(Size cameraResolution) {#setCameraResolution-android.util.Size-}
```
public void setCameraResolution(Size cameraResolution)
```


设置相机分辨率，默认是最低分辨率。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| cameraResolution | android.util.Size |  |

### setFlashEnabled(boolean flashEnabled) {#setFlashEnabled-boolean-}
```
public void setFlashEnabled(boolean flashEnabled)
```


设置启用闪光灯，仅适用于 CameraMode.PHOTO，默认值为 true。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| flashEnabled | boolean |  |

### setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText) {#setPreferencesButtonContentDescriptionText-java.lang.String-}
```
public void setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)
```


设置 PreferencesButtonContent 的 ContentDescriptionText。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| preferencesButtonContentDescriptionText | java.lang.String | PreferencesButtonContent 的 ContentDescriptionText |

### setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings) {#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-}
```
public void setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)
```


设置与识别区域标记相关的设置。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| recognitionAreaSettings | com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings |  |

### setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText) {#setRecognitionButtonContentDescriptionText-java.lang.String-}
```
public void setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)
```


设置 RecognitionButton 的 ContentDescriptionText。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| recognitionButtonContentDescriptionText | java.lang.String | RecognitionButton 的 ContentDescriptionText |

### setRecognizeButtonSize(int recognizeImageButtonSize) {#setRecognizeButtonSize-int-}
```
public void setRecognizeButtonSize(int recognizeImageButtonSize)
```


设置 RecognizeButton 的大小。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| recognizeImageButtonSize | int | RecognizeButton 的大小 |

### setScannerPreferencesButtonSize(int scannerPreferencesButtonSize) {#setScannerPreferencesButtonSize-int-}
```
public void setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)
```


设置 PreferencesButton 的大小。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| scannerPreferencesButtonSize | int | PreferencesButton 的大小 |

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel parcel, int i) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel parcel, int i)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| parcel | android.os.Parcel |  |
| i | int |  |

