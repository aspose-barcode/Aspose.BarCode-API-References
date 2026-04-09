---
title: USADriveIdCodetext.MandatoryFields
second_title: Aspose.BarCode for Android via Java API Reference
description: カードの必須要素フィールド
type: docs
weight: 10
url: /ja/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.MandatoryFields
```

カードの必須要素（フィールド）
## Constructors

| Constructor | Description |
| --- | --- |
| [MandatoryFields()](#MandatoryFields--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressCity()](#getAddressCity--) | DAI, カード所有者住所の市区町村部分, DL/ID, V20ANS |
| [getAddressPostalCode()](#getAddressPostalCode--) | DAK, 米国およびカナダのカード所有者住所の郵便番号部分. |
| [getAddressState()](#getAddressState--) | DAJ, カード所有者住所の州部分, DL/ID, F2A |
| [getAddressStreet1()](#getAddressStreet1--) | DAG, カード所有者住所の通り部分, DL/ID, V35ANS |
| [getClass()](#getClass--) |  |
| [getCountryIdentification()](#getCountryIdentification--) | DCG, DL/IDが発行されている国. |
| [getCustomerIDNumber()](#getCustomerIDNumber--) | DAQ, 発行機関によって割り当てられまたは計算された番号, DL/ID, V25ANS |
| [getDateOfBirth()](#getDateOfBirth--) | DBB, 文書が発行された日付, MMDDCCYY for U.S., CCYYMMDD for Canada, DL/ID, F8N |
| [getDocumentDiscriminator()](#getDocumentDiscriminator--) | DCF, 番号は、過去に発行された可能性のある他の文書と区別して、その顧客に発行された特定の文書を一意に識別する必要があります。 |
| [getEndorsementCodes()](#getEndorsementCodes--) | DCD, 管轄特有の裏書コード, DL, V5ANS |
| [getEyeColor()](#getEyeColor--) | DAY, カード所有者の目の色。 |
| [getFamilyName()](#getFamilyName--) | DCS, カード所有者の姓, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getFamilyNameTruncation--) | DDE, フィールドが切り詰められたか（T）、切り詰められていないか（N）、または切り詰めかどうか不明か（U）を示すコード, DL/ID, F1A |
| [getFirstName()](#getFirstName--) | DAC, カード所有者の名, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getFirstNameTruncation--) | DDF, フィールドが切り詰められたか（T）、切り詰められていないか（N）、または切り詰めかどうか不明か（U）を示すコード, DL/ID, F1A |
| [getHeight()](#getHeight--) | DAU, カード所有者の身長。 |
| [getMiddleName()](#getMiddleName--) | DAD, カード所有者のミドルネーム。 |
| [getMiddleNameTruncation()](#getMiddleNameTruncation--) | DDG, フィールドが切り詰められたか（T）、切り詰められていないか（N）、または切り詰めかどうか不明か（U）を示すコード, DL/ID, F1A |
| [getRestrictionCodes()](#getRestrictionCodes--) | DCB, 管轄特有の制限コード, DL, V12ANS |
| [getSex()](#getSex--) | DBC, カード所有者の性別。 |
| [getVehicleClass()](#getVehicleClass--) | DCA, 管轄特有の車両クラス/グループコード, DL, V6ANS |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressCity(String value)](#setAddressCity-java.lang.String-) | DAI, カード所有者住所の市区町村部分, DL/ID, V20ANS |
| [setAddressPostalCode(String value)](#setAddressPostalCode-java.lang.String-) | DAK, 米国およびカナダのカード所有者住所の郵便番号部分. |
| [setAddressState(String value)](#setAddressState-java.lang.String-) | DAJ, カード所有者住所の州部分, DL/ID, F2A |
| [setAddressStreet1(String value)](#setAddressStreet1-java.lang.String-) | DAG, カード所有者住所の通り部分, DL/ID, V35ANS |
| [setCountryIdentification(USADriveIdCountry value)](#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-) | DCG, DL/IDが発行されている国. |
| [setCustomerIDNumber(String value)](#setCustomerIDNumber-java.lang.String-) | DAQ, 発行機関によって割り当てられまたは計算された番号, DL/ID, V25ANS |
| [setDateOfBirth(LocalDate value)](#setDateOfBirth-java.time.LocalDate-) | DBB, 文書が発行された日付, MMDDCCYY for U.S., CCYYMMDD for Canada, DL/ID, F8N |
| [setDocumentDiscriminator(String value)](#setDocumentDiscriminator-java.lang.String-) | DCF, 番号は、過去に発行された可能性のある他の文書と区別して、その顧客に発行された特定の文書を一意に識別する必要があります。 |
| [setEndorsementCodes(String value)](#setEndorsementCodes-java.lang.String-) | DCD, 管轄特有の裏書コード, DL, V5ANS |
| [setEyeColor(USADriveIdEyeColor value)](#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-) | DAY, カード所有者の目の色。 |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | DCS, カード所有者の姓, DL/ID, V40ANS |
| [setFamilyNameTruncation(String value)](#setFamilyNameTruncation-java.lang.String-) | DDE, フィールドが切り詰められたか（T）、切り詰められていないか（N）、または切り詰めかどうか不明か（U）を示すコード, DL/ID, F1A |
| [setFirstName(String value)](#setFirstName-java.lang.String-) | DAC, カード所有者の名, DL/ID, V40ANS |
| [setFirstNameTruncation(String value)](#setFirstNameTruncation-java.lang.String-) | DDF, フィールドが切り詰められたか（T）、切り詰められていないか（N）、または切り詰めかどうか不明か（U）を示すコード, DL/ID, F1A |
| [setHeight(String value)](#setHeight-java.lang.String-) | DAU, カード所有者の身長。 |
| [setMiddleName(String value)](#setMiddleName-java.lang.String-) | DAD, カード所有者のミドルネーム。 |
| [setMiddleNameTruncation(String value)](#setMiddleNameTruncation-java.lang.String-) | DDG, フィールドが切り詰められたか（T）、切り詰められていないか（N）、または切り詰めかどうか不明か（U）を示すコード, DL/ID, F1A |
| [setRestrictionCodes(String value)](#setRestrictionCodes-java.lang.String-) | DCB, 管轄特有の制限コード, DL, V12ANS |
| [setSex(USADriveIdSex value)](#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-) | DBC, カード所有者の性別。 |
| [setVehicleClass(String value)](#setVehicleClass-java.lang.String-) | DCA, 管轄特有の車両クラス/グループコード, DL, V6ANS |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MandatoryFields() {#MandatoryFields--}
```
public MandatoryFields()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressCity() {#getAddressCity--}
```
public final String getAddressCity()
```


DAI, カード所有者住所の市区町村部分, DL/ID, V20ANS

**Returns:**
java.lang.String
### getAddressPostalCode() {#getAddressPostalCode--}
```
public final String getAddressPostalCode()
```


DAK, 米国およびカナダのカード所有者住所の郵便番号部分. 米国の郵便番号の末尾部分が不明な場合、0 が使用され、末尾の数字が最大9桁になるまで埋められます, DL/ID, F11ANS

**Returns:**
java.lang.String
### getAddressState() {#getAddressState--}
```
public final String getAddressState()
```


DAJ, カード所有者住所の州部分, DL/ID, F2A

**Returns:**
java.lang.String
### getAddressStreet1() {#getAddressStreet1--}
```
public final String getAddressStreet1()
```


DAG, カード所有者住所の通り部分, DL/ID, V35ANS

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryIdentification() {#getCountryIdentification--}
```
public final USADriveIdCountry getCountryIdentification()
```


DCG、DL/IDが発行される国。U.S. = USA、Canada = CAN、DL/ID、F3A

**Returns:**
[USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry)
### getCustomerIDNumber() {#getCustomerIDNumber--}
```
public final String getCustomerIDNumber()
```


DAQ, 発行機関によって割り当てられまたは計算された番号, DL/ID, V25ANS

**Returns:**
java.lang.String
### getDateOfBirth() {#getDateOfBirth--}
```
public final LocalDate getDateOfBirth()
```


DBB, 文書が発行された日付, MMDDCCYY for U.S., CCYYMMDD for Canada, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getDocumentDiscriminator() {#getDocumentDiscriminator--}
```
public final String getDocumentDiscriminator()
```


DCF、番号はその顧客に発行された特定の文書を過去に発行された他の文書と区別できるように一意である必要があります。この番号は文書の識別、監査情報番号、または在庫管理など複数の目的に使用される場合があります、DL/ID、V25ANS

**Returns:**
java.lang.String
### getEndorsementCodes() {#getEndorsementCodes--}
```
public final String getEndorsementCodes()
```


DCD, 管轄特有の裏書コード, DL, V5ANS

**Returns:**
java.lang.String
### getEyeColor() {#getEyeColor--}
```
public final USADriveIdEyeColor getEyeColor()
```


DAY、カード所有者の目の色。（ANSI D-20コード）。DL/ID、F3A

**Returns:**
[USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor)
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


DCS, カード所有者の姓, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFamilyNameTruncation() {#getFamilyNameTruncation--}
```
public final String getFamilyNameTruncation()
```


DDE, フィールドが切り詰められたか（T）、切り詰められていないか（N）、または切り詰めかどうか不明か（U）を示すコード, DL/ID, F1A

**Returns:**
java.lang.String
### getFirstName() {#getFirstName--}
```
public final String getFirstName()
```


DAC, カード所有者の名, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFirstNameTruncation() {#getFirstNameTruncation--}
```
public final String getFirstNameTruncation()
```


DDF, フィールドが切り詰められたか（T）、切り詰められていないか（N）、または切り詰めかどうか不明か（U）を示すコード, DL/ID, F1A

**Returns:**
java.lang.String
### getHeight() {#getHeight--}
```
public final String getHeight()
```


DAU、カード所有者の身長。インチ（in）：インチ数の後に「 in」を付けます。例：6'1'' = "073 in" センチメートル（cm）：センチメートル数の後に「 cm」を付けます。例：181センチメートル="181 cm"、DL/ID、F6ANS

**Returns:**
java.lang.String
### getMiddleName() {#getMiddleName--}
```
public final String getMiddleName()
```


DAD、カード所有者のミドルネーム。複数のミドルネームがある場合はカンマ「,」で区切ります。DL/ID、V40ANS

**Returns:**
java.lang.String
### getMiddleNameTruncation() {#getMiddleNameTruncation--}
```
public final String getMiddleNameTruncation()
```


DDG, フィールドが切り詰められたか（T）、切り詰められていないか（N）、または切り詰めかどうか不明か（U）を示すコード, DL/ID, F1A

**Returns:**
java.lang.String
### getRestrictionCodes() {#getRestrictionCodes--}
```
public final String getRestrictionCodes()
```


DCB, 管轄特有の制限コード, DL, V12ANS

**Returns:**
java.lang.String
### getSex() {#getSex--}
```
public final USADriveIdSex getSex()
```


DBC、カード所有者の性別。1 = 男性、2 = 女性、9 = 未指定、DL/ID、F1N

**Returns:**
[USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex)
### getVehicleClass() {#getVehicleClass--}
```
public final String getVehicleClass()
```


DCA, 管轄特有の車両クラス/グループコード, DL, V6ANS

**Returns:**
java.lang.String
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




### setAddressCity(String value) {#setAddressCity-java.lang.String-}
```
public final void setAddressCity(String value)
```


DAI, カード所有者住所の市区町村部分, DL/ID, V20ANS

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setAddressPostalCode(String value) {#setAddressPostalCode-java.lang.String-}
```
public final void setAddressPostalCode(String value)
```


DAK, 米国およびカナダのカード所有者住所の郵便番号部分. 米国の郵便番号の末尾部分が不明な場合、0 が使用され、末尾の数字が最大9桁になるまで埋められます, DL/ID, F11ANS

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setAddressState(String value) {#setAddressState-java.lang.String-}
```
public final void setAddressState(String value)
```


DAJ, カード所有者住所の州部分, DL/ID, F2A

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setAddressStreet1(String value) {#setAddressStreet1-java.lang.String-}
```
public final void setAddressStreet1(String value)
```


DAG, カード所有者住所の通り部分, DL/ID, V35ANS

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setCountryIdentification(USADriveIdCountry value) {#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-}
```
public final void setCountryIdentification(USADriveIdCountry value)
```


DCG、DL/IDが発行される国。U.S. = USA、Canada = CAN、DL/ID、F3A

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry) |  |

### setCustomerIDNumber(String value) {#setCustomerIDNumber-java.lang.String-}
```
public final void setCustomerIDNumber(String value)
```


DAQ, 発行機関によって割り当てられまたは計算された番号, DL/ID, V25ANS

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setDateOfBirth(LocalDate value) {#setDateOfBirth-java.time.LocalDate-}
```
public final void setDateOfBirth(LocalDate value)
```


DBB, 文書が発行された日付, MMDDCCYY for U.S., CCYYMMDD for Canada, DL/ID, F8N

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.time.LocalDate |  |

### setDocumentDiscriminator(String value) {#setDocumentDiscriminator-java.lang.String-}
```
public final void setDocumentDiscriminator(String value)
```


DCF、番号はその顧客に発行された特定の文書を過去に発行された他の文書と区別できるように一意である必要があります。この番号は文書の識別、監査情報番号、または在庫管理など複数の目的に使用される場合があります、DL/ID、V25ANS

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setEndorsementCodes(String value) {#setEndorsementCodes-java.lang.String-}
```
public final void setEndorsementCodes(String value)
```


DCD, 管轄特有の裏書コード, DL, V5ANS

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setEyeColor(USADriveIdEyeColor value) {#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-}
```
public final void setEyeColor(USADriveIdEyeColor value)
```


DAY、カード所有者の目の色。（ANSI D-20コード）。DL/ID、F3A

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor) |  |

### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public final void setFamilyName(String value)
```


DCS, カード所有者の姓, DL/ID, V40ANS

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setFamilyNameTruncation(String value) {#setFamilyNameTruncation-java.lang.String-}
```
public final void setFamilyNameTruncation(String value)
```


DDE, フィールドが切り詰められたか（T）、切り詰められていないか（N）、または切り詰めかどうか不明か（U）を示すコード, DL/ID, F1A

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setFirstName(String value) {#setFirstName-java.lang.String-}
```
public final void setFirstName(String value)
```


DAC, カード所有者の名, DL/ID, V40ANS

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setFirstNameTruncation(String value) {#setFirstNameTruncation-java.lang.String-}
```
public final void setFirstNameTruncation(String value)
```


DDF, フィールドが切り詰められたか（T）、切り詰められていないか（N）、または切り詰めかどうか不明か（U）を示すコード, DL/ID, F1A

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setHeight(String value) {#setHeight-java.lang.String-}
```
public final void setHeight(String value)
```


DAU、カード所有者の身長。インチ（in）：インチ数の後に「 in」を付けます。例：6'1'' = "073 in" センチメートル（cm）：センチメートル数の後に「 cm」を付けます。例：181センチメートル="181 cm"、DL/ID、F6ANS

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setMiddleName(String value) {#setMiddleName-java.lang.String-}
```
public final void setMiddleName(String value)
```


DAD、カード所有者のミドルネーム。複数のミドルネームがある場合はカンマ「,」で区切ります。DL/ID、V40ANS

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setMiddleNameTruncation(String value) {#setMiddleNameTruncation-java.lang.String-}
```
public final void setMiddleNameTruncation(String value)
```


DDG, フィールドが切り詰められたか（T）、切り詰められていないか（N）、または切り詰めかどうか不明か（U）を示すコード, DL/ID, F1A

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setRestrictionCodes(String value) {#setRestrictionCodes-java.lang.String-}
```
public final void setRestrictionCodes(String value)
```


DCB, 管轄特有の制限コード, DL, V12ANS

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setSex(USADriveIdSex value) {#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-}
```
public final void setSex(USADriveIdSex value)
```


DBC、カード所有者の性別。1 = 男性、2 = 女性、9 = 未指定、DL/ID、F1N

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex) |  |

### setVehicleClass(String value) {#setVehicleClass-java.lang.String-}
```
public final void setVehicleClass(String value)
```


DCA, 管轄特有の車両クラス/グループコード, DL, V6ANS

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| 値 | java.lang.String |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

