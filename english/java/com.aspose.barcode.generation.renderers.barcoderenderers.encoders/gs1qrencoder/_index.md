---
title: GS1QREncoder
second_title: Aspose.BarCode for Java API Reference
description: Contains functions for encoding GS1QR
type: docs
weight: 44
url: /java/com.aspose.barcode.generation.renderers.barcoderenderers.encoders/gs1qrencoder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.renderers.barcoderenderers.encoders.BarCodeEncoder](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders/barcodeencoder), [com.aspose.barcode.generation.renderers.barcoderenderers.encoders.QREncoder](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders/qrencoder)
```
public class GS1QREncoder extends QREncoder
```

Contains functions for encoding GS1QR
## Constructors

| Constructor | Description |
| --- | --- |
| [GS1QREncoder(QrEncoderParameters parameters)](#GS1QREncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.QrEncoderParameters-) | Initializes a new instance of the  GS1QREncoder  class.> |
## Methods

| Method | Description |
| --- | --- |
| [encode(String str)](#encode-java.lang.String-) | Encodes string of data to GS1QR barcode string |
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
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GS1QREncoder(QrEncoderParameters parameters) {#GS1QREncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.QrEncoderParameters-}
```
public GS1QREncoder(QrEncoderParameters parameters)
```


Initializes a new instance of the  GS1QREncoder  class.>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parameters | [QrEncoderParameters](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters/qrencoderparameters) |  |

### encode(String str) {#encode-java.lang.String-}
```
public String encode(String str)
```


Encodes string of data to GS1QR barcode string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String | Input string |

**Returns:**
java.lang.String - Binary string
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

