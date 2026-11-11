---
title: "Sınıf License"
second_title: "Aspose.BarCode for .NET API Referansı"
description: "Aspose.BarCode.License sınıfı. Bileşeni lisanslamak için yöntemler sağlar"
type: docs
weight: 1760
url: /tr/net/aspose.barcode/license/
---
## License class

Bileşeni lisanslamak için yöntemler sağlar.

```csharp
public class License
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [License](license/)() | Varsayılan yapıcı. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense)(Stream) | Kütüphaneyi lisanslar. |
| [SetLicense](../../aspose.barcode/license/setlicense/#setlicense_1)(string) | Kütüphaneyi lisanslar. |

## Örnekler

Bu örnekte, bileşeni içeren klasörde, çağıran derlemeyi içeren klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### Ayrıca Bakınız

* namespace [Aspose.BarCode](../../aspose.barcode/)
* assembly [Aspose.BarCode](../../)


