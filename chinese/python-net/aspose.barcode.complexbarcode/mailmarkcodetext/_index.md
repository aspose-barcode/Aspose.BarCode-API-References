---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.complexbarcode/mailmarkcodetext/
---

## MailmarkCodetext class

用于编码和解码嵌入在 4-state Royal Mailmark 代码中的文本的类。

MailmarkCodetext 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| MailmarkCodetext() | 初始化 MailmarkCodetext 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| format | "0" – 空或测试<br/>            "1" – 信件<br/>            "2" – 大信件 |
| version_id | 当前 "1" – 用于 Mailmark 条形码（0 和 2 到 9 以及 A 到 Z 为将来使用保留） |
| klass | "0" - 空或测试<br/>            "1" - 1C (Retail)<br/>            "2" - 2C (Retail)<br/>            "3" - 3C (Retail)<br/>            "4" - Premium (RetailPublishing Mail) (for potential future use)<br/>            "5" - Deferred (Retail)<br/>            "6" - Air (Retail) (for potential future use)<br/>            "7" - Surface (Retail) (for potential future use)<br/>            "8" - Premium (Network Access)<br/>            "9" - Standard (Network Access) |
| supply_chain_id | 最大值为 Barcode C 的 99 和 Barcode L 的 999999。 |
| item_id | 最大值为 99999999。 |
| destination_post_code_and_dps | PC 和 DP 必须符合 PAF 格式。<br/>            九字符字符串表示国际 "XY11     "（注意 5 个尾随空格）或一个模式<br/>            用于表示国内分拣代码的字符。<br/>            国内分拣代码由外部邮编、内部邮编和投递点后缀组成。 |
## 方法
| 名称 | 描述 |
| :- | :- |
| get_constructed_codetext() | 从 Mailmark 数据构建 codetext。 |
| init_from_string(constructed_codetext) | 从构建的 codetext 初始化 Mailmark 数据。 |
| get_barcode_type() | 获取条形码类型。 |

### 另见

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

