---
title: MaxiCodeCodetext
second_title: Aspose.BarCode for Android via Java API Reference
description: MaxiCode 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스.
type: docs
weight: 25
url: /ko/androidjava/com.aspose.barcode.complexbarcode/maxicodecodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public abstract class MaxiCodeCodetext implements IComplexCodetext
```

MaxiCode 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스.

이 샘플은 원시 MaxiCode 코덱스트를 MaxiCodeCodetext 인스턴스로 디코딩하는 방법을 보여줍니다.

```

 BarCodeReader reader = new BarCodeReader("test.png", DecodeType.MAXI_CODE);
 for (BarCodeResult result : reader.readBarCodes())
 {
      MaxiCodeCodetext resultMaxiCodeCodetext = ComplexCodetextReader.tryDecodeMaxiCode(result.getExtended().getMaxiCode().getMode(), result.getCodeText());
      System.out.println("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
      System.out.println("MaxiCode mode: " + resultMaxiCodeCodetext.getMode());
      System.out.println("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
 }
 
```
## Constructors

| Constructor | 설명 |
| --- | --- |
| [MaxiCodeCodetext()](#MaxiCodeCodetext--) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | 바코드 유형을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | 코드텍스트를 구성합니다. |
| [getECIEncoding()](#getECIEncoding--) | ECI 인코딩을 가져옵니다. |
| [getEncodeMode()](#getEncodeMode--) | MaxiCode 인코드 모드를 가져옵니다. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | MaxiCode 인코드 모드를 가져옵니다. |
| [getMode()](#getMode--) | MaxiCode 모드를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 구성된 코드텍스트에서 인스턴스를 초기화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI 인코딩을 설정합니다. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | MaxiCode 인코드 모드를 설정합니다. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | MaxiCode 인코드 모드를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeCodetext() {#MaxiCodeCodetext--}
```
public MaxiCodeCodetext()
```


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
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


바코드 유형을 가져옵니다.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public abstract String getConstructedCodetext()
```


코드텍스트를 구성합니다.

**Returns:**
java.lang.String - 구성된 코드텍스트
### getECIEncoding() {#getECIEncoding--}
```
public final int getECIEncoding()
```


ECI 인코딩을 가져옵니다. MaxiCodeEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1

**Returns:**
int - ECI 인코딩.
### getEncodeMode() {#getEncodeMode--}
```
public final MaxiCodeEncodeMode getEncodeMode()
```


MaxiCode 인코드 모드를 가져옵니다. 기본값: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMaxiCodeEncodeMode() {#getMaxiCodeEncodeMode--}
```
public final MaxiCodeEncodeMode getMaxiCodeEncodeMode()
```


MaxiCode 인코드 모드를 가져옵니다. 기본값: Auto.

**Returns:**
[MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) - a MaxiCode encode mode.
### getMode() {#getMode--}
```
public abstract int getMode()
```


MaxiCode 모드를 가져옵니다.

**Returns:**
int - MaxiCode 모드
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public abstract void initFromString(String constructedCodetext)
```


구성된 코드텍스트에서 인스턴스를 초기화합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| constructedCodetext | java.lang.String | 구성된 코드텍스트. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setECIEncoding(int value) {#setECIEncoding-int-}
```
public final void setECIEncoding(int value)
```


ECI 인코딩을 설정합니다. MaxiCodeEncodeMode가 Auto인 경우에 사용됩니다. 기본값: ISO-8859-1

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int | ECI 인코딩. |

### setEncodeMode(MaxiCodeEncodeMode value) {#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setEncodeMode(MaxiCodeEncodeMode value)
```


MaxiCode 인코드 모드를 설정합니다. 기본값: Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | MaxiCode 인코드 모드. |

### setMaxiCodeEncodeMode(MaxiCodeEncodeMode value) {#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-}
```
public final void setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)
```


MaxiCode 인코드 모드를 설정합니다. 기본값: Auto.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [MaxiCodeEncodeMode](../../com.aspose.barcode.generation/maxicodeencodemode) | MaxiCode 인코드 모드. |

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

