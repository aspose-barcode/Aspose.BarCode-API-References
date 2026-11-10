---
title: "类 Metered"
second_title: "Aspose.BarCode 适用于 .NET API 参考"
description: "Aspose.BarCode.Metered 类。提供设置计量密钥的方法。"
type: docs
weight: 1770
url: /zh/net/aspose.barcode/metered/
---
## Metered class

提供设置计量密钥的方法。

```csharp
public class Metered
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Metered](metered/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetProductName](../../aspose.barcode/metered/getproductname/)() | 获取已授权产品的名称 |
| [SetMeteredKey](../../aspose.barcode/metered/setmeteredkey/)(string, string) | 设置计量公共和私有密钥。如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这就足够了。然而，如果始终无法上传消耗数据并超过 24 小时，许可证将被设置为评估状态，为避免此情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。 |
| static [GetConsumptionCredit](../../aspose.barcode/metered/getconsumptioncredit/)() | 获取消耗信用 |
| static [GetConsumptionQuantity](../../aspose.barcode/metered/getconsumptionquantity/)() | 获取消耗文件大小 |
| static [IsMeteredLicensed](../../aspose.barcode/metered/ismeteredlicensed/)() | 检查计量是否已授权 |

## 示例

在此示例中，将尝试设置计量的公钥和私钥

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### 另见

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


