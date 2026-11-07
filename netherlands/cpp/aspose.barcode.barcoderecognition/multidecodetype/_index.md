---
title: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType klasse"
linktitle: "MultiDecodeType"
second_title: "Aspose.BarCode for C++ API-referentie"
description: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType klasse. Samengestelde decodeertype in C++."
type: docs
weight: 2600
url: /nl/cpp/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class


Samengestelde decodeertype.

```cpp
class MultiDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                        public System::IEquatable<System::SharedPtr<MultiDecodeType>>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<SingleDecodeType\>) | Voegt nog één [SingleDecodeType](../singledecodetype/) toe aan de [MultiDecodeType](./). |
| [ContainsAll](./containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Controleer of dit alle barcode-typen bevat. |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Bevat een van de typen. |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Retourneert een waarde die aangeeft of dit exemplaar gelijk is aan een opgegeven [MultiDecodeType](./) waarde. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Retourneert een waarde die aangeeft of deze collectie decodeertypen alleen de opgegeven [SingleDecodeType](../singledecodetype/) waarde bevat. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Retourneert een waarde die aangeeft of dit exemplaar gelijk is aan een opgegeven [MultiDecodeType](./) waarde. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Retourneert een waarde die aangeeft of deze instantie gelijk is aan een opgegeven [BaseDecodeType](../basedecodetype/)-waarde. |
| [Exclude](./exclude/)(System::SharedPtr\<SingleDecodeType\>) | Sluit [SingleDecodeType](../singledecodetype/) uit van de [MultiDecodeType](./) en retourneert een nieuw [MultiDecodeType](./) exemplaar. |
| [get_GetSingleTypesCount](./get_getsingletypescount/)() | Retourneert een aantal enkele typen. |
| [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode voor deze instantie. |
| [GetSingleTypes](./getsingletypes/)() | Stelt een lijst van enkele typen voor. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Initialiseert een nieuw exemplaar van de [MultiDecodeType](./) klasse. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialiseert een nieuw exemplaar van de [MultiDecodeType](./) klasse. |
| [ToString](./tostring/)() const override | Overschreven methode die [MultiDecodeType](./) als een string weergeeft. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Converteert de stringrepresentatie van een [MultiDecodeType](./) naar zijn exemplaar. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converteert de tekenreeksrepresentatie van een [SingleDecodeType](../singledecodetype/) naar de bijbehorende instantie. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Converteert de tekenreeksrepresentatie van een [BaseDecodeType](../basedecodetype/) naar de bijbehorende instantie, nadat het concrete type is bepaald. Een retourwaarde geeft aan of de conversie geslaagd of mislukt is. |
## Opmerkingen


Dit voorbeeld toont hoe samengestelde MultiDecode-typen te maken die [SingleDecodeType](../singledecodetype/) en MultiDecode-typen combineren.
```cpp
[C#]
MultiDecodeType types1 = new MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultiDecodeType types2 = new MultiDecodeType(types1, DecodeType.Code128, DecodeType.Code39);
[VB.NET]
Dim multiType1 As MultiDecodeType
multiType1 = New MultiDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multiType2 As MultiDecodeType
multiType2 = New MultiDecodeType(multiType1, DecodeType.Code128, DecodeType.Code39)
```

## Zie ook

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
