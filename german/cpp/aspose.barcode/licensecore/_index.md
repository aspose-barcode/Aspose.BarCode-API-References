---
title: "Aspose::BarCode::LicenseCore Klasse"
linktitle: "LicenseCore"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::LicenseCore Klasse. Klasse, die die Lizenz in C++ liest und implementiert."
type: docs
weight: 400
url: /de/cpp/aspose.barcode/licensecore/
---
## LicenseCore class


Klasse, die die Lizenz liest und implementiert.

```cpp
class LicenseCore : public System::Object
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [EncodeSignature](./encodesignature/)(System::SharedPtr\<System::Object\>) | Kodiert Daten in eine Signatur. |
| static [GetFileNameInFolderOfAssembly](./getfilenameinfolderofassembly/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>) | Versucht, den Dateinamen im Assembly-Ordner zu finden. |
| [LicenseCore](./licensecore/)() | Initialisiert eine neue Instanz der Klasse [LicenseCore](./). |
| static [RemoveMeteredLicense](./removemeteredlicense/)() |  |
| [ResetLicense](./resetlicense/)() | Methode setzt den Lizenzstatus für die interne Verwendung und Tests zurück. |
| [SetLicense](./setlicense/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Sucht die Lizenz, lädt sie und versucht, sie zu implementieren. Das Ergebnis der Implementierung wird in errorCode gesetzt. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Versucht, die Lizenz zu implementieren. Das Ergebnis der Implementierung wird in errorCode gesetzt. |
| static [SetMeteredLicense](./setmeteredlicense/)(bool, System::String) |  |
## Siehe auch

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
