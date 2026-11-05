---
title: "CodabarParameters"
second_title: "Aspose.BarCode for Android via Java API 参考"
description: "Codabar 参数。"
type: docs
weight: 22
url: /zh/androidjava/com.aspose.barcode.generation/codabarparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodabarParameters
```

Codabar 参数。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChecksumMode()](#getChecksumMode--) | 获取 Codabar 条码的校验和算法。 |
| [getClass()](#getClass--) |  |
| [getStartSymbol()](#getStartSymbol--) | Codabar 符号系统的起始符号（字符）。 |
| [getStopSymbol()](#getStopSymbol--) | Codabar 符号系统的结束符号（字符）。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChecksumMode(CodabarChecksumMode value)](#setChecksumMode-com.aspose.barcode.generation.CodabarChecksumMode-) | 设置 Codabar 条码的校验和算法。 |
| [setStartSymbol(CodabarSymbol value)](#setStartSymbol-com.aspose.barcode.generation.CodabarSymbol-) | Codabar 符号系统的起始符号（字符）。 |
| [setStopSymbol(CodabarSymbol value)](#setStopSymbol-com.aspose.barcode.generation.CodabarSymbol-) | Codabar 符号系统的结束符号（字符）。 |
| [toString()](#toString--) | 返回此 [CodabarParameters](../../com.aspose.barcode.generation/codabarparameters) 的人类可读字符串表示。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getChecksumMode() {#getChecksumMode--}
```
public final CodabarChecksumMode getChecksumMode()
```


获取 Codabar 条码的校验和算法。默认值：CodabarChecksumMode.Mod16。要启用校验和计算，请将属性 EnableChecksum 的值设置为 EnableChecksum.Yes。参见 ChecksumMode (\#getChecksumMode.getChecksumMode/\#setChecksumMode.setChecksumMode)。

**Returns:**
[CodabarChecksumMode](../../com.aspose.barcode.generation/codabarchecksummode) - the checksum algorithm for Codabar barcodes.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getStartSymbol() {#getStartSymbol--}
```
public final CodabarSymbol getStartSymbol()
```


Codabar 符号系统的起始符号（字符）。默认值：CodabarSymbol.A

**Returns:**
[CodabarSymbol](../../com.aspose.barcode.generation/codabarsymbol)
### getStopSymbol() {#getStopSymbol--}
```
public final CodabarSymbol getStopSymbol()
```


Codabar 符号系统的结束符号（字符）。默认值：CodabarSymbol.A

**Returns:**
[CodabarSymbol](../../com.aspose.barcode.generation/codabarsymbol)
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setChecksumMode(CodabarChecksumMode value) {#setChecksumMode-com.aspose.barcode.generation.CodabarChecksumMode-}
```
public final void setChecksumMode(CodabarChecksumMode value)
```


设置 Codabar 条码的校验和算法。默认值：CodabarChecksumMode.Mod16。要启用校验和计算，请将属性 EnableChecksum 的值设置为 EnableChecksum.Yes。参见 ChecksumMode (\#getChecksumMode.getChecksumMode/\#setChecksumMode.setChecksumMode)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CodabarChecksumMode](../../com.aspose.barcode.generation/codabarchecksummode) | Codabar 条码的校验和算法。 |

### setStartSymbol(CodabarSymbol value) {#setStartSymbol-com.aspose.barcode.generation.CodabarSymbol-}
```
public final void setStartSymbol(CodabarSymbol value)
```


Codabar 符号系统的起始符号（字符）。默认值：CodabarSymbol.A

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CodabarSymbol](../../com.aspose.barcode.generation/codabarsymbol) |  |

### setStopSymbol(CodabarSymbol value) {#setStopSymbol-com.aspose.barcode.generation.CodabarSymbol-}
```
public final void setStopSymbol(CodabarSymbol value)
```


Codabar 符号系统的结束符号（字符）。默认值：CodabarSymbol.A

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [CodabarSymbol](../../com.aspose.barcode.generation/codabarsymbol) |  |

### toString() {#toString--}
```
public String toString()
```


返回此 [CodabarParameters](../../com.aspose.barcode.generation/codabarparameters) 的人类可读字符串表示。

**Returns:**
java.lang.String - 表示此 [CodabarParameters](../../com.aspose.barcode.generation/codabarparameters) 的字符串。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | 整数 |  |

