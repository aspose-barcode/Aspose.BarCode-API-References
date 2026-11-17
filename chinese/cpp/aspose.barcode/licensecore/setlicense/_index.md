---
title: "method"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ API 参考"
description: " 方法。搜索许可证，加载并尝试实现。实现的结果在 C++ 中设置到 errorCode。"
type: docs
weight: 300
url: /zh/cpp/aspose.barcode/licensecore/setlicense/
---
## LicenseCore::SetLicense(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


搜索许可证，加载并尝试实现。实现的结果被设置为 errorCode

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::String licenseName, System::SharedPtr<System::Reflection::Assembly> clientAssembly, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| licenseName | System::String | 可以是完整或简短的文件名，或嵌入资源的名称。 |
| clientAssembly | System::SharedPtr\<System::Reflection::Assembly\> | 调用程序集以查找搜索路径 |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | 错误代码，用于存储许可证状态以及可能的错误消息的附加信息 |

## 另见

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## LicenseCore::SetLicense(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


尝试实现许可证。实现的结果被设置为 errorCode

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parameter | Type | 描述 |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | 包含已存储许可证的流 |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | 错误代码，用于存储许可证状态以及可能的错误消息的附加信息 |

## 另见

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
