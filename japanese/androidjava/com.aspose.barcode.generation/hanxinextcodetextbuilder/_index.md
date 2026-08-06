---
title: HanXinExtCodetextBuilder
second_title: Aspose.BarCode for Android via Java API Reference
description: 
type: docs
weight: 49
url: /ja/androidjava/com.aspose.barcode.generation/hanxinextcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public class HanXinExtCodetextBuilder
```

HanXinEncodeMode の拡張モード用 Han Xin コードの拡張コードテキストジェネレータ

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

| Constructor | Description |
| --- | --- |
| [HanXinExtCodetextBuilder()](#HanXinExtCodetextBuilder--) |  |
## Methods

| Method | Description |
| --- | --- |
| [addAuto(String text)](#addAuto-java.lang.String-) | Auto モードでコードテキストフラグメントを追加します |
| [addBinary(String text)](#addBinary-java.lang.String-) | Binary モードでコードテキストフラグメントを追加します |
| [addCommonChineseRegionOne(String text)](#addCommonChineseRegionOne-java.lang.String-) | Common Chinese Region One モードでコードテキストフラグメントを追加します |
| [addCommonChineseRegionTwo(String text)](#addCommonChineseRegionTwo-java.lang.String-) | Common Chinese Region Two モードでコードテキストフラグメントを追加します |
| [addECI(String text, int encoding)](#addECI-java.lang.String-int-) | ECI モードでコードテキストフラグメントを追加します |
| [addGB18030FourByte(String text)](#addGB18030FourByte-java.lang.String-) | GB18030 Four Byte モードでコードテキストフラグメントを追加します |
| [addGB18030TwoByte(String text)](#addGB18030TwoByte-java.lang.String-) | GB18030 Two Byte モードでコードテキストフラグメントを追加します |
| [addGS1(String text)](#addGS1-java.lang.String-) | GS1 モードでコードテキストフラグメントを追加します |
| [addNumeric(String text)](#addNumeric-java.lang.String-) | Numeric モードでコードテキストフラグメントを追加します |
| [addText(String text)](#addText-java.lang.String-) | Text モードでコードテキストフラグメントを追加します |
| [addURI(String text)](#addURI-java.lang.String-) | URI モードでコードテキストフラグメントを追加します |
| [addUnicode(String text)](#addUnicode-java.lang.String-) | Unicode モードでコードテキストフラグメントを追加します |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | 拡張モードのコードテキストビルダーからコードテキストを返します |
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


Auto モードでコードテキストフラグメントを追加します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | コードテキスト文字列 |

### addBinary(String text) {#addBinary-java.lang.String-}
```
public void addBinary(String text)
```


Binary モードでコードテキストフラグメントを追加します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | コードテキスト文字列 |

### addCommonChineseRegionOne(String text) {#addCommonChineseRegionOne-java.lang.String-}
```
public void addCommonChineseRegionOne(String text)
```


Common Chinese Region One モードでコードテキストフラグメントを追加します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | コードテキスト文字列 |

### addCommonChineseRegionTwo(String text) {#addCommonChineseRegionTwo-java.lang.String-}
```
public void addCommonChineseRegionTwo(String text)
```


Common Chinese Region Two モードでコードテキストフラグメントを追加します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | コードテキスト文字列 |

### addECI(String text, int encoding) {#addECI-java.lang.String-int-}
```
public void addECI(String text, int encoding)
```


ECI モードでコードテキストフラグメントを追加します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | コードテキスト文字列 |
| エンコーディング | int | 整数形式の ECI エンコーディング |

### addGB18030FourByte(String text) {#addGB18030FourByte-java.lang.String-}
```
public void addGB18030FourByte(String text)
```


GB18030 Four Byte モードでコードテキストフラグメントを追加します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | コードテキスト文字列 |

### addGB18030TwoByte(String text) {#addGB18030TwoByte-java.lang.String-}
```
public void addGB18030TwoByte(String text)
```


GB18030 Two Byte モードでコードテキストフラグメントを追加します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | コードテキスト文字列 |

### addGS1(String text) {#addGS1-java.lang.String-}
```
public void addGS1(String text)
```


GS1 モードでコードテキストフラグメントを追加します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | コードテキスト文字列 |

### addNumeric(String text) {#addNumeric-java.lang.String-}
```
public void addNumeric(String text)
```


Numeric モードでコードテキストフラグメントを追加します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | コードテキスト文字列 |

### addText(String text) {#addText-java.lang.String-}
```
public void addText(String text)
```


Text モードでコードテキストフラグメントを追加します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | コードテキスト文字列 |

### addURI(String text) {#addURI-java.lang.String-}
```
public void addURI(String text)
```


URI モードでコードテキストフラグメントを追加します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | コードテキスト文字列 |

### addUnicode(String text) {#addUnicode-java.lang.String-}
```
public void addUnicode(String text)
```


Unicode モードでコードテキストフラグメントを追加します

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | コードテキスト文字列 |

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


拡張モードのコードテキストビルダーからコードテキストを返します

**Returns:**
java.lang.String - 拡張モードのコードテキスト
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

