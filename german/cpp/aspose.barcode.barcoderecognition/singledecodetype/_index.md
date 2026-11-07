---
title: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType Klasse"
linktitle: "SingleDecodeType"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::SingleDecodeType Klasse. Einzelner Dekodierungstyp. Siehe Dekodierungstyp, um eine Instanz in C++ zu erhalten."
type: docs
weight: 3200
url: /de/cpp/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class


Einzelner Decodetyp. Siehe Decodetyp, um eine Instanz zu erhalten.

```cpp
class SingleDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                         public System::IEquatable<System::SharedPtr<SingleDecodeType>>
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Gibt einen Wert zurück, der angibt, ob diese Instanz in die angegebene Liste aufgenommen wurde. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [SingleDecodeType](./)-Wert entspricht. |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Gibt einen Wert zurück, der angibt, ob die angegebene [MultiDecodeType](../multidecodetype/)-Sammlung ausschließlich diesen Dekodierungstyp enthält. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [SingleDecodeType](./)-Wert entspricht. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BaseDecodeType](../basedecodetype/)-Wert entspricht. |
| [get_TypeIndex](./get_typeindex/)() const | Ermittelt einen Index des Dekodierungstyps |
| [get_TypeName](./get_typename/)() const | Ermittelt einen Namen des Dekodierungstyps |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [GetString](./getstring/)() | Konvertiert die Instanz von [SingleDecodeType](./) in ihre äquivalente Zeichenkettenrepräsentation. Das Zeichenkettenformat ist: "Index:-1; Name:None". |
| static [GetString](./getstring/)(System::SharedPtr\<SingleDecodeType\>) | Konvertiert die Instanz von [SingleDecodeType](./) in ihre äquivalente Zeichenkettenrepräsentation. Das Zeichenkettenformat ist: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | Konvertiert die Zeichenkettenrepräsentation des Namens eines [SingleDecodeType](./) in seine Instanz. |
| [ToString](./tostring/)() const override | Gibt den Namen des angegebenen [SingleDecodeType](./) als Zeichenkette zurück. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Konvertiert die Zeichenkettenrepräsentation eines [SingleDecodeType](./) in seine Instanz. Der Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Konvertiert die Zeichenkettenrepräsentation eines [MultiDecodeType](../multidecodetype/) in seine Instanz. Der Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Konvertiert die Zeichenkettenrepräsentation eines [BaseDecodeType](../basedecodetype/) in seine Instanz, nachdem der konkrete Typ ermittelt wurde. Der Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
## Hinweise


Dieses Beispiel zeigt, wie man eine Instanz eines einzelnen Dekodierungstyps erhält.
```cpp
[C#]
SingleDecodeType singleType = DecodeType.QR

[VB.NET]
Dim singleType As SingleDecodeType
singleType = DecodeType.QR
```

## Siehe auch

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
