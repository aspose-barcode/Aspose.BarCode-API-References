---
title: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.complexbarcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

用于编码和解码嵌入在 Royal Mail 2D Mailmark 代码中的文本的类。

Mailmark2DCodetext 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| Mailmark2DCodetext() | 初始化 Mailmark2DCodetext 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| upu_country_id | 标识 UPU 国家 ID。最大长度：4 个字符。 |
| information_type_id | 标识每种产品类型的皇家邮政 Mailmark 条码负载。 |
| version_id | 标识与每个信息类型 ID 相关的条码版本。 |
| klass | 标识项目的类别。 |
| supply_chain_id | 标识参与邮件发送的唯一客户组。<br/>            最大值：9999999。 |
| item_id | 标识供应链 ID 中的唯一项目。<br/>            每个 Mailmark 条码必须携带一个 ID<br/>            以便在至少 90 天内唯一识别。<br/>            最大值：99999999。 |
| destination_post_code_and_dps | 包含带有 DPS 的收货地址邮编<br/>            若为内陆地区，邮编/DP 包含以下字符数。<br/>            区域（1 或 2 个字符） 区（1 或 2 个字符）<br/>            扇区（1 个字符） 单元（2 个字符） DPS（2 个字符）。<br/>            邮编和 DPS 必须符合有效的 PAF® 格式。 |
| rts_flag | 指示请求的退回寄件服务级别的标志。 |
| return_to_sender_post_code | 包含退回寄件邮编，但不含 DPS。<br/>            不含 DPS 的邮编必须符合 PAF® 格式。 |
| customer_content | 供客户使用的可选空间。 |
| customer_content_encode_mode | Datamatrix 条码的编码模式。<br/>            默认值：EncodeMode.C40。 |
| data_matrix_type | 2D Mailmark 类型定义 Data Matrix 条码的尺寸。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| get_constructed_codetext() | 从 Mailmark 数据构建 codetext。 |
| init_from_string(constructed_codetext) | 从构建的 codetext 初始化 Mailmark 数据。 |
| get_barcode_type() | 获取条形码类型。 |

### 另见

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

