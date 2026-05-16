---
title: BarCodeResult
second_title: Aspose.BarCode for Android via Java API Reference
description: 인식된 바코드 데이터를 저장합니다. 예를 들어 SingleDecodeType type string codetext BarCodeRegionParameters region 및 기타 매개변수
type: docs
weight: 18
url: /ko/androidjava/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

SingleDecodeType 유형, string codetext, BarCodeRegionParameters 영역 및 기타 매개변수와 같은 인식된 바코드 데이터를 저장합니다

--------------------

> ```
> This sample shows how to obtain BarCodeResult.
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## Constructors

| Constructor | 설명 |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | BarCodeResult 클래스의 복사본을 생성합니다. |
## Methods

| Method | 설명 |
| --- | --- |
| [deepClone()](#deepClone--) | BarCodeResult 클래스의 복사본을 생성합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 인스턴스가 지정된 BarCodeResult 값과 같은지 여부를 나타내는 값을 반환합니다. |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | 인코딩된 코드 바이트를 가져옵니다. |
| [getCodeText()](#getCodeText--) | 코드 텍스트를 가져옵니다. |
| [getCodeText(Charset encoding)](#getCodeText-java.nio.charset.Charset-) | 인코딩된 코드 텍스트를 가져옵니다. |
| [getCodeType()](#getCodeType--) | 바코드 유형을 가져옵니다. |
| [getCodeTypeName()](#getCodeTypeName--) | 바코드 유형의 이름을 가져옵니다. |
| [getConfidence()](#getConfidence--) | 인식된 바코드의 신뢰도 수준을 가져옵니다. |
| [getExtended()](#getExtended--) | 인식된 바코드의 확장 매개변수를 가져옵니다. |
| [getReadingQuality()](#getReadingQuality--) | 읽기 품질을 가져옵니다. |
| [getRegion()](#getRegion--) | 바코드 영역을 가져옵니다. |
| [hashCode()](#hashCode--) | 이 인스턴스의 해시 코드를 반환합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 이 BarCodeResult의 사람이 읽을 수 있는 문자열 표현을 반환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


BarCodeResult 클래스의 복사본을 생성합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | BarCodeResult 복사 인스턴스. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


BarCodeResult 클래스의 복사본을 생성합니다.

**Returns:**
java.lang.Object - BarCodeResult 클래스의 복사본을 반환합니다.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


이 인스턴스가 지정된 BarCodeResult 값과 같은지 여부를 나타내는 값을 반환합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 BarCodeResult 값. |

**Returns:**
boolean -  **true**  if obj가 이 인스턴스와 동일한 값을 가지고 있는 경우; 그렇지 않은 경우 **false**.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeBytes() {#getCodeBytes--}
```
public byte[] getCodeBytes()
```


인코딩된 코드 바이트를 가져옵니다.

값: 바코드의 코드 바이트

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


코드 텍스트를 가져옵니다.

값: 바코드의 코드 텍스트

**Returns:**
java.lang.String
### getCodeText(Charset encoding) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset encoding)
```


인코딩된 코드 텍스트를 가져옵니다.

--------------------

> ```
> This example shows how to use ```
> GetCodeText
> ```:
>   
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 인코딩 | java.nio.charset.Charset | 코드 텍스트에 대한 인코딩입니다. |

**Returns:**
java.lang.String - 인식된 코드 텍스트를 포함하는 문자열.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


바코드 유형을 가져옵니다.

값: 인식된 바코드의 유형 정보

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


바코드 유형의 이름을 가져옵니다.

값: 인식된 바코드의 유형 이름

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public int getConfidence()
```


인식된 바코드의 신뢰도 수준을 가져옵니다.

값: BarCodeConfidence.Strong은 가짜나 오인식이 없으며, BarCodeConfidence.Moderate는 약한 체크섬이 있거나 없을 경우 가짜 또는 잘못된 코드 텍스트가 발생할 수 있고, BarCodeConfidence.None은 항상 잘못된 코드 텍스트이며 가짜 인식일 수 있습니다.

**Returns:**
int
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


인식된 바코드의 확장 매개변수를 가져옵니다.

값: 인식된 바코드의 확장 매개변수

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


읽기 품질을 가져옵니다. 1D 및 우편 바코드에 적용됩니다.

값: 읽기 품질 백분율

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


바코드 영역을 가져옵니다.

값: 인식된 바코드의 영역

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
### hashCode() {#hashCode--}
```
public int hashCode()
```


이 인스턴스의 해시 코드를 반환합니다.

**Returns:**
int - 32비트 부호 있는 정수 해시 코드입니다.
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


이 BarCodeResult의 사람이 읽을 수 있는 문자열 표현을 반환합니다.

**Returns:**
java.lang.String - 이 BarCodeResult를 나타내는 문자열.
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

