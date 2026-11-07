---
title: "metode"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ Referensi API"
description: " method. Mengonversi representasi string dari MultiDecodeType menjadi instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal di C++."
type: docs
weight: 1100
url: /id/cpp/aspose.barcode.barcoderecognition/multidecodetype/tryparse/
---
## MultiDecodeType::TryParse method


Mengonversi representasi string dari [MultiDecodeType](../) menjadi instance-nya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::MultiDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parsingType | System::String | Sebuah string dalam format baik "AllSupportedTypes" atau "EAN8,EAN13,CodaBar" untuk dikonversi. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Sebuah [MultiDecodeType](../) aktual dikembalikan, ketika konversi selesai dengan sukses; |

### ReturnValue

**true** if s was converted successfully; otherwise, **false**.
## Catatan



sebaliknya ia mengembalikan tipe tak tentu.

atau [MultiDecodeType](../) ("None").

## Lihat Juga

* Class [MultiDecodeType](../)
* Class [MultiDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
