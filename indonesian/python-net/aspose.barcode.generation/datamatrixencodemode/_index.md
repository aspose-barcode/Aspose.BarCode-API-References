---
title: "DataMatrixEncodeMode"
second_title: "Referensi API Aspose.Sildes untuk Python via .NET"
description: 
type: docs
url: /id/python-net/aspose.barcode.generation/datamatrixencodemode/
---

## DataMatrixEncodeMode enumeration

Mode enkode encoder DataMatrix, default ke Auto

## Members
| Nama anggota | Deskripsi |
| :- | :- |
| AUTO | Dalam mode Auto, CodeText dienkode dengan kepadatan data maksimum. <br/>            Karakter Unicode dikodekan ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI.<br/>            Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian dilempar. |
| ASCII | Mengenkripsi satu karakter alfanumerik atau dua karakter numerik per byte |
| C40 | Menggunakan encoding C40. Mengenkripsi alfanumerik huruf besar, huruf kecil, dan karakter khusus |
| TEXT | Menggunakan encoding Text. Mengenkripsi alfanumerik huruf kecil, huruf besar, dan karakter khusus |
| EDIFACT | Menggunakan encoding EDIFACT. Menggunakan enam bit per karakter, mengenkripsi digit, huruf besar, dan banyak tanda baca, tetapi tidak mendukung huruf kecil. |
| ANSIX12 | Menggunakan encoding ANSI X12. |
| EXTENDED |  |
| BASE256 | Mengenkripsi nilai 8 bit |
| BINARY | Dalam mode Binary, CodeText dienkode dengan kepadatan data maksimum. <br/>            Jika ditemukan karakter Unicode, sebuah pengecualian dilempar. |
| ECI | Dalam mode ECI, seluruh pesan dikodekan ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI.<br/>            Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian dilempar.<br/>            Harap dicatat bahwa beberapa pemindai lama (sebelum 2006) mungkin tidak mendukung mode ini. |

### Lihat Juga

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

