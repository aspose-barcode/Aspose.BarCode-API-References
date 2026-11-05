---
title: "RecognitionProcessingFragmentSettings"
second_title: "Aspose.BarCode for Android via Java API 参考"
description: 
type: docs
weight: 27
url: /zh/androidjava/com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionProcessingFragmentSettings implements Parcelable
```
## 字段

| 字段 | 描述 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundDuringRecognitionProcess()](#getBackgroundDuringRecognitionProcess--) | 获取将在识别过程中渲染的背景 |
| [getClass()](#getClass--) |  |
| [getProgressBarColor()](#getProgressBarColor--) | 获取在识别过程中渲染的进度条颜色 |
| [getProgressBarSize()](#getProgressBarSize--) | 获取在识别过程中渲染的进度条大小 |
| [getRecognitionCancelButtonRightOffset()](#getRecognitionCancelButtonRightOffset--) | 获取在识别过程中渲染于进度条下方的“Cancel”按钮距右边框的偏移量 |
| [getRecognitionCancelButtonText()](#getRecognitionCancelButtonText--) | 获取在识别过程中渲染于进度条下方的“Cancel”按钮的文本 |
| [getRecognitionCancelButtonTextColor()](#getRecognitionCancelButtonTextColor--) | 获取在识别过程中渲染于进度条下方的“Cancel”按钮的颜色 |
| [getRecognitionCancelButtonTextSize()](#getRecognitionCancelButtonTextSize--) | 获取在识别过程中渲染于进度条下方的“Cancel”按钮的文字大小 |
| [getRecognitionCancelButtonVisibility()](#getRecognitionCancelButtonVisibility--) | 获取在识别过程中渲染于进度条下方的“Cancel”按钮的可见性 |
| [getRecognitionProcessAboveLabelText()](#getRecognitionProcessAboveLabelText--) | 获取在识别过程中渲染于进度条上方的 TextView 文本 |
| [getRecognitionProcessAboveLabelTextColor()](#getRecognitionProcessAboveLabelTextColor--) | 获取在识别过程中渲染于进度条上方的 TextView 颜色 |
| [getRecognitionProcessAboveLabelTextSize()](#getRecognitionProcessAboveLabelTextSize--) | 获取在识别过程中渲染于进度条上方的 TextView 文字大小 |
| [getRecognitionProcessAboveLabelTextVisible()](#getRecognitionProcessAboveLabelTextVisible--) | 获取在识别过程中渲染于进度条上方的 TextView 颜色 |
| [hashCode()](#hashCode--) |  |
| [importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)](#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-) | 导入设置 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)](#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-) | 设置将在识别过程中渲染的背景 |
| [setProgressBarColor(int progressBarColor)](#setProgressBarColor-int-) | 设置在识别过程中渲染的进度条颜色 |
| [setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)](#setRecognitionCancelButtonRightOffset-int-) | 设置在识别过程中渲染于进度条下方的“Cancel”按钮距右边框的偏移量 |
| [setRecognitionCancelButtonText(String recognitionCancelButtonText)](#setRecognitionCancelButtonText-java.lang.String-) | 设置在识别过程中渲染于进度条下方的“Cancel”按钮的文本 |
| [setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)](#setRecognitionCancelButtonTextColor-int-) | 设置在识别过程中渲染于进度条下方的“Cancel”按钮的颜色 |
| [setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)](#setRecognitionCancelButtonTextSize-float-) | 设置在识别过程中渲染于进度条下方的“Cancel”按钮的文字大小 |
| [setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)](#setRecognitionCancelButtonVisibility-boolean-) | 设置在识别过程中渲染于进度条下方的“Cancel”按钮的可见性 |
| [setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)](#setRecognitionProcessAboveLabelText-java.lang.String-) | 设置在识别过程中渲染于进度条上方的 TextView 文本 |
| [setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)](#setRecognitionProcessAboveLabelTextColor-int-) | 设置在识别过程中渲染于进度条上方的 TextView 颜色 |
| [setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)](#setRecognitionProcessAboveLabelTextSize-int-) | 设置在识别过程中渲染于进度条上方的 TextView 文字大小 |
| [setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)](#setRecognitionProcessAboveLabelTextVisible-boolean-) | 设置在识别过程中渲染于进度条上方的 TextView 颜色 |
| [setRecognitionProgressBarSize(int progressBarSize)](#setRecognitionProgressBarSize-int-) | 设置在识别过程中渲染的进度条大小 |
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
整数
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getBackgroundDuringRecognitionProcess() {#getBackgroundDuringRecognitionProcess--}
```
public RecognitionProcessFragmentBackground getBackgroundDuringRecognitionProcess()
```


获取将在识别过程中渲染的背景

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground - 将在识别过程中渲染的背景
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


获取在识别过程中渲染的进度条颜色

**Returns:**
int - 进度条颜色
### getProgressBarSize() {#getProgressBarSize--}
```
public int getProgressBarSize()
```


获取在识别过程中渲染的进度条大小

**Returns:**
int - 进度条的大小
### getRecognitionCancelButtonRightOffset() {#getRecognitionCancelButtonRightOffset--}
```
public int getRecognitionCancelButtonRightOffset()
```


获取在识别过程中渲染于进度条下方的“Cancel”按钮距右边框的偏移量

**Returns:**
int - "Cancel"按钮右边框的偏移量
### getRecognitionCancelButtonText() {#getRecognitionCancelButtonText--}
```
public String getRecognitionCancelButtonText()
```


获取在识别过程中渲染于进度条下方的“Cancel”按钮的文本

**Returns:**
java.lang.String - 渲染在进度条下方的"Cancel"按钮的文本
### getRecognitionCancelButtonTextColor() {#getRecognitionCancelButtonTextColor--}
```
public int getRecognitionCancelButtonTextColor()
```


获取在识别过程中渲染于进度条下方的“Cancel”按钮的颜色

**Returns:**
int - 渲染在进度条下方的"Cancel"按钮的颜色
### getRecognitionCancelButtonTextSize() {#getRecognitionCancelButtonTextSize--}
```
public float getRecognitionCancelButtonTextSize()
```


获取在识别过程中渲染于进度条下方的“Cancel”按钮的文字大小

**Returns:**
float - 渲染在进度条下方的"Cancel"按钮的文字大小
### getRecognitionCancelButtonVisibility() {#getRecognitionCancelButtonVisibility--}
```
public boolean getRecognitionCancelButtonVisibility()
```


获取在识别过程中渲染于进度条下方的“Cancel”按钮的可见性

**Returns:**
boolean - "Cancel"按钮的可见性
### getRecognitionProcessAboveLabelText() {#getRecognitionProcessAboveLabelText--}
```
public String getRecognitionProcessAboveLabelText()
```


获取在识别过程中渲染于进度条上方的 TextView 文本

**Returns:**
java.lang.String - 渲染在进度条上方的TextView的文本
### getRecognitionProcessAboveLabelTextColor() {#getRecognitionProcessAboveLabelTextColor--}
```
public int getRecognitionProcessAboveLabelTextColor()
```


获取在识别过程中渲染于进度条上方的 TextView 颜色

**Returns:**
int - 渲染在进度条上方的TextView的颜色
### getRecognitionProcessAboveLabelTextSize() {#getRecognitionProcessAboveLabelTextSize--}
```
public float getRecognitionProcessAboveLabelTextSize()
```


获取在识别过程中渲染于进度条上方的 TextView 文字大小

**Returns:**
float - 渲染在进度条上方的TextView的文字大小
### getRecognitionProcessAboveLabelTextVisible() {#getRecognitionProcessAboveLabelTextVisible--}
```
public boolean getRecognitionProcessAboveLabelTextVisible()
```


获取在识别过程中渲染于进度条上方的 TextView 颜色

**Returns:**
boolean - 渲染在进度条上方的TextView的颜色
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
整数
### importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings) {#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-}
```
public void importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)
```


导入设置

**Parameters:**
| 参数 | 类型 | 描述 |
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


设置将在识别过程中渲染的背景

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| backgroundImage | com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground | 在识别过程期间将被渲染的背景 |

### setProgressBarColor(int progressBarColor) {#setProgressBarColor-int-}
```
public void setProgressBarColor(int progressBarColor)
```


设置在识别过程中渲染的进度条颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| progressBarColor | 整数 | 进度条的颜色 |

### setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset) {#setRecognitionCancelButtonRightOffset-int-}
```
public void setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)
```


设置在识别过程中渲染于进度条下方的“Cancel”按钮距右边框的偏移量

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recognitionCancelButtonRightOffset | 整数 | "Cancel"按钮右边框的偏移量 |

### setRecognitionCancelButtonText(String recognitionCancelButtonText) {#setRecognitionCancelButtonText-java.lang.String-}
```
public void setRecognitionCancelButtonText(String recognitionCancelButtonText)
```


设置在识别过程中渲染于进度条下方的“Cancel”按钮的文本

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recognitionCancelButtonText | java.lang.String | "Cancel"按钮渲染在进度条下方的文本 |

### setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor) {#setRecognitionCancelButtonTextColor-int-}
```
public void setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)
```


设置在识别过程中渲染于进度条下方的“Cancel”按钮的颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recognitionCancelButtonTextColor | 整数 | "Cancel"按钮渲染在进度条下方的颜色 |

### setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize) {#setRecognitionCancelButtonTextSize-float-}
```
public void setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)
```


设置在识别过程中渲染于进度条下方的“Cancel”按钮的文字大小

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recognitionCancelButtonTextSize | float | "Cancel"按钮渲染在进度条下方的文字大小 |

### setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible) {#setRecognitionCancelButtonVisibility-boolean-}
```
public void setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)
```


设置在识别过程中渲染于进度条下方的“Cancel”按钮的可见性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recognitionCancelButtonVisible | 布尔 | "Cancel"按钮的可见性 |

### setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText) {#setRecognitionProcessAboveLabelText-java.lang.String-}
```
public void setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)
```


设置在识别过程中渲染于进度条上方的 TextView 文本

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recognitionProcessAboveLabelText | java.lang.String | 在进度条上方渲染的 TextView 的文本 |

### setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor) {#setRecognitionProcessAboveLabelTextColor-int-}
```
public void setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)
```


设置在识别过程中渲染于进度条上方的 TextView 颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recognitionProcessAboveLabelTextColor | 整数 | 在进度条上方渲染的 TextView 的颜色 |

### setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize) {#setRecognitionProcessAboveLabelTextSize-int-}
```
public void setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)
```


设置在识别过程中渲染于进度条上方的 TextView 文字大小

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recognitionAboveLabelTextSize | 整数 | 在进度条上方渲染的 TextView 的文字大小 |

### setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible) {#setRecognitionProcessAboveLabelTextVisible-boolean-}
```
public void setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)
```


设置在识别过程中渲染于进度条上方的 TextView 颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| recognitionProcessAboveLabelTextVisible | 布尔 | 在进度条上方渲染的 TextView 的颜色 |

### setRecognitionProgressBarSize(int progressBarSize) {#setRecognitionProgressBarSize-int-}
```
public void setRecognitionProgressBarSize(int progressBarSize)
```


设置在识别过程中渲染的进度条大小

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| progressBarSize | 整数 | 进度条的大小 |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | 整数 |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | 整数 |  |

