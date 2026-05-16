---
title: CameraProcessingFragmentSettings
second_title: Aspose.BarCode for Android via Java API Reference
description: CameraProcessingFragment 설정
type: docs
weight: 20
url: /ko/androidjava/com.aspose.barcode.component.barcodescanner/cameraprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class CameraProcessingFragmentSettings implements Parcelable
```

CameraProcessingFragment 설정
## 필드

| 필드 | 설명 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraProcessingMode()](#getCameraProcessingMode--) | 카메라 사용 모드를 가져옵니다. |
| [getCameraResolution()](#getCameraResolution--) | 현재 카메라 해상도를 가져옵니다. 기본값은 최소 해상도입니다. |
| [getClass()](#getClass--) |  |
| [getPreferencesButtonContentDescriptionText()](#getPreferencesButtonContentDescriptionText--) | PreferencesButtonContent의 ContentDescriptionText를 가져옵니다. |
| [getRecognitionAreaSettings()](#getRecognitionAreaSettings--) | 인식 영역 마커와 관련된 설정을 가져옵니다. |
| [getRecognitionButtonContentDescriptionText()](#getRecognitionButtonContentDescriptionText--) | RecognitionButton의 ContentDescriptionText를 가져옵니다. |
| [getRecognizeButtonSize()](#getRecognizeButtonSize--) | RecognizeButton의 크기를 가져옵니다. |
| [getScannerPreferencesButtonSize()](#getScannerPreferencesButtonSize--) | PreferencesButton의 크기를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isFlashEnabled()](#isFlashEnabled--) | 플래시가 활성화된 경우 true를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraProcessingMode(CameraMode cameraProcessingMode)](#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-) | TODO 속성에 추가? 카메라 사용 모드를 설정합니다. |
| [setCameraResolution(Size cameraResolution)](#setCameraResolution-android.util.Size-) | 카메라 해상도를 설정합니다. 기본값은 최소 해상도입니다. |
| [setFlashEnabled(boolean flashEnabled)](#setFlashEnabled-boolean-) | 플래시 라이트를 활성화합니다. CameraMode.PHOTO와만 호환됩니다. 기본값은 true입니다. |
| [setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)](#setPreferencesButtonContentDescriptionText-java.lang.String-) | PreferencesButtonContent의 ContentDescriptionText를 설정합니다. |
| [setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)](#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-) | 인식 영역 마커와 관련된 설정을 설정합니다. |
| [setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)](#setRecognitionButtonContentDescriptionText-java.lang.String-) | RecognitionButton의 ContentDescriptionText를 설정합니다. |
| [setRecognizeButtonSize(int recognizeImageButtonSize)](#setRecognizeButtonSize-int-) | RecognizeButton의 크기를 설정합니다. |
| [setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)](#setScannerPreferencesButtonSize-int-) | PreferencesButton의 크기를 설정합니다. |
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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCameraProcessingMode() {#getCameraProcessingMode--}
```
public CameraMode getCameraProcessingMode()
```


카메라 사용 모드를 가져옵니다. 현재 두 가지 모드 = PHOTO 및 SNAPSHOT을 지원합니다

**Returns:**
[CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) - mode of camera usage
### getCameraResolution() {#getCameraResolution--}
```
public Size getCameraResolution()
```


현재 카메라 해상도를 가져옵니다. 기본값은 최소 해상도입니다.

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


PreferencesButtonContent의 ContentDescriptionText를 가져옵니다.

**Returns:**
java.lang.String - PreferencesButtonContent의 ContentDescriptionText
### getRecognitionAreaSettings() {#getRecognitionAreaSettings--}
```
public RecognitionAreaSettings getRecognitionAreaSettings()
```


인식 영역 마커와 관련된 설정을 가져옵니다.

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings
### getRecognitionButtonContentDescriptionText() {#getRecognitionButtonContentDescriptionText--}
```
public String getRecognitionButtonContentDescriptionText()
```


RecognitionButton의 ContentDescriptionText를 가져옵니다.

**Returns:**
java.lang.String - RecognitionButton의 ContentDescriptionText
### getRecognizeButtonSize() {#getRecognizeButtonSize--}
```
public int getRecognizeButtonSize()
```


RecognizeButton의 크기를 가져옵니다.

**Returns:**
int - RecognizeButton의 크기
### getScannerPreferencesButtonSize() {#getScannerPreferencesButtonSize--}
```
public int getScannerPreferencesButtonSize()
```


PreferencesButton의 크기를 가져옵니다.

**Returns:**
int - PreferencesButton의 크기
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


플래시가 활성화된 경우 true를 반환합니다. CameraMode.PHOTO와만 호환됩니다. 기본값은 true입니다

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


TODO 속성에 추가하시겠습니까? 카메라 사용 모드를 설정합니다. 현재 두 가지 모드 = PHOTO 및 SNAPSHOT을 지원합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| cameraProcessingMode | [CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) |  |

### setCameraResolution(Size cameraResolution) {#setCameraResolution-android.util.Size-}
```
public void setCameraResolution(Size cameraResolution)
```


카메라 해상도를 설정합니다. 기본값은 최소 해상도입니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| cameraResolution | android.util.Size |  |

### setFlashEnabled(boolean flashEnabled) {#setFlashEnabled-boolean-}
```
public void setFlashEnabled(boolean flashEnabled)
```


플래시 라이트를 활성화합니다. CameraMode.PHOTO와만 호환됩니다. 기본값은 true입니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| flashEnabled | boolean |  |

### setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText) {#setPreferencesButtonContentDescriptionText-java.lang.String-}
```
public void setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)
```


PreferencesButtonContent의 ContentDescriptionText를 설정합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| preferencesButtonContentDescriptionText | java.lang.String | PreferencesButtonContent의 ContentDescriptionText |

### setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings) {#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-}
```
public void setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)
```


인식 영역 마커와 관련된 설정을 설정합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| recognitionAreaSettings | com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings |  |

### setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText) {#setRecognitionButtonContentDescriptionText-java.lang.String-}
```
public void setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)
```


RecognitionButton의 ContentDescriptionText를 설정합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| recognitionButtonContentDescriptionText | java.lang.String | RecognitionButton의 ContentDescriptionText |

### setRecognizeButtonSize(int recognizeImageButtonSize) {#setRecognizeButtonSize-int-}
```
public void setRecognizeButtonSize(int recognizeImageButtonSize)
```


RecognizeButton의 크기를 설정합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| recognizeImageButtonSize | int | RecognizeButton의 크기 |

### setScannerPreferencesButtonSize(int scannerPreferencesButtonSize) {#setScannerPreferencesButtonSize-int-}
```
public void setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)
```


PreferencesButton의 크기를 설정합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| scannerPreferencesButtonSize | int | PreferencesButton의 크기 |

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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel parcel, int i) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel parcel, int i)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| parcel | android.os.Parcel |  |
| i | int |  |

