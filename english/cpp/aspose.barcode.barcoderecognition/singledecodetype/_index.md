---
title: Aspose::BarCode::BarCodeRecognition::SingleDecodeType class
linktitle: SingleDecodeType
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::SingleDecodeType class. Single decode type. See decode type to get instance in C++.'
type: docs
weight: 2900
url: /cpp/aspose.barcode.barcoderecognition/singledecodetype/
---
## SingleDecodeType class


Single decode type. See decode type to get instance.

```cpp
class SingleDecodeType : public Aspose::BarCode::BarCodeRecognition::BaseDecodeType,
                         public System::IEquatable<System::SharedPtr<Aspose::BarCode::BarCodeRecognition::SingleDecodeType>>
```

## Methods

| Method | Description |
| --- | --- |
| [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) override | Returns a value indicating whether this instance is included into the list specified. |
| [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) override | Returns a value indicating whether this instance is equal to a specified [SingleDecodeType](./) value. |
| [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) override | Returns a value indicating whether the specified [MultiDecodeType](../multidecodetype/) collection contains only this decode type. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returns a value indicating whether this instance is equal to a specified [SingleDecodeType](./) value. |
| [Equals](../basedecodetype/equals/)(System::SharedPtr\<BaseDecodeType\>) override | Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](../basedecodetype/) value. |
| [get_TypeIndex](./get_typeindex/)() | Gets an index of decode type |
| [get_TypeName](./get_typename/)() | Gets a name of decode type |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [GetString](./getstring/)() | Converts the instance of [SingleDecodeType](./) to its equivalent string representation. The string format is: "Index:-1; Name:None". |
| static [GetString](./getstring/)(System::SharedPtr\<SingleDecodeType\>) | Converts the instance of [SingleDecodeType](./) to its equivalent string representation. The string format is: "Index:-1; Name:None". |
| static [Parse](./parse/)(System::String) | Converts the string representation of the name of a [SingleDecodeType](./) to its instance. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [ToString](./tostring/)() const override | Returns the name of the given [SingleDecodeType](./) as a string. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converts the string representation of a [SingleDecodeType](./) to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Converts the string representation of a [MultiDecodeType](../multidecodetype/) to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](../basedecodetype/tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Converts the string representation of a [BaseDecodeType](../basedecodetype/) to its instance, having determined the concrete type. A return value indicates whether the conversion succeeded or failed. |
## Remarks


This sample shows how to get instance of single decode type. 
```cpp
[C#]
SingleDecodeType singleType = DecodeType.QR 

[VB.NET]
Dim singleType As SingleDecodeType 
singleType = DecodeType.QR
```

## See Also

* Class [BaseDecodeType](../basedecodetype/)
* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
