---
title: DatabarOmnidirectionalStackedEncoder
second_title: Aspose.BarCode for Java API Reference
description: The class for Databar omni directional stacked encoder
type: docs
weight: 28
url: /java/com.aspose.barcode.generation.renderers.barcoderenderers.encoders/databaromnidirectionalstackedencoder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.renderers.barcoderenderers.encoders.BarCodeEncoder](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders/barcodeencoder), [com.aspose.barcode.generation.renderers.barcoderenderers.encoders.DatabarOmniDirectionalEncoder](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders/databaromnidirectionalencoder), [com.aspose.barcode.generation.renderers.barcoderenderers.encoders.DatabarStackedEncoder](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders/databarstackedencoder)
```
public class DatabarOmnidirectionalStackedEncoder extends DatabarStackedEncoder
```

The class for Databar omni directional stacked encoder
## Constructors

| Constructor | Description |
| --- | --- |
| [DatabarOmnidirectionalStackedEncoder(DataBarEncoderParameters parameters)](#DatabarOmnidirectionalStackedEncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.DataBarEncoderParameters-) | Initializes a new instance of the  DatabarOmnidirectionalStackedEncoder  class. |
## Methods

| Method | Description |
| --- | --- |
| [encode(String str)](#encode-java.lang.String-) | Encodes string of data to Databar Stacked barcode string |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChecksum()](#getChecksum--) |  |
| [getClass()](#getClass--) |  |
| [getEnableChecksum()](#getEnableChecksum--) |  |
| [getHumanReadableCodeText()](#getHumanReadableCodeText--) |  |
| [getHumanReadableCodeText_Rename_Namesake()](#getHumanReadableCodeText-Rename-Namesake--) |  |
| [getParameters()](#getParameters--) |  |
| [getRSSWidth(int val, int n, int elements, int maxWidth, int noNarrow)](#getRSSWidth-int-int-int-int-int-) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DatabarOmnidirectionalStackedEncoder(DataBarEncoderParameters parameters) {#DatabarOmnidirectionalStackedEncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.DataBarEncoderParameters-}
```
public DatabarOmnidirectionalStackedEncoder(DataBarEncoderParameters parameters)
```


Initializes a new instance of the  DatabarOmnidirectionalStackedEncoder  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parameters | [DataBarEncoderParameters](../../com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters/databarencoderparameters) |  |

### encode(String str) {#encode-java.lang.String-}
```
public String encode(String str)
```


Encodes string of data to Databar Stacked barcode string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| str | java.lang.String | input data |

**Returns:**
java.lang.String - strings of bits for the barcode
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
### getRSSWidth(int val, int n, int elements, int maxWidth, int noNarrow) {#getRSSWidth-int-int-int-int-int-}
```
public static Int32List getRSSWidth(int val, int n, int elements, int maxWidth, int noNarrow)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| val | int |  |
| n | int |  |
| elements | int |  |
| maxWidth | int |  |
| noNarrow | int |  |

**Returns:**
[Int32List](../../com.aspose.barcode.common.generic.list/int32list)
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

