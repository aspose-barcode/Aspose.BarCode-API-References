---
title: "GS1HanXinEncoder"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "GS1HanXin 인코딩을 위한 함수가 포함됩니다."
type: docs
weight: 45
url: /ko/java/com.aspose.barcode.generation/gs1hanxinencoder/
---
**Inheritance:**
java.lang.Object, com.aspose.barcode.generation.renderers.barcoderenderers.encoders.BarCodeEncoder, com.aspose.barcode.generation.HanXinEncoder
```
public class GS1HanXinEncoder extends HanXinEncoder
```

GS1HanXin 인코딩을 위한 함수가 포함됩니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GS1HanXinEncoder(HanXinEncoderParameters parameters)](#GS1HanXinEncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.HanXinEncoderParameters-) | 입력 데이터는 모드 구분자로 괄호 ()만 사용해야 합니다, 예: (01)12345678901231(21)ASPOSE(30)9876. GS1 사양에 따르면, 모든 사전 정의된 길이의 GS1 데이터 문자열은 사전 정의되지 않은 길이의 GS1 데이터 문자열 뒤에 와야 합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [encode(String str)](#encode-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlwaysShowChecksum()](#getAlwaysShowChecksum--) |  |
| [getChecksum()](#getChecksum--) |  |
| [getClass()](#getClass--) |  |
| [getEnableChecksum()](#getEnableChecksum--) |  |
| [getEncodeType()](#getEncodeType--) |  |
| [getHumanReadableCodeText()](#getHumanReadableCodeText--) |  |
| [getParameters()](#getParameters--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GS1HanXinEncoder(HanXinEncoderParameters parameters) {#GS1HanXinEncoder-com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.HanXinEncoderParameters-}
```
public GS1HanXinEncoder(HanXinEncoderParameters parameters)
```


입력 데이터는 모드 구분자로 괄호 ()만 사용해야 합니다, 예: (01)12345678901231(21)ASPOSE(30)9876. GS1 사양에 따르면, 모든 사전 정의된 길이의 GS1 데이터 문자열은 사전 정의되지 않은 길이의 GS1 데이터 문자열 뒤에 와야 합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 매개변수 | com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.HanXinEncoderParameters |  |

### encode(String str) {#encode-java.lang.String-}
```
public String encode(String str)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | java.lang.String |  |

**Returns:**
java.lang.String
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlwaysShowChecksum() {#getAlwaysShowChecksum--}
```
public boolean getAlwaysShowChecksum()
```




**Returns:**
boolean
### getChecksum() {#getChecksum--}
```
public String getChecksum()
```




**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnableChecksum() {#getEnableChecksum--}
```
public EnableChecksum getEnableChecksum()
```




**Returns:**
[EnableChecksum](../../com.aspose.barcode.generation/enablechecksum)
### getEncodeType() {#getEncodeType--}
```
public BaseEncodeType getEncodeType()
```




**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getHumanReadableCodeText() {#getHumanReadableCodeText--}
```
public String getHumanReadableCodeText()
```




**Returns:**
java.lang.String
### getParameters() {#getParameters--}
```
public EncoderParameters getParameters()
```




**Returns:**
com.aspose.barcode.generation.renderers.barcoderenderers.encoders.parameters.EncoderParameters
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
public final native void wait(long arg0)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

