---
title: "ComplexBarcodeGenerator Class"
linktitle: "ComplexBarcodeGenerator"
articleTitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for Node.js via Java"
description: "ComplexBarcodeGenerator for backend complex barcode (e.g. SwissQR) images generation."
type: docs
weight: 30
url: /nodejs/complexbarcodegenerator/
---
## ComplexBarcodeGenerator class

ComplexBarcodeGenerator for backend complex barcode (e.g. SwissQR) images generation.

```javascript
public class ComplexBarcodeGenerator : joint.BaseJavaClass
```

## Constructors

| Name | Description |
| --- | --- |
| [ComplexBarcodeGenerator](./complexbarcodegenerator/#constructor)(*object*) | Creates an instance of ComplexBarcodeGenerator. |

## Methods

| Name | Description |
| --- | --- |
| [generateBarCodeImage](./generatebarcodeimage/)(*object*) | Generates complex barcode image under current settings. |
| [getParameters](./getparameters/) | Generation parameters. |
| [init](./init/) |  |
| [save](./save/)(*object, object*) | Generates and saves complex barcode image under current settings. |

## Fields

| Name | Description |
| --- | --- |
| [javaClassName](./javaclassname/) |  |
| [parameters](./parameters/) |  |

## Examples

This sample shows how to create and save a SwissQR image.

```javascript
let swissQRCodetext = new SwissQRCodetext(null);
swissQRCodetext.getBill().setAccount("Account");
swissQRCodetext.getBill().setBillInformation("BillInformation");
swissQRCodetext.getBill().setBillInformation("BillInformation");
swissQRCodetext.getBill().setAmount(1024);
swissQRCodetext.getBill().getCreditor().setName("Creditor.Name");
swissQRCodetext.getBill().getCreditor().setAddressLine1("Creditor.AddressLine1");
swissQRCodetext.getBill().getCreditor().setAddressLine2("Creditor.AddressLine2");
swissQRCodetext.getBill().getCreditor().setCountryCode("Nl");
swissQRCodetext.getBill().setUnstructuredMessage("UnstructuredMessage");
swissQRCodetext.getBill().setReference("Reference");
swissQRCodetext.getBill().setAlternativeSchemes([new AlternativeScheme("AlternativeSchemeInstruction1"),new AlternativeScheme("AlternativeSchemeInstruction2")]);
swissQRCodetext.getBill().setDebtor(new Address(null));
swissQRCodetext.getBill().getDebtor().setName("Debtor.Name");
swissQRCodetext.getBill().getDebtor().setAddressLine1("Debtor.AddressLine1");
swissQRCodetext.getBill().getDebtor().setAddressLine2("Debtor.AddressLine2");
swissQRCodetext.getBill().getDebtor().setCountryCode("Lux");
let cg = new ComplexBarcodeGenerator(swissQRCodetext);
let res = cg.generateBarCodeImage(BarcodeImageFormat.PNG);
```

### See Also

* assembly [Aspose.BarCode](../)

