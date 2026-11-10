---
title: "类 USADriveIdCodetext.OptionalFields"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextOptionalFields 类。卡片的可选元素字段"
type: docs
weight: 830
url: /zh/net/aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/
---
## USADriveIdCodetext.OptionalFields class

卡片的可选元素（字段）

```csharp
public class OptionalFields
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/.ctor)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AddressStreet2](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/addressstreet2) { get; set; } | DAH，持卡人地址街道部分的第二行，DL/ID，V35ANS |
| [AliasAKAFamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakafamilyname) { get; set; } | DBN，持卡人已知的其他姓氏，DL/ID，V10ANS |
| [AliasAKAGivenName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakagivenname) { get; set; } | DBG，持卡人已知的其他名字，DL/ID，V15ANS |
| [AliasAKASuffixName](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/aliasakasuffixname) { get; set; } | DBS，持卡人已知的其他后缀，DL/ID，V5ANS |
| [AuditInformation](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/auditinformation) { get; set; } | DCJ，一串字母和/或数字，用于标识驾驶执照/身份证何时、何地、由谁制作。如果卡片或MRT未使用审计信息，则必须在驾驶员记录中包含此信息，DL/ID，V25ANS |
| [CardRevisionDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/cardrevisiondate) { get; set; } | DDB，DHS 必需字段，指示 DL/ID 可见格式最近一次版本更改或修改的日期。（美国为 MMDDCCYY，加拿大为 CCYYMMDD），DL/ID，F8N |
| [ComplianceType](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/compliancetype) { get; set; } | DDA，DHS 必需字段，指示合规性：“F” = 合规；“N” = 不合规，DL/ID，F1A |
| [EndorsementCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/endorsementcodedescription) { get; set; } | DCQ，解释特定司法辖区代码的文本，这些代码指示授予持卡人超出车辆类别的额外驾驶特权，DL，V50ANS |
| [HairColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/haircolor) { get; set; } | DAZ，秃头，黑色，金发，棕色，灰色，红色/栗色，沙色，白色，未知。如果签发司法辖区希望缩写颜色，必须使用 AAMVA D20 中提供的三字符代码，DL/ID，V12A |
| [HAZMATEndorsementExpDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/hazmatendorsementexpdate) { get; set; } | DDC，文件授予的危险品背书失效的日期。（美国为 MMDDCCYY，加拿大为 CCYYMMDD），DL，F8N |
| [InventoryControlNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/inventorycontrolnumber) { get; set; } | DCK，一串附加在用于生产驾驶执照和身份证的原材料（卡纸、层压等）上的字母和/或数字。（DHS 推荐字段），DL/ID，V25ANS |
| [LimitedDurationDocIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/limiteddurationdocindicator) { get; set; } | DDD，DHS 必需字段，指示持卡人拥有临时合法状态 = “1”，DL/ID，F1N |
| [NameSuffix](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/namesuffix) { get; set; } | DCU，姓名后缀（如果司法辖区参与需要姓名后缀的系统（PDPS、CDLIS 等），则必须在 DL/ID 和 MRT 中收集并显示该后缀）。JR（Junior），SR（Senior），1ST 或 I（First），最高至 9TH 或 IX（Ninth），DL/ID，V5ANS |
| [OrganDonorIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/organdonorindicator) { get; set; } | DDK，指示持卡人是器官捐献者的字段 = “1”，DL/ID，F1N |
| [PlaceOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/placeofbirth) { get; set; } | DCI，国家和市镇和/或州/省，DL/ID，V33A |
| [RaceEthnicity](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/raceethnicity) { get; set; } | DCL，持卡人的种族或族裔代码，定义见 AAMVA D20，DL/ID，V3A |
| [RestrictionCodeDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/restrictioncodedescription) { get; set; } | DCR，描述特定司法辖区限制代码的文本，这些代码限制驾驶特权，DL，V50ANS |
| [StandardEndorsementCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardendorsementcode) { get; set; } | DCN，持卡人的标准背书代码。请参阅 D20 中的代码。此数据元素是未来标准化背书代码工作的占位符，DL，F5AN |
| [StandardRestrictionCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardrestrictioncode) { get; set; } | DCO，持卡人的标准限制代码。请参阅 D20 中的代码。此数据元素是为将来标准化限制代码的工作预留的占位符，DL，F12AN |
| [StandardVehClassification](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/standardvehclassification) { get; set; } | DCM，持卡人的标准车辆分类代码。此数据元素是为将来标准化车辆分类的工作预留的占位符，DL，F4AN |
| [Under18Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under18until) { get; set; } | DDH，持卡人年满 18 岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N |
| [Under19Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under19until) { get; set; } | DDI，持卡人年满 19 岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N |
| [Under21Until](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/under21until) { get; set; } | DDJ，持卡人年满 21 岁的日期。（美国使用 MMDDCCYY，加拿大使用 CCYYMMDD），DL/ID，F8N |
| [VehClassDescription](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/vehclassdescription) { get; set; } | DCP，解释持卡人被授权驾驶的车辆分类的特定司法辖区代码的文本，DL，V50ANS |
| [VeteranIndicator](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/veteranindicator) { get; set; } | DDL，指示持卡人是退伍军人的字段 = “1”，DL/ID，F1N |
| [WeightKilograms](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightkilograms) { get; set; } | DAX，持卡人的体重（千克），例如 84 kg = “084”，DL/ID，F3N |
| [WeightPounds](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightpounds) { get; set; } | DAW，持卡人的体重（磅），例如 185 lb = “185”，DL/ID，F3N |
| [WeightRange](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields/weightrange) { get; set; } | DCE，指示持卡人的近似体重范围：0 = 最高 31 kg（最高 70 磅），1 = 32 – 45 kg（71 – 100 磅），2 = 46 - 59 kg（101 – 130 磅），3 = 60 - 70 kg（131 – 160 磅），4 = 71 - 86 kg（161 – 190 磅），5 = 87 - 100 kg（191 – 220 磅），6 = 101 - 113 kg（221 – 250 磅），7 = 114 - 127 kg（251 – 280 磅），8 = 128 – 145 kg（281 – 320 磅），9 = 146+ kg（321+ 磅），DL/ID，F1N |

### 另见

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


