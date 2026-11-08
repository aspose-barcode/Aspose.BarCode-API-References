---
title: "Aspose::BarCode::Generation::SymbologyEncodeType-klass"
linktitle: "SymbologyEncodeType"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::Generation::SymbologyEncodeType-klass. Symbolkodningstyp. Se EncodeTypes för att få en instans i C++."
type: docs
weight: 4900
url: /sv/cpp/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class


Symbolkodningstyp. Se [EncodeTypes](../encodetypes/) för att få en instans.

```cpp
class SymbologyEncodeType : public Aspose::BarCode::Generation::BaseEncodeType
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Equals](../baseencodetype/equals/)(System::SharedPtr\<BaseEncodeType\>) override | Returnerar ett värde som indikerar om denna instans är lika med ett specificerat [BaseEncodeType](../baseencodetype/) värde. |
| [get_Classification](../baseencodetype/get_classification/)() const | Hämtar en klassificering av denna symbologi. |
| [get_TypeIndex](../baseencodetype/get_typeindex/)() const | Hämtar ett index för kodningstyp |
| [get_TypeName](../baseencodetype/get_typename/)() const | Hämtar ett namn för kodningstyp |
| [GetHashCode](../baseencodetype/gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [GetString](../baseencodetype/getstring/)() | Konverterar instansen av [BaseEncodeType](../baseencodetype/) till dess motsvarande strängrepresentation. Strängformatet är: "Index:0; Name:Codabar". |
| static [GetString](../baseencodetype/getstring/)(System::SharedPtr\<BaseEncodeType\>) | Konverterar instansen av [BaseEncodeType](../baseencodetype/) till dess motsvarande strängrepresentation. Strängformatet är: "Index:-1; Name:None". |
| static [Parse](../baseencodetype/parse/)(System::String) | Konverterar strängrepresentationen av namnet på en [BaseEncodeType](../baseencodetype/) till dess instans. |
| [ToString](../baseencodetype/tostring/)() const override | Returnerar namnet på den angivna [BaseEncodeType](../baseencodetype/) som en sträng. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Konverterar strängrepresentationen av en [BaseEncodeType](../baseencodetype/) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | Konverterar strängrepresentationen av en [BaseEncodeType](../baseencodetype/) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
## Anmärkningar


Detta exempel visar hur man får en instans av klassen [SymbologyEncodeType](./).
```cpp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR

[VB.NET]
Dim symbologyType As SymbologyEncodeType
symbologyType = EncodeTypes.QR
```

## Se även

* Class [BaseEncodeType](../baseencodetype/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
