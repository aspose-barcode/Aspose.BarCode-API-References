---
title: "ExtCodetextBuilder"
second_title: "Aspose.BarCode for Java API Reference"
description: "用于自动生成扩展代码文本模式的帮助类"
type: docs
weight: 38
url: /zh/java/com.aspose.barcode.generation/extcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public abstract class ExtCodetextBuilder
```

用于自动生成扩展代码文本模式的帮助类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ExtCodetextBuilder()](#ExtCodetextBuilder--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | 添加带有扩展通道标识符的 codetext |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | 向扩展 codetext 项目添加普通 codetext |
| [clear()](#clear--) | 清除扩展 codetext 项目 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | 从生成项列表生成扩展代码文本 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExtCodetextBuilder() {#ExtCodetextBuilder--}
```
public ExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public final void addECICodetext(int ECIEncoding, String codetext)
```


添加带有扩展通道标识符的 codetext

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ECIEncoding | int | 扩展通道标识符 |
| codetext | java.lang.String | 以 Unicode 形式的 Codetext，用于添加为带有扩展通道标识符的扩展 codetext 项目 |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


向扩展 codetext 项目添加普通 codetext

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| codetext | java.lang.String | 以 Unicode 形式的代码文本，用于添加为扩展代码文本项 |

### clear() {#clear--}
```
public void clear()
```


清除扩展 codetext 项目

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtendedCodetext() {#getExtendedCodetext--}
```
public abstract String getExtendedCodetext()
```


从生成项列表生成扩展代码文本

**Returns:**
java.lang.String - 返回扩展代码文本的字符串
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
| arg1 | int |  |

