---
title: Aspose::BarCode::Generation::SymbologyEncodeType class
linktitle: SymbologyEncodeType
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::SymbologyEncodeType class. Symbology encode type. See EncodeTypes to get instance in C++.'
type: docs
weight: 4400
url: /cpp/aspose.barcode.generation/symbologyencodetype/
---
## SymbologyEncodeType class


Symbology encode type. See [EncodeTypes](../encodetypes/) to get instance.

```cpp
class SymbologyEncodeType : public Aspose::BarCode::Generation::BaseEncodeType
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](../baseencodetype/equals/)(System::SharedPtr\<BaseEncodeType\>) override | Returns a value indicating whether this instance is equal to a specified [BaseEncodeType](../baseencodetype/) value. |
| [get_Classification](../baseencodetype/get_classification/)() | Gets a classification of this symbology. |
| [get_TypeIndex](../baseencodetype/get_typeindex/)() | Gets an index of encode type |
| [get_TypeName](../baseencodetype/get_typename/)() | Gets a name of encode type |
| [GetHashCode](../baseencodetype/gethashcode/)() const override | Returns the hash code for this instance. |
| [GetString](../baseencodetype/getstring/)() | Converts the instance of [BaseEncodeType](../baseencodetype/) to its equivalent string representation. The string format is: "Index:0; Name:Codabar". |
| static [GetString](../baseencodetype/getstring/)(System::SharedPtr\<BaseEncodeType\>) | Converts the instance of [BaseEncodeType](../baseencodetype/) to its equivalent string representation. The string format is: "Index:-1; Name:None". |
| static [Parse](../baseencodetype/parse/)(System::String) | Converts the string representation of the name of a [BaseEncodeType](../baseencodetype/) to its instance. |
| [ToString](../baseencodetype/tostring/)() const override | Returns the name of the given [BaseEncodeType](../baseencodetype/) as a string. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Converts the string representation of a [BaseEncodeType](../baseencodetype/) to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](../baseencodetype/tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | Converts the string representation of a [BaseEncodeType](../baseencodetype/) to its instance. A return value indicates whether the conversion succeeded or failed. |
## Remarks


This sample shows how to get instance of [SymbologyEncodeType](./) class. 
```cpp
[C#]
SymbologyEncodeType symbologyType = EncodeTypes.QR 

[VB.NET]
Dim symbologyType As SymbologyEncodeType 
symbologyType = EncodeTypes.QR
```

## See Also

* Class [BaseEncodeType](../baseencodetype/)
* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
