---
title: RecognitionProcessingFragmentSettings
second_title: Aspose.BarCode for Android via Java API Reference
description: 
type: docs
weight: 27
url: /ja/androidjava/com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionProcessingFragmentSettings implements Parcelable
```
## フィールド

| フィールド | Description |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Description |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundDuringRecognitionProcess()](#getBackgroundDuringRecognitionProcess--) | 認識処理中にレンダリングされる背景を取得します |
| [getClass()](#getClass--) |  |
| [getProgressBarColor()](#getProgressBarColor--) | 認識中にレンダリングされたプログレスバーの色を取得します |
| [getProgressBarSize()](#getProgressBarSize--) | 認識中にレンダリングされたプログレスバーのサイズを取得します |
| [getRecognitionCancelButtonRightOffset()](#getRecognitionCancelButtonRightOffset--) | 認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンの右端からのオフセットを取得します |
| [getRecognitionCancelButtonText()](#getRecognitionCancelButtonText--) | 認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンのテキストを取得します |
| [getRecognitionCancelButtonTextColor()](#getRecognitionCancelButtonTextColor--) | 認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンの色を取得します |
| [getRecognitionCancelButtonTextSize()](#getRecognitionCancelButtonTextSize--) | 認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンのテキストサイズを取得します |
| [getRecognitionCancelButtonVisibility()](#getRecognitionCancelButtonVisibility--) | 認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンの表示状態を取得します |
| [getRecognitionProcessAboveLabelText()](#getRecognitionProcessAboveLabelText--) | 認識中にプログレスバーの上にレンダリングされた TextView のテキストを取得します |
| [getRecognitionProcessAboveLabelTextColor()](#getRecognitionProcessAboveLabelTextColor--) | 認識中にプログレスバーの上にレンダリングされた TextView の色を取得します |
| [getRecognitionProcessAboveLabelTextSize()](#getRecognitionProcessAboveLabelTextSize--) | 認識中にプログレスバーの上にレンダリングされた TextView のテキストサイズを取得します |
| [getRecognitionProcessAboveLabelTextVisible()](#getRecognitionProcessAboveLabelTextVisible--) | 認識中にプログレスバーの上にレンダリングされた TextView の色を取得します |
| [hashCode()](#hashCode--) |  |
| [importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)](#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-) | 設定をインポートします |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)](#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-) | 認識処理中にレンダリングされる背景を設定します |
| [setProgressBarColor(int progressBarColor)](#setProgressBarColor-int-) | 認識中にレンダリングされたプログレスバーの色を設定します |
| [setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)](#setRecognitionCancelButtonRightOffset-int-) | 認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンの右端からのオフセットを設定します |
| [setRecognitionCancelButtonText(String recognitionCancelButtonText)](#setRecognitionCancelButtonText-java.lang.String-) | 認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンのテキストを設定します |
| [setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)](#setRecognitionCancelButtonTextColor-int-) | 認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンの色を設定します |
| [setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)](#setRecognitionCancelButtonTextSize-float-) | 認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンのテキストサイズを設定します |
| [setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)](#setRecognitionCancelButtonVisibility-boolean-) | 認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンの表示状態を設定します |
| [setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)](#setRecognitionProcessAboveLabelText-java.lang.String-) | 認識中にプログレスバーの上にレンダリングされた TextView のテキストを設定します |
| [setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)](#setRecognitionProcessAboveLabelTextColor-int-) | 認識中にプログレスバーの上にレンダリングされた TextView の色を設定します |
| [setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)](#setRecognitionProcessAboveLabelTextSize-int-) | 認識中にプログレスバーの上にレンダリングされた TextView のテキストサイズを設定します |
| [setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)](#setRecognitionProcessAboveLabelTextVisible-boolean-) | 認識中にプログレスバーの上にレンダリングされた TextView の色を設定します |
| [setRecognitionProgressBarSize(int progressBarSize)](#setRecognitionProgressBarSize-int-) | 認識中にレンダリングされたプログレスバーのサイズを設定します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<RecognitionProcessingFragmentSettings> CREATOR
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
### getBackgroundDuringRecognitionProcess() {#getBackgroundDuringRecognitionProcess--}
```
public RecognitionProcessFragmentBackground getBackgroundDuringRecognitionProcess()
```


認識処理中にレンダリングされる背景を取得します

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground - 認識処理中にレンダリングされる背景
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getProgressBarColor() {#getProgressBarColor--}
```
public int getProgressBarColor()
```


認識中にレンダリングされたプログレスバーの色を取得します

**Returns:**
int - プログレスバーの色
### getProgressBarSize() {#getProgressBarSize--}
```
public int getProgressBarSize()
```


認識中にレンダリングされたプログレスバーのサイズを取得します

**Returns:**
int - プログレスバーのサイズ
### getRecognitionCancelButtonRightOffset() {#getRecognitionCancelButtonRightOffset--}
```
public int getRecognitionCancelButtonRightOffset()
```


認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンの右端からのオフセットを取得します

**Returns:**
int - "Cancel" ボタンの右端からのオフセット
### getRecognitionCancelButtonText() {#getRecognitionCancelButtonText--}
```
public String getRecognitionCancelButtonText()
```


認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンのテキストを取得します

**Returns:**
java.lang.String - プログレスバーの下に表示される "Cancel" ボタンのテキスト
### getRecognitionCancelButtonTextColor() {#getRecognitionCancelButtonTextColor--}
```
public int getRecognitionCancelButtonTextColor()
```


認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンの色を取得します

**Returns:**
int - プログレスバーの下に表示される "Cancel" ボタンの色
### getRecognitionCancelButtonTextSize() {#getRecognitionCancelButtonTextSize--}
```
public float getRecognitionCancelButtonTextSize()
```


認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンのテキストサイズを取得します

**Returns:**
float - プログレスバーの下に表示される "Cancel" ボタンのテキストサイズ
### getRecognitionCancelButtonVisibility() {#getRecognitionCancelButtonVisibility--}
```
public boolean getRecognitionCancelButtonVisibility()
```


認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンの表示状態を取得します

**Returns:**
boolean - "Cancel" ボタンの可視性
### getRecognitionProcessAboveLabelText() {#getRecognitionProcessAboveLabelText--}
```
public String getRecognitionProcessAboveLabelText()
```


認識中にプログレスバーの上にレンダリングされた TextView のテキストを取得します

**Returns:**
java.lang.String - プログレスバーの上に表示される TextView のテキスト
### getRecognitionProcessAboveLabelTextColor() {#getRecognitionProcessAboveLabelTextColor--}
```
public int getRecognitionProcessAboveLabelTextColor()
```


認識中にプログレスバーの上にレンダリングされた TextView の色を取得します

**Returns:**
int - プログレスバーの上に表示される TextView の色
### getRecognitionProcessAboveLabelTextSize() {#getRecognitionProcessAboveLabelTextSize--}
```
public float getRecognitionProcessAboveLabelTextSize()
```


認識中にプログレスバーの上にレンダリングされた TextView のテキストサイズを取得します

**Returns:**
float - プログレスバーの上に表示される TextView のテキストサイズ
### getRecognitionProcessAboveLabelTextVisible() {#getRecognitionProcessAboveLabelTextVisible--}
```
public boolean getRecognitionProcessAboveLabelTextVisible()
```


認識中にプログレスバーの上にレンダリングされた TextView の色を取得します

**Returns:**
boolean - プログレスバーの上に表示される TextView の色
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings) {#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-}
```
public void importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)
```


設定をインポートします

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionProcessingFragmentSettings | com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage) {#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-}
```
public void setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)
```


認識処理中にレンダリングされる背景を設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| backgroundImage | com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground | 認識プロセス中に表示される背景 |

### setProgressBarColor(int progressBarColor) {#setProgressBarColor-int-}
```
public void setProgressBarColor(int progressBarColor)
```


認識中にレンダリングされたプログレスバーの色を設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| progressBarColor | int | プログレスバーの色 |

### setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset) {#setRecognitionCancelButtonRightOffset-int-}
```
public void setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)
```


認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンの右端からのオフセットを設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionCancelButtonRightOffset | int | "Cancel" ボタンの右端からのオフセット |

### setRecognitionCancelButtonText(String recognitionCancelButtonText) {#setRecognitionCancelButtonText-java.lang.String-}
```
public void setRecognitionCancelButtonText(String recognitionCancelButtonText)
```


認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンのテキストを設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionCancelButtonText | java.lang.String | プログレスバーの下に表示される "Cancel" ボタンのテキスト |

### setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor) {#setRecognitionCancelButtonTextColor-int-}
```
public void setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)
```


認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンの色を設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionCancelButtonTextColor | int | プログレスバーの下に表示される "Cancel" ボタンの色 |

### setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize) {#setRecognitionCancelButtonTextSize-float-}
```
public void setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)
```


認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンのテキストサイズを設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionCancelButtonTextSize | float | \"Cancel\" ボタンのテキストサイズ（プログレスの下に表示される） |

### setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible) {#setRecognitionCancelButtonVisibility-boolean-}
```
public void setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)
```


認識中にプログレスバーの下にレンダリングされた "Cancel" ボタンの表示状態を設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionCancelButtonVisible | boolean | \"Cancel\" ボタンの可視性 |

### setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText) {#setRecognitionProcessAboveLabelText-java.lang.String-}
```
public void setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)
```


認識中にプログレスバーの上にレンダリングされた TextView のテキストを設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionProcessAboveLabelText | java.lang.String | プログレスバーの上に表示される TextView のテキスト |

### setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor) {#setRecognitionProcessAboveLabelTextColor-int-}
```
public void setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)
```


認識中にプログレスバーの上にレンダリングされた TextView の色を設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionProcessAboveLabelTextColor | int | プログレスバーの上に表示される TextView の色 |

### setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize) {#setRecognitionProcessAboveLabelTextSize-int-}
```
public void setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)
```


認識中にプログレスバーの上にレンダリングされた TextView のテキストサイズを設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionAboveLabelTextSize | int | プログレスバーの上に表示される TextView のテキストサイズ |

### setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible) {#setRecognitionProcessAboveLabelTextVisible-boolean-}
```
public void setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)
```


認識中にプログレスバーの上にレンダリングされた TextView の色を設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionProcessAboveLabelTextVisible | boolean | プログレスバーの上に表示される TextView の色 |

### setRecognitionProgressBarSize(int progressBarSize) {#setRecognitionProgressBarSize-int-}
```
public void setRecognitionProgressBarSize(int progressBarSize)
```


認識中にレンダリングされたプログレスバーのサイズを設定します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| progressBarSize | int | プログレスバーのサイズ |

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

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

