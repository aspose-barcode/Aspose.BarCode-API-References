---
title: "DataMatrixParameters"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode for Node.js via Java API Reference"
description: "DataMatrix parameters."
type: docs
weight: 360
url: /nodejs/aspose.barcode/datamatrixparameters/
---

## DataMatrixParameters class

DataMatrix parameters.

```js
new DataMatrixParameters()
```

## Methods

| Name | Description |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | Height/Width ratio of 2D BarCode module. |
| [getColumns()](#getcolumns) | Columns count. |
| [getDataMatrixEcc()](#getdatamatrixecc) ~~(deprecated)~~ | Gets a Datamatrix ECC type. Default value: DataMatrixEccType.ECC_200. |
| [getDataMatrixEncodeMode()](#getdatamatrixencodemode) ~~(deprecated)~~ | Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.AUTO. |
| [getDataMatrixVersion()](#getdatamatrixversion) ~~(deprecated)~~ | Gets a Datamatrix symbol size. Default value: DataMatrixVersion.Auto. |
| [getEccType()](#getecctype) | Gets a Datamatrix ECC type. Default value: DataMatrixEccType.Ecc200. |
| [getECIEncoding()](#geteciencoding) | Gets ECI encoding. Used when DataMatrixEncodeMode is Auto. Default value: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Encode mode of Datamatrix barcode. Default value: EncodeMode.Auto. |
| [getMacroCharacters()](#getmacrocharacters) | ISO/IEC 16022 5.2.4.7 Macro characters 11.3 Protocol for Macro characters in the first position (ECC 200 only) Macro Cha |
| [getRows()](#getrows) | Rows count. |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Barcode ID for Structured Append mode of Datamatrix barcode. Default value: 0 |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Barcodes count for Structured Append mode of Datamatrix barcode. Default value: 0 |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | File ID for Structured Append mode of Datamatrix barcode. Default value: 0 |
| [getVersion()](#getversion) | Gets a Datamatrix symbol size. Default value: Version.Auto. |
| [isReaderProgramming()](#isreaderprogramming) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization.  |
| [setAspectRatio()](#setaspectratio) | Height/Width ratio of 2D BarCode module. |
| [setColumns()](#setcolumns) | Columns count. |
| [setDataMatrixEcc()](#setdatamatrixecc) ~~(deprecated)~~ | Sets a Datamatrix ECC type. Default value: DataMatrixEccType.ECC_200. |
| [setDataMatrixEncodeMode()](#setdatamatrixencodemode) ~~(deprecated)~~ | Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.AUTO. |
| [setDataMatrixVersion()](#setdatamatrixversion) ~~(deprecated)~~ | Sets a Datamatrix symbol size. Default value: DataMatrixVersion.Auto. |
| [setEccType(value)](#setecctype) | Sets a Datamatrix ECC type. Default value: DataMatrixEccType.Ecc200. |
| [setECIEncoding()](#seteciencoding) | Sets ECI encoding. Used when DataMatrixEncodeMode is Auto. Default value: ISO-8859-1 |
| [setEncodeMode()](#setencodemode) | Encode mode of Datamatrix barcode. Default value: EncodeMode.Auto. |
| [setMacroCharacters()](#setmacrocharacters) | ISO/IEC 16022 5.2.4.7 Macro characters 11.3 Protocol for Macro characters in the first position (ECC 200 only) Macro Cha |
| [setReaderProgramming()](#setreaderprogramming) | Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization.  |
| [setRows()](#setrows) | Rows count. |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | Barcode ID for Structured Append mode of Datamatrix barcode. Default value: 0 |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | Barcodes count for Structured Append mode of Datamatrix barcode. Default value: 0 |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | File ID for Structured Append mode of Datamatrix barcode. Default value: 0 |
| [setVersion(value)](#setversion) | Sets a Datamatrix symbol size. Default value: Version.Auto. |
| [toString()](#tostring) | Returns a human-readable string representation of this DataMatrixParameters. |

### getAspectRatio() {#getaspectratio}

Height/Width ratio of 2D BarCode module.

### getColumns() {#getcolumns}

Columns count.

### getDataMatrixEcc() {#getdatamatrixecc}

> **Deprecated.** See method description for replacement.

Gets a Datamatrix ECC type. Default value: DataMatrixEccType.ECC_200.

### getDataMatrixEncodeMode() {#getdatamatrixencodemode}

> **Deprecated.** See method description for replacement.

Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.AUTO.

### getDataMatrixVersion() {#getdatamatrixversion}

> **Deprecated.** See method description for replacement.

Gets a Datamatrix symbol size. Default value: DataMatrixVersion.Auto.

### getEccType() {#getecctype}

Gets a Datamatrix ECC type. Default value: DataMatrixEccType.Ecc200.

**Returns:** a Datamatrix ECC type.

### getECIEncoding() {#geteciencoding}

Gets ECI encoding. Used when DataMatrixEncodeMode is Auto. Default value: ISO-8859-1

### getEncodeMode() {#getencodemode}

Encode mode of Datamatrix barcode. Default value: EncodeMode.Auto.

### getMacroCharacters() {#getmacrocharacters}

ISO/IEC 16022 5.2.4.7 Macro characters 11.3 Protocol for Macro characters in the first position (ECC 200 only) Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with DataMatrixEccType.ECC_200 or DataMatrixEccType.ECC_AUTO. Cannot be used with EncodeTypes.GS_1_DATA_MATRIX Default value: MacroCharacter.NONE.

### getRows() {#getrows}

Rows count.

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Barcode ID for Structured Append mode of Datamatrix barcode. Default value: 0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Barcodes count for Structured Append mode of Datamatrix barcode. Default value: 0

### getStructuredAppendFileId() {#getstructuredappendfileid}

File ID for Structured Append mode of Datamatrix barcode. Default value: 0

### getVersion() {#getversion}

Gets a Datamatrix symbol size. Default value: Version.Auto.

**Returns:** a Datamatrix symbol size.

### isReaderProgramming() {#isreaderprogramming}

Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. Default value: false

### setAspectRatio() {#setaspectratio}

Height/Width ratio of 2D BarCode module.

### setColumns() {#setcolumns}

Columns count.

### setDataMatrixEcc() {#setdatamatrixecc}

> **Deprecated.** See method description for replacement.

Sets a Datamatrix ECC type. Default value: DataMatrixEccType.ECC_200.

### setDataMatrixEncodeMode() {#setdatamatrixencodemode}

> **Deprecated.** See method description for replacement.

Encode mode of Datamatrix barcode. Default value: DataMatrixEncodeMode.AUTO.

### setDataMatrixVersion() {#setdatamatrixversion}

> **Deprecated.** See method description for replacement.

Sets a Datamatrix symbol size. Default value: DataMatrixVersion.Auto.

### setEccType(value) {#setecctype}

Sets a Datamatrix ECC type. Default value: DataMatrixEccType.Ecc200.

| Parameter | Description |
| --- | --- |
| value | a Datamatrix ECC type. |

### setECIEncoding() {#seteciencoding}

Sets ECI encoding. Used when DataMatrixEncodeMode is Auto. Default value: ISO-8859-1

### setEncodeMode() {#setencodemode}

Encode mode of Datamatrix barcode. Default value: EncodeMode.Auto.

### setMacroCharacters() {#setmacrocharacters}

ISO/IEC 16022 5.2.4.7 Macro characters 11.3 Protocol for Macro characters in the first position (ECC 200 only) Macro Characters 05 and 06 values are used to obtain more compact encoding in special modes. Can be used only with DataMatrixEccType.ECC_200 or DataMatrixEccType.ECC_AUTO. Cannot be used with EncodeTypes.GS_1_DATA_MATRIX Default value: MacroCharacter.NONE.

### setReaderProgramming() {#setreaderprogramming}

Used to instruct the reader to interpret the data contained within the symbol as programming for reader initialization. Default value: false

### setRows() {#setrows}

Rows count.

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

Barcode ID for Structured Append mode of Datamatrix barcode. Default value: 0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

Barcodes count for Structured Append mode of Datamatrix barcode. Default value: 0

### setStructuredAppendFileId() {#setstructuredappendfileid}

File ID for Structured Append mode of Datamatrix barcode. Default value: 0

### setVersion(value) {#setversion}

Sets a Datamatrix symbol size. Default value: Version.Auto.

| Parameter | Description |
| --- | --- |
| value | a Datamatrix symbol size. |

### toString() {#tostring}

Returns a human-readable string representation of this DataMatrixParameters.

**Returns:** presentation of this DataMatrixParameters.
