---
title: "Aspose::BarCode::LicenseCore klass"
linktitle: "LicenseCore"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::LicenseCore klass. Klass som läser och implementerar licensen i C++."
type: docs
weight: 400
url: /sv/cpp/aspose.barcode/licensecore/
---
## LicenseCore class


Klass som läser och implementerar licensen.

```cpp
class LicenseCore : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [EncodeSignature](./encodesignature/)(System::SharedPtr\<System::Object\>) | Kodar data till signatur |
| static [GetFileNameInFolderOfAssembly](./getfilenameinfolderofassembly/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>) | Försöker hitta filnamn i assemblies-mappen. |
| [LicenseCore](./licensecore/)() | Initierar en ny instans av klassen [LicenseCore](./). |
| static [RemoveMeteredLicense](./removemeteredlicense/)() |  |
| [ResetLicense](./resetlicense/)() | Metoden återställer licenstillståndet för internt bruk och tester. |
| [SetLicense](./setlicense/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Söker licens, laddar och försöker implementera. Resultatet av implementeringen sätts till errorCode. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Försöker implementera licensen. Resultatet av implementeringen sätts till errorCode. |
| static [SetMeteredLicense](./setmeteredlicense/)(bool, System::String) |  |
## Se även

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
