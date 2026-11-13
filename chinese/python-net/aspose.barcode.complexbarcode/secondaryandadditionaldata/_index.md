---
title: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---

## SecondaryAndAdditionalData class

用于存储 HIBC LIC 次要和附加数据的类。

该 SecondaryAndAdditionalData 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| SecondaryAndAdditionalData() | 初始化 SecondaryAndAdditionalData 类的新实例 |
## 属性
| 名称 | 描述 |
| :- | :- |
| expiry_date_format | 识别到期日期格式。 |
| expiry_date | 识别到期日期。若 ExpiryDateFormat 未设置为 None，则使用此值。 |
| lot_number | 标识批号或批次号。批号/批次号必须是最长为 18 个字符的字母数字字符串。 |
| serial_number | 标识序列号。序列号必须是最长为 18 个字符的字母数字字符串。 |
| date_of_manufacture | 标识生产日期。<br/>            为了不使用此字段，生产日期可以设置为 DateTime.MinValue。<br/>            默认值：DateTime.MinValue |
| quantity | 标识数量，必须是 0 到 500 的整数值。 <br/>            为了不使用此字段，数量可以设置为 -1。<br/>            默认值：-1 |
## 方法
| 名称 | 描述 |
| :- | :- |
| parse_from_string(secondary_data_codetext) | 根据 HIBC LIC 规范，从字符串格式实例化次要和附加补充数据。 |

### 另见

* namespace [aspose.barcode.complexbarcode](/barcode/python-net/aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

