---
title: GS1HanXinEncoder
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 包含用于编码 GS1HanXin 的函数
type: docs
weight: 47
url: /zh/androidjava/com.aspose.barcode.generation/gs1hanxinencoder/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.generation.renderers.barcoderenderers.encoders.BarCodeEncoder, com.aspose.barcode.generation.HanXinEncoder
```
public class GS1HanXinEncoder extends HanXinEncoder
```

包含用于编码 GS1HanXin 的函数
## Constructors

| Constructor | 描述 |
| --- | --- |
| [GS1HanXinEncoder(HanXinEncoderParameters parameters)](#GS1HanXinEncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.HanXinEncoderParameters-) | 输入数据应仅使用括号 () 作为模式分隔符，例如：(01)12345678901231(21)ASPOSE(30)9876。根据 GS1 规范，所有预定义长度的 GS1 数据字符串后面应跟随所有非预定义长度的 GS1 数据字符串。 |
## Methods

| Method | 描述 |
| --- | --- |
| [encode(String str)](#encode-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlwaysShowChecksum()](#getAlwaysShowChecksum--) |  |
| [getChecksum()](#getChecksum--) |  |
| [getClass()](#getClass--) |  |
| [getEnableChecksum()](#getEnableChecksum--) |  |
| [getEncodeType()](#getEncodeType--) |  |
| [getHumanReadableCodeText()](#getHumanReadableCodeText--) |  |
| [getParameters()](#getParameters--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GS1HanXinEncoder(HanXinEncoderParameters parameters) {#GS1HanXinEncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.HanXinEncoderParameters-}
```
public GS1HanXinEncoder(HanXinEncoderParameters parameters)
```


输入数据应仅使用括号 () 作为模式分隔符，例如：(01)12345678901231(21)ASPOSE(30)9876。根据 GS1 规范，所有预定义长度的 GS1 数据字符串后面应跟随所有非预定义长度的 GS1 数据字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 参数 | com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.HanXinEncoderParameters |  |

### encode(String str) {#encode-java.lang.String-}
```
public String encode(String str)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| str | java.lang.String |  |

**Returns:**
java.lang.String
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlwaysShowChecksum() {#getAlwaysShowChecksum--}
```
public boolean getAlwaysShowChecksum()
```




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
### getEncodeType() {#getEncodeType--}
```
public BaseEncodeType getEncodeType()
```




**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getHumanReadableCodeText() {#getHumanReadableCodeText--}
```
public String getHumanReadableCodeText()
```




**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public EncoderParameters getParameters()
```




**Returns:**
com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.EncoderParameters
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
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

