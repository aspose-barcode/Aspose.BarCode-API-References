---
title: BarcodeScannerPreferences
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: تفضيلات BarcodeScanner.
type: docs
weight: 16
url: /ar/androidjava/com.aspose.barcode.component.barcodescanner/barcodescannerpreferences/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class BarcodeScannerPreferences implements Parcelable
```

تفضيلات BarcodeScanner. تحتوي على معلمات تؤثر على عملية التعرف والبيانات التي تم التعرف عليها. BarcodeScannerPreferences تمتد من BarcodeRecognitionSettings، وتحتوي فئة BarcodeScannerPreferences على خصائص خاصة بواجهة برمجة تطبيقات BarcodeScanner وتنفذ واجهة Parcelable لتبادل التفضيلات بين نشاط العميل وBarcodeScannerActivity. تعمل BarcodeScannerPreferences فقط داخل تطبيق العميل عبر BarcodeScannerActivity
## الحقول

| حقل | الوصف |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeRecognitionSettings()](#getBarcodeRecognitionSettings--) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isRotationEnabled()](#isRotationEnabled--) | الحصول على تمكين دوران العرض. القيمة الافتراضية هي false |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setRotationEnabled(boolean rotationEnabled)](#setRotationEnabled-boolean-) | يضبط تمكين دوران العرض. يوصى باستخدام false |
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
| Parameter | Type | الوصف |
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


الحصول على تمكين دوران العرض. القيمة الافتراضية هي false

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


يضبط تمكين دوران العرض. يوصى باستخدام false

**Parameters:**
| Parameter | Type | الوصف |
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

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

