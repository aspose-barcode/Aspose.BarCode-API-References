---
title: "AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Riferimento API di Aspose.BarCode per Node.js via Java"
description: "Parametri di decodifica AustraliaPost."
type: docs
weight: 30
url: /it/nodejs/aspose.barcode/australiapostsettings/
---

## AustraliaPostSettings class

Parametri di decodifica AustraliaPost. Contiene parametri che influenzano i dati riconosciuti della simbologia AustraliaPost.

```js
new AustraliaPostSettings()
```

Costruttore AustraliaPostSettings

## Metodi

| Nome | Descrizione |
| --- | --- |
| [getCustomerInformationInterpretingType()](#getcustomerinformationinterpretingtype) | Ottiene il Tipo di Interpretazione per le Informazioni del Cliente di AustralianPost BarCode. DEFAULT è CustomerInformationInterpre |
| [getIgnoreEndingFillingPatternsForCTable()](#getignoreendingfillingpatternsforctable) | Il flag che forza il decoder AustraliaPost a ignorare gli ultimi pattern di riempimento nel campo Informazioni del Cliente durante la decodifica |
| [setCustomerInformationInterpretingType(value)](#setcustomerinformationinterpretingtype) | Imposta il Tipo di Interpretazione per le Informazioni del Cliente di AustralianPost BarCode. DEFAULT è CustomerInformationInterpre |
| [setIgnoreEndingFillingPatternsForCTable()](#setignoreendingfillingpatternsforctable) | Il flag che forza il decoder AustraliaPost a ignorare gli ultimi pattern di riempimento nel campo Informazioni del Cliente durante la decodifica |

### getCustomerInformationInterpretingType() {#getcustomerinformationinterpretingtype}

Ottiene il Tipo di Interpretazione per le Informazioni del Cliente di AustralianPost BarCode. DEFAULT è CustomerInformationInterpretingType.OTHER.

**Returns:** The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode

### getIgnoreEndingFillingPatternsForCTable() {#getignoreendingfillingpatternsforctable}

Il flag che forza il decoder AustraliaPost a ignorare gli ultimi pattern di riempimento nel campo Informazioni del Cliente durante la decodifica come metodo CTable. Il metodo di codifica CTable non presenta alcuna lacuna nella tabella di codifica e la sequenza "333" dei pattern di riempimento viene decodificata come la lettera "z".

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
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

### setCustomerInformationInterpretingType(value) {#setcustomerinformationinterpretingtype}

Imposta il Tipo di Interpretazione per le Informazioni del Cliente di AustralianPost BarCode. DEFAULT è CustomerInformationInterpretingType.OTHER.

| Parametro | Descrizione |
| --- | --- |
| valore | Il tipo di interpretazione (CTable, NTable o Altro) delle informazioni del cliente per AustralianPost BarCode |

### setIgnoreEndingFillingPatternsForCTable() {#setignoreendingfillingpatternsforctable}

Il flag che forza il decoder AustraliaPost a ignorare gli ultimi pattern di riempimento nel campo Informazioni del Cliente durante la decodifica come metodo CTable. Il metodo di codifica CTable non presenta alcuna lacuna nella tabella di codifica e la sequenza "333" dei pattern di riempimento viene decodificata come la lettera "z".

**Returns:** The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

**Example:**

```js
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
