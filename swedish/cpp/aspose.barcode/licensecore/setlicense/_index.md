---
title: "metod"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ API-referens"
description: " metod. Söker efter licens, laddar och försöker implementera. Resultatet av implementeringen sätts till errorCode i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.barcode/licensecore/setlicense/
---
## LicenseCore::SetLicense(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Söker licens, laddar och försöker implementera. Resultatet av implementeringen sätts till errorCode.

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::String licenseName, System::SharedPtr<System::Reflection::Assembly> clientAssembly, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseName | System::String | Kan vara ett fullständigt eller kort filnamn eller namn på en inbäddad resurs. |
| clientAssembly | System::SharedPtr\<System::Reflection::Assembly\> | anropande assembly för att hitta sökväg |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | felkod som lagrar licenstillstånd och ytterligare information för möjligt felmeddelande |

## Se även

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## LicenseCore::SetLicense(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Försöker implementera licensen. Resultatet av implementeringen sätts till errorCode.

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | System::SharedPtr\<System::IO::Stream\> | ström med lagrad licens |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | felkod som lagrar licenstillstånd och ytterligare information för möjligt felmeddelande |

## Se även

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
