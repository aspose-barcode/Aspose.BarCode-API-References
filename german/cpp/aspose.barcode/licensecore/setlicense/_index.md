---
title: "Methode"
linktitle: "SetLicense"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: " Methode. Sucht die Lizenz, lädt sie und versucht sie zu implementieren. Das Ergebnis der Implementierung wird in C++ in errorCode gesetzt."
type: docs
weight: 300
url: /de/cpp/aspose.barcode/licensecore/setlicense/
---
## LicenseCore::SetLicense(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Sucht die Lizenz, lädt sie und versucht, sie zu implementieren. Das Ergebnis der Implementierung wird in errorCode gesetzt.

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::String licenseName, System::SharedPtr<System::Reflection::Assembly> clientAssembly, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseName | System::String | Kann ein voller oder kurzer Dateiname oder der Name einer eingebetteten Ressource sein. |
| clientAssembly | System::SharedPtr\<System::Reflection::Assembly\> | Aufrufendes Assembly, um den Suchpfad zu ermitteln. |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | Fehlercode, der den Lizenzstatus und zusätzliche Informationen für mögliche Fehlermeldungen enthält. |

## Siehe auch

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## LicenseCore::SetLicense(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Versucht, die Lizenz zu implementieren. Das Ergebnis der Implementierung wird in errorCode gesetzt.

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | Stream mit gespeicherter Lizenz |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | Fehlercode, der den Lizenzstatus und zusätzliche Informationen für mögliche Fehlermeldungen enthält. |

## Siehe auch

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
