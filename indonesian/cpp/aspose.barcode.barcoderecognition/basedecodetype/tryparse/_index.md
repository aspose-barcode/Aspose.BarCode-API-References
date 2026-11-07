---
title: "metode"
linktitle: "TryParse"
second_title: "Aspose.BarCode for C++ Referensi API"
description: "Metode. Mengonversi representasi string dari SingleDecodeType menjadi instansinya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal di C++."
type: docs
weight: 400
url: /id/cpp/aspose.barcode.barcoderecognition/basedecodetype/tryparse/
---
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<SingleDecodeType\>\&) method


Mengonversi representasi string dari [SingleDecodeType](../../singledecodetype/) menjadi instansinya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<SingleDecodeType> &result)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parsingType | System::String | String yang berisi [SingleDecodeType](../../singledecodetype/) dalam format seperti "EAN8" atau "EAN13" atau "CodaBar"... untuk dikonversi. |
| result | System::SharedPtr\<SingleDecodeType\>\& | Sebuah [SingleDecodeType](../../singledecodetype/) yang sebenarnya dikembalikan, ketika konversi selesai dengan sukses; jika tidak, mengembalikan tipe tak tentu: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Lihat Juga

* Class [SingleDecodeType](../../singledecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<MultiDecodeType\>\&) method


Mengonversi representasi string dari [MultiDecodeType](../../multidecodetype/) menjadi instansinya. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<MultiDecodeType> &result)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parsingType | System::String | String yang berisi representasi [MultiDecodeType](../../multidecodetype/) untuk dikonversi. |
| result | System::SharedPtr\<MultiDecodeType\>\& | Sebuah [MultiDecodeType](../../multidecodetype/) yang sebenarnya dikembalikan, ketika konversi selesai dengan sukses; jika tidak, mengembalikan tipe tak tentu: new [MultiDecodeType](../../multidecodetype/)([DecodeType.None](../../decodetype/none/)) |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Lihat Juga

* Class [MultiDecodeType](../../multidecodetype/)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## BaseDecodeType::TryParse(System::String, System::SharedPtr\<BaseDecodeType\>\&) method


Mengonversi representasi string dari [BaseDecodeType](../) menjadi instansinya, setelah menentukan tipe konkret. Nilai kembali menunjukkan apakah konversi berhasil atau gagal.

```cpp
static bool Aspose::BarCode::BarCodeRecognition::BaseDecodeType::TryParse(System::String parsingType, System::SharedPtr<BaseDecodeType> &result)
```


| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parsingType | System::String | String yang berisi representasi [MultiDecodeType](../../multidecodetype/) untuk dikonversi. |
| result | System::SharedPtr\<BaseDecodeType\>\& | Sebuah [MultiDecodeType](../../multidecodetype/) yang sebenarnya dikembalikan, ketika konversi selesai dengan sukses; jika tidak, mengembalikan tipe tak tentu: [DecodeType.None](../../decodetype/none/). |

### ReturnValue

**true** if parsingType was converted successfully; otherwise, **false**.

## Lihat Juga

* Class [BaseDecodeType](../)
* Class [BaseDecodeType](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
