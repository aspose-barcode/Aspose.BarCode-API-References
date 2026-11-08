---
title: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType klass"
linktitle: "BaseDecodeType"
second_title: "Aspose.BarCode for C++ API-referens"
description: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType klass. Bas-klass för MultiDecodeType och SingleDecodeType i C++."
type: docs
weight: 900
url: /sv/cpp/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class


Bas-klass för [MultiDecodeType](../multidecodetype/) och [SingleDecodeType](../singledecodetype/).

```cpp
class BaseDecodeType : public virtual System::IEquatable<System::SharedPtr<BaseDecodeType>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Bestämmer om någon av de angivna avkodningstyperna är inkluderad i |
| virtual [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) | Returnerar ett värde som indikerar om denna instans är lika med ett specificerat [SingleDecodeType](../singledecodetype/)-värde. |
| virtual [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) | Returnerar ett värde som indikerar om denna instans är lika med ett specificerat [MultiDecodeType](../multidecodetype/)-värde. |
| [Equals](./equals/)(System::SharedPtr\<BaseDecodeType\>) override | Returnerar ett värde som indikerar om detta objekt är lika med ett specificerat [BaseDecodeType](./)-värde. |
| [GetHashCode](./gethashcode/)() const override | Returnerar hash‑koden för detta objekt. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Konverterar strängrepresentationen av en [SingleDecodeType](../singledecodetype/) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Konverterar strängrepresentationen av en [MultiDecodeType](../multidecodetype/) till dess instans. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Konverterar strängrepresentationen av en [BaseDecodeType](./) till dess instans, efter att den konkreta typen har bestämts. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |
## Anmärkningar


Detta exempel visar hur man använder [BaseDecodeType](./) med [SingleDecodeType](../singledecodetype/) och [MultiDecodeType](../multidecodetype/)
```cpp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

## Se även

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
