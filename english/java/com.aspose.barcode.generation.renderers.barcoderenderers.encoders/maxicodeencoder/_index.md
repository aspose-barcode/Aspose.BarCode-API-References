---
title: MaxiCodeEncoder
second_title: Aspose.BarCode for Java API Reference
description: Contains functions for encoding MaxiCode
type: docs
weight: 67
url: /java/com.aspose.barcode.generation.renderers.barcoderenderers.encoders/maxicodeencoder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.renderers.barcoderenderers.encoders.BarCodeEncoder](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders/barcodeencoder)
```
public class MaxiCodeEncoder extends BarCodeEncoder
```

Contains functions for encoding MaxiCode
## Constructors

| Constructor | Description |
| --- | --- |
| [MaxiCodeEncoder(MaxiCodeEncoderParameters parameters)](#MaxiCodeEncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.MaxiCodeEncoderParameters-) |  |
## Methods

| Method | Description |
| --- | --- |
| [encode(String str)](#encode-java.lang.String-) |  |
| [encodeBytes(String str, List<Integer> dataCodeWords)](#encodeBytes-java.lang.String-java.util.List-java.lang.Integer--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChecksum()](#getChecksum--) |  |
| [getClass()](#getClass--) |  |
| [getEnableChecksum()](#getEnableChecksum--) |  |
| [getHumanReadableCodeText()](#getHumanReadableCodeText--) |  |
| [getHumanReadableCodeText_Rename_Namesake()](#getHumanReadableCodeText-Rename-Namesake--) |  |
| [getParameters()](#getParameters--) |  |
| [getSixBitsSequence(List<Integer> codewords)](#getSixBitsSequence-java.util.List-java.lang.Integer--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeEncoder(MaxiCodeEncoderParameters parameters) {#MaxiCodeEncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.MaxiCodeEncoderParameters-}
```
public MaxiCodeEncoder(MaxiCodeEncoderParameters parameters)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parameters | [MaxiCodeEncoderParameters](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters/maxicodeencoderparameters) |  |

### encode(String str) {#encode-java.lang.String-}
```
public String encode(String str)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |

**Returns:**
java.lang.String
### encodeBytes(String str, List<Integer> dataCodeWords) {#encodeBytes-java.lang.String-java.util.List-java.lang.Integer--}
```
public int encodeBytes(String str, List<Integer> dataCodeWords)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String |  |
| dataCodeWords | java.util.List<java.lang.Integer> |  |

**Returns:**
int
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
### getChecksum() {#getChecksum--}
```
public String getChecksum()
```




**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnableChecksum() {#getEnableChecksum--}
```
public EnableChecksum getEnableChecksum()
```




**Returns:**
[EnableChecksum](../../com.aspose.barcode.generation/enablechecksum)
### getHumanReadableCodeText() {#getHumanReadableCodeText--}
```
public String getHumanReadableCodeText()
```




**Returns:**
java.lang.String
### getHumanReadableCodeText_Rename_Namesake() {#getHumanReadableCodeText-Rename-Namesake--}
```
public String getHumanReadableCodeText_Rename_Namesake()
```




**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public EncoderParameters getParameters()
```




**Returns:**
[EncoderParameters](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters/encoderparameters)
### getSixBitsSequence(List<Integer> codewords) {#getSixBitsSequence-java.util.List-java.lang.Integer--}
```
public static byte[] getSixBitsSequence(List<Integer> codewords)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codewords | java.util.List<java.lang.Integer> |  |

**Returns:**
byte[]
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

