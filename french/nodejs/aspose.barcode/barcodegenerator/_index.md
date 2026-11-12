---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Référence de l'API Aspose.BarCode pour Node.js via Java"
description: "BarcodeGenerator pour la génération d'images de codes-barres côté serveur."
type: docs
weight: 130
url: /fr/nodejs/aspose.barcode/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator pour la génération d'images de codes-barres côté serveur. symbologies prises en charge : 1D : Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D : Aztec, DataMatrix, PDf417, QR code ...

```js
new BarcodeGenerator(encodeType, codeText)
```

Constructeur BarcodeGenerator.

| Paramètre | Description |
| --- | --- |
| encodeType | Type de symbologie du code-barres. Utilisez la classe EncodeTypes pour configurer une symbologie |
| codeText | Texte à encoder. |

**Throws:** BarcodeException

**Example:**

```js
// This sample shows how to create and save a barcode image.
let encode_type = EncodeTypes.CODE_128;
let generator = new BarcodeGenerator(encode_type);
generator.setCodeText("123ABC");
```

## Méthodes

| Nom | Description |
| --- | --- |
| [importFromXml(filePath)](#importfromxml) *(static)* | Importe les propriétés BarCode du fichier XML spécifié et crée une instance de BarcodeGenerator. |
| [exportToXml(filePath)](#exporttoxml) | Exporte les propriétés BarCode vers le fichier XML spécifié |
| [generateBarCodeImage(format)](#generatebarcodeimage) | Génère l'image du code-barres avec les paramètres actuels. Cet exemple montre comment créer et enregistrer une image de code-barres. |
| [getBarcodeType()](#getbarcodetype) | Type de symbologie du code-barres. |
| [getCodeText()](#getcodetext) | Texte à encoder. |
| [getParameters()](#getparameters) | Paramètres de génération. |
| [save(filePath, format)](#save) | Enregistre l'image du code-barres dans un fichier spécifique dans un format spécifique. |
| [setBarcodeType()](#setbarcodetype) | Type de symbologie du code-barres. |
| [setCodeText(codeText, encoding, insertBOM)](#setcodetext) | Encode le texte Unicode `codeText ` en une séquence d'octets en utilisant le `encoding ` spécifié. UTF-8 est le plus couramment utilisé en |

### importFromXml(filePath) (static) {#importfromxml}

Importe les propriétés BarCode du fichier XML spécifié et crée une instance de BarcodeGenerator.

| Paramètre | Description |
| --- | --- |
| filePath | Le nom du fichier |

**Returns:** BarcodeGenerator instance

### exportToXml(filePath) {#exporttoxml}

Exporte les propriétés BarCode vers le fichier XML spécifié

| Paramètre | Description |
| --- | --- |
| filePath | Le fichier xml |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

**Throws:** IOException

### generateBarCodeImage(format) {#generatebarcodeimage}

Génère l'image du code-barres avec les paramètres actuels. Cet exemple montre comment créer et enregistrer une image de code-barres.

| Paramètre | Type | Description |
| --- | --- | --- |
| format | BarCodeImageFormat | Valeur BarCodeImageFormat (PNG, BMP, JPEG, GIF) |

**Returns:** String — base64 representation of image.

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```

### getBarcodeType() {#getbarcodetype}

Type de symbologie du code-barres.

### getCodeText() {#getcodetext}

Texte à encoder.

### getParameters() {#getparameters}

Paramètres de génération.

**Returns:** BaseGenerationParameters

### save(filePath, format) {#save}

Enregistre l'image du code-barres dans un fichier spécifique dans un format spécifique.

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Chemin où enregistrer. |
| format | BarCodeImageFormat | Valeur BarCodeImageFormat (PNG, BMP, JPEG, GIF) |

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```

### setBarcodeType() {#setbarcodetype}

Type de symbologie du code-barres.

### setCodeText(codeText, encoding, insertBOM) {#setcodetext}

Encode le texte Unicode `codeText ` en une séquence d'octets en utilisant le `encoding ` spécifié. UTF-8 est l'encodage le plus couramment utilisé. Si l'encodage le supporte et que `insertBOM ` est défini sur `true`, la fonction inclut un `byte order mark (BOM) `. Cette fonction est destinée uniquement à une utilisation avec les codes-barres 2D (par exemple, Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR, etc.). Elle permet l'encodage manuel de texte Unicode en utilisant des encodages nationaux ou spéciaux ; cependant, cette méthode est considérée comme obsolète dans les applications modernes. Pour les cas d'utilisation modernes, l'encodage `ECI ` est recommandé pour les données Unicode. L'utilisation de cette fonction avec des codes-barres 1D, des codes-barres conformes GS1 (y compris 2D), ou des codes-barres HIBC (y compris 2D) n'est pas prise en charge par les normes de codes-barres correspondantes et peut entraîner des résultats imprévisibles. Cet exemple montre comment utiliser `SetCodeText` avec ou sans BOM pour les codes-barres 2D. //Encode codetext using UTF-8 with BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText(\"車種名\", \"UTF-8\", true); gen.save(\"barcode.png\", BarCodeImageFormat.PNG); let reader = new BarCodeReader(\"barcode.png\", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log(\"BarCode CodeText: \" + result.getCodeText()); } //Encode codetext using UTF-8 without BOM let gen = new BarcodeGenerator(EncodeTypes.QR, null); gen.setCodeText(\"車種名\", \"UTF-8\", false); gen.save(\"barcode.png\", BarCodeImageFormat.PNG); let reader = new BarCodeReader(\"barcode.png\", null, DecodeType.QR); let results = reader.readBarCodes(); for(let i = 0; i < results.length; i++) { let result = results[i]; console.log(\"BarCode CodeText: \" + result.getCodeText()); }

| Paramètre | Description |
| --- | --- |
| codeText | Chaîne CodeText |
| encodage | Encodage appliqué |
| insertBOM | Indique s'il faut insérer un marqueur d'ordre d'octets (BOM) lorsque l'encodage spécifié le supporte (par ex., UTF-8, UTF-16, UTF-32). Si défini sur `true`, le BOM est ajouté ; si `false`, le BOM est omis même si l'encodage en utilise normalement un. |
