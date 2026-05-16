---
title: RecognitionProcessingFragmentSettings
second_title: Aspose.BarCode for Android via Java API Reference
description: 
type: docs
weight: 27
url: /ko/androidjava/com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionProcessingFragmentSettings implements Parcelable
```
## 필드

| 필드 | 설명 |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundDuringRecognitionProcess()](#getBackgroundDuringRecognitionProcess--) | 인식 과정 중에 렌더링될 배경을 가져옵니다 |
| [getClass()](#getClass--) |  |
| [getProgressBarColor()](#getProgressBarColor--) | 인식 중에 렌더링된 진행 표시줄의 색상을 가져옵니다 |
| [getProgressBarSize()](#getProgressBarSize--) | 인식 중에 렌더링된 진행 표시줄의 크기를 가져옵니다 |
| [getRecognitionCancelButtonRightOffset()](#getRecognitionCancelButtonRightOffset--) | 인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 오른쪽 테두리로부터의 오프셋을 가져옵니다 |
| [getRecognitionCancelButtonText()](#getRecognitionCancelButtonText--) | 인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 텍스트를 가져옵니다 |
| [getRecognitionCancelButtonTextColor()](#getRecognitionCancelButtonTextColor--) | 인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 색상을 가져옵니다 |
| [getRecognitionCancelButtonTextSize()](#getRecognitionCancelButtonTextSize--) | 인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 텍스트 크기를 가져옵니다 |
| [getRecognitionCancelButtonVisibility()](#getRecognitionCancelButtonVisibility--) | 인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 가시성을 가져옵니다 |
| [getRecognitionProcessAboveLabelText()](#getRecognitionProcessAboveLabelText--) | 인식 중 진행 표시줄 위에 렌더링된 TextView의 텍스트를 가져옵니다 |
| [getRecognitionProcessAboveLabelTextColor()](#getRecognitionProcessAboveLabelTextColor--) | 인식 중 진행 표시줄 위에 렌더링된 TextView의 색상을 가져옵니다 |
| [getRecognitionProcessAboveLabelTextSize()](#getRecognitionProcessAboveLabelTextSize--) | 인식 중 진행 표시줄 위에 렌더링된 TextView의 텍스트 크기를 가져옵니다 |
| [getRecognitionProcessAboveLabelTextVisible()](#getRecognitionProcessAboveLabelTextVisible--) | 인식 중 진행 표시줄 위에 렌더링된 TextView의 색상을 가져옵니다 |
| [hashCode()](#hashCode--) |  |
| [importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)](#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-) | 설정을 가져옵니다 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)](#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-) | 인식 과정 중에 렌더링될 배경을 설정합니다 |
| [setProgressBarColor(int progressBarColor)](#setProgressBarColor-int-) | 인식 중에 렌더링된 진행 표시줄의 색상을 설정합니다 |
| [setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)](#setRecognitionCancelButtonRightOffset-int-) | 인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 오른쪽 테두리로부터의 오프셋을 설정합니다 |
| [setRecognitionCancelButtonText(String recognitionCancelButtonText)](#setRecognitionCancelButtonText-java.lang.String-) | 인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 텍스트를 설정합니다 |
| [setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)](#setRecognitionCancelButtonTextColor-int-) | 인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 색상을 설정합니다 |
| [setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)](#setRecognitionCancelButtonTextSize-float-) | 인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 텍스트 크기를 설정합니다 |
| [setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)](#setRecognitionCancelButtonVisibility-boolean-) | 인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 가시성을 설정합니다 |
| [setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)](#setRecognitionProcessAboveLabelText-java.lang.String-) | 인식 중 진행 표시줄 위에 렌더링된 TextView의 텍스트를 설정합니다 |
| [setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)](#setRecognitionProcessAboveLabelTextColor-int-) | 인식 중 진행 표시줄 위에 렌더링된 TextView의 색상을 설정합니다 |
| [setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)](#setRecognitionProcessAboveLabelTextSize-int-) | 인식 중 진행 표시줄 위에 렌더링된 TextView의 텍스트 크기를 설정합니다 |
| [setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)](#setRecognitionProcessAboveLabelTextVisible-boolean-) | 인식 중 진행 표시줄 위에 렌더링된 TextView의 색상을 설정합니다 |
| [setRecognitionProgressBarSize(int progressBarSize)](#setRecognitionProgressBarSize-int-) | 인식 중에 렌더링된 진행 표시줄의 크기를 설정합니다 |
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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBackgroundDuringRecognitionProcess() {#getBackgroundDuringRecognitionProcess--}
```
public RecognitionProcessFragmentBackground getBackgroundDuringRecognitionProcess()
```


인식 과정 중에 렌더링될 배경을 가져옵니다

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground - 인식 과정 중에 렌더링될 배경
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


인식 중에 렌더링된 진행 표시줄의 색상을 가져옵니다

**Returns:**
int - 진행 표시줄 색상
### getProgressBarSize() {#getProgressBarSize--}
```
public int getProgressBarSize()
```


인식 중에 렌더링된 진행 표시줄의 크기를 가져옵니다

**Returns:**
int - 진행 표시줄 크기
### getRecognitionCancelButtonRightOffset() {#getRecognitionCancelButtonRightOffset--}
```
public int getRecognitionCancelButtonRightOffset()
```


인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 오른쪽 테두리로부터의 오프셋을 가져옵니다

**Returns:**
int - "Cancel" 버튼의 오른쪽 경계로부터 오프셋
### getRecognitionCancelButtonText() {#getRecognitionCancelButtonText--}
```
public String getRecognitionCancelButtonText()
```


인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 텍스트를 가져옵니다

**Returns:**
java.lang.String - 진행 표시줄 아래에 표시되는 "Cancel" 버튼 텍스트
### getRecognitionCancelButtonTextColor() {#getRecognitionCancelButtonTextColor--}
```
public int getRecognitionCancelButtonTextColor()
```


인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 색상을 가져옵니다

**Returns:**
int - 진행 표시줄 아래에 표시되는 "Cancel" 버튼 색상
### getRecognitionCancelButtonTextSize() {#getRecognitionCancelButtonTextSize--}
```
public float getRecognitionCancelButtonTextSize()
```


인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 텍스트 크기를 가져옵니다

**Returns:**
float - 진행 표시줄 아래에 표시되는 "Cancel" 버튼 텍스트 크기
### getRecognitionCancelButtonVisibility() {#getRecognitionCancelButtonVisibility--}
```
public boolean getRecognitionCancelButtonVisibility()
```


인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 가시성을 가져옵니다

**Returns:**
boolean - "Cancel" 버튼 가시성
### getRecognitionProcessAboveLabelText() {#getRecognitionProcessAboveLabelText--}
```
public String getRecognitionProcessAboveLabelText()
```


인식 중 진행 표시줄 위에 렌더링된 TextView의 텍스트를 가져옵니다

**Returns:**
java.lang.String - 진행 표시줄 위에 표시되는 TextView 텍스트
### getRecognitionProcessAboveLabelTextColor() {#getRecognitionProcessAboveLabelTextColor--}
```
public int getRecognitionProcessAboveLabelTextColor()
```


인식 중 진행 표시줄 위에 렌더링된 TextView의 색상을 가져옵니다

**Returns:**
int - 진행 표시줄 위에 표시되는 TextView 색상
### getRecognitionProcessAboveLabelTextSize() {#getRecognitionProcessAboveLabelTextSize--}
```
public float getRecognitionProcessAboveLabelTextSize()
```


인식 중 진행 표시줄 위에 렌더링된 TextView의 텍스트 크기를 가져옵니다

**Returns:**
float - 진행 표시줄 위에 표시되는 TextView 텍스트 크기
### getRecognitionProcessAboveLabelTextVisible() {#getRecognitionProcessAboveLabelTextVisible--}
```
public boolean getRecognitionProcessAboveLabelTextVisible()
```


인식 중 진행 표시줄 위에 렌더링된 TextView의 색상을 가져옵니다

**Returns:**
boolean - 진행 표시줄 위에 표시되는 TextView 색상
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


설정을 가져옵니다

**Parameters:**
| Parameter | Type | 설명 |
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


인식 과정 중에 렌더링될 배경을 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| backgroundImage | com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground | 인식 과정 중에 렌더링될 배경 |

### setProgressBarColor(int progressBarColor) {#setProgressBarColor-int-}
```
public void setProgressBarColor(int progressBarColor)
```


인식 중에 렌더링된 진행 표시줄의 색상을 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| progressBarColor | int | 진행 표시줄 색상 |

### setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset) {#setRecognitionCancelButtonRightOffset-int-}
```
public void setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)
```


인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 오른쪽 테두리로부터의 오프셋을 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| recognitionCancelButtonRightOffset | int | "Cancel" 버튼의 오른쪽 경계로부터 오프셋 |

### setRecognitionCancelButtonText(String recognitionCancelButtonText) {#setRecognitionCancelButtonText-java.lang.String-}
```
public void setRecognitionCancelButtonText(String recognitionCancelButtonText)
```


인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 텍스트를 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| recognitionCancelButtonText | java.lang.String | "Cancel" 버튼이 진행 표시줄 아래에 표시되는 텍스트 |

### setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor) {#setRecognitionCancelButtonTextColor-int-}
```
public void setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)
```


인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 색상을 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| recognitionCancelButtonTextColor | int | 진행 표시줄 아래에 표시되는 "Cancel" 버튼 색상 |

### setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize) {#setRecognitionCancelButtonTextSize-float-}
```
public void setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)
```


인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 텍스트 크기를 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| recognitionCancelButtonTextSize | float | "Cancel" 버튼 아래에 렌더링된 텍스트 크기 |

### setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible) {#setRecognitionCancelButtonVisibility-boolean-}
```
public void setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)
```


인식 중 진행 표시줄 아래에 렌더링된 "Cancel" 버튼의 가시성을 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| recognitionCancelButtonVisible | boolean | "Cancel" 버튼의 가시성 |

### setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText) {#setRecognitionProcessAboveLabelText-java.lang.String-}
```
public void setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)
```


인식 중 진행 표시줄 위에 렌더링된 TextView의 텍스트를 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| recognitionProcessAboveLabelText | java.lang.String | 진행 표시줄 위에 렌더링된 TextView의 텍스트 |

### setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor) {#setRecognitionProcessAboveLabelTextColor-int-}
```
public void setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)
```


인식 중 진행 표시줄 위에 렌더링된 TextView의 색상을 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| recognitionProcessAboveLabelTextColor | int | 진행 표시줄 위에 렌더링된 TextView의 색상 |

### setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize) {#setRecognitionProcessAboveLabelTextSize-int-}
```
public void setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)
```


인식 중 진행 표시줄 위에 렌더링된 TextView의 텍스트 크기를 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| recognitionAboveLabelTextSize | int | 진행 표시줄 위에 렌더링된 TextView의 텍스트 크기 |

### setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible) {#setRecognitionProcessAboveLabelTextVisible-boolean-}
```
public void setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)
```


인식 중 진행 표시줄 위에 렌더링된 TextView의 색상을 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| recognitionProcessAboveLabelTextVisible | boolean | 진행 표시줄 위에 렌더링된 TextView의 색상 |

### setRecognitionProgressBarSize(int progressBarSize) {#setRecognitionProgressBarSize-int-}
```
public void setRecognitionProgressBarSize(int progressBarSize)
```


인식 중에 렌더링된 진행 표시줄의 크기를 설정합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| progressBarSize | int | 진행 표시줄의 크기 |

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

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

