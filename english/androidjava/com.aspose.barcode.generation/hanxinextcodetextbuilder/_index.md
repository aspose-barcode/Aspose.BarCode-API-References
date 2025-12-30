---
title: HanXinExtCodetextBuilder
second_title: Aspose.BarCode for Android via Java API Reference
description: 
type: docs
weight: 49
url: /androidjava/com.aspose.barcode.generation/hanxinextcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public class HanXinExtCodetextBuilder
```

Extended codetext generator for Han Xin Code for Extended Mode of HanXinEncodeMode

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
>  BarcodeGenerator bg = new BarcodeGenerator(EncodeTypes.HanXin, str);
>  bg.getParameters().getBarcode().getHanXin().setHanXinEncodeMode(HanXinEncodeMode.EXTENDED);
>  Bitmap img = bg.generateBarCodeImage();
>  BarCodeReader r = new BarCodeReader(img, DecodeType.HAN_XIN))
>  BarcodeResult[] found = r.readBarCodes();
>  Assert.assertEquals(1, found.length);
>  Assert.assertEquals(expectedStr, found[0].getCodeText());
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [HanXinExtCodetextBuilder()](#HanXinExtCodetextBuilder--) |  |
## Methods

| Method | Description |
| --- | --- |
| [addAuto(String text)](#addAuto-java.lang.String-) | Adds codetext fragment in Auto mode |
| [addBinary(String text)](#addBinary-java.lang.String-) | Adds codetext fragment in Binary mode |
| [addCommonChineseRegionOne(String text)](#addCommonChineseRegionOne-java.lang.String-) | Adds codetext fragment in Common Chinese Region One mode |
| [addCommonChineseRegionTwo(String text)](#addCommonChineseRegionTwo-java.lang.String-) | Adds codetext fragment in Common Chinese Region Two mode |
| [addECI(String text, int encoding)](#addECI-java.lang.String-int-) | Adds codetext fragment in ECI mode |
| [addGB18030FourByte(String text)](#addGB18030FourByte-java.lang.String-) | Adds codetext fragment in GB18030 Four Byte mode |
| [addGB18030TwoByte(String text)](#addGB18030TwoByte-java.lang.String-) | Adds codetext fragment in GB18030 Two Byte mode |
| [addGS1(String text)](#addGS1-java.lang.String-) | Adds codetext fragment in GS1 mode |
| [addNumeric(String text)](#addNumeric-java.lang.String-) | Adds codetext fragment in Numeric mode |
| [addText(String text)](#addText-java.lang.String-) | Adds codetext fragment in Text mode |
| [addURI(String text)](#addURI-java.lang.String-) | Adds codetext fragment in URI mode |
| [addUnicode(String text)](#addUnicode-java.lang.String-) | Adds codetext fragment in Unicode mode |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Returns codetext from Extended mode codetext builder |
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


Adds codetext fragment in Auto mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Codetext string |

### addBinary(String text) {#addBinary-java.lang.String-}
```
public void addBinary(String text)
```


Adds codetext fragment in Binary mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Codetext string |

### addCommonChineseRegionOne(String text) {#addCommonChineseRegionOne-java.lang.String-}
```
public void addCommonChineseRegionOne(String text)
```


Adds codetext fragment in Common Chinese Region One mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Codetext string |

### addCommonChineseRegionTwo(String text) {#addCommonChineseRegionTwo-java.lang.String-}
```
public void addCommonChineseRegionTwo(String text)
```


Adds codetext fragment in Common Chinese Region Two mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Codetext string |

### addECI(String text, int encoding) {#addECI-java.lang.String-int-}
```
public void addECI(String text, int encoding)
```


Adds codetext fragment in ECI mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Codetext string |
| encoding | int | ECI encoding in integer format |

### addGB18030FourByte(String text) {#addGB18030FourByte-java.lang.String-}
```
public void addGB18030FourByte(String text)
```


Adds codetext fragment in GB18030 Four Byte mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Codetext string |

### addGB18030TwoByte(String text) {#addGB18030TwoByte-java.lang.String-}
```
public void addGB18030TwoByte(String text)
```


Adds codetext fragment in GB18030 Two Byte mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Codetext string |

### addGS1(String text) {#addGS1-java.lang.String-}
```
public void addGS1(String text)
```


Adds codetext fragment in GS1 mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Codetext string |

### addNumeric(String text) {#addNumeric-java.lang.String-}
```
public void addNumeric(String text)
```


Adds codetext fragment in Numeric mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Codetext string |

### addText(String text) {#addText-java.lang.String-}
```
public void addText(String text)
```


Adds codetext fragment in Text mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Codetext string |

### addURI(String text) {#addURI-java.lang.String-}
```
public void addURI(String text)
```


Adds codetext fragment in URI mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Codetext string |

### addUnicode(String text) {#addUnicode-java.lang.String-}
```
public void addUnicode(String text)
```


Adds codetext fragment in Unicode mode

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Codetext string |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


Returns codetext from Extended mode codetext builder

**Returns:**
java.lang.String - Codetext in Extended mode
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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

