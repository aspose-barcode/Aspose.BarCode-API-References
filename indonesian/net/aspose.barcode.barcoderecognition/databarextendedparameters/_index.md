---
title: DataBarExtendedParameters
second_title: Aspose.BarCode untuk .NET API Referensi
description: Menyimpan informasi tambahan DataBar dari barcode yang dikenali
type: docs
weight: 180
url: /id/net/aspose.barcode.barcoderecognition/databarextendedparameters/
---
## DataBarExtendedParameters class

Menyimpan informasi tambahan DataBar dari barcode yang dikenali

```csharp
public sealed class DataBarExtendedParameters : BaseExtendedParameters
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Is2DCompositeComponent](../../aspose.barcode.barcoderecognition/databarextendedparameters/is2dcompositecomponent/) { get; } | Mendapatkan bendera komponen komposit DataBar 2D. Nilai default salah. |
| [IsEmpty](../../aspose.barcode.barcoderecognition/baseextendedparameters/isempty/) { get; } | Menguji apakah semua parameter hanya memiliki nilai default |

## Metode

| Nama | Keterangan |
| --- | --- |
| override [Equals](../../aspose.barcode.barcoderecognition/databarextendedparameters/equals/)(object) | Mengembalikan nilai yang menunjukkan apakah instance ini sama dengan yang ditentukan`DataBarExtendedParameters` nilai. |
| override [GetHashCode](../../aspose.barcode.barcoderecognition/databarextendedparameters/gethashcode/)() | Mengembalikan kode hash untuk instance ini. |
| override [ToString](../../aspose.barcode.barcoderecognition/databarextendedparameters/tostring/)() | Mengembalikan representasi string yang dapat dibaca manusia dari ini`DataBarExtendedParameters` . |
| [operator ==](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_equality/) | Mengembalikan nilai yang menunjukkan apakah yang pertama`DataBarExtendedParameters` nilainya sama dengan detik. |
| [operator !=](../../aspose.barcode.barcoderecognition/databarextendedparameters/op_inequality/) | Mengembalikan nilai yang menunjukkan jika yang pertama`DataBarExtendedParameters` nilainya berbeda dengan yang kedua. |

### Contoh

Contoh ini menunjukkan cara mendapatkan informasi tambahan DataBar

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.DatabarOmniDirectional))
{
    foreach (BarCodeResult result in reader.ReadBarCodes())
    {
        Console.WriteLine("BarCode Type: " + result.CodeTypeName);
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity);
    }
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.DatabarOmniDirectional)
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
        Console.WriteLine("BarCode CodeText: " + result.CodeText)
        Console.WriteLine("QR Structured Append Quantity: " + result.Extended.QR.QRStructuredAppendModeBarCodesQuantity)
    Next
End Using
```

### Lihat juga

* class [BaseExtendedParameters](../baseextendedparameters/)
* ruang nama [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->