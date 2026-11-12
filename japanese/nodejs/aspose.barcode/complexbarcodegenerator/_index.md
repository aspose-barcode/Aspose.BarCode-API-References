---
title: "ComplexBarcodeGenerator"
linktitle: "ComplexBarcodeGenerator"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "バックエンドの複合バーコード用 ComplexBarcodeGenerator (例:"
type: docs
weight: 280
url: /ja/nodejs/aspose.barcode/complexbarcodegenerator/
---

## ComplexBarcodeGenerator class

バックエンドの複合バーコード（例: SwissQR）画像生成のための ComplexBarcodeGenerator。

```js
new ComplexBarcodeGenerator(complexCodetext)
```

ComplexBarcodeGenerator のインスタンスを作成します。

| パラメータ | 説明 |
| --- | --- |
| complexCodetext | 複合コードテキスト |

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

## メソッド

| 名前 | 説明 |
| --- | --- |
| [generateBarCodeImage()](#generatebarcodeimage) | 現在の設定で複合バーコード画像を生成します。 |
| [getParameters()](#getparameters) | 生成パラメータ。 |
| [save(filePath, format)](#save) | 現在の設定で複合バーコード画像を生成し、保存します。 |

### generateBarCodeImage() {#generatebarcodeimage}

現在の設定で複合バーコード画像を生成します。

**Returns:** Base64 presentation of image.

### getParameters() {#getparameters}

生成パラメータ。

### save(filePath, format) {#save}

現在の設定で複合バーコード画像を生成し、保存します。

| パラメータ | 説明 |
| --- | --- |
| filePath | 保存先のパス。 |
| フォーマット | BarCodeImageFormat(PNG, BMP, JPEG, GIF) |
