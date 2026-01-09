---
title: Aspose::BarCode::ComplexBarcode::PrimaryData class
linktitle: PrimaryData
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::PrimaryData class. Class for storing HIBC LIC primary data in C++.'
type: docs
weight: 2300
url: /cpp/aspose.barcode.complexbarcode/primarydata/
---
## PrimaryData class


Class for storing HIBC LIC primary data.

```cpp
class PrimaryData : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returns a value indicating whether this instance is equal to a specified [PrimaryData](./) value. |
| [get_LabelerIdentificationCode](./get_labeleridentificationcode/)() | Identifies date of labeler identification code. Labeler identification code must be 4 symbols alphanumeric string, with first character always being alphabetic. |
| [get_ProductOrCatalogNumber](./get_productorcatalognumber/)() | Identifies product or catalog number. Product or catalog number must be alphanumeric string up to 18 sybmols length. |
| [get_UnitOfMeasureID](./get_unitofmeasureid/)() | Identifies unit of measure ID. Unit of measure ID must be integer value from 0 to 9. |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [ParseFromString](./parsefromstring/)(System::String) | Instantiates primary data from string format according HIBC LIC specification. |
| [PrimaryData](./primarydata/)() |  |
| [set_LabelerIdentificationCode](./set_labeleridentificationcode/)(System::String) | Identifies date of labeler identification code. Labeler identification code must be 4 symbols alphanumeric string, with first character always being alphabetic. |
| [set_ProductOrCatalogNumber](./set_productorcatalognumber/)(System::String) | Identifies product or catalog number. Product or catalog number must be alphanumeric string up to 18 sybmols length. |
| [set_UnitOfMeasureID](./set_unitofmeasureid/)(int32_t) | Identifies unit of measure ID. Unit of measure ID must be integer value from 0 to 9. |
| [ToString](./tostring/)() const override | Converts data to string format according HIBC LIC specification. |
## See Also

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
