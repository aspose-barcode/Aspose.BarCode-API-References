---
title: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext 类"
linktitle: "USADriveIdCodetext"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::USADriveIdCodetext 类。用于在 C++ 中对嵌入美国驾驶执照 PDF417 代码的文本进行编码和解码的类。"
type: docs
weight: 2900
url: /zh/cpp/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class


用于对嵌入美国驾驶 [License](../../aspose.barcode/license/) PDF417 代码的文本进行编码和解码的类。

```cpp
class USADriveIdCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_AAMVAVersionNumber](./get_aamvaversionnumber/)() const | AAMVA 版本号 00-99 |
| [get_IssuerIdentificationNumber](./get_issueridentificationnumber/)() const | 此号码唯一标识发行司法管辖区，可通过联系 ISO 发行机构（AAMVA）获取。应编码完整的 6 位 IIN。 |
| [get_JurisdictionSpecificSubfile](./get_jurisdictionspecificsubfile/)() const | 司法管辖区特定字段 |
| [get_JurisdictionVersionNumber](./get_jurisdictionversionnumber/)() const | 司法管辖区版本号 00-99 |
| [get_MandatoryElements](./get_mandatoryelements/)() const | 卡片的必填元素（字段） |
| [get_NumberOfEntries](./get_numberofentries/)() const | 子文件数量 00-99 |
| [get_OptionalElements](./get_optionalelements/)() const | 卡片的可选元素（字段） |
| [get_SubfileDesignator](./get_subfiledesignator/)() const | 包含以下子文件、类型、偏移量和长度的信息。重要提示：仅设置类型，偏移量和长度将自动设置。 |
| [GetBarcodeType](./getbarcodetype/)() override | 返回美国驾驶执照（PDF417）的条码类型 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 从美国驾驶执照数据构建编码文本 |
| [InitFromString](./initfromstring/)(System::String) override | 从编码文本初始化美国驾驶执照对象 |
| [SaveToXml](./savetoxml/)(System::SharedPtr\<System::IO::Stream\>) | 保存为 XML |
| [set_AAMVAVersionNumber](./set_aamvaversionnumber/)(System::String) | AAMVA 版本号 00-99 |
| [set_IssuerIdentificationNumber](./set_issueridentificationnumber/)(System::String) | 此号码唯一标识发行司法管辖区，可通过联系 ISO 发行机构（AAMVA）获取。应编码完整的 6 位 IIN。 |
| [set_JurisdictionSpecificSubfile](./set_jurisdictionspecificsubfile/)(System::SharedPtr\<USADriveIdJurisdSubfile\>) | 司法管辖区特定字段 |
| [set_JurisdictionVersionNumber](./set_jurisdictionversionnumber/)(System::String) | 司法管辖区版本号 00-99 |
| [set_MandatoryElements](./set_mandatoryelements/)(System::SharedPtr\<USADriveIdCodetext::MandatoryFields\>) | 卡片的必填元素（字段） |
| [set_NumberOfEntries](./set_numberofentries/)(int32_t) | 子文件数量 00-99 |
| [set_OptionalElements](./set_optionalelements/)(System::SharedPtr\<USADriveIdCodetext::OptionalFields\>) | 卡片的可选元素（字段） |
| [set_SubfileDesignator](./set_subfiledesignator/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<USADriveIdCodetext::SubfileProperties\>>>) | 包含以下子文件、类型、偏移量和长度的信息。重要提示：仅设置类型，偏移量和长度将自动设置。 |
| [USADriveIdCodetext](./usadriveidcodetext/)() | 默认构造函数 |
## 另见

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
