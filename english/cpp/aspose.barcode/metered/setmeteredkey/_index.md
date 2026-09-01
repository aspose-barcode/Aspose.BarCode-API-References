---
title:  method
linktitle: SetMeteredKey
second_title: Aspose.BarCode for C++ API Reference
description: ' method. Sets metered public and private key. If you purchase metered license, when start application, this API should be called, normally, this is enough. However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again in C++.'
type: docs
weight: 200
url: /cpp/aspose.barcode/metered/setmeteredkey/
---
## Metered::SetMeteredKey method


Sets metered public and private key. If you purchase metered license, when start application, this API should be called, normally, this is enough. However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again.

```cpp
void Aspose::BarCode::Metered::SetMeteredKey(System::String publicKey, System::String privateKey)
```


| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | System::String | public key |
| privateKey | System::String | private key |

## See Also

* Class [Metered](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
