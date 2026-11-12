---
title: "OptionalFields"
linktitle: "OptionalFields"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "卡片的可选元素（字段）"
type: docs
weight: 730
url: /zh/nodejs/aspose.barcode/optionalfields/
---

## OptionalFields class

卡片的可选元素（字段）

```js
new OptionalFields()
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getAliasAKAFamilyName()](#getaliasakafamilyname) | DBN，持卡人已知的其他姓氏，DL/ID，V10ANS |
| [getAliasAKAGivenName()](#getaliasakagivenname) | DBG，持卡人已知的其他名字，DL/ID，V15ANS |
| [getAliasAKASuffixName()](#getaliasakasuffixname) | DBS，持卡人已知的其他后缀，DL/ID，V5ANS |
| [getAuditInformation()](#getauditinformation) | DCJ，一串字母和/或数字，用于标识驾驶执照/身份证的制作时间、地点和制作者。如果 a |
| [getCardRevisionDate()](#getcardrevisiondate) | DDB，DHS 必填字段，指示最近一次版本更改或对可见格式的修改日期。 |
| [getComplianceType()](#getcompliancetype) | DDA，DHS 必填字段，指示合规性：“F” = 合规；以及，“N” = 不合规，DL/ID，F1A。 |
| [getEndorsementCodeDescription()](#getendorsementcodedescription) | DCQ，解释特定司法辖区代码，指示授予持卡人的额外驾驶特权的文本。 |
| [getHairColor()](#gethaircolor) | DAZ，光头，黑色，金发，棕色，灰色，红色/赤褐色，沙色，白色，未知。如果发证司法辖区希望缩写。 |
| [getHAZMATEndorsementExpDate()](#gethazmatendorsementexpdate) | DDC，文件授予的危险品背书失效的日期。（美国使用 MMDDCCYY，加拿大使用 CC…）。 |
| [getInventoryControlNumber()](#getinventorycontrolnumber) | DCK，一串附加在用于生产的原材料（卡纸、层压板等）上的字母和/或数字。 |
| [getLimitedDurationDocIndicator()](#getlimiteddurationdocindicator) | DDD，DHS 必填字段，指示持卡人拥有临时合法状态 = “1”，DL/ID，F1N。 |
| [getNameSuffix()](#getnamesuffix) | DCU，姓名后缀（如果司法辖区参与需要姓名后缀的系统（PDPS、CDLIS 等），则必须提供后缀）。 |
| [getOrganDonorIndicator()](#getorgandonorindicator) | DDK，指示持卡人是器官捐献者的字段 = “1”，DL/ID，F1N。 |
| [getPlaceOfBirth()](#getplaceofbirth) | DCI，国家和市镇和/或州/省，DL/ID，V33A。 |
| [getRaceEthnicity()](#getraceethnicity) | DCL，持卡人的种族或族裔代码，依据 AAMVA D20 定义，DL/ID，V3A。 |
| [getRestrictionCodeDescription()](#getrestrictioncodedescription) | DCR，描述特定司法辖区限制代码（s）的文本，这些代码限制驾驶特权，DL，V50ANS。 |
| [getStandardEndorsementCode()](#getstandardendorsementcode) | DCN，持卡人的标准背书代码。请参阅 D20 中的代码。此数据元素是未来工作的占位符。 |
| [getStandardRestrictionCode()](#getstandardrestrictioncode) | DCO，持卡人的标准限制代码。请参阅 D20 中的代码。此数据元素是未来工作的占位符。 |
| [getStandardVehClassification()](#getstandardvehclassification) | DCM，持卡人的标准车辆分类代码。此数据元素是未来工作中标准化的占位符。 |
| [getUnder18Until()](#getunder18until) | DDH，持卡人年满 18 岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N。 |
| [getUnder21Until()](#getunder21until) | DDJ，持卡人年满 21 岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N。 |
| [getVehClassDescription()](#getvehclassdescription) | DCP，解释特定司法辖区代码（s）的文本，说明持卡人被授权驾驶的车辆分类。 |
| [getVeteranIndicator()](#getveteranindicator) | DDL，指示持卡人是退伍军人的字段 = “1”，DL/ID，F1N。 |
| [getWeightKilograms()](#getweightkilograms) | DAX，持卡人的体重（千克），例如 84 kg = “084”，DL/ID，F3N。 |
| [getWeightPounds()](#getweightpounds) | DAW，持卡人的体重（磅），例如 185 lb = “185”，DL/ID，F3N。 |
| [getWeightRange()](#getweightrange) | DCE，指示持卡人的大致体重范围：0 = 最高 31 kg（最高 70 磅），1 = 32 – 45 kg（71 – 100 磅）。 |
| [setAddressStreet2()](#setaddressstreet2) | DAH，持卡人地址街道部分的第二行，DL/ID，V35ANS。 |
| [setAliasAKAFamilyName()](#setaliasakafamilyname) | DBN，持卡人已知的其他姓氏，DL/ID，V10ANS |
| [setAliasAKAGivenName()](#setaliasakagivenname) | DBG，持卡人已知的其他名字，DL/ID，V15ANS |
| [setAliasAKASuffixName()](#setaliasakasuffixname) | DBS，持卡人已知的其他后缀，DL/ID，V5ANS |
| [setAuditInformation()](#setauditinformation) | DCJ，一串字母和/或数字，用于标识驾驶执照/身份证的制作时间、地点和制作者。如果 a |
| [setCardRevisionDate()](#setcardrevisiondate) | DDB，DHS 必填字段，指示最近一次版本更改或对可见格式的修改日期。 |
| [setComplianceType()](#setcompliancetype) | DDA，DHS 必填字段，指示合规性：“F” = 合规；以及，“N” = 不合规，DL/ID，F1A。 |
| [setEndorsementCodeDescription()](#setendorsementcodedescription) | DCQ，解释特定司法辖区代码，指示授予持卡人的额外驾驶特权的文本。 |
| [setHairColor()](#sethaircolor) | DAZ，光头，黑色，金发，棕色，灰色，红色/赤褐色，沙色，白色，未知。如果发证司法辖区希望缩写。 |
| [setInventoryControlNumber()](#setinventorycontrolnumber) | DCK，一串附加在用于生产的原材料（卡纸、层压板等）上的字母和/或数字。 |
| [setLimitedDurationDocIndicator()](#setlimiteddurationdocindicator) | DDD，DHS 必填字段，指示持卡人拥有临时合法状态 = “1”，DL/ID，F1N。 |
| [setNameSuffix()](#setnamesuffix) | DCU，姓名后缀（如果司法辖区参与需要姓名后缀的系统（PDPS、CDLIS 等），则必须提供后缀）。 |
| [setOrganDonorIndicator()](#setorgandonorindicator) | DDK，指示持卡人是器官捐献者的字段 = “1”，DL/ID，F1N。 |
| [setPlaceOfBirth()](#setplaceofbirth) | DCI，国家和市镇和/或州/省，DL/ID，V33A。 |
| [setRaceEthnicity()](#setraceethnicity) | DCL，持卡人的种族或族裔代码，依据 AAMVA D20 定义，DL/ID，V3A。 |
| [setRestrictionCodeDescription()](#setrestrictioncodedescription) | DCR，描述特定司法辖区限制代码（s）的文本，这些代码限制驾驶特权，DL，V50ANS。 |
| [setStandardEndorsementCode()](#setstandardendorsementcode) | DCN，持卡人的标准背书代码。请参阅 D20 中的代码。此数据元素是未来工作的占位符。 |
| [setStandardRestrictionCode()](#setstandardrestrictioncode) | DCO，持卡人的标准限制代码。请参阅 D20 中的代码。此数据元素是未来工作的占位符。 |
| [setStandardVehClassification()](#setstandardvehclassification) | DCM，持卡人的标准车辆分类代码。此数据元素是未来工作中标准化的占位符。 |
| [setUnder18Until()](#setunder18until) | DDI，持卡人年满 19 岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N。 |
| [setUnder19Until()](#setunder19until) | DDI，持卡人年满 19 岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N。 |
| [setUnder21Until()](#setunder21until) | DDJ，持卡人年满 21 岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N。 |
| [setVehClassDescription()](#setvehclassdescription) | DCP，解释特定司法辖区代码（s）的文本，说明持卡人被授权驾驶的车辆分类。 |
| [setVeteranIndicator()](#setveteranindicator) | DDL，指示持卡人是退伍军人的字段 = “1”，DL/ID，F1N。 |
| [setWeightKilograms()](#setweightkilograms) | DAX，持卡人的体重（千克），例如 84 kg = “084”，DL/ID，F3N。 |
| [setWeightPounds()](#setweightpounds) | DAW，持卡人的体重（磅），例如 185 lb = “185”，DL/ID，F3N。 |
| [setWeightRange()](#setweightrange) | DCE，指示持卡人的大致体重范围：0 = 最高 31 kg（最高 70 磅），1 = 32 – 45 kg（71 – 100 磅）。 |

### getAliasAKAFamilyName() {#getaliasakafamilyname}

DBN，持卡人已知的其他姓氏，DL/ID，V10ANS

### getAliasAKAGivenName() {#getaliasakagivenname}

DBG，持卡人已知的其他名字，DL/ID，V15ANS

### getAliasAKASuffixName() {#getaliasakasuffixname}

DBS，持卡人已知的其他后缀，DL/ID，V5ANS

### getAuditInformation() {#getauditinformation}

DCJ，一串字母和/或数字，用于标识驾驶执照/身份证的制作时间、地点和制作者。如果卡片或 MRT 上未使用审计信息，则必须将其记录在驾驶员记录中，DL/ID，V25ANS。

### getCardRevisionDate() {#getcardrevisiondate}

DDB，DHS 必填字段，指示最近一次版本更改或对 DL/ID 可见格式的修改日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N

### getComplianceType() {#getcompliancetype}

DDA，DHS 必填字段，指示合规性：“F” = 合规；以及，“N” = 不合规，DL/ID，F1A。

### getEndorsementCodeDescription() {#getendorsementcodedescription}

DCQ，解释特定司法辖区代码的文本，这些代码指示授予持卡人超出车辆类别的额外驾驶权限，DL，V50ANS

### getHairColor() {#gethaircolor}

DAZ，光头，黑色，金发，棕色，灰色，红色/赤褐色，沙色，白色，未知。如果发行司法辖区希望缩写颜色，必须使用 AAMVA D20 中提供的三字符代码，DL/ID，V12A

### getHAZMATEndorsementExpDate() {#gethazmatendorsementexpdate}

DDC，文件授予的危险品背书失效的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL，F8N

### getInventoryControlNumber() {#getinventorycontrolnumber}

DCK，附加在用于生产驾驶执照和身份证的原材料（卡纸、层压板等）上的字母和/或数字串。（DHS 推荐字段），DL/ID，V25ANS

### getLimitedDurationDocIndicator() {#getlimiteddurationdocindicator}

DDD，DHS 必填字段，指示持卡人拥有临时合法状态 = “1”，DL/ID，F1N。

### getNameSuffix() {#getnamesuffix}

DCU，姓名后缀（如果司法辖区参与需要姓名后缀的系统（PDPS、CDLIS 等），则必须收集并在 DL/ID 以及 MRT 中显示该后缀）。JR（Junior），SR（Senior），1ST 或 I（First），最高可至 9TH 或 IX（Ninth），DL/ID，V5ANS

### getOrganDonorIndicator() {#getorgandonorindicator}

DDK，指示持卡人是器官捐献者的字段 = “1”，DL/ID，F1N。

### getPlaceOfBirth() {#getplaceofbirth}

DCI，国家和市镇和/或州/省，DL/ID，V33A。

### getRaceEthnicity() {#getraceethnicity}

DCL，持卡人的种族或族裔代码，依据 AAMVA D20 定义，DL/ID，V3A。

### getRestrictionCodeDescription() {#getrestrictioncodedescription}

DCR，描述特定司法辖区限制代码（s）的文本，这些代码限制驾驶特权，DL，V50ANS。

### getStandardEndorsementCode() {#getstandardendorsementcode}

DCN，持卡人的标准背书代码。请参见 D20 中的代码。此数据元素是未来标准化背书代码工作的占位符，DL，F5AN

### getStandardRestrictionCode() {#getstandardrestrictioncode}

DCO，持卡人的标准限制代码。请参见 D20 中的代码。此数据元素是未来标准化限制代码工作的占位符，DL，F12AN

### getStandardVehClassification() {#getstandardvehclassification}

DCM，持卡人的标准车辆分类代码。此数据元素是未来标准化车辆分类工作的占位符，DL，F4AN

### getUnder18Until() {#getunder18until}

DDH，持卡人年满 18 岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N。

### getUnder21Until() {#getunder21until}

DDJ，持卡人年满 21 岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N。

### getVehClassDescription() {#getvehclassdescription}

DCP，解释特定司法辖区代码的文本，这些代码用于持卡人被授权驾驶的车辆分类，DL，V50ANS

### getVeteranIndicator() {#getveteranindicator}

DDL，指示持卡人是退伍军人的字段 = “1”，DL/ID，F1N。

### getWeightKilograms() {#getweightkilograms}

DAX，持卡人的体重（千克），例如 84 kg = “084”，DL/ID，F3N。

### getWeightPounds() {#getweightpounds}

DAW，持卡人的体重（磅），例如 185 lb = “185”，DL/ID，F3N。

### getWeightRange() {#getweightrange}

DCE，指示持卡人的大致体重范围：0 = 最高 31 kg（最高 70 磅），1 = 32 – 45 kg（71 – 100 磅），2 = 46 - 59 kg（101 – 130 磅），3 = 60 - 70 kg（131 – 160 磅），4 = 71 - 86 kg（161 – 190 磅），5 = 87 - 100 kg（191 – 220 磅），6 = 101 - 113 kg（221 – 250 磅），7 = 114 - 127 kg（251 – 280 磅），8 = 128 – 145 kg（281 – 320 磅），9 = 146+ kg（321+ 磅），DL/ID，F1N

### setAddressStreet2() {#setaddressstreet2}

DAH，持卡人地址街道部分的第二行，DL/ID，V35ANS。

### setAliasAKAFamilyName() {#setaliasakafamilyname}

DBN，持卡人已知的其他姓氏，DL/ID，V10ANS

### setAliasAKAGivenName() {#setaliasakagivenname}

DBG，持卡人已知的其他名字，DL/ID，V15ANS

### setAliasAKASuffixName() {#setaliasakasuffixname}

DBS，持卡人已知的其他后缀，DL/ID，V5ANS

### setAuditInformation() {#setauditinformation}

DCJ，一串字母和/或数字，用于标识驾驶执照/身份证的制作时间、地点和制作者。如果卡片或 MRT 上未使用审计信息，则必须将其记录在驾驶员记录中，DL/ID，V25ANS。

### setCardRevisionDate() {#setcardrevisiondate}

DDB，DHS 必填字段，指示最近一次版本更改或对 DL/ID 可见格式的修改日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N

### setComplianceType() {#setcompliancetype}

DDA，DHS 必填字段，指示合规性：“F” = 合规；以及，“N” = 不合规，DL/ID，F1A。

### setEndorsementCodeDescription() {#setendorsementcodedescription}

DCQ，解释特定司法辖区代码的文本，这些代码指示授予持卡人超出车辆类别的额外驾驶权限，DL，V50ANS

### setHairColor() {#sethaircolor}

DAZ，光头，黑色，金发，棕色，灰色，红色/赤褐色，沙色，白色，未知。如果发行司法辖区希望缩写颜色，必须使用 AAMVA D20 中提供的三字符代码，DL/ID，V12A

### setInventoryControlNumber() {#setinventorycontrolnumber}

DCK，附加在用于生产驾驶执照和身份证的原材料（卡纸、层压板等）上的字母和/或数字串。（DHS 推荐字段），DL/ID，V25ANS

### setLimitedDurationDocIndicator() {#setlimiteddurationdocindicator}

DDD，DHS 必填字段，指示持卡人拥有临时合法状态 = “1”，DL/ID，F1N。

### setNameSuffix() {#setnamesuffix}

DCU，姓名后缀（如果司法辖区参与需要姓名后缀的系统（PDPS、CDLIS 等），则必须收集并在 DL/ID 以及 MRT 中显示该后缀）。JR（Junior），SR（Senior），1ST 或 I（First），最高可至 9TH 或 IX（Ninth），DL/ID，V5ANS

### setOrganDonorIndicator() {#setorgandonorindicator}

DDK，指示持卡人是器官捐献者的字段 = “1”，DL/ID，F1N。

### setPlaceOfBirth() {#setplaceofbirth}

DCI，国家和市镇和/或州/省，DL/ID，V33A。

### setRaceEthnicity() {#setraceethnicity}

DCL，持卡人的种族或族裔代码，依据 AAMVA D20 定义，DL/ID，V3A。

### setRestrictionCodeDescription() {#setrestrictioncodedescription}

DCR，描述特定司法辖区限制代码（s）的文本，这些代码限制驾驶特权，DL，V50ANS。

### setStandardEndorsementCode() {#setstandardendorsementcode}

DCN，持卡人的标准背书代码。请参见 D20 中的代码。此数据元素是未来标准化背书代码工作的占位符，DL，F5AN

### setStandardRestrictionCode() {#setstandardrestrictioncode}

DCO，持卡人的标准限制代码。请参见 D20 中的代码。此数据元素是未来标准化限制代码工作的占位符，DL，F12AN

### setStandardVehClassification() {#setstandardvehclassification}

DCM，持卡人的标准车辆分类代码。此数据元素是未来标准化车辆分类工作的占位符，DL，F4AN

### setUnder18Until() {#setunder18until}

DDI，持卡人年满 19 岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N。

### setUnder19Until() {#setunder19until}

DDI，持卡人年满 19 岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N。

### setUnder21Until() {#setunder21until}

DDJ，持卡人年满 21 岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N。

### setVehClassDescription() {#setvehclassdescription}

DCP，解释特定司法辖区代码的文本，这些代码用于持卡人被授权驾驶的车辆分类，DL，V50ANS

### setVeteranIndicator() {#setveteranindicator}

DDL，指示持卡人是退伍军人的字段 = “1”，DL/ID，F1N。

### setWeightKilograms() {#setweightkilograms}

DAX，持卡人的体重（千克），例如 84 kg = “084”，DL/ID，F3N。

### setWeightPounds() {#setweightpounds}

DAW，持卡人的体重（磅），例如 185 lb = “185”，DL/ID，F3N。

### setWeightRange() {#setweightrange}

DCE，指示持卡人的大致体重范围：0 = 最高 31 kg（最高 70 磅），1 = 32 – 45 kg（71 – 100 磅），2 = 46 - 59 kg（101 – 130 磅），3 = 60 - 70 kg（131 – 160 磅），4 = 71 - 86 kg（161 – 190 磅），5 = 87 - 100 kg（191 – 220 磅），6 = 101 - 113 kg（221 – 250 磅），7 = 114 - 127 kg（251 – 280 磅），8 = 128 – 145 kg（281 – 320 磅），9 = 146+ kg（321+ 磅），DL/ID，F1N
