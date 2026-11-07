---
title: "Aspose::BarCode::BarCodeRecognition::BarCodeReader kelas"
linktitle: "BarCodeReader"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Aspose::BarCode::BarCodeRecognition::BarCodeReader kelas. BarCodeReader mengenkapsulasi sebuah gambar yang mungkin berisi satu atau beberapa barcode, kemudian dapat melakukan operasi ReadBarCodes untuk mendeteksi barcode dalam C++."
type: docs
weight: 500
url: /id/cpp/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class


[BarCodeReader](./) encapsulates an image which may contain one or several barcodes, it then can perform ReadBarCodes operation to detect barcodes.

```cpp
class BarCodeReader : public System::IDisposable
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [Abort](./abort/)() | Fungsi meminta penghentian sesi pengenalan saat ini dari thread lain. Abort adalah metode yang tidak dapat diblokir dan mengembalikan kontrol segera setelah dipanggil. Metode ini harus digunakan ketika proses pengenalan terlalu lama. |
| [BarCodeReader](./barcodereader/)() | Menginisialisasi instance baru dari kelas [BarCodeReader](./) dengan nilai default. Memerlukan penetapan gambar (SetBitmapImage()) sebelum memanggil metode [ReadBarCodes()](./readbarcodes/). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Menginisialisasi instance baru dari kelas [BarCodeReader](./) dari sebuah gambar. |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::SharedPtr\<BaseDecodeType\>) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::String) | Menginisialisasi instance baru dari kelas [BarCodeReader](./) dari file. |
| [BarCodeReader](./barcodereader/)(System::String, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::String, System::SharedPtr\<BaseDecodeType\>) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<BaseDecodeType\>) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<System::IO::Stream\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, System::SharedPtr\<BaseDecodeType\>) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, System::SharedPtr\<BaseDecodeType\>) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, System::SharedPtr\<BaseDecodeType\>) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>, const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Menginisialisasi instance baru dari kelas [BarCodeReader](./). |
| [BarCodeReader](./barcodereader/)(System::SharedPtr\<LuminanceFrame\>) | Menginisialisasi instance baru dari kelas [BarCodeReader](./) dari sebuah frame luminansi. |
| [Dispose](./dispose/)() override | Lepaskan sumber daya |
| [ExportToXml](./exporttoxml/)(System::String) | Mengekspor properti [BarCode](../../aspose.barcode/) ke file xml yang ditentukan |
| [ExportToXml](./exporttoxml/)(System::SharedPtr\<System::IO::Stream\>) | Mengekspor properti [BarCode](../../aspose.barcode/) ke aliran xml yang ditentukan |
| [get_BarCodeReadType](./get_barcodereadtype/)() | Mendapatkan tipe dekode barcode yang digunakan untuk pengenalan. Harus diatur sebelum memanggil [ReadBarCodes](./readbarcodes/). |
| [get_BarcodeSettings](./get_barcodesettings/)() | Parameter dekode utama [BarCode](../../aspose.barcode/). Berisi parameter yang memengaruhi data yang dikenali. |
| [get_FoundBarCodes](./get_foundbarcodes/)() | Mendapatkan array [BarCodeResult](../barcoderesult/) yang dikenali |
| [get_FoundCount](./get_foundcount/)() | Mendapatkan jumlah barcode yang dikenali |
| static [get_ProcessorSettings](./get_processorsettings/)() | Mendapatkan pengaturan penggunaan inti prosesor. |
| [get_QualitySettings](./get_qualitysettings/)() | [QualitySettings](../qualitysettings/) memungkinkan mengkonfigurasi kualitas dan kecepatan pengenalan secara manual. Anda dapat dengan cepat mengatur [QualitySettings](../qualitysettings/) menggunakan preset bawaan: HighPerformance, NormalQuality, HighQuality, MaxBarCodes atau Anda dapat mengkonfigurasi opsi terpisah secara manual. Nilai default dari [QualitySettings](../qualitysettings/) adalah NormalQuality. |
| [get_Timeout](./get_timeout/)() | Mendapatkan batas waktu proses pengenalan dalam milidetik. |
| static [ImportFromXml](./importfromxml/)(System::String) | Mengimpor properti [BarCode](../../aspose.barcode/) dari file xml yang ditentukan dan menerapkannya ke instance [BarCodeReader](./) saat ini. |
| static [ImportFromXml](./importfromxml/)(System::SharedPtr\<System::IO::Stream\>) | Mengimpor properti [BarCode](../../aspose.barcode/) dari aliran xml yang ditentukan dan menerapkannya ke instance [BarCodeReader](./) saat ini. |
| [ReadBarCodes](./readbarcodes/)() | Membaca [BarCodeResult](../barcoderesult/) dari gambar. |
| [set_BarCodeReadType](./set_barcodereadtype/)(System::SharedPtr\<BaseDecodeType\>) | Mengatur jenis dekode barcode yang digunakan untuk pengenalan. Harus diatur sebelum memanggil [ReadBarCodes](./readbarcodes/). |
| [set_QualitySettings](./set_qualitysettings/)(System::SharedPtr\<Aspose::BarCode::BarCodeRecognition::QualitySettings\>) | [QualitySettings](../qualitysettings/) memungkinkan mengkonfigurasi kualitas dan kecepatan pengenalan secara manual. Anda dapat dengan cepat mengatur [QualitySettings](../qualitysettings/) menggunakan preset bawaan: HighPerformance, NormalQuality, HighQuality, MaxBarCodes atau Anda dapat mengkonfigurasi opsi terpisah secara manual. Nilai default dari [QualitySettings](../qualitysettings/) adalah NormalQuality. |
| [set_Timeout](./set_timeout/)(int32_t) | Mengatur batas waktu proses pengenalan dalam milidetik. |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>) | Mengatur gambar bitmap untuk pengenalan. Harus dipanggil sebelum metode [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Mengatur gambar bitmap dan area untuk pengenalan. Harus dipanggil sebelum metode [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::Drawing::Bitmap\>, System::Drawing::Rectangle) | Mengatur gambar bitmap dan area untuk pengenalan. Harus dipanggil sebelum metode [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::String) | Mengatur file gambar untuk pengenalan. Harus dipanggil sebelum metode [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<System::IO::Stream\>) | Mengatur aliran gambar untuk pengenalan. Harus dipanggil sebelum metode [ReadBarCodes()](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::Drawing::Rectangle) | Mengatur bingkai luminansi dan area untuk pengenalan. Harus dipanggil sebelum metode [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>, System::ArrayPtr\<System::Drawing::Rectangle\>) | Mengatur bingkai luminansi dan area untuk pengenalan. Harus dipanggil sebelum metode [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeImage](./setbarcodeimage/)(System::SharedPtr\<LuminanceFrame\>) | Mengatur bingkai luminansi untuk pengenalan. Harus dipanggil sebelum metode [ReadBarCodes](./readbarcodes/). |
| [SetBarCodeReadType](./setbarcodereadtype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Mengatur array tipe [SingleDecodeType](../singledecodetype/) untuk pengenalan. Harus dipanggil sebelum metode [ReadBarCodes()](./readbarcodes/). |
## Catatan


Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.
```cpp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

## Lihat Juga

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
