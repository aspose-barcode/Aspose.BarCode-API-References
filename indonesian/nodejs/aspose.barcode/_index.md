---
title: "aspose.barcode"
linktitle: "aspose.barcode"
second_title: "Referensi API Aspose.BarCode untuk Node.js via Java"
description: "Namespace aspose.barcode menyediakan kelas dan enum untuk membuat, menyesuaikan, dan mendekode berbagai jenis barcode di Node.js via Java."
type: docs
weight: 10
url: /id/nodejs/aspose.barcode/
---
Gunakan tipe ini untuk mengonfigurasi pengaturan pembuatan barcode seperti format alamat, spesifikasi regional, dan parameter lanjutan untuk Aztec dan simbol lainnya. Namespace ini mencakup pembantu untuk membangun teks kode yang diperluas dan menangani standar pos khusus.

## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [Address](./address/) | Alamat kreditur atau debitur. Anda dapat mengatur jalan, nomor rumah, kode pos, dan kota (tipe alamat terstruktur) o |
| [AlternativeScheme](./alternativescheme/) | Instruksi skema pembayaran alternatif |
| [AustraliaPostSettings](./australiapostsettings/) | Parameter dekode AustraliaPost. Berisi parameter yang memengaruhi data yang dikenali dari simbol AustraliaPost |
| [AustralianPostParameters](./australianpostparameters/) | Parameter barcode AustralianPost. |
| [AztecExtCodetextBuilder](./aztecextcodetextbuilder/) | Generator kode teks diperluas untuk barcode Aztec dalam Mode ExtendedCodetext dari AztecEncodeMode. Gunakan properti TwoDDisplayText |
| [AztecExtendedParameters](./aztecextendedparameters/) | Menyimpan data khusus dari barcode Aztec yang dikenali. Contoh ini menunjukkan cara mendapatkan nilai mentah Aztec dengan let generator = new Barcod |
| [AztecParameters](./aztecparameters/) | Parameter Aztec. |
| [BarCodeExtendedParameters](./barcodeextendedparameters/) | Menyimpan parameter tambahan dari barcode yang dikenali |
| [BarCodeReader](./barcodereader/) | BarCodeReader membungkus sebuah gambar yang mungkin berisi satu atau beberapa barcode, kemudian dapat melakukan operasi ReadBarCodes |
| [BarCodeRegionParameters](./barcoderegionparameters/) | Mewakili wilayah barcode yang dikenali dan sudut barcode |
| [BarCodeResult](./barcoderesult/) | Menyimpan data barcode yang dikenali seperti tipe SingleDecodeType, `string` codetext, wilayah BarCodeRegionParameters, dan lainnya p |
| [BarcodeException](./barcodeexception/) |  |
| [BarcodeGenerator](./barcodegenerator/) | BarcodeGenerator untuk pembuatan gambar barcode backend. simbol yang didukung: 1D: Codabar, Code11, Code128, Code39Stand |
| [BarcodeParameters](./barcodeparameters/) | Parameter generasi Barcode. |
| [BarcodeSettings](./barcodesettings/) | Parameter decoding BarCode utama. Berisi parameter yang memengaruhi data yang dikenali. |
| [BaseGenerationParameters](./basegenerationparameters/) | Parameter generasi gambar Barcode. |
| [BorderParameters](./borderparameters/) | Parameter batas gambar Barcode |
| [CMYKColor](./cmykcolor/) | Kelas untuk warna CMYK. Instance null berarti CMYK tidak digunakan, dan warna RGB default sedang digunakan. |
| [CaptionParameters](./captionparameters/) | Parameter keterangan. |
| [CodabarExtendedParameters](./codabarextendedparameters/) | Menyimpan informasi tambahan Codabar dari barcode yang dikenali |
| [CodabarParameters](./codabarparameters/) | Parameter Codabar. |
| [CodablockParameters](./codablockparameters/) | Parameter Codablock. |
| [Code128DataPortion](./code128dataportion/) | Berisi data subtipe untuk barcode tipe Code128 |
| [Code128ExtendedParameters](./code128extendedparameters/) | Menyimpan data khusus dari barcode Code128 yang dikenali Mewakili wilayah barcode yang dikenali dan sudut barcode |
| [Code128Parameters](./code128parameters/) | Parameter Code128. |
| [Code16KParameters](./code16kparameters/) | Parameter Code16K. |
| [CodetextParameters](./codetextparameters/) | Parameter Codetext. |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/) | ComplexBarcodeGenerator untuk generasi gambar barcode kompleks backend (mis. SwissQR). |
| [ComplexCodetextReader](./complexcodetextreader/) | ComplexCodetextReader mendekode codetext ke tipe barcode kompleks yang ditentukan. |
| [CouponParameters](./couponparameters/) | Parameter kupon. Digunakan untuk UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon. |
| [DataBarExtendedParameters](./databarextendedparameters/) | Menyimpan informasi tambahan DataBar dari barcode yang dikenali |
| [DataBarParameters](./databarparameters/) | Parameter Databar. |
| [DataElement](./dataelement/) | Mewakili bidang data spesifik yurisdiksi yang digunakan dalam dokumen, misalnya ElementID = "ZVA" dengan Value = "01". |
| [DataMatrixExtCodetextBuilder](./datamatrixextcodetextbuilder/) | Generator codetext diperluas untuk barcode DataMatrix 2D untuk Mode ExtendedCodetext dari DataMatrixEncodeMode //Extended code |
| [DataMatrixExtendedParameters](./datamatrixextendedparameters/) | Menyimpan data khusus dari barcode DataMatrix yang dikenali Contoh ini menunjukkan cara mendapatkan nilai mentah DataMatrix, biarkan generator = |
| [DataMatrixParameters](./datamatrixparameters/) | Parameter DataMatrix. |
| [DotCodeExtCodetextBuilder](./dotcodeextcodetextbuilder/) | Generator codetext diperluas untuk barcode DotCode 2D untuk Mode ExtendedCodetext dari DotCodeEncodeMode |
| [DotCodeExtendedParameters](./dotcodeextendedparameters/) | Menyimpan data khusus dari barcode DotCode yang dikenali Contoh ini menunjukkan cara mendapatkan nilai mentah DotCode |
| [DotCodeParameters](./dotcodeparameters/) | Parameter DotCode. |
| [ExtCodetextBuilder](./extcodetextbuilder/) | Kelas pembantu untuk pembuatan codetext otomatis pada Mode Codetext Terluas |
| [FontUnit](./fontunit/) | Mendefinisikan format khusus untuk teks, termasuk jenis huruf, ukuran, dan atribut gaya di mana ukuran berada dalam properti nilai Unit. |
| [GS1CompositeBarExtendedParameters](./gs1compositebarextendedparameters/) | Menyimpan data khusus dari kode batang yang dikenali `GS1 Composite Bar ` |
| [GS1CompositeBarParameters](./gs1compositebarparameters/) | Parameter bar GS1 Composite. |
| [HIBCLICCombinedCodetext](./hibcliccombinedcodetext/) | Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC LIC yang menyimpan data utama dan sekunder. Contoh ini |
| [HIBCLICComplexCodetext](./hibcliccomplexcodetext/) | Kelas dasar untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC LIC. Contoh ini menunjukkan cara mendekode HIBC LI mentah |
| [HIBCLICPrimaryDataCodetext](./hibclicprimarydatacodetext/) | Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC LIC yang menyimpan data utama. Contoh ini menunjukkan cara |
| [HIBCLICSecondaryAndAdditionalDataCodetext](./hibclicsecondaryandadditionaldatacodetext/) | Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC LIC yang menyimpan data sekunder. |
| [HIBCPASCodetext](./hibcpascodetext/) | Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode HIBC PAS. |
| [HIBCPASRecord](./hibcpasrecord/) | Kelas untuk menyimpan catatan HIBC PAS. |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/) | Generator codetext terluas untuk Kode Han Xin pada Mode Terluas HanXinEncodeMode //mode codetext terluas //buat kode |
| [HanXinParameters](./hanxinparameters/) | Parameter Han Xin. |
| [HslaColor](./hslacolor/) | Kelas untuk merepresentasikan warna HSLA (Hue, Saturation, Lightness, Alpha) |
| [IComplexCodetext](./icomplexcodetext/) | Antarmuka untuk codetext kompleks yang digunakan dengan ComplexBarcodeGenerator. |
| [ITFParameters](./itfparameters/) | Parameter ITF. |
| [ImageParameters](./imageparameters/) | Parameter gambar. |
| [License](./license/) | Menyediakan metode untuk melisensikan komponen. |
| [Mailmark2DCodetext](./mailmark2dcodetext/) | Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode Royal Mail 2D Mailmark. |
| [MailmarkCodetext](./mailmarkcodetext/) | Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode Royal Mailmark 4-status. |
| [MandatoryFields](./mandatoryfields/) | Elemen (field) wajib dari kartu |
| [MaxiCodeCodetext](./maxicodecodetext/) | Kelas dasar untuk mengkodekan dan mendekode teks yang tertanam dalam kode MaxiCode. Contoh ini menunjukkan cara mendekode MaxiCod mentah |
| [MaxiCodeCodetextMode2](./maxicodecodetextmode2/) | Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode MaxiCode untuk mode 2. |
| [MaxiCodeCodetextMode3](./maxicodecodetextmode3/) | Kelas untuk mengkodekan dan mendekode teks yang tertanam dalam kode MaxiCode untuk mode 3. Contoh ini menunjukkan cara mengkodekan dan |
| [MaxiCodeExtCodetextBuilder](./maxicodeextcodetextbuilder/) | Generator codetext terluas untuk kode batang MaxiCode pada Mode ExtendedCodetext dari MaxiCodeEncodeMode Gunakan TwoDDisplayText pr |
| [MaxiCodeExtendedParameters](./maxicodeextendedparameters/) | Menyimpan informasi tambahan MaxiCode dari barcode yang dikenali |
| [MaxiCodeParameters](./maxicodeparameters/) | Parameter MaxiCode. |
| [MaxiCodeSecondMessage](./maxicodesecondmessage/) | Kelas untuk mengenkode dan mendekode teks kode MaxiCode untuk mode 4, 5, dan 6. |
| [MaxiCodeStandardCodetext](./maxicodestandardcodetext/) | Kelas untuk mengenkode dan mendekode teks kode MaxiCode untuk mode 4, 5, dan 6. |
| [MaxiCodeStandardSecondMessage](./maxicodestandardsecondmessage/) | Kelas untuk mengenkode dan mendekode pesan kedua standar untuk barcode MaxiCode. |
| [MaxiCodeStandartSecondMessage](./maxicodestandartsecondmessage/) | Kelas untuk mengenkode dan mendekode pesan kedua standar untuk barcode MaxiCode. |
| [MaxiCodeStructuredCodetext](./maxicodestructuredcodetext/) | Kelas dasar untuk mengenkode dan mendekode teks yang tertanam dalam kode MaxiCode untuk mode 2 dan 3. |
| [MaxiCodeStructuredSecondMessage](./maxicodestructuredsecondmessage/) | Kelas untuk mengenkode dan mendekode pesan kedua terstruktur untuk barcode MaxiCode. |
| [OneDExtendedParameters](./onedextendedparameters/) | Menyimpan data khusus dari barcode 1D yang dikenali seperti teks kode terpisah dan checksum. |
| [OptionalFields](./optionalfields/) | Elemen opsional (field) dari kartu. |
| [Padding](./padding/) | Parameter padding. |
| [PatchCodeParameters](./patchcodeparameters/) | Parameter PatchCode. |
| [Pdf417ExtendedParameters](./pdf417extendedparameters/) | Menyimpan informasi metadata MacroPdf417 dari barcode yang dikenali. |
| [Pdf417Parameters](./pdf417parameters/) | Parameter PDF417. Berisi parameter PDF417, MacroPDF417, MicroPDF417, dan GS1MicroPdf417. MacroPDF417 membutuhkan dua file |
| [PdfParameters](./pdfparameters/) | Pembungkus parameter PDF. Mengharapkan instance `mwObject` yang mendasari yang menyediakan metode getter/setter yang sesuai. |
| [PostalParameters](./postalparameters/) | Parameter pos. Digunakan untuk Postnet, Planet. |
| [PrimaryData](./primarydata/) | Kelas untuk menyimpan data utama HIBC LIC. |
| [QRExtendedParameters](./qrextendedparameters/) | Menyimpan informasi QR Structured Append dari barcode yang dikenali. |
| [QrExtCodetextBuilder](./qrextcodetextbuilder/) | Generator teks kode ekstended untuk barcode QR 2D untuk Mode ExtendedCodetext dari QREncodeMode. Gunakan properti Display2DText dari B |
| [QrParameters](./qrparameters/) | Parameter QR. |
| [QrStructuredAppendParameters](./qrstructuredappendparameters/) | Parameter QR structured append. |
| [Quadrangle](./quadrangle/) | Menyimpan sekumpulan empat Point yang mewakili wilayah Quadrangle. |
| [QualitySettings](./qualitysettings/) | QualitySettings memungkinkan mengkonfigurasi kualitas dan kecepatan pengenalan secara manual. Anda dapat dengan cepat mengatur QualitySettings dengan em |
| [RecognitionAbortedException](./recognitionabortedexception/) | Mewakili pengecualian penghentian pengenalan yang dilempar ketika batas waktu terlampaui selama pengenalan dengan BarCodeReader. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/) | Kelas untuk menyimpan data sekunder dan tambahan HIBC LIC. |
| [SubfileProperties](./subfileproperties/) | Properti subfile USA DL, offset, dan panjang diatur secara otomatis. |
| [SupplementParameters](./supplementparameters/) | Parameter supplement. Digunakan untuk Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN. |
| [SvgParameters](./svgparameters/) | Parameter SVG. |
| [SwissQRBill](./swissqrbill/) | Data tagihan SwissQR |
| [SwissQRCodetext](./swissqrcodetext/) | Kelas untuk mengenkode dan mendekode teks yang tertanam dalam kode SwissQR. |
| [USADriveIdCodetext](./usadriveidcodetext/) | Kelas untuk mengenkode dan mendekode teks yang tertanam dalam kode PDF417 Surat Izin Mengemudi USA. |
| [USADriveIdJurisdSubfile](./usadriveidjurisdsubfile/) | Kelas untuk bidang spesifik yurisdiksi untuk Surat Izin Mengemudi USA. |
| [Unit](./unit/) | Menentukan nilai ukuran dalam berbagai satuan (Pixel, Inci, dll). |
