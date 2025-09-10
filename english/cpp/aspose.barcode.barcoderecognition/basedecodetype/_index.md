---
title: Aspose::BarCode::BarCodeRecognition::BaseDecodeType class
linktitle: BaseDecodeType
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::BaseDecodeType class. Base class for MultyDecodeType and SingleDecodeType in C++.'
type: docs
weight: 900
url: /cpp/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class


Base class for [MultyDecodeType](../multydecodetype/) and [SingleDecodeType](../singledecodetype/).

```cpp
class BaseDecodeType : public virtual System::IEquatable<System::SharedPtr<Aspose::BarCode::BarCodeRecognition::BaseDecodeType>>
```

## Methods

| Method | Description |
| --- | --- |
| virtual [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>\>\&) | Determines whether any of the given decode types is included into. |
| virtual [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) | Returns a value indicating whether this instance is equal to a specified [SingleDecodeType](../singledecodetype/) value. |
| virtual [Equals](./equals/)(System::SharedPtr\<MultyDecodeType\>) | Returns a value indicating whether this instance is equal to a specified [MultyDecodeType](../multydecodetype/) value. |
| [Equals](./equals/)(System::SharedPtr\<BaseDecodeType\>) override | Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](./) value. |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converts the string representation of a [SingleDecodeType](../singledecodetype/) to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultyDecodeType\>\&) | Converts the string representation of a [MultyDecodeType](../multydecodetype/) to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Converts the string representation of a [BaseDecodeType](./) to its instance, having determined the concrete type. A return value indicates whether the conversion succeeded or failed. |
## Remarks


This sample shows how to use [BaseDecodeType](./) with [SingleDecodeType](../singledecodetype/) and [MultyDecodeType](../multydecodetype/)
```cpp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultyDecodeType(DecodeType.Code128, DecodeType.Code39Standard, DecodeType.Code39Extended);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultyDecodeType(DecodeType.Code128, DecodeType.Code39Standard, DecodeType.Code39Extended)
```




## See Also

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
