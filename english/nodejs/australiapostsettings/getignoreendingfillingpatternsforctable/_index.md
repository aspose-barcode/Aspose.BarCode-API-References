---
title: "AustraliaPostSettings.getIgnoreEndingFillingPatternsForCTable"
linktitle: "getIgnoreEndingFillingPatternsForCTable"
articleTitle: "getIgnoreEndingFillingPatternsForCTable"
second_title: "Aspose.BarCode for Node.js via Java"
description: "The flag which force AustraliaPost decoder to ignore last filling patterns in Customer Information Field during decoding as CTable method. CTable encoding me..."
type: docs
weight: 50
url: /nodejs/australiapostsettings/getignoreendingfillingpatternsforctable/
---
## getIgnoreEndingFillingPatternsForCTable() {#getignoreendingfillingpatternsforctable}

The flag which force AustraliaPost decoder to ignore last filling patterns in Customer Information Field during decoding as CTable method. CTable encoding method does not have any gaps in encoding table and sequnce "333" of filling paterns is decoded as letter "z".

```javascript
getIgnoreEndingFillingPatternsForCTable()
```

### Return Value

The

flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

## Examples

```javascript
let generator = new BarcodeGenerator(EncodeTypes.AUSTRALIA_POST, "5912345678AB");
generator.getParameters().getBarcode().getAustralianPost().setAustralianPostEncodingTable(CustomerInformationInterpretingType.C_TABLE);
let image = generator.generateBarCodeImage(BarcodeImageFormat.PNG);
let reader = new BarCodeReader(image, null, DecodeType.AUSTRALIA_POST);
reader.getBarcodeSettings().getAustraliaPost().setCustomerInformationInterpretingType(CustomerInformationInterpretingType.C_TABLE);
reader.getBarcodeSettings().getAustraliaPost().setIgnoreEndingFillingPatternsForCTable(true);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log("BarCode Type: " + result.getCodeType());
console.log("BarCode CodeText: " + result.getCodeText());
}
```

### See Also

* class [AustraliaPostSettings](../)
* assembly [Aspose.BarCode](../../)

