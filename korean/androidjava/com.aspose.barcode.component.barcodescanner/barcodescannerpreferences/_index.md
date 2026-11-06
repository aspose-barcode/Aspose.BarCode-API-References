---
title: "BarcodeScannerPreferences"
second_title: "Aspose.BarCode for Android via Java API 참조"
description: "BarcodeScanner 기본 설정."
type: docs
weight: 16
url: /ko/androidjava/com.aspose.barcode.component.barcodescanner/barcodescannerpreferences/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class BarcodeScannerPreferences implements Parcelable
```

BarcodeScannerPreferences 설정. 인식 과정 및 인식된 데이터에 영향을 주는 매개변수를 포함합니다. BarcodeScannerPreferences는 BarcodeRecognitionSettings를 상속합니다, BarcodeScannerPreferences 클래스는 BarcodeScanner API에 특화된 내용을 포함하고 있으며, 클라이언트 액티비티와 BarcodeScannerActivity 간에 설정을 교환하기 위해 Parcelable 인터페이스를 구현합니다. BarcodeScannerPreferences는 BarcodeScannerActivity를 통해 클라이언트 애플리케이션 내부에서만 작동합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeRecognitionSettings()](#getBarcodeRecognitionSettings--) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isRotationEnabled()](#isRotationEnabled--) | 디스플레이 회전이 활성화된 상태를 가져옵니다. 기본값은 false입니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setRotationEnabled(boolean rotationEnabled)](#setRotationEnabled-boolean-) | 디스플레이 회전을 활성화하도록 설정합니다. 권장 사용은 false입니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<BarcodeScannerPreferences> CREATOR
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBarcodeRecognitionSettings() {#getBarcodeRecognitionSettings--}
```
public BarcodeRecognitionSettings getBarcodeRecognitionSettings()
```




**Returns:**
com.aspose.barcode.component.barcodescanner.BarcodeRecognitionSettings
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isRotationEnabled() {#isRotationEnabled--}
```
public boolean isRotationEnabled()
```


디스플레이 회전이 활성화된 상태를 가져옵니다. 기본값은 false입니다.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setRotationEnabled(boolean rotationEnabled) {#setRotationEnabled-boolean-}
```
public void setRotationEnabled(boolean rotationEnabled)
```


디스플레이 회전을 활성화하도록 설정합니다. 권장 사용은 false입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rotationEnabled | boolean |  |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

