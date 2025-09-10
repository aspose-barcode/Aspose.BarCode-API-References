---
title: Aspose::BarCode::ComplexBarcode::MailmarkCodetext class
linktitle: MailmarkCodetext
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::MailmarkCodetext class. Class for encoding and decoding the text embedded in the 4-state Royal Mailmark code in C++.'
type: docs
weight: 1300
url: /cpp/aspose.barcode.complexbarcode/mailmarkcodetext/
---
## MailmarkCodetext class


Class for encoding and decoding the text embedded in the 4-state Royal Mailmark code.

```cpp
class MailmarkCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Description |
| --- | --- |
| [get_Class](./get_class/)() const | "0" - Null or Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Retail) "6" - Air (Retail) (for potential future use) "7" - Surface (Retail) (for potential future use) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [get_DestinationPostCodePlusDPS](./get_destinationpostcodeplusdps/)() const | The PC and DP must comply with a PAF format. Nine character string denoting international "XY11     " (note the 5 trailing spaces) or a pattern of characters denoting a domestic sorting code. A domestic sorting code consists of an outward postcode, an inward postcode, and a Delivery Point Suffix. |
| [get_Format](./get_format/)() const | "0" – Null or Test "1" – Letter "2" – Large Letter |
| [get_ItemID](./get_itemid/)() const | Maximum value is 99999999. |
| [get_SupplychainID](./get_supplychainid/)() const | Maximum values are 99 for Barcode C and 999999 for Barcode L. |
| [get_VersionID](./get_versionid/)() const | Currently "1" – For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use) |
| [GetBarcodeType](./getbarcodetype/)() override | Gets barcode type. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construct codetext from Mailmark data. |
| [InitFromString](./initfromstring/)(System::String) override | Initializes Mailmark data from constructed codetext. |
| [MailmarkCodetext](./mailmarkcodetext/)() | Initializes a new instance of the [MailmarkCodetext](./) class. |
| [set_Class](./set_class/)(System::String) | "0" - Null or Test "1" - 1C (Retail) "2" - 2C (Retail) "3" - 3C (Retail) "4" - Premium (RetailPublishing Mail) (for potential future use) "5" - Deferred (Retail) "6" - Air (Retail) (for potential future use) "7" - Surface (Retail) (for potential future use) "8" - Premium (Network Access) "9" - Standard (Network Access) |
| [set_DestinationPostCodePlusDPS](./set_destinationpostcodeplusdps/)(System::String) | The PC and DP must comply with a PAF format. Nine character string denoting international "XY11     " (note the 5 trailing spaces) or a pattern of characters denoting a domestic sorting code. A domestic sorting code consists of an outward postcode, an inward postcode, and a Delivery Point Suffix. |
| [set_Format](./set_format/)(int32_t) | "0" – Null or Test "1" – Letter "2" – Large Letter |
| [set_ItemID](./set_itemid/)(int32_t) | Maximum value is 99999999. |
| [set_SupplychainID](./set_supplychainid/)(int32_t) | Maximum values are 99 for Barcode C and 999999 for Barcode L. |
| [set_VersionID](./set_versionid/)(int32_t) | Currently "1" – For Mailmark barcode (0 and 2 to 9 and A to Z spare for future use) |
## See Also

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
