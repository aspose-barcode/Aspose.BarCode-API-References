---
title: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode Android için Java API Referansı"
description: 
type: docs
weight: 48
url: /tr/androidjava/com.aspose.barcode.generation/hanxinextcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public class HanXinExtCodetextBuilder
```

Han Xin Code için HanXinEncodeMode'un Genişletilmiş Modu için genişletilmiş kod metni oluşturucu

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
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HanXinExtCodetextBuilder()](#HanXinExtCodetextBuilder--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addAuto(String text)](#addAuto-java.lang.String-) | Auto modunda kod metni parçacığı ekler |
| [addBinary(String text)](#addBinary-java.lang.String-) | Binary modunda kod metni parçacığı ekler |
| [addCommonChineseRegionOne(String text)](#addCommonChineseRegionOne-java.lang.String-) | Common Chinese Region One modunda kod metni parçacığı ekler |
| [addCommonChineseRegionTwo(String text)](#addCommonChineseRegionTwo-java.lang.String-) | Common Chinese Region Two modunda kod metni parçacığı ekler |
| [addECI(String text, int encoding)](#addECI-java.lang.String-int-) | ECI modunda kod metni parçacığı ekler |
| [addGB18030FourByte(String text)](#addGB18030FourByte-java.lang.String-) | GB18030 Four Byte modunda kod metni parçacığı ekler |
| [addGB18030TwoByte(String text)](#addGB18030TwoByte-java.lang.String-) | GB18030 Two Byte modunda kod metni parçacığı ekler |
| [addGS1(String text)](#addGS1-java.lang.String-) | GS1 modunda kod metni parçacığı ekler |
| [addNumeric(String text)](#addNumeric-java.lang.String-) | Numeric modunda kod metni parçacığı ekler |
| [addText(String text)](#addText-java.lang.String-) | Text modunda kod metni parçacığı ekler |
| [addURI(String text)](#addURI-java.lang.String-) | URI modunda kod metni parçacığı ekler |
| [addUnicode(String text)](#addUnicode-java.lang.String-) | Unicode modunda kod metni parçacığı ekler |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | Genişletilmiş mod kod metni oluşturucusundan kod metnini döndürür |
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


Auto modunda kod metni parçacığı ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Kod metni dizesi |

### addBinary(String text) {#addBinary-java.lang.String-}
```
public void addBinary(String text)
```


Binary modunda kod metni parçacığı ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Kod metni dizesi |

### addCommonChineseRegionOne(String text) {#addCommonChineseRegionOne-java.lang.String-}
```
public void addCommonChineseRegionOne(String text)
```


Common Chinese Region One modunda kod metni parçacığı ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Kod metni dizesi |

### addCommonChineseRegionTwo(String text) {#addCommonChineseRegionTwo-java.lang.String-}
```
public void addCommonChineseRegionTwo(String text)
```


Common Chinese Region Two modunda kod metni parçacığı ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Kod metni dizesi |

### addECI(String text, int encoding) {#addECI-java.lang.String-int-}
```
public void addECI(String text, int encoding)
```


ECI modunda kod metni parçacığı ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Kod metni dizesi |
| encoding | int | Tam sayı formatında ECI kodlaması |

### addGB18030FourByte(String text) {#addGB18030FourByte-java.lang.String-}
```
public void addGB18030FourByte(String text)
```


GB18030 Four Byte modunda kod metni parçacığı ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Kod metni dizesi |

### addGB18030TwoByte(String text) {#addGB18030TwoByte-java.lang.String-}
```
public void addGB18030TwoByte(String text)
```


GB18030 Two Byte modunda kod metni parçacığı ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Kod metni dizesi |

### addGS1(String text) {#addGS1-java.lang.String-}
```
public void addGS1(String text)
```


GS1 modunda kod metni parçacığı ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Kod metni dizesi |

### addNumeric(String text) {#addNumeric-java.lang.String-}
```
public void addNumeric(String text)
```


Numeric modunda kod metni parçacığı ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Kod metni dizesi |

### addText(String text) {#addText-java.lang.String-}
```
public void addText(String text)
```


Text modunda kod metni parçacığı ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Kod metni dizesi |

### addURI(String text) {#addURI-java.lang.String-}
```
public void addURI(String text)
```


URI modunda kod metni parçacığı ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Kod metni dizesi |

### addUnicode(String text) {#addUnicode-java.lang.String-}
```
public void addUnicode(String text)
```


Unicode modunda kod metni parçacığı ekler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | java.lang.String | Kod metni dizesi |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Genişletilmiş mod kod metni oluşturucusundan kod metnini döndürür

**Returns:**
java.lang.String - Genişletilmiş modda kod metni
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

