---
title: USADriveIdCodetext
second_title: Aspose.BarCode for Android via Java API Reference
description: USA 운전 면허 PDF417 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스.
type: docs
weight: 38
url: /ko/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class USADriveIdCodetext implements IComplexCodetext
```

USA 운전 면허 PDF417 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스.
## Constructors

| Constructor | 설명 |
| --- | --- |
| [USADriveIdCodetext()](#USADriveIdCodetext--) | 기본 생성자 |
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAAMVAVersionNumber()](#getAAMVAVersionNumber--) | AAMVA 버전 번호 00-99 |
| [getBarcodeType()](#getBarcodeType--) | USA DL(Pdf417)의 바코드 유형을 반환합니다. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | USA DL 데이터에서 코덱스트를 구성합니다. |
| [getIssuerIdentificationNumber()](#getIssuerIdentificationNumber--) | 이 번호는 발행 관할 구역을 고유하게 식별하며, ISO 발행 기관(AAMVA)에 문의하여 얻을 수 있습니다. |
| [getJurisdictionSpecificSubfile()](#getJurisdictionSpecificSubfile--) | 관할 구역별 필드 |
| [getJurisdictionVersionNumber()](#getJurisdictionVersionNumber--) | 관할 구역 버전 번호 00-99 |
| [getMandatoryElements()](#getMandatoryElements--) | 카드의 필수 요소(필드) |
| [getNumberOfEntries()](#getNumberOfEntries--) | 서브파일 번호 00-99 |
| [getOptionalElements()](#getOptionalElements--) | 카드의 선택적 요소(필드) |
| [getSubfileDesignator()](#getSubfileDesignator--) | 다음 서브파일, 유형, 오프셋 및 길이에 대한 정보를 포함합니다. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | 코덱스트에서 USA DL 객체를 초기화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveToXml(OutputStream stream)](#saveToXml-java.io.OutputStream-) | XML로 저장합니다. |
| [setAAMVAVersionNumber(String value)](#setAAMVAVersionNumber-java.lang.String-) | AAMVA 버전 번호 00-99 |
| [setIssuerIdentificationNumber(String value)](#setIssuerIdentificationNumber-java.lang.String-) | 이 번호는 발행 관할 구역을 고유하게 식별하며, ISO 발행 기관(AAMVA)에 문의하여 얻을 수 있습니다. |
| [setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)](#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-) | 관할 구역별 필드 |
| [setJurisdictionVersionNumber(String value)](#setJurisdictionVersionNumber-java.lang.String-) | 관할 구역 버전 번호 00-99 |
| [setMandatoryElements(USADriveIdCodetext.MandatoryFields value)](#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-) | 카드의 필수 요소(필드) |
| [setNumberOfEntries(int value)](#setNumberOfEntries-int-) | 서브파일 번호 00-99 |
| [setOptionalElements(USADriveIdCodetext.OptionalFields value)](#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-) | 카드의 선택적 요소(필드) |
| [setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)](#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--) | 다음 서브파일, 유형, 오프셋 및 길이에 대한 정보를 포함합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### USADriveIdCodetext() {#USADriveIdCodetext--}
```
public USADriveIdCodetext()
```


기본 생성자

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
### getAAMVAVersionNumber() {#getAAMVAVersionNumber--}
```
public final String getAAMVAVersionNumber()
```


AAMVA 버전 번호 00-99

**Returns:**
java.lang.String
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```


