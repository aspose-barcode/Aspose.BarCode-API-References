---
title: CameraProcessingFragmentSettings
second_title: Aspose.BarCode for Android via Java API Reference
description: Settings for CameraProcessingFragment
type: docs
weight: 20
url: /ja/androidjava/com.aspose.barcode.component.barcodescanner/cameraprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class CameraProcessingFragmentSettings implements Parcelable
```

Settings for CameraProcessingFragment
## フィールド

| フィールド | Description |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Description |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraProcessingMode()](#getCameraProcessingMode--) | カメラ使用モードを取得します。 |
| [getCameraResolution()](#getCameraResolution--) | 現在のカメラ解像度を取得します。デフォルトは最小解像度です。 |
| [getClass()](#getClass--) |  |
| [getPreferencesButtonContentDescriptionText()](#getPreferencesButtonContentDescriptionText--) | PreferencesButtonContent の ContentDescriptionText を取得します。 |
| [getRecognitionAreaSettings()](#getRecognitionAreaSettings--) | 認識領域マーカーに関連する設定を取得します。 |
| [getRecognitionButtonContentDescriptionText()](#getRecognitionButtonContentDescriptionText--) | RecognitionButton の ContentDescriptionText を取得します。 |
| [getRecognizeButtonSize()](#getRecognizeButtonSize--) | RecognizeButton のサイズを取得します。 |
| [getScannerPreferencesButtonSize()](#getScannerPreferencesButtonSize--) | PreferencesButton のサイズを取得します。 |
| [hashCode()](#hashCode--) |  |
| [isFlashEnabled()](#isFlashEnabled--) | フラッシュが有効な場合、true を返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraProcessingMode(CameraMode cameraProcessingMode)](#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-) | TODO: プロパティに追加しますか？ カメラ使用モードを設定します。 |
| [setCameraResolution(Size cameraResolution)](#setCameraResolution-android.util.Size-) | カメラ解像度を設定します。デフォルトは最小解像度です。 |
| [setFlashEnabled(boolean flashEnabled)](#setFlashEnabled-boolean-) | フラッシュライトを有効に設定します。CameraMode.PHOTO のみ適用可能です。デフォルトは true です。 |
| [setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)](#setPreferencesButtonContentDescriptionText-java.lang.String-) | PreferencesButtonContent の ContentDescriptionText を設定します。 |
| [setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)](#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-) | 認識領域マーカーに関連する設定を設定します。 |
| [setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)](#setRecognitionButtonContentDescriptionText-java.lang.String-) | RecognitionButton の ContentDescriptionText を設定します。 |
| [setRecognizeButtonSize(int recognizeImageButtonSize)](#setRecognizeButtonSize-int-) | RecognizeButton のサイズを設定します。 |
| [setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)](#setScannerPreferencesButtonSize-int-) | PreferencesButton のサイズを設定します。 |
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCameraProcessingMode() {#getCameraProcessingMode--}
```
public CameraMode getCameraProcessingMode()
```


カメラ使用モードを取得します。現在、PHOTO と SNAPSHOT の 2 つのモードがサポートされています

**Returns:**
[CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) - mode of camera usage
### getCameraResolution() {#getCameraResolution--}
```
public Size getCameraResolution()
```


現在のカメラ解像度を取得します。デフォルトは最小解像度です。

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


PreferencesButtonContent の ContentDescriptionText を取得します。

**Returns:**
java.lang.String - PreferencesButtonContent の ContentDescriptionText
### getRecognitionAreaSettings() {#getRecognitionAreaSettings--}
```
public RecognitionAreaSettings getRecognitionAreaSettings()
```


認識領域マーカーに関連する設定を取得します。

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings
### getRecognitionButtonContentDescriptionText() {#getRecognitionButtonContentDescriptionText--}
```
public String getRecognitionButtonContentDescriptionText()
```


RecognitionButton の ContentDescriptionText を取得します。

**Returns:**
java.lang.String - RecognitionButton の ContentDescriptionText
### getRecognizeButtonSize() {#getRecognizeButtonSize--}
```
public int getRecognizeButtonSize()
```


RecognizeButton のサイズを取得します。

**Returns:**
int - RecognizeButton のサイズ
### getScannerPreferencesButtonSize() {#getScannerPreferencesButtonSize--}
```
public int getScannerPreferencesButtonSize()
```


PreferencesButton のサイズを取得します。

**Returns:**
int - PreferencesButton のサイズ
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


フラッシュが有効な場合は true を返します。CameraMode.PHOTO のみで使用可能です。デフォルトは true です

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


TODO プロパティに追加しますか？ カメラ使用モードを設定します。現在、PHOTO と SNAPSHOT の 2 つのモードがサポートされています

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cameraProcessingMode | [CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) |  |

### setCameraResolution(Size cameraResolution) {#setCameraResolution-android.util.Size-}
```
public void setCameraResolution(Size cameraResolution)
```


カメラ解像度を設定します。デフォルトは最小解像度です。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cameraResolution | android.util.Size |  |

### setFlashEnabled(boolean flashEnabled) {#setFlashEnabled-boolean-}
```
public void setFlashEnabled(boolean flashEnabled)
```


フラッシュライトを有効に設定します。CameraMode.PHOTO のみ適用可能です。デフォルトは true です。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flashEnabled | boolean |  |

### setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText) {#setPreferencesButtonContentDescriptionText-java.lang.String-}
```
public void setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)
```


PreferencesButtonContent の ContentDescriptionText を設定します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| preferencesButtonContentDescriptionText | java.lang.String | PreferencesButtonContent の ContentDescriptionText |

### setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings) {#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-}
```
public void setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)
```


認識領域マーカーに関連する設定を設定します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionAreaSettings | com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings |  |

### setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText) {#setRecognitionButtonContentDescriptionText-java.lang.String-}
```
public void setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)
```


RecognitionButton の ContentDescriptionText を設定します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionButtonContentDescriptionText | java.lang.String | RecognitionButton の ContentDescriptionText |

### setRecognizeButtonSize(int recognizeImageButtonSize) {#setRecognizeButtonSize-int-}
```
public void setRecognizeButtonSize(int recognizeImageButtonSize)
```


RecognizeButton のサイズを設定します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognizeImageButtonSize | int | RecognizeButton のサイズ |

### setScannerPreferencesButtonSize(int scannerPreferencesButtonSize) {#setScannerPreferencesButtonSize-int-}
```
public void setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)
```


PreferencesButton のサイズを設定します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scannerPreferencesButtonSize | int | PreferencesButton のサイズ |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel parcel, int i) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel parcel, int i)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parcel | android.os.Parcel |  |
| i | int |  |

