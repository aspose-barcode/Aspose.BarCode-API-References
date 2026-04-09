---
title: MaxiCodeStandardCodetext
second_title: Aspose.BarCode for Android via Java API Reference
description: 모드 4, 5 및 6용 MaxiCode 코드텍스트를 인코딩 및 디코딩하기 위한 클래스입니다.
type: docs
weight: 29
url: /ko/androidjava/com.aspose.barcode.complexbarcode/maxicodestandardcodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.MaxiCodeCodetext](../../com.aspose.barcode.complexbarcode/maxicodecodetext)
```
public class MaxiCodeStandardCodetext extends MaxiCodeCodetext
```

모드 4, 5 및 6용 MaxiCode 코드텍스트를 인코딩 및 디코딩하기 위한 클래스.

```
//Mode 4
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_4);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();

 //Mode 5
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_5);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();

 //Mode 6
 MaxiCodeStandardCodetext maxiCodeCodetext = new MaxiCodeStandardCodetext();
 maxiCodeCodetext.setMode(MaxiCodeMode.MODE_6);
 maxiCodeCodetext.setMessage("Test message");
 ComplexBarcodeGenerator complexGenerator = new ComplexBarcodeGenerator(maxiCodeCodetext.getConstructedCodetext());
 complexGenerator.generateBarCodeImage();
```
## Constructors

| Constructor | 설명 |
| --- | --- |
| [MaxiCodeStandardCodetext()](#MaxiCodeStandardCodetext--) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 MaxiCodeStandardCodetext 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getBarcodeType()](#getBarcodeType--) | 바코드 유형을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | 코드텍스트를 구성합니다. |
| [getECIEncoding()](#getECIEncoding--) | ECI 인코딩을 가져옵니다. |
| [getEncodeMode()](#getEncodeMode--) | MaxiCode 인코드 모드를 가져옵니다. |
| [getMaxiCodeEncodeMode()](#getMaxiCodeEncodeMode--) | MaxiCode 인코드 모드를 가져옵니다. |
| [getMessage()](#getMessage--) | 메시지를 가져옵니다. |
| [getMode()](#getMode--) | MaxiCode 모드를 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 구성된 코드텍스트에서 인스턴스를 초기화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setECIEncoding(int value)](#setECIEncoding-int-) | ECI 인코딩을 설정합니다. |
| [setEncodeMode(MaxiCodeEncodeMode value)](#setEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | MaxiCode 인코드 모드를 설정합니다. |
| [setMaxiCodeEncodeMode(MaxiCodeEncodeMode value)](#setMaxiCodeEncodeMode-com.aspose.barcode.generation.MaxiCodeEncodeMode-) | MaxiCode 인코드 모드를 설정합니다. |
| [setMessage(String value)](#setMessage-java.lang.String-) | 메시지를 설정합니다. |
| [setMode(int mode)](#setMode-int-) | MaxiCode 모드를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaxiCodeStandardCodetext() {#MaxiCodeStandardCodetext--}
```
public MaxiCodeStandardCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 MaxiCodeStandardCodetext 값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 MaxiCodeStandardCodetext 값. |

**Returns:**
boolean - obj가 이 인스턴스와 동일한 값을 가지면; 그렇지 않으면, **false**.
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
public String getConstructedCodetext()
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
### getMessage() {#getMessage--}
```
public String getMessage()
```


메시지를 가져옵니다.

**Returns:**
java.lang.String
### getMode() {#getMode--}
```
public int getMode()
```


MaxiCode 모드를 가져옵니다.

**Returns:**
int - MaxiCode 모드
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
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

### setMessage(String value) {#setMessage-java.lang.String-}
```
public void setMessage(String value)
```


메시지를 설정합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setMode(int mode) {#setMode-int-}
```
public void setMode(int mode)
```


MaxiCode 모드를 설정합니다. 표준 코드텍스트는 모드 4, 5 및 6에서만 사용할 수 있습니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 모드 | int |  |

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

