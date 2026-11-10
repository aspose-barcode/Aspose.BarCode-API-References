---
title: "类 USADriveIdCodetext.MandatoryFields"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetextMandatoryFields 类。卡片的必填元素字段"
type: docs
weight: 820
url: /zh/net/aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
## USADriveIdCodetext.MandatoryFields class

卡片的必填元素（字段）

```csharp
public class MandatoryFields
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/.ctor)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AddressCity](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresscity) { get; set; } | DAI，持卡人地址的城市部分，DL/ID，V20ANS |
| [AddressPostalCode](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addresspostalcode) { get; set; } | DAK，美国和加拿大持卡人地址的邮政编码部分。如果美国邮政编码的后缀未知，将使用零填充至 9 位数字的后缀部分，DL/ID，F11ANS |
| [AddressState](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstate) { get; set; } | DAJ，持卡人地址的州部分，DL/ID，F2A |
| [AddressStreet1](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/addressstreet1) { get; set; } | DAG，持卡人地址的街道部分，DL/ID，V35ANS |
| [CountryIdentification](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/countryidentification) { get; set; } | DCG，DL/ID 所在的国家。美国 = USA，加拿大 = CAN，DL/ID，F3A |
| [CustomerIDNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/customeridnumber) { get; set; } | DAQ，发行机构分配或计算的号码，DL/ID，V25ANS |
| [DateOfBirth](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/dateofbirth) { get; set; } | DBB，文件签发日期，美国为 MMDDCCYY，加拿大为 CCYYMMDD，DL/ID，F8N |
| [DocumentDiscriminator](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/documentdiscriminator) { get; set; } | DCF，号码必须唯一标识发给该客户的特定文件，以区别过去可能已签发的其他文件。此号码可用于文件区分、审计信息编号和/或库存控制，DL/ID，V25ANS |
| [EndorsementCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/endorsementcodes) { get; set; } | DCD，司法辖区特定的背书代码，DL，V5ANS |
| [ExpirationDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/expirationdate) { get; set; } | DBA，文件到期日期，美国为 MMDDCCYY，加拿大为 CCYYMMDD，DL/ID，F8N |
| [EyeColor](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/eyecolor) { get; set; } | DAY，持卡人眼睛颜色。（ANSI D-20 代码）。DL/ID，F3A |
| [FamilyName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familyname) { get; set; } | DCS，持卡人姓氏，DL/ID，V40ANS |
| [FamilyNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/familynametruncation) { get; set; } | DDE，指示字段是否被截断的代码（T=已截断，N=未截断，U=未知），DL/ID，F1A |
| [FirstName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstname) { get; set; } | DAC，持卡人名字，DL/ID，V40ANS |
| [FirstNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/firstnametruncation) { get; set; } | DDF，指示字段是否被截断的代码（T=已截断，N=未截断，U=未知），DL/ID，F1A |
| [Height](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/height) { get; set; } | DAU，持卡人身高。英寸（in）：数字后跟 " in" 示例 6'1'' = "073 in"；厘米（cm）：数字后跟 " cm" 示例 181 厘米 = "181 cm"，DL/ID，F6ANS |
| [IssueDate](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/issuedate) { get; set; } | DBD，文件签发日期，美国为 MMDDCCYY，加拿大为 CCYYMMDD，DL/ID，F8N |
| [MiddleName](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlename) { get; set; } | DAD，持卡人中间名。若有多个中间名，应以逗号 "," 分隔，DL/ID，V40ANS |
| [MiddleNameTruncation](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/middlenametruncation) { get; set; } | DDG，指示字段是否被截断的代码（T=已截断，N=未截断，U=未知），DL/ID，F1A |
| [RestrictionCodes](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/restrictioncodes) { get; set; } | DCB，司法辖区特定限制代码，DL，V12ANS |
| [Sex](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/sex) { get; set; } | DBC，持卡人性别。1 = 男性，2 = 女性，9 = 未指定，DL/ID，F1N |
| [VehicleClass](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/vehicleclass) { get; set; } | DCA，司法辖区特定车辆类别/组代码，DL，V6ANS |

### 另见

* class [USADriveIdCodetext](../usadriveidcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


