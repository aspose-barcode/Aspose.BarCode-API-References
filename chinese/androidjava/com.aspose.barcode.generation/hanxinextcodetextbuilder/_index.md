---
title: HanXinExtCodetextBuilder
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 
type: docs
weight: 49
url: /zh/androidjava/com.aspose.barcode.generation/hanxinextcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public class HanXinExtCodetextBuilder
```

适用于 HanXinEncodeMode 的 Han Xin 码扩展模式的扩展码文本生成器

--------------------

> ```
> //Extended codetext mode
>  //create codetext
>  HanXinExtCodetextBuilder codeTextBuilder = new HanXinExtCodetextBuilder();
>  codeTextBuilder.addGB18030TwoByte("\u6f04");
>  codeTextBuilder.addGB18030FourByte("\u3401");
>  codeTextBuilder.addCommonChineseRegionOne("\u5168");
>  codeTextBuilder.addCommonChineseRegionTwo("\u8785");
>  codeTextBuilder.addNumeric("123");
>  codeTextBuilder.addText("qwe");
>  codeTextBuilder.addUnicode("\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l");
>  codeTextBuilder.addECI("\u0391\u0392\u0393\u0394\u0395", 9);
>  codeTextBuilder.addAuto("abc");
>  codeTextBuilder.addBinary("abc");
>  codeTextBuilder.addURI("backslashes_should_be_doubled\\000555:test");
>  codeTextBuilder.addGS1("(01)03453120000011(17)191125(10)ABCD1234(21)10");
>  String expectedStr = "\u6f04\u3401\u5168\u8785123qwe\u0131nt\u0259\u02c8næ\u0283\u0259n\u0259l\u0391\u0392\u0393\u0394\u0395abcabcbackslashes_should_be_doubled\\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10";
>  //generate codetext
>  String str = codeTextBuilder.getExtendedCodetext();
>  //generate
>  BarcodeGenerator bg = new BarcodeGenerator(EncodeTypes.HAN_XIN, str);
>  bg.getParameters().getBarcode().getHanXin().setEncodeMode(EncodeMode.EXTENDED);
>  BufferedImage img = bg.generateBarCodeImage();
>  BarCodeReader r = new BarCodeReader(img, DecodeType.HAN_XIN))
>  BarcodeResult[] found = r.readBarCodes();
>  Assert.assertEquals(1, found.length);
>  Assert.assertEquals(expectedStr, found[0].getCodeText());
> ```
## Constructors

| Constructor | 描述 |
| --- | --- |
| [HanXinExtCodetextBuilder()](#HanXinExtCodetextBuilder--) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [addAuto(String text)](#addAuto-java.lang.String-) | 在自动模式下添加码文本片段 |
| [addBinary(String text)](#addBinary-java.lang.String-) | 在二进制模式下添加码文本片段 |
| [addCommonChineseRegionOne(String text)](#addCommonChineseRegionOne-java.lang.String-) | 在通用中文区域一模式下添加码文本片段 |
| [addCommonChineseRegionTwo(String text)](#addCommonChineseRegionTwo-java.lang.String-) | 在通用中文区域二模式下添加码文本片段 |
| [addECI(String text, int encoding)](#addECI-java.lang.String-int-) | 在 ECI 模式下添加码文本片段 |
| [addGB18030FourByte(String text)](#addGB18030FourByte-java.lang.String-) | 在 GB18030 四字节模式下添加码文本片段 |
| [addGB18030TwoByte(String text)](#addGB18030TwoByte-java.lang.String-) | 在 GB18030 两字节模式下添加码文本片段 |
| [addGS1(String text)](#addGS1-java.lang.String-) | 在 GS1 模式下添加码文本片段 |
| [addNumeric(String text)](#addNumeric-java.lang.String-) | 在数字模式下添加码文本片段 |
| [addText(String text)](#addText-java.lang.String-) | 在文本模式下添加码文本片段 |
| [addURI(String text)](#addURI-java.lang.String-) | 在 URI 模式下添加码文本片段 |
| [addUnicode(String text)](#addUnicode-java.lang.String-) | 在 Unicode 模式下添加码文本片段 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | 从扩展模式码文本构建器返回码文本 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HanXinExtCodetextBuilder() {#HanXinExtCodetextBuilder--}
```
public HanXinExtCodetextBuilder()
```


### addAuto(String text) {#addAuto-java.lang.String-}
```
public void addAuto(String text)
```


在自动模式下添加码文本片段

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 码文本字符串 |

### addBinary(String text) {#addBinary-java.lang.String-}
```
public void addBinary(String text)
```


在二进制模式下添加码文本片段

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 码文本字符串 |

### addCommonChineseRegionOne(String text) {#addCommonChineseRegionOne-java.lang.String-}
```
public void addCommonChineseRegionOne(String text)
```


在通用中文区域一模式下添加码文本片段

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 码文本字符串 |

### addCommonChineseRegionTwo(String text) {#addCommonChineseRegionTwo-java.lang.String-}
```
public void addCommonChineseRegionTwo(String text)
```


在通用中文区域二模式下添加码文本片段

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 码文本字符串 |

### addECI(String text, int encoding) {#addECI-java.lang.String-int-}
```
public void addECI(String text, int encoding)
```


在 ECI 模式下添加码文本片段

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 码文本字符串 |
| 编码 | int | ECI 编码（整数格式） |

### addGB18030FourByte(String text) {#addGB18030FourByte-java.lang.String-}
```
public void addGB18030FourByte(String text)
```


在 GB18030 四字节模式下添加码文本片段

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 码文本字符串 |

### addGB18030TwoByte(String text) {#addGB18030TwoByte-java.lang.String-}
```
public void addGB18030TwoByte(String text)
```


在 GB18030 两字节模式下添加码文本片段

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 码文本字符串 |

### addGS1(String text) {#addGS1-java.lang.String-}
```
public void addGS1(String text)
```


在 GS1 模式下添加码文本片段

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 码文本字符串 |

### addNumeric(String text) {#addNumeric-java.lang.String-}
```
public void addNumeric(String text)
```


在数字模式下添加码文本片段

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 码文本字符串 |

### addText(String text) {#addText-java.lang.String-}
```
public void addText(String text)
```


在文本模式下添加码文本片段

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 码文本字符串 |

### addURI(String text) {#addURI-java.lang.String-}
```
public void addURI(String text)
```


在 URI 模式下添加码文本片段

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 码文本字符串 |

### addUnicode(String text) {#addUnicode-java.lang.String-}
```
public void addUnicode(String text)
```


在 Unicode 模式下添加码文本片段

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String | 码文本字符串 |

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


从扩展模式码文本构建器返回码文本

**Returns:**
java.lang.String - 扩展模式下的码文本
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

