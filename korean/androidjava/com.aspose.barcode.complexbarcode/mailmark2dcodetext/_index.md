---
title: Mailmark2DCodetext
second_title: Aspose.BarCode for Android via Java API Reference
description: Royal Mail 2D Mailmark 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스.
type: docs
weight: 23
url: /ko/androidjava/com.aspose.barcode.complexbarcode/mailmark2dcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public class Mailmark2DCodetext implements IComplexCodetext
```

Royal Mail 2D Mailmark 코드에 삽입된 텍스트를 인코딩 및 디코딩하기 위한 클래스.
## Constructors

| Constructor | 설명 |
| --- | --- |
| [Mailmark2DCodetext()](#Mailmark2DCodetext--) | Create default instance of Mailmark2DCodetext class. |
## Methods

| Method | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | 바코드 유형을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | Construct codetext from Mailmark data. |
| [getCustomerContent()](#getCustomerContent--) | Optional space for use by customer. |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | Encode mode of Datamatrix barcode. |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [getInformationTypeID()](#getInformationTypeID--) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [getItemID()](#getItemID--) | Identifies the unique item within the Supply Chain ID. |
| [getRTSFlag()](#getRTSFlag--) | 반송 서비스 수준을 나타내는 플래그입니다. |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | 반송 우편 코드가 포함되어 있지만 DPS는 포함되지 않습니다. |
| [getSupplyChainID()](#getSupplyChainID--) | 메일링에 참여하는 고유한 고객 그룹을 식별합니다. |
| [getUPUCountryID()](#getUPUCountryID--) | UPU 국가 ID를 식별합니다. 최대 길이: 4자. |
| [getVersionID()](#getVersionID--) | 각 정보 유형 ID에 해당하는 바코드 버전을 식별합니다. |
| [getclass()](#getclass--) | 항목의 클래스를 식별합니다. |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | Initializes Mailmark data from constructed codetext. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | Optional space for use by customer. |
| [setCustomerContentEncodeMode(DataMatrixEncodeMode value)](#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-) | Encode mode of Datamatrix barcode. |
| [setDataMatrixType(Mailmark2DType value)](#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [setItemID(int value)](#setItemID-int-) | Identifies the unique item within the Supply Chain ID. |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | 반송 서비스 수준을 나타내는 플래그입니다. |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | 반송 우편 코드가 포함되어 있지만 DPS는 포함되지 않습니다. |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | 메일링에 참여하는 고유한 고객 그룹을 식별합니다. |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | UPU 국가 ID를 식별합니다. 최대 길이: 4자. |
| [setVersionID(String value)](#setVersionID-java.lang.String-) | 각 정보 유형 ID에 해당하는 바코드 버전을 식별합니다. |
| [setclass(String value)](#setclass-java.lang.String-) | 항목의 클래스를 식별합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mailmark2DCodetext() {#Mailmark2DCodetext--}
```
public Mailmark2DCodetext()
```


Create default instance of Mailmark2DCodetext class.

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


Construct codetext from Mailmark data.

**Returns:**
java.lang.String - 구성된 코드텍스트
### getCustomerContent() {#getCustomerContent--}
```
public String getCustomerContent()
```


고객이 사용할 수 있는 선택적 공간입니다. 유형별 최대 길이: 유형 7: 6자, 유형 9: 45자, 유형 29: 25자

**Returns:**
java.lang.String - 고객 콘텐츠
### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public DataMatrixEncodeMode getCustomerContentEncodeMode()
```


Datamatrix 바코드의 인코드 모드입니다. 기본값: DataMatrixEncodeMode.C40.

**Returns:**
[DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) - Encode mode of Datamatrix barcode.
### getDataMatrixType() {#getDataMatrixType--}
```
public Mailmark2DType getDataMatrixType()
```


2D Mailmark Type defines size of Data Matrix barcode.

**Returns:**
[Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) - Size of Data Matrix barcode
### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public String getDestinationPostCodeAndDPS()
```


DPS가 포함된 배송 주소의 우편 코드를 포함합니다. 내륙인 경우 우편 코드/DP는 다음과 같은 문자 수를 가집니다. 지역(1~2자) 구역(1~2자) 섹터(1자) 유닛(2자) DPS(2자). 우편 코드와 DPS는 유효한 PAF® 형식이어야 합니다.

**Returns:**
java.lang.String - DPS가 포함된 배송 주소의 우편 코드
### getInformationTypeID() {#getInformationTypeID--}
```
public String getInformationTypeID()
```


각 제품 유형에 대한 Royal Mail Mailmark 바코드 페이로드를 식별합니다. 유효값: '0' - 국내 정렬 및 비정렬, 'A' - 온라인 우편, 'B' - 프랭킹, 'C' - 통합

**Returns:**
java.lang.String - 정보 유형 ID
### getItemID() {#getItemID--}
```
public int getItemID()
```


공급망 ID 내에서 고유한 항목을 식별합니다. 모든 Mailmark 바코드는 최소 90일 동안 고유하게 식별될 수 있도록 ID를 포함해야 합니다. 최대값: 99999999.

**Returns:**
int - 공급망 ID 내의 항목
### getRTSFlag() {#getRTSFlag--}
```
public String getRTSFlag()
```


반송 서비스 수준을 나타내는 플래그입니다.

**Returns:**
java.lang.String - RTS 플래그
### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public String getReturnToSenderPostCode()
```


