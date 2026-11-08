---
title: "Aspose::BarCode::Generation::BaseEncodeType klass"
linktitle: "BaseEncodeType"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::BaseEncodeType klass. Basisklass för SymbologyEncodeType i C++."
type: docs
weight: 600
url: /sv/cpp/aspose.barcode.generation/baseencodetype/
---
## BaseEncodeType class


Basisklass för [SymbologyEncodeType](../symbologyencodetype/).

```cpp
class BaseEncodeType : public System::IEquatable<System::SharedPtr<BaseEncodeType>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<BaseEncodeType\>) override | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [BaseEncodeType](./)-värde. |
| [get_Classification](./get_classification/)() const | Hämtar en klassificering av denna symbologi. |
| [get_TypeIndex](./get_typeindex/)() const | Hämtar ett index för kodningstyp |
| [get_TypeName](./get_typename/)() const | Hämtar ett namn för kodningstyp |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [GetString](./getstring/)() | Konverterar instansen av [BaseEncodeType](./) till dess motsvarande strängrepresentation. Strängformatet är: "Index:0; Name:Codabar". |
| static [GetString](./getstring/)(System::SharedPtr\<BaseEncodeType\>) | Konverterar instansen av [BaseEncodeType](./) till dess motsvarande strängrepresentation. Strängformatet är: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | Konverterar strängrepresentationen av namnet på en [BaseEncodeType](./) till dess instans. |
| [ToString](./tostring/)() const override | Returnerar namnet på den givna [BaseEncodeType](./) som en sträng. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Konverterar strängrepresentationen av en [BaseEncodeType](./) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | Konverterar strängrepresentationen av en [BaseEncodeType](./) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
## Se även

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
