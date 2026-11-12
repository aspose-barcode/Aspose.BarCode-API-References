---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Aspose.BarCode for Node.js via Java API リファレンス"
description: "バックエンドでのバーコード画像生成用 BarcodeGenerator。"
type: docs
weight: 130
url: /ja/nodejs/aspose.barcode/barcodegenerator/
---

## BarcodeGenerator class

バックエンドでのバーコード画像生成用 BarcodeGenerator。サポートされているシンボロジー: 1D: Codabar、Code11、Code128、Code39Standard、Code39Extended、Code93Standard、Code93Extended、EAN13、EAN8、Interleaved2of5、MSI、Standard2of5、UPCA、UPCE、ISBN、GS1Code128、Postnet、Planet、EAN14、SCC14、SSCC18、ITF14、SingaporePost ... 2D: Aztec、DataMatrix、PDf417、QR code ...

```js
new BarcodeGenerator(encodeType, codeText)
```

BarcodeGenerator コンストラクタ。

| パラメータ | 説明 |
| --- | --- |
| encodeType | バーコードシンボロジーのタイプ。シンボロジーを設定するには EncodeTypes クラスを使用します。 |
| codeText | エンコードするテキスト。 |

**Throws:** BarcodeException

**Example:**

```js
// This sample shows how to create and save a barcode image.
let encode_type = EncodeTypes.CODE_128;
let generator = new BarcodeGenerator(encode_type);
generator.setCodeText("123ABC");
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [importFromXml(filePath)](#importfromxml) *(static)* | 指定された XML ファイルから BarCode プロパティをインポートし、BarcodeGenerator インスタンスを作成します。 |
| [exportToXml(filePath)](#exporttoxml) | 指定された XML ファイルへ BarCode プロパティをエクスポートします。 |
| [generateBarCodeImage(format)](#generatebarcodeimage) | 現在の設定でバーコード画像を生成します。このサンプルはバーコード画像の作成と保存方法を示しています。 |
| [getBarcodeType()](#getbarcodetype) | バーコードシンボロジーのタイプ。 |
| [getCodeText()](#getcodetext) | エンコードするテキスト。 |
| [getParameters()](#getparameters) | 生成パラメータ。 |
| [save(filePath, format)](#save) | バーコード画像を特定の形式で特定のファイルに保存します。 |
| [setBarcodeType()](#setbarcodetype) | バーコードシンボロジーのタイプ。 |
| [setCodeText(codeText, encoding, insertBOM)](#setcodetext) | 指定された `encoding` を使用して Unicode `codeText` をバイト列にエンコードします。UTF-8 は最も一般的に使用されるエンコーディングです。 |

### importFromXml(filePath) (static) {#importfromxml}

指定された XML ファイルから BarCode プロパティをインポートし、BarcodeGenerator インスタンスを作成します。

| パラメータ | 説明 |
| --- | --- |
| filePath | ファイル名 |

**Returns:** BarcodeGenerator instance

### exportToXml(filePath) {#exporttoxml}

指定された XML ファイルへ BarCode プロパティをエクスポートします。

| パラメータ | 説明 |
| --- | --- |
| filePath | XML ファイル |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

**Throws:** IOException

### generateBarCodeImage(format) {#generatebarcodeimage}

現在の設定でバーコード画像を生成します。このサンプルはバーコード画像の作成と保存方法を示しています。

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| フォーマット | BarCodeImageFormat | BarCodeImageFormat の値 (PNG, BMP, JPEG, GIF) |

**Returns:** String — base64 representation of image.

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```

### getBarcodeType() {#getbarcodetype}

バーコードシンボロジーのタイプ。

### getCodeText() {#getcodetext}

エンコードするテキスト。

### getParameters() {#getparameters}

生成パラメータ。

**Returns:** BaseGenerationParameters

### save(filePath, format) {#save}

バーコード画像を特定の形式で特定のファイルに保存します。

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filePath | String | 保存先のパス。 |
| フォーマット | BarCodeImageFormat | BarCodeImageFormat の値 (PNG, BMP, JPEG, GIF) |

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```

### setBarcodeType() {#setbarcodetype}

バーコードシンボロジーのタイプ。

### setCodeText(codeText, encoding, insertBOM) {#setcodetext}

指定された `encoding` を使用して Unicode `codeText` をバイト列にエンコードします。UTF-8 は最も一般的に使用されるエンコーディングです。エンコーディングが対応しており、`insertBOM` が `true` に設定されている場合、関数は `byte order mark (BOM)` を含めます。この関数は 2D バーコード（例: Aztec、QR、DataMatrix、PDF417、MaxiCode、DotCode、HanXin、RectMicroQR など）でのみ使用することを想定しています。国別エンコーディングや特殊エンコーディングを使用した Unicode テキストの手動エンコードを可能にしますが、現代のアプリケーションではこの方法は旧式と見なされています。最新のユースケースでは Unicode データに対して `ECI` エンコーディングの使用が推奨されます。この関数を 1D バーコード、GS1 準拠バーコード（2D を含む）または HIBC バーコード（2D を含む）で使用すると、対応するバーコード規格でサポートされず、予測不能な結果になる可能性があります。この例は 2D バーコードで BOM の有無にかかわらず `SetCodeText` を使用する方法を示しています。 //Encode codetext using UTF-8 with BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText(\"車種名\", \"UTF-8\", true); gen.save(\"barcode.png\", BarCodeImageFormat.PNG); let reader = new BarCodeReader(\"barcode.png\", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log(\"BarCode CodeText: \" + result.getCodeText()); } //Encode codetext using UTF-8 without BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText(\"車種名\", \"UTF-8\", false); gen.save(\"barcode.png\", BarCodeImageFormat.PNG); let reader = new BarCodeReader(\"barcode.png\", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log(\"BarCode CodeText: \" + result.getCodeText()); }

| パラメータ | 説明 |
| --- | --- |
| codeText | CodeText 文字列 |
| エンコーディング | 適用されたエンコーディング |
| insertBOM | 指定されたエンコーディングがサポートしている場合にバイトオーダーマーク (BOM) を挿入するかどうかを示します（例: UTF-8、UTF-16、UTF-32）。`true` に設定すると BOM が追加され、`false` に設定すると、エンコーディングが通常 BOM を使用する場合でも省略されます。 |
