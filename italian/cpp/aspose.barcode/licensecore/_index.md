---
title: "Aspose::BarCode::LicenseCore classe"
linktitle: "LicenseCore"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: "Aspose::BarCode::LicenseCore classe. Classe che legge e implementa la licenza in C++."
type: docs
weight: 400
url: /it/cpp/aspose.barcode/licensecore/
---
## LicenseCore class


Classe che legge e implementa la licenza.

```cpp
class LicenseCore : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [EncodeSignature](./encodesignature/)(System::SharedPtr\<System::Object\>) | Codifica i dati in firma |
| static [GetFileNameInFolderOfAssembly](./getfilenameinfolderofassembly/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>) | Cerca di trovare il nome file nella cartella dell'assembly. |
| [LicenseCore](./licensecore/)() | Inizializza una nuova istanza della classe [LicenseCore](./). |
| static [RemoveMeteredLicense](./removemeteredlicense/)() |  |
| [ResetLicense](./resetlicense/)() | Il metodo resetta lo stato della licenza per uso interno e test. |
| [SetLicense](./setlicense/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Cerca la licenza, la carica e tenta di implementarla. Il risultato dell'implementazione è impostato su errorCode. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Tenta di implementare la licenza. Il risultato dell'implementazione è impostato su errorCode. |
| static [SetMeteredLicense](./setmeteredlicense/)(bool, System::String) |  |
## Vedi anche

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
