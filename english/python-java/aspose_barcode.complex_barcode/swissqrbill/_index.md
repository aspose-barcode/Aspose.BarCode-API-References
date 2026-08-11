---
title: "SwissQRBill"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode for Python via Java"
description: "SwissQR bill data."
type: docs
weight: 10
url: /python-java/aspose_barcode.complex_barcode/swissqrbill/
---

## SwissQRBill class

**Module:** `aspose_barcode.complex_barcode.swiss_qr_bill`


SwissQR bill data.


## Constructors

| Name | Description |
| --- | --- |
| [__init__](#constructor) |  |

## Methods

| Name | Return Type | Static | Description |
| --- | --- | --- | --- |
| [__eq__](#__eq__) | `bool` | No | Determines whether the specified object is equal to the current object. |
| [__hash__](#__hash__) | `int` | No | Returns the hash code for the current instance. |
| [create_and_set_creditor_reference](#create_and_set_creditor_reference) | `None` | No | Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum. Whitespace is removed from the reference |

## Properties

| Name | Type | Description |
| --- | --- | --- |
| [account](#account) | `Optional[str]` | Gets the creditor's account number. Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein. Spaces are allowed in the account number. |
| [alternative_schemes](#alternative_schemes) | `List[AlternativeScheme]` | Gets the alternative payment schemes. A maximum of two schemes with parameters are allowed. |
| [amount](#amount) | `float` | Gets the payment amount. Valid values are between 0.01 and 999,999,999.99. |
| [bill_information](#bill_information) | `Optional[str]` | Gets the additional structured bill information. |
| [creditor](#creditor) | `Optional[Address]` | Gets the creditor address. |
| [currency](#currency) | `Optional[str]` | Gets the payment currency. Valid values are "CHF" and "EUR". |
| [debtor](#debtor) | `Optional[Address]` | Gets the debtor address. The debtor is optional. If it is omitted, both setting this field to None or setting an address with all None or empty values is ok. |
| [reference](#reference) | `Optional[str]` | Gets the creditor payment reference. The reference is mandatory for SwissQR IBANs, i.e.IBANs in the range CHxx30000xxxxxx through CHxx31999xxxxx. If specified, the reference must be either a valid SwissQR reference (corresponding to ISR reference form) or a valid creditor reference according to ISO 11649 ("RFxxxx"). Both may contain spaces for formatting. |
| [unstructured_message](#unstructured_message) | `Optional[str]` | Gets the additional unstructured message. |
| [version](#version) | `QrBillStandardVersion` | Gets the version of the SwissQR bill standard. |

### SwissQRBill Constructor {#constructor}

```python
__init__(self, _java_class)
```

| Parameter | Type | Description |
| --- | --- | --- |
| `_java_class` | `` |  |

### SwissQRBill.__eq__ {#__eq__}

```python
__eq__(self, SwissQRBill other) -> bool
```

Determines whether the specified object is equal to the current object.

| Parameter | Type | Description |
| --- | --- | --- |
| `other` | `SwissQRBill` |  |

**Return Type:** `bool` — True if the specified object is equal to the current object; otherwise, false.

### SwissQRBill.__hash__ {#__hash__}

```python
__hash__(self) -> int
```

Returns the hash code for the current instance.

**Return Type:** `int` — A hash code for the current object.

### SwissQRBill.create_and_set_creditor_reference {#create_and_set_creditor_reference}

```python
create_and_set_creditor_reference(self, str raw_reference)
```

Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 checksum. Whitespace is removed from the reference

| Parameter | Type | Description |
| --- | --- | --- |
| `raw_reference` | `str` |  |

### SwissQRBill.account {#account}

**Type:** `Optional[str]`

Gets the creditor's account number. Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein. Spaces are allowed in the account number.

**Returns:** The creditor account number.

Sets the creditor's account number. Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein. Spaces are allowed in the account number.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### SwissQRBill.alternative_schemes {#alternative_schemes}

**Type:** `List[AlternativeScheme]`

Gets the alternative payment schemes. A maximum of two schemes with parameters are allowed.

**Returns:** The alternative payment schemes.

Sets the alternative payment schemes. A maximum of two schemes with parameters are allowed.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `List[AlternativeScheme]` |  |

### SwissQRBill.amount {#amount}

**Type:** `float`

Gets the payment amount. Valid values are between 0.01 and 999,999,999.99.

**Returns:** The payment amount.

Sets the payment amount. Valid values are between 0.01 and 999,999,999.99.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `float` |  |

### SwissQRBill.bill_information {#bill_information}

**Type:** `Optional[str]`

Gets the additional structured bill information.

**Returns:** The structured bill information.

Sets the additional structured bill information.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### SwissQRBill.creditor {#creditor}

**Type:** `Optional[Address]`

Gets the creditor address.

**Returns:** The creditor address.

Sets the creditor address.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Address` |  |

### SwissQRBill.currency {#currency}

**Type:** `Optional[str]`

Gets the payment currency. Valid values are "CHF" and "EUR".

**Returns:** The payment currency.

Sets the payment currency. Valid values are "CHF" and "EUR".

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### SwissQRBill.debtor {#debtor}

**Type:** `Optional[Address]`

Gets the debtor address. The debtor is optional. If it is omitted, both setting this field to None or setting an address with all None or empty values is ok.

**Returns:** The debtor address.

Sets the debtor address. The debtor is optional. If it is omitted, both setting this field to None or setting an address with all None or empty values is ok.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `Address` |  |

### SwissQRBill.reference {#reference}

**Type:** `Optional[str]`

Gets the creditor payment reference. The reference is mandatory for SwissQR IBANs, i.e.IBANs in the range CHxx30000xxxxxx through CHxx31999xxxxx. If specified, the reference must be either a valid SwissQR reference (corresponding to ISR reference form) or a valid creditor reference according to ISO 11649 ("RFxxxx"). Both may contain spaces for formatting.

**Returns:** The creditor payment reference.

Sets the creditor payment reference. The reference is mandatory for SwissQR IBANs, i.e.IBANs in the range CHxx30000xxxxxx through CHxx31999xxxxx. If specified, the reference must be either a valid SwissQR reference (corresponding to ISR reference form) or a valid creditor reference according to ISO 11649 ("RFxxxx"). Both may contain spaces for formatting.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### SwissQRBill.unstructured_message {#unstructured_message}

**Type:** `Optional[str]`

Gets the additional unstructured message.

**Returns:** The unstructured message.

Sets the additional unstructured message.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `str` |  |

### SwissQRBill.version {#version}

**Type:** `QrBillStandardVersion`

Gets the version of the SwissQR bill standard.

**Returns:** The SwissQR bill standard version.

Sets the version of the SwissQR bill standard.

| Parameter | Type | Description |
| --- | --- | --- |
| `value` | `QrBillStandardVersion` |  |

