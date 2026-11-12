---
title: "DataMatrixParameters"
linktitle: "DataMatrixParameters"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "DataMatrix パラメータ。"
type: docs
weight: 360
url: /ja/nodejs/aspose.barcode/datamatrixparameters/
---

## DataMatrixParameters class

DataMatrix パラメータ。

```js
new DataMatrixParameters()
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getAspectRatio()](#getaspectratio) | 2D バーコードモジュールの高さ/幅比率 |
| [getColumns()](#getcolumns) | 列数。 |
| [getDataMatrixEcc()](#getdatamatrixecc) ~~(deprecated)~~ | Datamatrix の ECC タイプを取得します。デフォルト値: DataMatrixEccType.ECC_200. |
| [getDataMatrixEncodeMode()](#getdatamatrixencodemode) ~~(deprecated)~~ | Datamatrix バーコードのエンコードモード。デフォルト値: DataMatrixEncodeMode.AUTO. |
| [getDataMatrixVersion()](#getdatamatrixversion) ~~(deprecated)~~ | Datamatrix のシンボルサイズを取得します。デフォルト値: DataMatrixVersion.Auto. |
| [getEccType()](#getecctype) | Datamatrix の ECC タイプを取得します。デフォルト値: DataMatrixEccType.Ecc200. |
| [getECIEncoding()](#geteciencoding) | ECI エンコーディングを取得します。DataMatrixEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1 |
| [getEncodeMode()](#getencodemode) | Datamatrix バーコードのエンコードモード。デフォルト値: EncodeMode.Auto. |
| [getMacroCharacters()](#getmacrocharacters) | ISO/IEC 16022 5.2.4.7 マクロ文字 11.3 先頭位置のマクロ文字に関するプロトコル（ECC 200 のみ） Macro Cha |
| [getRows()](#getrows) | 行数。 |
| [getStructuredAppendBarcodeId()](#getstructuredappendbarcodeid) | Datamatrix バーコードの Structured Append モードのバーコード ID。デフォルト値: 0 |
| [getStructuredAppendBarcodesCount()](#getstructuredappendbarcodescount) | Datamatrix バーコードの Structured Append モードのバーコード数。デフォルト値: 0 |
| [getStructuredAppendFileId()](#getstructuredappendfileid) | Datamatrix バーコードの Structured Append モードのファイル ID。デフォルト値: 0 |
| [getVersion()](#getversion) | Datamatrix のシンボルサイズを取得します。デフォルト値: Version.Auto. |
| [isReaderProgramming()](#isreaderprogramming) | リーダーにシンボル内に含まれるデータをリーダー初期化用のプログラミングとして解釈させるために使用されます。 |
| [setAspectRatio()](#setaspectratio) | 2D バーコードモジュールの高さ/幅比率 |
| [setColumns()](#setcolumns) | 列数。 |
| [setDataMatrixEcc()](#setdatamatrixecc) ~~(deprecated)~~ | Datamatrix の ECC タイプを設定します。デフォルト値: DataMatrixEccType.ECC_200. |
| [setDataMatrixEncodeMode()](#setdatamatrixencodemode) ~~(deprecated)~~ | Datamatrix バーコードのエンコードモード。デフォルト値: DataMatrixEncodeMode.AUTO. |
| [setDataMatrixVersion()](#setdatamatrixversion) ~~(deprecated)~~ | Datamatrix のシンボルサイズを設定します。デフォルト値: DataMatrixVersion.Auto. |
| [setEccType(value)](#setecctype) | Datamatrix の ECC タイプを設定します。デフォルト値: DataMatrixEccType.Ecc200. |
| [setECIEncoding()](#seteciencoding) | ECI エンコーディングを設定します。DataMatrixEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1 |
| [setEncodeMode()](#setencodemode) | Datamatrix バーコードのエンコードモード。デフォルト値: EncodeMode.Auto. |
| [setMacroCharacters()](#setmacrocharacters) | ISO/IEC 16022 5.2.4.7 マクロ文字 11.3 先頭位置のマクロ文字に関するプロトコル（ECC 200 のみ） Macro Cha |
| [setReaderProgramming()](#setreaderprogramming) | リーダーにシンボル内に含まれるデータをリーダー初期化用のプログラミングとして解釈させるために使用されます。 |
| [setRows()](#setrows) | 行数。 |
| [setStructuredAppendBarcodeId()](#setstructuredappendbarcodeid) | Datamatrix バーコードの Structured Append モードのバーコード ID。デフォルト値: 0 |
| [setStructuredAppendBarcodesCount()](#setstructuredappendbarcodescount) | Datamatrix バーコードの Structured Append モードのバーコード数。デフォルト値: 0 |
| [setStructuredAppendFileId()](#setstructuredappendfileid) | Datamatrix バーコードの Structured Append モードのファイル ID。デフォルト値: 0 |
| [setVersion(value)](#setversion) | Datamatrix のシンボルサイズを設定します。デフォルト値: Version.Auto。 |
| [toString()](#tostring) | この DataMatrixParameters の人間が読みやすい文字列表現を返します。 |

### getAspectRatio() {#getaspectratio}

2D バーコードモジュールの高さ/幅比率

### getColumns() {#getcolumns}

列数。

### getDataMatrixEcc() {#getdatamatrixecc}

> **Deprecated.** See method description for replacement.

Datamatrix の ECC タイプを取得します。デフォルト値: DataMatrixEccType.ECC_200.

### getDataMatrixEncodeMode() {#getdatamatrixencodemode}

> **Deprecated.** See method description for replacement.

Datamatrix バーコードのエンコードモード。デフォルト値: DataMatrixEncodeMode.AUTO.

### getDataMatrixVersion() {#getdatamatrixversion}

> **Deprecated.** See method description for replacement.

Datamatrix のシンボルサイズを取得します。デフォルト値: DataMatrixVersion.Auto.

### getEccType() {#getecctype}

Datamatrix の ECC タイプを取得します。デフォルト値: DataMatrixEccType.Ecc200.

**Returns:** a Datamatrix ECC type.

### getECIEncoding() {#geteciencoding}

ECI エンコーディングを取得します。DataMatrixEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1

### getEncodeMode() {#getencodemode}

Datamatrix バーコードのエンコードモード。デフォルト値: EncodeMode.Auto.

### getMacroCharacters() {#getmacrocharacters}

ISO/IEC 16022 5.2.4.7 マクロ文字 11.3 最初の位置におけるマクロ文字のプロトコル（ECC 200 のみ） マクロ文字 05 と 06 の値は、特別モードでよりコンパクトなエンコードを取得するために使用されます。DataMatrixEccType.ECC_200 または DataMatrixEccType.ECC_AUTO と併用でき、EncodeTypes.GS_1_DATA_MATRIX では使用できません。デフォルト値: MacroCharacter.NONE。

### getRows() {#getrows}

行数。

### getStructuredAppendBarcodeId() {#getstructuredappendbarcodeid}

Datamatrix バーコードの Structured Append モードのバーコード ID。デフォルト値: 0

### getStructuredAppendBarcodesCount() {#getstructuredappendbarcodescount}

Datamatrix バーコードの Structured Append モードのバーコード数。デフォルト値: 0

### getStructuredAppendFileId() {#getstructuredappendfileid}

Datamatrix バーコードの Structured Append モードのファイル ID。デフォルト値: 0

### getVersion() {#getversion}

Datamatrix のシンボルサイズを取得します。デフォルト値: Version.Auto.

**Returns:** a Datamatrix symbol size.

### isReaderProgramming() {#isreaderprogramming}

シンボル内に含まれるデータをリーダーの初期化用プログラミングとして解釈するようリーダーに指示するために使用されます。デフォルト値: false

### setAspectRatio() {#setaspectratio}

2D バーコードモジュールの高さ/幅比率

### setColumns() {#setcolumns}

列数。

### setDataMatrixEcc() {#setdatamatrixecc}

> **Deprecated.** See method description for replacement.

Datamatrix の ECC タイプを設定します。デフォルト値: DataMatrixEccType.ECC_200.

### setDataMatrixEncodeMode() {#setdatamatrixencodemode}

> **Deprecated.** See method description for replacement.

Datamatrix バーコードのエンコードモード。デフォルト値: DataMatrixEncodeMode.AUTO.

### setDataMatrixVersion() {#setdatamatrixversion}

> **Deprecated.** See method description for replacement.

Datamatrix のシンボルサイズを設定します。デフォルト値: DataMatrixVersion.Auto.

### setEccType(value) {#setecctype}

Datamatrix の ECC タイプを設定します。デフォルト値: DataMatrixEccType.Ecc200.

| パラメータ | 説明 |
| --- | --- |
| 値 | Datamatrix の ECC タイプです。 |

### setECIEncoding() {#seteciencoding}

ECI エンコーディングを設定します。DataMatrixEncodeMode が Auto の場合に使用されます。デフォルト値: ISO-8859-1

### setEncodeMode() {#setencodemode}

Datamatrix バーコードのエンコードモード。デフォルト値: EncodeMode.Auto.

### setMacroCharacters() {#setmacrocharacters}

ISO/IEC 16022 5.2.4.7 マクロ文字 11.3 最初の位置におけるマクロ文字のプロトコル（ECC 200 のみ） マクロ文字 05 と 06 の値は、特別モードでよりコンパクトなエンコードを取得するために使用されます。DataMatrixEccType.ECC_200 または DataMatrixEccType.ECC_AUTO と併用でき、EncodeTypes.GS_1_DATA_MATRIX では使用できません。デフォルト値: MacroCharacter.NONE。

### setReaderProgramming() {#setreaderprogramming}

シンボル内に含まれるデータをリーダーの初期化用プログラミングとして解釈するようリーダーに指示するために使用されます。デフォルト値: false

### setRows() {#setrows}

行数。

### setStructuredAppendBarcodeId() {#setstructuredappendbarcodeid}

Datamatrix バーコードの Structured Append モードのバーコード ID。デフォルト値: 0

### setStructuredAppendBarcodesCount() {#setstructuredappendbarcodescount}

Datamatrix バーコードの Structured Append モードのバーコード数。デフォルト値: 0

### setStructuredAppendFileId() {#setstructuredappendfileid}

Datamatrix バーコードの Structured Append モードのファイル ID。デフォルト値: 0

### setVersion(value) {#setversion}

Datamatrix のシンボルサイズを設定します。デフォルト値: Version.Auto。

| パラメータ | 説明 |
| --- | --- |
| 値 | Datamatrix のシンボルサイズです。 |

### toString() {#tostring}

この DataMatrixParameters の人間が読みやすい文字列表現を返します。

**Returns:** presentation of this DataMatrixParameters.
