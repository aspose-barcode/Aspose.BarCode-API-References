---
title: "Aspose::BarCode::BarCodeRecognition::LuminanceFrame sınıfı"
linktitle: "LuminanceFrame"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::BarCodeRecognition::LuminanceFrame sınıfı. 8 bitlik gri tonlamalı bir görüntü çerçevesini temsil eder. Her piksel, C++'da parlaklık değerini içeren bir bayt ile temsil edilir."
type: docs
weight: 2400
url: /tr/cpp/aspose.barcode.barcoderecognition/luminanceframe/
---
## LuminanceFrame class


8 bitlik gri tonlamalı bir görüntü çerçevesini temsil eder. Her piksel, parlaklık değerini içeren bir bayt ile temsil edilir.

```cpp
class LuminanceFrame : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Data](./get_data/)() const | Parlaklık verilerini alır. |
| [get_Height](./get_height/)() const | Çerçevenin yüksekliğini piksel olarak alır. |
| [get_RotationDegrees](./get_rotationdegrees/)() const | Çerçevenin doğru yönelime sahip olması için saat yönünde döndürülmesi gereken derece sayısını alır. |
| [get_RowStride](./get_rowstride/)() const | İki yan yana satırın başlangıçları arasındaki bayt cinsinden mesafeyi alır. |
| [get_Width](./get_width/)() const | Çerçevenin genişliğini piksel olarak alır. |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t) | Satırlar arasında doldurma olmadan yeni bir [LuminanceFrame](./) sınıfı örneği başlatır. Yan yana satırlar arasındaki mesafe *width* değerine eşittir. |
| [LuminanceFrame](./luminanceframe/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, int32_t, int32_t) | Belirtilen satır adımıyla yeni bir [LuminanceFrame](./) sınıfı örneği başlatır. |
## Ayrıca Bakınız

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
