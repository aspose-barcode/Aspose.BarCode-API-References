---
title: "Aspose::BarCode::Generation::BaseEncodeType Klasse"
linktitle: "BaseEncodeType"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::Generation::BaseEncodeType Klasse. Basisklasse für SymbologyEncodeType in C++."
type: docs
weight: 600
url: /de/cpp/aspose.barcode.generation/baseencodetype/
---
## BaseEncodeType class


Basisklasse für [SymbologyEncodeType](../symbologyencodetype/).

```cpp
class BaseEncodeType : public System::IEquatable<System::SharedPtr<BaseEncodeType>>
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<BaseEncodeType\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BaseEncodeType](./)-Wert entspricht. |
| [get_Classification](./get_classification/)() const | Ermittelt eine Klassifizierung dieses Symbols. |
| [get_TypeIndex](./get_typeindex/)() const | Ermittelt einen Index des Kodierungstyps. |
| [get_TypeName](./get_typename/)() const | Ermittelt einen Namen des Kodierungstyps. |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [GetString](./getstring/)() | Konvertiert die Instanz von [BaseEncodeType](./) in ihre entsprechende Zeichenkettenrepräsentation. Das Zeichenkettenformat ist: "Index:0; Name:Codabar". |
| static [GetString](./getstring/)(System::SharedPtr\<BaseEncodeType\>) | Konvertiert die Instanz von [BaseEncodeType](./) in ihre entsprechende Zeichenkettenrepräsentation. Das Zeichenkettenformat ist: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | Konvertiert die Zeichenkettenrepräsentation des Namens eines [BaseEncodeType](./) in seine Instanz. |
| [ToString](./tostring/)() const override | Gibt den Namen des angegebenen [BaseEncodeType](./) als Zeichenkette zurück. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Konvertiert die Zeichenkettenrepräsentation eines [BaseEncodeType](./) in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | Konvertiert die Zeichenkettenrepräsentation eines [BaseEncodeType](./) in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
## Siehe auch

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
