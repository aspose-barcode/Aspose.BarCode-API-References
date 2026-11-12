---
title: "AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode для Node.js через Java справка API"
description: "Параметры декодирования AustraliaPost."
type: docs
weight: 30
url: /ru/nodejs/aspose.barcode/australiapostsettings/
---

## AustraliaPostSettings class

Параметры декодирования AustraliaPost. Содержит параметры, влияющие на распознанные данные символогии AustraliaPost.

```js
new AustraliaPostSettings()
```

Конструктор AustraliaPostSettings

## Методы

| Имя | Описание |
| --- | --- |
| [getCustomerInformationInterpretingType()](#getcustomerinformationinterpretingtype) | Получает тип интерпретации для клиентской информации AustralianPost BarCode. По умолчанию — CustomerInformationInterpre |
| [getIgnoreEndingFillingPatternsForCTable()](#getignoreendingfillingpatternsforctable) | Флаг, заставляющий декодер AustraliaPost игнорировать последние шаблоны заполнения в поле клиентской информации при декодировании |
| [setCustomerInformationInterpretingType(value)](#setcustomerinformationinterpretingtype) | Устанавливает тип интерпретации для клиентской информации AustralianPost BarCode. По умолчанию — CustomerInformationInterpre |
| [setIgnoreEndingFillingPatternsForCTable()](#setignoreendingfillingpatternsforctable) | Флаг, заставляющий декодер AustraliaPost игнорировать последние шаблоны заполнения в поле клиентской информации при декодировании |

### getCustomerInformationInterpretingType() {#getcustomerinformationinterpretingtype}

Получает тип интерпретации для клиентской информации AustralianPost BarCode. По умолчанию — CustomerInformationInterpretingType.OTHER.

**Returns:** The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode

### getIgnoreEndingFillingPatternsForCTable() {#getignoreendingfillingpatternsforctable}

Флаг, заставляющий декодер AustraliaPost игнорировать последние шаблоны заполнения в поле клиентской информации при декодировании методом CTable. Метод кодирования CTable не имеет пробелов в таблице кодов, и последовательность "333" шаблонов заполнения декодируется как буква "z".

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

Устанавливает тип интерпретации для клиентской информации AustralianPost BarCode. По умолчанию — CustomerInformationInterpretingType.OTHER.

| Параметр | Описание |
| --- | --- |
| значение | Тип интерпретации (CTable, NTable или Other) клиентской информации для AustralianPost BarCode |

### setIgnoreEndingFillingPatternsForCTable() {#setignoreendingfillingpatternsforctable}

Флаг, заставляющий декодер AustraliaPost игнорировать последние шаблоны заполнения в поле клиентской информации при декодировании методом CTable. Метод кодирования CTable не имеет пробелов в таблице кодов, и последовательность "333" шаблонов заполнения декодируется как буква "z".

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
