---
title: "Kelas DataMatrixExtendedParameters"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Kelas Aspose.BarCode.BarCodeRecognition.DataMatrixExtendedParameters. Menyimpan data khusus dari kode batang DataMatrix yang dikenali"
type: docs
weight: 220
url: /id/net/aspose.barcode.barcoderecognition/datamatrixextendedparameters/
---
## DataMatrixExtendedParameters class

Menyimpan data khusus dari kode batang DataMatrix yang dikenali

```csharp
public sealed class DataMatrixExtendedParameters : BaseExtendedParameters
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Menguji apakah semua parameter hanya memiliki nilai default. |
| [IsReaderProgramming](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/isreaderprogramming/) { get; } | Menunjukkan apakah kode digunakan untuk memberi instruksi kepada pembaca agar menafsirkan data berikut sebagai instruksi untuk inisialisasi atau pemrograman ulang pembaca barcode. Nilai default adalah false. |
| [StructuredAppendBarcodeId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodeid/) { get; } | Mendapatkan ID dari kode batang mode penambahan terstruktur DataMatrix. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah kode batang. Nilai default adalah -1. |
| [StructuredAppendBarcodesCount](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendbarcodescount/) { get; } | Mendapatkan jumlah kode batang mode penambahan terstruktur DataMatrix. Nilai default adalah -1. Jumlah harus berupa nilai antara 1 hingga 35. |
| [StructuredAppendFileId](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/structuredappendfileid/) { get; } | Mendapatkan ID dari kode batang mode penambahan terstruktur DataMatrix. ID dimulai dari 1 dan harus kurang atau sama dengan jumlah kode batang. Nilai default adalah -1. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/equals/)(object) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan nilai `DataMatrixExtendedParameters` yang ditentukan. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/gethashcode/)() | Mengembalikan kode hash untuk instance ini. |
| override [ToString](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/tostring/)() | Mengembalikan representasi string yang dapat dibaca manusia dari `DataMatrixExtendedParameters`. |
| [operator ==](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_equality/) | Mengembalikan nilai yang menunjukkan apakah nilai `DataMatrixExtendedParameters` pertama sama dengan nilai kedua. |
| [operator !=](../../aspose.barcode.barcoderecognition/datamatrixextendedparameters/op_inequality/) | Mengembalikan nilai yang menunjukkan apakah nilai `DataMatrixExtendedParameters` pertama berbeda dari nilai kedua. |

## Contoh

Contoh ini menunjukkan cara mendapatkan nilai mentah DataMatrix

```csharp
[C#]
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DataMatrix, "12345"))
{
    generator.Save(@"c:\test.png");
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DataMatrix))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode type: " + result.CodeTypeName);
        Console.WriteLine("BarCode codetext: " + result.CodeText);
        Console.WriteLine("DataMatrix barcode ID: " + result.Extended.DataMatrix.StructuredAppendBarcodeId);
        Console.WriteLine("DataMatrix barcodes count: " + result.Extended.DataMatrix.StructuredAppendBarcodesCount);
        Console.WriteLine("DataMatrix file ID: " + result.Extended.DataMatrix.StructuredAppendFileId);
        Console.WriteLine("DataMatrix is reader programming: " + result.Extended.DataMatrix.IsReaderProgramming);
    }
}
```

### Lihat Juga

* class [BaseExtendedParameters](../baseextendedparameters/)
* namespace [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../)


