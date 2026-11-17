---
title: "method"
linktitle: "SetMeteredKey"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。设置计量的公钥和私钥。如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这已经足够。然而，如果始终无法上传消费数据且超过 24 小时，许可证将被设置为评估状态。为避免这种情况，您应该定期检查许可证状态，如果是评估状态，请在 C++ 中再次调用此 API。"
type: docs
weight: 200
url: /zh/cpp/aspose.barcode/metered/setmeteredkey/
---
## Metered::SetMeteredKey method


设置计量公钥和私钥。如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这已经足够。然而，如果始终无法上传消耗数据且超过 24 小时，许可证将被设置为评估状态，为避免这种情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。

```cpp
void Aspose::BarCode::Metered::SetMeteredKey(System::String publicKey, System::String privateKey)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| publicKey | System::String | 公钥 |
| privateKey | System::String | 私钥 |

## 另见

* Class [Metered](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
