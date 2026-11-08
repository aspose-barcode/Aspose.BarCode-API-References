---
title: "Aspose::BarCode::Metered sınıfı"
linktitle: "Ölçülen"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::Metered sınıfı. C++'ta ölçülen anahtarı ayarlamak için yöntemler sağlar."
type: docs
weight: 500
url: /tr/cpp/aspose.barcode/metered/
---
## Metered class


Sayaç anahtarını ayarlamak için yöntemler sağlar.

```cpp
class Metered : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | Tüketim kredisini alır |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | Tüketim dosya boyutunu alır |
| [GetProductName](./getproductname/)() | Lisanslı ürünün adını alır |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | Ölçülenin lisanslı olup olmadığını kontrol et |
| [Metered](./metered/)() | Bu sınıfın yeni bir örneğini başlatır. |
| [SetMeteredKey](./setmeteredkey/)(System::String, System::String) | Ölçülen genel ve özel anahtarı ayarlar. Ölçülen lisansı satın alırsanız, uygulamayı başlattığınızda bu API çağrılmalıdır, genellikle bu yeterlidir. Ancak, tüketim verilerini yükleme sürekli başarısız olur ve 24 saati aşarsa, lisans değerlendirme durumuna ayarlanır; böyle bir durumu önlemek için lisans durumunu düzenli olarak kontrol etmelisiniz, eğer değerlendirme durumundaysa, bu API'yi tekrar çağırın. |
## Açıklamalar


Bu örnekte, ölçülen genel ve özel anahtarı ayarlamaya çalışılacak

<ms>
```cpp
[C#]
@verbatim
Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
@endverbatim
```
</ms>

<java> bileşen jar dosyası:
```cpp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```
</java>
## Ayrıca Bakınız

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
