---
title: "USADriveIdCodetext.MandatoryFields"
second_title: "Aspose.BarCode for Java API Reference"
description: "卡片的必填元素字段"
type: docs
weight: 10
url: /zh/java/com.aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.MandatoryFields
```

卡片的必填元素（字段）
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MandatoryFields()](#MandatoryFields--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressCity()](#getAddressCity--) | DAI，持卡人地址的城市部分，DL/ID，V20ANS |
| [getAddressPostalCode()](#getAddressPostalCode--) | DAK，美国和加拿大持卡人地址的邮政编码部分。 |
| [getAddressState()](#getAddressState--) | DAJ, 持卡人地址的州部分, DL/ID, F2A |
| [getAddressStreet1()](#getAddressStreet1--) | DAG, 持卡人地址的街道部分, DL/ID, V35ANS |
| [getClass()](#getClass--) |  |
| [getCountryIdentification()](#getCountryIdentification--) | DCG, DL/ID 签发的国家. |
| [getCustomerIDNumber()](#getCustomerIDNumber--) | DAQ, 发行机构分配或计算的号码, DL/ID, V25ANS |
| [getDateOfBirth()](#getDateOfBirth--) | DBB, 文件签发日期, MMDDCCYY（美国），CCYYMMDD（加拿大），DL/ID, F8N |
| [getDocumentDiscriminator()](#getDocumentDiscriminator--) | DCF, 号码必须唯一标识发给该客户的特定文件，以区别于过去可能已发出的其他文件. |
| [getEndorsementCodes()](#getEndorsementCodes--) | DCD, 管辖区特定的背书代码, DL, V5ANS |
| [getExpirationDate()](#getExpirationDate--) | DBA, 文件到期日期, MMDDCCYY（美国），CCYYMMDD（加拿大），DL/ID, F8N |
| [getEyeColor()](#getEyeColor--) | DAY, 持卡人眼睛的颜色. |
| [getFamilyName()](#getFamilyName--) | DCS, 持卡人姓氏, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getFamilyNameTruncation--) | DDE, 表示字段是否被截断的代码（截断 T），未截断 N，或未知 U, DL/ID, F1A |
| [getFirstName()](#getFirstName--) | DAC, 持卡人名字, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getFirstNameTruncation--) | DDF, 表示字段是否被截断的代码（截断 T），未截断 N，或未知 U, DL/ID, F1A |
| [getHeight()](#getHeight--) | DAU, 持卡人身高. |
| [getIssueDate()](#getIssueDate--) | DBD, 文件签发日期, MMDDCCYY（美国），CCYYMMDD（加拿大），DL/ID, F8N |
| [getMiddleName()](#getMiddleName--) | DAD, 持卡人中间名（们）. |
| [getMiddleNameTruncation()](#getMiddleNameTruncation--) | DDG, 表示字段是否被截断的代码（截断 T），未截断 N，或未知 U, DL/ID, F1A |
| [getRestrictionCodes()](#getRestrictionCodes--) | DCB, 管辖区特定的限制代码, DL, V12ANS |
| [getSex()](#getSex--) | DBC, 持卡人性别. |
| [getVehicleClass()](#getVehicleClass--) | DCA, 管辖区特定的车辆类别/组代码, DL, V6ANS |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressCity(String value)](#setAddressCity-java.lang.String-) | DAI，持卡人地址的城市部分，DL/ID，V20ANS |
| [setAddressPostalCode(String value)](#setAddressPostalCode-java.lang.String-) | DAK，美国和加拿大持卡人地址的邮政编码部分。 |
| [setAddressState(String value)](#setAddressState-java.lang.String-) | DAJ, 持卡人地址的州部分, DL/ID, F2A |
| [setAddressStreet1(String value)](#setAddressStreet1-java.lang.String-) | DAG, 持卡人地址的街道部分, DL/ID, V35ANS |
| [setCountryIdentification(USADriveIdCountry value)](#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-) | DCG, DL/ID 签发的国家. |
| [setCustomerIDNumber(String value)](#setCustomerIDNumber-java.lang.String-) | DAQ, 发行机构分配或计算的号码, DL/ID, V25ANS |
| [setDateOfBirth(LocalDate value)](#setDateOfBirth-java.time.LocalDate-) | DBB, 文件签发日期, MMDDCCYY（美国），CCYYMMDD（加拿大），DL/ID, F8N |
| [setDocumentDiscriminator(String value)](#setDocumentDiscriminator-java.lang.String-) | DCF, 号码必须唯一标识发给该客户的特定文件，以区别于过去可能已发出的其他文件. |
| [setEndorsementCodes(String value)](#setEndorsementCodes-java.lang.String-) | DCD, 管辖区特定的背书代码, DL, V5ANS |
| [setExpirationDate(LocalDate value)](#setExpirationDate-java.time.LocalDate-) | DBA, 文件到期日期, MMDDCCYY（美国），CCYYMMDD（加拿大），DL/ID, F8N |
| [setEyeColor(USADriveIdEyeColor value)](#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-) | DAY, 持卡人眼睛的颜色. |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | DCS, 持卡人姓氏, DL/ID, V40ANS |
| [setFamilyNameTruncation(String value)](#setFamilyNameTruncation-java.lang.String-) | DDE, 表示字段是否被截断的代码（截断 T），未截断 N，或未知 U, DL/ID, F1A |
| [setFirstName(String value)](#setFirstName-java.lang.String-) | DAC, 持卡人名字, DL/ID, V40ANS |
| [setFirstNameTruncation(String value)](#setFirstNameTruncation-java.lang.String-) | DDF, 表示字段是否被截断的代码（截断 T），未截断 N，或未知 U, DL/ID, F1A |
| [setHeight(String value)](#setHeight-java.lang.String-) | DAU, 持卡人身高. |
| [setIssueDate(LocalDate value)](#setIssueDate-java.time.LocalDate-) | DBD, 文件签发日期, MMDDCCYY（美国），CCYYMMDD（加拿大），DL/ID, F8N |
| [setMiddleName(String value)](#setMiddleName-java.lang.String-) | DAD, 持卡人中间名（们）. |
| [setMiddleNameTruncation(String value)](#setMiddleNameTruncation-java.lang.String-) | DDG, 表示字段是否被截断的代码（截断 T），未截断 N，或未知 U, DL/ID, F1A |
| [setRestrictionCodes(String value)](#setRestrictionCodes-java.lang.String-) | DCB, 管辖区特定的限制代码, DL, V12ANS |
| [setSex(USADriveIdSex value)](#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-) | DBC, 持卡人性别. |
| [setVehicleClass(String value)](#setVehicleClass-java.lang.String-) | DCA, 管辖区特定的车辆类别/组代码, DL, V6ANS |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressCity() {#getAddressCity--}
```
public final String getAddressCity()
```


DAI，持卡人地址的城市部分，DL/ID，V20ANS

**Returns:**
java.lang.String
### getAddressPostalCode() {#getAddressPostalCode--}
```
public final String getAddressPostalCode()
```


DAK, 持卡人地址在美国和加拿大的邮政编码部分。如果美国的邮政编码后缀未知，将使用零填充至 9 位数字, DL/ID, F11ANS

**Returns:**
java.lang.String
### getAddressState() {#getAddressState--}
```
public final String getAddressState()
```


DAJ, 持卡人地址的州部分, DL/ID, F2A

**Returns:**
java.lang.String
### getAddressStreet1() {#getAddressStreet1--}
```
public final String getAddressStreet1()
```


DAG, 持卡人地址的街道部分, DL/ID, V35ANS

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


DCG, DL/ID 签发的国家。美国 = USA，加拿大 = CAN, DL/ID, F3A

**Returns:**
[USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry)
### getCustomerIDNumber() {#getCustomerIDNumber--}
```
public final String getCustomerIDNumber()
```


DAQ, 发行机构分配或计算的号码, DL/ID, V25ANS

**Returns:**
java.lang.String
### getDateOfBirth() {#getDateOfBirth--}
```
public final LocalDate getDateOfBirth()
```


DBB, 文件签发日期, MMDDCCYY（美国），CCYYMMDD（加拿大），DL/ID, F8N

**Returns:**
java.time.LocalDate
### getDocumentDiscriminator() {#getDocumentDiscriminator--}
```
public final String getDocumentDiscriminator()
```


DCF, 号码必须唯一标识发给该客户的特定文件，以区别于过去可能已发出的其他文件。此号码可用于文件区分、审计信息编号和/或库存控制等多种用途, DL/ID, V25ANS

**Returns:**
java.lang.String
### getEndorsementCodes() {#getEndorsementCodes--}
```
public final String getEndorsementCodes()
```


DCD, 管辖区特定的背书代码, DL, V5ANS

**Returns:**
java.lang.String
### getExpirationDate() {#getExpirationDate--}
```
public final LocalDate getExpirationDate()
```


DBA, 文件到期日期, MMDDCCYY（美国），CCYYMMDD（加拿大），DL/ID, F8N

**Returns:**
java.time.LocalDate
### getEyeColor() {#getEyeColor--}
```
public final USADriveIdEyeColor getEyeColor()
```


DAY, 持卡人眼睛的颜色（ANSI D-20 代码）。DL/ID, F3A

**Returns:**
[USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor)
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


DCS, 持卡人姓氏, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFamilyNameTruncation() {#getFamilyNameTruncation--}
```
public final String getFamilyNameTruncation()
```


DDE, 表示字段是否被截断的代码（截断 T），未截断 N，或未知 U, DL/ID, F1A

**Returns:**
java.lang.String
### getFirstName() {#getFirstName--}
```
public final String getFirstName()
```


DAC, 持卡人名字, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFirstNameTruncation() {#getFirstNameTruncation--}
```
public final String getFirstNameTruncation()
```


DDF, 表示字段是否被截断的代码（截断 T），未截断 N，或未知 U, DL/ID, F1A

**Returns:**
java.lang.String
### getHeight() {#getHeight--}
```
public final String getHeight()
```


DAU，持卡人身高。英寸（in）：英寸数后跟 " in"，例如 6'1'' = "073 in" 厘米（cm）：厘米数后跟 " cm"，例如 181厘米="181 cm"，DL/ID，F6ANS

**Returns:**
java.lang.String
### getIssueDate() {#getIssueDate--}
```
public final LocalDate getIssueDate()
```


DBD, 文件签发日期, MMDDCCYY（美国），CCYYMMDD（加拿大），DL/ID, F8N

**Returns:**
java.time.LocalDate
### getMiddleName() {#getMiddleName--}
```
public final String getMiddleName()
```


DAD，持卡人中间名。若有多个中间名，应使用逗号 "," 分隔。DL/ID，V40ANS

**Returns:**
java.lang.String
### getMiddleNameTruncation() {#getMiddleNameTruncation--}
```
public final String getMiddleNameTruncation()
```


DDG, 表示字段是否被截断的代码（截断 T），未截断 N，或未知 U, DL/ID, F1A

**Returns:**
java.lang.String
### getRestrictionCodes() {#getRestrictionCodes--}
```
public final String getRestrictionCodes()
```


DCB, 管辖区特定的限制代码, DL, V12ANS

**Returns:**
java.lang.String
### getSex() {#getSex--}
```
public final USADriveIdSex getSex()
```


DBC，持卡人性别。1 = 男性，2 = 女性，9 = 未指定，DL/ID，F1N

**Returns:**
[USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex)
### getVehicleClass() {#getVehicleClass--}
```
public final String getVehicleClass()
```


DCA, 管辖区特定的车辆类别/组代码, DL, V6ANS

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


DAI，持卡人地址的城市部分，DL/ID，V20ANS

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setAddressPostalCode(String value) {#setAddressPostalCode-java.lang.String-}
```
public final void setAddressPostalCode(String value)
```


DAK, 持卡人地址在美国和加拿大的邮政编码部分。如果美国的邮政编码后缀未知，将使用零填充至 9 位数字, DL/ID, F11ANS

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setAddressState(String value) {#setAddressState-java.lang.String-}
```
public final void setAddressState(String value)
```


DAJ, 持卡人地址的州部分, DL/ID, F2A

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setAddressStreet1(String value) {#setAddressStreet1-java.lang.String-}
```
public final void setAddressStreet1(String value)
```


DAG, 持卡人地址的街道部分, DL/ID, V35ANS

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setCountryIdentification(USADriveIdCountry value) {#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-}
```
public final void setCountryIdentification(USADriveIdCountry value)
```


DCG, DL/ID 签发的国家。美国 = USA，加拿大 = CAN, DL/ID, F3A

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry) |  |

### setCustomerIDNumber(String value) {#setCustomerIDNumber-java.lang.String-}
```
public final void setCustomerIDNumber(String value)
```


DAQ, 发行机构分配或计算的号码, DL/ID, V25ANS

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setDateOfBirth(LocalDate value) {#setDateOfBirth-java.time.LocalDate-}
```
public final void setDateOfBirth(LocalDate value)
```


DBB, 文件签发日期, MMDDCCYY（美国），CCYYMMDD（加拿大），DL/ID, F8N

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.time.LocalDate |  |

### setDocumentDiscriminator(String value) {#setDocumentDiscriminator-java.lang.String-}
```
public final void setDocumentDiscriminator(String value)
```


DCF, 号码必须唯一标识发给该客户的特定文件，以区别于过去可能已发出的其他文件。此号码可用于文件区分、审计信息编号和/或库存控制等多种用途, DL/ID, V25ANS

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setEndorsementCodes(String value) {#setEndorsementCodes-java.lang.String-}
```
public final void setEndorsementCodes(String value)
```


DCD, 管辖区特定的背书代码, DL, V5ANS

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setExpirationDate(LocalDate value) {#setExpirationDate-java.time.LocalDate-}
```
public final void setExpirationDate(LocalDate value)
```


DBA, 文件到期日期, MMDDCCYY（美国），CCYYMMDD（加拿大），DL/ID, F8N

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.time.LocalDate |  |

### setEyeColor(USADriveIdEyeColor value) {#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-}
```
public final void setEyeColor(USADriveIdEyeColor value)
```


DAY, 持卡人眼睛的颜色（ANSI D-20 代码）。DL/ID, F3A

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor) |  |

### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public final void setFamilyName(String value)
```


