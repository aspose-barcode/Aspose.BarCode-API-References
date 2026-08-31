---
title: Aspose::BarCode::LicenseCore class
linktitle: LicenseCore
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::LicenseCore class. Class with reads and implements the license in C++.'
type: docs
weight: 400
url: /cpp/aspose.barcode/licensecore/
---
## LicenseCore class


Class with reads and implements the license

```cpp
class LicenseCore : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [EncodeSignature](./encodesignature/)(System::SharedPtr\<System::Object\>) | Encodes data to signature |
| static [GetFileNameInFolderOfAssembly](./getfilenameinfolderofassembly/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>) | Tries to find filename in assebly folder |
| [LicenseCore](./licensecore/)() | Initializes a new instance of the [LicenseCore](./) class. |
| static [RemoveMeteredLicense](./removemeteredlicense/)() |  |
| [ResetLicense](./resetlicense/)() | Method resets license state for the internal use and tests |
| [SetLicense](./setlicense/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Searches license, loads and tries to implement. The result of the implementation is set to errorCode |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Tries to implement the license. The result of the implementation is set to errorCode |
| static [SetMeteredLicense](./setmeteredlicense/)(bool, System::String) |  |
## See Also

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
