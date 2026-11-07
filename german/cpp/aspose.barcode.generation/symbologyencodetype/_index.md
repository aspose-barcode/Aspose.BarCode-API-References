---
title: "Aspose::BarCode::Generation::SymbologyEncodeType Klasse"
linktitle: "SymbologyEncodeType"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::SymbologyEncodeType Klasse. Symbolkodierungstyp. Siehe EncodeTypes, um eine Instanz in C++ zu erhalten."
type: docs
weight: 4900
url: /de/cpp/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class


Symbolkodierungstyp. Siehe [EncodeTypes](../encodetypes/), um eine Instanz zu erhalten.

```cpp
class SymbologyEncodeType : public Aspose::BarCode::Generation::BaseEncodeType
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [Equals](../baseencodetype/equals/)(System::SharedPtr\<BaseEncodeType\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BaseEncodeType](../baseencodetype/)-Wert entspricht. |
| [get_Classification](../baseencodetype/get_classification/)() const | Ermittelt eine Klassifizierung dieses Symbols. |
| [get_TypeIndex](../baseencodetype/get_typeindex/)() const | Ermittelt einen Index des Kodierungstyps. |
| [get_TypeName](../baseencodetype/get_typename/)() const | Ermittelt einen Namen des Kodierungstyps. |
| [GetHashCode](../baseencodetype/gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [GetString](../baseencodetype/getstring/)() | Konvertiert die Instanz von [BaseEncodeType](../baseencodetype/) in ihre entsprechende Zeichenkettenrepräsentation. Das Zeichenkettenformat ist: "Index:0; Name:Codabar". |
| static [GetString](../baseencodetype/getstring/)(System::SharedPtr\<BaseEncodeType\>) | Konvertiert die Instanz von [BaseEncodeType](../baseencodetype/) in ihre entsprechende Zeichenkettenrepräsentation. Das Zeichenkettenformat ist: "Index:-1; Name:None". |
| static [Parse](../baseencodetype/parse/)(System::String) | Konvertiert die Zeichenkettenrepräsentation des Namens eines [BaseEncodeType](../baseencodetype/) in seine Instanz. |
| [ToString](../baseencodetype/tostring/)() const override | Gibt den Namen des angegebenen [BaseEncodeType](../baseencodetype/) als Zeichenkette zurück. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Konvertiert die Zeichenkettenrepräsentation eines [BaseEncodeType](../baseencodetype/) in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | Konvertiert die Zeichenkettenrepräsentation eines [BaseEncodeType](../baseencodetype/) in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
## Hinweise


Dieses Beispiel zeigt, wie man eine Instanz der Klasse [SymbologyEncodeType](./) erhält.
```cpp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR

[VB.NET]
Dim symbologyType As SymbologyEncodeType
symbologyType = EncodeTypes.QR
```

## Siehe auch

* Class [BaseEncodeType](../baseencodetype/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
