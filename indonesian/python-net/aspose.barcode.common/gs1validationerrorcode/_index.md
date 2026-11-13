---
title: "GS1ValidationErrorCode"
second_title: "Referensi API Aspose.Sildes untuk Python via .NET"
description: 
type: docs
url: /id/python-net/aspose.barcode.common/gs1validationerrorcode/
---

## GS1ValidationErrorCode enumeration

Mengidentifikasi kesalahan validasi string elemen GS1, URI Digital Link, atau nilai.

## Members
| Nama anggota | Deskripsi |
| :- | :- |
| EMPTY_ELEMENT_STRING | String elemen GS1 yang diberikan kosong. |
| MISSING_OPENING_PARENTHESIS | Kurung buka yang seharusnya memulai Application Identifier tidak ada. |
| MISSING_CLOSING_PARENTHESIS | Application Identifier tidak memiliki kurung tutup. |
| INVALID_APPLICATION_IDENTIFIER | Application Identifier tidak berisi dua hingga empat digit ASCII. |
| UNKNOWN_APPLICATION_IDENTIFIER | Application Identifier yang diberikan tidak didefinisikan oleh GS1 Syntax Dictionary yang didukung. |
| MISSING_VALUE | Application Identifier hadir tanpa nilai. |
| INVALID_ESCAPE_SEQUENCE | Nilai mengandung urutan escape yang tidak didukung. Hanya \( yang didukung. |
| VALUE_TOO_SHORT | Nilai lebih pendek dari panjang minimum yang ditentukan untuk Application Identifier-nya. |
| VALUE_TOO_LONG | Nilai lebih panjang dari panjang maksimum yang ditentukan untuk Application Identifier-nya. |
| INVALID_CHARACTER | Nilai mengandung karakter di luar set karakter yang diizinkan untuk komponennya. |
| INVALID_CHECKSUM | Checksum numerik atau alfabetik tidak valid. |
| INVALID_DATE | Komponen tanggal bukan tanggal yang bermakna menurut aturan yang ditetapkan untuk Application Identifier-nya. |
| INVALID_TIME | Komponen waktu berada di luar rentang yang diizinkan atau memiliki struktur yang tidak valid. |
| INVALID_CODE_LIST_VALUE | Nilai komponen tidak ada dalam daftar kode tertutup yang diizinkan. |
| INVALID_COMPONENT_LENGTH | Komponen tidak memenuhi struktur panjang khusus komponen tersebut. |
| TRUNCATED_COMPONENT | Komponen dengan panjang tetap berakhir sebelum semua karakter yang diperlukan hadir. |
| UNEXPECTED_DATA | Data tetap ada setelah semua komponen yang didefinisikan untuk Application Identifier telah dikonsumsi. |
| INVALID_VALUE | Komponen melanggar aturan konten yang tidak memiliki kode kesalahan validasi yang lebih spesifik. |
| GCP_PREFIX_TOO_SHORT | Komponen terlalu pendek untuk memuat GS1 Company Prefix struktural minimal empat digit. |
| INVALID_GCP_PREFIX | GS1 Company Prefix struktural mengandung karakter selain digit ASCII. |
| INVALID_DIGITAL_LINK_URI | Nilai yang diberikan bukan URI GS1 Digital Link absolut yang terbentuk dengan baik. |
| UNSUPPORTED_DIGITAL_LINK_SCHEME | URI GS1 Digital Link menggunakan skema selain HTTP atau HTTPS. |
| MISSING_DIGITAL_LINK_PRIMARY_KEY | Path URI GS1 Digital Link tidak mengandung kunci utama yang didukung. |
| INVALID_DIGITAL_LINK_PATH | Path URI GS1 Digital Link tidak terdiri dari pasangan AI dan nilai yang valid. |
| INVALID_DIGITAL_LINK_QUALIFIER | Application Identifier jalur bukan qualifier yang diizinkan pada posisi tersebut. |
| INVALID_DIGITAL_LINK_QUERY_PARAMETER | Parameter kueri GS1 Digital Link tidak valid. |
| APPLICATION_IDENTIFIER_NOT_ALLOWED_IN_DIGITAL_LINK | Application Identifier tidak diizinkan sebagai atribut data GS1 Digital Link. |
| INVALID_PERCENT_ENCODING | Komponen URI GS1 Digital Link mengandung pengkodean persentase yang tidak valid. |
| MULTIPLE_DIGITAL_LINK_PRIMARY_KEYS | Lebih dari satu elemen dapat dipilih sebagai kunci utama GS1 Digital Link. |
| UNSUPPORTED_ELEMENT_COMBINATION | Kombinasi elemen GS1 yang diberikan tidak didukung oleh simbol atau mode pengkodean yang dipilih. |

### Lihat Juga

* namespace [aspose.barcode.common](/barcode/python-net/aspose.barcode.common/)
* assembly [Aspose.BarCode](/barcode/python-net/)

