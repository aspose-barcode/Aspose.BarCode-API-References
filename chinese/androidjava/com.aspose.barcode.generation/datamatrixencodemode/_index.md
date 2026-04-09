---
title: DataMatrixEncodeMode
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: DataMatrix 编码器的编码模式默认设为 Auto
type: docs
weight: 83
url: /zh/androidjava/com.aspose.barcode.generation/datamatrixencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DataMatrixEncodeMode extends Enum<DataMatrixEncodeMode>
```

DataMatrix 编码器的编码模式，默认自动。

--------------------

> ```
> This sample shows how to do codetext in Extended Mode.
>  
>  //Auto mode
>  String codetext = "\u72acRight\u72d7";
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setECIEncoding(ECIEncodings.UTF8);
>  generator.save("test.bmp");
>  //Bytes mode
>  byte[] encodedArr = { (byte)0xFF, (byte)0xFE, (byte)0xFD, (byte)0xFC, (byte)0xFB, (byte)0xFA, (byte)0xF9 };
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  generator.setCodetext(encodedArr);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.BINARY);
>  generator.save("test.bmp");
>  //Extended codetext mode
>  //create codetext
>  DataMatrixExtCodetextBuilder codetextBuilder=new DataMatrixExtCodetextBuilder();
>  codetextBuilder.addECICodetextWithEncodeMode(ECIEncodings.Win1251,EncodeMode.BYTES,"World");
>  codetextBuilder.addPlainCodetext("Will");
>  codetextBuilder.addECICodetext(ECIEncodings.UTF8,"\u72acRight\u72d7");
>  codetextBuilder.addCodetextWithEncodeMode(EncodeMode.C40,"ABCDE");
>  //generate codetext
>  String codetext=codetextBuilder.getExtended();
>  //generate
>  BarcodeGenerator generator=new BarcodeGenerator(EncodeTypes.DATA_MATRIX,codetext);
>  generator.getParameters().getBarcode().getDataMatrix().setEncodeMode(EncodeMode.EXTENDED_CODETEXT);
>  generator.save("test.bmp");
> ```
## 字段

| 字段 | 描述 |
| --- | --- |
| [ANSIX12](#ANSIX12) | 使用 ANSI X12 编码。 |
| [ASCII](#ASCII) | 每字节编码一个字母数字字符或两个数字字符 |
| [AUTO](#AUTO) | 在 Auto 模式下，CodeText 以最大数据紧凑度进行编码。 |
| [BASE_256](#BASE-256) | 编码 8 位值 |
| [BINARY](#BINARY) | 在 Binary 模式下，CodeText 以最大数据紧凑度进行编码。 |
| [BYTES](#BYTES) | 编码 8 位值 |
| [C40](#C40) | 使用 C40 编码。 |
| [ECI](#ECI) | 在 ECI 模式下，整个消息会使用 ECIEncoding 指定的编码重新编码，并插入 ECI 标识符。 |
| [EDIFACT](#EDIFACT) | 使用 EDIFACT 编码。 |
| [EXTENDED](#EXTENDED) | ExtendedCodetext 模式允许在代码文本中手动切换编码方案和 ECI 编码。 |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) |  |
| [TEXT](#TEXT) | 使用 Text 编码。 |
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
### ANSIX12 {#ANSIX12}
```
public static final DataMatrixEncodeMode ANSIX12
```


使用 ANSI X12 编码。

### ASCII {#ASCII}
```
public static final DataMatrixEncodeMode ASCII
```


每字节编码一个字母数字字符或两个数字字符

### AUTO {#AUTO}
```
public static final DataMatrixEncodeMode AUTO
```


在 Auto 模式下，CodeText 以最高数据紧凑度进行编码。Unicode 字符会使用 ECIEncoding 指定的编码重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则抛出异常。

### BASE_256 {#BASE-256}
```
public static final DataMatrixEncodeMode BASE_256
```


编码 8 位值

### BINARY {#BINARY}
```
public static final DataMatrixEncodeMode BINARY
```


在 Binary 模式下，CodeText 以最高数据紧凑度进行编码。如果发现 Unicode 字符，则抛出异常。

### BYTES {#BYTES}
```
public static final DataMatrixEncodeMode BYTES
```


编码 8 位值

### C40 {#C40}
```
public static final DataMatrixEncodeMode C40
```


使用 C40 编码。编码大写字母数字、小写字母和特殊字符

### ECI {#ECI}
```
public static final DataMatrixEncodeMode ECI
```


在 ECI 模式下，整个消息会使用 ECIEncoding 指定的编码重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则抛出异常。请注意，某些旧（2006 年之前）的扫描仪可能不支持此模式。

### EDIFACT {#EDIFACT}
```
public static final DataMatrixEncodeMode EDIFACT
```


使用 EDIFACT 编码。每个字符使用六位，编码数字、大写字母和许多标点符号，但不支持小写字母。

### EXTENDED {#EXTENDED}
```
public static final DataMatrixEncodeMode EXTENDED
```


ExtendedCodetext 模式允许在代码文本中手动切换编码方案和 ECI 编码。最好使用 DataMatrixExtCodetextBuilder 来生成扩展代码文本。使用 Display2DText 属性设置可见文本以去除管理字符。ECI 标识符设置为单斜杠加六位数字标识符 \"\\\\000026\" —— UTF8 ECI 标识符。所有在 ECI 标识符之后的 Unicode 字符会自动编码为正确的字符集。编码方案的设置格式如下：\"\\\\Encodation\_scheme\_name:text\\\\Encodation\_scheme\_name:text\"。允许的编码方案有：EDIFACT、ANSIX12、ASCII、C40、Text、Auto。文本中的所有反斜杠 (\\\\) 必须加倍。

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final DataMatrixEncodeMode EXTENDED_CODETEXT
```


ExtendedCodetext 模式允许在代码文本中手动切换编码方案和 ECI 编码。

最好使用 DataMatrixExtCodetextBuilder 来生成扩展代码文本。

使用 Display2DText 属性设置可见文本以去除管理字符。

ECI 标识符设置为单斜杠加六位数字标识符 \"\\\\000026\" —— UTF8 ECI 标识符

所有在 ECI 标识符之后的 Unicode 字符会自动编码为正确的字符集。

编码方案的设置格式如下：\"\\\\Encodation\_scheme\_name:text\\\\Encodation\_scheme\_name:text\"。

允许的编码方案有：EDIFACT、ANSIX12、ASCII、C40、Text、Auto。

文本中的所有反斜杠 (\\\\) 必须加倍。

### TEXT {#TEXT}
```
public static final DataMatrixEncodeMode TEXT
```


使用 Text 编码。编码小写字母数字、大写字母和特殊字符

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
public static DataMatrixEncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode)
### values() {#values--}
```
public static DataMatrixEncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.DataMatrixEncodeMode[]
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

