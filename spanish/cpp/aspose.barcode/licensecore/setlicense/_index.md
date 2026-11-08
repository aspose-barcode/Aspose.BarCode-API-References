---
title: "método"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ Referencia de API"
description: " método. Busca la licencia, la carga e intenta implementarla. El resultado de la implementación se asigna a errorCode en C++."
type: docs
weight: 300
url: /es/cpp/aspose.barcode/licensecore/setlicense/
---
## LicenseCore::SetLicense(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Busca la licencia, la carga e intenta implementarla. El resultado de la implementación se asigna a errorCode.

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::String licenseName, System::SharedPtr<System::Reflection::Assembly> clientAssembly, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| licenseName | System::String | Puede ser un nombre de archivo completo o corto, o el nombre de un recurso incrustado. |
| clientAssembly | System::SharedPtr\<System::Reflection::Assembly\> | ensamblado que llama para encontrar la ruta de búsqueda |
| errorCode | System::SharedPtr\\<Common::Generic::Types::Tup\\<LicenseErrors, System::DateTime, System::DateTime\\>> | código de error que almacena el estado de la licencia e información adicional para un posible mensaje de error |

## Ver también

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## LicenseCore::SetLicense(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Intenta implementar la licencia. El resultado de la implementación se asigna a errorCode.

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | flujo con la licencia almacenada |
| errorCode | System::SharedPtr\\<Common::Generic::Types::Tup\\<LicenseErrors, System::DateTime, System::DateTime\\>> | código de error que almacena el estado de la licencia e información adicional para un posible mensaje de error |

## Ver también

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
