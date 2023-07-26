---
title: QRExtendedParameters
second_title: Aspose.BarCode for Java API Reference
description: Stores a QR Structured Append information of recognized barcode
type: docs
weight: 34
url: /java/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Stores a QR Structured Append information of recognized barcode

--------------------

> ```
> This sample shows how to get QR Structured Append data
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.QR);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode Type: " + result.getCodeTypeName());
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
>     System.out.println("QR Structured Append Index: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodeIndex());
>     System.out.println("QR Structured Append ParityData: " + result.getExtended().getQR().getQRStructuredAppendModeParityData());
>  }
> ```
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified  QRExtendedParameters  value. |
| [getClass()](#getClass--) |  |
| [getQRStructuredAppendModeBarCodeIndex()](#getQRStructuredAppendModeBarCodeIndex--) | Gets the index of the QR structured append mode barcode. |
| [getQRStructuredAppendModeBarCodesQuantity()](#getQRStructuredAppendModeBarCodesQuantity--) | Gets the QR structured append mode barcodes quantity. |
| [getQRStructuredAppendModeParityData()](#getQRStructuredAppendModeParityData--) | Gets the QR structured append mode parity data. |
| [hashCode()](#hashCode--) | Returns the hash code for this instance. |
| [isEmpty()](#isEmpty--) | Tests whether all parameters has only default values |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returns a human-readable string representation of this  QRExtendedParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns a value indicating whether this instance is equal to a specified  QRExtendedParameters  value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | An System.Object value to compare to this instance. |

**Returns:**
boolean -  **true**  if obj has the same value as this instance; otherwise,  **false** .
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


Gets the index of the QR structured append mode barcode. Index starts from 0. Default value is -1.

Value: The quantity of the QR structured append mode barcode.

**Returns:**
int
### getQRStructuredAppendModeBarCodesQuantity() {#getQRStructuredAppendModeBarCodesQuantity--}
```
public int getQRStructuredAppendModeBarCodesQuantity()
```


Gets the QR structured append mode barcodes quantity. Default value is -1.

Value: The quantity of the QR structured append mode barcode.

**Returns:**
int
### getQRStructuredAppendModeParityData() {#getQRStructuredAppendModeParityData--}
```
public int getQRStructuredAppendModeParityData()
```


Gets the QR structured append mode parity data. Default value is -1.

Value: The index of the QR structured append mode barcode.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code for this instance.

**Returns:**
int - A 32-bit signed integer hash code.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Tests whether all parameters has only default values

Value: Returns  **true**  if all parameters has only default values; otherwise,  **false** .

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




### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this  QRExtendedParameters .

**Returns:**
java.lang.String - A string that represents this  QRExtendedParameters .
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

