---
title: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType klass"
linktitle: "SingleDecodeType"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType klass. Enstaka avkodningstyp. Se avkodningstyp för att få instans i C++."
type: docs
weight: 3200
url: /sv/cpp/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class


Enkel avkodningstyp. Se avkodningstyp för att få en instans.

```cpp
class SingleDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                         public System::IEquatable<System::SharedPtr<SingleDecodeType>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Returnerar ett värde som indikerar om denna instans är inkluderad i den angivna listan. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Returnerar ett värde som indikerar om denna instans är lika med ett specificerat [SingleDecodeType](./)-värde. |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Returnerar ett värde som indikerar om den specificerade [MultiDecodeType](../multidecodetype/)-samlingen endast innehåller denna avkodningstyp. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returnerar ett värde som indikerar om denna instans är lika med ett specificerat [SingleDecodeType](./)-värde. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Returnerar ett värde som indikerar om denna instans är lika med ett specificerat [BaseDecodeType](../basedecodetype/)-värde. |
| [get_TypeIndex](./get_typeindex/)() const | Hämtar ett index för avkodningstypen |
| [get_TypeName](./get_typename/)() const | Hämtar ett namn för avkodningstypen |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [GetString](./getstring/)() | Konverterar instansen av [SingleDecodeType](./) till dess motsvarande strängrepresentation. Strängformatet är: "Index:-1; Name:None". |
| static [GetString](./getstring/)(System::SharedPtr\<SingleDecodeType\>) | Konverterar instansen av [SingleDecodeType](./) till dess motsvarande strängrepresentation. Strängformatet är: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | Konverterar strängrepresentationen av namnet på en [SingleDecodeType](./) till dess instans. |
| [ToString](./tostring/)() const override | Returnerar namnet på den givna [SingleDecodeType](./) som en sträng. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Konverterar strängrepresentationen av en [SingleDecodeType](./) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Konverterar strängrepresentationen av en [MultiDecodeType](../multidecodetype/) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Konverterar strängrepresentationen av en [BaseDecodeType](../basedecodetype/) till dess instans, efter att ha bestämt den konkreta typen. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
## Anmärkningar


Detta exempel visar hur man får en instans av en enstaka avkodningstyp.
```cpp
[C#]
SingleDecodeType singleType = DecodeType.QR

[VB.NET]
Dim singleType As SingleDecodeType
singleType = DecodeType.QR
```

## Se även

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
