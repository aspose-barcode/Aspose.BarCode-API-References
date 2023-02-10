---
title: QualitySettings
second_title: Aspose.BarCode untuk .NET API Referensi
description: QualitySettings memungkinkan untuk mengonfigurasi kualitas dan kecepatan pengenalan secara manual. Anda dapat dengan cepat mengatur QualitySettings dengan preset tertanam HighPerformance NormalQuality HighQuality MaxBarCodes atau Anda dapat mengonfigurasi opsi terpisah secara manual. Nilai default QualitySettings adalah NormalQuality.
type: docs
weight: 270
url: /id/net/aspose.barcode.barcoderecognition/qualitysettings/
---
## QualitySettings class

QualitySettings memungkinkan untuk mengonfigurasi kualitas dan kecepatan pengenalan secara manual. Anda dapat dengan cepat mengatur QualitySettings dengan preset tertanam: HighPerformance, NormalQuality, HighQuality, MaxBarCodes atau Anda dapat mengonfigurasi opsi terpisah secara manual. Nilai default QualitySettings adalah NormalQuality.

```csharp
public sealed class QualitySettings
```

## Properti

| Nama | Keterangan |
| --- | --- |
| static [HighPerformance](../../aspose.barcode.barcoderecognition/qualitysettings/highperformance/) { get; } | Prasetel kualitas pengenalan Performa Tinggi. Barcode berkualitas tinggi dikenali dengan baik dalam mode ini. |
| static [HighQuality](../../aspose.barcode.barcoderecognition/qualitysettings/highquality/) { get; } | Prasetel kualitas pengenalan Kualitas Tinggi. Prasetel ini dikembangkan untuk barcode berkualitas rendah. Memungkinkan untuk mendeteksi barcode yang diagonal dan sangat rusak. |
| static [HighQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/highqualitydetection/) { get; } | Preset kualitas pengenalan HighQualityDetection. Sama seperti NormalQuality tetapi dengan kualitas tinggi[`DetectorSettings`](./detectorsettings/) |
| static [MaxBarCodes](../../aspose.barcode.barcoderecognition/qualitysettings/maxbarcodes/) { get; } | Preset kualitas pengenalan MaxBarCodes. Prasetel ini dikembangkan untuk mengenali semua kemungkinan kode batang, bahkan kode batang yang salah. |
| static [MaxQualityDetection](../../aspose.barcode.barcoderecognition/qualitysettings/maxqualitydetection/) { get; } | Preset kualitas pengenalan MaxQualityDetection. Sama seperti NormalQuality tetapi dengan kualitas tertinggi[`DetectorSettings`](./detectorsettings/) . Memungkinkan untuk mendeteksi barcode diagonal dan rusak. |
| static [NormalQuality](../../aspose.barcode.barcoderecognition/qualitysettings/normalquality/) { get; } | Prasetel kualitas pengenalan Kualitas Normal. Cocok untuk sebagian besar barcode |
| [AllowComplexBackground](../../aspose.barcode.barcoderecognition/qualitysettings/allowcomplexbackground/) { get; set; } | Mengizinkan mesin mengenali kode batang warna pada latar belakang warna sebagai pemindaian tambahan. Mode sangat lambat. |
| [AllowDatamatrixIndustrialBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowdatamatrixindustrialbarcodes/) { get; set; } | Mengizinkan mesin untuk Datamatrix mengenali kode batang Datamatrix industri yang putus-putus. Mode lambat yang membantu hanya untuk barcode putus-putus yang terdiri dari bintik-bintik. |
| [AllowDecreasedImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowdecreasedimage/) { get; set; } | Mengizinkan mesin mengenali gambar yang dikurangi sebagai pemindaian tambahan. Ukuran untuk penurunan dipilih oleh algoritme mesin internal. Mode membantu mengenali kode batang yang bersuara dan buram tetapi ditangkap dengan resolusi tinggi. |
| [AllowDetectScanGap](../../aspose.barcode.barcoderecognition/qualitysettings/allowdetectscangap/) { get; set; } | Mengizinkan mesin menggunakan celah di antara pemindaian untuk meningkatkan kecepatan pengenalan. Mode dapat membuat masalah pengenalan dengan barcode tinggi rendah. |
| [AllowIncorrectBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/allowincorrectbarcodes/) { get; set; } | Mengizinkan mesin mengenali kode batang yang memiliki nilai checksumm atau salah. Mode dapat digunakan untuk mengenali barcode rusak dengan teks yang salah. |
| [AllowInvertImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowinvertimage/) { get; set; } | Memungkinkan mesin mengenali gambar berwarna terbalik sebagai pemindaian tambahan. Mode dapat digunakan saat kode batang berwarna putih dengan latar belakang hitam. |
| [AllowMedianSmoothing](../../aspose.barcode.barcoderecognition/qualitysettings/allowmediansmoothing/) { get; set; } | Mengizinkan mesin mengaktifkan perataan median sebagai pemindaian tambahan. Mode membantu mengenali kode batang yang bersuara. |
| [AllowMicroWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowmicrowhitespotsremoving/) { get; set; } | Mengizinkan mesin kode batang Pos untuk mengenali gambar yang sedikit bersuara. Mode membantu mengenali barcode Pos yang sedikit rusak. |
| [AllowOneDFastBarcodesDetector](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedfastbarcodesdetector/) { get; set; } | Memungkinkan mesin untuk kode batang 1D dengan cepat mengenali kode batang berkualitas tinggi yang mengisi hampir seluruh gambar. Mode membantu mengenali kode batang yang dihasilkan dengan cepat dari Internet. |
| [AllowOneDWipedBarsRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowonedwipedbarsrestoration/) { get; set; } | Mengizinkan mesin untuk kode batang 1D untuk mengenali kode batang dengan pola batang tunggal yang dihapus/direkatkan. |
| [AllowQRMicroQrRestoration](../../aspose.barcode.barcoderecognition/qualitysettings/allowqrmicroqrrestoration/) { get; set; } | Memungkinkan mesin untuk QR/MicroQR mengenali kode batang MicroQR yang rusak. |
| [AllowRegularImage](../../aspose.barcode.barcoderecognition/qualitysettings/allowregularimage/) { get; set; } | Mengizinkan mesin mengenali gambar biasa tanpa pemulihan apa pun sebagai pemindaian utama. Mode untuk mengenali gambar apa adanya. |
| [AllowSaltAndPaperFiltering](../../aspose.barcode.barcoderecognition/qualitysettings/allowsaltandpaperfiltering/) { get; set; } | Mengizinkan mesin mengenali kode batang dengan jenis kebisingan garam dan kertas. Mode dapat menghilangkan noise kecil dengan titik putih dan hitam. |
| [AllowWhiteSpotsRemoving](../../aspose.barcode.barcoderecognition/qualitysettings/allowwhitespotsremoving/) { get; set; } | Memungkinkan mesin mengenali gambar tanpa bintik putih kecil sebagai pemindaian tambahan. Mode membantu mengenali gambar bersuara serta median smoothing filtering. |
| [CheckMore1DVariants](../../aspose.barcode.barcoderecognition/qualitysettings/checkmore1dvariants/) { get; set; } | Mengizinkan mesin mengenali kode batang 1D dengan checksum dengan mencentang lebih banyak varian pengenalan. Nilai default: False. |
| [DetectorSettings](../../aspose.barcode.barcoderecognition/qualitysettings/detectorsettings/) { get; set; } | Pengaturan detektor kode batang. |
| [FastScanOnly](../../aspose.barcode.barcoderecognition/qualitysettings/fastscanonly/) { get; set; } | Memungkinkan mesin untuk kode batang 1D dengan cepat mengenali potongan tengah gambar dan mengembalikan hasil tanpa menggunakan algoritme yang memakan waktu. |
| [MedianSmoothingWindowSize](../../aspose.barcode.barcoderecognition/qualitysettings/mediansmoothingwindowsize/) { get; set; } | Ukuran jendela untuk perataan median. Nilai umum adalah 3 atau 4. Nilai default adalah 3. AllowMedianSmoothing harus disetel. |
| [ReadTinyBarcodes](../../aspose.barcode.barcoderecognition/qualitysettings/readtinybarcodes/) { get; set; } | Mengizinkan mesin mengenali kode batang kecil pada gambar besar. Diabaikan jika[`AllowIncorrectBarcodes`](./allowincorrectbarcodes/) diatur ke True. Nilai default: False. |
| [UseOldBarcodeDetector](../../aspose.barcode.barcoderecognition/qualitysettings/useoldbarcodedetector/) { get; set; } | Beralih ke detektor barcode lama. |

