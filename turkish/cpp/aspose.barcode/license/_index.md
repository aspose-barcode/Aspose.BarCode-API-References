---
title: "Aspose::BarCode::License sınıfı"
linktitle: "Lisans"
second_title: "Aspose.BarCode for C++ API Referansı"
description: "Aspose::BarCode::License sınıfı. Bileşeni C++'ta lisanslamak için yöntemler sağlar."
type: docs
weight: 300
url: /tr/cpp/aspose.barcode/license/
---
## License class


Bileşeni lisanslamak için yöntemler sağlar.

```cpp
class License : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [License](./license/)() | Bu sınıfın yeni bir örneğini başlatır. |
| [SetLicense](./setlicense/)(System::String) | Kütüphaneyi lisanslar. |
| [SetLicense](./setlicense/)(System::SharedPtr\<System::IO::Stream\>) | Kütüphaneyi lisanslar. |
## Açıklamalar


Bu örnekte, bileşeni içeren klasörde, çağıran derlemeyi içeren klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemenin gömülü kaynaklarında MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır.
```cpp
[C#]
@verbatim
License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
@endverbatim
```

## Ayrıca Bakınız

* Namespace [Aspose::BarCode](../)
* Library [Aspose.BarCode for C++](../../)
