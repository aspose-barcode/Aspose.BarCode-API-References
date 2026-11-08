---
title: "DotCodeExtCodetextBuilder"
second_title: "Aspose.BarCode for Java API Reference"
description: 
type: docs
weight: 33
url: /zh/java/com.aspose.barcode.generation/dotcodeextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class DotCodeExtCodetextBuilder extends ExtCodetextBuilder
```

用于 DotCodeEncodeMode 的 ExtendedCodetext 模式的 2D DotCode 条码的扩展码文本生成器

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  DotCodeExtCodetextBuilder textBuilder = new DotCodeExtCodetextBuilder();
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addFNC1FormatIdentifier();
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  textBuilder.addFNC3SymbolSeparator();
>  textBuilder.addFNC3ReaderInitialization();
>  textBuilder.addPlainCodetext("Reader initialization info");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DOT_CODE, codetext);
>  generator.getParameters().getBarcode().getDotCode().setDotCodeEncodeMode(DotCodeEncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DotCodeExtCodetextBuilder()](#DotCodeExtCodetextBuilder--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | 添加带有扩展通道标识符的 codetext |
| [addFNC1FormatIdentifier()](#addFNC1FormatIdentifier--) | 向扩展码文本项添加 FNC1 格式标识符 |
| [addFNC3ReaderInitialization()](#addFNC3ReaderInitialization--) | 向扩展码文本项添加 FNC3 读取器初始化 |
| [addFNC3SymbolSeparator()](#addFNC3SymbolSeparator--) | 向扩展码文本项添加 FNC3 符号分隔符 |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | 向扩展 codetext 项目添加普通 codetext |
| [addStructuredAppendMode(int barcodeId, int barcodesCount)](#addStructuredAppendMode-int-int-) | 向扩展码文本项添加结构化追加模式 |
| [clear()](#clear--) | 清除扩展 codetext 项目 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | 从扩展 codetext 列表生成 Extended codetext。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DotCodeExtCodetextBuilder() {#DotCodeExtCodetextBuilder--}
```
public DotCodeExtCodetextBuilder()
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

### addFNC1FormatIdentifier() {#addFNC1FormatIdentifier--}
```
public final void addFNC1FormatIdentifier()
```


向扩展码文本项添加 FNC1 格式标识符

### addFNC3ReaderInitialization() {#addFNC3ReaderInitialization--}
```
public final void addFNC3ReaderInitialization()
```


向扩展码文本项添加 FNC3 读取器初始化

### addFNC3SymbolSeparator() {#addFNC3SymbolSeparator--}
```
public final void addFNC3SymbolSeparator()
```


向扩展码文本项添加 FNC3 符号分隔符

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public final void addPlainCodetext(String codetext)
```


向扩展 codetext 项目添加普通 codetext

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| codetext | java.lang.String | 以 Unicode 形式的代码文本，用于添加为扩展代码文本项 |

### addStructuredAppendMode(int barcodeId, int barcodesCount) {#addStructuredAppendMode-int-int-}
```
public final void addStructuredAppendMode(int barcodeId, int barcodesCount)
```


向扩展码文本项添加结构化追加模式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| barcodeId | int | 条码的 ID |
| barcodesCount | int | 条码数量 |

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
public String getExtendedCodetext()
```


从扩展 codetext 列表生成 Extended codetext。

**Returns:**
java.lang.String - 扩展代码文本作为字符串
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

