---
title: "Class Metered"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.Metered sınıfı. Ölçülen anahtarı ayarlamak için yöntemler sağlar"
type: docs
weight: 1770
url: /tr/net/aspose.barcode/metered/
---
## Metered class

Ölçülen anahtarı ayarlamak için yöntemler sağlar.

```csharp
public class Metered
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Metered](metered/)() | Varsayılan yapıcı. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetProductName](../../aspose.barcode/metered/getproductname/)() | Lisanslı ürünün adını alır |
| [SetMeteredKey](../../aspose.barcode/metered/setmeteredkey/)(string, string) | Ölçülen genel ve özel anahtarı ayarlar. Ölçülen lisans satın alırsanız, uygulamayı başlattığınızda bu API çağrılmalıdır; genellikle bu yeterlidir. Ancak, tüketim verileri yüklenemeyip 24 saati aşarsa, lisans değerlendirme durumuna geçer; bu durumu önlemek için lisans durumunu düzenli olarak kontrol etmeli, eğer değerlendirme durumundaysa bu API'yi tekrar çağırmalısınız. |
| static [GetConsumptionCredit](../../aspose.barcode/metered/getconsumptioncredit/)() | Tüketim kredisini alır |
| static [GetConsumptionQuantity](../../aspose.barcode/metered/getconsumptionquantity/)() | Tüketim dosyası boyutunu alır |
| static [IsMeteredLicensed](../../aspose.barcode/metered/ismeteredlicensed/)() | Metered'in lisanslı olup olmadığını kontrol edin |

## Örnekler

Bu örnekte, metered genel ve özel anahtarını ayarlamaya çalışılacak

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


