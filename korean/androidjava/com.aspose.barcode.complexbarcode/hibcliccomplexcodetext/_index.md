---
title: HIBCLICComplexCodetext
second_title: Aspose.BarCode for Android via Java API Reference
description: HIBC LIC 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스.
type: docs
weight: 15
url: /ko/androidjava/com.aspose.barcode.complexbarcode/hibcliccomplexcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public abstract class HIBCLICComplexCodetext implements IComplexCodetext
```

HIBC LIC 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 기본 클래스.

--------------------

> ```
> This sample shows how to decode raw HIBC LIC codetext to HIBCLICComplexCodetext instance.
>  
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.HIBC_AZTEC_LIC);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      HIBCLICComplexCodetext resultHIBCLICComplexCodetext = ComplexCodetextReader.tryDecodeHIBCLIC(result.getCodeText());
>      System.out.println("BarCode Type: " + resultMaxiCodeCodetext.getBarcodeType());
>      System.out.println("BarCode CodeText: " + resultMaxiCodeCodetext.getConstructedCodetext());
>  }
> ```
## Constructors

| Constructor | 설명 |
| --- | --- |
| [HIBCLICComplexCodetext()](#HIBCLICComplexCodetext--) |  |
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | 바코드 유형을 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | 코드텍스트를 구성합니다. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 구성된 코드텍스트에서 인스턴스를 초기화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | 바코드 유형을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCLICComplexCodetext() {#HIBCLICComplexCodetext--}
```
public HIBCLICComplexCodetext()
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
public BaseEncodeType getBarcodeType()
```


바코드 유형을 가져오거나 설정합니다. HIBC LIC 코드텍스트는 HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC 및 HIBCQRLIC 인코드 유형을 사용하여 인코딩할 수 있습니다. 기본값: HIBCCode39LIC.

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




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


바코드 유형을 가져오거나 설정합니다. HIBC LIC 코드텍스트는 HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC 및 HIBCQRLIC 인코드 유형을 사용하여 인코딩할 수 있습니다. 기본값: HIBCCode39LIC.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

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

