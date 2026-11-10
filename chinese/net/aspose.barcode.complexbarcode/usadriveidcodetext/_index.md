---
title: "类 USADriveIdCodetext"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.ComplexBarcode.USADriveIdCodetext 类。用于对嵌入美国驾驶执照 PDF417 代码中的文本进行编码和解码的类。"
type: docs
weight: 810
url: /zh/net/aspose.barcode.complexbarcode/usadriveidcodetext/
---
## USADriveIdCodetext class

用于对嵌入在美国驾照 PDF417 代码中的文本进行编码和解码的类.

```csharp
public sealed class USADriveIdCodetext : IComplexCodetext
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [USADriveIdCodetext](usadriveidcodetext/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AAMVAVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/aamvaversionnumber/) { get; set; } | AAMVA 版本号 00-99 |
| [IssuerIdentificationNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/issueridentificationnumber/) { get; set; } | 此号码唯一标识发行司法辖区，可通过联系 ISO 发行机构（AAMVA）获取。应编码完整的6位 IIN。 |
| [JurisdictionSpecificSubfile](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionspecificsubfile/) { get; set; } | 特定司法辖区字段 |
| [JurisdictionVersionNumber](../../aspose.barcode.complexbarcode/usadriveidcodetext/jurisdictionversionnumber/) { get; set; } | 司法辖区版本号 00-99 |
| [MandatoryElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/mandatoryelements/) { get; set; } | 卡片的必填元素（字段） |
| [NumberOfEntries](../../aspose.barcode.complexbarcode/usadriveidcodetext/numberofentries/) { get; set; } | 子文件数量 00-99 |
| [OptionalElements](../../aspose.barcode.complexbarcode/usadriveidcodetext/optionalelements/) { get; set; } | 卡片的可选元素（字段） |
| [SubfileDesignator](../../aspose.barcode.complexbarcode/usadriveidcodetext/subfiledesignator/) { get; set; } | 包含以下子文件、类型、偏移量和长度的信息。重要提示：仅设置类型，偏移量和长度将自动设置。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetBarcodeType](../../aspose.barcode.complexbarcode/usadriveidcodetext/getbarcodetype/)() | 返回美国驾驶执照（Pdf417）的条码类型 |
| [GetConstructedCodetext](../../aspose.barcode.complexbarcode/usadriveidcodetext/getconstructedcodetext/)() | 从美国驾驶执照数据构建编码文本 |
| [InitFromString](../../aspose.barcode.complexbarcode/usadriveidcodetext/initfromstring/)(string) | 从编码文本初始化美国驾驶执照对象 |
| [SaveToXml](../../aspose.barcode.complexbarcode/usadriveidcodetext/savetoxml/)(Stream) | 保存为 XML |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| class [MandatoryFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields) | 卡片的必填元素（字段） |
| class [OptionalFields](../../aspose.barcode.complexbarcode/usadriveidcodetext.optionalfields) | 卡片的可选元素（字段） |
| class [SubfileProperties](../../aspose.barcode.complexbarcode/usadriveidcodetext.subfileproperties) | USA DL 子文件属性的偏移量和长度会自动设置。 |

### 另见

* interface [IComplexCodetext](../icomplexcodetext/)
* namespace [Aspose.BarCode.ComplexBarcode](../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../)


