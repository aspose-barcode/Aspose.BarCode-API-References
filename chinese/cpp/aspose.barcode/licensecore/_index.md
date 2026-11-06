---
title: "Aspose::BarCode::LicenseCore 类"
linktitle: "LicenseCore"
second_title: "Aspose.BarCode for C++ API 参考"
description: "Aspose::BarCode::LicenseCore 类。类在 C++ 中读取并实现许可证。"
type: docs
weight: 400
url: /zh/cpp/aspose.barcode/licensecore/
---
## LicenseCore class


读取并实现许可证的类

```cpp
class LicenseCore : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| [EncodeSignature](./encodesignature/)(System::SharedPtr\<System::Object\>) | 将数据编码为签名 |
| static [GetFileNameInFolderOfAssembly](./getfilenameinfolderofassembly/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>) | 尝试在 assebly 文件夹中查找文件名 |
| [LicenseCore](./licensecore/)() | 初始化 [LicenseCore](./) 类的新实例。 |
| static [RemoveMeteredLicense](./removemeteredlicense/)() |  |
| [ResetLicense](./resetlicense/)() | 方法重置许可证状态以供内部使用和测试 |
| [SetLicense](./setlicense/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | 搜索许可证，加载并尝试实现。实现的结果被设置为 errorCode |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | 尝试实现许可证。实现的结果被设置为 errorCode |
| static [SetMeteredLicense](./setmeteredlicense/)(bool, System::String) |  |
## 另见

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
