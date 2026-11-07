---
title: "method"
linktitle: "SetLicense"
second_title: "Aspose.BarCode для C++ справочник API"
description: " метод. Ищет лицензию, загружает её и пытается применить. Результат применения записывается в errorCode в C++."
type: docs
weight: 300
url: /ru/cpp/aspose.barcode/licensecore/setlicense/
---
## LicenseCore::SetLicense(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Ищет лицензию, загружает её и пытается реализовать. Результат реализации устанавливается в errorCode

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::String licenseName, System::SharedPtr<System::Reflection::Assembly> clientAssembly, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| licenseName | System::String | Может быть полным или коротким именем файла или именем встроенного ресурса. |
| clientAssembly | System::SharedPtr\<System::Reflection::Assembly\> | вызывающая сборка для поиска пути |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | код ошибки, который хранит состояние лицензии и дополнительную информацию для возможного сообщения об ошибке |

## См. также

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## LicenseCore::SetLicense(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Пытается реализовать лицензию. Результат реализации устанавливается в errorCode

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parameter | Type | Описание |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | поток с сохранённой лицензией |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | код ошибки, который хранит состояние лицензии и дополнительную информацию для возможного сообщения об ошибке |

## См. также

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
