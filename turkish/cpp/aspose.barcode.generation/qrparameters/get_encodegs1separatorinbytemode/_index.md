---
title: "metot"
linktitle: "get_EncodeGS1SeparatorInByteMode"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "C++'da Aspose::BarCode::Generation::QrParameters sınıfının get_EncodeGS1SeparatorInByteMode metodunun nasıl kullanılacağını."
type: docs
weight: 1700
url: /tr/cpp/aspose.barcode.generation/qrparameters/get_encodegs1separatorinbytemode/
---
## QrParameters::get_EncodeGS1SeparatorInByteMode method




```cpp
bool Aspose::BarCode::Generation::QrParameters::get_EncodeGS1SeparatorInByteMode() const
```

## Açıklamalar


QR ve RectMicroQR barkodları için GS1 özel karakterlerinin Bayt modunda kodlanıp kodlanmayacağını gösteren bir değer alır.

Yanlış ise, QR spesifikasyonuna göre GS1 ayırıcıları Alfanümerik modda '' olarak kodlanabilir.

Doğru ise, GS1 grup ayırıcıları Bayt modunda 0x1D karakteri olarak kodlanır ve '' karakterleri de veri olarak korunması için Bayt modunda kodlanır.

Bu seçenek, Bayt seviyesinde GS1 grup ayırıcıları bekleyen çözücülerle uyumluluğu artırabilir ve '' veri karakterlerinin GS1 ayırıcıları olarak yorumlanmasını önler.
## Ayrıca Bakınız

* Class [QrParameters](../)
* Namespace [Aspose::BarCode::Generation](../../)
* Library [Aspose.BarCode for C++](../../../)
