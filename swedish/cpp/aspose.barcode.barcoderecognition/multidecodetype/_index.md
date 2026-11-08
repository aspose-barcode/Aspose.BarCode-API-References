---
title: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType klass"
linktitle: "MultiDecodeType"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType klass. Sammansatt avkodningstyp i C++."
type: docs
weight: 2600
url: /sv/cpp/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class


Sammansatt avkodningstyp.

```cpp
class MultiDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                        public System::IEquatable<System::SharedPtr<MultiDecodeType>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<SingleDecodeType\>) | Lägger till en ytterligare [SingleDecodeType](../singledecodetype/) till [MultiDecodeType](./). |
| [ContainsAll](./containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Kontrollera om detta innehåller alla typer från streckkodstyper. |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Innehåller någon av typerna |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Returnerar ett värde som indikerar om denna instans är lika med ett specificerat [MultiDecodeType](./)-värde. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Returnerar ett värde som indikerar om denna samling av avkodningstyper endast innehåller det specificerade [SingleDecodeType](../singledecodetype/)-värdet. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returnerar ett värde som indikerar om denna instans är lika med ett specificerat [MultiDecodeType](./)-värde. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Returnerar ett värde som indikerar om denna instans är lika med ett specificerat [BaseDecodeType](../basedecodetype/)-värde. |
| [Exclude](./exclude/)(System::SharedPtr\<SingleDecodeType\>) | Exkluderar [SingleDecodeType](../singledecodetype/) från [MultiDecodeType](./) och returnerar en ny [MultiDecodeType](./)-instans. |
| [get_GetSingleTypesCount](./get_getsingletypescount/)() | Returnerar ett antal enkla typer. |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| [GetSingleTypes](./getsingletypes/)() | Representerar en lista av enkla typer. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Initierar en ny instans av klassen [MultiDecodeType](./). |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initierar en ny instans av klassen [MultiDecodeType](./). |
| [ToString](./tostring/)() const override | Åsidosatt metod som representerar [MultiDecodeType](./) som en sträng. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Konverterar strängrepresentationen av ett [MultiDecodeType](./) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Konverterar strängrepresentationen av en [SingleDecodeType](../singledecodetype/) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Konverterar strängrepresentationen av en [BaseDecodeType](../basedecodetype/) till dess instans, efter att ha bestämt den konkreta typen. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
## Anmärkningar


Detta exempel visar hur man skapar sammansatta MultiDecode-typer som kombinerar [SingleDecodeType](../singledecodetype/) och MultiDecode-typer.
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

## Se även

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
