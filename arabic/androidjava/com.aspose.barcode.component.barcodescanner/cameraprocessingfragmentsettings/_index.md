---
title: CameraProcessingFragmentSettings
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: إعدادات CameraProcessingFragment
type: docs
weight: 20
url: /ar/androidjava/com.aspose.barcode.component.barcodescanner/cameraprocessingfragmentsettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public class CameraProcessingFragmentSettings implements Parcelable
```

إعدادات CameraProcessingFragment
## الحقول

| حقل | الوصف |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraProcessingMode()](#getCameraProcessingMode--) | يحصل على وضع استخدام الكاميرا. |
| [getCameraResolution()](#getCameraResolution--) | يحصل على دقة الكاميرا الحالية. الافتراضي هو الحد الأدنى للدقة |
| [getClass()](#getClass--) |  |
| [getPreferencesButtonContentDescriptionText()](#getPreferencesButtonContentDescriptionText--) | يحصل على ContentDescriptionText الخاص بـ PreferencesButtonContent |
| [getRecognitionAreaSettings()](#getRecognitionAreaSettings--) | يحصل على الإعداد المتعلق بعلامة منطقة التعرف |
| [getRecognitionButtonContentDescriptionText()](#getRecognitionButtonContentDescriptionText--) | يحصل على ContentDescriptionText الخاص بـ RecognitionButton |
| [getRecognizeButtonSize()](#getRecognizeButtonSize--) | يحصل على حجم RecognizeButton |
| [getScannerPreferencesButtonSize()](#getScannerPreferencesButtonSize--) | يحصل على حجم PreferencesButton |
| [hashCode()](#hashCode--) |  |
| [isFlashEnabled()](#isFlashEnabled--) | يرجع true إذا كان الفلاش مفعلاً. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraProcessingMode(CameraMode cameraProcessingMode)](#setCameraProcessingMode-com.aspose.barcode.component.barcodescanner.CameraMode-) | TODO إضافة إلى الخصائص؟ يحدد وضع استخدام الكاميرا. |
| [setCameraResolution(Size cameraResolution)](#setCameraResolution-android.util.Size-) | يحدد دقة الكاميرا. الافتراضي هو الحد الأدنى للدقة |
| [setFlashEnabled(boolean flashEnabled)](#setFlashEnabled-boolean-) | يحدد تشغيل فلاش الضوء. مناسب فقط مع CameraMode.PHOTO. الافتراضي هو true |
| [setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)](#setPreferencesButtonContentDescriptionText-java.lang.String-) | يحدد ContentDescriptionText الخاص بـ PreferencesButtonContent |
| [setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)](#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-) | يحدد الإعداد المتعلق بعلامة منطقة التعرف |
| [setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)](#setRecognitionButtonContentDescriptionText-java.lang.String-) | يحدد ContentDescriptionText الخاص بـ RecognitionButton |
| [setRecognizeButtonSize(int recognizeImageButtonSize)](#setRecognizeButtonSize-int-) | يحدد حجم RecognizeButton |
| [setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)](#setScannerPreferencesButtonSize-int-) | يحدد حجم PreferencesButton |
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
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getCameraProcessingMode() {#getCameraProcessingMode--}
```
public CameraMode getCameraProcessingMode()
```


يحصل على وضع استخدام الكاميرا. يدعم الوضعان الحاليان = PHOTO و SNAPSHOT

**Returns:**
[CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) - mode of camera usage
### getCameraResolution() {#getCameraResolution--}
```
public Size getCameraResolution()
```


يحصل على دقة الكاميرا الحالية. الافتراضي هو الحد الأدنى للدقة

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


يحصل على ContentDescriptionText الخاص بـ PreferencesButtonContent

**Returns:**
java.lang.String - نص وصف المحتوى الخاص بـ PreferencesButtonContent
### getRecognitionAreaSettings() {#getRecognitionAreaSettings--}
```
public RecognitionAreaSettings getRecognitionAreaSettings()
```


يحصل على الإعداد المتعلق بعلامة منطقة التعرف

**Returns:**
com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings
### getRecognitionButtonContentDescriptionText() {#getRecognitionButtonContentDescriptionText--}
```
public String getRecognitionButtonContentDescriptionText()
```


يحصل على ContentDescriptionText الخاص بـ RecognitionButton

**Returns:**
java.lang.String - نص وصف المحتوى لزر التعرف
### getRecognizeButtonSize() {#getRecognizeButtonSize--}
```
public int getRecognizeButtonSize()
```


يحصل على حجم RecognizeButton

**Returns:**
int - حجم زر التعرف
### getScannerPreferencesButtonSize() {#getScannerPreferencesButtonSize--}
```
public int getScannerPreferencesButtonSize()
```


يحصل على حجم PreferencesButton

**Returns:**
int - حجم زر التفضيلات
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


يعيد true إذا كان الفلاش مفعلاً. مناسب فقط مع CameraMode.PHOTO. القيمة الافتراضية هي true

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


TODO إضافة إلى الخصائص؟ يحدد وضع استخدام الكاميرا. يدعم الوضعان الحاليان = PHOTO و SNAPSHOT

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| cameraProcessingMode | [CameraMode](../../com.aspose.barcode.component.barcodescanner/cameramode) |  |

### setCameraResolution(Size cameraResolution) {#setCameraResolution-android.util.Size-}
```
public void setCameraResolution(Size cameraResolution)
```


يحدد دقة الكاميرا. الافتراضي هو الحد الأدنى للدقة

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| cameraResolution | android.util.Size |  |

### setFlashEnabled(boolean flashEnabled) {#setFlashEnabled-boolean-}
```
public void setFlashEnabled(boolean flashEnabled)
```


يحدد تشغيل فلاش الضوء. مناسب فقط مع CameraMode.PHOTO. الافتراضي هو true

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| flashEnabled | boolean |  |

### setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText) {#setPreferencesButtonContentDescriptionText-java.lang.String-}
```
public void setPreferencesButtonContentDescriptionText(String preferencesButtonContentDescriptionText)
```


يحدد ContentDescriptionText الخاص بـ PreferencesButtonContent

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| preferencesButtonContentDescriptionText | java.lang.String | نص وصف المحتوى لزر تفضيلات المحتوى |

### setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings) {#setRecognitionAreaSettings-com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings-}
```
public void setRecognitionAreaSettings(RecognitionAreaSettings recognitionAreaSettings)
```


يحدد الإعداد المتعلق بعلامة منطقة التعرف

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| recognitionAreaSettings | com.aspose.barcode.component.barcodescanner.RecognitionAreaSettings |  |

### setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText) {#setRecognitionButtonContentDescriptionText-java.lang.String-}
```
public void setRecognitionButtonContentDescriptionText(String recognitionButtonContentDescriptionText)
```


يحدد ContentDescriptionText الخاص بـ RecognitionButton

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| recognitionButtonContentDescriptionText | java.lang.String | نص وصف المحتوى لزر التعرف |

### setRecognizeButtonSize(int recognizeImageButtonSize) {#setRecognizeButtonSize-int-}
```
public void setRecognizeButtonSize(int recognizeImageButtonSize)
```


يحدد حجم RecognizeButton

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| recognizeImageButtonSize | int | حجم زر التعرف |

### setScannerPreferencesButtonSize(int scannerPreferencesButtonSize) {#setScannerPreferencesButtonSize-int-}
```
public void setScannerPreferencesButtonSize(int scannerPreferencesButtonSize)
```


يحدد حجم PreferencesButton

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| scannerPreferencesButtonSize | int | حجم زر التفضيلات |

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeToParcel(Parcel parcel, int i) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel parcel, int i)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| parcel | android.os.Parcel |  |
| i | int |  |

