---
title: Aspose::BarCode::BarCodeRecognition::MultyDecodeType class
linktitle: MultyDecodeType
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::MultyDecodeType class. Composite decode type in C++.'
type: docs
weight: 2300
url: /cpp/aspose.barcode.barcoderecognition/multydecodetype/
---
## MultyDecodeType class


Composite decode type.

```cpp
class MultyDecodeType : public Aspose::BarCode::BarCodeRecognition::MultiDecodeType
```

## Methods

| Method | Description |
| --- | --- |
| [Add](../multidecodetype/add/)(System::SharedPtr\<SingleDecodeType\>) | Adds one more [SingleDecodeType](../singledecodetype/) to the [MultiDecodeType](../multidecodetype/). |
| [ContainsAll](../multidecodetype/containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Check if this contains all types from barcode types. |
| [ContainsAny](../multidecodetype/containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Is contain any of types |
| [Equals](../multidecodetype/equals/)(System::SharedPtr\<MultiDecodeType\>) override | Returns a value indicating whether this instance is equal to a specified [MultiDecodeType](../multidecodetype/) value. |
| [Equals](../multidecodetype/equals/)(System::SharedPtr\<SingleDecodeType\>) override | Returns a value indicating whether this decode types collection contains only specified [SingleDecodeType](../singledecodetype/) value. |
| [Equals](../multidecodetype/equals/)(System::SharedPtr\<System::Object\>) override | Returns a value indicating whether this instance is equal to a specified [MultiDecodeType](../multidecodetype/) value. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](../basedecodetype/) value. |
| [Exclude](../multidecodetype/exclude/)(System::SharedPtr\<SingleDecodeType\>) | Excludes [SingleDecodeType](../singledecodetype/) from the [MultiDecodeType](../multidecodetype/) and returns new [MultiDecodeType](../multidecodetype/) instance. |
| [get_GetSingleTypesCount](../multidecodetype/get_getsingletypescount/)() | Returns a number of single types. |
| [GetHashCode](../multidecodetype/gethashcode/)() const override | Returns the hash code for this instance. |
| [GetSingleTypes](../multidecodetype/getsingletypes/)() | Represents a list of single types. |
| [MultiDecodeType](../multidecodetype/multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Initializes a new instance of the [MultiDecodeType](../multidecodetype/) class. |
| [MultiDecodeType](../multidecodetype/multidecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initializes a new instance of the [MultiDecodeType](../multidecodetype/) class. |
| [MultyDecodeType](./multydecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>>\&) | Initializes a new instance of the [MultyDecodeType](./) class. |
| [MultyDecodeType](./multydecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Initializes a new instance of the [MultyDecodeType](./) class. |
| [SetTemplateWeakPtr](../multidecodetype/settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [ToString](../multidecodetype/tostring/)() const override | Overridden method representing [MultiDecodeType](../multidecodetype/) as a string. |
| static [TryParse](../multidecodetype/tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Converts the string representation of a [MultiDecodeType](../multidecodetype/) to its instance. A return value indicates whether the conversion succeeded or failed. |
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

* Class [MultiDecodeType](../multidecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