USA DL(Pdf417)의 바코드 유형을 반환합니다.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type (Pdf417)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public final String getConstructedCodetext()
```


USA DL 데이터에서 코덱스트를 구성합니다.

**Returns:**
java.lang.String - 구성된 코드텍스트
### getIssuerIdentificationNumber() {#getIssuerIdentificationNumber--}
```
public final String getIssuerIdentificationNumber()
```


이 번호는 발행 관할 구역을 고유하게 식별하며, ISO 발행 기관(AAMVA)에 문의하여 얻을 수 있습니다. 전체 6자리 IIN을 인코딩해야 합니다.

**Returns:**
java.lang.String
### getJurisdictionSpecificSubfile() {#getJurisdictionSpecificSubfile--}
```
public final USADriveIdJurisdSubfile getJurisdictionSpecificSubfile()
```


관할 구역별 필드

**Returns:**
[USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile)
### getJurisdictionVersionNumber() {#getJurisdictionVersionNumber--}
```
public final String getJurisdictionVersionNumber()
```


관할 구역 버전 번호 00-99

**Returns:**
java.lang.String
### getMandatoryElements() {#getMandatoryElements--}
```
public final USADriveIdCodetext.MandatoryFields getMandatoryElements()
```


카드의 필수 요소(필드)

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields
### getNumberOfEntries() {#getNumberOfEntries--}
```
public final int getNumberOfEntries()
```


서브파일 번호 00-99

**Returns:**
int
### getOptionalElements() {#getOptionalElements--}
```
public final USADriveIdCodetext.OptionalFields getOptionalElements()
```


카드의 선택적 요소(필드)

**Returns:**
com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields
### getSubfileDesignator() {#getSubfileDesignator--}
```
public final List<USADriveIdCodetext.SubfileProperties> getSubfileDesignator()
```


다음 서브파일, 유형, 오프셋 및 길이에 대한 정보를 포함합니다. 중요: 유형만 설정하면 오프셋과 길이는 자동으로 설정됩니다.

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public final void initFromString(String constructedCodetext)
```


코덱스트에서 USA DL 객체를 초기화합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| constructedCodetext | java.lang.String | 구성된 코드 텍스트 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveToXml(OutputStream stream) {#saveToXml-java.io.OutputStream-}
```
public final void saveToXml(OutputStream stream)
```


XML로 저장합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 저장할 스트림 |

### setAAMVAVersionNumber(String value) {#setAAMVAVersionNumber-java.lang.String-}
```
public final void setAAMVAVersionNumber(String value)
```


AAMVA 버전 번호 00-99

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setIssuerIdentificationNumber(String value) {#setIssuerIdentificationNumber-java.lang.String-}
```
public final void setIssuerIdentificationNumber(String value)
```


이 번호는 발행 관할 구역을 고유하게 식별하며, ISO 발행 기관(AAMVA)에 문의하여 얻을 수 있습니다. 전체 6자리 IIN을 인코딩해야 합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value) {#setJurisdictionSpecificSubfile-com.aspose.barcode.complexbarcode.USADriveIdJurisdSubfile-}
```
public final void setJurisdictionSpecificSubfile(USADriveIdJurisdSubfile value)
```


관할 구역별 필드

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [USADriveIdJurisdSubfile](../../com.aspose.barcode.complexbarcode/usadriveidjurisdsubfile) |  |

### setJurisdictionVersionNumber(String value) {#setJurisdictionVersionNumber-java.lang.String-}
```
public final void setJurisdictionVersionNumber(String value)
```


관할 구역 버전 번호 00-99

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setMandatoryElements(USADriveIdCodetext.MandatoryFields value) {#setMandatoryElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields-}
```
public final void setMandatoryElements(USADriveIdCodetext.MandatoryFields value)
```


카드의 필수 요소(필드)

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | com.aspose.barcode.complexbarcode.USADriveIdCodetext.MandatoryFields |  |

### setNumberOfEntries(int value) {#setNumberOfEntries-int-}
```
public final void setNumberOfEntries(int value)
```


서브파일 번호 00-99

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setOptionalElements(USADriveIdCodetext.OptionalFields value) {#setOptionalElements-com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields-}
```
public final void setOptionalElements(USADriveIdCodetext.OptionalFields value)
```


카드의 선택적 요소(필드)

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | com.aspose.barcode.complexbarcode.USADriveIdCodetext.OptionalFields |  |

### setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value) {#setSubfileDesignator-java.util.List-com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties--}
```
public final void setSubfileDesignator(List<USADriveIdCodetext.SubfileProperties> value)
```


다음 서브파일, 유형, 오프셋 및 길이에 대한 정보를 포함합니다. 중요: 유형만 설정하면 오프셋과 길이는 자동으로 설정됩니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.util.List<com.aspose.barcode.complexbarcode.USADriveIdCodetext.SubfileProperties> |  |

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