반송 우편 코드를 포함하지만 DPS는 포함되지 않습니다. DPS가 없는 PC는 PAF® 형식이어야 합니다.

**Returns:**
java.lang.String - DPS가 없는 반송 우편 코드
### getSupplyChainID() {#getSupplyChainID--}
```
public int getSupplyChainID()
```


메일링에 참여하는 고유한 고객 그룹을 식별합니다. 최대값: 9999999.

**Returns:**
int - 공급망 ID
### getUPUCountryID() {#getUPUCountryID--}
```
public String getUPUCountryID()
```


UPU 국가 ID를 식별합니다. 최대 길이: 4자.

**Returns:**
java.lang.String - 국가 ID
### getVersionID() {#getVersionID--}
```
public String getVersionID()
```


각 정보 유형 ID에 해당하는 바코드 버전을 식별합니다. 유효값: 현재 '1'. '0' 및 '2'~'9', 'A'~'Z'는 향후 사용을 위해 예약되어 있습니다.

**Returns:**
java.lang.String - 버전 ID
### getclass() {#getclass--}
```
public String getclass()
```


항목의 클래스를 식별합니다. 유효값: '1' - 1C(소매), '2' - 2C(소매), '3' - Economy(소매), '5' - Deffered(소매), '8' - Premium(네트워크 액세스), '9' - Standard(네트워크 액세스)

**Returns:**
java.lang.String - 항목의 클래스
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


Initializes Mailmark data from constructed codetext.

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




### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public void setCustomerContent(String value)
```


고객이 사용할 수 있는 선택적 공간입니다. 유형별 최대 길이: 유형 7: 6자, 유형 9: 45자, 유형 29: 25자

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 고객 콘텐츠 |

### setCustomerContentEncodeMode(DataMatrixEncodeMode value) {#setCustomerContentEncodeMode-com.aspose.barcode.generation.DataMatrixEncodeMode-}
```
public void setCustomerContentEncodeMode(DataMatrixEncodeMode value)
```


Datamatrix 바코드의 인코드 모드. 기본값: EncodeMode.C40.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [DataMatrixEncodeMode](../../com.aspose.barcode.generation/datamatrixencodemode) | Encode mode of Datamatrix barcode. |

### setDataMatrixType(Mailmark2DType value) {#setDataMatrixType-com.aspose.barcode.complexbarcode.Mailmark2DType-}
```
public void setDataMatrixType(Mailmark2DType value)
```


2D Mailmark Type defines size of Data Matrix barcode.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| value | [Mailmark2DType](../../com.aspose.barcode.complexbarcode/mailmark2dtype) | Data Matrix 바코드 크기 |

### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public void setDestinationPostCodeAndDPS(String value)
```


DPS가 포함된 배송 주소의 우편 코드를 포함합니다. 내륙인 경우 우편 코드/DP는 다음과 같은 문자 수를 가집니다. 지역(1~2자) 구역(1~2자) 섹터(1자) 유닛(2자) DPS(2자). 우편 코드와 DPS는 유효한 PAF® 형식이어야 합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | DPS가 포함된 배송 주소의 우편번호 |

### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public void setInformationTypeID(String value)
```


각 제품 유형에 대한 Royal Mail Mailmark 바코드 페이로드를 식별합니다. 유효값: '0' - 국내 정렬 및 비정렬, 'A' - 온라인 우편, 'B' - 프랭킹, 'C' - 통합

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 정보 유형 ID |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


공급망 ID 내에서 고유한 항목을 식별합니다. 모든 Mailmark 바코드는 최소 90일 동안 고유하게 식별될 수 있도록 ID를 포함해야 합니다. 최대값: 99999999.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int | 공급망 내 항목 ID |

### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public void setRTSFlag(String value)
```


반송 서비스 수준을 나타내는 플래그입니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public void setReturnToSenderPostCode(String value)
```


반송 우편 코드를 포함하지만 DPS는 포함되지 않습니다. DPS가 없는 PC는 PAF® 형식이어야 합니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | DPS 없이 반송자 우편번호 |

### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public void setSupplyChainID(int value)
```


메일링에 참여하는 고유한 고객 그룹을 식별합니다. 최대값: 9999999.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | int | 공급망 ID |

### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public void setUPUCountryID(String value)
```


UPU 국가 ID를 식별합니다. 최대 길이: 4자.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 국가 ID |

### setVersionID(String value) {#setVersionID-java.lang.String-}
```
public void setVersionID(String value)
```


각 정보 유형 ID에 해당하는 바코드 버전을 식별합니다. 유효값: 현재 '1'. '0' 및 '2'~'9', 'A'~'Z'는 향후 사용을 위해 예약되어 있습니다.

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 버전 ID |

### setclass(String value) {#setclass-java.lang.String-}
```
public void setclass(String value)
```


항목의 클래스를 식별합니다. 유효값: '1' - 1C(소매), '2' - 2C(소매), '3' - Economy(소매), '5' - Deffered(소매), '8' - Premium(네트워크 액세스), '9' - Standard(네트워크 액세스)

**Parameters:**
| Parameter | Type | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 항목 클래스 |

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

