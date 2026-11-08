---
title: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext sınıfı"
linktitle: "MailmarkCodetext"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::ComplexBarcode::MailmarkCodetext sınıfı. C++'ta 4 durumlu Royal Mailmark koduna gömülü metni kodlamak ve çözmek için sınıf."
type: docs
weight: 1500
url: /tr/cpp/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class


4 durumlu Royal Mailmark kodunda gömülü metni kodlamak ve çözmek için sınıf.

```cpp
class MailmarkCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Class](./get_class/)() const | \"0\" - Boş veya Test \"1\" - 1C (Perakende) \"2\" - 2C (Perakende) \"3\" - 3C (Perakende) \"4\" - Premium (RetailPublishing Mail) (potansiyel gelecekteki kullanım için) \"5\" - Ertelenmiş (Perakende) \"6\" - Hava (Perakende) (potansiyel gelecekteki kullanım için) \"7\" - Yüzey (Perakende) (potansiyel gelecekteki kullanım için) \"8\" - Premium (Ağ Erişimi) \"9\" - Standart (Ağ Erişimi) |
| [get_DestinationPostCodePlusDPS](./get_destinationpostcodeplusdps/)() const | PC ve DP, bir PAF formatına uymalıdır. Uluslararası \"XY11     \" (5 boşluk olduğunu unutmayın) belirten dokuz karakterlik dize veya yerel bir sıralama kodunu belirten karakter deseni. Yerel bir sıralama kodu, dış posta kodu, iç posta kodu ve Teslim Noktası Soneki'nden oluşur. |
| [get_Format](./get_format/)() const | \"0\" – Boş veya Test \"1\" – Mektup \"2\" – Büyük Mektup |
| [get_ItemID](./get_itemid/)() const | Azami değer 99999999'dur. |
| [get_SupplychainID](./get_supplychainid/)() const | Azami değerler Barcode C için 99 ve Barcode L için 999999'dur. |
| [get_VersionID](./get_versionid/)() const | Şu anda \"1\" – Mailmark barkodu için (0 ve 2'den 9'a ve A'dan Z'ye gelecekteki kullanım için ayrılmıştır) |
| [GetBarcodeType](./getbarcodetype/)() override | Barkod tipini alır. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Mailmark verilerinden kod metni oluşturur. |
| [InitFromString](./initfromstring/)(System::String) override | Oluşturulan kod metninden Mailmark verilerini başlatır. |
| [MailmarkCodetext](./mailmarkcodetext/)() | Yeni bir [MailmarkCodetext](./) sınıfının örneğini başlatır. |
| [set_Class](./set_class/)(System::String) | \"0\" - Boş veya Test \"1\" - 1C (Perakende) \"2\" - 2C (Perakende) \"3\" - 3C (Perakende) \"4\" - Premium (RetailPublishing Mail) (potansiyel gelecekteki kullanım için) \"5\" - Ertelenmiş (Perakende) \"6\" - Hava (Perakende) (potansiyel gelecekteki kullanım için) \"7\" - Yüzey (Perakende) (potansiyel gelecekteki kullanım için) \"8\" - Premium (Ağ Erişimi) \"9\" - Standart (Ağ Erişimi) |
| [set_DestinationPostCodePlusDPS](./set_destinationpostcodeplusdps/)(System::String) | PC ve DP, bir PAF formatına uymalıdır. Uluslararası \"XY11     \" (5 boşluk olduğunu unutmayın) belirten dokuz karakterlik dize veya yerel bir sıralama kodunu belirten karakter deseni. Yerel bir sıralama kodu, dış posta kodu, iç posta kodu ve Teslim Noktası Soneki'nden oluşur. |
| [set_Format](./set_format/)(int32_t) | \"0\" – Boş veya Test \"1\" – Mektup \"2\" – Büyük Mektup |
| [set_ItemID](./set_itemid/)(int32_t) | Azami değer 99999999'dur. |
| [set_SupplychainID](./set_supplychainid/)(int32_t) | Azami değerler Barcode C için 99 ve Barcode L için 999999'dur. |
| [set_VersionID](./set_versionid/)(int32_t) | Şu anda \"1\" – Mailmark barkodu için (0 ve 2'den 9'a ve A'dan Z'ye gelecekteki kullanım için ayrılmıştır) |
## Ayrıca Bakınız

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