### Contoh

Contoh ini menunjukkan cara menggunakan QualitySettings dengan BarCodeReader

```csharp
[C#]
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // atur mode kinerja tinggi
   reader.QualitySettings = QualitySettings.HighPerformance;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // mode kualitas normal diatur secara default
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // atur mode kualitas tinggi dengan pengenalan kecepatan rendah 
   reader.QualitySettings = QualitySettings.HighQuality;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // atur mode barcode maks, yang mencoba menemukan semua kemungkinan barcode, bahkan salah. Mode pengenalan paling lambat
   reader.QualitySettings = QualitySettings.MaxBarCodes;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // atur mode kinerja tinggi
   reader.QualitySettings = QualitySettings.HighPerformance;
   // atur opsi terpisah
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.Code39Standard, DecodeType.Code128))
{
   // mode default adalah Kualitas Normal
   // atur opsi terpisah
   reader.QualitySettings.AllowMedianSmoothing = true;
   reader.QualitySettings.MedianSmoothingWindowSize = 5;
   foreach (BarCodeResult result in reader.ReadBarCodes())
      Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
[VB.NET]
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'mengatur mode kinerja tinggi
    reader.QualitySettings = QualitySettings.HighPerformance
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'mode kualitas normal diatur secara default
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'atur mode kualitas tinggi dengan pengenalan kecepatan rendah
    reader.QualitySettings = QualitySettings.HighQuality
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
    'atur mode barcode maks, yang mencoba menemukan semua kemungkinan barcode, bahkan salah. Mode pengenalan paling lambat
    reader.QualitySettings = QualitySettings.MaxBarCodes
    For Each result As BarCodeResult In reader.ReadBarCodes()
        Console.WriteLine("BarCode Type: " + result.CodeTypeName)
    Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'mengatur mode kinerja tinggi
   reader.QualitySettings = QualitySettings.HighPerformance
   'mengatur pilihan terpisah
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
Using reader As New BarCodeReader("c:\test.png", DecodeType.Code39Standard, DecodeType.Code128)
   'mode default adalah NormalQuality
   'mengatur pilihan terpisah
   reader.QualitySettings.AllowMedianSmoothing = True
   reader.QualitySettings.MedianSmoothingWindowSize = 5
   For Each result As BarCodeResult In reader.ReadBarCodes()
       Console.WriteLine("BarCode Type: " + result.CodeTypeName)
   Next
End Using
```

### Lihat juga

* ruang nama [Aspose.BarCode.BarCodeRecognition](../../aspose.barcode.barcoderecognition/)
* perakitan [Aspose.BarCode](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.BarCode.dll -->
