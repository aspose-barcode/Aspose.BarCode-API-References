---
title: "metode"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Metode. Mencari lisensi, memuatnya, dan mencoba mengimplementasikan. Hasil implementasi disetel ke errorCode dalam C++."
type: docs
weight: 300
url: /id/cpp/aspose.barcode/licensecore/setlicense/
---
## LicenseCore::SetLicense(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Mencari lisensi, memuat dan mencoba mengimplementasikan. Hasil implementasi diatur ke errorCode

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::String licenseName, System::SharedPtr<System::Reflection::Assembly> clientAssembly, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licenseName | System::String | Dapat berupa nama file lengkap atau singkat atau nama sumber daya yang disematkan. |
| clientAssembly | System::SharedPtr\<System::Reflection::Assembly\> | assembly pemanggil untuk menemukan jalur pencarian |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | kode error yang menyimpan status lisensi dan informasi tambahan untuk kemungkinan pesan error |

## Lihat Juga

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## LicenseCore::SetLicense(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) method


Mencoba mengimplementasikan lisensi. Hasil implementasi diatur ke errorCode

```cpp
void Aspose::BarCode::LicenseCore::SetLicense(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Common::Generic::Types::Tup<LicenseErrors, System::DateTime, System::DateTime>> errorCode)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | stream dengan lisensi yang disimpan |
| errorCode | System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>> | kode error yang menyimpan status lisensi dan informasi tambahan untuk kemungkinan pesan error |

## Lihat Juga

* Class [Tup](../../../aspose.barcode.common.generic.types/tup/)
* Enum [LicenseErrors](../../licenseerrors/)
* Class [LicenseCore](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
