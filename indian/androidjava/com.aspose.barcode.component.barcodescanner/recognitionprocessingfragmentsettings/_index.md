---
title: RecognitionProcessingFragmentSettings
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: 
type: docs
weight: 27
url: /hi/androidjava/com.aspose.barcode.component.barcodescanner/recognitionprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class RecognitionProcessingFragmentSettings implements Parcelable
```
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundDuringRecognitionProcess()](#getBackgroundDuringRecognitionProcess--) | पहचान प्रक्रिया के दौरान रेंडर किया जाने वाला बैकग्राउंड प्राप्त करता है |
| [getClass()](#getClass--) |  |
| [getProgressBarColor()](#getProgressBarColor--) | पहचान के दौरान रेंडर किए गए प्रोग्रेस बार का रंग प्राप्त करता है |
| [getProgressBarSize()](#getProgressBarSize--) | पहचान के दौरान रेंडर किए गए प्रोग्रेस बार का आकार प्राप्त करता है |
| [getRecognitionCancelButtonRightOffset()](#getRecognitionCancelButtonRightOffset--) | पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन की दाएँ सीमा से ऑफसेट प्राप्त करता है |
| [getRecognitionCancelButtonText()](#getRecognitionCancelButtonText--) | पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन का टेक्स्ट प्राप्त करता है |
| [getRecognitionCancelButtonTextColor()](#getRecognitionCancelButtonTextColor--) | पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन का रंग प्राप्त करता है |
| [getRecognitionCancelButtonTextSize()](#getRecognitionCancelButtonTextSize--) | पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन का टेक्स्ट आकार प्राप्त करता है |
| [getRecognitionCancelButtonVisibility()](#getRecognitionCancelButtonVisibility--) | पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन की दृश्यता प्राप्त करता है |
| [getRecognitionProcessAboveLabelText()](#getRecognitionProcessAboveLabelText--) | पहचान के दौरान प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का टेक्स्ट प्राप्त करता है |
| [getRecognitionProcessAboveLabelTextColor()](#getRecognitionProcessAboveLabelTextColor--) | पहचान के दौरान प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का रंग प्राप्त करता है |
| [getRecognitionProcessAboveLabelTextSize()](#getRecognitionProcessAboveLabelTextSize--) | पहचान के दौरान प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का टेक्स्ट आकार प्राप्त करता है |
| [getRecognitionProcessAboveLabelTextVisible()](#getRecognitionProcessAboveLabelTextVisible--) | पहचान के दौरान प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का रंग प्राप्त करता है |
| [hashCode()](#hashCode--) |  |
| [importSettings(RecognitionProcessingFragmentSettings recognitionProcessingFragmentSettings)](#importSettings-com.aspose.barcode.component.barcodescanner.RecognitionProcessingFragmentSettings-) | सेटिंग्स आयात करता है |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundImageDuringRecognitionProcess(RecognitionProcessFragmentBackground backgroundImage)](#setBackgroundImageDuringRecognitionProcess-com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground-) | पहचान प्रक्रिया के दौरान रेंडर किया जाने वाला बैकग्राउंड सेट करता है |
| [setProgressBarColor(int progressBarColor)](#setProgressBarColor-int-) | पहचान के दौरान रेंडर किए गए प्रोग्रेस बार का रंग सेट करता है |
| [setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)](#setRecognitionCancelButtonRightOffset-int-) | पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन की दाएँ सीमा से ऑफसेट सेट करता है |
| [setRecognitionCancelButtonText(String recognitionCancelButtonText)](#setRecognitionCancelButtonText-java.lang.String-) | पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन का टेक्स्ट सेट करता है |
| [setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)](#setRecognitionCancelButtonTextColor-int-) | पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन का रंग सेट करता है |
| [setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)](#setRecognitionCancelButtonTextSize-float-) | पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन का टेक्स्ट आकार सेट करता है |
| [setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)](#setRecognitionCancelButtonVisibility-boolean-) | पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन की दृश्यता सेट करता है |
| [setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)](#setRecognitionProcessAboveLabelText-java.lang.String-) | पहचान के दौरान प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का टेक्स्ट सेट करता है |
| [setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)](#setRecognitionProcessAboveLabelTextColor-int-) | पहचान के दौरान प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का रंग सेट करता है |
| [setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)](#setRecognitionProcessAboveLabelTextSize-int-) | पहचान के दौरान प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का टेक्स्ट आकार सेट करता है |
| [setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)](#setRecognitionProcessAboveLabelTextVisible-boolean-) | पहचान के दौरान प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का रंग सेट करता है |
| [setRecognitionProgressBarSize(int progressBarSize)](#setRecognitionProgressBarSize-int-) | पहचान के दौरान रेंडर किए गए प्रोग्रेस बार का आकार सेट करता है |
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBackgroundDuringRecognitionProcess() {#getBackgroundDuringRecognitionProcess--}
```
public RecognitionProcessFragmentBackground getBackgroundDuringRecognitionProcess()
```


पहचान प्रक्रिया के दौरान रेंडर किया जाने वाला बैकग्राउंड प्राप्त करता है

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground - पहचान प्रक्रिया के दौरान रेंडर किया जाने वाला बैकग्राउंड
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


पहचान के दौरान रेंडर किए गए प्रोग्रेस बार का रंग प्राप्त करता है

**Returns:**
int - प्रोग्रेस बार का रंग
### getProgressBarSize() {#getProgressBarSize--}
```
public int getProgressBarSize()
```


पहचान के दौरान रेंडर किए गए प्रोग्रेस बार का आकार प्राप्त करता है

**Returns:**
int - प्रोग्रेस बार का आकार
### getRecognitionCancelButtonRightOffset() {#getRecognitionCancelButtonRightOffset--}
```
public int getRecognitionCancelButtonRightOffset()
```


पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन की दाएँ सीमा से ऑफसेट प्राप्त करता है

**Returns:**
int - "Cancel" बटन की दाएँ सीमा से ऑफसेट
### getRecognitionCancelButtonText() {#getRecognitionCancelButtonText--}
```
public String getRecognitionCancelButtonText()
```


पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन का टेक्स्ट प्राप्त करता है

**Returns:**
java.lang.String - प्रोग्रेस बार के नीचे प्रदर्शित "Cancel" बटन का टेक्स्ट
### getRecognitionCancelButtonTextColor() {#getRecognitionCancelButtonTextColor--}
```
public int getRecognitionCancelButtonTextColor()
```


पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन का रंग प्राप्त करता है

**Returns:**
int - प्रोग्रेस बार के नीचे प्रदर्शित "Cancel" बटन का रंग
### getRecognitionCancelButtonTextSize() {#getRecognitionCancelButtonTextSize--}
```
public float getRecognitionCancelButtonTextSize()
```


पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन का टेक्स्ट आकार प्राप्त करता है

**Returns:**
float - प्रोग्रेस के नीचे प्रदर्शित "Cancel" बटन के टेक्स्ट का आकार
### getRecognitionCancelButtonVisibility() {#getRecognitionCancelButtonVisibility--}
```
public boolean getRecognitionCancelButtonVisibility()
```


पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन की दृश्यता प्राप्त करता है

**Returns:**
boolean - "Cancel" बटन की दृश्यता
### getRecognitionProcessAboveLabelText() {#getRecognitionProcessAboveLabelText--}
```
public String getRecognitionProcessAboveLabelText()
```


पहचान के दौरान प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का टेक्स्ट प्राप्त करता है

**Returns:**
java.lang.String - प्रोग्रेस बार के ऊपर प्रदर्शित TextView का टेक्स्ट
### getRecognitionProcessAboveLabelTextColor() {#getRecognitionProcessAboveLabelTextColor--}
```
public int getRecognitionProcessAboveLabelTextColor()
```


पहचान के दौरान प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का रंग प्राप्त करता है

**Returns:**
int - प्रोग्रेस बार के ऊपर प्रदर्शित TextView का रंग
### getRecognitionProcessAboveLabelTextSize() {#getRecognitionProcessAboveLabelTextSize--}
```
public float getRecognitionProcessAboveLabelTextSize()
```


पहचान के दौरान प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का टेक्स्ट आकार प्राप्त करता है

**Returns:**
float - प्रोग्रेस बार के ऊपर प्रदर्शित TextView के टेक्स्ट का आकार
### getRecognitionProcessAboveLabelTextVisible() {#getRecognitionProcessAboveLabelTextVisible--}
```
public boolean getRecognitionProcessAboveLabelTextVisible()
```


पहचान के दौरान प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का रंग प्राप्त करता है

**Returns:**
boolean - प्रोग्रेस बार के ऊपर प्रदर्शित TextView का रंग
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


सेटिंग्स आयात करता है

**Parameters:**
| Parameter | Type | विवरण |
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


पहचान प्रक्रिया के दौरान रेंडर किया जाने वाला बैकग्राउंड सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| backgroundImage | com.aspose.barcode.component.barcodescanner.RecognitionProcessFragmentBackground | पहचान प्रक्रिया के दौरान प्रदर्शित होने वाली पृष्ठभूमि |

### setProgressBarColor(int progressBarColor) {#setProgressBarColor-int-}
```
public void setProgressBarColor(int progressBarColor)
```


पहचान के दौरान रेंडर किए गए प्रोग्रेस बार का रंग सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| progressBarColor | int | प्रोग्रेस बार का रंग |

### setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset) {#setRecognitionCancelButtonRightOffset-int-}
```
public void setRecognitionCancelButtonRightOffset(int recognitionCancelButtonRightOffset)
```


पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन की दाएँ सीमा से ऑफसेट सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| recognitionCancelButtonRightOffset | int | "Cancel" बटन की दाएँ सीमा से ऑफसेट |

### setRecognitionCancelButtonText(String recognitionCancelButtonText) {#setRecognitionCancelButtonText-java.lang.String-}
```
public void setRecognitionCancelButtonText(String recognitionCancelButtonText)
```


पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन का टेक्स्ट सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| recognitionCancelButtonText | java.lang.String | "Cancel" बटन का टेक्स्ट जो प्रोग्रेस बार के नीचे प्रदर्शित होता है |

### setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor) {#setRecognitionCancelButtonTextColor-int-}
```
public void setRecognitionCancelButtonTextColor(int recognitionCancelButtonTextColor)
```


पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन का रंग सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| recognitionCancelButtonTextColor | int | "Cancel" बटन का रंग जो प्रोग्रेस बार के नीचे प्रदर्शित होता है |

### setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize) {#setRecognitionCancelButtonTextSize-float-}
```
public void setRecognitionCancelButtonTextSize(float recognitionCancelButtonTextSize)
```


पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन का टेक्स्ट आकार सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| recognitionCancelButtonTextSize | float | प्रोग्रेस के नीचे रेंडर किए गए "Cancel" बटन का टेक्स्ट आकार |

### setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible) {#setRecognitionCancelButtonVisibility-boolean-}
```
public void setRecognitionCancelButtonVisibility(boolean recognitionCancelButtonVisible)
```


पहचान के दौरान प्रोग्रेस बार के नीचे रेंडर किए गए "Cancel" बटन की दृश्यता सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| recognitionCancelButtonVisible | boolean | "Cancel" बटन की दृश्यता |

### setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText) {#setRecognitionProcessAboveLabelText-java.lang.String-}
```
public void setRecognitionProcessAboveLabelText(String recognitionProcessAboveLabelText)
```


पहचान के दौरान प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का टेक्स्ट सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| recognitionProcessAboveLabelText | java.lang.String | प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का टेक्स्ट |

### setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor) {#setRecognitionProcessAboveLabelTextColor-int-}
```
public void setRecognitionProcessAboveLabelTextColor(int recognitionProcessAboveLabelTextColor)
```


पहचान के दौरान प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का रंग सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| recognitionProcessAboveLabelTextColor | int | प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का रंग |

### setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize) {#setRecognitionProcessAboveLabelTextSize-int-}
```
public void setRecognitionProcessAboveLabelTextSize(int recognitionAboveLabelTextSize)
```


पहचान के दौरान प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का टेक्स्ट आकार सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| recognitionAboveLabelTextSize | int | प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का टेक्स्ट आकार |

### setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible) {#setRecognitionProcessAboveLabelTextVisible-boolean-}
```
public void setRecognitionProcessAboveLabelTextVisible(boolean recognitionProcessAboveLabelTextVisible)
```


पहचान के दौरान प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का रंग सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| recognitionProcessAboveLabelTextVisible | boolean | प्रोग्रेस बार के ऊपर रेंडर किए गए TextView का रंग |

### setRecognitionProgressBarSize(int progressBarSize) {#setRecognitionProgressBarSize-int-}
```
public void setRecognitionProgressBarSize(int progressBarSize)
```


पहचान के दौरान रेंडर किए गए प्रोग्रेस बार का आकार सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| progressBarSize | int | प्रोग्रेस बार का आकार |

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |
| arg1 | int |  |

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

