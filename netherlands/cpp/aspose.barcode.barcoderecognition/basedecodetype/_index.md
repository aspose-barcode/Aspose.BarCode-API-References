---
title: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType klasse"
linktitle: "BaseDecodeType"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType klasse. Basisklasse voor MultiDecodeType en SingleDecodeType in C++."
type: docs
weight: 900
url: /nl/cpp/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class


Basisklasse voor [MultiDecodeType](../multidecodetype/) en [SingleDecodeType](../singledecodetype/).

```cpp
class BaseDecodeType : public virtual System::IEquatable<System::SharedPtr<BaseDecodeType>>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Bepaalt of een van de opgegeven decode-types is opgenomen in |
| virtual [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [SingleDecodeType](../singledecodetype/)-waarde. |
| virtual [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [MultiDecodeType](../multidecodetype/)-waarde. |
| [Equals](./equals/)(System::SharedPtr\<BaseDecodeType\>) override | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [BaseDecodeType](./) waarde. |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converteert de tekenreeksrepresentatie van een [SingleDecodeType](../singledecodetype/) naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Converteert de tekenreeksrepresentatie van een [MultiDecodeType](../multidecodetype/) naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Converteert de tekenreeksrepresentatie van een [BaseDecodeType](./) naar de bijbehorende instantie, nadat het concrete type is bepaald. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is. |
## Opmerkingen


Dit voorbeeld toont hoe [BaseDecodeType](./) te gebruiken met [SingleDecodeType](../singledecodetype/) en [MultiDecodeType](../multidecodetype/).
```cpp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

## Zie ook

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
