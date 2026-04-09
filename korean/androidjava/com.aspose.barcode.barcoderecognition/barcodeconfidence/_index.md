---
title: BarCodeConfidence
second_title: Aspose.BarCode for Android via Java API Reference
description: 인식 신뢰도 수준을 포함합니다
type: docs
weight: 13
url: /ko/androidjava/com.aspose.barcode.barcoderecognition/barcodeconfidence/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeConfidence
```

인식 신뢰도 수준을 포함합니다

--------------------

> ```
> This sample shows how BarCodeConfidence changed, depending on barcode type
>  
>  //Moderate confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
>  //Strong confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.QR);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
> ```
## 필드

| 필드 | 설명 |
| --- | --- |
| [MODERATE](#MODERATE) | 바코드(주로 1D 바코드)의 인식 신뢰도(체크섬이 약하거나 없을 경우). |
| [NONE](#NONE) | 코드텍스트가 올바르게 인식되지 않았거나 바코드가 가능한 fakeBarCodeExtendedParameters 로 감지된 경우의 인식 신뢰도. |
| [STRONG](#STRONG) | Reed\\u2013Solomon과 같은 BCH 코드로 확인된 인식 신뢰도. |
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MODERATE {#MODERATE}
```
public static final int MODERATE
```


바코드(주로 1D 바코드)의 인식 신뢰도(체크섬이 약하거나 없을 경우). 신뢰도가 낮으면 코드텍스트에 오인식이 발생하거나 가짜 인식이 포함될 수 있습니다.

### NONE {#NONE}
```
public static final int NONE
```


코드텍스트가 올바르게 인식되지 않았거나 바코드가 가능한 fakeBarCodeExtendedParameters 로 감지된 경우의 인식 신뢰도.

### STRONG {#STRONG}
```
public static final int STRONG
```


Reed\\u2013Solomon과 같은 BCH 코드로 확인된 인식 신뢰도. 읽은 코드텍스트에 오류나 가짜 인식이 없어야 합니다.

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

