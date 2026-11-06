---
title: "CameraProcessingFragmentSettings"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "CameraProcessingFragment の設定"
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

CameraProcessingFragment の設定
## フィールド

| フィールド | 説明 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## メソッド

| メソッド | 説明 |
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
| [isFlashEnabled()](#isFlashEnabled--) | フラッシュが有効な場合は true を返します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraProcessingMode(CameraMode cameraProcessingMode)](#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-) | TODO: プロパティに追加しますか？ カメラ使用モードを設定します。 |
| [setCameraResolution(Size cameraResolution)](#setCameraResolution-android.util.Size-) | カメラ解像度を設定します。デフォルトは最小解像度です。 |
| [setFlashEnabled(boolean flashEnabled)](#setFlashEnabled-boolean-) | フラッシュライトの有効化を設定します。CameraMode.PHOTO のみで使用可能です。デフォルトは true です。 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCameraProcessingMode() {#getCameraProcessingMode--}
```
public CameraMode getCameraProcessingMode()
```


カメラ使用モードを取得します。現在、PHOTO と SNAPSHOT の 2 つのモードがサポートされています。

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
java.lang.String - ContentDescriptionText の PreferencesButtonContent
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
java.lang.String - ContentDescriptionText の RecognitionButton
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


フラッシュが有効な場合は true を返します。CameraMode.PHOTO のみで使用可能です。デフォルトは true です。

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


TODO プロパティに追加しますか？ カメラ使用モードを設定します。現在は PHOTO と SNAPSHOT の 2 つのモードをサポートしています。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cameraProcessingMode | [CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) |  |

### setCameraResolution(Size cameraResolution) {#setCameraResolution-android.util.Size-}
```
public void setCameraResolution(Size cameraResolution)
```


カメラ解像度を設定します。デフォルトは最小解像度です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cameraResolution | android.util.Size |  |

### setFlashEnabled(boolean flashEnabled) {#setFlashEnabled-boolean-}
```
public void setFlashEnabled(boolean flashEnabled)
```


フラッシュライトの有効化を設定します。CameraMode.PHOTO のみで使用可能です。デフォルトは true です。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| flashEnabled | boolean |  |

### setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText) {#setPreferencesButtonContentDescriptionText-java.lang.String-}
```
public void setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)
```


PreferencesButtonContent の ContentDescriptionText を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| preferencesButtonContentDescriptionText | java.lang.String | ContentDescriptionText の PreferencesButtonContent |

### setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings) {#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-}
```
public void setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)
```


認識領域マーカーに関連する設定を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| recognitionAreaSettings | com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings |  |

### setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText) {#setRecognitionButtonContentDescriptionText-java.lang.String-}
```
public void setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)
```


RecognitionButton の ContentDescriptionText を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| recognitionButtonContentDescriptionText | java.lang.String | ContentDescriptionText の RecognitionButton |

### setRecognizeButtonSize(int recognizeImageButtonSize) {#setRecognizeButtonSize-int-}
```
public void setRecognizeButtonSize(int recognizeImageButtonSize)
```


RecognizeButton のサイズを設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| recognizeImageButtonSize | int | RecognizeButton のサイズ |

### setScannerPreferencesButtonSize(int scannerPreferencesButtonSize) {#setScannerPreferencesButtonSize-int-}
```
public void setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)
```


PreferencesButton のサイズを設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel parcel, int i) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel parcel, int i)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| parcel | android.os.Parcel |  |
| i | int |  |

