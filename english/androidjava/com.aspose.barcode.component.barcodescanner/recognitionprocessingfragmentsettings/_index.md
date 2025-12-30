---
title: RecognitionProcessingFragmentSettings
second_title: Aspose.BarCode for Android via Java API Reference
description: 
type: docs
weight: 27
url: /androidjava/com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionProcessingFragmentSettings implements Parcelable
```
## Fields

| Field | Description |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | Description |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundDuringRecognitionProcess()](#getBackgroundDuringRecognitionProcess--) | Gets the background that will be rendered during recogntion process |
| [getClass()](#getClass--) |  |
| [getProgressBarColor()](#getProgressBarColor--) | Gets color of progress bar that rendered during recognition |
| [getProgressBarSize()](#getProgressBarSize--) | Gets size of progress bar that rendered during recognition |
| [getRecognitionCancelButtonRightOffset()](#getRecognitionCancelButtonRightOffset--) | Gets offset from right border of "Cancel" Button that rendered below progress bar during recognition |
| [getRecognitionCancelButtonText()](#getRecognitionCancelButtonText--) | Gets text of "Cancel" Button that rendered below progress bar during recognition |
| [getRecognitionCancelButtonTextColor()](#getRecognitionCancelButtonTextColor--) | Gets color of "Cancel" Button that rendered below progress bar during recognition |
| [getRecognitionCancelButtonTextSize()](#getRecognitionCancelButtonTextSize--) | Gets text size of "Cancel" Button that rendered below progress bar during recognition |
| [getRecognitionCancelButtonVisibility()](#getRecognitionCancelButtonVisibility--) | Gets visibility of "Cancel" Button that rendered below progress bar during recognition |
| [getRecognitionProcessAboveLabelText()](#getRecognitionProcessAboveLabelText--) | Gets text of TextView that rendered above progress bar during recognition |
| [getRecognitionProcessAboveLabelTextColor()](#getRecognitionProcessAboveLabelTextColor--) | Gets color of TextView that rendered above progress bar during recognition |
| [getRecognitionProcessAboveLabelTextSize()](#getRecognitionProcessAboveLabelTextSize--) | Gets text size of TextView that rendered above progress bar during recognition |
| [getRecognitionProcessAboveLabelTextVisible()](#getRecognitionProcessAboveLabelTextVisible--) | Gets color of TextView that rendered above progress bar during recognition |
| [hashCode()](#hashCode--) |  |
| [importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)](#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-) | Imports the settings |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)](#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-) | Sets the background that will be rendered during recogntion process |
| [setProgressBarColor(int progressBarColor)](#setProgressBarColor-int-) | Sets color of progress bar that rendered during recognition |
| [setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)](#setRecognitionCancelButtonRightOffset-int-) | Sets offset from right border of "Cancel" Button that rendered below progress bar during recognition |
| [setRecognitionCancelButtonText(String recognitionCancelButtonText)](#setRecognitionCancelButtonText-java.lang.String-) | Sets text of "Cancel" Button that rendered below progress bar during recognition |
| [setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)](#setRecognitionCancelButtonTextColor-int-) | Sets color of "Cancel" Button that rendered below progress bar during recognition |
| [setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)](#setRecognitionCancelButtonTextSize-float-) | Sets text size of "Cancel" Button that rendered below progress bar during recognition |
| [setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)](#setRecognitionCancelButtonVisibility-boolean-) | Sets visibility of "Cancel" Button that rendered below progress bar during recognition |
| [setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)](#setRecognitionProcessAboveLabelText-java.lang.String-) | Sets text of TextView that rendered above progress bar during recognition |
| [setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)](#setRecognitionProcessAboveLabelTextColor-int-) | Sets color of TextView that rendered above progress bar during recognition |
| [setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)](#setRecognitionProcessAboveLabelTextSize-int-) | Sets text size of TextView that rendered above progress bar during recognition |
| [setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)](#setRecognitionProcessAboveLabelTextVisible-boolean-) | Sets color of TextView that rendered above progress bar during recognition |
| [setRecognitionProgressBarSize(int progressBarSize)](#setRecognitionProgressBarSize-int-) | Sets size of progress bar that rendered during recognition |
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


Gets the background that will be rendered during recogntion process

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground - the background that will be rendered during recogntion process
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


Gets color of progress bar that rendered during recognition

**Returns:**
int - color of progress bar
### getProgressBarSize() {#getProgressBarSize--}
```
public int getProgressBarSize()
```


Gets size of progress bar that rendered during recognition

**Returns:**
int - size of progress bar
### getRecognitionCancelButtonRightOffset() {#getRecognitionCancelButtonRightOffset--}
```
public int getRecognitionCancelButtonRightOffset()
```


Gets offset from right border of "Cancel" Button that rendered below progress bar during recognition

**Returns:**
int - offset from right border of "Cancel" Button
### getRecognitionCancelButtonText() {#getRecognitionCancelButtonText--}
```
public String getRecognitionCancelButtonText()
```


Gets text of "Cancel" Button that rendered below progress bar during recognition

**Returns:**
java.lang.String - text of "Cancel" Button that rendered below progress bar
### getRecognitionCancelButtonTextColor() {#getRecognitionCancelButtonTextColor--}
```
public int getRecognitionCancelButtonTextColor()
```


Gets color of "Cancel" Button that rendered below progress bar during recognition

**Returns:**
int - color of "Cancel" Button that rendered below progress bar
### getRecognitionCancelButtonTextSize() {#getRecognitionCancelButtonTextSize--}
```
public float getRecognitionCancelButtonTextSize()
```


Gets text size of "Cancel" Button that rendered below progress bar during recognition

**Returns:**
float - text size of "Cancel" Button that rendered below progress
### getRecognitionCancelButtonVisibility() {#getRecognitionCancelButtonVisibility--}
```
public boolean getRecognitionCancelButtonVisibility()
```


Gets visibility of "Cancel" Button that rendered below progress bar during recognition

**Returns:**
boolean - visibility of "Cancel" Button
### getRecognitionProcessAboveLabelText() {#getRecognitionProcessAboveLabelText--}
```
public String getRecognitionProcessAboveLabelText()
```


Gets text of TextView that rendered above progress bar during recognition

**Returns:**
java.lang.String - text of TextView that rendered above progress bar
### getRecognitionProcessAboveLabelTextColor() {#getRecognitionProcessAboveLabelTextColor--}
```
public int getRecognitionProcessAboveLabelTextColor()
```


Gets color of TextView that rendered above progress bar during recognition

**Returns:**
int - color of TextView that rendered above progress bar
### getRecognitionProcessAboveLabelTextSize() {#getRecognitionProcessAboveLabelTextSize--}
```
public float getRecognitionProcessAboveLabelTextSize()
```


Gets text size of TextView that rendered above progress bar during recognition

**Returns:**
float - text size of TextView that rendered above progress bar
### getRecognitionProcessAboveLabelTextVisible() {#getRecognitionProcessAboveLabelTextVisible--}
```
public boolean getRecognitionProcessAboveLabelTextVisible()
```


Gets color of TextView that rendered above progress bar during recognition

**Returns:**
boolean - color of TextView that rendered above progress bar
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


Imports the settings

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


Sets the background that will be rendered during recogntion process

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| backgroundImage | com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground | the background that will be rendered during recogntion process |

### setProgressBarColor(int progressBarColor) {#setProgressBarColor-int-}
```
public void setProgressBarColor(int progressBarColor)
```


Sets color of progress bar that rendered during recognition

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| progressBarColor | int | color of progress bar |

### setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset) {#setRecognitionCancelButtonRightOffset-int-}
```
public void setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)
```


Sets offset from right border of "Cancel" Button that rendered below progress bar during recognition

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionCancelButtonRightOffset | int | offset from right border of "Cancel" Button |

### setRecognitionCancelButtonText(String recognitionCancelButtonText) {#setRecognitionCancelButtonText-java.lang.String-}
```
public void setRecognitionCancelButtonText(String recognitionCancelButtonText)
```


Sets text of "Cancel" Button that rendered below progress bar during recognition

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionCancelButtonText | java.lang.String | text of "Cancel" Button that rendered below progress bar |

### setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor) {#setRecognitionCancelButtonTextColor-int-}
```
public void setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)
```


Sets color of "Cancel" Button that rendered below progress bar during recognition

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionCancelButtonTextColor | int | color of "Cancel" Button that rendered below progress bar |

### setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize) {#setRecognitionCancelButtonTextSize-float-}
```
public void setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)
```


Sets text size of "Cancel" Button that rendered below progress bar during recognition

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionCancelButtonTextSize | float | text size of "Cancel" Button that rendered below progress |

### setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible) {#setRecognitionCancelButtonVisibility-boolean-}
```
public void setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)
```


Sets visibility of "Cancel" Button that rendered below progress bar during recognition

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionCancelButtonVisible | boolean | visibility of "Cancel" Button |

### setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText) {#setRecognitionProcessAboveLabelText-java.lang.String-}
```
public void setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)
```


Sets text of TextView that rendered above progress bar during recognition

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionProcessAboveLabelText | java.lang.String | text of TextView that rendered above progress bar |

### setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor) {#setRecognitionProcessAboveLabelTextColor-int-}
```
public void setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)
```


Sets color of TextView that rendered above progress bar during recognition

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionProcessAboveLabelTextColor | int | color of TextView that rendered above progress bar |

### setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize) {#setRecognitionProcessAboveLabelTextSize-int-}
```
public void setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)
```


Sets text size of TextView that rendered above progress bar during recognition

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionAboveLabelTextSize | int | text size of TextView that rendered above progress bar |

### setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible) {#setRecognitionProcessAboveLabelTextVisible-boolean-}
```
public void setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)
```


Sets color of TextView that rendered above progress bar during recognition

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| recognitionProcessAboveLabelTextVisible | boolean | color of TextView that rendered above progress bar |

### setRecognitionProgressBarSize(int progressBarSize) {#setRecognitionProgressBarSize-int-}
```
public void setRecognitionProgressBarSize(int progressBarSize)
```


Sets size of progress bar that rendered during recognition

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| progressBarSize | int | size of progress bar |

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

