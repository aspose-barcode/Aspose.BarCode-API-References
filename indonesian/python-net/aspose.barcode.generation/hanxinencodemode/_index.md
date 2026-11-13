---
title: "HanXinEncodeMode"
second_title: "Referensi API Aspose.Sildes untuk Python via .NET"
description: 
type: docs
url: /id/python-net/aspose.barcode.generation/hanxinencodemode/
---

## HanXinEncodeMode enumeration

Mode enkoding Han Xin Code. Disarankan menggunakan Auto dengan karakter ASCII / Cina atau Unicode untuk karakter Unicode.

## Members
| Nama anggota | Deskripsi |
| :- | :- |
| AUTO | Dalam mode Auto, CodeText dienkode dengan kepadatan data maksimum. <br/>            Karakter Unicode dienkode menggunakan enkoding GB18030 sesuai spesifikasi barcode HanXin. |
| BINARY | Dalam mode Binary, CodeText dienkode dengan kepadatan data maksimum. <br/>            Jika ditemukan karakter Unicode, sebuah pengecualian dilempar. |
| ECI | Dalam mode ECI, seluruh pesan dikodekan ulang dengan encoding yang ditentukan oleh ECIEncoding dengan penyisipan pengidentifikasi ECI.<br/>            Jika ditemukan karakter yang tidak didukung oleh encoding ECI yang dipilih, sebuah pengecualian dilempar.<br/>            Harap dicatat bahwa beberapa pemindai lama (sebelum 2006) mungkin tidak mendukung mode ini. |
| UNICODE | Mode Unicode merancang cara untuk merepresentasikan data teks apa pun yang merujuk ke enkoding/charset UTF8 dalam Han Xin Code. |
| URI | Mode URI menunjukkan data yang direpresentasikan dalam Han Xin Code adalah Uniform Resource Identifier (URI)<br/>            referensi ke RFC 3986. |
| EXTENDED | Mode Extended memungkinkan kombinasi mode internal: Auto, Binary, Text, Numeric, URI, Unicode, ECI, Common Chinese Region One,<br/>            Common Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte.<br/>            Codetext dapat dibangun secara manual dengan awalan dan backslash ganda, misalnya: @"\auto:abc\000009:ΑΒΓΔΕ\auto:ab\\c" atau menggunakan HanXinExtCodetextBuilder.<br/>            Jika codetext berisi fragmen ECI, maka hanya mode berikut yang dapat berada dalam codetext setelah fragmen ECI:<br/>            Auto, Binary, Text, Numeric, URI, ECI. |

### Lihat Juga

* namespace [aspose.barcode.generation](/barcode/python-net/aspose.barcode.generation/)
* assembly [Aspose.BarCode](/barcode/python-net/)

