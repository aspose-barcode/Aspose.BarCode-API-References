---
title: "yapıcı"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " yapıcı. Satırlar arasında doldurma olmadan LuminanceFrame sınıfının yeni bir örneğini başlatır. Yan yana satırlar arasındaki mesafe C++'da genişliğe eşittir."
type: docs
weight: 600
url: /tr/cpp/aspose.barcode.barcoderecognition/luminanceframe/luminanceframe/
---
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) constructor


Satırlar arasında doldurma olmadan [LuminanceFrame](../) sınıfının yeni bir örneğini başlatır. Yan yana satırlar arasındaki mesafe *width*'a eşittir.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rotationDegrees=0)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Bir piksel başına bir bayt içeren parlaklık verileri. |
| width | int32_t | Çerçeve genişliği piksel cinsinden. |
| height | int32_t | Çerçeve yüksekliği piksel cinsinden. |
| rotationDegrees | int32_t | Çerçeveyi dik konumda göstermek için gereken saat yönünde döndürme. Desteklenen değerler 0, 90, 180 ve 270'tir. Varsayılan değer 0'dır. |

## Ayrıca Bakınız

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
## LuminanceFrame::LuminanceFrame(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) constructor


Belirtilen satır adımıyla [LuminanceFrame](../) sınıfının yeni bir örneğini başlatır.

```cpp
Aspose::BarCode::BarCodeRecognition::LuminanceFrame::LuminanceFrame(System::ArrayPtr<uint8_t> data, int32_t width, int32_t height, int32_t rowStride, int32_t rotationDegrees)
```


| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | System::ArrayPtr\<uint8_t\> | Bir piksel başına bir bayt içeren parlaklık verileri. |
| width | int32_t | Çerçeve genişliği piksel cinsinden. |
| height | int32_t | Çerçeve yüksekliği piksel cinsinden. |
| rowStride | int32_t | İki yan yana satırın başlangıçları arasındaki bayt cinsinden mesafe. Değer *width* değerinden daha az olamaz. |
| rotationDegrees | int32_t | Kareyi dik konumda göstermek için gereken saat yönünde döndürme. Desteklenen değerler 0, 90, 180 ve 270. |

## Ayrıca Bakınız

* Class [LuminanceFrame](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
