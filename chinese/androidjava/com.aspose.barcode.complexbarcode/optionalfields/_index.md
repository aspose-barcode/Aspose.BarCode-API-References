---
title: USADriveIdCodetext.OptionalFields
second_title: Aspose.BarCode 适用于 Android 通过 Java API 参考
description: 卡片的可选元素字段
type: docs
weight: 11
url: /zh/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.OptionalFields
```

卡片的可选元素（字段）
## Constructors

| Constructor | 描述 |
| --- | --- |
| [OptionalFields()](#OptionalFields--) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressStreet2()](#getAddressStreet2--) | DAH，持卡人地址街道部分的第二行，DL/ID，V35ANS |
| [getAliasAKAFamilyName()](#getAliasAKAFamilyName--) | DBN，持卡人已知的其他姓氏，DL/ID，V10ANS |
| [getAliasAKAGivenName()](#getAliasAKAGivenName--) | DBG，持卡人已知的其他名字，DL/ID，V15ANS |
| [getAliasAKASuffixName()](#getAliasAKASuffixName--) | DBS，持卡人已知的其他后缀，DL/ID，V5ANS |
| [getAuditInformation()](#getAuditInformation--) | DCJ，一串字母和/或数字，用于标识驾驶执照/身份证的制作时间、地点和制作者。 |
| [getCardRevisionDate()](#getCardRevisionDate--) | DDB，DHS 必需字段，指示 DL/ID 可见格式最近一次版本更改或修改的日期。 |
| [getClass()](#getClass--) |  |
| [getComplianceType()](#getComplianceType--) | DDA，DHS 必需字段，指示合规性：\u201cF\u201d = 合规；以及，\u201cN\u201d = 不合规，DL/ID，F1A |
| [getEndorsementCodeDescription()](#getEndorsementCodeDescription--) | DCQ，解释特定司法辖区代码的文本，这些代码指示授予持卡人超出车辆类别的额外驾驶权限，DL，V50ANS |
| [getHAZMATEndorsementExpDate()](#getHAZMATEndorsementExpDate--) | DDC，文件授予的危险品背书失效的日期。 |
| [getHairColor()](#getHairColor--) | DAZ，秃头，黑色，金发，棕色，灰色，红色/栗色，浅色，白色，未知。 |
| [getInventoryControlNumber()](#getInventoryControlNumber--) | DCK，一串字母和/或数字，贴在用于生产驾驶执照和身份证的原材料（卡纸、层压板等）上。 |
| [getLimitedDurationDocIndicator()](#getLimitedDurationDocIndicator--) | DDD，DHS 必需字段，指示持卡人拥有临时合法状态 = \u201c1\u201d，DL/ID，F1N |
| [getNameSuffix()](#getNameSuffix--) | DCU，姓名后缀（如果司法辖区参与需要姓名后缀的系统（PDPS、CDLIS 等），则必须收集并在 DL/ID 和 MRT 中显示该后缀）。 |
| [getOrganDonorIndicator()](#getOrganDonorIndicator--) | DDK，指示持卡人是器官捐献者的字段 = \u201c1\u201d，DL/ID，F1N |
| [getPlaceOfBirth()](#getPlaceOfBirth--) | DCI，国家和市镇和/或州/省，DL/ID，V33A |
| [getRaceEthnicity()](#getRaceEthnicity--) | DCL，持卡人种族或族裔代码，依据 AAMVA D20 定义，DL/ID，V3A |
| [getRestrictionCodeDescription()](#getRestrictionCodeDescription--) | DCR，描述特定司法辖区限制代码的文本，这些代码限制驾驶权限，DL，V50ANS |
| [getStandardEndorsementCode()](#getStandardEndorsementCode--) | DCN，持卡人的标准背书代码。 |
| [getStandardRestrictionCode()](#getStandardRestrictionCode--) | DCO，持卡人的标准限制代码。 |
| [getStandardVehClassification()](#getStandardVehClassification--) | DCM，持卡人的标准车辆分类代码。 |
| [getUnder18Until()](#getUnder18Until--) | DDH，持卡人年满18岁的日期。 |
| [getUnder19Until()](#getUnder19Until--) | DDI，持卡人年满19岁的日期。 |
| [getUnder21Until()](#getUnder21Until--) | DDJ，持卡人年满21岁的日期。 |
| [getVehClassDescription()](#getVehClassDescription--) | DCP，解释持卡人被授权驾驶的车辆分类的司法辖区特定代码的文本，DL，V50ANS |
| [getVeteranIndicator()](#getVeteranIndicator--) | DDL，指示持卡人是退伍军人的字段 = \u201c1\u201d，DL/ID，F1N |
| [getWeightKilograms()](#getWeightKilograms--) | DAX，持卡人的体重（千克），示例。 |
| [getWeightPounds()](#getWeightPounds--) | DAW，持卡人的体重（磅），示例。 |
| [getWeightRange()](#getWeightRange--) | DCE，指示持卡人大致体重范围：0 = up to 31 kg(up to 70 lbs), 1 = 32 – 45 kg(71 – 100 lbs), 2 = 46 - 59 kg(101 – 130 lbs), 3 = 60 - 70 kg(131 – 160 lbs), 4 = 71 - 86 kg(161 – 190 lbs), 5 = 87 - 100 kg(191 – 220 lbs), 6 = 101 - 113 kg(221 – 250 lbs), 7 = 114 - 127 kg(251 – 280 lbs), 8 = 128 – 145 kg(281 – 320 lbs), 9 = 146+ kg(321+ lbs)，DL/ID，F1N |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressStreet2(String value)](#setAddressStreet2-java.lang.String-) | DAH，持卡人地址街道部分的第二行，DL/ID，V35ANS |
| [setAliasAKAFamilyName(String value)](#setAliasAKAFamilyName-java.lang.String-) | DBN，持卡人已知的其他姓氏，DL/ID，V10ANS |
| [setAliasAKAGivenName(String value)](#setAliasAKAGivenName-java.lang.String-) | DBG，持卡人已知的其他名字，DL/ID，V15ANS |
| [setAliasAKASuffixName(String value)](#setAliasAKASuffixName-java.lang.String-) | DBS，持卡人已知的其他后缀，DL/ID，V5ANS |
| [setAuditInformation(String value)](#setAuditInformation-java.lang.String-) | DCJ，一串字母和/或数字，用于标识驾驶执照/身份证的制作时间、地点和制作者。 |
| [setCardRevisionDate(LocalDate value)](#setCardRevisionDate-java.time.LocalDate-) | DDB，DHS 必需字段，指示 DL/ID 可见格式最近一次版本更改或修改的日期。 |
| [setComplianceType(String value)](#setComplianceType-java.lang.String-) | DDA，DHS 必需字段，指示合规性：\u201cF\u201d = 合规；以及，\u201cN\u201d = 不合规，DL/ID，F1A |
| [setEndorsementCodeDescription(String value)](#setEndorsementCodeDescription-java.lang.String-) | DCQ，解释特定司法辖区代码的文本，这些代码指示授予持卡人超出车辆类别的额外驾驶权限，DL，V50ANS |
| [setHairColor(USADriveIdHairColor value)](#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-) | DAZ，秃头，黑色，金发，棕色，灰色，红色/栗色，浅色，白色，未知。 |
| [setInventoryControlNumber(String value)](#setInventoryControlNumber-java.lang.String-) | DCK，一串字母和/或数字，贴在用于生产驾驶执照和身份证的原材料（卡纸、层压板等）上。 |
| [setLimitedDurationDocIndicator(String value)](#setLimitedDurationDocIndicator-java.lang.String-) | DDD，DHS 必需字段，指示持卡人拥有临时合法状态 = \u201c1\u201d，DL/ID，F1N |
| [setNameSuffix(String value)](#setNameSuffix-java.lang.String-) | DCU，姓名后缀（如果司法辖区参与需要姓名后缀的系统（PDPS、CDLIS 等），则必须收集并在 DL/ID 和 MRT 中显示该后缀）。 |
| [setOrganDonorIndicator(String value)](#setOrganDonorIndicator-java.lang.String-) | DDK，指示持卡人是器官捐献者的字段 = \u201c1\u201d，DL/ID，F1N |
| [setPlaceOfBirth(String value)](#setPlaceOfBirth-java.lang.String-) | DCI，国家和市镇和/或州/省，DL/ID，V33A |
| [setRaceEthnicity(String value)](#setRaceEthnicity-java.lang.String-) | DCL，持卡人种族或族裔代码，依据 AAMVA D20 定义，DL/ID，V3A |
| [setRestrictionCodeDescription(String value)](#setRestrictionCodeDescription-java.lang.String-) | DCR，描述特定司法辖区限制代码的文本，这些代码限制驾驶权限，DL，V50ANS |
| [setStandardEndorsementCode(String value)](#setStandardEndorsementCode-java.lang.String-) | DCN，持卡人的标准背书代码。 |
| [setStandardRestrictionCode(String value)](#setStandardRestrictionCode-java.lang.String-) | DCO，持卡人的标准限制代码。 |
| [setStandardVehClassification(String value)](#setStandardVehClassification-java.lang.String-) | DCM，持卡人的标准车辆分类代码。 |
| [setUnder18Until(LocalDate value)](#setUnder18Until-java.time.LocalDate-) | DDH，持卡人年满18岁的日期。 |
| [setUnder19Until(LocalDate value)](#setUnder19Until-java.time.LocalDate-) | DDI，持卡人年满19岁的日期。 |
| [setUnder21Until(LocalDate value)](#setUnder21Until-java.time.LocalDate-) | DDJ，持卡人年满21岁的日期。 |
| [setVehClassDescription(String value)](#setVehClassDescription-java.lang.String-) | DCP，解释持卡人被授权驾驶的车辆分类的司法辖区特定代码的文本，DL，V50ANS |
| [setVeteranIndicator(String value)](#setVeteranIndicator-java.lang.String-) | DDL，指示持卡人是退伍军人的字段 = \u201c1\u201d，DL/ID，F1N |
| [setWeightKilograms(int value)](#setWeightKilograms-int-) | DAX，持卡人的体重（千克），示例。 |
| [setWeightPounds(int value)](#setWeightPounds-int-) | DAW，持卡人的体重（磅），示例。 |
| [setWeightRange(String value)](#setWeightRange-java.lang.String-) | DCE，指示持卡人大致体重范围：0 = up to 31 kg(up to 70 lbs), 1 = 32 – 45 kg(71 – 100 lbs), 2 = 46 - 59 kg(101 – 130 lbs), 3 = 60 - 70 kg(131 – 160 lbs), 4 = 71 - 86 kg(161 – 190 lbs), 5 = 87 - 100 kg(191 – 220 lbs), 6 = 101 - 113 kg(221 – 250 lbs), 7 = 114 - 127 kg(251 – 280 lbs), 8 = 128 – 145 kg(281 – 320 lbs), 9 = 146+ kg(321+ lbs)，DL/ID，F1N |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OptionalFields() {#OptionalFields--}
```
public OptionalFields()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAddressStreet2() {#getAddressStreet2--}
```
public final String getAddressStreet2()
```


DAH，持卡人地址街道部分的第二行，DL/ID，V35ANS

**Returns:**
java.lang.String
### getAliasAKAFamilyName() {#getAliasAKAFamilyName--}
```
public final String getAliasAKAFamilyName()
```


DBN，持卡人已知的其他姓氏，DL/ID，V10ANS

**Returns:**
java.lang.String
### getAliasAKAGivenName() {#getAliasAKAGivenName--}
```
public final String getAliasAKAGivenName()
```


DBG，持卡人已知的其他名字，DL/ID，V15ANS

**Returns:**
java.lang.String
### getAliasAKASuffixName() {#getAliasAKASuffixName--}
```
public final String getAliasAKASuffixName()
```


DBS，持卡人已知的其他后缀，DL/ID，V5ANS

**Returns:**
java.lang.String
### getAuditInformation() {#getAuditInformation--}
```
public final String getAuditInformation()
```


DCJ，一串字母和/或数字，用于标识驾驶执照/身份证的制作时间、地点和制作者。如果卡片或MRT未使用审计信息，则必须在驾驶员记录中包含该信息，DL/ID，V25ANS

**Returns:**
java.lang.String
### getCardRevisionDate() {#getCardRevisionDate--}
```
public final LocalDate getCardRevisionDate()
```


DDB，DHS 必需字段，指示 DL/ID 可见格式最近一次版本更改或修改的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N

**Returns:**
java.time.LocalDate
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplianceType() {#getComplianceType--}
```
public final String getComplianceType()
```


DDA，DHS 必需字段，指示合规性：\u201cF\u201d = 合规；以及，\u201cN\u201d = 不合规，DL/ID，F1A

**Returns:**
java.lang.String
### getEndorsementCodeDescription() {#getEndorsementCodeDescription--}
```
public final String getEndorsementCodeDescription()
```


DCQ，解释特定司法辖区代码的文本，这些代码指示授予持卡人超出车辆类别的额外驾驶权限，DL，V50ANS

**Returns:**
java.lang.String
### getHAZMATEndorsementExpDate() {#getHAZMATEndorsementExpDate--}
```
public final LocalDate getHAZMATEndorsementExpDate()
```


DDC，文件授予的危险品许可失效的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL，F8N

**Returns:**
java.time.LocalDate
### getHairColor() {#getHairColor--}
```
public final USADriveIdHairColor getHairColor()
```


DAZ，光头，黑色，金发，棕色，灰色，红/栗色，沙色，白色，未知。如果签发辖区希望缩写颜色，必须使用 AAMVA D20 中提供的三字符代码，DL/ID，V12A

**Returns:**
[USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor)
### getInventoryControlNumber() {#getInventoryControlNumber--}
```
public final String getInventoryControlNumber()
```


DCK，一串附着在用于生产驾驶执照和身份证的原材料（卡纸、层压板等）上的字母和/或数字。（DHS 推荐字段），DL/ID，V25ANS

**Returns:**
java.lang.String
### getLimitedDurationDocIndicator() {#getLimitedDurationDocIndicator--}
```
public final String getLimitedDurationDocIndicator()
```


DDD，DHS 必需字段，指示持卡人拥有临时合法状态 = \u201c1\u201d，DL/ID，F1N

**Returns:**
java.lang.String
### getNameSuffix() {#getNameSuffix--}
```
public final String getNameSuffix()
```


DCU，姓名后缀（如果辖区参与需要姓名后缀的系统（PDPS、CDLIS 等），则必须收集并在 DL/ID 和 MRT 中显示后缀）。JR（Junior），SR（Senior），1ST 或 I（First），最高 9TH 或 IX（第九），DL/ID，V5ANS

**Returns:**
java.lang.String
### getOrganDonorIndicator() {#getOrganDonorIndicator--}
```
public final String getOrganDonorIndicator()
```


DDK，指示持卡人是器官捐献者的字段 = \u201c1\u201d，DL/ID，F1N

**Returns:**
java.lang.String
### getPlaceOfBirth() {#getPlaceOfBirth--}
```
public final String getPlaceOfBirth()
```


DCI，国家和市镇和/或州/省，DL/ID，V33A

**Returns:**
java.lang.String
### getRaceEthnicity() {#getRaceEthnicity--}
```
public final String getRaceEthnicity()
```


DCL，持卡人种族或族裔代码，依据 AAMVA D20 定义，DL/ID，V3A

**Returns:**
java.lang.String
### getRestrictionCodeDescription() {#getRestrictionCodeDescription--}
```
public final String getRestrictionCodeDescription()
```


DCR，描述特定司法辖区限制代码的文本，这些代码限制驾驶权限，DL，V50ANS

**Returns:**
java.lang.String
### getStandardEndorsementCode() {#getStandardEndorsementCode--}
```
public final String getStandardEndorsementCode()
```


DCN，持卡人的标准背书代码。请参阅 D20 中的代码。此数据元素是未来标准化背书代码工作的占位符，DL，F5AN

**Returns:**
java.lang.String
### getStandardRestrictionCode() {#getStandardRestrictionCode--}
```
public final String getStandardRestrictionCode()
```


DCO，持卡人的标准限制代码。请参阅 D20 中的代码。此数据元素是未来标准化限制代码工作的占位符，DL，F12AN

**Returns:**
java.lang.String
### getStandardVehClassification() {#getStandardVehClassification--}
```
public final String getStandardVehClassification()
```


DCM，持卡人的标准车辆分类代码。此数据元素是未来标准化车辆分类工作的占位符，DL，F4AN

**Returns:**
java.lang.String
### getUnder18Until() {#getUnder18Until--}
```
public final LocalDate getUnder18Until()
```


DDH，持卡人年满18岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N

**Returns:**
java.time.LocalDate
### getUnder19Until() {#getUnder19Until--}
```
public final LocalDate getUnder19Until()
```


DDI，持卡人年满19岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N

**Returns:**
java.time.LocalDate
### getUnder21Until() {#getUnder21Until--}
```
public final LocalDate getUnder21Until()
```


DDJ，持卡人年满21岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N

**Returns:**
java.time.LocalDate
### getVehClassDescription() {#getVehClassDescription--}
```
public final String getVehClassDescription()
```


DCP，解释持卡人被授权驾驶的车辆分类的司法辖区特定代码的文本，DL，V50ANS

**Returns:**
java.lang.String
### getVeteranIndicator() {#getVeteranIndicator--}
```
public final String getVeteranIndicator()
```


DDL，指示持卡人是退伍军人的字段 = \u201c1\u201d，DL/ID，F1N

**Returns:**
java.lang.String
### getWeightKilograms() {#getWeightKilograms--}
```
public final int getWeightKilograms()
```


DAX，持卡人的体重（千克），示例：84 kg = \u201c084\u201d，DL/ID，F3N

**Returns:**
int
### getWeightPounds() {#getWeightPounds--}
```
public final int getWeightPounds()
```


DAW，持卡人的体重（磅），示例：185 lb = \u201c185\u201d，DL/ID，F3N

**Returns:**
int
### getWeightRange() {#getWeightRange--}
```
public final String getWeightRange()
```


DCE，指示持卡人大致体重范围：0 = up to 31 kg(up to 70 lbs), 1 = 32 – 45 kg(71 – 100 lbs), 2 = 46 - 59 kg(101 – 130 lbs), 3 = 60 - 70 kg(131 – 160 lbs), 4 = 71 - 86 kg(161 – 190 lbs), 5 = 87 - 100 kg(191 – 220 lbs), 6 = 101 - 113 kg(221 – 250 lbs), 7 = 114 - 127 kg(251 – 280 lbs), 8 = 128 – 145 kg(281 – 320 lbs), 9 = 146+ kg(321+ lbs)，DL/ID，F1N

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




### setAddressStreet2(String value) {#setAddressStreet2-java.lang.String-}
```
public final void setAddressStreet2(String value)
```


DAH，持卡人地址街道部分的第二行，DL/ID，V35ANS

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setAliasAKAFamilyName(String value) {#setAliasAKAFamilyName-java.lang.String-}
```
public final void setAliasAKAFamilyName(String value)
```


DBN，持卡人已知的其他姓氏，DL/ID，V10ANS

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setAliasAKAGivenName(String value) {#setAliasAKAGivenName-java.lang.String-}
```
public final void setAliasAKAGivenName(String value)
```


DBG，持卡人已知的其他名字，DL/ID，V15ANS

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setAliasAKASuffixName(String value) {#setAliasAKASuffixName-java.lang.String-}
```
public final void setAliasAKASuffixName(String value)
```


DBS，持卡人已知的其他后缀，DL/ID，V5ANS

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setAuditInformation(String value) {#setAuditInformation-java.lang.String-}
```
public final void setAuditInformation(String value)
```


DCJ，一串字母和/或数字，用于标识驾驶执照/身份证的制作时间、地点和制作者。如果卡片或MRT未使用审计信息，则必须在驾驶员记录中包含该信息，DL/ID，V25ANS

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setCardRevisionDate(LocalDate value) {#setCardRevisionDate-java.time.LocalDate-}
```
public final void setCardRevisionDate(LocalDate value)
```


DDB，DHS 必需字段，指示 DL/ID 可见格式最近一次版本更改或修改的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.time.LocalDate |  |

### setComplianceType(String value) {#setComplianceType-java.lang.String-}
```
public final void setComplianceType(String value)
```


DDA，DHS 必需字段，指示合规性：\u201cF\u201d = 合规；以及，\u201cN\u201d = 不合规，DL/ID，F1A

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setEndorsementCodeDescription(String value) {#setEndorsementCodeDescription-java.lang.String-}
```
public final void setEndorsementCodeDescription(String value)
```


DCQ，解释特定司法辖区代码的文本，这些代码指示授予持卡人超出车辆类别的额外驾驶权限，DL，V50ANS

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setHairColor(USADriveIdHairColor value) {#setHairColor-com.aspose.barcode.complexbarcode.USADriveIdHairColor-}
```
public final void setHairColor(USADriveIdHairColor value)
```


DAZ，光头，黑色，金发，棕色，灰色，红/栗色，沙色，白色，未知。如果签发辖区希望缩写颜色，必须使用 AAMVA D20 中提供的三字符代码，DL/ID，V12A

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [USADriveIdHairColor](../../com.aspose.barcode.complexbarcode/usadriveidhaircolor) |  |

### setInventoryControlNumber(String value) {#setInventoryControlNumber-java.lang.String-}
```
public final void setInventoryControlNumber(String value)
```


DCK，一串附着在用于生产驾驶执照和身份证的原材料（卡纸、层压板等）上的字母和/或数字。（DHS 推荐字段），DL/ID，V25ANS

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setLimitedDurationDocIndicator(String value) {#setLimitedDurationDocIndicator-java.lang.String-}
```
public final void setLimitedDurationDocIndicator(String value)
```


DDD，DHS 必需字段，指示持卡人拥有临时合法状态 = \u201c1\u201d，DL/ID，F1N

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setNameSuffix(String value) {#setNameSuffix-java.lang.String-}
```
public final void setNameSuffix(String value)
```


DCU，姓名后缀（如果辖区参与需要姓名后缀的系统（PDPS、CDLIS 等），则必须收集并在 DL/ID 和 MRT 中显示后缀）。JR（Junior），SR（Senior），1ST 或 I（First），最高 9TH 或 IX（第九），DL/ID，V5ANS

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setOrganDonorIndicator(String value) {#setOrganDonorIndicator-java.lang.String-}
```
public final void setOrganDonorIndicator(String value)
```


DDK，指示持卡人是器官捐献者的字段 = \u201c1\u201d，DL/ID，F1N

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setPlaceOfBirth(String value) {#setPlaceOfBirth-java.lang.String-}
```
public final void setPlaceOfBirth(String value)
```


DCI，国家和市镇和/或州/省，DL/ID，V33A

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setRaceEthnicity(String value) {#setRaceEthnicity-java.lang.String-}
```
public final void setRaceEthnicity(String value)
```


DCL，持卡人种族或族裔代码，依据 AAMVA D20 定义，DL/ID，V3A

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setRestrictionCodeDescription(String value) {#setRestrictionCodeDescription-java.lang.String-}
```
public final void setRestrictionCodeDescription(String value)
```


DCR，描述特定司法辖区限制代码的文本，这些代码限制驾驶权限，DL，V50ANS

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setStandardEndorsementCode(String value) {#setStandardEndorsementCode-java.lang.String-}
```
public final void setStandardEndorsementCode(String value)
```


DCN，持卡人的标准背书代码。请参阅 D20 中的代码。此数据元素是未来标准化背书代码工作的占位符，DL，F5AN

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setStandardRestrictionCode(String value) {#setStandardRestrictionCode-java.lang.String-}
```
public final void setStandardRestrictionCode(String value)
```


DCO，持卡人的标准限制代码。请参阅 D20 中的代码。此数据元素是未来标准化限制代码工作的占位符，DL，F12AN

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setStandardVehClassification(String value) {#setStandardVehClassification-java.lang.String-}
```
public final void setStandardVehClassification(String value)
```


DCM，持卡人的标准车辆分类代码。此数据元素是未来标准化车辆分类工作的占位符，DL，F4AN

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setUnder18Until(LocalDate value) {#setUnder18Until-java.time.LocalDate-}
```
public final void setUnder18Until(LocalDate value)
```


DDH，持卡人年满18岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.time.LocalDate |  |

### setUnder19Until(LocalDate value) {#setUnder19Until-java.time.LocalDate-}
```
public final void setUnder19Until(LocalDate value)
```


DDI，持卡人年满19岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.time.LocalDate |  |

### setUnder21Until(LocalDate value) {#setUnder21Until-java.time.LocalDate-}
```
public final void setUnder21Until(LocalDate value)
```


DDJ，持卡人年满21岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.time.LocalDate |  |

### setVehClassDescription(String value) {#setVehClassDescription-java.lang.String-}
```
public final void setVehClassDescription(String value)
```


DCP，解释持卡人被授权驾驶的车辆分类的司法辖区特定代码的文本，DL，V50ANS

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setVeteranIndicator(String value) {#setVeteranIndicator-java.lang.String-}
```
public final void setVeteranIndicator(String value)
```


DDL，指示持卡人是退伍军人的字段 = \u201c1\u201d，DL/ID，F1N

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### setWeightKilograms(int value) {#setWeightKilograms-int-}
```
public final void setWeightKilograms(int value)
```


DAX，持卡人的体重（千克），示例：84 kg = \u201c084\u201d，DL/ID，F3N

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setWeightPounds(int value) {#setWeightPounds-int-}
```
public final void setWeightPounds(int value)
```


DAW，持卡人的体重（磅），示例：185 lb = \u201c185\u201d，DL/ID，F3N

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setWeightRange(String value) {#setWeightRange-java.lang.String-}
```
public final void setWeightRange(String value)
```


DCE，指示持卡人大致体重范围：0 = up to 31 kg(up to 70 lbs), 1 = 32 – 45 kg(71 – 100 lbs), 2 = 46 - 59 kg(101 – 130 lbs), 3 = 60 - 70 kg(131 – 160 lbs), 4 = 71 - 86 kg(161 – 190 lbs), 5 = 87 - 100 kg(191 – 220 lbs), 6 = 101 - 113 kg(221 – 250 lbs), 7 = 114 - 127 kg(251 – 280 lbs), 8 = 128 – 145 kg(281 – 320 lbs), 9 = 146+ kg(321+ lbs)，DL/ID，F1N

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

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
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

