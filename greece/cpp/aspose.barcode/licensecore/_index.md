---
title: "Aspose::BarCode::LicenseCore κλάση"
linktitle: "LicenseCore"
second_title: "Aspose.BarCode για C++ Αναφορά API"
description: "Aspose::BarCode::LicenseCore κλάση. Κλάση που διαβάζει και υλοποιεί την άδεια σε C++."
type: docs
weight: 400
url: /el/cpp/aspose.barcode/licensecore/
---
## LicenseCore class


Κλάση που διαβάζει και υλοποιεί την άδεια

```cpp
class LicenseCore : public System::Object
```

## Methods

| Method | Περιγραφή |
| --- | --- |
| [EncodeSignature](./encodesignature/)(System::SharedPtr\<System::Object\>) | Κωδικοποιεί δεδομένα σε υπογραφή |
| static [GetFileNameInFolderOfAssembly](./getfilenameinfolderofassembly/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>) | Προσπαθεί να βρει το όνομα αρχείου στον φάκελο assembly |
| [LicenseCore](./licensecore/)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [LicenseCore](./). |
| static [RemoveMeteredLicense](./removemeteredlicense/)() |  |
| [ResetLicense](./resetlicense/)() | Η μέθοδος επαναφέρει την κατάσταση της άδειας για εσωτερική χρήση και δοκιμές. |
| [SetLicense](./setlicense/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Αναζητά την άδεια, τη φορτώνει και προσπαθεί να την υλοποιήσει. Το αποτέλεσμα της υλοποίησης ορίζεται στο errorCode |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Προσπαθεί να υλοποιήσει την άδεια. Το αποτέλεσμα της υλοποίησης ορίζεται στο errorCode |
| static [SetMeteredLicense](./setmeteredlicense/)(bool, System::String) |  |
## Δείτε επίσης

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
