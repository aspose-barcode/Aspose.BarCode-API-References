---
title: Aspose::BarCode::Generation::BaseEncodeType class
linktitle: BaseEncodeType
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::Generation::BaseEncodeType class. Base class for SymbologyEncodeType in C++.'
type: docs
weight: 600
url: /cpp/aspose.barcode.generation/baseencodetype/
---
## BaseEncodeType class


Base class for [SymbologyEncodeType](../symbologyencodetype/).

```cpp
class BaseEncodeType : public System::IEquatable<System::SharedPtr<Aspose::BarCode::Generation::BaseEncodeType>>
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<BaseEncodeType\>) override | Returns a value indicating whether this instance is equal to a specified [BaseEncodeType](./) value. |
| [get_Classification](./get_classification/)() | Gets a classification of this symbology. |
| [get_TypeIndex](./get_typeindex/)() | Gets an index of encode type |
| [get_TypeName](./get_typename/)() | Gets a name of encode type |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [GetString](./getstring/)() | Converts the instance of [BaseEncodeType](./) to its equivalent string representation. The string format is: "Index:0; Name:Codabar". |
| static [GetString](./getstring/)(System::SharedPtr\<BaseEncodeType\>) | Converts the instance of [BaseEncodeType](./) to its equivalent string representation. The string format is: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | Converts the string representation of the name of a [BaseEncodeType](./) to its instance. |
| [ToString](./tostring/)() const override | Returns the name of the given [BaseEncodeType](./) as a string. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseEncodeType\>\&) | Converts the string representation of a [BaseEncodeType](./) to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SymbologyEncodeType\>\&) | Converts the string representation of a [BaseEncodeType](./) to its instance. A return value indicates whether the conversion succeeded or failed. |
## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
