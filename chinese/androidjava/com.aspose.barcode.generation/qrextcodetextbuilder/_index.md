---
title: QrExtCodetextBuilder
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 用于 2D QR 条形码的扩展码文本生成器，适用于 QrEncodeMode 的 ExtendedCodetext Mode，使用 BarcodeGenerator 的 TwoDDisplayText 属性来设置可见文本，以去除管理字符。
type: docs
weight: 63
url: /zh/androidjava/com.aspose.barcode.generation/qrextcodetextbuilder/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.generation.ExtCodetextBuilder](../../com.aspose.barcode.generation/extcodetextbuilder)
```
public class QrExtCodetextBuilder extends ExtCodetextBuilder
```

Extended codetext generator for 2D QR barcodes for ExtendedCodetext Mode of QrEncodeMode Use TwoDDisplayText property of BarcodeGenerator to set visible text to removing managing characters. This sample shows how to use FNC1 first position in Extended Mode: QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder(); lTextBuilder.addFNC1FirstPosition(); lTextBuilder.addPlainCodetext("000%89%%0"); lTextBuilder.addFNC1GroupSeparator(); lTextBuilder.addPlainCodetext("12345<FNC1>"); //generate codetext String lCodetext = lTextBuilder.getExtendedCodetext(); //generate BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR); generator.getParameters().getBarcode().getQR().setQrEncodeMode(QREncodeMode.ExtendedCodetext); generator.getParameters().getBarcode().getQR().setQrErrorLevel(QRErrorLevel.LevelL); generator.setCodeText(lCodetext); generator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("test.bmp"); This sample shows how to use FNC1 second position in Extended Mode. //create codetext QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder(); TextBuilder.addFNC1SecondPosition("12"); TextBuilder.addPlainCodetext("TRUE3456"); //generate codetext String lCodetext = lTextBuilder.getExtendedCodetext(); //generate BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR); generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ExtendedCodetext); generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LevelL); generator.setCodeText(lCodetext); generatorgenerator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("test.bmp"); This sample shows how to use multi ECI mode in Extended Mode. //create codetext QrExtCodetextBuilder lTextBuilder = new QrExtCodetextBuilder(); TextBuilder.addECICodetext(ECIEncodings.Win1251, "Will"); TextBuilder.addECICodetext(ECIEncodings.UTF8, "Right"); TextBuilder.addECICodetext(ECIEncodings.UTF16BE, "Power"); TextBuilder.addPlainCodetext(@"t\\e\\\\st"); //generate codetext String lCodetext = lTextBuilder.getExtendedCodetext(); //generate BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR); generator.getParameters().getBarcode().getQR().setEncodeMode(QREncodeMode.ExtendedCodetext); generator.getParameters().getBarcode().getQR().setErrorLevel(QRErrorLevel.LevelL); generator.setCodeText(lCodetext); generatorgenerator.getParameters().getBarcode().getCodeTextParameters().setTwoDDisplayText("My Text"); generator.save("test.bmp");
## Constructors

| Constructor | 描述 |
| --- | --- |
| [QrExtCodetextBuilder()](#QrExtCodetextBuilder--) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | 添加带有扩展通道标识符的代码文本 |
| [addFNC1FirstPosition()](#addFNC1FirstPosition--) | Adds FNC1 in first position to the extended codetext items |
| [addFNC1GroupSeparator()](#addFNC1GroupSeparator--) | Adds Group Separator (GS - '\\\\u001D') to the extended codetext items |
| [addFNC1SecondPosition(String codetext)](#addFNC1SecondPosition-java.lang.String-) | Adds FNC1 in second position to the extended codetext items |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | 向扩展 codetext 项添加普通 codetext |
| [clear()](#clear--) | 清除扩展 codetext 项 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | 从扩展 codetext 列表生成扩展 codetext。 |
| [hashCode()](#hashCode--) |  |
| [isNeedToShieldItemFromPrevECI(int Index)](#isNeedToShieldItemFromPrevECI-int-) | 检查是否需要通过 "\\000000" 屏蔽前一个项目 |
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


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public void addECICodetext(int ECIEncoding, String codetext)
```


添加带有扩展通道标识符的代码文本

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| ECIEncoding | int | 扩展通道标识符 |
| codetext | java.lang.String | 以 Unicode 编码的 Codetext，添加为带有 Extended Channel Identifier 的扩展 codetext 项 |

### addFNC1FirstPosition() {#addFNC1FirstPosition--}
```
public void addFNC1FirstPosition()
```


Adds FNC1 in first position to the extended codetext items

### addFNC1GroupSeparator() {#addFNC1GroupSeparator--}
```
public void addFNC1GroupSeparator()
```


Adds Group Separator (GS - '\\\\u001D') to the extended codetext items

### addFNC1SecondPosition(String codetext) {#addFNC1SecondPosition-java.lang.String-}
```
public void addFNC1SecondPosition(String codetext)
```


Adds FNC1 in second position to the extended codetext items

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| codetext | java.lang.String | 第二位置的 FNC1 值 |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


向扩展 codetext 项添加普通 codetext

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| codetext | java.lang.String | 以 Unicode 编码的 Codetext，添加为扩展 codetext 项 |

### clear() {#clear--}
```
public void clear()
```


清除扩展 codetext 项

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


从扩展 codetext 列表生成扩展 codetext。

**Returns:**
java.lang.String - 作为字符串的扩展 codetext
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNeedToShieldItemFromPrevECI(int Index) {#isNeedToShieldItemFromPrevECI-int-}
```
public boolean isNeedToShieldItemFromPrevECI(int Index)
```


检查是否需要通过 "\\000000" 屏蔽前一个项目

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 索引 | int | m\_List 中的索引 |

**Returns:**
boolean - 是否需要屏蔽
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

