---
title: StructuredAppendStateHandler
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 19
url: /java/com.aspose.barcode.barcoderecognition.recognition.qr.statehandler/structuredappendstatehandler/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.barcoderecognition.recognition.qr.statehandler.IStateHandlerCallback](../../com.aspose.barcode.barcoderecognition.recognition.qr.statehandler/istatehandlercallback)
```
public class StructuredAppendStateHandler implements IStateHandlerCallback
```
## Constructors

| Constructor | Description |
| --- | --- |
| [StructuredAppendStateHandler()](#StructuredAppendStateHandler--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getQRStructuredAppendModeBarCodeIndex()](#getQRStructuredAppendModeBarCodeIndex--) |  |
| [getQRStructuredAppendModeBarCodesQuantity()](#getQRStructuredAppendModeBarCodesQuantity--) |  |
| [getQRStructuredAppendModeParityData()](#getQRStructuredAppendModeParityData--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [stateHandler(ExtBitStream stream, QRDecodingStack output, int version, boolean isQR)](#stateHandler-com.aspose.barcode.barcoderecognition.common.ExtBitStream-com.aspose.barcode.barcoderecognition.recognition.qr.statehandler.QRDecodingStack-int-boolean-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StructuredAppendStateHandler() {#StructuredAppendStateHandler--}
```
public StructuredAppendStateHandler()
```


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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getQRStructuredAppendModeBarCodeIndex() {#getQRStructuredAppendModeBarCodeIndex--}
```
public int getQRStructuredAppendModeBarCodeIndex()
```




**Returns:**
int
### getQRStructuredAppendModeBarCodesQuantity() {#getQRStructuredAppendModeBarCodesQuantity--}
```
public int getQRStructuredAppendModeBarCodesQuantity()
```




**Returns:**
int
### getQRStructuredAppendModeParityData() {#getQRStructuredAppendModeParityData--}
```
public int getQRStructuredAppendModeParityData()
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




### stateHandler(ExtBitStream stream, QRDecodingStack output, int version, boolean isQR) {#stateHandler-com.aspose.barcode.barcoderecognition.common.ExtBitStream-com.aspose.barcode.barcoderecognition.recognition.qr.statehandler.QRDecodingStack-int-boolean-}
```
public int stateHandler(ExtBitStream stream, QRDecodingStack output, int version, boolean isQR)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | [ExtBitStream](../../com.aspose.barcode.barcoderecognition.common/extbitstream) |  |
| output | [QRDecodingStack](../../com.aspose.barcode.barcoderecognition.recognition.qr.statehandler/qrdecodingstack) |  |
| version | int |  |
| isQR | boolean |  |

**Returns:**
int
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
