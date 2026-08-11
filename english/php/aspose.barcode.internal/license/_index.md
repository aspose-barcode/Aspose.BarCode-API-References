---
title: "License"
linktitle: "License"
second_title: "Aspose.BarCode for PHP via Java"
description: ""
type: docs
weight: 10
url: /php/aspose.barcode.internal/license/
---

## License class

**Namespace:** `Aspose.Barcode.Internal`


## Constructors

| Name | Description |
| --- | --- |
| [__construct](#constructor) |  |

## Methods

| Name | Static | Description |
| --- | --- | --- |
| [isLicensed](#islicensed) | No |  |
| [prepareLicenseContent](#preparelicensecontent) | Yes | This method is intended only for cases where license content is passed to the methods readBarCodes() and generateBarCodeImage() with the flag $passLicense = true) |
| [resetLicense](#resetlicense) | No |  |
| [setLicense](#setlicense) | No |  |
| [setLicenseFromBase64](#setlicensefrombase64) | No |  |
| [setLicenseFromFile](#setlicensefromfile) | No |  |

## Properties

| Name | Static | Read/Write | Description |
| --- | --- | --- | --- |
| [LicenseContent](#licensecontent) | Yes | Read-only |  |

### License__construct() {#constructor}

### isLicensedisLicensed() {#islicensed}

### prepareLicenseContentprepareLicenseContent(string $licenseFilePath) (static) {#preparelicensecontent}

This method is intended only for cases where license content is passed to the methods readBarCodes() and generateBarCodeImage() with the flag $passLicense = true)

| Parameter | Type | Description |
| --- | --- | --- |
| `$licenseFilePath` | `string` |  |

**Returns:** void

### resetLicenseresetLicense() {#resetlicense}

### setLicensesetLicense(string $licenseFileOrBase64Content) {#setlicense}

| Parameter | Type | Description |
| --- | --- | --- |
| `$licenseFileOrBase64Content` | `string` |  |

### setLicenseFromBase64setLicenseFromBase64(string $licenseContent) {#setlicensefrombase64}

| Parameter | Type | Description |
| --- | --- | --- |
| `$licenseContent` | `string` |  |

### setLicenseFromFilesetLicenseFromFile(string $licenseFilePath) {#setlicensefromfile}

| Parameter | Type | Description |
| --- | --- | --- |
| `$licenseFilePath` | `string` |  |

### LicenseContent {#licensecontent}

**Access:** Read-only

**Static:** Yes

