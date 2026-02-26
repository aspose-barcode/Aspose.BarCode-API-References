---
title: BarcodeSettings.getChecksumValidation
linktitle: getChecksumValidation
articleTitle: getChecksumValidation
second_title: Aspose.BarCode for Node.js via Java
description: Enable checksum validation during recognition for 1D and Postal barcodes. Default is treated as Yes for symbologies which must contain checksum, as No where checksum only possible. Checksum never used: Codabar, PatchCode, Pharmacode, DataLogic2of5 Checksum is possible: Code39 Standard/Extended...
type: docs
weight: 40
url: /nodejs/barcodesettings/getchecksumvalidation/
---
## getChecksumValidation() {#getchecksumvalidation}

Enable checksum validation during recognition for 1D and Postal barcodes. Default is treated as Yes for symbologies which must contain checksum, as No where checksum only possible. Checksum never used: Codabar, PatchCode, Pharmacode, DataLogic2of5 Checksum is possible: Code39 Standard/Extended, Standard2of5, Interleaved2of5, ItalianPost25, Matrix2of5, MSI, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN Checksum always used: Rest symbologies

```javascript
getChecksumValidation()
```

### Return Value

Enable

checksum validation during recognition for 1D and Postal barcodes.

## Examples

```javascript
let generator = new BarcodeGenerator(EncodeTypes.EAN_13, "1234567890128");
generator.save("c:/test.png", BarcodeImageFormat.PNG);
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum disabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.OFF);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log ("BarCode CodeText: " + result.getCodeText());
console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

```javascript
let reader = new BarCodeReader("c:/test.png", DecodeType.EAN_13);
//checksum enabled
reader.getBarcodeSettings().setChecksumValidation(ChecksumValidation.ON);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
let result = results[i];
console.log ("BarCode CodeText: " + result.CodeText);
console.log ("BarCode Value: " + result.getExtended().getOneD().getValue());
console.log ("BarCode Checksum: " + result.getExtended().getOneD().getCheckSum());
}
```

### See Also

* class [BarcodeSettings](../)
* assembly [Aspose.BarCode](../../)

