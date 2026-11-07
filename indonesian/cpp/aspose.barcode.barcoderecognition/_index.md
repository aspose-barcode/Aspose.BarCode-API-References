---
title: "Namespace Aspose::BarCode::BarCodeRecognition"
linktitle: "Aspose::BarCode::BarCodeRecognition"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Cara menggunakan namespace Aspose::BarCode::BarCodeRecognition dalam C++."
type: docs
weight: 200
url: /id/cpp/aspose.barcode.barcoderecognition/
---



## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](./australiapostcustomerinformationdecoder/) | Antarmuka publik untuk dekoding Customer Information Field yang digunakan dalam simbol AustraliaPost. Implementasi harus disediakan oleh pengguna. |
| [AustraliaPostSettings](./australiapostsettings/) | Parameter dekoding AustraliaPost. Berisi parameter yang memengaruhi data yang dikenali pada simbol AustraliaPost. |
| [AztecExtendedParameters](./aztecextendedparameters/) | Menyimpan data khusus dari kode batang Aztec yang dikenali |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Menyimpan parameter tambahan dari kode batang yang dikenali |
| [BarCodeReader](./barcodereader/) | [BarCodeReader](./barcodereader/) membungkus sebuah gambar yang mungkin berisi satu atau beberapa kode batang, kemudian dapat melakukan operasi ReadBarCodes untuk mendeteksi kode batang. |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Mewakili wilayah kode batang yang dikenali dan sudut kode batang |
| [BarCodeResult](./barcoderesult/) | Menyimpan data kode batang yang dikenali seperti tipe [SingleDecodeType](./singledecodetype/), teks kode **System::String**, wilayah [BarCodeRegionParameters](./barcoderegionparameters/) dan parameter lainnya |
| [BarcodeSettings](./barcodesettings/) | Parameter dekoding utama [BarCode](../aspose.barcode/). Berisi parameter yang memengaruhi data yang dikenali. |
| [BaseDecodeType](./basedecodetype/) | Kelas dasar untuk [MultiDecodeType](./multidecodetype/) dan [SingleDecodeType](./singledecodetype/). |
| [BaseExtendedParameters](./baseextendedparameters/) | Kelas dasar untuk penyimpanan parameter tambahan dari kode batang yang dikenali |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Menyimpan informasi tambahan Codabar dari kode batang yang dikenali |
| [Code128DataPortion](./code128dataportion/) | Berisi data subtipe untuk kode batang tipe Code128 |
| [Code128ExtendedParameters](./code128extendedparameters/) | Menyimpan data khusus dari kode batang Code128 yang dikenali |
| [DataBarExtendedParameters](./databarextendedparameters/) | Menyimpan informasi tambahan DataBar dari kode batang yang dikenali |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Menyimpan data khusus dari kode batang [DataMatrix](../aspose.barcode.barcoderecognition.datamatrix/) yang dikenali |
| [DecodeType](./decodetype/) | Tentukan tipe kode batang yang akan dibaca. |
| [Details_BarCodeRecognitionException](./details_barcoderecognitionexception/) | Pengecualian umum yang dilempar oleh [BarCodeReader](./barcodereader/), diturunkan dari BarCodeException |
| [Details_RecognitionAbortedException](./details_recognitionabortedexception/) | Mewakili pengecualian penghentian pengenalan yang dilempar ketika batas waktu terlampaui selama pengenalan dengan [BarCodeReader](./barcodereader/). |
| [Details_RecognitionEngineException](./details_recognitionengineexception/) |  |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Menyimpan data khusus dari kode batang DotCode yang dikenali |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Menyimpan data khusus dari kode batang **GS1 Composite Bar** yang dikenali |
| [Iso15416Quality](./iso15416quality/) | Menyimpan nilai kualitas kode batang yang dihitung sesuai standar ISO/IEC 15416 untuk kode batang 1D. |
| [IsoSymbolQuality](./isosymbolquality/) | Menyimpan hasil evaluasi kualitas simbol kode batang sesuai standar ISO/IEC. |
| [LuminanceFrame](./luminanceframe/) | Mewakili bingkai gambar grayscale 8-bit. Setiap piksel direpresentasikan oleh satu byte yang berisi nilai luminansinya. |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Menyimpan informasi tambahan MaxiCode dari kode batang yang dikenali |
| [MultiDecodeType](./multidecodetype/) | Tipe decode komposit. |
| [OneDExtendedParameters](./onedextendedparameters/) | Menyimpan data khusus dari kode batang 1D yang dikenali seperti teks kode terpisah dan checksum |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Menyimpan informasi metadata MacroPdf417 dari kode batang yang dikenali |
| [QRExtendedParameters](./qrextendedparameters/) | Menyimpan informasi Structured Append [QR](../aspose.barcode.barcoderecognition.qr/) dari kode batang yang dikenali |
| [Quadrangle](./quadrangle/) | Menyimpan sekumpulan empat [Point](../) yang mewakili wilayah [Quadrangle](./quadrangle/). |
| [QualitySettings](./qualitysettings/) | [QualitySettings](./qualitysettings/) memungkinkan mengkonfigurasi kualitas dan kecepatan pengenalan secara manual. Anda dapat dengan cepat mengatur [QualitySettings](./qualitysettings/) dengan preset tersemat: HighPerformance, NormalQuality, HighQuality, MaxQuality atau Anda dapat mengkonfigurasi opsi terpisah secara manual. Nilai default dari [QualitySettings](./qualitysettings/) adalah NormalQuality. |
| [SingleDecodeType](./singledecodetype/) | Tipe decode tunggal. Lihat tipe decode untuk mendapatkan instance. |
## Enums

| Enum | Deskripsi |
| --- | --- |
| [ChecksumValidation](./checksumvalidation/) |  |
| [Code128SubType](./code128subtype/) | Berisi tipe-tipe subset Code128 |
| [BarCodeConfidence](./barcodeconfidence/) | Berisi tingkat kepercayaan pengenalan |
| [BarcodeQualityMode](./barcodequalitymode/) |  |
| [ComplexBackgroundMode](./complexbackgroundmode/) |  |
| [DeconvolutionMode](./deconvolutionmode/) |  |
| [InverseImageMode](./inverseimagemode/) |  |
| [XDimensionMode](./xdimensionmode/) |  |
## Typedefs

| Typedef | Deskripsi |
| --- | --- |
| [BarCodeRecognitionException](./barcoderecognitionexception/) |  |
| [RecognitionEngineException](./recognitionengineexception/) |  |
| [RecognitionAbortedException](./recognitionabortedexception/) |  |
