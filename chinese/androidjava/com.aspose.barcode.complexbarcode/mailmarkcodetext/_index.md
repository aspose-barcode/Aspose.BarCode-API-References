---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode for Android via Java API 参考"
description: "用于对嵌入 4 状态 Royal Mailmark 代码中的文本进行编码和解码的类。"
type: docs
weight: 24
url: /zh/androidjava/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

用于对嵌入 4 状态 Royal Mailmark 代码中的文本进行编码和解码的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | 初始化 MailmarkCodetext 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | 获取条形码类型。 |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | "0" - 空或测试 "1" - 1C（零售） "2" - 2C（零售） "3" - 3C（零售） "4" - Premium（RetailPublishing Mail）（供未来使用） "5" - Deferred（零售） "6" - Air（零售）（供未来使用） "7" - Surface（零售）（供未来使用） "8" - Premium（网络访问） "9" - Standard（网络访问） |
| [getConstructedCodetext()](#getConstructedCodetext--) | 从 Mailmark 数据构造代码文本。 |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | PC 和 DP 必须符合 PAF 格式。 |
| [getFormat()](#getFormat--) | "0" \\u2013 空或测试 "1" \\u2013 信件 "2" \\u2013 大信件 |
| [getItemID()](#getItemID--) | 最大值为 99999999。 |
| [getSupplychainID()](#getSupplychainID--) | Barcode C 的最大值为 99，Barcode L 的最大值为 999999。 |
| [getVersionID()](#getVersionID--) | 当前 "1" \\u2013 用于 Mailmark 条形码（0 以及 2 到 9 和 A 到 Z 预留供未来使用） |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 从构造的代码文本初始化 Mailmark 数据。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | "0" - 空或测试 "1" - 1C（零售） "2" - 2C（零售） "3" - 3C（零售） "4" - Premium（RetailPublishing Mail）（供未来使用） "5" - Deferred（零售） "6" - Air（零售）（供未来使用） "7" - Surface（零售）（供未来使用） "8" - Premium（网络访问） "9" - Standard（网络访问） |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | PC 和 DP 必须符合 PAF 格式。 |
| [setFormat(int value)](#setFormat-int-) | "0" \\u2013 空或测试 "1" \\u2013 信件 "2" \\u2013 大信件 |
| [setItemID(int value)](#setItemID-int-) | 最大值为 99999999。 |
| [setSupplychainID(int value)](#setSupplychainID-int-) | Barcode C 的最大值为 99，Barcode L 的最大值为 999999。 |
| [setVersionID(int value)](#setVersionID-int-) | 当前 "1" \\u2013 用于 Mailmark 条形码（0 以及 2 到 9 和 A 到 Z 预留供未来使用） |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


初始化 MailmarkCodetext 类的新实例。

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


获取条形码类型。

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClass_() {#getClass---}
```
public String getClass_()
```


"0" - 空或测试 "1" - 1C（零售） "2" - 2C（零售） "3" - 3C（零售） "4" - Premium（RetailPublishing Mail）（供未来使用） "5" - Deferred（零售） "6" - Air（零售）（供未来使用） "7" - Surface（零售）（供未来使用） "8" - Premium（网络访问） "9" - Standard（网络访问）

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


从 Mailmark 数据构造代码文本。

**Returns:**
java.lang.String - 已构建的 codetext
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


PC 和 DP 必须符合 PAF 格式。九字符字符串表示国际 "XY11 "（注意后面的 5 个空格）或表示国内分拣代码的字符模式。国内分拣代码由外部邮编、内部邮编和投递点后缀组成。

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


"0" \\u2013 空或测试 "1" \\u2013 信件 "2" \\u2013 大信件

**Returns:**
整数
### getItemID() {#getItemID--}
```
public int getItemID()
```


最大值为 99999999。

**Returns:**
整数
### getSupplychainID() {#getSupplychainID--}
```
public int getSupplychainID()
```


Barcode C 的最大值为 99，Barcode L 的最大值为 999999。

**Returns:**
整数
### getVersionID() {#getVersionID--}
```
public int getVersionID()
```


当前 "1" \\u2013 用于 Mailmark 条形码（0 以及 2 到 9 和 A 到 Z 预留供未来使用）

**Returns:**
整数
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
整数
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


从构造的代码文本初始化 Mailmark 数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| constructedCodetext | java.lang.String | 已构建的 codetext。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setClass(String value) {#setClass-java.lang.String-}
```
public void setClass(String value)
```


"0" - 空或测试 "1" - 1C（零售） "2" - 2C（零售） "3" - 3C（零售） "4" - Premium（RetailPublishing Mail）（供未来使用） "5" - Deferred（零售） "6" - Air（零售）（供未来使用） "7" - Surface（零售）（供未来使用） "8" - Premium（网络访问） "9" - Standard（网络访问）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


PC 和 DP 必须符合 PAF 格式。九字符字符串表示国际 "XY11 "（注意后面的 5 个空格）或表示国内分拣代码的字符模式。国内分拣代码由外部邮编、内部邮编和投递点后缀组成。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


"0" \\u2013 空或测试 "1" \\u2013 信件 "2" \\u2013 大信件

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


最大值为 99999999。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


Barcode C 的最大值为 99，Barcode L 的最大值为 999999。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


当前 "1" \\u2013 用于 Mailmark 条形码（0 以及 2 到 9 和 A 到 Z 预留供未来使用）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 整数 |  |

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

