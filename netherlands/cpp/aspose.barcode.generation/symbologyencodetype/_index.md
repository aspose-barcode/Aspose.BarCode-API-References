---
title: "Aspose::BarCode::Generation::SymbologyEncodeType class"
linktitle: "SymbologyEncodeType"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::Generation::SymbologyEncodeType class. Symboliek-coderingstype. Zie EncodeTypes om een instantie te krijgen in C++."
type: docs
weight: 4900
url: /nl/cpp/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class


Symboliek-coderingstype. Zie [EncodeTypes](../encodetypes/) om een instantie te krijgen.

```cpp
class SymbologyEncodeType : public Aspose::BarCode::Generation::BaseEncodeType
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Equals](../baseencodetype/equals/)(System::SharedPtr\<BaseEncodeType\>) override | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [BaseEncodeType](../baseencodetype/) waarde. |
| [get_Classification](../baseencodetype/get_classification/)() const | Haalt een classificatie van deze symboliek op. |
| [get_TypeIndex](../baseencodetype/get_typeindex/)() const | Haalt een index van het coderings type op. |
| [get_TypeName](../baseencodetype/get_typename/)() const | Haalt een naam van het coderings type op. |
| [GetHashCode](../baseencodetype/gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [GetString](../baseencodetype/getstring/)() | Converteert de instantie van [BaseEncodeType](../baseencodetype/) naar de equivalente tekenreeksrepresentatie. Het tekenreeksformaat is: "Index:0; Name:Codabar". |
| static [GetString](../baseencodetype/getstring/)(System::SharedPtr\<BaseEncodeType\>) | Converteert de instantie van [BaseEncodeType](../baseencodetype/) naar de equivalente tekenreeksrepresentatie. Het tekenreeksformaat is: "Index:-1; Name:None". |
| static [Parse](../baseencodetype/parse/)(System::String) | Converteert de tekenreeksrepresentatie van de naam van een [BaseEncodeType](../baseencodetype/) naar de instantie. |
| [ToString](../baseencodetype/tostring/)() const override | Retourneert de naam van de gegeven [BaseEncodeType](../baseencodetype/) als een tekenreeks. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Converteert de tekenreeksrepresentatie van een [BaseEncodeType](../baseencodetype/) naar de instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | Converteert de tekenreeksrepresentatie van een [BaseEncodeType](../baseencodetype/) naar de instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is. |
## Opmerkingen


Dit voorbeeld laat zien hoe een instantie van de [SymbologyEncodeType](./) klasse te verkrijgen.
```cpp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR

[VB.NET]
Dim symbologyType As SymbologyEncodeType
symbologyType = EncodeTypes.QR
```

## Zie ook

* Class [BaseEncodeType](../baseencodetype/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
