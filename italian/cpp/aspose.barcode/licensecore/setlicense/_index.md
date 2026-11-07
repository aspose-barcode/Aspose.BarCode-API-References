---
title: "method"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ Riferimento API"
description: " metodo. Cerca la licenza, la carica e tenta di implementarla. Il risultato dell'implementazione è impostato su errorCode in C++."
type: docs
weight: 300
url: /it/cpp/aspose.barcode/licensecore/setlicense/
---
## LicenseCore::SetLicense(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Cerca la licenza, la carica e tenta di implementarla. Il risultato dell'implementazione è impostato su errorCode.

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::String licenseName, System::SharedPtr<System::Reflection::Assembly> clientAssembly, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| licenseName | System::String | Può essere un nome file completo o breve o il nome di una risorsa incorporata. |
| clientAssembly | System::SharedPtr\<System::Reflection::Assembly\> | assembly chiamante per trovare il percorso di ricerca |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | codice di errore che memorizza lo stato della licenza e informazioni aggiuntive per un possibile messaggio di errore |

## Vedi anche

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## LicenseCore::SetLicense(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Tenta di implementare la licenza. Il risultato dell'implementazione è impostato su errorCode.

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parameter | Type | Descrizione |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | stream con licenza memorizzata |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | codice di errore che memorizza lo stato della licenza e informazioni aggiuntive per un possibile messaggio di errore |

## Vedi anche

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
