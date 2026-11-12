---
title: "BarcodeGenerator"
linktitle: "BarcodeGenerator"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "BarcodeGenerator για δημιουργία εικόνων barcode στο backend."
type: docs
weight: 130
url: /el/nodejs/aspose.barcode/barcodegenerator/
---

## BarcodeGenerator class

BarcodeGenerator για δημιουργία εικόνων barcode στο backend. υποστηριζόμενοι συμβολισμοί: 1D: Codabar, Code11, Code128, Code39Standard, Code39Extended Code93Standard, Code93Extended, EAN13, EAN8, Interleaved2of5, MSI, Standard2of5, UPCA, UPCE, ISBN, GS1Code128, Postnet, Planet EAN14, SCC14, SSCC18, ITF14, SingaporePost ... 2D: Aztec, DataMatrix, PDf417, QR code ...

```js
new BarcodeGenerator(encodeType, codeText)
```

Κατασκευαστής BarcodeGenerator.

| Παράμετρος | Περιγραφή |
| --- | --- |
| encodeType | Τύπος συμβολισμού barcode. Χρησιμοποιήστε την κλάση EncodeTypes για να ρυθμίσετε έναν συμβολισμό |
| codeText | Κείμενο προς κωδικοποίηση. |

**Throws:** BarcodeException

**Example:**

```js
// This sample shows how to create and save a barcode image.
let encode_type = EncodeTypes.CODE_128;
let generator = new BarcodeGenerator(encode_type);
generator.setCodeText("123ABC");
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [importFromXml(filePath)](#importfromxml) *(static)* | Εισάγει τις ιδιότητες BarCode από το καθορισμένο αρχείο xml και δημιουργεί μια παρουσία BarcodeGenerator. |
| [exportToXml(filePath)](#exporttoxml) | Εξάγει τις ιδιότητες BarCode στο καθορισμένο αρχείο xml. |
| [generateBarCodeImage(format)](#generatebarcodeimage) | Δημιουργήστε την εικόνα barcode με τις τρέχουσες ρυθμίσεις. Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα barcode. |
| [getBarcodeType()](#getbarcodetype) | Τύπος συμβολισμού barcode. |
| [getCodeText()](#getcodetext) | Κείμενο προς κωδικοποίηση. |
| [getParameters()](#getparameters) | Παράμετροι δημιουργίας. |
| [save(filePath, format)](#save) | Αποθηκεύστε την εικόνα barcode σε συγκεκριμένο αρχείο σε συγκεκριμένη μορφή. |
| [setBarcodeType()](#setbarcodetype) | Τύπος συμβολισμού barcode. |
| [setCodeText(codeText, encoding, insertBOM)](#setcodetext) | Κωδικοποιεί το Unicode `codeText` σε μια ακολουθία byte χρησιμοποιώντας το καθορισμένο `encoding`. Το UTF-8 είναι το πιο συχνά χρησιμοποιούμενο en |

### importFromXml(filePath) (static) {#importfromxml}

Εισάγει τις ιδιότητες BarCode από το καθορισμένο αρχείο xml και δημιουργεί μια παρουσία BarcodeGenerator.

| Παράμετρος | Περιγραφή |
| --- | --- |
| filePath | Το όνομα του file |

**Returns:** BarcodeGenerator instance

### exportToXml(filePath) {#exporttoxml}

Εξάγει τις ιδιότητες BarCode στο καθορισμένο αρχείο xml.

| Παράμετρος | Περιγραφή |
| --- | --- |
| filePath | Το αρχείο xml |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

**Throws:** IOException

### generateBarCodeImage(format) {#generatebarcodeimage}

Δημιουργήστε την εικόνα barcode με τις τρέχουσες ρυθμίσεις. Αυτό το παράδειγμα δείχνει πώς να δημιουργήσετε και να αποθηκεύσετε μια εικόνα barcode.

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μορφή | BarCodeImageFormat | Τιμή BarCodeImageFormat (PNG, BMP, JPEG, GIF) |

**Returns:** String — base64 representation of image.

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
let image = generator.generateBarCodeImage(BarCodeImageFormat.GIF);
```

