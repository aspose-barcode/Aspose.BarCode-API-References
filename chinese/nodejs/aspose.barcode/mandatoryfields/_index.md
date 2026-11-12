---
title: "MandatoryFields"
linktitle: "MandatoryFields"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "卡片的必填元素（字段）。"
type: docs
weight: 590
url: /zh/nodejs/aspose.barcode/mandatoryfields/
---

## MandatoryFields class

卡片的必填元素（字段）。

```js
new MandatoryFields()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getAddressCity()](#getaddresscity) | DAI，持卡人地址的城市部分，DL/ID，V20ANS |
| [getAddressPostalCode()](#getaddresspostalcode) | DAK，美国和加拿大持卡人地址的邮政编码部分。如果邮政编码的后缀在 |
| [getAddressState()](#getaddressstate) | DAJ，持卡人地址的州部分，DL/ID，F2A |
| [getAddressStreet1()](#getaddressstreet1) | DAG，持卡人地址的街道部分，DL/ID，V35ANS |
| [getCountryIdentification()](#getcountryidentification) | DCG, 签发 DL/ID 的国家。美国 = USA，加拿大 = CAN, DL/ID, F3A |
| [getCustomerIDNumber()](#getcustomeridnumber) | DAQ, 由签发机构分配或计算的号码, DL/ID, V25ANS |
| [getDateOfBirth()](#getdateofbirth) | DBB, 文件签发日期，U.S. 使用 MMDDCCYY 格式，加拿大使用 CCYYMMDD 格式, DL/ID, F8N |
| [getDocumentDiscriminator()](#getdocumentdiscriminator) | DCF, 号码必须唯一标识发给该客户的特定文件，以区别于可能已发出的其他文件 |
| [getEndorsementCodes()](#getendorsementcodes) | DCD, 司法辖区特定的背书代码, DL, V5ANS |
| [getEyeColor()](#geteyecolor) | DAY, 持卡人眼睛的颜色。（ANSI D-20 代码）。DL/ID, F3A |
| [getFamilyName()](#getfamilyname) | DCS, 持卡人的姓氏, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getfamilynametruncation) | DDE, 用于指示字段是否被截断的代码（T 表示已截断，N 表示未截断，未知表示未确定是否截断） |
| [getFirstName()](#getfirstname) | DAC, 持卡人的名字, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getfirstnametruncation) | DDF, 用于指示字段是否被截断的代码（T 表示已截断，N 表示未截断，未知表示未确定是否截断） |
| [getHeight()](#getheight) | DAU, 持卡人身高。英寸（in）：英寸数后跟 " in"，例如 6'1'' = "073 in"；厘米（cm）：厘米数 |
| [getMiddleName()](#getmiddlename) | DAD, 持卡人的中间名（们）。如果有多个中间名，应以逗号 "," 分隔。 , DL |
| [getMiddleNameTruncation()](#getmiddlenametruncation) | DDG, 用于指示字段是否被截断的代码（T 表示已截断，N 表示未截断，未知表示未确定是否截断） |
| [getRestrictionCodes()](#getrestrictioncodes) | DCB, 司法辖区特定的限制代码, DL, V12ANS |
| [getSex()](#getsex) | DBC, 持卡人性别。1 = 男性，2 = 女性，9 = 未指定, DL/ID, F1N |
| [getVehicleClass()](#getvehicleclass) | DCA, 司法辖区特定的车辆类别/组代码, DL, V6ANS |
| [setAddressCity()](#setaddresscity) | DAI，持卡人地址的城市部分，DL/ID，V20ANS |
| [setAddressPostalCode()](#setaddresspostalcode) | DAK，美国和加拿大持卡人地址的邮政编码部分。如果邮政编码的后缀在 |
| [setAddressState()](#setaddressstate) | DAJ，持卡人地址的州部分，DL/ID，F2A |
| [setAddressStreet1()](#setaddressstreet1) | DAG，持卡人地址的街道部分，DL/ID，V35ANS |
| [setCountryIdentification()](#setcountryidentification) | DCG, 签发 DL/ID 的国家。美国 = USA，加拿大 = CAN, DL/ID, F3A |
| [setCustomerIDNumber()](#setcustomeridnumber) | DAQ, 由签发机构分配或计算的号码, DL/ID, V25ANS |
| [setDateOfBirth()](#setdateofbirth) | DBB, 文件签发日期，U.S. 使用 MMDDCCYY 格式，加拿大使用 CCYYMMDD 格式, DL/ID, F8N |
| [setDocumentDiscriminator()](#setdocumentdiscriminator) | DCF, 号码必须唯一标识发给该客户的特定文件，以区别于可能已发出的其他文件 |
| [setEndorsementCodes()](#setendorsementcodes) | DCD, 司法辖区特定的背书代码, DL, V5ANS |
| [setEyeColor()](#seteyecolor) | DAY, 持卡人眼睛的颜色。（ANSI D-20 代码）。DL/ID, F3A |
| [setFamilyName()](#setfamilyname) | DCS, 持卡人的姓氏, DL/ID, V40ANS |
| [setFamilyNameTruncation()](#setfamilynametruncation) | DDE, 用于指示字段是否被截断的代码（T 表示已截断，N 表示未截断，未知表示未确定是否截断） |
| [setFirstName()](#setfirstname) | DAC, 持卡人的名字, DL/ID, V40ANS |
| [setFirstNameTruncation()](#setfirstnametruncation) | DDF, 用于指示字段是否被截断的代码（T 表示已截断，N 表示未截断，未知表示未确定是否截断） |
| [setHeight()](#setheight) | DAU, 持卡人身高。英寸（in）：英寸数后跟 " in"，例如 6'1'' = "073 in"；厘米（cm）：厘米数 |
| [setMiddleName()](#setmiddlename) | DAD, 持卡人的中间名（们）。如果有多个中间名，应以逗号 "," 分隔。 , DL |
| [setMiddleNameTruncation()](#setmiddlenametruncation) | DDG, 用于指示字段是否被截断的代码（T 表示已截断，N 表示未截断，未知表示未确定是否截断） |
| [setRestrictionCodes()](#setrestrictioncodes) | DCB, 司法辖区特定的限制代码, DL, V12ANS |
| [setSex()](#setsex) | DBC, 持卡人性别。1 = 男性，2 = 女性，9 = 未指定, DL/ID, F1N |
| [setVehicleClass()](#setvehicleclass) | DCA, 司法辖区特定的车辆类别/组代码, DL, V6ANS |

### getAddressCity() {#getaddresscity}

DAI，持卡人地址的城市部分，DL/ID，V20ANS

### getAddressPostalCode() {#getaddresspostalcode}

DAK, 持卡人地址在美国和加拿大的邮政编码部分。如果美国的邮政编码后缀未知，将使用零填充至 9 位数字。DL/ID, F11ANS

### getAddressState() {#getaddressstate}

DAJ，持卡人地址的州部分，DL/ID，F2A

### getAddressStreet1() {#getaddressstreet1}

DAG，持卡人地址的街道部分，DL/ID，V35ANS

### getCountryIdentification() {#getcountryidentification}

DCG, 签发 DL/ID 的国家。美国 = USA，加拿大 = CAN, DL/ID, F3A

### getCustomerIDNumber() {#getcustomeridnumber}

DAQ, 由签发机构分配或计算的号码, DL/ID, V25ANS

### getDateOfBirth() {#getdateofbirth}

DBB, 文件签发日期，U.S. 使用 MMDDCCYY 格式，加拿大使用 CCYYMMDD 格式, DL/ID, F8N

### getDocumentDiscriminator() {#getdocumentdiscriminator}

DCF, 号码必须唯一标识发给该客户的特定文件，以区别于过去可能已发出的其他文件。此号码可用于文件区分、审计信息编号和/或库存控制，DL/ID, V25ANS

### getEndorsementCodes() {#getendorsementcodes}

DCD, 司法辖区特定的背书代码, DL, V5ANS

### getEyeColor() {#geteyecolor}

DAY, 持卡人眼睛的颜色。（ANSI D-20 代码）。DL/ID, F3A

### getFamilyName() {#getfamilyname}

DCS, 持卡人的姓氏, DL/ID, V40ANS

### getFamilyNameTruncation() {#getfamilynametruncation}

DDE, 用于指示字段是否被截断的代码（T 表示已截断，N 表示未截断，U 表示未知是否截断），DL/ID, F1A

### getFirstName() {#getfirstname}

DAC, 持卡人的名字, DL/ID, V40ANS

### getFirstNameTruncation() {#getfirstnametruncation}

DDF, 用于指示字段是否被截断的代码（T 表示已截断，N 表示未截断，U 表示未知是否截断），DL/ID, F1A

### getHeight() {#getheight}

DAU, 持卡人身高。英寸（in）：英寸数后跟 " in"，例如 6'1'' = "073 in"；厘米（cm）：厘米数后跟 " cm"，例如 181 厘米 = "181 cm"，DL/ID, F6ANS

### getMiddleName() {#getmiddlename}

DAD, 持卡人的中间名（们）。如果有多个中间名，应以逗号 "," 分隔。 , DL/ID, V40ANS

### getMiddleNameTruncation() {#getmiddlenametruncation}

DDG, 用于指示字段是否被截断的代码（T 表示已截断，N 表示未截断，U 表示未知是否截断），DL/ID, F1A

### getRestrictionCodes() {#getrestrictioncodes}

DCB, 司法辖区特定的限制代码, DL, V12ANS

### getSex() {#getsex}

DBC, 持卡人性别。1 = 男性，2 = 女性，9 = 未指定, DL/ID, F1N

### getVehicleClass() {#getvehicleclass}

DCA, 司法辖区特定的车辆类别/组代码, DL, V6ANS

### setAddressCity() {#setaddresscity}

DAI，持卡人地址的城市部分，DL/ID，V20ANS

### setAddressPostalCode() {#setaddresspostalcode}

DAK, 持卡人地址在美国和加拿大的邮政编码部分。如果美国的邮政编码后缀未知，将使用零填充至 9 位数字。DL/ID, F11ANS

### setAddressState() {#setaddressstate}

DAJ，持卡人地址的州部分，DL/ID，F2A

### setAddressStreet1() {#setaddressstreet1}

DAG，持卡人地址的街道部分，DL/ID，V35ANS

### setCountryIdentification() {#setcountryidentification}

DCG, 签发 DL/ID 的国家。美国 = USA，加拿大 = CAN, DL/ID, F3A

### setCustomerIDNumber() {#setcustomeridnumber}

DAQ, 由签发机构分配或计算的号码, DL/ID, V25ANS

### setDateOfBirth() {#setdateofbirth}

DBB, 文件签发日期，U.S. 使用 MMDDCCYY 格式，加拿大使用 CCYYMMDD 格式, DL/ID, F8N

### setDocumentDiscriminator() {#setdocumentdiscriminator}

DCF, 号码必须唯一标识发给该客户的特定文件，以区别于过去可能已发出的其他文件。此号码可用于文件区分、审计信息编号和/或库存控制，DL/ID, V25ANS

### setEndorsementCodes() {#setendorsementcodes}

DCD, 司法辖区特定的背书代码, DL, V5ANS

### setEyeColor() {#seteyecolor}

DAY, 持卡人眼睛的颜色。（ANSI D-20 代码）。DL/ID, F3A

### setFamilyName() {#setfamilyname}

DCS, 持卡人的姓氏, DL/ID, V40ANS

### setFamilyNameTruncation() {#setfamilynametruncation}

DDE, 用于指示字段是否被截断的代码（T 表示已截断，N 表示未截断，U 表示未知是否截断），DL/ID, F1A

### setFirstName() {#setfirstname}

DAC, 持卡人的名字, DL/ID, V40ANS

### setFirstNameTruncation() {#setfirstnametruncation}

DDF, 用于指示字段是否被截断的代码（T 表示已截断，N 表示未截断，U 表示未知是否截断），DL/ID, F1A

### setHeight() {#setheight}

DAU, 持卡人身高。英寸（in）：英寸数后跟 " in"，例如 6'1'' = "073 in"；厘米（cm）：厘米数后跟 " cm"，例如 181 厘米 = "181 cm"，DL/ID, F6ANS

### setMiddleName() {#setmiddlename}

DAD, 持卡人的中间名（们）。如果有多个中间名，应以逗号 "," 分隔。 , DL/ID, V40ANS

### setMiddleNameTruncation() {#setmiddlenametruncation}

DDG, 用于指示字段是否被截断的代码（T 表示已截断，N 表示未截断，U 表示未知是否截断），DL/ID, F1A

### setRestrictionCodes() {#setrestrictioncodes}

DCB, 司法辖区特定的限制代码, DL, V12ANS

### setSex() {#setsex}

DBC, 持卡人性别。1 = 男性，2 = 女性，9 = 未指定, DL/ID, F1N

### setVehicleClass() {#setvehicleclass}

DCA, 司法辖区特定的车辆类别/组代码, DL, V6ANS
