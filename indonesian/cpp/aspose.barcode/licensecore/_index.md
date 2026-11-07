---
title: "Aspose::BarCode::LicenseCore kelas"
linktitle: "LicenseCore"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::LicenseCore kelas. Kelas dengan membaca dan mengimplementasikan lisensi dalam C++."
type: docs
weight: 400
url: /id/cpp/aspose.barcode/licensecore/
---
## LicenseCore class


Kelas yang membaca dan mengimplementasikan lisensi

```cpp
class LicenseCore : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [EncodeSignature](./encodesignature/)(System::SharedPtr\<System::Object\>) | Menyandikan data menjadi tanda tangan |
| static [GetFileNameInFolderOfAssembly](./getfilenameinfolderofassembly/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>) | Mencoba menemukan nama file di folder assebly |
| [LicenseCore](./licensecore/)() | Menginisialisasi instance baru dari kelas [LicenseCore](./). |
| static [RemoveMeteredLicense](./removemeteredlicense/)() |  |
| [ResetLicense](./resetlicense/)() | Metode mengatur ulang status lisensi untuk penggunaan internal dan pengujian |
| [SetLicense](./setlicense/)(System::String, System::SharedPtr\<System::Reflection::Assembly\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Mencari lisensi, memuat dan mencoba mengimplementasikan. Hasil implementasi diatur ke errorCode |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Common::Generic::Types::Tup\<LicenseErrors, System::DateTime, System::DateTime\>>) | Mencoba mengimplementasikan lisensi. Hasil implementasi diatur ke errorCode |
| static [SetMeteredLicense](./setmeteredlicense/)(bool, System::String) |  |
## Lihat Juga

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
