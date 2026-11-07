---
title: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType class"
linktitle: "MultiDecodeType"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::MultiDecodeType class. Zusammengesetzter Decodierungstyp in C++."
type: docs
weight: 2600
url: /de/cpp/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class


Zusammengesetzter Decodetyp.

```cpp
class MultiDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                        public System::IEquatable<System::SharedPtr<MultiDecodeType>>
```

## Methods

| Method | Beschreibung |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<SingleDecodeType\>) | Fügt einen weiteren [SingleDecodeType](../singledecodetype/) zum [MultiDecodeType](./) hinzu. |
| [ContainsAll](./containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Prüft, ob dies alle Typen aus den Barcode-Typen enthält. |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Enthält irgendeinen der Typen. |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [MultiDecodeType](./)-Wert gleich ist. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Gibt einen Wert zurück, der angibt, ob diese Sammlung von Decodierungstypen nur den angegebenen [SingleDecodeType](../singledecodetype/)-Wert enthält. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [MultiDecodeType](./)-Wert gleich ist. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BaseDecodeType](../basedecodetype/)-Wert entspricht. |
| [Exclude](./exclude/)(System::SharedPtr\<SingleDecodeType\>) | Schließt [SingleDecodeType](../singledecodetype/) vom [MultiDecodeType](./) aus und gibt eine neue [MultiDecodeType](./)-Instanz zurück. |
| [get_GetSingleTypesCount](./get_getsingletypescount/)() | Gibt die Anzahl einzelner Typen zurück. |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| [GetSingleTypes](./getsingletypes/)() | Stellt eine Liste einzelner Typen dar. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Initialisiert eine neue Instanz der [MultiDecodeType](./)-Klasse. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initialisiert eine neue Instanz der [MultiDecodeType](./)-Klasse. |
| [ToString](./tostring/)() const override | Überschriebene Methode, die [MultiDecodeType](./) als Zeichenkette darstellt. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Konvertiert die Zeichenkettenrepräsentation eines [MultiDecodeType](./) in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Konvertiert die Zeichenkettenrepräsentation eines [SingleDecodeType](../singledecodetype/) in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Konvertiert die Zeichenkettenrepräsentation eines [BaseDecodeType](../basedecodetype/) in seine Instanz, nachdem der konkrete Typ ermittelt wurde. Der Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
## Hinweise


Dieses Beispiel zeigt, wie zusammengesetzte MultiDecode-Typen erstellt werden, die [SingleDecodeType](../singledecodetype/) und MultiDecode-Typen kombinieren.
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

## Siehe auch

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
