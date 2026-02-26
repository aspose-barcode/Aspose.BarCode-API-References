---
title: CustomerInformationInterpretingType Enum
linktitle: CustomerInformationInterpretingType
articleTitle: CustomerInformationInterpretingType
second_title: Aspose.BarCode for Node.js via Java
description: "Defines the interpreting type(C_TABLE or N_TABLE) of customer information for AustralianPost BarCode."
type: docs
weight: 1490
url: /nodejs/customerinformationinterpretingtype/
---
## CustomerInformationInterpretingType enumeration

Defines the interpreting type(C_TABLE or N_TABLE) of customer information for AustralianPost BarCode.

```javascript
public enum CustomerInformationInterpretingType
```

## Values

| Name | Value | Description |
| --- | :---: | --- |
| C_TABLE | `0` | Use C_TABLE to interpret the customer information. Allows A..Z, a..z, 1..9, space and # sing. let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678ABCde"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE); let image = generator.generateBarcodeImage(BarcodeImageFormat.PNG); let reader = new BarCodeReader(image, DecodeType.AUSTRALIA_POST); reader.setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode Type: " + result.getCodeType()); console.log("BarCode CodeText: " + result.getCodeText()); } |
| N_TABLE | `1` | Use N_TABLE to interpret the customer information. Allows digits. let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "59123456781234567"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.N_TABLE); let image = generator.generateBarcodeImage(BarcodeImageFormat.PNG); let reader = new BarCodeReader(image, DecodeType.AUSTRALIA_POST); reader.setCustomerInformationInterpretingType(CustomerInformationInterpretingType.N_TABLE); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode Type: " + result.getCodeType()); console.log("BarCode CodeText: " + result.getCodeText()); } |
| OTHER | `2` | Do not interpret the customer information. Allows 0, 1, 2 or 3 symbol only. let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "59123456780123012301230123"); generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.OTHER); let image = generator.generateBarcodeImage(BarcodeImageFormat.PNG); let reader = new BarCodeReader(image, DecodeType.AUSTRALIA_POST); reader.setCustomerInformationInterpretingType(CustomerInformationInterpretingType.OTHER)); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log("BarCode Type: " + result.getCodeType()); console.log("BarCode CodeText: " + result.getCodeText()); } |

## Examples

```javascript
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678ABCde");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
image = generator.generateBarCodeImage();
let reader = new BarCodeReader(image, DecodeType.AUSTRALIA_POST);
reader.setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode Type: " + result.getCodeType());
console.log("BarCode CodeText: " + result.getCodeText());
}
```

generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "59123456781234567");

```javascript
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.N_TABLE);
image = generator.generateBarCodeImage();
reader = new BarCodeReader(image, DecodeType.AUSTRALIA_POST);
reader.setCustomerInformationInterpretingType(CustomerInformationInterpretingType.N_TABLE);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode Type: " + result.getCodeType());
console.log("BarCode CodeText: " + result.getCodeText());
}
```

```javascript
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "59123456780123012301230123");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.OTHER);
image = generator.generateBarCodeImage();
let reader = new BarCodeReader(image, DecodeType.AUSTRALIA_POST);
reader.CustomerInformationInterpretingType = CustomerInformationInterpretingType.OTHER);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode Type: " + result.getCodeType());
console.log("BarCode CodeText: " + result.getCodeText());
}
```

### See Also

* assembly [Aspose.BarCode](../)

