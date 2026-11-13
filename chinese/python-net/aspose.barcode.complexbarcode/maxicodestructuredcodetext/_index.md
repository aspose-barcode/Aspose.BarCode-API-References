---
title: "MaxiCodeStructuredCodetext"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.complexbarcode/maxicodestructuredcodetext/
---

## MaxiCodeStructuredCodetext class

用于编码和解码嵌入在 MaxiCode 代码中模式 2 和 3 的文本的基类。

该 MaxiCodeStructuredCodetext 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| encode_mode | 获取或设置 MaxiCode 编码模式。<br/>            默认值：Auto。 |
| eci_encoding | 获取或设置 ECI 编码。当 MaxiCodeEncodeMode 为 Auto 时使用。<br/>            默认值：ISO-8859-1 |
| postal_code | 标识邮政编码。模式 2 必须为 9 位数字或 <br/>            模式 3 为 6 个字母数字符号。 |
| country_code | 标识 3 位国家代码。 |
| service_category | 标识 3 位服务类别。 |
| second_message | 标识条码的第二条信息。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| get_mode() | 获取 MaxiCode 模式。 |
| get_constructed_codetext() | 构建代码文本 |
| init_from_string(constructed_codetext) | 从构建的代码文本初始化实例。 |
| get_barcode_type() | 获取条形码类型。 |

### 另见

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

