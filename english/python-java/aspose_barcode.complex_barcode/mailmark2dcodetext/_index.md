---
title: "Mailmark2DCodetext Class"
linktitle: "Mailmark2DCodetext"
articleTitle: "Mailmark2DCodetext"
second_title: "Aspose.BarCode for Python via Java"
description: ""
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/mailmark2dcodetext/
---

## Mailmark2DCodetext class

**Module:** `aspose_barcode.complex_barcode.mailmark_2d_codetext`

**Inherits:** `IComplexCodetext`


## Constructors

| Name | Description |
| --- | --- |
| [__init__](./mailmark2dcodetext/) | Create default instance of Mailmark2DCodetext class. |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [barcode_type](./barcode_type/) | `EncodeTypes` | No | Reimplemented from IComplexCodetext. |
| [constructed_codetext](./constructed_codetext/) | `Optional[str]` | No | Reimplemented from IComplexCodetext. |
| [init_from_string](./init_from_string/) | `None` | No | Reimplemented from IComplexCodetext. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [class_](./class_/) | `Optional[str]` | Identifies the class of the item. Valid Values: “1” - 1C (Retail) “2” - 2C (Retail) “3” - Economy (Retail) “5” - Deffered (Retail) “8” - Premium (Network Access) “9” - Standard (Network Access) |
| [customer_content](./customer_content/) | `Optional[str]` | Optional space for use by customer. Max length by Type: Type 7: 6 characters Type 9: 45 characters Type 29: 25 characters |
| [customer_content_encode_mode](./customer_content_encode_mode/) | `DataMatrixEncodeMode` | Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.C40. |
| [data_matrix_type](./data_matrix_type/) | `Mailmark2DType` | 2D Mailmark Type defines size of Data Matrix barcode. |
| [destination_postcode_dps](./destination_postcode_dps/) | `Optional[str]` | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. Area (1 or 2 characters) District(1 or 2 characters) Sector(1 character) Unit(2 characters) DPS (2 characters). The Postcode and DPS must comply with a valid PAF® format. |
| [information_type_id](./information_type_id/) | `Optional[str]` | Identifies the Royal Mail Mailmark barcode payload for each product type. Valid Values: “0” - Domestic Sorted & Unsorted “A” - Online Postage “B” - Franking “C” - Consolidation |
| [item_id](./item_id/) | `int` | Every Mailmark barcode is required to carry an ID Max value: 99999999. |
| [return_to_sender_postcode](./return_to_sender_postcode/) | `Optional[str]` | Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format. |
| [rts_flag](./rts_flag/) | `Optional[str]` | Flag which indicates what level of Return to Sender service is being requested. |
| [supply_chain_id](./supply_chain_id/) | `int` | Identifies the unique group of customers involved in the mailing. Max value: 9999999. |
| [upu_country_id](./upu_country_id/) | `Optional[str]` | Identifies the UPU Country ID.Max length: 4 characters. |
| [version_id](./version_id/) | `Optional[str]` | Identifies the barcode version as relevant to each Information Type ID. Valid Values: Currently “1”. “0” & “2” to “9” and “A” to “Z” spare reserved for potential future use. |
