---
title: "metot"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " yöntem. Lisansı arar, yükler ve uygulamaya çalışır. Uygulamanın sonucu C++'ta errorCode değişkenine atanır."
type: docs
weight: 300
url: /tr/cpp/aspose.barcode/licensecore/setlicense/
---
## LicenseCore::SetLicense(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Lisansı arar, yükler ve uygulamaya çalışır. Uygulamanın sonucu errorCode değişkenine ayarlanır.

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::String licenseName, System::SharedPtr<System::Reflection::Assembly> clientAssembly, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licenseName | System::String | Tam veya kısa bir dosya adı ya da gömülü kaynağın adı olabilir. |
| clientAssembly | System::SharedPtr\<System::Reflection::Assembly\> | arama yolunu bulmak için çağıran derleme |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | lisans durumunu ve olası hata mesajı için ek bilgileri saklayan hata kodu |

## Ayrıca Bakınız

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## LicenseCore::SetLicense(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Lisansı uygulamaya çalışır. Uygulamanın sonucu errorCode değişkenine ayarlanır.

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | saklanan lisans ile akış |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | lisans durumunu ve olası hata mesajı için ek bilgileri saklayan hata kodu |

## Ayrıca Bakınız

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
