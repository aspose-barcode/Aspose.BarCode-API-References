---
title: Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class
linktitle: SecondaryAndAdditionalData
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::SecondaryAndAdditionalData class. Class for storing HIBC LIC secondary and additional data in C++.'
type: docs
weight: 2400
url: /cpp/aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
## SecondaryAndAdditionalData class


Class for storing HIBC LIC secondary and additional data.

```cpp
class SecondaryAndAdditionalData : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Returns a value indicating whether this instance is equal to a specified [SecondaryAndAdditionalData](./) value. |
| [get_DateOfManufacture](./get_dateofmanufacture/)() const | Identifies date of manufacture. Date of manufacture can be set to DateTime.MinValue in order not to use this field. Default value: DateTime.MinValue |
| [get_ExpiryDate](./get_expirydate/)() const | Identifies expiry date. Will be used if ExpiryDateFormat is not set to None. |
| [get_ExpiryDateFormat](./get_expirydateformat/)() const | Identifies expiry date format. |
| [get_LotNumber](./get_lotnumber/)() | Identifies lot or batch number. Lot/batch number must be alphanumeric string with up to 18 sybmols length. . |
| [get_Quantity](./get_quantity/)() | Identifies quantity, must be integer value from 0 to 500. Quantity can be set to -1 in order not to use this field. Default value: -1 |
| [get_SerialNumber](./get_serialnumber/)() | Identifies serial number. Serial number must be alphanumeric string up to 18 sybmols length. |
| [GetHashCode](./gethashcode/)() const override | Returns the hash code for this instance. |
| [ParseFromString](./parsefromstring/)(System::String) | Instantiates secondary and additional supplemental data from string format according HIBC LIC specification. |
| [SecondaryAndAdditionalData](./secondaryandadditionaldata/)() |  |
| [set_DateOfManufacture](./set_dateofmanufacture/)(System::DateTime) | Identifies date of manufacture. Date of manufacture can be set to DateTime.MinValue in order not to use this field. Default value: DateTime.MinValue |
| [set_ExpiryDate](./set_expirydate/)(System::DateTime) | Identifies expiry date. Will be used if ExpiryDateFormat is not set to None. |
| [set_ExpiryDateFormat](./set_expirydateformat/)(HIBCLICDateFormat) | Identifies expiry date format. |
| [set_LotNumber](./set_lotnumber/)(System::String) | Identifies lot or batch number. Lot/batch number must be alphanumeric string with up to 18 sybmols length. . |
| [set_Quantity](./set_quantity/)(int32_t) | Identifies quantity, must be integer value from 0 to 500. Quantity can be set to -1 in order not to use this field. Default value: -1 |
| [set_SerialNumber](./set_serialnumber/)(System::String) | Identifies serial number. Serial number must be alphanumeric string up to 18 sybmols length. |
| [ToString](./tostring/)() const override | Converts data to string format according HIBC LIC specification. |
## See Also

* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
