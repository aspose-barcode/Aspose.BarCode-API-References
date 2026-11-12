---
title: "ComplexBarcodeGenerator"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for Node.js via Java API 参考"
description: "用于后端复杂条码的 ComplexBarcodeGenerator（例如。"
type: docs
weight: 280
url: /zh/nodejs/aspose.barcode/complexbarcodegenerator/
---

## ComplexBarcodeGenerator class

用于后端复杂条形码（例如 SwissQR）图像生成的 ComplexBarcodeGenerator。

```js
new ComplexBarcodeGenerator(complexCodetext)
```

创建 ComplexBarcodeGenerator 的实例。

| 参数 | 描述 |
| --- | --- |
| complexCodetext | 复杂代码文本 |

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

## 方法

| 名称 | 描述 |
| --- | --- |
| [generateBarCodeImage()](#generatebarcodeimage) | 根据当前设置生成复杂条码图像。 |
| [getParameters()](#getparameters) | 生成参数。 |
| [save(filePath, format)](#save) | 根据当前设置生成并保存复杂条码图像。 |

### generateBarCodeImage() {#generatebarcodeimage}

根据当前设置生成复杂条码图像。

**Returns:** Base64 presentation of image.

### getParameters() {#getparameters}

生成参数。

### save(filePath, format) {#save}

根据当前设置生成并保存复杂条码图像。

| 参数 | 描述 |
| --- | --- |
| filePath | 保存路径。 |
| 格式 | BarCodeImageFormat(PNG, BMP, JPEG, GIF) |
