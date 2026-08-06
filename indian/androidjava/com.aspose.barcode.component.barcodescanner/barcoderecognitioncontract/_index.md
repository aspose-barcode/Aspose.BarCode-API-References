---
title: BarcodeRecognitionContract
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: Internal BarcodeRecognitionContract u043du0443u0436u0435u043d u0434u043bu044f u043du0430u0441u0442u0440u043eu0439u043au0438 u0432u044bu0437u043eu0432u0430 BarcodeScannerActivity u0438u0437 u043au043bu0438u0435u043du0442u0441u043au043eu0439 u0430u043au0442u0438u0432u0438u0442u0438
type: docs
weight: 10
url: /hi/androidjava/com.aspose.barcode.component.barcodescanner/barcoderecognitioncontract/
---
**Inheritance:**
java.lang.Object, androidx.activity.result.contract.ActivityResultContract
```
public class BarcodeRecognitionContract extends ActivityResultContract<BarcodeScannerPreferences,BarcodeRecognitionResultsHandlerParcelable>
```

आंतरिक BarcodeRecognitionContract बारकोडस्कैनरएक्टिविटी को क्लाइंट एक्टिविटी से कॉल करने की सेटिंग के लिए आवश्यक है
## Constructors

| Constructor | विवरण |
| --- | --- |
| [BarcodeRecognitionContract()](#BarcodeRecognitionContract--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [createIntent(Context arg0, I arg1)](#createIntent-android.content.Context-I-) |  |
| [createIntent(Context context, BarcodeScannerPreferences barcodeScannerPreferences)](#createIntent-android.content.Context-com.aspose.barcode.component.barcodescanner.BarcodeScannerPreferences-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSynchronousResult(Context arg0, I arg1)](#getSynchronousResult-android.content.Context-I-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseResult(int resultCode, Intent intent)](#parseResult-int-android.content.Intent-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarcodeRecognitionContract() {#BarcodeRecognitionContract--}
```
public BarcodeRecognitionContract()
```


### createIntent(Context arg0, I arg1) {#createIntent-android.content.Context-I-}
```
public abstract Intent createIntent(Context arg0, I arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | android.content.Context |  |
| arg1 | I |  |

**Returns:**
android.content.Intent
### createIntent(Context context, BarcodeScannerPreferences barcodeScannerPreferences) {#createIntent-android.content.Context-com.aspose.barcode.component.barcodescanner.BarcodeScannerPreferences-}
```
public Intent createIntent(Context context, BarcodeScannerPreferences barcodeScannerPreferences)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| context | android.content.Context |  |
| barcodeScannerPreferences | com.aspose.barcode.component.barcodescanner.BarcodeScannerPreferences |  |

**Returns:**
android.content.Intent
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getSynchronousResult(Context arg0, I arg1) {#getSynchronousResult-android.content.Context-I-}
```
public ActivityResultContract.SynchronousResult<O> getSynchronousResult(Context arg0, I arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | android.content.Context |  |
| arg1 | I |  |

**Returns:**
androidx.activity.result.contract.ActivityResultContract.SynchronousResult<O>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parseResult(int resultCode, Intent intent) {#parseResult-int-android.content.Intent-}
```
public BarcodeRecognitionResultsHandlerParcelable parseResult(int resultCode, Intent intent)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| resultCode | int |  |
| इंटेंट | android.content.Intent |  |

**Returns:**
com.aspose.barcode.component.barcodescanner.BarcodeRecognitionResultsHandlerParcelable
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

