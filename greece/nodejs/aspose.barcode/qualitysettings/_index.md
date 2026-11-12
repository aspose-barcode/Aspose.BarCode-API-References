---
title: "QualitySettings"
linktitle: "QualitySettings"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Το QualitySettings επιτρέπει τη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης χειροκίνητα."
type: docs
weight: 860
url: /el/nodejs/aspose.barcode/qualitysettings/
---

## QualitySettings class

Το QualitySettings επιτρέπει τη διαμόρφωση της ποιότητας και της ταχύτητας αναγνώρισης χειροκίνητα. Μπορείτε γρήγορα να ρυθμίσετε το QualitySettings με ενσωματωμένες προεπιλογές: HighPerformance, NormalQuality, HighQuality, MaxBarCodes ή μπορείτε να διαμορφώσετε χειροκίνητα ξεχωριστές επιλογές. Η προεπιλεγμένη τιμή του QualitySettings είναι NormalQuality.

```js
new QualitySettings()
```

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

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getHighPerformance()](#gethighperformance) *(static)* | Προεπιλογή ποιότητας αναγνώρισης HighPerformance. Τα barcode υψηλής ποιότητας αναγνωρίζονται καλά σε αυτή τη λειτουργία. |
| [getHighQuality()](#gethighquality) *(static)* | Προεπιλογή ποιότητας αναγνώρισης HighQuality. Αυτή η προεπιλογή έχει αναπτυχθεί για barcode χαμηλής ποιότητας. |
| [getMaxQuality()](#getmaxquality) *(static)* | Προεπιλογή ποιότητας αναγνώρισης MaxQuality. Αυτή η προεπιλογή έχει αναπτυχθεί για την αναγνώριση όλων των πιθανών barcode, ακόμη και λανθασμένων barco |
| [getNormalQuality()](#getnormalquality) *(static)* | Προεπιλογή ποιότητας αναγνώρισης NormalQuality. Κατάλληλη για τα περισσότερα barcode |
| [getAllowIncorrectBarcodes()](#getallowincorrectbarcodes) | Επιτρέπει στη μηχανή να αναγνωρίζει barcode που έχουν εσφαλμένο checksum ή εσφαλμένες τιμές. Η λειτουργία μπορεί να χρησιμοποιηθεί για την αναγνώριση dam |
| [getBarcodeQuality()](#getbarcodequality) | Λειτουργία που επιτρέπει στις μεθόδους να αναγνωρίζουν στοιχεία barcode με την επιλεγμένη ποιότητα. Στοιχείο barcode με χαμηλότερη ποιότητα r |
| [getComplexBackground()](#getcomplexbackground) | Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες. |
| [getDeconvolution()](#getdeconvolution) | Λειτουργία αποσύνθεσης (αποκατάσταση εικόνας) που ορίζει το επίπεδο υποβάθμισης της εικόνας. Αρχικά η αποσύνθεση είναι μια λειτουργία |
| [getInverseImage()](#getinverseimage) | Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση κωδικών barcode σε εικόνες με αντιστροφή χρωμάτων (λαμπρότητα). |
| [getMinimalXDimension()](#getminimalxdimension) | Ελάχιστο μέγεθος του XDimension σε εικονοστοιχεία που χρησιμοποιείται με το UseMinimalXDimension. |
| [getXDimension()](#getxdimension) | Λειτουργία αναγνώρισης που ορίζει το μέγεθος (από 1 έως άπειρο) του ελάχιστου στοιχείου του barcode: κελί πλέγματος ή γραμμή. |
| [setAllowIncorrectBarcodes(value)](#setallowincorrectbarcodes) | Επιτρέπει στη μηχανή να αναγνωρίζει barcode που έχουν εσφαλμένο checksum ή εσφαλμένες τιμές. Η λειτουργία μπορεί να χρησιμοποιηθεί για την αναγνώριση dam |
| [setBarcodeQuality(value)](#setbarcodequality) | Λειτουργία που επιτρέπει στις μεθόδους να αναγνωρίζουν στοιχεία barcode με την επιλεγμένη ποιότητα. Στοιχείο barcode με χαμηλότερη ποιότητα r |
| [setComplexBackground(value)](#setcomplexbackground) | Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες. |
| [setDeconvolution(value)](#setdeconvolution) | Λειτουργία αποσύνθεσης (αποκατάσταση εικόνας) που ορίζει το επίπεδο υποβάθμισης της εικόνας. Αρχικά η αποσύνθεση είναι μια λειτουργία |
| [setInverseImage(value)](#setinverseimage) | Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση κωδικών barcode σε εικόνες με αντιστροφή χρωμάτων (λαμπρότητα). |
| [setMinimalXDimension(value)](#setminimalxdimension) | Ελάχιστο μέγεθος του XDimension σε εικονοστοιχεία που χρησιμοποιείται με το UseMinimalXDimension. |
| [setXDimension(value)](#setxdimension) | Λειτουργία αναγνώρισης που ορίζει το μέγεθος (από 1 έως άπειρο) του ελάχιστου στοιχείου του barcode: κελί πλέγματος ή γραμμή. |

### getHighPerformance() (static) {#gethighperformance}

Προεπιλογή ποιότητας αναγνώρισης HighPerformance. Τα barcode υψηλής ποιότητας αναγνωρίζονται καλά σε αυτή τη λειτουργία.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighPerformance());
```

### getHighQuality() (static) {#gethighquality}

Προεπιλογή ποιότητας αναγνώρισης HighQuality. Αυτή η προεπιλογή έχει αναπτυχθεί για barcode χαμηλής ποιότητας.

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighQuality());
```

### getMaxQuality() (static) {#getmaxquality}

Προεπιλογή ποιότητας αναγνώρισης MaxQuality. Αυτή η προεπιλογή έχει αναπτυχθεί για την αναγνώριση όλων των δυνατών barcode, ακόμη και λανθασμένων barcode. Αυτό το παράδειγμα δείχνει πώς να χρησιμοποιήσετε τη λειτουργία MaxQuality reader = new BarCodeReader("test.png"null, null, DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128); { reader.setQualitySettings(QualitySettings.getMaxQuality()); for(let i = 0; i < reader.readBarCodes().length; i++) echo (reader.getFoundBarcodes()[i].getCodeText()); } Τιμή: Προεπιλογή ποιότητας αναγνώρισης MaxQuality.

### getNormalQuality() (static) {#getnormalquality}

Προεπιλογή ποιότητας αναγνώρισης NormalQuality. Κατάλληλη για τα περισσότερα barcode

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getNormalQuality());
```

### getAllowIncorrectBarcodes() {#getallowincorrectbarcodes}

Επιτρέπει στη μηχανή να αναγνωρίζει barcode που έχουν εσφαλμένο checksum ή εσφαλμένες τιμές. Η λειτουργία μπορεί να χρησιμοποιηθεί για την αναγνώριση κατεστραμμένων barcode με λανθασμένο κείμενο.

**Returns:** Allows engine to recognize incorrect barcodes.

### getBarcodeQuality() {#getbarcodequality}

Λειτουργία που ενεργοποιεί μεθόδους για την αναγνώριση στοιχείων barcode με την επιλεγμένη ποιότητα. Στοιχείο barcode με χαμηλότερη ποιότητα απαιτεί πιο απαιτητικές μεθόδους, γεγονός που επιβραδύνει την αναγνώριση.

**Returns:** Mode which enables methods to recognize barcode elements with the selected quality.

### getComplexBackground() {#getcomplexbackground}

Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες.

**Returns:** Additional recognition of color barcodes on color images.

### getDeconvolution() {#getdeconvolution}

Λειτουργία αποσύνθεσης (αποκατάσταση εικόνας) που ορίζει το επίπεδο υποβάθμισης της εικόνας. Αρχικά η αποσύνθεση είναι μια λειτουργία που μπορεί να αποκαταστήσει μια εικόνα που έχει υποβαθμιστεί (συνελιχθεί) από οποιαδήποτε φυσική λειτουργία όπως η θολούρα, κατά τη λήψη της εικόνας με την κάμερα. Επειδή δεν μπορούμε να εντοπίσουμε τη λειτουργία της εικόνας που τη διαφθείρει, πρέπει να ελέγξουμε τις πιο γνωστές λειτουργίες όπως η οξύτητα ή η μαθηματική μορφολογία.

**Returns:** Deconvolution mode which defines level of image degradation.

### getInverseImage() {#getinverseimage}

Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση κωδικών barcode σε εικόνες με αντιστροφή χρωμάτων (λαμπρότητα).

**Returns:** Additional recognition of barcodes on images with inverse colors

### getMinimalXDimension() {#getminimalxdimension}

Ελάχιστο μέγεθος του XDimension σε εικονοστοιχεία που χρησιμοποιείται με το UseMinimalXDimension.

**Returns:** Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

### getXDimension() {#getxdimension}

Λειτουργία αναγνώρισης που ορίζει το μέγεθος (από 1 έως άπειρο) του ελάχιστου στοιχείου του barcode: κελί πλέγματος ή γραμμή.

**Returns:** size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

### setAllowIncorrectBarcodes(value) {#setallowincorrectbarcodes}

Επιτρέπει στη μηχανή να αναγνωρίζει barcode που έχουν εσφαλμένο checksum ή εσφαλμένες τιμές. Η λειτουργία μπορεί να χρησιμοποιηθεί για την αναγνώριση κατεστραμμένων barcode με λανθασμένο κείμενο.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Επιτρέπει στη μηχανή να αναγνωρίζει λανθασμένα barcode. |

### setBarcodeQuality(value) {#setbarcodequality}

Λειτουργία που ενεργοποιεί μεθόδους για την αναγνώριση στοιχείων barcode με την επιλεγμένη ποιότητα. Στοιχείο barcode με χαμηλότερη ποιότητα απαιτεί πιο απαιτητικές μεθόδους, γεγονός που επιβραδύνει την αναγνώριση.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Λειτουργία που ενεργοποιεί μεθόδους για την αναγνώριση στοιχείων barcode με την επιλεγμένη ποιότητα. |

### setComplexBackground(value) {#setcomplexbackground}

Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Πρόσθετη αναγνώριση χρωματικών barcode σε χρωματικές εικόνες. |

### setDeconvolution(value) {#setdeconvolution}

Λειτουργία αποσύνθεσης (αποκατάσταση εικόνας) που ορίζει το επίπεδο υποβάθμισης της εικόνας. Αρχικά η αποσύνθεση είναι μια λειτουργία που μπορεί να αποκαταστήσει μια εικόνα που έχει υποβαθμιστεί (συνελιχθεί) από οποιαδήποτε φυσική λειτουργία όπως η θολούρα, κατά τη λήψη της εικόνας με την κάμερα. Επειδή δεν μπορούμε να εντοπίσουμε τη λειτουργία της εικόνας που τη διαφθείρει, πρέπει να ελέγξουμε τις πιο γνωστές λειτουργίες όπως η οξύτητα ή η μαθηματική μορφολογία.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Λειτουργία αποσύνθεσης που ορίζει το επίπεδο υποβάθμισης της εικόνας. |

### setInverseImage(value) {#setinverseimage}

Λειτουργία που ενεργοποιεί ή απενεργοποιεί την πρόσθετη αναγνώριση κωδικών barcode σε εικόνες με αντιστροφή χρωμάτων (λαμπρότητα).

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Πρόσθετη αναγνώριση barcode σε εικόνες με αντίστροφα χρώματα |

### setMinimalXDimension(value) {#setminimalxdimension}

Ελάχιστο μέγεθος του XDimension σε εικονοστοιχεία που χρησιμοποιείται με το UseMinimalXDimension.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | Ελάχιστο μέγεθος του XDimension σε εικονοστοιχεία που χρησιμοποιείται με το UseMinimalXDimension. |

### setXDimension(value) {#setxdimension}

Λειτουργία αναγνώρισης που ορίζει το μέγεθος (από 1 έως άπειρο) του ελάχιστου στοιχείου του barcode: κελί πλέγματος ή γραμμή.

| Παράμετρος | Περιγραφή |
| --- | --- |
| τιμή | (από 1 έως άπειρο) του ελάχιστου στοιχείου του barcode: κελί πλέγματος ή γραμμή. |
