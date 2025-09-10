---
title: Aspose::BarCode::BarCodeRecognition::MultyDecodeType class
linktitle: MultyDecodeType
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::MultyDecodeType class. Composite decode type in C++.'
type: docs
weight: 2000
url: /cpp/aspose.barcode.barcoderecognition/multydecodetype/
---
## MultyDecodeType class


Composite decode type.

```cpp
class MultyDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                        public System::IEquatable<System::SharedPtr<Aspose::BarCode::BarCodeRecognition::MultyDecodeType>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<SingleDecodeType\>) | Adds one more [SingleDecodeType](../singledecodetype/) to the [MultyDecodeType](./). |
| [ContainsAll](./containsall/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>\>\&) | Check if this contains all types from barcode types. |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>\>\&) override | Is contain any of types. |
| [Equals](./equals/)(System::SharedPtr\<MultyDecodeType\>) override | Returns a value indicating whether this instance is equal to a specified [MultyDecodeType](./) value. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returns a value indicating whether this instance is equal to a specified [MultyDecodeType](./) value. |
| virtual [Equals](../basedecodetype/equals/)(System::SharedPtr\<SingleDecodeType\>) | Returns a value indicating whether this instance is equal to a specified [SingleDecodeType](../singledecodetype/) value. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](../basedecodetype/) value. |
| [Exclude](./exclude/)(System::SharedPtr\<SingleDecodeType\>) | Excludes [SingleDecodeType](../singledecodetype/) from the [MultyDecodeType](./) and returns new [MultyDecodeType](./) instance. |
| [get_GetSingleTypesCount](./get_getsingletypescount/)() | Returns a number of single types. |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [GetSingleTypes](./getsingletypes/)() | Represents a list of single types. |
| [MultyDecodeType](./multydecodetype/)(const System::ArrayPtr\<System::SharedPtr\<SingleDecodeType\>\>\&) | Initializes a new instance of the [MultyDecodeType](./) class. |
| [MultyDecodeType](./multydecodetype/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>\>\&) | Initializes a new instance of the [MultyDecodeType](./) class. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [ToString](./tostring/)() const override | Overridden method representing [MultyDecodeType](./) as a string. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultyDecodeType\>\&) | Converts the string representation of a [MultyDecodeType](./) to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converts the string representation of a [SingleDecodeType](../singledecodetype/) to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Converts the string representation of a [BaseDecodeType](../basedecodetype/) to its instance, having determined the concrete type. A return value indicates whether the conversion succeeded or failed. |
## Remarks


This sample shows how to create compound MultyDecode types that combine [SingleDecodeType](../singledecodetype/) and MultiDecode types. 
```cpp
[C#]
MultyDecodeType types1 = new MultyDecodeType(DecodeType.QR, DecodeType.DataMatrix);
MultyDecodeType types2 = new MultyDecodeType(types1, DecodeType.Code128, DecodeType.Code39Standard);
[VB.NET]
Dim multyType1 As MultyDecodeType 
multyType1 = New MultyDecodeType(DecodeType.QR, DecodeType.DataMatrix)
Dim multyType2 As MultyDecodeType
multyType2 = New MultyDecodeType(multyType1, DecodeType.Code128, DecodeType.Code39Standard)
```

## See Also

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
