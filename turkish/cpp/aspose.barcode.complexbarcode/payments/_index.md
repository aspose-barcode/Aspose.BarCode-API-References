---
title: "Aspose::BarCode::ComplexBarcode::Payments sınıfı"
linktitle: "Payments"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::Payments sınıfı. C++'ta İsviçre Ödeme standartlarıyla ilgili alan doğrulamaları."
type: docs
weight: 2400
url: /tr/cpp/aspose.barcode.complexbarcode/payments/
---
## Payments class


İsviçre Ödeme standartlarıyla ilgili alan doğrulamaları.

```cpp
class Payments
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [CleanValue](./cleanvalue/)(System::String, Payments::CleaningResult\&) | Bir dize değerini temizleyerek 2018 İsviçre Ödeme Standartları için geçerli hale getirir. |
| static [CreateIso11649Reference](./createiso11649reference/)(System::String) | Ham bir dizeye "RF" önekini ekleyip modulo 97 kontrol toplamını ekleyerek bir ISO11649 alacaklı referansı oluşturur. |
| static [FormatIban](./formatiban/)(System::String) | Bir IBAN veya alacaklı referansını boşluk ekleyerek biçimlendirir |
| static [FormatQrReferenceNumber](./formatqrreferencenumber/)(System::String) | Bir QR referans numarasını boşluk ekleyerek biçimlendirir. |
| static [IsAlphaNumeric](./isalphanumeric/)(System::String) |  |
| static [IsValidIban](./isvalidiban/)(System::String) | Dizenin geçerli bir IBAN numarası olup olmadığını doğrular |
| static [IsValidIso11649Reference](./isvalidiso11649reference/)(System::String) | Dizenin geçerli bir ISO 11649 referans numarası olup olmadığını doğrular |
| static [IsValidQrReference](./isvalidqrreference/)(System::String) | Dizenin geçerli bir QR referansı olup olmadığını doğrular. |
| [Payments](./payments/)() |  |
## Ayrıca Bakınız

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
