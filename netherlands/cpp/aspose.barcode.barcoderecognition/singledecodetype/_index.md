---
title: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType klasse"
linktitle: "SingleDecodeType"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType klasse. Enkele decode-type. Zie decode-type om een instantie te krijgen in C++."
type: docs
weight: 3200
url: /nl/cpp/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class


Enkel decodeertype. Zie decodeertype om een instantie te verkrijgen.

```cpp
class SingleDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                         public System::IEquatable<System::SharedPtr<SingleDecodeType>>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Retourneert een waarde die aangeeft of deze instantie is opgenomen in de opgegeven lijst. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [SingleDecodeType](./)-waarde. |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Retourneert een waarde die aangeeft of de opgegeven [MultiDecodeType](../multidecodetype/)-collectie alleen dit decode-type bevat. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [SingleDecodeType](./)-waarde. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [BaseDecodeType](../basedecodetype/)-waarde. |
| [get_TypeIndex](./get_typeindex/)() const | Haalt een index van decode-type op |
| [get_TypeName](./get_typename/)() const | Haalt een naam van decode-type op |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [GetString](./getstring/)() | Converteert de instantie van [SingleDecodeType](./) naar de equivalente tekenreeksrepresentatie. Het tekenreeksformaat is: "Index:-1; Name:None". |
| static [GetString](./getstring/)(System::SharedPtr\<SingleDecodeType\>) | Converteert de instantie van [SingleDecodeType](./) naar de equivalente tekenreeksrepresentatie. Het tekenreeksformaat is: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | Converteert de tekenreeksrepresentatie van de naam van een [SingleDecodeType](./) naar de bijbehorende instantie. |
| [ToString](./tostring/)() const override | Retourneert de naam van de opgegeven [SingleDecodeType](./) als een tekenreeks. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converteert de tekenreeksrepresentatie van een [SingleDecodeType](./) naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Converteert de tekenreeksrepresentatie van een [MultiDecodeType](../multidecodetype/) naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Converteert de tekenreeksrepresentatie van een [BaseDecodeType](../basedecodetype/) naar de bijbehorende instantie, nadat het concrete type is bepaald. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is. |
## Opmerkingen


Dit voorbeeld toont hoe u een instantie van een enkel decode-type kunt verkrijgen.
```cpp
[C#]
SingleDecodeType singleType = DecodeType.QR

[VB.NET]
Dim singleType As SingleDecodeType
singleType = DecodeType.QR
```

## Zie ook

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
