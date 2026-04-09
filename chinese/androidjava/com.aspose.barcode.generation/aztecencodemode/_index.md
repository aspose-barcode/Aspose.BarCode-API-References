---
title: AztecEncodeMode
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: Aztec 条形码的编码模式。
type: docs
weight: 73
url: /zh/androidjava/com.aspose.barcode.generation/aztecencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum AztecEncodeMode extends Enum<AztecEncodeMode>
```

Aztec 条形码的编码模式。

--------------------

> ```
> String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
>  generator.getParameters().getBarcode().getAztec().setECIEncoding(ECIEncodings.UTF_8);
>  generator.save("test.bmp");
>  byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC);
>  generator.setCodetext(encodedArr);
>  generator.getParameters().getBarcode().getAztec().setAztecEncodeMode(AztecEncodeMode.BINARY);
>  generator.save("test.bmp");
> 
>  //Extended mode
>  //create codetext
>  AztecExtCodetextBuilder textBuilder = new AztecExtCodetextBuilder();
>  textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>  textBuilder.addECICodetext(ECIEncodings.UTF8, "\u72acRight\u72d7");
>  textBuilder.addECICodetext(ECIEncodings.UTF16BE, "\u72acPower\u72d7");
>  textBuilder.addPlainCodetext("Plain text");
>  //generate codetext
>  String codetext = textBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.AZTEC, codetext);
>  generator.getParameters().getBarcode().getAztec().setAztecEncodeMode(AztecEncodeMode.EXTENDED);
>  generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>  generator.save("test.bmp");
> ```
## 字段

| 字段 | 描述 |
| --- | --- |
| [AUTO](#AUTO) | 在 Auto 模式下，CodeText 以最大数据紧凑度进行编码。 |
| [BINARY](#BINARY) | 在 Binary 模式下，CodeText 以最大数据紧凑度进行编码。 |
| [BYTES](#BYTES) | 将 codetext 编码为纯字节。 |
| [ECI](#ECI) | 在 ECI 模式下，整个消息会使用 ECIEncoding 指定的编码重新编码，并插入 ECI 标识符。 |
| [EXTENDED](#EXTENDED) |  |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AUTO {#AUTO}
```
public static final AztecEncodeMode AUTO
```


在 Auto 模式下，CodeText 以最高数据紧凑度进行编码。Unicode 字符会使用 ECIEncoding 指定的编码重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则抛出异常。

### BINARY {#BINARY}
```
public static final AztecEncodeMode BINARY
```


在 Binary 模式下，CodeText 以最高数据紧凑度进行编码。如果发现 Unicode 字符，则抛出异常。

### BYTES {#BYTES}
```
public static final AztecEncodeMode BYTES
```


将 codetext 编码为纯字节。如果检测到任何 Unicode 字符，该字符将被编码为两个字节，低位字节在前。

### ECI {#ECI}
```
public static final AztecEncodeMode ECI
```


在 ECI 模式下，整个消息会使用 ECIEncoding 指定的编码重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则抛出异常。请注意，某些旧（2006 年之前）的扫描仪可能不支持此模式。

### EXTENDED {#EXTENDED}
```
public static final AztecEncodeMode EXTENDED
```


支持多 ECI 模式的扩展模式。

建议使用 AztecExtCodetextBuilder 进行扩展代码文本生成。

使用 Display2DText 属性设置可见文本以去除管理字符。

ECI 标识符设置为单斜杠加六位数字标识符 \"\\\\000026\" —— UTF8 ECI 标识符

所有在 ECI 标识符之后的 Unicode 字符会自动编码为正确的字符集。

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final AztecEncodeMode EXTENDED_CODETEXT
```


支持多 ECI 模式的扩展模式。

建议使用 AztecExtCodetextBuilder 进行扩展代码文本生成。

使用 Display2DText 属性设置可见文本以去除管理字符。

ECI 标识符设置为单斜杠加六位数字标识符 \"\\\\000026\" —— UTF8 ECI 标识符

所有在 ECI 标识符之后的 Unicode 字符会自动编码为正确的字符集。

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### getValue() {#getValue--}
```
public int getValue()
```




**Returns:**
int
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




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




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static AztecEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
com.aspose.barcode.generation.AztecEncodeMode
### values() {#values--}
```
public static AztecEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.AztecEncodeMode[]
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

