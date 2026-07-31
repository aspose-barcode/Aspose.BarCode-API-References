---
title: "QrExtCodetextBuilder Class"
linktitle: "QrExtCodetextBuilder"
articleTitle: "QrExtCodetextBuilder"
second_title: "Aspose.BarCode for Node.js via Java"
description: "Extended codetext generator for 2D QR barcodes for ExtendedCodetext Mode of QREncodeMode Use Display2DText property of BarCodeBuilder to set visible text to ..."
type: docs
weight: 820
url: /nodejs/aspose.barcode/qrextcodetextbuilder/
---

## QrExtCodetextBuilder class

Extended codetext generator for 2D QR barcodes for ExtendedCodetext Mode of QREncodeMode Use Display2DText property of BarCodeBuilder to set visible text to removing managing characters.

```js
new QrExtCodetextBuilder()
```

**Example:**

```js
//Example how to generate FNC1 first position for Extended Mode
 //create codetext
 const lTextBuilder = new QrExtCodetextBuilder();
 lTextBuilder.addFNC1FirstPosition();
 lTextBuilder.addPlainCodetext("000%89%%0");
 lTextBuilder.addFNC1GroupSeparator();
 lTextBuilder.addPlainCodetext("12345&lt;FNC1&gt;");
 //generate codetext
 const lCodetext = lTextBuilder.getExtendedCodetext();
```

## Methods

| Name | Description |
| --- | --- |
| [addCodetextWithCompactionMode(mode, codetext)](./addcodetextwithcompactionmode/) | Adds codetext with the specified QR compaction mode to the extended codetext items. |
| [addFNC1FirstPosition()](./addfnc1firstposition/) | Adds FNC1 in first position to the extended codetext items |
| [addFNC1GroupSeparator()](./addfnc1groupseparator/) | Adds Group Separator (GS - '\\u001D') to the extended codetext items |
| [addFNC1SecondPosition(codetext)](./addfnc1secondposition/) | Adds FNC1 in second position to the extended codetext items |
| [clear()](./clear/) | Clears extended codetext items |
| [getExtendedCodetext()](./getextendedcodetext/) | Generates Extended codetext from the extended codetext list. |
