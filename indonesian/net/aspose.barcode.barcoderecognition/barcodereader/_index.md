---
title: BarCodeReader
second_title: Aspose.BarCode untuk .NET API Referensi
description: BarCodeReader mengenkapsulasi gambar yang mungkin berisi satu atau beberapa barcode kemudian dapat melakukan operasi ReadBarCodes untuk mendeteksi barcode.
type: docs
weight: 60
url: /id/net/aspose.barcode.barcoderecognition/barcodereader/
---
## BarCodeReader class

BarCodeReader mengenkapsulasi gambar yang mungkin berisi satu atau beberapa barcode, kemudian dapat melakukan operasi ReadBarCodes untuk mendeteksi barcode.

```csharp
public class BarCodeReader : Component
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [BarCodeReader](barcodereader/#constructor)() | Menginisialisasi instance baru dari`BarCodeReader` kelas dengan nilai default. Diperlukan untuk menyetel gambar (SetBitmapImage()) sebelum memanggil metode ReadBarCodes(). |
| [BarCodeReader](barcodereader/#constructor_1)(Bitmap) | Menginisialisasi instance baru dari`BarCodeReader` kelas dari gambar. |
| [BarCodeReader](barcodereader/#constructor_8)(Stream) | Menginisialisasi instance baru dari`BarCodeReader` kelas. |
| [BarCodeReader](barcodereader/#constructor_11)(string) | Menginisialisasi instance baru dari`BarCodeReader` kelas dari file. |
| [BarCodeReader](barcodereader/#constructor_2)(Bitmap, BaseDecodeType) | Menginisialisasi instance baru dari`BarCodeReader` kelas. |
| [BarCodeReader](barcodereader/#constructor_3)(Bitmap, params BaseDecodeType[]) | Menginisialisasi instance baru dari`BarCodeReader` kelas. |
| [BarCodeReader](barcodereader/#constructor_9)(Stream, BaseDecodeType) | Menginisialisasi instance baru dari`BarCodeReader` kelas. |
| [BarCodeReader](barcodereader/#constructor_10)(Stream, params BaseDecodeType[]) | Menginisialisasi instance baru dari`BarCodeReader` kelas. |
| [BarCodeReader](barcodereader/#constructor_12)(string, BaseDecodeType) | Menginisialisasi instance baru dari`BarCodeReader` kelas. |
| [BarCodeReader](barcodereader/#constructor_13)(string, params BaseDecodeType[]) | Menginisialisasi instance baru dari`BarCodeReader` kelas. |
| [BarCodeReader](barcodereader/#constructor_4)(Bitmap, Rectangle, BaseDecodeType) | Menginisialisasi instance baru dari`BarCodeReader` kelas. |
| [BarCodeReader](barcodereader/#constructor_5)(Bitmap, Rectangle, params BaseDecodeType[]) | Menginisialisasi instance baru dari`BarCodeReader` kelas. |
| [BarCodeReader](barcodereader/#constructor_6)(Bitmap, Rectangle[], BaseDecodeType) | Menginisialisasi instance baru dari`BarCodeReader` kelas. |
| [BarCodeReader](barcodereader/#constructor_7)(Bitmap, Rectangle[], params BaseDecodeType[]) | Menginisialisasi instance baru dari`BarCodeReader` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [BarcodeSettings](../../aspose.barcode.barcoderecognition/barcodereader/barcodesettings/) { get; } | Parameter decoding BarCode utama. Berisi parameter yang berpengaruh pada data yang dikenali. |
| [FoundBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/foundbarcodes/) { get; } | Diakui[`BarCodeResult`](../barcoderesult/)s array |
| [FoundCount](../../aspose.barcode.barcoderecognition/barcodereader/foundcount/) { get; } | Mendapatkan jumlah kode batang yang dikenali |
| [QualitySettings](../../aspose.barcode.barcoderecognition/barcodereader/qualitysettings/) { get; set; } | QualitySettings memungkinkan untuk mengonfigurasi kualitas dan kecepatan pengenalan secara manual. Anda dapat dengan cepat mengatur QualitySettings dengan preset tertanam: HighPerformance, NormalQuality, HighQuality, MaxBarCodes atau Anda dapat mengonfigurasi opsi terpisah secara manual. Nilai default QualitySettings adalah NormalQuality. |
| [Timeout](../../aspose.barcode.barcoderecognition/barcodereader/timeout/) { get; set; } | Mendapat atau menyetel batas waktu proses pengenalan dalam milidetik. |
| static [ProcessorSettings](../../aspose.barcode.barcoderecognition/barcodereader/processorsettings/) { get; } | Mendapatkan pengaturan penggunaan inti prosesor. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml)(Stream) | Mengimpor properti BarCode dari xml-stream yang ditentukan dan menerapkannya ke instance BarCodeReader saat ini. |
| static [ImportFromXml](../../aspose.barcode.barcoderecognition/barcodereader/importfromxml/#importfromxml_1)(string) | Mengimpor properti BarCode dari file xml yang ditentukan dan menerapkannya ke instance BarCodeReader saat ini. |
| [Abort](../../aspose.barcode.barcoderecognition/barcodereader/abort/)() | Fungsi meminta penghentian sesi pengenalan saat ini dari utas lainnya. Batalkan adalah metode yang tidak dapat diblokir dan mengembalikan kontrol tepat setelah menelepon. Metode ini sebaiknya digunakan saat proses pengenalan terlalu lama. |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml)(Stream) | Mengekspor properti BarCode ke aliran xml yang ditentukan |
| [ExportToXml](../../aspose.barcode.barcoderecognition/barcodereader/exporttoxml/#exporttoxml_1)(string) | Mengekspor properti BarCode ke file xml yang ditentukan |
| [ReadBarCodes](../../aspose.barcode.barcoderecognition/barcodereader/readbarcodes/)() | Baca[`BarCodeResult`](../barcoderesult/) s dari gambar. |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage)(Bitmap) | Mengatur gambar bitmap untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_3)(Stream) | Mengatur aliran gambar untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_4)(string) | Mengatur file gambar untuk dikenali. Harus dipanggil sebelum metode ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_1)(Bitmap, Rectangle) | Mengatur gambar bitmap dan area untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes(). |
| [SetBarCodeImage](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodeimage/#setbarcodeimage_2)(Bitmap, Rectangle[]) | Mengatur gambar bitmap dan area untuk dikenali. Harus dipanggil sebelum metode ReadBarCodes(). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/#setbarcodereadtype)(BaseDecodeType) | Mengatur jenis dekode untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes(). |
| [SetBarCodeReadType](../../aspose.barcode.barcoderecognition/barcodereader/setbarcodereadtype/#setbarcodereadtype_1)(params SingleDecodeType[]) | Set[`SingleDecodeType`](../singledecodetype/) ketik array untuk pengenalan. Harus dipanggil sebelum metode ReadBarCodes(). |

### Contoh

Contoh ini menunjukkan cara mendeteksi barcode Code39 dan Code128.

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
    Next
End Using
```

### Lihat juga

* ruang nama [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
