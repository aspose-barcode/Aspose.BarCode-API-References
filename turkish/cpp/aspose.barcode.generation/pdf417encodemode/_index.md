---
title: "enum"
linktitle: "Pdf417EncodeMode"
second_title: "Aspose.BarCode for C++ API Referansı"
description: " enum. C++'de Pdf417 barkod kodlama modu."
type: docs
weight: 7900
url: /tr/cpp/aspose.barcode.generation/pdf417encodemode/
---
## Pdf417EncodeMode enum


Pdf417 barkod kodlama modu

```cpp
enum class Pdf417EncodeMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Otomatik | 0 | Auto modunda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Unicode karakterleri, ECIEncoding tarafından belirtilen kodlamaya, bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. |
| İkili | 1 | İkili modda, CodeText maksimum veri sıkıştırmasıyla kodlanır. Bir Unicode karakteri bulunursa, bir istisna fırlatılır. |
| ECI | 2 | ECI modunda, tüm mesaj ECIEncoding tarafından belirtilen kodlamaya, bir ECI tanımlayıcısı eklenerek yeniden kodlanır. Seçilen ECI kodlaması tarafından desteklenmeyen bir karakter bulunursa, bir istisna fırlatılır. Lütfen bazı eski (2006 öncesi) tarayıcıların bu modu desteklemeyebileceğini unutmayın. |
| Genişletilmiş | 3 |  |

## Ayrıca Bakınız

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
