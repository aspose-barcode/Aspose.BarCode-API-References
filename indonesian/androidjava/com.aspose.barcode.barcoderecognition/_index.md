---
title: com.aspose.barcode.barcoderecognition
second_title: Referensi API Aspose.BarCode untuk Android via Java
description: Paket ini berisi alat untuk pengenalan barcode 1D/2D.
type: docs
weight: 11
url: /id/androidjava/com.aspose.barcode.barcoderecognition/
---

Paket ini berisi alat untuk pengenalan barcode 1D/2D.


## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | Parameter dekode AustraliaPost. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Menyimpan data khusus dari kode batang Aztec yang dikenali |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Berisi tingkat kepercayaan pengenalan |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Menyimpan parameter tambahan dari kode batang yang dikenali |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader membungkus sebuah gambar yang mungkin berisi satu atau beberapa kode batang, kemudian dapat melakukan operasi ReadBarCodes untuk mendeteksi kode batang. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Pengecualian umum yang dilemparkan oleh BarCodeReader, diwarisi dari BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Mewakili wilayah kode batang yang dikenali dan sudut kode batang |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Menyimpan data kode batang yang dikenali seperti tipe SingleDecodeType, string codetext, BarCodeRegionParameters region, dan parameter lainnya |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | Parameter dekode BarCode utama. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Pengaturan detektor kode batang. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Kelas dasar untuk MultiDecodeType dan SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Kelas dasar untuk penyimpanan parameter tambahan dari kode batang yang dikenali |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Menyimpan informasi tambahan Codabar dari kode batang yang dikenali |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Berisi data subtipe untuk kode batang tipe Code128 |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Menyimpan data khusus dari kode batang Code128 yang dikenali |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Berisi tipe-tipe subset Code128 |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Menyimpan informasi tambahan DataBar dari kode batang yang dikenali BarCodeReader reader = new BarCodeReader("test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Menyimpan data khusus dari DataMatrix yang dikenali |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Tentukan jenis kode batang yang akan dibaca. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Menyimpan data khusus dari DotCode yang dikenali |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Menyimpan data khusus dari  **GS1 Composite Bar**  yang dikenali |
| [ImageScalingModeInternal](../com.aspose.barcode.barcoderecognition/imagescalingmodeinternal) |  |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Menyimpan informasi tambahan MaxiCode dari kode batang yang dikenali |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Tipe decode komposit. |
| [MultyDecodeType](../com.aspose.barcode.barcoderecognition/multydecodetype) | Tipe decode komposit. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Menyimpan data khusus dari kode batang 1D yang dikenali seperti teks kode terpisah dan checksum |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Menyimpan informasi metadata MacroPdf417 dari kode batang yang dikenali |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings memungkinkan mengenali kode batang dengan peningkatan kinerja multi‑thread |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Menyimpan informasi QR Structured Append dari kode batang yang dikenali |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Menyimpan sekumpulan empat  Point s yang mewakili wilayah  Quadrangle . |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings memungkinkan mengkonfigurasi kualitas dan kecepatan pengenalan secara manual. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Mewakili pengecualian penghentian pengenalan yang dilempar ketika batas waktu terlampaui selama pengenalan dengan BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Tipe decode tunggal. |
| [TextEncodingDetection](../com.aspose.barcode.barcoderecognition/textencodingdetection) |  |

## Antarmuka

| Antarmuka | Deskripsi |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Antarmuka publik untuk decoding Customer Information Field yang digunakan dalam simbol AustraliaPost. |

## Enumerasi

| Enum | Deskripsi |
| --- | --- |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Mendefinisikan tipe interpretasi (C\_TABLE atau N\_TABLE) dari informasi pelanggan untuk BarCode AustralianPost. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [ImageScalingMode](../com.aspose.barcode.barcoderecognition/imagescalingmode) | Tentukan ukuran gambar yang diubah skala |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
