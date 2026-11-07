---
title: "enum"
linktitle: "Enkoding ECI"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Cara menggunakan enum di C++."
type: docs
weight: 6600
url: /id/cpp/aspose.barcode.generation/eciencodings/
---
## ECIEncodings enum




```cpp
enum class ECIEncodings
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| ISO_8859_1 | 3 | ISO/IEC 8859-1 alfabet Latin No. 1 enkoding. ECI Id:"\000003" |
| ISO_8859_2 | 4 | ISO/IEC 8859-2 alfabet Latin No. 2 enkoding. ECI Id:"\000004" |
| ISO_8859_3 | 5 | ISO/IEC 8859-3 alfabet Latin No. 3 enkoding. ECI Id:"\000005" |
| ISO_8859_4 | 6 | ISO/IEC 8859-4 alfabet Latin No. 4 enkoding. ECI Id:"\000006" |
| ISO_8859_5 | 7 | ISO/IEC 8859-5 alfabet Latin/Cyrillic enkoding. ECI Id:"\000007" |
| ISO_8859_6 | 8 | ISO/IEC 8859-6 alfabet Latin/Arab enkoding. ECI Id:"\000008" |
| ISO_8859_7 | 9 | ISO/IEC 8859-7 alfabet Latin/Yunani enkoding. ECI Id:"\000009" |
| ISO_8859_8 | 10 | ISO/IEC 8859-8 alfabet Latin/Ibrani enkoding. ECI Id:"\000010" |
| ISO_8859_9 | 11 | ISO/IEC 8859-9 alfabet Latin No. 5 enkoding. ECI Id:"\000011" |
| ISO_8859_10 | 12 | ISO/IEC 8859-10 alfabet Latin No. 6 pengkodean. ECI Id:"\000012" |
| ISO_8859_11 | 13 | ISO/IEC 8859-11 alfabet Latin/Thai pengkodean. ECI Id:"\000013" |
| ISO_8859_13 | 15 | ISO/IEC 8859-13 alfabet Latin No. 7 (Baltic Rim) pengkodean. ECI Id:"\000015" |
| ISO_8859_14 | 16 | ISO/IEC 8859-14 alfabet Latin No. 8 (Celtic) pengkodean. ECI Id:"\000016" |
| ISO_8859_15 | 17 | ISO/IEC 8859-15 alfabet Latin No. 9 pengkodean. ECI Id:"\000017" |
| ISO_8859_16 | 18 | ISO/IEC 8859-16 alfabet Latin No. 10 pengkodean. ECI Id:"\000018" |
| Shift_JIS | 20 | Shift JIS (JIS X 0208 Annex 1 + JIS X 0201) pengkodean. ECI Id:"\000020" |
| Win1250 | 21 | [Windows](../../aspose.barcode.windows/) 1250 Latin 2 (Eropa Tengah) pengkodean. ECI Id:"\000021" |
| Win1251 | 22 | [Windows](../../aspose.barcode.windows/) 1251 Cyrillic pengkodean. ECI Id:"\000022" |
| Win1252 | 23 | [Windows](../../aspose.barcode.windows/) 1252 Latin 1 pengkodean. ECI Id:"\000023" |
| Win1256 | 24 | [Windows](../../aspose.barcode.windows/) 1256 Arab pengkodean. ECI Id:"\000024" |
| UTF16BE | 25 | ISO/IEC 10646 UCS-2 (byte urutan tinggi dulu) pengkodean. ECI Id:"\000025" |
| UTF8 | 26 | ISO/IEC 10646 UTF-8 pengkodean. ECI Id:"\000026" |
| US_ASCII | 27 | ISO/IEC 646:1991 Versi Referensi Internasional dari set karakter terkode 7-bit ISO pengkodean. ECI Id:"\000027" |
| Big5 | 28 | Big 5 (Taiwan) Pengkodean Set Karakter Cina. ECI Id:"\000028" |
| GB2312 | 29 | Pengkodean Set Karakter Cina GB2312. ECI Id:"\000029" |
| EUC_KR | 30 | Pengkodean Set Karakter Korea. ECI Id:"\000030" |
| GBK | 31 | Pengkodean GBK (ekstensi GB2312 untuk Cina Sederhana). ECI Id:"\000031" |
| GB18030 | 32 | Pengkodean Set Karakter Cina GGB18030. ECI Id:"\000032" |
| UTF16LE | 33 | Pengkodean ISO/IEC 10646 UTF-16LE. ECI Id:"\000033" |
| UTF32BE | 34 | Pengkodean ISO/IEC 10646 UTF-32BE. ECI Id:"\000034" |
| UTF32LE | 35 | Pengkodean ISO/IEC 10646 UTF-32LE. ECI Id:"\000035" |
| INVARIANT | 170 | ISO/IEC 646: set karakter terkode 7-bit ISO - Pengkodean set Karakter Invarian. ECI Id:"\000170" |
| BINARY | 899 | Data biner 8-bit. ECI Id:"\000899" |
| NONE | 0 | Tidak Ada Interpretasi Saluran Ekstensi |

## Catatan


Pengidentifikasi Interpretasi Saluran Ekstensi. Ini digunakan untuk memberi tahu pembaca kode batang detail tentang referensi yang digunakan untuk mengkodekan data dalam simbol.

Contoh ini menunjukkan cara menggunakan pengkodean ECI dan menyimpan gambar [BarCode](../../aspose.barcode/)
```cpp
[C#]
using (Aspose.BarCode.Generation.BarcodeGenerator generator = new Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR))
{
    generator.CodeText = "12345TEXT";
    generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ECIEncoding;
    generator.Parameters.Barcode.QR.ECIEncoding = ECIEncodings.UTF8;
    generator.Save("test.png");
}
    [VB.NET]
    Using generator As New Aspose.BarCode.Generation.BarcodeGenerator(EncodeTypes.QR)
        generator.CodeText = "12345TEXT"
        generator.Parameters.Barcode.QR.EncodeMode = QREncodeMode.ECIEncoding
        generator.Parameters.Barcode.QR.ECIEncoding = ECIEncodings.UTF8
        generator.Save("test.png")
    End Using
```

## Lihat Juga

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
