---
title: DotCodeExtendedParameters
second_title: Aspose.BarCode for Android via Java API Reference
description: Stores special data of DotCode recognized barcode
type: docs
weight: 33
url: /androidjava/com.aspose.barcode.barcoderecognition/dotcodeextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DotCodeExtendedParameters extends BaseExtendedParameters
```

Stores special data of DotCode recognized barcode

This sample shows how to get DotCode raw values

```

 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, "12345");
 generator.save("c:\\test.png");

 BarCodeReader reader = new BarCodeReader(@"c:\\test.png", DecodeType.DOT_CODE);
 for (BarCodeResult result : reader.readBarCodes()
 {
      System.out.println("BarCode type: " + result.getCodeTypeName());
      System.out.println("BarCode codetext: " + result.getCodeText());
      System.out.println("DotCode barcode ID: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodeId());
      System.out.println("DotCode barcodes count: " + result.getExtended().getDotCode().getDotCodeStructuredAppendModeBarcodesCount());
 }
 
```
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Returns a value indicating whether this instance is equal to a specified [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) value. |
| [getClass()](#getClass--) |  |
| [getDotCodeIsReaderInitialization()](#getDotCodeIsReaderInitialization--) | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. |
| [getDotCodeStructuredAppendModeBarcodeId()](#getDotCodeStructuredAppendModeBarcodeId--) | Gets the ID of the DotCode structured append mode barcode. |
| [getDotCodeStructuredAppendModeBarcodesCount()](#getDotCodeStructuredAppendModeBarcodesCount--) | Gets the DotCode structured append mode barcodes count. |
| [getStructuredAppendModeBarcodeId()](#getStructuredAppendModeBarcodeId--) | Gets the ID of the DotCode structured append mode barcode. |
| [getStructuredAppendModeBarcodesCount()](#getStructuredAppendModeBarcodesCount--) | Gets the DotCode structured append mode barcodes count. |
| [hashCode()](#hashCode--) | Returns the hash code for this instance. |
| [isEmpty()](#isEmpty--) | Tests whether all parameters has only default values |
| [isReaderInitialization()](#isReaderInitialization--) | Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)](#op-Equality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-) | Returns a value indicating whether the first [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) value is equal to the second. |
| [op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)](#op-Inequality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-) | Returns a value indicating if the first [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) value is different from the second. |
| [toString()](#toString--) | Returns a human-readable string representation of this [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Returns a value indicating whether this instance is equal to a specified [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) value.

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
### getDotCodeIsReaderInitialization() {#getDotCodeIsReaderInitialization--}
```
public final boolean getDotCodeIsReaderInitialization()
```


Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false.

**Returns:**
boolean
### getDotCodeStructuredAppendModeBarcodeId() {#getDotCodeStructuredAppendModeBarcodeId--}
```
public final int getDotCodeStructuredAppendModeBarcodeId()
```


Gets the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1.

Value: The ID of the DotCode structured append mode barcode.

**Returns:**
int - the ID of the DotCode structured append mode barcode.
### getDotCodeStructuredAppendModeBarcodesCount() {#getDotCodeStructuredAppendModeBarcodesCount--}
```
public final int getDotCodeStructuredAppendModeBarcodesCount()
```


Gets the DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35.

Value: The count of the DotCode structured append mode barcode.

**Returns:**
int - the DotCode structured append mode barcodes count.
### getStructuredAppendModeBarcodeId() {#getStructuredAppendModeBarcodeId--}
```
public final int getStructuredAppendModeBarcodeId()
```


Gets the ID of the DotCode structured append mode barcode. ID starts from 1 and must be less or equal to barcodes count. Default value is -1.

Value: The ID of the DotCode structured append mode barcode.

**Returns:**
int - the ID of the DotCode structured append mode barcode.
### getStructuredAppendModeBarcodesCount() {#getStructuredAppendModeBarcodesCount--}
```
public final int getStructuredAppendModeBarcodesCount()
```


Gets the DotCode structured append mode barcodes count. Default value is -1. Count must be a value from 1 to 35.

Value: The count of the DotCode structured append mode barcode.

**Returns:**
int - the DotCode structured append mode barcodes count.
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
### isReaderInitialization() {#isReaderInitialization--}
```
public final boolean isReaderInitialization()
```


Indicates whether code is used for instruct reader to interpret the following data as instructions for initialization or reprogramming of the bar code reader. Default value is false.

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




### op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second) {#op-Equality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-}
```
public static boolean op_Equality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)
```


Returns a value indicating whether the first [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) value is equal to the second.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | A first compared value |
| second | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | A second compared value |

**Returns:**
boolean -  **true**  if first has the same value as second; otherwise,  **false** .
### op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second) {#op-Inequality-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-com.aspose.barcode.barcoderecognition.DotCodeExtendedParameters-}
```
public static boolean op_Inequality(DotCodeExtendedParameters first, DotCodeExtendedParameters second)
```


Returns a value indicating if the first [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) value is different from the second.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| first | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | A first compared value |
| second | [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | A second compared value |

**Returns:**
boolean -  **true**  if first has the different value from second; otherwise,  **false** .
### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).

**Returns:**
java.lang.String - A string that represents this [DotCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters).
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

