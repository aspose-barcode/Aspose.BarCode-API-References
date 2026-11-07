---
title: "metode"
linktitle: "SetLicense"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " metode. Mengaktifkan lisensi library dalam C++."
type: docs
weight: 200
url: /id/cpp/aspose.barcode/license/setlicense/
---
## License::SetLicense(System::String) method


Melisensikan perpustakaan.

```cpp
void Aspose::BarCode::License::SetLicense(System::String licenseName)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licenseName | System::String | Dapat berupa nama file lengkap atau singkat atau nama sumber daya yang disematkan. |
## Catatan


Mencoba menemukan lisensi di lokasi berikut:

1. Jalur eksplisit.

2. Folder yang berisi assembly komponen **Aspose**.

3. Folder yang berisi assembly pemanggil klien.

4. Folder yang berisi assembly entri (startup).

5. Sebuah sumber daya tersemat dalam assembly pemanggil klien.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Jalur eksplisit.

2. Sebuah sumber daya tersemat dalam assembly pemanggil klien.

Dalam contoh ini, akan dicoba menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tersemat dari assembly pemanggil.
```cpp
[C#]
@verbatim
License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
@endverbatim
```


## Lihat Juga

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) method


Melisensikan perpustakaan.

```cpp
void Aspose::BarCode::License::SetLicense(System::SharedPtr<System::IO::Stream> stream)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | System::SharedPtr\<System::IO::Stream\> | Aliran yang berisi lisensi. |
## Catatan



Gunakan metode ini untuk memuat lisensi dari aliran.


```cpp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

## Lihat Juga

* Class [License](../)
* Namespace [Aspose::BarCode](../../)
* Library [Aspose.BarCode for C++](../../../)
