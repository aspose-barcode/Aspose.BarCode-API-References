---
title: Aspose::BarCode::BarCodeRecognition::BaseDecodeType class
linktitle: BaseDecodeType
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::BarCodeRecognition::BaseDecodeType class. Base class for MultiDecodeType and SingleDecodeType in C++.'
type: docs
weight: 900
url: /cpp/aspose.barcode.barcoderecognition/basedecodetype/
---
## BaseDecodeType class


Base class for [MultiDecodeType](../multidecodetype/) and [SingleDecodeType](../singledecodetype/).

```cpp
class BaseDecodeType : public virtual System::IEquatable<System::SharedPtr<Aspose::BarCode::BarCodeRecognition::BaseDecodeType>>
```

## Methods

| Method | Description |
| --- | --- |
| virtual [ContainsAny](./containsany/)(const System::ArrayPtr\<System::SharedPtr\<BaseDecodeType\>>\&) | Determines whether any of the given decode types is included into |
| virtual [Equals](./equals/)(System::SharedPtr\<SingleDecodeType\>) | Returns a value indicating whether this instance is equal to a specified [SingleDecodeType](../singledecodetype/) value. |
| virtual [Equals](./equals/)(System::SharedPtr\<MultiDecodeType\>) | Returns a value indicating whether this instance is equal to a specified [MultiDecodeType](../multidecodetype/) value. |
| [Equals](./equals/)(System::SharedPtr\<BaseDecodeType\>) override | Returns a value indicating whether this instance is equal to a specified [BaseDecodeType](./) value. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<SingleDecodeType\>\&) | Converts the string representation of a [SingleDecodeType](../singledecodetype/) to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<MultiDecodeType\>\&) | Converts the string representation of a [MultiDecodeType](../multidecodetype/) to its instance. A return value indicates whether the conversion succeeded or failed. |
| static [TryParse](./tryparse/)(System::String, System::SharedPtr\<BaseDecodeType\>\&) | Converts the string representation of a [BaseDecodeType](./) to its instance, having determined the concrete type. A return value indicates whether the conversion succeeded or failed. |
## Remarks


This sample shows how to use [BaseDecodeType](./) with [SingleDecodeType](../singledecodetype/) and [MultiDecodeType](../multidecodetype/)
```cpp
[C#]
BaseDecodeType decodeOne = DecodeType.Code128;
BaseDecodeType decodeTwo = new MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII);
[VB.NET]
Dim decodeOne As BaseDecodeType = DecodeType.Code128
Dim decodeTwo As BaseDecodeType = New MultiDecodeType(DecodeType.Code128, DecodeType.Code39, DecodeType.Code39FullASCII)
```

## See Also

* Namespace [Aspose::BarCode::BarCodeRecognition](../)
* Library [Aspose.BarCode for C++](../../)
