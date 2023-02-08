---
title: BarCodeReaderImplementation
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 14
url: /java/com.aspose.barcode.barcoderecognition.internal/barcodereaderimplementation/
---
**Inheritance:**
java.lang.Object
```
public class BarCodeReaderImplementation
```
## Constructors

| Constructor | Description |
| --- | --- |
| [BarCodeReaderImplementation()](#BarCodeReaderImplementation--) |  |
## Fields

| Field | Description |
| --- | --- |
| [BarcodeSettings](#BarcodeSettings) |  |
| [_bitmapImageExt](#-bitmapImageExt) |  |
| [_recognizedResults](#-recognizedResults) |  |
## Methods

| Method | Description |
| --- | --- |
| [callAbort()](#callAbort--) |  |
| [dispose(boolean disposing)](#dispose-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeReadType()](#getBarcodeReadType--) |  |
| [getClass()](#getClass--) |  |
| [getLicCheck()](#getLicCheck--) |  |
| [getQualitySettings()](#getQualitySettings--) |  |
| [getTimeout()](#getTimeout--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [read()](#read--) |  |
| [setBarCodeImage(System.Drawing.Bitmap value)](#setBarCodeImage-com.aspose.ms.System.Drawing.Bitmap-) |  |
| [setBarCodeImage(System.Drawing.Bitmap value, System.Drawing.Rectangle area)](#setBarCodeImage-com.aspose.ms.System.Drawing.Bitmap-com.aspose.ms.System.Drawing.Rectangle-) |  |
| [setBarCodeImage(System.Drawing.Bitmap value, System.Drawing.Rectangle[] areas)](#setBarCodeImage-com.aspose.ms.System.Drawing.Bitmap-com.aspose.ms.System.Drawing.Rectangle---) |  |
| [setBarcodeReadType(BaseDecodeType _readType)](#setBarcodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-) |  |
| [setQualitySettings(QualitySettings value)](#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-) |  |
| [setTimeout(int value)](#setTimeout-int-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeReaderImplementation() {#BarCodeReaderImplementation--}
```
public BarCodeReaderImplementation()
```


### BarcodeSettings {#BarcodeSettings}
```
public BarcodeSettings BarcodeSettings
```


### _bitmapImageExt {#-bitmapImageExt}
```
public BitmapImageSource _bitmapImageExt
```


### _recognizedResults {#-recognizedResults}
```
public BarCodeResult[] _recognizedResults
```


### callAbort() {#callAbort--}
```
public boolean callAbort()
```




**Returns:**
boolean
### dispose(boolean disposing) {#dispose-boolean-}
```
public void dispose(boolean disposing)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| disposing | boolean |  |

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
### getBarcodeReadType() {#getBarcodeReadType--}
```
public BaseDecodeType getBarcodeReadType()
```




**Returns:**
[BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLicCheck() {#getLicCheck--}
```
public ILicenseChecker getLicCheck()
```




**Returns:**
com.aspose.licensing.internal.ILicenseChecker
### getQualitySettings() {#getQualitySettings--}
```
public QualitySettings getQualitySettings()
```




**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getTimeout() {#getTimeout--}
```
public final int getTimeout()
```




**Returns:**
int
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




### read() {#read--}
```
public BarCodeResult[] read()
```




**Returns:**
com.aspose.barcode.barcoderecognition.BarCodeResult[]
### setBarCodeImage(System.Drawing.Bitmap value) {#setBarCodeImage-com.aspose.ms.System.Drawing.Bitmap-}
```
public void setBarCodeImage(System.Drawing.Bitmap value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Drawing.Bitmap |  |

### setBarCodeImage(System.Drawing.Bitmap value, System.Drawing.Rectangle area) {#setBarCodeImage-com.aspose.ms.System.Drawing.Bitmap-com.aspose.ms.System.Drawing.Rectangle-}
```
public void setBarCodeImage(System.Drawing.Bitmap value, System.Drawing.Rectangle area)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Drawing.Bitmap |  |
| area | com.aspose.ms.System.Drawing.Rectangle |  |

### setBarCodeImage(System.Drawing.Bitmap value, System.Drawing.Rectangle[] areas) {#setBarCodeImage-com.aspose.ms.System.Drawing.Bitmap-com.aspose.ms.System.Drawing.Rectangle---}
```
public void setBarCodeImage(System.Drawing.Bitmap value, System.Drawing.Rectangle[] areas)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Drawing.Bitmap |  |
| areas | com.aspose.ms.System.Drawing.Rectangle[] |  |

### setBarcodeReadType(BaseDecodeType _readType) {#setBarcodeReadType-com.aspose.barcode.barcoderecognition.BaseDecodeType-}
```
public void setBarcodeReadType(BaseDecodeType _readType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| _readType | [BaseDecodeType](../../com.aspose.barcode.barcoderecognition/basedecodetype) |  |

### setQualitySettings(QualitySettings value) {#setQualitySettings-com.aspose.barcode.barcoderecognition.QualitySettings-}
```
public void setQualitySettings(QualitySettings value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings) |  |

### setTimeout(int value) {#setTimeout-int-}
```
public final void setTimeout(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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
public final native void wait(long arg0)
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

