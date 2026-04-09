---
title: HanXinExtCodetextBuilder
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: 
type: docs
weight: 49
url: /id/androidjava/com.aspose.barcode.generation/hanxinextcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public class HanXinExtCodetextBuilder
```

Generator codetext yang diperluas untuk Han Xin Code untuk Mode Diperluas dari HanXinEncodeMode

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

| Constructor | Deskripsi |
| --- | --- |
| [HanXinExtCodetextBuilder()](#HanXinExtCodetextBuilder--) |  |
## Methods

| Method | Deskripsi |
| --- | --- |
| [addAuto(String text)](#addAuto-java.lang.String-) | Menambahkan fragmen codetext dalam mode Otomatis |
| [addBinary(String text)](#addBinary-java.lang.String-) | Menambahkan fragmen codetext dalam mode Biner |
| [addCommonChineseRegionOne(String text)](#addCommonChineseRegionOne-java.lang.String-) | Menambahkan fragmen codetext dalam mode Wilayah Cina Umum Satu |
| [addCommonChineseRegionTwo(String text)](#addCommonChineseRegionTwo-java.lang.String-) | Menambahkan fragmen codetext dalam mode Wilayah Cina Umum Dua |
| [addECI(String text, int encoding)](#addECI-java.lang.String-int-) | Menambahkan fragmen codetext dalam mode ECI |
| [addGB18030FourByte(String text)](#addGB18030FourByte-java.lang.String-) | Menambahkan fragmen codetext dalam mode GB18030 Empat Byte |
| [addGB18030TwoByte(String text)](#addGB18030TwoByte-java.lang.String-) | Menambahkan fragmen codetext dalam mode GB18030 Dua Byte |
| [addGS1(String text)](#addGS1-java.lang.String-) | Menambahkan fragmen codetext dalam mode GS1 |
| [addNumeric(String text)](#addNumeric-java.lang.String-) | Menambahkan fragmen codetext dalam mode Numerik |
| [addText(String text)](#addText-java.lang.String-) | Menambahkan fragmen codetext dalam mode Teks |
| [addURI(String text)](#addURI-java.lang.String-) | Menambahkan fragmen codetext dalam mode URI |
| [addUnicode(String text)](#addUnicode-java.lang.String-) | Menambahkan fragmen codetext dalam mode Unicode |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Mengembalikan codetext dari pembuat codetext mode Diperluas |
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


Menambahkan fragmen codetext dalam mode Otomatis

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | String codetext |

### addBinary(String text) {#addBinary-java.lang.String-}
```
public void addBinary(String text)
```


Menambahkan fragmen codetext dalam mode Biner

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | String codetext |

### addCommonChineseRegionOne(String text) {#addCommonChineseRegionOne-java.lang.String-}
```
public void addCommonChineseRegionOne(String text)
```


Menambahkan fragmen codetext dalam mode Wilayah Cina Umum Satu

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | String codetext |

### addCommonChineseRegionTwo(String text) {#addCommonChineseRegionTwo-java.lang.String-}
```
public void addCommonChineseRegionTwo(String text)
```


Menambahkan fragmen codetext dalam mode Wilayah Cina Umum Dua

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | String codetext |

### addECI(String text, int encoding) {#addECI-java.lang.String-int-}
```
public void addECI(String text, int encoding)
```


Menambahkan fragmen codetext dalam mode ECI

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | String codetext |
| pengkodean | int | Enkoding ECI dalam format integer |

### addGB18030FourByte(String text) {#addGB18030FourByte-java.lang.String-}
```
public void addGB18030FourByte(String text)
```


Menambahkan fragmen codetext dalam mode GB18030 Empat Byte

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | String codetext |

### addGB18030TwoByte(String text) {#addGB18030TwoByte-java.lang.String-}
```
public void addGB18030TwoByte(String text)
```


Menambahkan fragmen codetext dalam mode GB18030 Dua Byte

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | String codetext |

### addGS1(String text) {#addGS1-java.lang.String-}
```
public void addGS1(String text)
```


Menambahkan fragmen codetext dalam mode GS1

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | String codetext |

### addNumeric(String text) {#addNumeric-java.lang.String-}
```
public void addNumeric(String text)
```


Menambahkan fragmen codetext dalam mode Numerik

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | String codetext |

### addText(String text) {#addText-java.lang.String-}
```
public void addText(String text)
```


Menambahkan fragmen codetext dalam mode Teks

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | String codetext |

### addURI(String text) {#addURI-java.lang.String-}
```
public void addURI(String text)
```


Menambahkan fragmen codetext dalam mode URI

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | String codetext |

### addUnicode(String text) {#addUnicode-java.lang.String-}
```
public void addUnicode(String text)
```


Menambahkan fragmen codetext dalam mode Unicode

**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| teks | java.lang.String | String codetext |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Deskripsi |
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


Mengembalikan codetext dari pembuat codetext mode Diperluas

**Returns:**
java.lang.String - Codetext dalam mode Diperluas
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
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

