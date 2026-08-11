---
title: "Mailmark2DCodetext"
linktitle: "Mailmark2DCodetext"
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
| [__init__](#constructor) | Create default instance of Mailmark2DCodetext class. |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [barcode_type](#barcode_type) | `EncodeTypes` | No | Reimplemented from IComplexCodetext. |
| [constructed_codetext](#constructed_codetext) | `Optional[str]` | No | Reimplemented from IComplexCodetext. |
| [init_from_string](#init_from_string) | `None` | No | Reimplemented from IComplexCodetext. |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [class_](#class_) | `Optional[str]` | Identifies the class of the item. Valid Values: “1” - 1C (Retail) “2” - 2C (Retail) “3” - Economy (Retail) “5” - Deffered (Retail) “8” - Premium (Network Access) “9” - Standard (Network Access) |
| [customer_content](#customer_content) | `Optional[str]` | Optional space for use by customer. Max length by Type: Type 7: 6 characters Type 9: 45 characters Type 29: 25 characters |
| [customer_content_encode_mode](#customer_content_encode_mode) | `DataMatrixEncodeMode` | Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.C40. |
| [data_matrix_type](#data_matrix_type) | `Mailmark2DType` | 2D Mailmark Type defines size of Data Matrix barcode. |
| [destination_postcode_dps](#destination_postcode_dps) | `Optional[str]` | Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. Area (1 or 2 characters) District(1 or 2 characters) Sector(1 character) Unit(2 characters) DPS (2 characters). The Postcode and DPS must comply with a valid PAF® format. |
| [information_type_id](#information_type_id) | `Optional[str]` | Identifies the Royal Mail Mailmark barcode payload for each product type. Valid Values: “0” - Domestic Sorted & Unsorted “A” - Online Postage “B” - Franking “C” - Consolidation |
| [item_id](#item_id) | `int` | Every Mailmark barcode is required to carry an ID Max value: 99999999. |
| [return_to_sender_postcode](#return_to_sender_postcode) | `Optional[str]` | Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format. |
| [rts_flag](#rts_flag) | `Optional[str]` | Flag which indicates what level of Return to Sender service is being requested. |
| [supply_chain_id](#supply_chain_id) | `int` | Identifies the unique group of customers involved in the mailing. Max value: 9999999. |
| [upu_country_id](#upu_country_id) | `Optional[str]` | Identifies the UPU Country ID.Max length: 4 characters. |
| [version_id](#version_id) | `Optional[str]` | Identifies the barcode version as relevant to each Information Type ID. Valid Values: Currently “1”. “0” & “2” to “9” and “A” to “Z” spare reserved for potential future use. |

### Mailmark2DCodetext Constructor {#constructor}

```python
__init__(self)
```

Create default instance of Mailmark2DCodetext class.

### Mailmark2DCodetext.barcode_type {#barcode_type}

```python
barcode_type(self) -> EncodeTypes
```

Reimplemented from IComplexCodetext.

**Return Type:** `EncodeTypes`

### Mailmark2DCodetext.constructed_codetext {#constructed_codetext}

```python
constructed_codetext(self) -> Optional[str]
```

Reimplemented from IComplexCodetext.

**Return Type:** `Optional[str]`

### Mailmark2DCodetext.init_from_string {#init_from_string}

```python
init_from_string(self, str constructed_codetext)
```

Reimplemented from IComplexCodetext.

| Parameter | Type | Description |
| --- | --- | --- |
| `constructed_codetext` | `str` |  |

### Mailmark2DCodetext.class_ {#class_}

**Type:** `Optional[str]`

Identifies the class of the item. Valid Values: “1” - 1C (Retail) “2” - 2C (Retail) “3” - Economy (Retail) “5” - Deffered (Retail) “8” - Premium (Network Access) “9” - Standard (Network Access)

**Returns:** class of the item

Identifies the class of the item.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` | Valid Values: “1” - 1C (Retail) “2” - 2C (Retail) “3” - Economy (Retail) “5” - Deffered (Retail) “8” - Premium (Network Access) “9” - Standard (Network Access) |

### Mailmark2DCodetext.customer_content {#customer_content}

**Type:** `Optional[str]`

Optional space for use by customer. Max length by Type: Type 7: 6 characters Type 9: 45 characters Type 29: 25 characters

**Returns:** Customer content

Optional space for use by customer. Max length by Type: Type 7: 6 characters Type 9: 45 characters Type 29: 25 characters

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` | Customer content |

### Mailmark2DCodetext.customer_content_encode_mode {#customer_content_encode_mode}

**Type:** `DataMatrixEncodeMode`

Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.C40.

**Returns:** Encode mode of Datamatrix barcode.

Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.C40.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `DataMatrixEncodeMode` |  |

### Mailmark2DCodetext.data_matrix_type {#data_matrix_type}

**Type:** `Mailmark2DType`

2D Mailmark Type defines size of Data Matrix barcode.

**Returns:** Size of Data Matrix barcode

2D Mailmark Type defines size of Data Matrix barcode.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Mailmark2DType` |  |

### Mailmark2DCodetext.destination_postcode_dps {#destination_postcode_dps}

**Type:** `Optional[str]`

Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. Area (1 or 2 characters) District(1 or 2 characters) Sector(1 character) Unit(2 characters) DPS (2 characters). The Postcode and DPS must comply with a valid PAF® format.

**Returns:** the Postcode of the Delivery Address with DPS

Contains the Postcode of the Delivery Address with DPS If inland the Postcode/DP contains the following number of characters. Area (1 or 2 characters) District(1 or 2 characters) Sector(1 character) Unit(2 characters) DPS (2 characters). The Postcode and DPS must comply with a valid PAF® format.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### Mailmark2DCodetext.information_type_id {#information_type_id}

**Type:** `Optional[str]`

Identifies the Royal Mail Mailmark barcode payload for each product type. Valid Values: “0” - Domestic Sorted & Unsorted “A” - Online Postage “B” - Franking “C” - Consolidation

**Returns:** Information type ID

Identifies the Royal Mail Mailmark barcode payload for each product type. Valid Values: “0” - Domestic Sorted & Unsorted “A” - Online Postage “B” - Franking “C” - Consolidation

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` | Information type ID |

### Mailmark2DCodetext.item_id {#item_id}

**Type:** `int`

Every Mailmark barcode is required to carry an ID Max value: 99999999.

**Returns:** item within the Supply Chain ID

Identifies the unique item within the Supply Chain ID. Every Mailmark barcode is required to carry an ID Max value: 99999999.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### Mailmark2DCodetext.return_to_sender_postcode {#return_to_sender_postcode}

**Type:** `Optional[str]`

Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format.

**Returns:** Return to Sender Post Code but no DPS

Contains the Return to Sender Post Code but no DPS. The PC(without DPS) must comply with a PAF® format.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### Mailmark2DCodetext.rts_flag {#rts_flag}

**Type:** `Optional[str]`

Flag which indicates what level of Return to Sender service is being requested.

**Returns:** RTS Flag

Flag which indicates what level of Return to Sender service is being requested.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### Mailmark2DCodetext.supply_chain_id {#supply_chain_id}

**Type:** `int`

Identifies the unique group of customers involved in the mailing. Max value: 9999999.

**Returns:** Supply chain ID

Identifies the unique group of customers involved in the mailing. Max value: 9999999. @param:: value: Supply chain ID

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `int` |  |

### Mailmark2DCodetext.upu_country_id {#upu_country_id}

**Type:** `Optional[str]`

Identifies the UPU Country ID.Max length: 4 characters.

**Returns:** Country ID

Identifies the UPU Country ID.Max length: 4 characters.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` | Country ID |

### Mailmark2DCodetext.version_id {#version_id}

**Type:** `Optional[str]`

Identifies the barcode version as relevant to each Information Type ID. Valid Values: Currently “1”. “0” & “2” to “9” and “A” to “Z” spare reserved for potential future use.

**Returns:** Version ID

Identifies the barcode version as relevant to each Information Type ID. Valid Values: Currently “1”. “0” & “2” to “9” and “A” to “Z” spare reserved for potential future use.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` | Version ID |

