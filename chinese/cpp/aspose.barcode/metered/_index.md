---
title: "Aspose::BarCode::Metered 类"
linktitle: "计量"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::Metered 类。提供在 C++ 中设置计量密钥的方法。"
type: docs
weight: 500
url: /zh/cpp/aspose.barcode/metered/
---
## Metered class


提供设置计量密钥的方法。

```cpp
class Metered : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | 获取消耗积分 |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | 获取消耗文件大小 |
| [GetProductName](./getproductname/)() | 获取已授权产品的名称 |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | 检查计量是否已授权 |
| [Metered](./metered/)() | 初始化此类的新实例。 |
| [SetMeteredKey](./setmeteredkey/)(System::String, System::String) | 设置计量公钥和私钥。如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这已经足够。然而，如果始终无法上传消耗数据且超过 24 小时，许可证将被设置为评估状态，为避免这种情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。 |
## 备注


在此示例中，将尝试设置计量公钥和私钥

<ms>
```cpp
[C#]
@verbatim
Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
@endverbatim
```
</ms>

<java> 组件 jar 文件:
```cpp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```
</java>
## 另见

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