### getBarcodeType() {#getbarcodetype}

Τύπος συμβολισμού barcode.

### getCodeText() {#getcodetext}

Κείμενο προς κωδικοποίηση.

### getParameters() {#getparameters}

Παράμετροι δημιουργίας.

**Returns:** BaseGenerationParameters

### save(filePath, format) {#save}

Αποθηκεύστε την εικόνα barcode σε συγκεκριμένο αρχείο σε συγκεκριμένη μορφή.

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Διαδρομή αποθήκευσης. |
| μορφή | BarCodeImageFormat | Τιμή BarCodeImageFormat (PNG, BMP, JPEG, GIF) |

**Example:**

```js
let generator = new BarCodeGenerator(EncodeTypes.CODE_128);
generator.save("file path", BarCodeImageFormat.GIF);
```

### setBarcodeType() {#setbarcodetype}

Τύπος συμβολισμού barcode.

### setCodeText(codeText, encoding, insertBOM) {#setcodetext}

Κωδικοποιεί το Unicode `codeText` σε μια ακολουθία byte χρησιμοποιώντας το καθορισμένο `encoding`. Το UTF-8 είναι η πιο συχνά χρησιμοποιούμενη κωδικοποίηση. Εάν η κωδικοποίηση το υποστηρίζει και το `insertBOM` οριστεί σε `true`, η συνάρτηση προσθέτει ένα `byte order mark (BOM)`. Αυτή η συνάρτηση προορίζεται μόνο για χρήση με 2D barcode (π.χ., Aztec, QR, DataMatrix, PDF417, MaxiCode, DotCode, HanXin, RectMicroQR κ.λπ.). Επιτρέπει την χειροκίνητη κωδικοποίηση κειμένου Unicode χρησιμοποιώντας εθνικές ή ειδικές κωδικοποιήσεις· ωστόσο, αυτή η μέθοδος θεωρείται παρωχημένη σε σύγχρονες εφαρμογές. Για σύγχρονες περιπτώσεις, συνιστάται η κωδικοποίηση `ECI` για δεδομένα Unicode. Η χρήση αυτής της συνάρτησης με 1D barcode, barcode συμβατά με GS1 (συμπεριλαμβανομένων των 2D) ή HIBC barcode (συμπεριλαμβανομένων των 2D) δεν υποστηρίζεται από τα αντίστοιχα πρότυπα barcode και μπορεί να οδηγήσει σε απρόβλεπτα αποτελέσματα. Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε το `SetCodeText` με ή χωρίς BOM για 2D barcode.
//Encode codetext using UTF-8 with BOM
let gen = new BarcodeGenerator(EncodeTypes.QR, null);
gen.setCodeText("車種名", "UTF-8", true);
gen.save("barcode.png", BarCodeImageFormat.PNG);
let reader = new BarCodeReader("barcode.png", null, DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++) {
    let result = results[i];
    console.log("BarCode CodeText: " + result.getCodeText());
}
//Encode codetext using UTF-8 without BOM
let gen = new BarcodeGenerator(EncodeTypes.QR, null);
gen.setCodeText("車種名", "UTF-8", false);
gen.save("barcode.png", BarCodeImageFormat.PNG);
let reader = new BarCodeReader("barcode.png", null, DecodeType.QR);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++) {
    let result = results[i];
    console.log("BarCode CodeText: " + result.getCodeText());
}

| Παράμετρος | Περιγραφή |
| --- | --- |
| codeText | Συμβολοσειρά CodeText |
| κωδικοποίηση | Εφαρμοσμένη κωδικοποίηση |
| insertBOM | Δηλώνει εάν θα εισαχθεί ένα byte order mark (BOM) όταν η καθορισμένη κωδικοποίηση το υποστηρίζει (π.χ., UTF-8, UTF-16, UTF-32). Εάν οριστεί σε `true`, το BOM προστίθεται· εάν οριστεί σε `false`, το BOM παραλείπεται ακόμη και αν η κωδικοποίηση το χρησιμοποιεί συνήθως. |
