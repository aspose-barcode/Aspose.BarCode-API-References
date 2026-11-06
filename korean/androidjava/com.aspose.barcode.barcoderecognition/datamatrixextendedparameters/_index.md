---
title: "DataMatrixExtendedParameters"
second_title: "Aspose.BarCode for Android via Java API 참조"
description: "인식된 DataMatrix 바코드의 특수 데이터를 저장합니다"
type: docs
weight: 29
url: /ko/androidjava/com.aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.barcoderecognition.BaseExtendedParameters](../../com.aspose.barcode.barcoderecognition/baseextendedparameters)
```
public final class DataMatrixExtendedParameters extends BaseExtendedParameters
```

인식된 DataMatrix 바코드의 특수 데이터를 저장합니다

--------------------

> ```
> This sample shows how to get DataMatrix raw values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX, "12345");
>  generator.save("c:\\test.png");
> 
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.DATA_MATRIX);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode type: " + result.getCodeTypeName());
>      System.out.println("BarCode codetext: " + result.getCodeText);
>      System.out.println("DataMatrix barcode ID: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodeId());
>      System.out.println("DataMatrix barcodes count: " + result.getExtended().getDataMatrix().getStructuredAppendBarcodesCount());
>      System.out.println("DataMatrix file ID: " + result.getExtended().getDataMatrix().getStructuredAppendFileId());
>      System.out.println("DataMatrix is reader programming: " + result.getExtended().getDataMatrix().isReaderProgramming));
>  }
> ```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된  DataMatrixExtendedParameters  값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getClass()](#getClass--) |  |
| [getStructuredAppendBarcodeId()](#getStructuredAppendBarcodeId--) | DataMatrix 구조 추가 모드 바코드의 ID를 가져옵니다. |
| [getStructuredAppendBarcodesCount()](#getStructuredAppendBarcodesCount--) | DataMatrix 구조 추가 모드 바코드 수를 가져옵니다. |
| [getStructuredAppendFileId()](#getStructuredAppendFileId--) | DataMatrix 구조 추가 모드 바코드의 ID를 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [isEmpty()](#isEmpty--) | 모든 매개변수가 기본값만 가지고 있는지 테스트합니다. |
| [isReaderProgramming()](#isReaderProgramming--) | 코드가 바코드 판독기를 초기화하거나 재프로그래밍하기 위한 지시로 해석하도록 판독기에게 지시하는 데 사용되는지 여부를 나타냅니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 이  DataMatrixExtendedParameters  의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된  DataMatrixExtendedParameters  값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 System.Object 값입니다. |

**Returns:**
boolean -  **true**  obj가 이 인스턴스와 동일한 값을 가지고 있는 경우; 그렇지 않으면 **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getStructuredAppendBarcodeId() {#getStructuredAppendBarcodeId--}
```
public int getStructuredAppendBarcodeId()
```


DataMatrix 구조 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다.

값: DataMatrix 구조 추가 모드 바코드의 ID.

**Returns:**
int
### getStructuredAppendBarcodesCount() {#getStructuredAppendBarcodesCount--}
```
public int getStructuredAppendBarcodesCount()
```


DataMatrix 구조 추가 모드 바코드 수를 가져옵니다. 기본값은 -1이며, 카운트는 1에서 35 사이의 값이어야 합니다.

값: DataMatrix 구조 추가 모드 바코드의 개수.

**Returns:**
int
### getStructuredAppendFileId() {#getStructuredAppendFileId--}
```
public int getStructuredAppendFileId()
```


DataMatrix 구조 추가 모드 바코드의 ID를 가져옵니다. ID는 1부터 시작하며 바코드 수보다 작거나 같아야 합니다. 기본값은 -1입니다.

값: DataMatrix 구조 추가 모드 바코드의 ID.

**Returns:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


모든 매개변수가 기본값만 가지고 있는지 테스트합니다.

값: 모든 매개변수가 기본값만 가지고 있는 경우 **true** 를 반환하고, 그렇지 않으면 **false** 를 반환합니다.

**Returns:**
boolean
### isReaderProgramming() {#isReaderProgramming--}
```
public boolean isReaderProgramming()
```


코드가 바코드 판독기에게 다음 데이터를 초기화 또는 재프로그래밍 지시로 해석하도록 지시하는 데 사용되는지 여부를 나타냅니다. 기본값은 false입니다.

**Returns:**
boolean
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


이  DataMatrixExtendedParameters  의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이  DataMatrixExtendedParameters  를 나타내는 문자열.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

