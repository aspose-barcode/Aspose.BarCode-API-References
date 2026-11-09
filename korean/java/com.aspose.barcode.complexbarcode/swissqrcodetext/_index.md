---
title: "SwissQRCodetext"
second_title: "Aspose.BarCode for Java API 레퍼런스"
description: "SwissQR 코드에 포함된 텍스트를 인코딩하고 디코딩하는 클래스."
type: docs
weight: 36
url: /ko/java/com.aspose.barcode.complexbarcode/swissqrcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class SwissQRCodetext implements IComplexCodetext
```

SwissQR 코드에 포함된 텍스트를 인코딩하고 디코딩하는 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SwissQRCodetext(SwissQRBill bill)](#SwissQRCodetext-com.aspose.barcode.complexbarcode.SwissQRBill-) | SwissQRCodetext의 인스턴스를 생성합니다. |
| [SwissQRCodetext()](#SwissQRCodetext--) | SwissQRCodetext의 인스턴스를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | 바코드 유형을 가져옵니다. |
| [getBill()](#getBill--) | SwissQR 청구서 데이터 |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | SwissQR 청구서 데이터에서 코덱스트를 구성합니다. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 구성된 코덱스트로 청구서를 초기화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SwissQRCodetext(SwissQRBill bill) {#SwissQRCodetext-com.aspose.barcode.complexbarcode.SwissQRBill-}
```
public SwissQRCodetext(SwissQRBill bill)
```


SwissQRCodetext의 인스턴스를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bill | [SwissQRBill](../../com.aspose.barcode.complexbarcode/swissqrbill) | SwissQR 청구서 데이터 |

### SwissQRCodetext() {#SwissQRCodetext--}
```
public SwissQRCodetext()
```


SwissQRCodetext의 인스턴스를 생성합니다.

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


바코드 유형을 가져옵니다.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getBill() {#getBill--}
```
public SwissQRBill getBill()
```


SwissQR 청구서 데이터

**Returns:**
[SwissQRBill](../../com.aspose.barcode.complexbarcode/swissqrbill)
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


SwissQR 청구서 데이터에서 코덱스트를 구성합니다.

**Returns:**
java.lang.String - 구성된 코드 텍스트
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


구성된 코덱스트로 청구서를 초기화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| constructedCodetext | java.lang.String | 구성된 코드 텍스트. |

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

