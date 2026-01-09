---
title: Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext class
linktitle: Mailmark2DCodetext
second_title: Aspose.BarCode for C++ API Reference
description: 'Aspose::BarCode::ComplexBarcode::Mailmark2DCodetext class. Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark code in C++.'
type: docs
weight: 1200
url: /cpp/aspose.barcode.complexbarcode/mailmark2dcodetext/
---
## Mailmark2DCodetext class


Class for encoding and decoding the text embedded in the Royal Mail 2D Mailmark code.

```cpp
class Mailmark2DCodetext : public Aspose::BarCode::ComplexBarcode::IComplexCodetext
```

## Methods

| Method | Description |
| --- | --- |
| [get_Class](./get_class/)() const | Identifies the class of the item. |
| [get_CustomerContent](./get_customercontent/)() const | Optional space for use by customer. |
| [get_CustomerContentEncodeMode](./get_customercontentencodemode/)() const | Encode mode of Datamatrix barcode. Default value: EncodeMode.C40. |
| [get_DataMatrixType](./get_datamatrixtype/)() const | 2D Mailmark Type defines size of Data Matrix barcode. |
| [get_DestinationPostCodeAndDPS](./get_destinationpostcodeanddps/)() const | Contains the Postcode of the Delivery [Address](../address/) with DPS If inland the Postcode/DP contains the following number of characters. Area (1 or 2 characters) District(1 or 2 characters) Sector(1 character) Unit(2 characters) DPS (2 characters). The Postcode and DPS must comply with a valid PAF® format. |
| [get_InformationTypeID](./get_informationtypeid/)() const | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [get_ItemID](./get_itemid/)() const | Identifies the unique item within the Supply Chain ID. Every Mailmark barcode is required to carry an ID so it can be uniquely identified for at least 90 days. Max value: 99999999. |
| [get_ReturnToSenderPostCode](./get_returntosenderpostcode/)() const | Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format. |
| [get_RTSFlag](./get_rtsflag/)() const | Flag which indicates what level of Return to Sender service is being requested. |
| [get_SupplyChainID](./get_supplychainid/)() const | Identifies the unique group of customers involved in the mailing. Max value: 9999999. |
| [get_UPUCountryID](./get_upucountryid/)() const | Identifies the UPU Country ID.Max length: 4 characters. |
| [get_VersionID](./get_versionid/)() const | Identifies the barcode version as relevant to each Information Type ID. |
| [GetBarcodeType](./getbarcodetype/)() override | Gets barcode type. |
| [GetConstructedCodetext](./getconstructedcodetext/)() override | Construct codetext from Mailmark data. |
| [InitFromString](./initfromstring/)(System::String) override | Initializes Mailmark data from constructed codetext. |
| [Mailmark2DCodetext](./mailmark2dcodetext/)() | Constructor. Create default instance of [Mailmark2DCodetext](./) class. |
| [set_Class](./set_class/)(System::String) | Identifies the class of the item. |
| [set_CustomerContent](./set_customercontent/)(System::String) | Optional space for use by customer. |
| [set_CustomerContentEncodeMode](./set_customercontentencodemode/)(Aspose::BarCode::Generation::DataMatrixEncodeMode) | Encode mode of Datamatrix barcode. Default value: EncodeMode.C40. |
| [set_DataMatrixType](./set_datamatrixtype/)(Mailmark2DType) | 2D Mailmark Type defines size of Data Matrix barcode. |
| [set_DestinationPostCodeAndDPS](./set_destinationpostcodeanddps/)(System::String) | Contains the Postcode of the Delivery [Address](../address/) with DPS If inland the Postcode/DP contains the following number of characters. Area (1 or 2 characters) District(1 or 2 characters) Sector(1 character) Unit(2 characters) DPS (2 characters). The Postcode and DPS must comply with a valid PAF® format. |
| [set_InformationTypeID](./set_informationtypeid/)(System::String) | Identifies the Royal Mail Mailmark barcode payload for each product type. |
| [set_ItemID](./set_itemid/)(int32_t) | Identifies the unique item within the Supply Chain ID. Every Mailmark barcode is required to carry an ID so it can be uniquely identified for at least 90 days. Max value: 99999999. |
| [set_ReturnToSenderPostCode](./set_returntosenderpostcode/)(System::String) | Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format. |
| [set_RTSFlag](./set_rtsflag/)(System::String) | Flag which indicates what level of Return to Sender service is being requested. |
| [set_SupplyChainID](./set_supplychainid/)(int32_t) | Identifies the unique group of customers involved in the mailing. Max value: 9999999. |
| [set_UPUCountryID](./set_upucountryid/)(System::String) | Identifies the UPU Country ID.Max length: 4 characters. |
| [set_VersionID](./set_versionid/)(System::String) | Identifies the barcode version as relevant to each Information Type ID. |
## See Also

* Class [IComplexCodetext](../icomplexcodetext/)
* Namespace [Aspose::BarCode::ComplexBarcode](../)
* Library [Aspose.BarCode for C++](../../)
