---
title: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType Klasse"
linktitle: "BaseDecodeType"
second_title: "Aspose.BarCode für C++ API-Referenz"
description: "Aspose::BarCode::BarCodeRecognition::BaseDecodeType Klasse. Basisklasse für MultiDecodeType und SingleDecodeType in C++."
type: docs
weight: 900
url: /de/cpp/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class


Basisklasse für [MultiDecodeType](../multidecodetype/) und [SingleDecodeType](../singledecodetype/).

```cpp
class BaseDecodeType : public virtual System::IEquatable<System::SharedPtr<BaseDecodeType>>
```

## Methods

| Method | Beschreibung |
| --- | --- |
| virtual [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Bestimmt, ob einer der angegebenen Dekodierungstypen enthalten ist. |
| virtual [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [SingleDecodeType](../singledecodetype/)-Wert entspricht. |
| virtual [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [MultiDecodeType](../multidecodetype/) Wert entspricht. |
| [Equals](./equals/)(System::SharedPtr\<BaseDecodeType\>) override | Gibt einen Wert zurück, der angibt, ob diese Instanz einem angegebenen [BaseDecodeType](./) Wert entspricht. |
| [GetHashCode](./gethashcode/)() const override | Gibt den Hashcode für diese Instanz zurück. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Konvertiert die Zeichenkettenrepräsentation eines [SingleDecodeType](../singledecodetype/) in seine Instanz. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Konvertiert die Zeichenkettenrepräsentation eines [MultiDecodeType](../multidecodetype/) in seine Instanz. Der Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Konvertiert die Zeichenkettenrepräsentation eines [BaseDecodeType](./) in seine Instanz, nachdem der konkrete Typ ermittelt wurde. Ein Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |
## Hinweise


Dieses Beispiel zeigt, wie man [BaseDecodeType](./) mit [SingleDecodeType](../singledecodetype/) und [MultiDecodeType](../multidecodetype/) verwendet.
```cpp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

## Siehe auch

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
