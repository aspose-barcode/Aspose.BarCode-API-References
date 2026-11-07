---
title: "Aspose::BarCode::LicenseCore klasse"
linktitle: "LicenseCore"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::LicenseCore klasse. Klasse die de licentie leest en implementeert in C++."
type: docs
weight: 400
url: /nl/cpp/aspose.barcode/licensecore/
---
## LicenseCore class


Klasse die de licentie leest en implementeert

```cpp
class LicenseCore : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [EncodeSignature](./encodesignature/)(System::SharedPtr\<System::Object\>) | Codeert gegevens naar handtekening. |
| static [GetFileNameInFolderOfAssembly](./getfilenameinfolderofassembly/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>) | Probeert bestandsnaam te vinden in assembly map. |
| [LicenseCore](./licensecore/)() | Initialiseert een nieuw exemplaar van de [LicenseCore](./) klasse. |
| static [RemoveMeteredLicense](./removemeteredlicense/)() |  |
| [ResetLicense](./resetlicense/)() | Methode reset de licentiestatus voor intern gebruik en tests. |
| [SetLicense](./setlicense/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Zoekt licentie, laadt en probeert te implementeren. Het resultaat van de implementatie wordt toegewezen aan errorCode. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Probeert de licentie te implementeren. Het resultaat van de implementatie wordt toegewezen aan errorCode. |
| static [SetMeteredLicense](./setmeteredlicense/)(bool, System::String) |  |
## Zie ook

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
