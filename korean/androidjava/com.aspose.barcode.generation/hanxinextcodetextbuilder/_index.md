---
title: HanXinExtCodetextBuilder
second_title: Aspose.BarCode for Android via Java API Reference
description: 
type: docs
weight: 49
url: /ko/androidjava/com.aspose.barcode.generation/hanxinextcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public class HanXinExtCodetextBuilder
```

HanXinEncodeMode의 확장 모드를 위한 Han Xin 코드 확장 코드텍스트 생성기

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

| Constructor | 설명 |
| --- | --- |
| [HanXinExtCodetextBuilder()](#HanXinExtCodetextBuilder--) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [addAuto(String text)](#addAuto-java.lang.String-) | 자동 모드에서 코드텍스트 조각을 추가합니다 |
| [addBinary(String text)](#addBinary-java.lang.String-) | 이진 모드에서 코드텍스트 조각을 추가합니다 |
| [addCommonChineseRegionOne(String text)](#addCommonChineseRegionOne-java.lang.String-) | 공통 중국 지역 1 모드에서 코드텍스트 조각을 추가합니다 |
| [addCommonChineseRegionTwo(String text)](#addCommonChineseRegionTwo-java.lang.String-) | 공통 중국 지역 2 모드에서 코드텍스트 조각을 추가합니다 |
| [addECI(String text, int encoding)](#addECI-java.lang.String-int-) | ECI 모드에서 코드텍스트 조각을 추가합니다 |
| [addGB18030FourByte(String text)](#addGB18030FourByte-java.lang.String-) | GB18030 4바이트 모드에서 코드텍스트 조각을 추가합니다 |
| [addGB18030TwoByte(String text)](#addGB18030TwoByte-java.lang.String-) | GB18030 2바이트 모드에서 코드텍스트 조각을 추가합니다 |
| [addGS1(String text)](#addGS1-java.lang.String-) | GS1 모드에서 코드텍스트 조각을 추가합니다 |
| [addNumeric(String text)](#addNumeric-java.lang.String-) | 숫자 모드에서 코드텍스트 조각을 추가합니다 |
| [addText(String text)](#addText-java.lang.String-) | 텍스트 모드에서 코드텍스트 조각을 추가합니다 |
| [addURI(String text)](#addURI-java.lang.String-) | URI 모드에서 코드텍스트 조각을 추가합니다 |
| [addUnicode(String text)](#addUnicode-java.lang.String-) | 유니코드 모드에서 코드텍스트 조각을 추가합니다 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | 확장 모드 코드텍스트 빌더에서 코드텍스트를 반환합니다 |
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


자동 모드에서 코드텍스트 조각을 추가합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 텍스트 | java.lang.String | 코드텍스트 문자열 |

### addBinary(String text) {#addBinary-java.lang.String-}
```
public void addBinary(String text)
```


이진 모드에서 코드텍스트 조각을 추가합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 텍스트 | java.lang.String | 코드텍스트 문자열 |

### addCommonChineseRegionOne(String text) {#addCommonChineseRegionOne-java.lang.String-}
```
public void addCommonChineseRegionOne(String text)
```


공통 중국 지역 1 모드에서 코드텍스트 조각을 추가합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 텍스트 | java.lang.String | 코드텍스트 문자열 |

### addCommonChineseRegionTwo(String text) {#addCommonChineseRegionTwo-java.lang.String-}
```
public void addCommonChineseRegionTwo(String text)
```


공통 중국 지역 2 모드에서 코드텍스트 조각을 추가합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 텍스트 | java.lang.String | 코드텍스트 문자열 |

### addECI(String text, int encoding) {#addECI-java.lang.String-int-}
```
public void addECI(String text, int encoding)
```


ECI 모드에서 코드텍스트 조각을 추가합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 텍스트 | java.lang.String | 코드텍스트 문자열 |
| 인코딩 | int | 정수 형식의 ECI 인코딩 |

### addGB18030FourByte(String text) {#addGB18030FourByte-java.lang.String-}
```
public void addGB18030FourByte(String text)
```


GB18030 4바이트 모드에서 코드텍스트 조각을 추가합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 텍스트 | java.lang.String | 코드텍스트 문자열 |

### addGB18030TwoByte(String text) {#addGB18030TwoByte-java.lang.String-}
```
public void addGB18030TwoByte(String text)
```


GB18030 2바이트 모드에서 코드텍스트 조각을 추가합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 텍스트 | java.lang.String | 코드텍스트 문자열 |

### addGS1(String text) {#addGS1-java.lang.String-}
```
public void addGS1(String text)
```


GS1 모드에서 코드텍스트 조각을 추가합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 텍스트 | java.lang.String | 코드텍스트 문자열 |

### addNumeric(String text) {#addNumeric-java.lang.String-}
```
public void addNumeric(String text)
```


숫자 모드에서 코드텍스트 조각을 추가합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 텍스트 | java.lang.String | 코드텍스트 문자열 |

### addText(String text) {#addText-java.lang.String-}
```
public void addText(String text)
```


텍스트 모드에서 코드텍스트 조각을 추가합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 텍스트 | java.lang.String | 코드텍스트 문자열 |

### addURI(String text) {#addURI-java.lang.String-}
```
public void addURI(String text)
```


URI 모드에서 코드텍스트 조각을 추가합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 텍스트 | java.lang.String | 코드텍스트 문자열 |

### addUnicode(String text) {#addUnicode-java.lang.String-}
```
public void addUnicode(String text)
```


유니코드 모드에서 코드텍스트 조각을 추가합니다

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 텍스트 | java.lang.String | 코드텍스트 문자열 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 설명 |
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


확장 모드 코드텍스트 빌더에서 코드텍스트를 반환합니다

**Returns:**
java.lang.String - 확장 모드의 코드텍스트
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
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

