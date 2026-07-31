---
title: "SwissQRBill Class"
linktitle: "SwissQRBill"
articleTitle: "SwissQRBill"
second_title: "Aspose.BarCode for Node.js via Java"
description: "SwissQR bill data"
type: docs
weight: 920
url: /nodejs/aspose.barcode/swissqrbill/
---

## SwissQRBill class

SwissQR bill data

```js
new SwissQRBill()
```

## Methods

| Name | Description |
| --- | --- |
| [createAndSetCreditorReference(rawReference)](./createandsetcreditorreference/) | Creates and sets a ISO11649 creditor reference from a raw string by prefixing the String with "RF" and the modulo 97 che |
| [equals(obj)](./equals/) | Determines whether the specified object is equal to the current object. |
| [getAccount()](./getaccount/) | Gets the creditor's account number. Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein. Space |
| [getAlternativeSchemes()](./getalternativeschemes/) | Gets ors sets the alternative payment schemes. A maximum of two schemes with parameters are allowed. |
| [getAmount()](./getamount/) | Gets the payment amount. Valid values are between 0.01 and 999,999,999.99. |
| [getBillInformation()](./getbillinformation/) | Gets the additional structured bill information. |
| [getCreditor()](./getcreditor/) | Gets the creditor address. |
| [getCurrency()](./getcurrency/) | Gets the payment currency. Valid values are "CHF" and "EUR". |
| [getDebtor()](./getdebtor/) | Gets the debtor address. The debtor is optional. If it is omitted, both setting this field to null or setting an address |
| [getReference()](./getreference/) | Gets the creditor payment reference. The reference is mandatory for SwissQR IBANs, i.e.IBANs in the range CHxx30000xxxxx |
| [getUnstructuredMessage()](./getunstructuredmessage/) | Gets the additional unstructured message. |
| [getVersion()](./getversion/) | Gets the version of the SwissQR bill standard. |
| [hashCode()](./hashcode/) | Gets the hash code for this instance. |
| [setAccount(value:)](./setaccount/) | Sets the creditor's account number. Account numbers must be valid IBANs of a bank of Switzerland or Liechtenstein. Space |
| [setAlternativeSchemes(value:)](./setalternativeschemes/) | Gets or sets the alternative payment schemes. A maximum of two schemes with parameters are allowed. |
| [setAmount(value)](./setamount/) | Sets the payment amount. Valid values are between 0.01 and 999,999,999.99. |
| [setBillInformation(value:)](./setbillinformation/) | Sets the additional structured bill information. |
| [setCreditor(value:)](./setcreditor/) | Sets the creditor address. |
| [setCurrency(value)](./setcurrency/) | Sets the payment currency. |
| [setDebtor(value:)](./setdebtor/) | Sets the debtor address. The debtor is optional. If it is omitted, both setting this field to null or setting an address |
| [setReference(value)](./setreference/) | Sets the creditor payment reference. The reference is mandatory for SwissQR IBANs, i.e.IBANs in the range CHxx30000xxxxx |
| [setUnstructuredMessage(value:)](./setunstructuredmessage/) | Sets the additional unstructured message. |
| [setVersion(value)](./setversion/) | Sets the version of the SwissQR bill standard. |
