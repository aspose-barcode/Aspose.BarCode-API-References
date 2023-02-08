---
title: OPCEncoder
second_title: Aspose.BarCode for Java API Reference
description: 
type: docs
weight: 69
url: /java/com.aspose.barcode.generation.renderers.barcoderenderers.encoders/opcencoder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.renderers.barcoderenderers.encoders.BarCodeEncoder](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders/barcodeencoder), [com.aspose.barcode.generation.renderers.barcoderenderers.encoders.Interleaved2of5Encoder](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders/interleaved2of5encoder)
```
public class OPCEncoder extends Interleaved2of5Encoder
```
## Constructors

| Constructor | Description |
| --- | --- |
| [OPCEncoder(EncoderParameters parameters)](#OPCEncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.EncoderParameters-) |  |
## Methods

| Method | Description |
| --- | --- |
| [encode(String str)](#encode-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChecksum()](#getChecksum--) |  |
| [getClass()](#getClass--) |  |
| [getEnableChecksum()](#getEnableChecksum--) |  |
| [getHumanReadableCodeText()](#getHumanReadableCodeText--) |  |
| [getHumanReadableCodeText_Rename_Namesake()](#getHumanReadableCodeText-Rename-Namesake--) |  |
| [getParameters()](#getParameters--) |  |
| [hashCode()](#hashCode--) |  |
| [makeCodeTextWithChecksum(String codetext1)](#makeCodeTextWithChecksum-java.lang.String-) |  |
| [makeHumanText(String s, String checksum)](#makeHumanText-java.lang.String-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OPCEncoder(EncoderParameters parameters) {#OPCEncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.EncoderParameters-}
```
public OPCEncoder(EncoderParameters parameters)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parameters | [EncoderParameters](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters/encoderparameters) |  |

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
### makeCodeTextWithChecksum(String codetext1) {#makeCodeTextWithChecksum-java.lang.String-}
```
public String makeCodeTextWithChecksum(String codetext1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codetext1 | java.lang.String |  |

**Returns:**
java.lang.String
### makeHumanText(String s, String checksum) {#makeHumanText-java.lang.String-java.lang.String-}
```
public String makeHumanText(String s, String checksum)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| s | java.lang.String |  |
| checksum | java.lang.String |  |

**Returns:**
java.lang.String
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

