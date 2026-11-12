---
title: "BarCodeReader"
linktitle: "BarCodeReader"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Το BarCodeReader περιέχει μια εικόνα που μπορεί να περιέχει ένα ή περισσότερα barcodes, και στη συνέχεια μπορεί να εκτελέσει την λειτουργία ReadBarCodes για την ανίχνευση των barcodes."
type: docs
weight: 90
url: /el/nodejs/aspose.barcode/barcodereader/
---

## BarCodeReader class

Το BarCodeReader περιέχει μια εικόνα που μπορεί να περιέχει ένα ή περισσότερα barcodes, και στη συνέχεια μπορεί να εκτελέσει την λειτουργία ReadBarCodes για την ανίχνευση των barcodes.

```js
new BarCodeReader(image, areas, decodeTypes)
```

Αρχικοποιεί μια νέα παρουσία του BarCodeReader

| Παράμετρος | Περιγραφή |
| --- | --- |
| εικόνα | κωδικοποιημένο ως συμβολοσειρά base64 ή διαδρομή προς την εικόνα |
| περιοχές | πίνακας αντικειμένων τύπου Rectangle |
| decodeTypes | ο πίνακας των αντικειμένων κατά DecodeType |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader("test.png", null,  [DecodeType.CODE_39, DecodeType.CODE_128]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [importFromXml(xmlFile)](#importfromxml) *(static)* | Εξάγει τις ιδιότητες BarCode στο αρχείο xml που καθορίζεται |
| [containsAny()](#containsany) | Καθορίζει εάν κάποιο από τους δοθέντες τύπους decode περιλαμβάνεται στο |
| [exportToXml(xmlFile)](#exporttoxml) | Εξάγει τις ιδιότητες BarCode στο αρχείο xml που καθορίζεται |
| [getBarCodeReadType()](#getbarcodereadtype) | Λαμβάνει τον τύπο decode της αποκωδικοποίησης barcode εισόδου |
| [getBarcodeSettings()](#getbarcodesettings) | Οι κύριες παράμετροι αποκωδικοποίησης BarCode. Περιέχει παραμέτρους που επηρεάζουν τα αναγνωρισμένα δεδομένα. |
| [getFoundBarCodes()](#getfoundbarcodes) | Λαμβάνει τον αναγνωρισμένο πίνακα BarCodeResult |
| [getFoundCount()](#getfoundcount) | Λαμβάνει τον αριθμό των αναγνωρισμένων barcodes |
| [getQualitySettings()](#getqualitysettings) | Το QualitySettings επιτρέπει τη χειροκίνητη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης. Μπορείτε να ρυθμίσετε γρήγορα το QualitySettings με το em |
| [getTimeout()](#gettimeout) | Λαμβάνει το timeout της διαδικασίας αναγνώρισης σε χιλιοστά του δευτερολέπτου. |
| [readBarCodes()](#readbarcodes) | Αναγνάει το BarCodeResult από την εικόνα. |
| [setBarCodeImage(imageResource, …areas)](#setbarcodeimage) | Ορίζει την bitmap εικόνα και τις περιοχές για αναγνώριση. Πρέπει να κληθεί πριν τη μέθοδο ReadBarCodes(). |
| [setBarCodeReadType(…types)](#setbarcodereadtype) | Ορίζει τον πίνακα τύπων SingleDecodeType για αναγνώριση. Πρέπει να κληθεί πριν τη μέθοδο readBarCodes(). |
| [setQualitySettings()](#setqualitysettings) | Το QualitySettings επιτρέπει τη χειροκίνητη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης. Μπορείτε να ρυθμίσετε γρήγορα το QualitySettings με το em |
| [setTimeout(value)](#settimeout) | Ορίζει το timeout της διαδικασίας αναγνώρισης σε χιλιοστά του δευτερολέπτου. |

### importFromXml(xmlFile) (static) {#importfromxml}

Εξάγει τις ιδιότητες BarCode στο αρχείο xml που καθορίζεται

| Παράμετρος | Περιγραφή |
| --- | --- |
| xmlFile | Το όνομα του file |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### containsAny() {#containsany}

Καθορίζει εάν κάποιο από τους δοθέντες τύπους decode περιλαμβάνεται στο

| Παράμετρος | Περιγραφή |
| --- | --- |
| ...decodeTypes | Τύποι προς επαλήθευση. |

**Returns:** bool Value is a true if any types are included into.

### exportToXml(xmlFile) {#exporttoxml}

Εξάγει τις ιδιότητες BarCode στο αρχείο xml που καθορίζεται

| Παράμετρος | Περιγραφή |
| --- | --- |
| xmlFile | Το όνομα του file |

**Returns:** Whether or not export completed successfully. Returns True in case of success; False Otherwise

### getBarCodeReadType() {#getbarcodereadtype}

Λαμβάνει τον τύπο decode της αποκωδικοποίησης barcode εισόδου

**Returns:** *

### getBarcodeSettings() {#getbarcodesettings}

Οι κύριες παράμετροι αποκωδικοποίησης BarCode. Περιέχει παραμέτρους που επηρεάζουν τα αναγνωρισμένα δεδομένα.

**Returns:** The main BarCode decoding parameters

### getFoundBarCodes() {#getfoundbarcodes}

Λαμβάνει τον αναγνωρισμένο πίνακα BarCodeResult

**Returns:** recognized BarCodeResult array

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " +  reader.getFoundBarCodes()[i].getCodeText());
```

### getFoundCount() {#getfoundcount}

Λαμβάνει τον αριθμό των αναγνωρισμένων barcodes

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
Value: The recognized barcodes count
```

### getQualitySettings() {#getqualitysettings}

Το QualitySettings επιτρέπει τη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης χειροκίνητα. Μπορείτε γρήγορα να ρυθμίσετε το QualitySettings με ενσωματωμένες προεπιλογές: HighPerformance, NormalQuality, HighQuality, MaxBarCodes ή μπορείτε να διαμορφώσετε χειροκίνητα ξεχωριστές επιλογές. Η προεπιλεγμένη τιμή του QualitySettings είναι NormalQuality.

**Returns:** QualitySettings to configure recognition quality and speed.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader

let reader = new BarCodeReader("test.png", null, null);
 //set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### getTimeout() {#gettimeout}

Λαμβάνει το timeout της διαδικασίας αναγνώρισης σε χιλιοστά του δευτερολέπτου.

**Returns:** The timeout.

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### readBarCodes() {#readbarcodes}

Αναγνάει το BarCodeResult από την εικόνα.

**Returns:** Returns array of recognized `BarCodeResult`s on the image. If nothing is recognized, zero array is returned.

**Example:**

```js
//This sample shows how to read barcodes with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.readBarCodes();
for(let i = 0; reader.getFoundCount() > i; ++i)
   console.log("BarCode CodeText: " + reader.getFoundBarCodes()[i].getCodeText());
```

### setBarCodeImage(imageResource, …areas) {#setbarcodeimage}

Ορίζει την bitmap εικόνα και τις περιοχές για αναγνώριση. Πρέπει να κληθεί πριν τη μέθοδο ReadBarCodes().

| Παράμετρος | Περιγραφή |
| --- | --- |
| imageResource | Η εικόνα για την αναγνώριση. |
| περιοχές | Λίστα περιοχών για την αναγνώριση |

**Throws:** BarcodeException

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let bmp = "test.png";
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
var img = new Image();
img.src = 'path_to_image';
width = img.width;
height = img.height;
reader.setBarCodeImage(bmp, new Rectangle[] { new Rectangle(0, 0, width, height) });
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setBarCodeReadType(…types) {#setbarcodereadtype}

Ορίζει τον πίνακα τύπων SingleDecodeType για αναγνώριση. Πρέπει να κληθεί πριν τη μέθοδο readBarCodes().

| Παράμετρος | Περιγραφή |
| --- | --- |
| τύποι | Ο πίνακας τύπων SingleDecodeType για ανάγνωση. |

**Example:**

```js
//This sample shows how to detect Code39 and Code128 barcodes.
let reader = new BarCodeReader();
reader.setBarCodeReadType([ DecodeType.CODE_39, DecodeType.CODE_128 ]);
reader.setBarCodeImage("test.png");
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
    console.log("BarCode Type: " + result.getCodeTypeName());
    console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setQualitySettings() {#setqualitysettings}

Το QualitySettings επιτρέπει τη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης χειροκίνητα. Μπορείτε γρήγορα να ρυθμίσετε το QualitySettings με ενσωματωμένες προεπιλογές: HighPerformance, NormalQuality, HighQuality, MaxBarCodes ή μπορείτε να διαμορφώσετε χειροκίνητα ξεχωριστές επιλογές. Η προεπιλεγμένη τιμή του QualitySettings είναι NormalQuality.

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
  let result = results[i];
  console.log("BarCode CodeText: " + result.getCodeText());
}
```

### setTimeout(value) {#settimeout}

Ορίζει το timeout της διαδικασίας αναγνώρισης σε χιλιοστά του δευτερολέπτου.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Το timeout. |

**Example:**

```js
let reader = new BarCodeReader("test.png", null, null);
reader.setTimeout(5000);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```
