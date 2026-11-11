---
title: "Kelas AztecExtendedParameters"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Kelas Aspose.BarCode.BarCodeRecognition.AztecExtendedParameters. Menyimpan data khusus dari barcode Aztec yang dikenali"
type: docs
weight: 40
url: /id/net/aspose.barcode.barcoderecognition/aztecextendedparameters/
---
## AztecExtendedParameters class

Menyimpan data khusus dari barcode Aztec yang dikenali

```csharp
public sealed class AztecExtendedParameters : BaseExtendedParameters
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Menguji apakah semua parameter hanya memiliki nilai default. |
| [IsReaderInitialization](../../aspose.barcode.barcoderecognition/aztecextendedparameters/isreaderinitialization/) { get; } | Menunjukkan apakah kode digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca barcode. Nilai default adalah false. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodeid/) { get; } | Mendapatkan ID barcode mode penambahan terstruktur Aztec. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah barcode. Nilai default adalah 0. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendbarcodescount/) { get; } | Mendapatkan jumlah barcode mode penambahan terstruktur Aztec. Nilai default adalah 0. Jumlah harus bernilai antara 1 hingga 26. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/aztecextendedparameters/structuredappendfileid/) { get; } | Mendapatkan ID File dari mode penambahan terstruktur Aztec. Nilai default adalah string kosong |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/aztecextendedparameters/equals/)(object) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai `AztecExtendedParameters` yang ditentukan. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/aztecextendedparameters/gethashcode/)() | Mengembalikan kode hash untuk instance ini. |
| override [ToString](../../aspose.barcode.barcoderecognition/aztecextendedparameters/tostring/)() | Mengembalikan representasi string yang dapat dibaca manusia dari `AztecExtendedParameters` ini. |
| [operator ==](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_equality/) | Mengembalikan nilai yang menunjukkan apakah nilai `AztecExtendedParameters` pertama sama dengan nilai kedua. |
| [operator !=](../../aspose.barcode.barcoderecognition/aztecextendedparameters/op_inequality/) | Mengembalikan nilai yang menunjukkan apakah nilai `AztecExtendedParameters` pertama berbeda dari nilai kedua. |

## Contoh

Contoh ini menunjukkan cara mendapatkan nilai mentah Aztec

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Aztec, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Aztec))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("Aztec barcode ID: " + result.Extended.Aztec.StructuredAppendBarcodeId);
        Console.WriteLine("Aztec barcodes count: " + result.Extended.Aztec.StructuredAppendBarcodesCount);
        Console.WriteLine("Aztec file ID: " + result.Extended.Aztec.StructuredAppendFileId);
        Console.WriteLine("Aztec is reader initialization: " + result.Extended.Aztec.IsReaderInitialization);
    }
}
```

### Lihat Juga

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


