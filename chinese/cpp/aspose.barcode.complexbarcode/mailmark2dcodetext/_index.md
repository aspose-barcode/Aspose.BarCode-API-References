---
title: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext 类"
linktitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext 类。用于在 C++ 中对嵌入皇家邮政 2D Mailmark 代码的文本进行编码和解码的类。"
type: docs
weight: 1400
url: /zh/cpp/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class


用于对嵌入在 Royal Mail 2D Mailmark 代码中的文本进行编码和解码的类。

```cpp
class Mailmark2DCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Class](./get_class/)() const | 标识项目的类别。 |
| [get_CustomerContent](./get_customercontent/)() const | 供客户使用的可选空间。 |
| [get_CustomerContentEncodeMode](./get_customercontentencodemode/)() const | Datamatrix 条形码的编码模式。默认值：EncodeMode.C40。 |
| [get_DataMatrixType](./get_datamatrixtype/)() const | 2D Mailmark 类型定义 Data Matrix 条形码的大小。 |
| [get_DestinationPostCodeAndDPS](./get_destinationpostcodeanddps/)() const | 包含带有 DPS 的收货 [Address](../address/) 的邮政编码。如果是内陆地区，邮政编码/DP 包含以下字符数：地区 (1 或 2 个字符) 区 (1 或 2 个字符) 扇区 (1 个字符) 单元 (2 个字符) DPS (2 个字符)。邮政编码和 DPS 必须符合有效的 PAF® 格式。 |
| [get_InformationTypeID](./get_informationtypeid/)() const | 标识每种产品类型的皇家邮政 Mailmark 条形码负载。 |
| [get_ItemID](./get_itemid/)() const | 标识供应链 ID 中的唯一项目。每个 Mailmark 条形码必须携带一个 ID，以便在至少 90 天内唯一识别。最大值：99999999。 |
| [get_ReturnToSenderPostCode](./get_returntosenderpostcode/)() const | 包含退回寄件人邮编，但不含 DPS。该邮编（不含 DPS）必须符合 PAF® 格式。 |
| [get_RTSFlag](./get_rtsflag/)() const | 指示请求的退回寄件人服务级别的标志。 |
| [get_SupplyChainID](./get_supplychainid/)() const | 标识参与邮件投递的唯一客户组。最大值：9999999。 |
| [get_UPUCountryID](./get_upucountryid/)() const | 标识 UPU 国家 ID。最大长度：4 个字符。 |
| [get_VersionID](./get_versionid/)() const | 标识与每个信息类型 ID 相关的条形码版本。 |
| [GetBarcodeType](./getbarcodetype/)() override | 获取条形码类型。 |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | 从 Mailmark 数据构建代码文本。 |
| [InitFromString](./initfromstring/)(System::String) override | 从构建的代码文本初始化 Mailmark 数据。 |
| [Mailmark2DCodetext](./mailmark2dcodetext/)() | 构造函数。创建 [Mailmark2DCodetext](./) 类的默认实例。 |
| [set_Class](./set_class/)(System::String) | 标识项目的类别。 |
| [set_CustomerContent](./set_customercontent/)(System::String) | 供客户使用的可选空间。 |
| [set_CustomerContentEncodeMode](./set_customercontentencodemode/)(Generation::DataMatrixEncodeMode) | Datamatrix 条形码的编码模式。默认值：EncodeMode.C40。 |
| [set_DataMatrixType](./set_datamatrixtype/)(Mailmark2DType) | 2D Mailmark 类型定义 Data Matrix 条形码的大小。 |
| [set_DestinationPostCodeAndDPS](./set_destinationpostcodeanddps/)(System::String) | 包含带有 DPS 的收货 [Address](../address/) 的邮政编码。如果是内陆地区，邮政编码/DP 包含以下字符数：地区 (1 或 2 个字符) 区 (1 或 2 个字符) 扇区 (1 个字符) 单元 (2 个字符) DPS (2 个字符)。邮政编码和 DPS 必须符合有效的 PAF® 格式。 |
| [set_InformationTypeID](./set_informationtypeid/)(System::String) | 标识每种产品类型的皇家邮政 Mailmark 条形码负载。 |
| [set_ItemID](./set_itemid/)(int32_t) | 标识供应链 ID 中的唯一项目。每个 Mailmark 条形码必须携带一个 ID，以便在至少 90 天内唯一识别。最大值：99999999。 |
| [set_ReturnToSenderPostCode](./set_returntosenderpostcode/)(System::String) | 包含退回寄件人邮编，但不含 DPS。该邮编（不含 DPS）必须符合 PAF® 格式。 |
| [set_RTSFlag](./set_rtsflag/)(System::String) | 指示请求的退回寄件人服务级别的标志。 |
| [set_SupplyChainID](./set_supplychainid/)(int32_t) | 标识参与邮件投递的唯一客户组。最大值：9999999。 |
| [set_UPUCountryID](./set_upucountryid/)(System::String) | 标识 UPU 国家 ID。最大长度：4 个字符。 |
| [set_VersionID](./set_versionid/)(System::String) | 标识与每个信息类型 ID 相关的条形码版本。 |
## 另见

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
