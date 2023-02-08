---
title: Code128Encoder
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 15
url: /java/com.aspose.barcode.generation.renderers.barcoderenderers.encoders/code128encoder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.renderers.barcoderenderers.encoders.BarCodeEncoder](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders/barcodeencoder)
```
public class Code128Encoder extends BarCodeEncoder
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Code128Encoder(EnableEscapeEncoderParameters parameters)](#Code128Encoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.EnableEscapeEncoderParameters-) |  |
## Fields

| Field | Description |
| --- | --- |
| [CODEA](#CODEA) |  |
| [CODEB](#CODEB) |  |
| [CODEC](#CODEC) |  |
| [CODESHIFT](#CODESHIFT) |  |
| [FNC1](#FNC1) |  |
| [STARTCHARA](#STARTCHARA) |  |
| [STOPCHAR](#STOPCHAR) |  |
| [_MappingTable](#-MappingTable) |  |
## Methods

| Method | Description |
| --- | --- |
| [encode(String code)](#encode-java.lang.String-) |  |
| [encodeSequence(String codetext)](#encodeSequence-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChecksum()](#getChecksum--) |  |
| [getClass()](#getClass--) |  |
| [getEnableChecksum()](#getEnableChecksum--) |  |
| [getHumanReadableCodeText()](#getHumanReadableCodeText--) |  |
| [getHumanReadableCodeText_Rename_Namesake()](#getHumanReadableCodeText-Rename-Namesake--) |  |
| [getParameters()](#getParameters--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [processCodeSets(String codetext)](#processCodeSets-java.lang.String-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Code128Encoder(EnableEscapeEncoderParameters parameters) {#Code128Encoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.EnableEscapeEncoderParameters-}
```
public Code128Encoder(EnableEscapeEncoderParameters parameters)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parameters | [EnableEscapeEncoderParameters](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters/enableescapeencoderparameters) |  |

### CODEA {#CODEA}
```
public static final char CODEA
```


### CODEB {#CODEB}
```
public static final char CODEB
```


### CODEC {#CODEC}
```
public static final char CODEC
```


### CODESHIFT {#CODESHIFT}
```
public static final char CODESHIFT
```


### FNC1 {#FNC1}
```
public static final char FNC1
```


### STARTCHARA {#STARTCHARA}
```
public static final char STARTCHARA
```


### STOPCHAR {#STOPCHAR}
```
public static final char STOPCHAR
```


### _MappingTable {#-MappingTable}
```
public static final String[] _MappingTable
```


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
### encodeSequence(String codetext) {#encodeSequence-java.lang.String-}
```
public String encodeSequence(String codetext)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codetext | java.lang.String |  |

**Returns:**
java.lang.String
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### processCodeSets(String codetext) {#processCodeSets-java.lang.String-}
```
public StringBuilder processCodeSets(String codetext)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codetext | java.lang.String |  |

**Returns:**
java.lang.StringBuilder
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

