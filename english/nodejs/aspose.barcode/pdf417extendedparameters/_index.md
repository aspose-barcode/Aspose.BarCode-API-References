---
title: "Pdf417ExtendedParameters Class"
linktitle: "Pdf417ExtendedParameters"
articleTitle: "Pdf417ExtendedParameters"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Stores a MacroPdf417 metadata information of recognized barcode"
type: docs
weight: 760
url: /nodejs/aspose.barcode/pdf417extendedparameters/
---

## Pdf417ExtendedParameters class

Stores a MacroPdf417 metadata information of recognized barcode

```js
new Pdf417ExtendedParameters()
```

**Example:**

```js
//This sample shows how to get Macro Pdf417 metadata
let generator = new BarcodeGenerator(EncodeTypes.MacroPdf417, "12345");
generator.getParameters().getBarcode().getPdf417().setPdf417MacroFileID(10);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentsCount(2);
generator.getParameters().getBarcode().getPdf417().setPdf417MacroSegmentID(1);
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  DecodeType.MACRO_PDF_417);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
    let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
    console.log("Macro Pdf417 FileID: " + result.getExtended().getPdf417().getMacroPdf417FileID());
    console.log("Macro Pdf417 Segments: " + result.getExtended().getPdf417().getMacroPdf417SegmentsCount());
    console.log("Macro Pdf417 SegmentID: " + result.getExtended().getPdf417().getMacroPdf417SegmentID());
}
```

## Methods

| Name | Description |
| --- | --- |
| [equals(obj)](./equals/) | Returns a value indicating whether this instance is equal to a specified Pdf417ExtendedParameters value. |
| [getMacroPdf417Addressee()](./getmacropdf417addressee/) | Macro PDF417 addressee name (optional). |
| [getMacroPdf417Checksum()](./getmacropdf417checksum/) | Macro PDF417 checksum (optional). |
| [getMacroPdf417FileID()](./getmacropdf417fileid/) | Gets the file ID of the barcode, only available with MacroPdf417.Value: The file ID for MacroPdf417 |
| [getMacroPdf417FileName()](./getmacropdf417filename/) | Macro PDF417 file name (optional). |
| [getMacroPdf417FileSize()](./getmacropdf417filesize/) | Macro PDF417 file size (optional). |
| [getMacroPdf417SegmentID()](./getmacropdf417segmentid/) | Gets the segment ID of the barcode,only available with MacroPdf417.Value: The segment ID of the barcode. |
| [getMacroPdf417SegmentsCount()](./getmacropdf417segmentscount/) | Gets macro pdf417 barcode segments count. Default value is -1.Value: Segments count. |
| [getMacroPdf417Sender()](./getmacropdf417sender/) | Macro PDF417 sender name (optional). |
| [getMacroPdf417Terminator()](./getmacropdf417terminator/) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [getMacroPdf417TimeStamp()](./getmacropdf417timestamp/) | Macro PDF417 time stamp (optional). |
| [hashCode()](./hashcode/) | Returns the hash code for this instance. |
| [isCode128Emulation()](./iscode128emulation/) | Flag that indicates that the MicroPdf417 barcode encoded with 908, 909, 910 or 911 Code 128 emulation codewords. |
| [isLinked()](./islinked/) | Flag that indicates that the barcode must be linked to 1D barcode. Value: Linkage flag |
| [isReaderInitialization()](./isreaderinitialization/) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. |
| [toString()](./tostring/) | Returns a human-readable string representation of this Pdf417ExtendedParameters. |
