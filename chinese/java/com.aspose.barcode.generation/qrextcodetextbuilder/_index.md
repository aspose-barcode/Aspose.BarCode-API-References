---
title: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for Java API Reference"
description: 
type: docs
weight: 61
url: /zh/java/com.aspose.barcode.generation/qrextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class QrExtCodetextBuilder extends ExtCodetextBuilder
```

用于 EncodeMode 的 ExtendedCodetext 模式的 2D QR 条码的扩展代码文本生成器

使用 BarcodeGenerator 的 TwoDDisplayText 属性来设置可见文本，以去除管理字符。

此示例展示了如何在扩展模式中使用 FNC1 的第一个位置。

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1FirstPosition();
 textBuilder.addPlainCodetext("000%89%%0");
 textBuilder.addFNC1GroupSeparator();
 textBuilder.addPlainCodetext("12345<FNC1>");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```

此示例展示了如何在扩展模式中使用 FNC1 的第二个位置。

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addFNC1SecondPosition("12");
 textBuilder.addPlainCodetext("TRUE3456");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```

此示例展示了如何在扩展模式中使用多 ECI 模式。

```

 //create codetext
 QrExtCodetextBuilder textBuilder = new QrExtCodetextBuilder();
 textBuilder.addECICodetext(ECIEncodings.WIN_1251, "Will");
 textBuilder.addECICodetext(ECIEncodings.UTF_8, "Right");
 textBuilder.addECICodetext(ECIEncodings.UTF_16_BE, "Power");
 textBuilder.addPlainCodetext("t\\e\\\\st");
 textBuilder.addCodetextWithCompactionMode(QrExtCompactionMode.ALPHA_NUMERIC, "ASPOSE2001");
 textBuilder.addCodetextWithCompactionMode(QrExtCompactionMode.NUMERIC, "20012026");
 //generate codetext
 String codetext = textBuilder.getExtendedCodetext();
 //generate
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR);
 generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.EXTENDED_CODETEXT);
 generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LEVEL_L);
 generator.setCodeText(codetext);
 generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text");
 generator.save("test.bmp");
 
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [QrExtCodetextBuilder()](#QrExtCodetextBuilder--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)](#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-) | 将具有指定 QR 紧凑模式的代码文本添加到扩展代码文本项中。 |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | 添加带有扩展通道标识符的 codetext |
| [addFNC1FirstPosition()](#addFNC1FirstPosition--) | 在第一个位置设置 FNC1。 |
| [addFNC1GroupSeparator()](#addFNC1GroupSeparator--) | 将组分隔符 (GS - '\\\\\\u001D') 添加到扩展代码文本项中 |
| [addFNC1SecondPosition(String codetext)](#addFNC1SecondPosition-java.lang.String-) | 在第二个位置设置 FNC1。 |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | 向扩展 codetext 项目添加普通 codetext |
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
### QrExtCodetextBuilder() {#QrExtCodetextBuilder--}
```
public QrExtCodetextBuilder()
```


### addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext) {#addCodetextWithCompactionMode-com.aspose.barcode.generation.QrExtCompactionMode-java.lang.String-}
```
public final void addCodetextWithCompactionMode(QrExtCompactionMode mode, String codetext)
```


将具有指定 QR 紧凑模式的代码文本添加到扩展代码文本项中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mode | [QrExtCompactionMode](../../com.aspose.barcode.generation/qrextcompactionmode) | 代码文本的 QR 紧凑模式。 |
| codetext | java.lang.String | 以 Unicode 编码的代码文本，作为扩展代码文本项添加。 |

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

### addFNC1FirstPosition() {#addFNC1FirstPosition--}
```
public final void addFNC1FirstPosition()
```


在第一个位置设置 FNC1。如果之前已设置其他 FNC1 模式，则会被替换。

### addFNC1GroupSeparator() {#addFNC1GroupSeparator--}
```
public final void addFNC1GroupSeparator()
```


将组分隔符 (GS - '\\\\\\u001D') 添加到扩展代码文本项中

### addFNC1SecondPosition(String codetext) {#addFNC1SecondPosition-java.lang.String-}
```
public final void addFNC1SecondPosition(String codetext)
```


在第二个位置设置 FNC1。如果之前已设置其他 FNC1 模式，则会被替换。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| codetext | java.lang.String | 第二个位置的 FNC1 值。该值必须是 a‑z 或 A‑Z 的单个字母，或 00 到 99 的两位数字。 |

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

