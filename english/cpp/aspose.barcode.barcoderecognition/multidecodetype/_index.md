---
title: Aspose::BarCode::BarCodeRecognition::MultiDecodeType class
linktitle: MultiDecodeType
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::MultiDecodeType class. Composite decode type in C++.'
type: docs
weight: 2200
url: /cpp/aspose.barcode.barcoderecognition/multidecodetype/
---
## MultiDecodeType class


Composite decode type.

```cpp
class MultiDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                        public System::IEquatable<System::SharedPtr<Aspose::BarCode::BarCodeRecognition::MultiDecodeType>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<SingleDecodeType\>) | Adds one more [SingleDecodeType](../singledecodetype/) to the [MultiDecodeType](./). |
| [ContainsAll](./containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Check if this contains all types from barcode types. |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Is contain any of types |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Returns a value indicating whether this instance is equal to a specified [MultiDecodeType](./) value. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Returns a value indicating whether this decode types collection contains only specified [SingleDecodeType](../singledecodetype/) value. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returns a value indicating whether this instance is equal to a specified [MultiDecodeType](./) value. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](../basedecodetype/) value. |
| [Exclude](./exclude/)(System::SharedPtr\<SingleDecodeType\>) | Excludes [SingleDecodeType](../singledecodetype/) from the [MultiDecodeType](./) and returns new [MultiDecodeType](./) instance. |
| [get_GetSingleTypesCount](./get_getsingletypescount/)() | Returns a number of single types. |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [GetSingleTypes](./getsingletypes/)() | Represents a list of single types. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Initializes a new instance of the [MultiDecodeType](./) class. |
| [MultiDecodeType](./multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initializes a new instance of the [MultiDecodeType](./) class. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [ToString](./tostring/)() const override | Overridden method representing [MultiDecodeType](./) as a string. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Converts the string representation of a [MultiDecodeType](./) to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converts the string representation of a [SingleDecodeType](../singledecodetype/) to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Converts the string representation of a [BaseDecodeType](../basedecodetype/) to its instance, having determined the concrete type. A return value indicates whether the conversion succeeded or failed. |
## Remarks


This sample shows how to create compound MultiDecode types that combine [SingleDecodeType](../singledecodetype/) and MultiDecode types. 
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

## See Also

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
