---
title: "Enum GS1ValidationErrorCode"
second_title: "Aspose.BarCode untuk .NET API Referensi"
description: "Aspose.BarCode.Common.GS1ValidationErrorCode enum. Mengidentifikasi kesalahan validasi string elemen GS1 Digital Link URI atau nilai"
type: docs
weight: 430
url: /id/net/aspose.barcode.common/gs1validationerrorcode/
---
## GS1ValidationErrorCode enumeration

Mengidentifikasi kesalahan validasi string elemen GS1, Digital Link URI, atau nilai.

```csharp
public enum GS1ValidationErrorCode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| EmptyElementString | `0` | String elemen GS1 yang diberikan kosong. |
| MissingOpeningParenthesis | `1` | Kurung buka yang seharusnya memulai Application Identifier tidak ada. |
| MissingClosingParenthesis | `2` | Application Identifier tidak memiliki kurung tutup. |
| InvalidApplicationIdentifier | `3` | Application Identifier tidak berisi dua hingga empat digit ASCII. |
| UnknownApplicationIdentifier | `4` | Application Identifier yang diberikan tidak didefinisikan oleh GS1 Syntax Dictionary yang didukung. |
| MissingValue | `5` | Application Identifier hadir tanpa nilai. |
| InvalidEscapeSequence | `6` | Nilai mengandung urutan escape yang tidak didukung. Hanya \( yang didukung. |
| ValueTooShort | `7` | Nilai lebih pendek daripada panjang minimum yang ditetapkan untuk Application Identifier-nya. |
| ValueTooLong | `8` | Nilai lebih panjang daripada panjang maksimum yang ditetapkan untuk Application Identifier-nya. |
| InvalidCharacter | `9` | Nilai mengandung karakter di luar set karakter yang diizinkan untuk komponennya. |
| InvalidChecksum | `10` | Checksum numerik atau alfabetik tidak valid. |
| InvalidDate | `11` | Komponen tanggal bukan tanggal yang bermakna menurut aturan yang ditetapkan untuk Application Identifier-nya. |
| InvalidTime | `12` | Komponen waktu berada di luar rentang yang diizinkan atau memiliki struktur yang tidak valid. |
| InvalidCodeListValue | `13` | Nilai komponen tidak ada dalam daftar kode tertutup yang diizinkan. |
| InvalidComponentLength | `14` | Komponen tidak memenuhi struktur panjang khusus komponen. |
| TruncatedComponent | `15` | Komponen dengan panjang tetap berakhir sebelum semua karakter yang diperlukan hadir. |
| UnexpectedData | `16` | Data tetap ada setelah semua komponen yang didefinisikan untuk Application Identifier telah dikonsumsi. |
| InvalidValue | `17` | Sebuah komponen melanggar aturan konten yang tidak memiliki kode kesalahan validasi yang lebih spesifik. |
| GcpPrefixTooShort | `18` | Sebuah komponen terlalu pendek untuk memuat GS1 Company Prefix struktural minimal empat digit. |
| InvalidGcpPrefix | `19` | GS1 Company Prefix struktural berisi karakter selain digit ASCII. |
| InvalidDigitalLinkUri | `20` | Nilai yang diberikan tidak berupa URI GS1 Digital Link absolut yang terbentuk dengan baik. |
| UnsupportedDigitalLinkScheme | `21` | URI GS1 Digital Link menggunakan skema selain HTTP atau HTTPS. |
| MissingDigitalLinkPrimaryKey | `22` | Path URI GS1 Digital Link tidak berisi kunci utama yang didukung. |
| InvalidDigitalLinkPath | `23` | Path URI GS1 Digital Link tidak terdiri dari pasangan AI dan nilai yang valid. |
| InvalidDigitalLinkQualifier | `24` | Application Identifier pada path tidak diizinkan sebagai kualifier pada posisi tersebut. |
| InvalidDigitalLinkQueryParameter | `25` | Parameter kueri GS1 Digital Link tidak terbentuk dengan benar. |
| ApplicationIdentifierNotAllowedInDigitalLink | `26` | Application Identifier tidak diizinkan sebagai atribut data GS1 Digital Link. |
| InvalidPercentEncoding | `27` | Komponen URI GS1 Digital Link berisi pengkodean persentase yang tidak terbentuk dengan benar. |
| MultipleDigitalLinkPrimaryKeys | `28` | Lebih dari satu elemen dapat dipilih sebagai kunci utama GS1 Digital Link. |
| UnsupportedElementCombination | `29` | Kombinasi GS1 elemen yang diberikan tidak didukung oleh simbol atau mode enkoding yang dipilih. |

### Lihat Juga

* namespace [Aspose.BarCode.Common](../../aspose.barcode.common/)
* assembly [Aspose.BarCode](../../)


