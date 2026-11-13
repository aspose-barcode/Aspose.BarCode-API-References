---
title: "QREncodeMode"
second_title: "Referensi API Aspose.Sildes untuk Python via .NET"
description: 
type: docs
url: /id/python-net/aspose.barcode.generation/qrencodemode/
---

## QREncodeMode enumeration

Mode enkoding untuk barcode QR.

## Members
| Nama anggota | Deskripsi |
| :- | :- |
| AUTO | Dalam mode Auto, CodeText dienkode dengan kepadatan data maksimum. <br/>            Karakter Unicode dienkode dalam mode kanji jika memungkinkan, atau mereka dienkode ulang dengan encoding ECIEncoding yang ditentukan dengan penyisipan identifier ECI.<br/>            Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian dilempar. |
| EXTENDED |  |
| BINARY | Dalam mode Binary, CodeText dienkode dengan kepadatan data maksimum. <br/>            Jika ditemukan karakter Unicode, sebuah pengecualian dilempar. |
| ECI | Dalam mode ECI, seluruh pesan dienkode ulang dengan encoding ECIEncoding yang ditentukan dengan penyisipan identifier ECI.<br/>            Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian dilempar.<br/>            Harap perhatikan bahwa beberapa pemindai lama (sebelum 2006) mungkin tidak mendukung mode ini.<br/>            Mode ini tidak didukung oleh kode batang MicroQR. |

### Lihat Juga

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

