---
title: QREncodeMode
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: QR 条形码的编码模式。
type: docs
weight: 102
url: /zh/androidjava/com.aspose.barcode.generation/qrencodemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum QREncodeMode extends Enum<QREncodeMode>
```

QR 条形码的编码模式。

--------------------

> ```
> Example how to use ECI encoding
>  
>      BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>      generator.setCodeText("12345TEXT");
>      generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ECI_ENCODING);
>      generator.getParameters().getBarcode().getQR().setQrECIEncoding(ECIEncodings.UTF8);
>      generator.save("test.png");
> ```

--------------------

> ```
> Example how to use FNC1 first position in Extended Mode
>   
>       QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
>       textBuilder.addPlainCodetext("000%89%%0");
>       textBuilder.addFNC1GroupSeparator();
>       textBuilder.addPlainCodetext("12345<FNC1>");
>       //generate barcode
>       BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>       generator.setCodeText(textBuilder.getExtended());
>       generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
>       generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>       generator.save("d:/test.png");
>  
>       *
>  This sample shows how to use FNC1 second position in Extended Mode.
>  
> 
>     //create codetext
>     QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
>     textBuilder.addFNC1SecondPosition("12");
>     textBuilder.addPlainCodetext("TRUE3456");
>     //generate barcode
>     BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>     generator.setCodeText(textBuilder.getExtended());
>     generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>     generator.save("d:/test.png");
>     
> 
>     This sample shows how to use multi ECI mode in Extended Mode.
>     
> 
>    //create codetext
>    QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
>    textBuilder.addECICodetext(ECIEncodings.Win1251, "Will");
>    textBuilder.addECICodetext(ECIEncodings.UTF8, "Right");
>    textBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power");
>    textBuilder.addPlainCodetext("t\e\\st");
>    //generate barcode
>    BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
>    generator.setCodeText(textBuilder.getExtended());
>    generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
>    generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
>    generator.save("d:/test.png");
> ```
## 字段

| 字段 | 描述 |
| --- | --- |
| [AUTO](#AUTO) | 在 Auto 模式下，CodeText 以最大数据紧凑度进行编码。 |
| [BINARY](#BINARY) | 在 Binary 模式下，CodeText 以最大数据紧凑度进行编码。 |
| [BYTES](#BYTES) | 将 codetext 编码为纯字节。 |
| [ECI](#ECI) | 在 ECI 模式下，整个消息会使用 ECIEncoding 指定的编码重新编码，并插入 ECI 标识符。 |
| [ECI_ENCODING](#ECI-ENCODING) | 使用在 ECIEncoding 属性中设置的值对代码文本进行编码。 |
| [EXTENDED](#EXTENDED) | 扩展通道模式，支持 FNC1 首位、FNC1 次位和多 ECI 模式。建议使用 QrExtCodetextBuilder 进行扩展代码文本生成。使用 Display2DText 属性设置可见文本以去除管理字符。编码原则：所有符号 "\\" 必须在代码文本中加倍为 "\\\\"。FNC1 在首位时在代码文本中表示为 "<FNC1>"，FNC1 在次位时表示为 "<FNC1(value)>"。 |
| [EXTENDED_CODETEXT](#EXTENDED-CODETEXT) | 扩展通道模式，支持 FNC1 首位、FNC1 次位和多 ECI 模式。建议使用 QrExtCodetextBuilder 进行扩展代码文本生成。使用 Display2DText 属性设置可见文本以去除管理字符。编码原则：所有符号 "\\" 必须在代码文本中加倍为 "\\\\"。FNC1 在首位时在代码文本中表示为 "<FNC1>"，FNC1 在次位时表示为 "<FNC1(value)>"。 |
| [UTF_16_BEBOM](#UTF-16-BEBOM) | 使用 UTF8 编码并以第一个 ByteOfMark 字符对代码文本进行编码。 |
| [UTF_8_BOM](#UTF-8-BOM) | 使用 UTF8 编码并以第一个 ByteOfMark 字符对代码文本进行编码。 |
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
public static final QREncodeMode AUTO
```


在 Auto 模式下，CodeText 以最大数据紧凑度进行编码。Unicode 字符如果可能会以汉字模式编码，否则会使用在 ECIEncoding 中指定的编码重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则抛出异常。

