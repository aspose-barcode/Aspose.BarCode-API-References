---
title: Metered
second_title: Aspose.BarCode for .NET API 参考
description: 提供设置计量键的方法
type: docs
weight: 1020
url: /zh/net/aspose.barcode/metered/
---
## Metered class

提供设置计量键的方法。

```csharp
public class Metered
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Metered](metered)() | 默认构造函数。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [SetMeteredKey](../../aspose.barcode/metered/setmeteredkey)(string, string) | 设置计量的公钥和私钥 |
| static [GetConsumptionCredit](../../aspose.barcode/metered/getconsumptioncredit)() | 获取消费额度 |
| static [GetConsumptionQuantity](../../aspose.barcode/metered/getconsumptionquantity)() | 获取消费文件大小 |

### 例子

在此示例中，将尝试设置计量的公钥和私钥

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### 也可以看看

* 命名空间 [Aspose.BarCode](../../aspose.barcode)
* 部件 [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->