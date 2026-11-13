---
title: "USADriveIdCodetext"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.complexbarcode/usadriveidcodetext/
---

## USADriveIdCodetext class

用于编码和解码嵌入在 USA 驾驶执照 PDF417 代码中的文本的类。

USADriveIdCodetext 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| USADriveIdCodetext() | 初始化 USADriveIdCodetext 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| issuer_identification_number | 此号码唯一标识 <br/>            发证司法辖区，可通过联系 ISO<br/>            发证机构（AAMVA）获取。应对完整的6位 IIN 进行编码。 |
| aamva_version_number | AAMVA 版本号 00-99 |
| jurisdiction_version_number | 司法辖区版本号 00-99 |
| number_of_entries | 子文件数量 00-99 |
| subfile_designator | 包含以下子文件、类型、偏移量和长度的信息。 <br/>            重要提示：仅设置类型，偏移量和长度将自动设置。 |
| mandatory_elements | 卡片的必填元素（字段） |
| optional_elements | 卡片的可选元素（字段） |
| jurisdiction_specific_subfile | 司法辖区特定字段 |
## 方法
| 名称 | 描述 |
| :- | :- |
| get_constructed_codetext() | 从 USA DL 数据构建代码文本 |
| init_from_string(constructed_codetext) | 从代码文本初始化 USA DL 对象 |
| get_barcode_type() | 返回 USA DL 的条形码类型（Pdf417） |
| save_to_xml(stream) | 保存为 XML |

### 另见

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

