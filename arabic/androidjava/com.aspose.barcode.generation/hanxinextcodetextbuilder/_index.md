---
title: HanXinExtCodetextBuilder
second_title: مرجع Aspose.BarCode لنظام Android عبر Java API
description: 
type: docs
weight: 49
url: /ar/androidjava/com.aspose.barcode.generation/hanxinextcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public class HanXinExtCodetextBuilder
```

مولد نص الشيفرة الموسع لرمز Han Xin Code للوضع الموسع من HanXinEncodeMode

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

| Constructor | الوصف |
| --- | --- |
| [HanXinExtCodetextBuilder()](#HanXinExtCodetextBuilder--) |  |
## Methods

| Method | الوصف |
| --- | --- |
| [addAuto(String text)](#addAuto-java.lang.String-) | يضيف جزء نص الشيفرة في الوضع التلقائي |
| [addBinary(String text)](#addBinary-java.lang.String-) | يضيف جزء نص الشيفرة في وضع الثنائي |
| [addCommonChineseRegionOne(String text)](#addCommonChineseRegionOne-java.lang.String-) | يضيف جزء نص الشيفرة في وضع المنطقة الصينية المشتركة الأولى |
| [addCommonChineseRegionTwo(String text)](#addCommonChineseRegionTwo-java.lang.String-) | يضيف جزء نص الشيفرة في وضع المنطقة الصينية المشتركة الثانية |
| [addECI(String text, int encoding)](#addECI-java.lang.String-int-) | يضيف جزء نص الشيفرة في وضع ECI |
| [addGB18030FourByte(String text)](#addGB18030FourByte-java.lang.String-) | يضيف جزء نص الشيفرة في وضع GB18030 بأربعة بايت |
| [addGB18030TwoByte(String text)](#addGB18030TwoByte-java.lang.String-) | يضيف جزء نص الشيفرة في وضع GB18030 بايتين |
| [addGS1(String text)](#addGS1-java.lang.String-) | يضيف جزء نص الشيفرة في وضع GS1 |
| [addNumeric(String text)](#addNumeric-java.lang.String-) | يضيف جزء نص الشيفرة في الوضع الرقمي |
| [addText(String text)](#addText-java.lang.String-) | يضيف جزء نص الشيفرة في وضع النص |
| [addURI(String text)](#addURI-java.lang.String-) | يضيف جزء نص الشيفرة في وضع URI |
| [addUnicode(String text)](#addUnicode-java.lang.String-) | يضيف جزء نص الشيفرة في وضع Unicode |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | يعيد نص الشيفرة من مُنشئ نص الشيفرة في الوضع الموسع |
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


يضيف جزء نص الشيفرة في الوضع التلقائي

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| text | java.lang.String | سلسلة نص الشيفرة |

### addBinary(String text) {#addBinary-java.lang.String-}
```
public void addBinary(String text)
```


يضيف جزء نص الشيفرة في وضع الثنائي

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| text | java.lang.String | سلسلة نص الشيفرة |

### addCommonChineseRegionOne(String text) {#addCommonChineseRegionOne-java.lang.String-}
```
public void addCommonChineseRegionOne(String text)
```


يضيف جزء نص الشيفرة في وضع المنطقة الصينية المشتركة الأولى

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| text | java.lang.String | سلسلة نص الشيفرة |

### addCommonChineseRegionTwo(String text) {#addCommonChineseRegionTwo-java.lang.String-}
```
public void addCommonChineseRegionTwo(String text)
```


يضيف جزء نص الشيفرة في وضع المنطقة الصينية المشتركة الثانية

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| text | java.lang.String | سلسلة نص الشيفرة |

### addECI(String text, int encoding) {#addECI-java.lang.String-int-}
```
public void addECI(String text, int encoding)
```


يضيف جزء نص الشيفرة في وضع ECI

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| text | java.lang.String | سلسلة نص الشيفرة |
| الترميز | int | ترميز ECI بصيغة عدد صحيح |

### addGB18030FourByte(String text) {#addGB18030FourByte-java.lang.String-}
```
public void addGB18030FourByte(String text)
```


يضيف جزء نص الشيفرة في وضع GB18030 بأربعة بايت

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| text | java.lang.String | سلسلة نص الشيفرة |

### addGB18030TwoByte(String text) {#addGB18030TwoByte-java.lang.String-}
```
public void addGB18030TwoByte(String text)
```


يضيف جزء نص الشيفرة في وضع GB18030 بايتين

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| text | java.lang.String | سلسلة نص الشيفرة |

### addGS1(String text) {#addGS1-java.lang.String-}
```
public void addGS1(String text)
```


يضيف جزء نص الشيفرة في وضع GS1

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| text | java.lang.String | سلسلة نص الشيفرة |

### addNumeric(String text) {#addNumeric-java.lang.String-}
```
public void addNumeric(String text)
```


يضيف جزء نص الشيفرة في الوضع الرقمي

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| text | java.lang.String | سلسلة نص الشيفرة |

### addText(String text) {#addText-java.lang.String-}
```
public void addText(String text)
```


يضيف جزء نص الشيفرة في وضع النص

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| text | java.lang.String | سلسلة نص الشيفرة |

### addURI(String text) {#addURI-java.lang.String-}
```
public void addURI(String text)
```


يضيف جزء نص الشيفرة في وضع URI

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| text | java.lang.String | سلسلة نص الشيفرة |

### addUnicode(String text) {#addUnicode-java.lang.String-}
```
public void addUnicode(String text)
```


يضيف جزء نص الشيفرة في وضع Unicode

**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| text | java.lang.String | سلسلة نص الشيفرة |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | الوصف |
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


يعيد نص الشيفرة من مُنشئ نص الشيفرة في الوضع الموسع

**Returns:**
java.lang.String - نص الشيفرة في الوضع الموسع
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
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

