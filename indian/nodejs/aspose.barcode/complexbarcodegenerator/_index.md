---
title: "ComplexBarcodeGenerator"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "बैकएंड जटिल बारकोड के लिए ComplexBarcodeGenerator (जैसे"
type: docs
weight: 280
url: /hi/nodejs/aspose.barcode/complexbarcodegenerator/
---

## ComplexBarcodeGenerator class

बैकएंड कॉम्प्लेक्स बारकोड (जैसे SwissQR) इमेज जनरेशन के लिए ComplexBarcodeGenerator।

```js
new ComplexBarcodeGenerator(complexCodetext)
```

ComplexBarcodeGenerator का एक उदाहरण बनाता है।

| पैरामीटर | विवरण |
| --- | --- |
| complexCodetext | जटिल कोडटेक्स्ट |

**Example:**

```js
This sample shows how to create and save a SwissQR image.
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

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [generateBarCodeImage()](#generatebarcodeimage) | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है। |
| [getParameters()](#getparameters) | उत्पादन पैरामीटर। |
| [save(filePath, format)](#save) | वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है और सहेजता है। |

### generateBarCodeImage() {#generatebarcodeimage}

वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है।

**Returns:** Base64 presentation of image.

### getParameters() {#getparameters}

उत्पादन पैरामीटर।

### save(filePath, format) {#save}

वर्तमान सेटिंग्स के तहत जटिल बारकोड छवि उत्पन्न करता है और सहेजता है।

| पैरामीटर | विवरण |
| --- | --- |
| filePath | सहेजने के लिए पथ। |
| फ़ॉर्मेट | BarCodeImageFormat(PNG, BMP, JPEG, GIF) |
