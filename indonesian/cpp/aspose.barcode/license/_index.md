---
title: "Aspose::BarCode::License kelas"
linktitle: "Lisensi"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::License kelas. Menyediakan metode untuk melisensikan komponen di C++."
type: docs
weight: 300
url: /id/cpp/aspose.barcode/license/
---
## License class


Menyediakan metode untuk melisensikan komponen.

```cpp
class License : public System::Object
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [License](./license/)() | Menginisialisasi instance baru dari kelas ini. |
| [SetLicense](./setlicense/)(System::String) | Melisensikan perpustakaan. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>) | Melisensikan perpustakaan. |
## Catatan


Dalam contoh ini, akan dicoba menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tersemat dari assembly pemanggil.
```cpp
[C#]
@verbatim
License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
@endverbatim
```

## Lihat Juga

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
