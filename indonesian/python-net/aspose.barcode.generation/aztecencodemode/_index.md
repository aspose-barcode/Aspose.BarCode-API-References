---
title: "AztecEncodeMode"
second_title: "Referensi API Aspose.Sildes untuk Python via .NET"
description: 
type: docs
url: /id/python-net/aspose.barcode.generation/aztecencodemode/
---

## AztecEncodeMode enumeration

Mode enkode untuk kode batang Aztec.

## Members
| Nama anggota | Deskripsi |
| :- | :- |
| AUTO | Dalam mode Auto, CodeText dienkode dengan kepadatan data maksimum. <br/>            Karakter Unicode dikodekan ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI.<br/>            Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian dilempar. |
| EXTENDED |  |
| BINARY | Dalam mode Binary, CodeText dienkode dengan kepadatan data maksimum. <br/>            Jika ditemukan karakter Unicode, sebuah pengecualian dilempar. |
| ECI | Dalam mode ECI, seluruh pesan dikodekan ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI.<br/>            Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian dilempar.<br/>            Harap dicatat bahwa beberapa pemindai lama (sebelum 2006) mungkin tidak mendukung mode ini. |

### Lihat Juga

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

