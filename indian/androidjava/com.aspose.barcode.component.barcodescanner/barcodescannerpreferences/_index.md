---
title: BarcodeScannerPreferences
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: BarcodeScanner की प्राथमिकताएँ।
type: docs
weight: 16
url: /hi/androidjava/com.aspose.barcode.component.barcodescanner/barcodescannerpreferences/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class BarcodeScannerPreferences implements Parcelable
```

BarcodeScanner प्राथमिकताएँ। इसमें ऐसे पैरामीटर होते हैं जो पहचान प्रक्रिया और पहचाने गए डेटा को प्रभावित करते हैं। BarcodeScannerPreferences, BarcodeRecognitionSettings को विस्तारित करता है, BarcodeScannerPreferences क्लास BarcodeScanner API के लिए विशिष्ट है और क्लाइंट एक्टिविटी और BarcodeScannerActivity के बीच प्राथमिकताओं का आदान‑प्रदान करने के लिए Parcelable इंटरफ़ेस को लागू करता है। BarcodeScannerPreferences केवल क्लाइंट एप्लिकेशन के भीतर BarcodeScannerActivity के माध्यम से काम करता है।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeRecognitionSettings()](#getBarcodeRecognitionSettings--) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isRotationEnabled()](#isRotationEnabled--) | डिस्प्ले रोटेशन सक्षम प्राप्त करता है, डिफ़ॉल्ट रूप से false है |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setRotationEnabled(boolean rotationEnabled)](#setRotationEnabled-boolean-) | डिस्प्ले रोटेशन सक्षम सेट करता है, अनुशंसित उपयोग false है |
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
| Parameter | Type | विवरण |
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


डिस्प्ले रोटेशन सक्षम प्राप्त करता है, डिफ़ॉल्ट रूप से false है

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


डिस्प्ले रोटेशन सक्षम सेट करता है, अनुशंसित उपयोग false है

**Parameters:**
| Parameter | Type | विवरण |
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

