---
title: "com.aspose.barcode.barcoderecognition"
second_title: "Referensi API Aspose.BarCode untuk Java"
description: "Paket ini berisi alat untuk pengenalan barcode 1D/2D."
type: docs
weight: 12
url: /id/java/com.aspose.barcode.barcoderecognition/
---

Paket ini berisi alat untuk pengenalan barcode 1D/2D.


## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [AustraliaPostSettings](../com.aspose.barcode.barcoderecognition/australiapostsettings) | Parameter dekoding AustraliaPost. |
| [AustraliaPostSettingsInternal](../com.aspose.barcode.barcoderecognition/australiapostsettingsinternal) |  |
| [AztecExtendedParameters](../com.aspose.barcode.barcoderecognition/aztecextendedparameters) | Menyimpan data khusus dari barcode Aztec yang dikenali |
| [BarCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/barcodeextendedparameters) | Menyimpan parameter tambahan dari barcode yang dikenali |
| [BarCodeReader](../com.aspose.barcode.barcoderecognition/barcodereader) | BarCodeReader membungkus sebuah gambar yang mungkin berisi satu atau beberapa barcode, kemudian dapat melakukan operasi ReadBarCodes untuk mendeteksi barcode. |
| [BarCodeRecognitionException](../com.aspose.barcode.barcoderecognition/barcoderecognitionexception) | Pengecualian umum yang dilemparkan oleh BarCodeReader, diturunkan dari BarCodeException |
| [BarCodeRegionParameters](../com.aspose.barcode.barcoderecognition/barcoderegionparameters) | Mewakili wilayah barcode yang dikenali dan sudut barcode |
| [BarCodeResult](../com.aspose.barcode.barcoderecognition/barcoderesult) | Menyimpan data barcode yang dikenali seperti tipe SingleDecodeType, string codetext, BarCodeRegionParameters region, dan parameter lainnya |
| [BarCodeResultInternalCalls](../com.aspose.barcode.barcoderecognition/barcoderesultinternalcalls) |  |
| [BarcodeSettings](../com.aspose.barcode.barcoderecognition/barcodesettings) | Parameter dekoding BarCode utama. |
| [BarcodeSettingsInternal](../com.aspose.barcode.barcoderecognition/barcodesettingsinternal) |  |
| [BarcodeSvmDetectorSettings](../com.aspose.barcode.barcoderecognition/barcodesvmdetectorsettings) | Pengaturan detektor barcode. |
| [BaseDecodeType](../com.aspose.barcode.barcoderecognition/basedecodetype) | Kelas dasar untuk MultiDecodeType dan SingleDecodeType. |
| [BaseExtendedParameters](../com.aspose.barcode.barcoderecognition/baseextendedparameters) | Kelas dasar untuk penyimpanan parameter tambahan dari barcode yang dikenali |
| [CodabarExtendedParameters](../com.aspose.barcode.barcoderecognition/codabarextendedparameters) | Menyimpan informasi tambahan Codabar dari barcode yang dikenali |
| [Code128DataPortion](../com.aspose.barcode.barcoderecognition/code128dataportion) | Berisi data subtipe untuk barcode tipe Code128 |
| [Code128DataPortionInternal](../com.aspose.barcode.barcoderecognition/code128dataportioninternal) |  |
| [Code128ExtendedParameters](../com.aspose.barcode.barcoderecognition/code128extendedparameters) | Menyimpan data khusus dari barcode Code128 yang dikenali |
| [DataBarExtendedParameters](../com.aspose.barcode.barcoderecognition/databarextendedparameters) | Menyimpan informasi tambahan DataBar dari barcode yang dikenali BarCodeReader reader = new BarCodeReader("c:\\\\test.png", DecodeType.DATABAR\_OMNI\_DIRECTIONAL); for(BarCodeResult result : reader.readBarCodes()) System.out.println("BarCode Type: " + result.getCodeTypeName()); System.out.println("BarCode CodeText: " + result.getCodeText()); System.out.println("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity()); |
| [DataMatrixExtendedParameters](../com.aspose.barcode.barcoderecognition/datamatrixextendedparameters) | Menyimpan data khusus dari barcode DataMatrix yang dikenali |
| [DecodeType](../com.aspose.barcode.barcoderecognition/decodetype) | Tentukan tipe barcode yang akan dibaca. |
| [DotCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/dotcodeextendedparameters) | Menyimpan data khusus dari barcode DotCode yang dikenali |
| [GS1CompositeBarExtendedParameters](../com.aspose.barcode.barcoderecognition/gs1compositebarextendedparameters) | Menyimpan data khusus dari **GS1 Composite Bar** yang dikenali |
| [MaxiCodeExtendedParameters](../com.aspose.barcode.barcoderecognition/maxicodeextendedparameters) | Menyimpan informasi tambahan MaxiCode dari barcode yang dikenali |
| [MultiDecodeType](../com.aspose.barcode.barcoderecognition/multidecodetype) | Tipe decode komposit. |
| [OneDExtendedParameters](../com.aspose.barcode.barcoderecognition/onedextendedparameters) | Menyimpan data khusus dari barcode 1D yang dikenali seperti codetext terpisah dan checksum |
| [Pdf417ExtendedParameters](../com.aspose.barcode.barcoderecognition/pdf417extendedparameters) | Menyimpan informasi metadata MacroPdf417 dari barcode yang dikenali |
| [ProcessorSettings](../com.aspose.barcode.barcoderecognition/processorsettings) | ProcessorSettings memungkinkan pengenalan barcode dengan peningkatan kinerja multi-threaded |
| [QRExtendedParameters](../com.aspose.barcode.barcoderecognition/qrextendedparameters) | Menyimpan informasi QR Structured Append dari barcode yang dikenali |
| [Quadrangle](../com.aspose.barcode.barcoderecognition/quadrangle) | Menyimpan sekumpulan empat Point yang mewakili wilayah Quadrangle. |
| [QualitySettings](../com.aspose.barcode.barcoderecognition/qualitysettings) | QualitySettings memungkinkan konfigurasi kualitas dan kecepatan pengenalan secara manual. |
| [QualitySettingsInternal](../com.aspose.barcode.barcoderecognition/qualitysettingsinternal) |  |
| [RecognitionAbortedException](../com.aspose.barcode.barcoderecognition/recognitionabortedexception) | Mewakili exception penghentian pengenalan yang dilempar ketika batas waktu terlampaui selama pengenalan dengan BarCodeReader. |
| [RecognitionOptions](../com.aspose.barcode.barcoderecognition/recognitionoptions) |  |
| [SingleDecodeType](../com.aspose.barcode.barcoderecognition/singledecodetype) | Tipe decode tunggal. |

## Antarmuka

| Antarmuka | Deskripsi |
| --- | --- |
| [AustraliaPostCustomerInformationDecoder](../com.aspose.barcode.barcoderecognition/australiapostcustomerinformationdecoder) | Antarmuka publik untuk decoding Customer Information Field yang digunakan dalam simbol AustraliaPost. |

## Enumerasi

| Enum | Deskripsi |
| --- | --- |
| [BarCodeConfidence](../com.aspose.barcode.barcoderecognition/barcodeconfidence) | Berisi tingkat kepercayaan pengenalan |
| [BarcodeQualityMode](../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |
| [ChecksumValidation](../com.aspose.barcode.barcoderecognition/checksumvalidation) |  |
| [Code128SubType](../com.aspose.barcode.barcoderecognition/code128subtype) | Berisi tipe-tipe subset Code128. |
| [ComplexBackgroundMode](../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |
| [CustomerInformationInterpretingType](../com.aspose.barcode.barcoderecognition/customerinformationinterpretingtype) | Mendefinisikan tipe interpretasi (C\_TABLE atau N\_TABLE) dari informasi pelanggan untuk BarCode AustralianPost. |
| [DeconvolutionMode](../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |
| [InverseImageMode](../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |
| [XDimensionMode](../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |
