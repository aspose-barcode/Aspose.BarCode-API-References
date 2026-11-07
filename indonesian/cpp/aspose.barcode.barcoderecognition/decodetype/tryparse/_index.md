---
title: "metode"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Metode. Mengonversi representasi string dari SingleDecodeType menjadi instansinya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal di C++."
type: docs
weight: 500
url: /id/cpp/aspose.barcode.barcoderecognition/decodetype/tryparse/
---
## DecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


Mengonversi representasi string dari [SingleDecodeType](../../singledecodetype/) menjadi instansinya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parsingType | System::String | String yang berisi [SingleDecodeType](../../singledecodetype/) dalam format seperti "EAN8" atau "EAN13" atau "CodaBar"... untuk dikonversi. |
| result | System::SharedPtr\<SingleDecodeType\>\& | Sebuah [SingleDecodeType](../../singledecodetype/) aktual mengembalikan nilai, ketika konversi selesai dengan sukses; jika tidak, mengembalikan tipe tak tentu: [DecodeType.None](../none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Lihat Juga

* Class [SingleDecodeType](../../singledecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## DecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


Mengonversi representasi string dari [MultiDecodeType](../../multidecodetype/) menjadi instansinya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::DecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parsingType | System::String | Sebuah string dalam format baik "AllSupportedTypes" atau "EAN8,EAN13,CodaBar" untuk dikonversi. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Sebuah [MultiDecodeType](../../multidecodetype/) aktual dikembalikan, ketika konversi selesai dengan sukses; jika tidak, mengembalikan tipe tak tentu: new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Lihat Juga

* Class [MultiDecodeType](../../multidecodetype/)
* Class [DecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
