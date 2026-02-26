---
title: QRExtendedParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Stores a QR Structured Append information of recognized barcode
type: docs
weight: 42
url: /androidjava/com.aspose.barcode.barcoderecognition/qrextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class QRExtendedParameters extends BaseExtendedParameters
```

Stores a QR Structured Append information of recognized barcode

This sample shows how to get QR Structured Append data

```
{
```
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) value. |
| [getClass()](#getClass--) |  |
| [getErrorLevel()](#getErrorLevel--) | Reed-Solomon error correction level of recognized barcode. |
| [getMicroQRVersion()](#getMicroQRVersion--) | Version of recognized MicroQR Code. |
| [getQRErrorLevel()](#getQRErrorLevel--) | Reed-Solomon error correction level of recognized barcode. |
| [getQRStructuredAppendModeBarCodeIndex()](#getQRStructuredAppendModeBarCodeIndex--) | Gets the index of the QR structured append mode barcode. |
| [getQRStructuredAppendModeBarCodesQuantity()](#getQRStructuredAppendModeBarCodesQuantity--) | Gets the QR structured append mode barcodes quantity. |
| [getQRStructuredAppendModeParityData()](#getQRStructuredAppendModeParityData--) | Gets the QR structured append mode parity data. |
| [getQRVersion()](#getQRVersion--) | Version of recognized QR Code. |
| [getRectMicroQRVersion()](#getRectMicroQRVersion--) | Version of recognized RectMicroQR Code. |
| [getStructuredAppendModeBarCodeIndex()](#getStructuredAppendModeBarCodeIndex--) | Gets the index of the QR structured append mode barcode. |
| [getStructuredAppendModeBarCodesQuantity()](#getStructuredAppendModeBarCodesQuantity--) | Gets the QR structured append mode barcodes quantity. |
| [getStructuredAppendModeParityData()](#getStructuredAppendModeParityData--) | Gets the QR structured append mode parity data. |
| [getVersion()](#getVersion--) | Version of recognized QR Code. |
| [hashCode()](#hashCode--) | Returns the hash code for this instance. |
| [isEmpty()](#isEmpty--) | Tests whether all parameters has only default values |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(QRExtendedParameters first, QRExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Returns a value indicating whether the first [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) value is equal to the second. |
| [op_Inequality(QRExtendedParameters first, QRExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-) | Returns a value indicating if the first [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) value is different from the second. |
| [toString()](#toString--) | Returns a human-readable string representation of this [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns a value indicating whether this instance is equal to a specified [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) value.

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
### getErrorLevel() {#getErrorLevel--}
```
public final QRErrorLevel getErrorLevel()
```


Reed-Solomon error correction level of recognized barcode. From low to high: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getMicroQRVersion() {#getMicroQRVersion--}
```
public final MicroQRVersion getMicroQRVersion()
```


Version of recognized MicroQR Code. From M1 to M4.

**Returns:**
[MicroQRVersion](../../com.aspose.barcode.generation/microqrversion)
### getQRErrorLevel() {#getQRErrorLevel--}
```
public final QRErrorLevel getQRErrorLevel()
```


Reed-Solomon error correction level of recognized barcode. From low to high: LevelL, LevelM, LevelQ, LevelH.

**Returns:**
[QRErrorLevel](../../com.aspose.barcode.generation/qrerrorlevel)
### getQRStructuredAppendModeBarCodeIndex() {#getQRStructuredAppendModeBarCodeIndex--}
```
public final int getQRStructuredAppendModeBarCodeIndex()
```


Gets the index of the QR structured append mode barcode. Index starts from 0. Default value is -1.

Value: The quantity of the QR structured append mode barcode.

**Returns:**
int - the index of the QR structured append mode barcode.
### getQRStructuredAppendModeBarCodesQuantity() {#getQRStructuredAppendModeBarCodesQuantity--}
```
public final int getQRStructuredAppendModeBarCodesQuantity()
```


Gets the QR structured append mode barcodes quantity. Default value is -1.

Value: The quantity of the QR structured append mode barcode.

**Returns:**
int - the QR structured append mode barcodes quantity.
### getQRStructuredAppendModeParityData() {#getQRStructuredAppendModeParityData--}
```
public final int getQRStructuredAppendModeParityData()
```


Gets the QR structured append mode parity data. Default value is -1.

Value: The index of the QR structured append mode barcode.

**Returns:**
int - the QR structured append mode parity data.
### getQRVersion() {#getQRVersion--}
```
public final QRVersion getQRVersion()
```


Version of recognized QR Code. From Version1 to Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
### getRectMicroQRVersion() {#getRectMicroQRVersion--}
```
public final RectMicroQRVersion getRectMicroQRVersion()
```


Version of recognized RectMicroQR Code. From R7x43 to R17x139.

**Returns:**
[RectMicroQRVersion](../../com.aspose.barcode.generation/rectmicroqrversion)
### getStructuredAppendModeBarCodeIndex() {#getStructuredAppendModeBarCodeIndex--}
```
public final int getStructuredAppendModeBarCodeIndex()
```


Gets the index of the QR structured append mode barcode. Index starts from 0. Default value is -1.

Value: The quantity of the QR structured append mode barcode.

**Returns:**
int - the index of the QR structured append mode barcode.
### getStructuredAppendModeBarCodesQuantity() {#getStructuredAppendModeBarCodesQuantity--}
```
public final int getStructuredAppendModeBarCodesQuantity()
```


Gets the QR structured append mode barcodes quantity. Default value is -1.

Value: The quantity of the QR structured append mode barcode.

**Returns:**
int - the QR structured append mode barcodes quantity.
### getStructuredAppendModeParityData() {#getStructuredAppendModeParityData--}
```
public final int getStructuredAppendModeParityData()
```


Gets the QR structured append mode parity data. Default value is -1.

Value: The index of the QR structured append mode barcode.

**Returns:**
int - the QR structured append mode parity data.
### getVersion() {#getVersion--}
```
public final QRVersion getVersion()
```


Version of recognized QR Code. From Version1 to Version40.

**Returns:**
[QRVersion](../../com.aspose.barcode.generation/qrversion)
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




### op_Equality(QRExtendedParameters first, QRExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Equality(QRExtendedParameters first, QRExtendedParameters second)
```


Returns a value indicating whether the first [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) value is equal to the second.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | A first compared value |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | A second compared value |

**Returns:**
boolean -  **true**  if first has the same value as second; otherwise,  **false** .
### op_Inequality(QRExtendedParameters first, QRExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.QRExtendedParameters-com.aspose.barcode.barcoderecognition.QRExtendedParameters-}
```
public static boolean op_Inequality(QRExtendedParameters first, QRExtendedParameters second)
```


Returns a value indicating if the first [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) value is different from the second.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | A first compared value |
| second | [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters) | A second compared value |

**Returns:**
boolean -  **true**  if first has the different value from second; otherwise,  **false** .
### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).

**Returns:**
java.lang.String - A string that represents this [QRExtendedParameters](../../com.aspose.barcode.barcoderecognition/qrextendedparameters).
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

