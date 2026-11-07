---
title: "methode"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ API-referentie"
description: " methode. Zoekt licentie, laadt en probeert te implementeren. Het resultaat van de implementatie wordt ingesteld op errorCode in C++."
type: docs
weight: 300
url: /nl/cpp/aspose.barcode/licensecore/setlicense/
---
## LicenseCore::SetLicense(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Zoekt licentie, laadt en probeert te implementeren. Het resultaat van de implementatie wordt toegewezen aan errorCode.

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::String licenseName, System::SharedPtr<System::Reflection::Assembly> clientAssembly, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| licenseName | System::String | Kan een volledige of korte bestandsnaam of de naam van een ingesloten resource zijn. |
| clientAssembly | System::SharedPtr\<System::Reflection::Assembly\> | aanroepende assembly om zoekpad te vinden |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | foutcode die de licentiestatus opslaat en aanvullende informatie voor een mogelijke foutmelding bevat |

## Zie ook

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## LicenseCore::SetLicense(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Probeert de licentie te implementeren. Het resultaat van de implementatie wordt toegewezen aan errorCode.

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | stroom met opgeslagen licentie |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | foutcode die de licentiestatus opslaat en aanvullende informatie voor een mogelijke foutmelding bevat |

## Zie ook

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
