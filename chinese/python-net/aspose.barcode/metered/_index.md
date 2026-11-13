---
title: "Metered"
second_title: "Aspose.BarCode for Python via .NET API Reference"
description: 
type: docs
url: /zh/python-net/aspose.barcode/metered/
---

## Metered class

提供设置计量密钥的方法。

Metered 类型公开以下成员：
## 构造函数
| 名称 | 描述 |
| :- | :- |
| Metered() | 初始化 Metered 类的新实例 |
## 方法
| 名称 | 描述 |
| :- | :- |
| set_metered_key(public_key, private_key) | 设置计量的公钥和私钥。<br/>            如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这已足够。<br/>            但是，如果始终无法上传消费数据且超过 24 小时，许可证将被设置为评估状态，<br/>            为避免这种情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。 |
| get_consumption_quantity() | 获取消费文件大小 |
| get_consumption_credit() | 获取消费积分 |
| get_product_name() | 获取已授权产品的名称 |
| is_metered_licensed() | 检查计量是否已授权 |

### 另见

* namespace [aspose.barcode](/barcode/python-net/aspose.barcode/)
* assembly [Aspose.BarCode](/barcode/python-net/)

