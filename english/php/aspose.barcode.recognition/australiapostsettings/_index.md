---
title: "AustraliaPostSettings"
linktitle: "AustraliaPostSettings"
second_title: "Aspose.BarCode for PHP via Java"
description: "AustraliaPost decoding parameters. Contains parameters which make influence on recognized data of AustraliaPost symbology."
type: docs
weight: 10
url: /php/aspose.barcode.recognition/australiapostsettings/
---

## AustraliaPostSettings class

**Namespace:** `Aspose.Barcode.Recognition`


AustraliaPost decoding parameters. Contains parameters which make influence on recognized data of AustraliaPost symbology.


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) | AustraliaPostSettings constructor |

## Properties

| Name | Read/Write | Description |
| --- | --- | --- |
| [CustomerInformationInterpretingType](#customerinformationinterpretingtype) | Read/Write | Gets or sets the Interpreting Type for the Customer Information of AustralianPost BarCode.DEFAULT is CustomerInformationInterpretingType.OTHER. |
| [IgnoreEndingFillingPatternsForCTable](#ignoreendingfillingpatternsforctable) | Read/Write | The flag which force AustraliaPost decoder to ignore last filling patterns in Customer Information Field during decoding as CTable method. CTable encoding method does not have any gaps in encoding table and sequnce "333" of filling paterns is decoded as letter "z". |

### AustraliaPostSettings__construct(AustraliaPostSettingsDTO $australiaPostSettingsDto) {#constructor}

AustraliaPostSettings constructor

| Parameter | Type | Description |
| --- | --- | --- |
| `$australiaPostSettingsDto` | `AustraliaPostSettingsDTO` |  |

### CustomerInformationInterpretingType {#customerinformationinterpretingtype}

**Access:** Read/Write

**Returns:** int The interpreting type (CTable, NTable or Other) of customer information for AustralianPost BarCode

Gets or sets the Interpreting Type for the Customer Information of AustralianPost BarCode.DEFAULT is CustomerInformationInterpretingType.OTHER.

Gets or sets the Interpreting Type for the Customer Information of AustralianPost BarCode.DEFAULT is CustomerInformationInterpretingType.OTHER.

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `int` |  |

### IgnoreEndingFillingPatternsForCTable {#ignoreendingfillingpatternsforctable}

**Access:** Read/Write

**Returns:** bool The flag which force AustraliaPost decoder to ignore last filling patterns during CTable method decoding

The flag which force AustraliaPost decoder to ignore last filling patterns in Customer Information Field during decoding as CTable method. CTable encoding method does not have any gaps in encoding table and sequnce "333" of filling paterns is decoded as letter "z".

The flag which force AustraliaPost decoder to ignore last filling patterns in Customer Information Field during decoding as CTable method. CTable encoding method does not have any gaps in encoding table and sequnce "333" of filling paterns is decoded as letter "z".

| Parameter | Type | Description |
| --- | --- | --- |
| `$value` | `bool` |  |