### BINARY {#BINARY}
```
public static final QREncodeMode BINARY
```


在 Binary 模式下，CodeText 以最高数据紧凑度进行编码。如果发现 Unicode 字符，则抛出异常。

### BYTES {#BYTES}
```
public static final QREncodeMode BYTES
```


将 codetext 编码为纯字节。如果检测到任何 Unicode 字符，该字符将被编码为两个字节，低位字节在前。

### ECI {#ECI}
```
public static final QREncodeMode ECI
```


在 ECI 模式下，整个消息使用在 ECIEncoding 中指定的编码重新编码，并插入 ECI 标识符。如果发现字符不受所选 ECI 编码支持，则抛出异常。请注意，某些旧（2006 年之前）的扫描仪可能不支持此模式。MicroQR 条码不支持此模式。

### ECI_ENCODING {#ECI-ENCODING}
```
public static final QREncodeMode ECI_ENCODING
```


使用在 ECIEncoding 属性中设置的值对代码文本进行编码。某些旧（2006 年之前）的条码扫描仪可能会出现问题。MicroQR 条码不支持此模式。

### EXTENDED {#EXTENDED}
```
public static final QREncodeMode EXTENDED
```


扩展通道模式，支持 FNC1 首位、FNC1 次位和多 ECI 模式。建议使用 QrExtCodetextBuilder 进行扩展代码文本生成。使用 Display2DText 属性设置可见文本以去除管理字符。编码原则：所有符号 "\\" 必须在代码文本中加倍为 "\\\\"。FNC1 在首位时在代码文本中表示为 "<FNC1>"，FNC1 在次位时表示为 "<FNC1(value)>"。该值必须是单个符号（a-z、A-Z）或 0 到 99 的数字。FNC1 模式的组分隔符设置为 0x1D 字符 '\\\\u001D'。如果需要在条码中插入 "<FNC1>" 字符串，请写成 "<\\FNC1>"。ECI 标识符设置为单斜杠加六位数字标识符 "\\000026" - UTF8 ECI 标识符。要禁用当前 ECI 模式并转换为默认 JIS8 零模式，设置 ECI 标识符为 "\\000000"。所有在 ECI 标识符之后的 Unicode 字符将自动编码为正确的字符集。此模式不受 MicroQR 条码支持。

### EXTENDED_CODETEXT {#EXTENDED-CODETEXT}
```
public static final QREncodeMode EXTENDED_CODETEXT
```


扩展通道模式，支持 FNC1 首位、FNC1 次位和多 ECI 模式。建议使用 QrExtCodetextBuilder 进行扩展代码文本生成。使用 Display2DText 属性设置可见文本以去除管理字符。编码原则：所有符号 "\\" 必须在代码文本中加倍为 "\\\\"。FNC1 在首位时在代码文本中表示为 "<FNC1>"，FNC1 在次位时表示为 "<FNC1(value)>"。该值必须是单个符号（a-z、A-Z）或 0 到 99 的数字。FNC1 模式的组分隔符设置为 0x1D 字符 '\\\\u001D'。如果需要在条码中插入 "<FNC1>" 字符串，请写成 "<\\FNC1>"。ECI 标识符设置为单斜杠加六位数字标识符 "\\000026" - UTF8 ECI 标识符。要禁用当前 ECI 模式并转换为默认 JIS8 零模式，设置 ECI 标识符为 "\\000000"。所有在 ECI 标识符之后的 Unicode 字符将自动编码为正确的字符集。此模式不受 MicroQR 条码支持。

### UTF_16_BEBOM {#UTF-16-BEBOM}
```
public static final QREncodeMode UTF_16_BEBOM
```


使用 UTF8 编码并以第一个 ByteOfMark 字符对代码文本进行编码。某些条码扫描仪可能会出现问题。

### UTF_8_BOM {#UTF-8-BOM}
```
public static final QREncodeMode UTF_8_BOM
```


使用 UTF8 编码并以第一个 ByteOfMark 字符对代码文本进行编码。

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
public static QREncodeMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[QREncodeMode](../../com.aspose.barcode.generation/qrencodemode)
### values() {#values--}
```
public static QREncodeMode[] values()
```




**Returns:**
com.aspose.barcode.generation.QREncodeMode[]
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

