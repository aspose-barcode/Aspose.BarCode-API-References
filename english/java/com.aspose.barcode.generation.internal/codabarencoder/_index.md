---
title: CodabarEncoder
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.aspose.barcode.generation.internal/codabarencoder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.renderers.barcoderenderers.encoders.BarCodeEncoder](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders/barcodeencoder)
```
public class CodabarEncoder extends BarCodeEncoder
```
## Constructors

| Constructor | Description |
| --- | --- |
| [CodabarEncoder(CodabarEncoderParameters parameters)](#CodabarEncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.CodabarEncoderParameters-) |  |
## Methods

| Method | Description |
| --- | --- |
| [charToEncodedValue(char c)](#charToEncodedValue-char-) |  |
| [encode(String code)](#encode-java.lang.String-) |  |
| [encodedValueToChar(int id)](#encodedValueToChar-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChecksum()](#getChecksum--) |  |
| [getClass()](#getClass--) |  |
| [getEnableChecksum()](#getEnableChecksum--) |  |
| [getHumanReadableCodeText()](#getHumanReadableCodeText--) |  |
| [getHumanReadableCodeText_Rename_Namesake()](#getHumanReadableCodeText-Rename-Namesake--) |  |
| [getParameters()](#getParameters--) |  |
| [hashCode()](#hashCode--) |  |
| [isValidCode(String code)](#isValidCode-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CodabarEncoder(CodabarEncoderParameters parameters) {#CodabarEncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.CodabarEncoderParameters-}
```
public CodabarEncoder(CodabarEncoderParameters parameters)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parameters | [CodabarEncoderParameters](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters/codabarencoderparameters) |  |

### charToEncodedValue(char c) {#charToEncodedValue-char-}
```
public static int charToEncodedValue(char c)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| c | char |  |

**Returns:**
int
### encode(String code) {#encode-java.lang.String-}
```
public String encode(String code)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| code | java.lang.String |  |

**Returns:**
java.lang.String
### encodedValueToChar(int id) {#encodedValueToChar-int-}
```
public static char encodedValueToChar(int id)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int |  |

**Returns:**
char
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isValidCode(String code) {#isValidCode-java.lang.String-}
```
public boolean isValidCode(String code)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| code | java.lang.String |  |

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

