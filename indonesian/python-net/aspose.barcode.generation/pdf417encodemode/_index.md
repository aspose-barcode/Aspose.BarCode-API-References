---
title: "Pdf417EncodeMode"
second_title: "Referensi API Aspose.Sildes untuk Python via .NET"
description: 
type: docs
url: /id/python-net/aspose.barcode.generation/pdf417encodemode/
---

## Pdf417EncodeMode enumeration

Mode enkoding barcode Pdf417

## Members
| Nama anggota | Deskripsi |
| :- | :- |
| AUTO | Dalam mode Auto, CodeText dienkode dengan kepadatan data maksimum. <br/>            Karakter Unicode dikodekan ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI.<br/>            Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian dilempar. |
| BINARY | Dalam mode Binary, CodeText dienkode dengan kepadatan data maksimum. <br/>            Jika ditemukan karakter Unicode, sebuah pengecualian dilempar. |
| ECI | Dalam mode ECI, seluruh pesan dikodekan ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI.<br/>            Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian dilempar.<br/>            Harap dicatat bahwa beberapa pemindai lama (sebelum 2006) mungkin tidak mendukung mode ini. |
| EXTENDED |  |

### Lihat Juga

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

