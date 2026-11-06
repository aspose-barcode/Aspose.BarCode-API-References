---
title: "BarcodeRecognitionContract"
second_title: "Aspose.BarCode for Android via Java API Reference"
description: "Internal BarcodeRecognitionContract は、クライアントアクティビティから BarcodeScannerActivity を呼び出す設定に必要です。"
type: docs
weight: 10
url: /ja/androidjava/com.aspose.barcode.component.barcodescanner/barcoderecognitioncontract/
---
**Inheritance:**
java.lang.Object, androidx.activity.result.contract.ActivityResultContract
```
public class BarcodeRecognitionContract extends ActivityResultContract<BarcodeScannerPreferences,BarcodeRecognitionResultsHandlerParcelable>
```

内部 BarcodeRecognitionContract 呼び出しの設定に必要 BarcodeScannerActivity クライアントアクティビティから
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BarcodeRecognitionContract()](#BarcodeRecognitionContract--) |  |
## メソッド

| メソッド | 説明 |
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
| パラメータ | 型 | 説明 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| コンテキスト | android.content.Context |  |
| barcodeScannerPreferences | com.aspose.barcode.component.barcodescanner.BarcodeScannerPreferences |  |

**Returns:**
android.content.Intent
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
| パラメータ | 型 | 説明 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resultCode | int |  |
| intent | android.content.Intent |  |

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