DCS, 持卡人姓氏, DL/ID, V40ANS

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setFamilyNameTruncation(String value) {#setFamilyNameTruncation-java.lang.String-}
```
public final void setFamilyNameTruncation(String value)
```


DDE, 表示字段是否被截断的代码（截断 T），未截断 N，或未知 U, DL/ID, F1A

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setFirstName(String value) {#setFirstName-java.lang.String-}
```
public final void setFirstName(String value)
```


DAC, 持卡人名字, DL/ID, V40ANS

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setFirstNameTruncation(String value) {#setFirstNameTruncation-java.lang.String-}
```
public final void setFirstNameTruncation(String value)
```


DDF, 表示字段是否被截断的代码（截断 T），未截断 N，或未知 U, DL/ID, F1A

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setHeight(String value) {#setHeight-java.lang.String-}
```
public final void setHeight(String value)
```


DAU，持卡人身高。英寸（in）：英寸数后跟 " in"，例如 6'1'' = "073 in" 厘米（cm）：厘米数后跟 " cm"，例如 181厘米="181 cm"，DL/ID，F6ANS

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setIssueDate(LocalDate value) {#setIssueDate-java.time.LocalDate-}
```
public final void setIssueDate(LocalDate value)
```


DBD, 文件签发日期, MMDDCCYY（美国），CCYYMMDD（加拿大），DL/ID, F8N

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.time.LocalDate |  |

### setMiddleName(String value) {#setMiddleName-java.lang.String-}
```
public final void setMiddleName(String value)
```


DAD，持卡人中间名。若有多个中间名，应使用逗号 "," 分隔。DL/ID，V40ANS

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setMiddleNameTruncation(String value) {#setMiddleNameTruncation-java.lang.String-}
```
public final void setMiddleNameTruncation(String value)
```


DDG, 表示字段是否被截断的代码（截断 T），未截断 N，或未知 U, DL/ID, F1A

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setRestrictionCodes(String value) {#setRestrictionCodes-java.lang.String-}
```
public final void setRestrictionCodes(String value)
```


DCB, 管辖区特定的限制代码, DL, V12ANS

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### setSex(USADriveIdSex value) {#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-}
```
public final void setSex(USADriveIdSex value)
```


DBC，持卡人性别。1 = 男性，2 = 女性，9 = 未指定，DL/ID，F1N

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex) |  |

### setVehicleClass(String value) {#setVehicleClass-java.lang.String-}
```
public final void setVehicleClass(String value)
```


DCA, 管辖区特定的车辆类别/组代码, DL, V6ANS

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

