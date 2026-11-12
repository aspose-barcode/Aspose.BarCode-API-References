---
title: "PdfParameters"
linktitle: "PdfParameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Περιτύλιγμα παραμέτρων PDF."
type: docs
weight: 780
url: /el/nodejs/aspose.barcode/pdfparameters/
---

## PdfParameters class

Περιτύλιγμα παραμέτρων PDF. Αναμένει μια υποκείμενη παρουσία `mwObject` που παρέχει τις αντίστοιχες μεθόδους getter/setter που επιστρέφουν/δέχονται συμβολοσειρές CMYK όπως "30_100_0_30" ή `null`.

```js
new PdfParameters(mwObject)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mwObject | αντικείμενο | – παρουσία της κλάσης Java PdfParameters |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [_initializeWrapperMembers()](#-initializewrappermembers) | αρχικοποιητής no-op |
| [getCMYKBackColor()](#getcmykbackcolor) | Τιμή χρώματος παρασκηνίου CMYK. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB. |
| [getCMYKBarColor()](#getcmykbarcolor) | Τιμή χρώματος CMYK του barcode. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB. |
| [getCMYKCaptionAboveColor()](#getcmykcaptionabovecolor) | Τιμή χρώματος CMYK της λεζάντας επάνω. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB. |
| [getCMYKCaptionBelowColor()](#getcmykcaptionbelowcolor) | Τιμή χρώματος CMYK της λεζάντας κάτω. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB. |
| [getCMYKCodetextColor()](#getcmykcodetextcolor) | Τιμή χρώματος CMYK του Codetext. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB. |
| [isTextAsPath()](#istextaspath) | Χρησιμοποιούνται διαδρομές αντί για κείμενο (χρησιμοποιήστε εάν οι χαρακτήρες Unicode δεν εμφανίζονται) Προεπιλεγμένη τιμή: false. |
| [setCMYKBackColor(value)](#setcmykbackcolor) | Τιμή χρώματος παρασκηνίου CMYK. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB. |
| [setCMYKBarColor(value)](#setcmykbarcolor) | Τιμή χρώματος CMYK του barcode. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB. |
| [setCMYKCaptionAboveColor(value)](#setcmykcaptionabovecolor) | Τιμή χρώματος CMYK της λεζάντας επάνω. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB. |
| [setCMYKCaptionBelowColor(value)](#setcmykcaptionbelowcolor) | Τιμή χρώματος CMYK της λεζάντας κάτω. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB. |
| [setCMYKCodetextColor(value)](#setcmykcodetextcolor) | Τιμή χρώματος CMYK του Codetext. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB. |
| [setTextAsPath()](#settextaspath) | Χρησιμοποιούνται διαδρομές αντί για κείμενο (χρησιμοποιήστε εάν οι χαρακτήρες Unicode δεν εμφανίζονται) Προεπιλεγμένη τιμή: false. |

### _initializeWrapperMembers() {#-initializewrappermembers}

αρχικοποιητής no-op

### getCMYKBackColor() {#getcmykbackcolor}

Τιμή χρώματος παρασκηνίου CMYK. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB.

**Returns:** CMYKColor\|null

### getCMYKBarColor() {#getcmykbarcolor}

Τιμή χρώματος CMYK του barcode. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB.

**Returns:** CMYKColor\|null

### getCMYKCaptionAboveColor() {#getcmykcaptionabovecolor}

Τιμή χρώματος CMYK της λεζάντας επάνω. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB.

**Returns:** CMYKColor\|null

### getCMYKCaptionBelowColor() {#getcmykcaptionbelowcolor}

Τιμή χρώματος CMYK της λεζάντας κάτω. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB.

**Returns:** CMYKColor\|null

### getCMYKCodetextColor() {#getcmykcodetextcolor}

Τιμή χρώματος CMYK του Codetext. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB.

**Returns:** CMYKColor\|null

### isTextAsPath() {#istextaspath}

Χρησιμοποιούνται διαδρομές αντί για κείμενο (χρησιμοποιήστε εάν οι χαρακτήρες Unicode δεν εμφανίζονται) Προεπιλεγμένη τιμή: false.

### setCMYKBackColor(value) {#setcmykbackcolor}

Τιμή χρώματος παρασκηνίου CMYK. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB.

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | CMYKColor\ | null |  |

### setCMYKBarColor(value) {#setcmykbarcolor}

Τιμή χρώματος CMYK του barcode. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB.

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | CMYKColor\ | null |  |

### setCMYKCaptionAboveColor(value) {#setcmykcaptionabovecolor}

Τιμή χρώματος CMYK της λεζάντας επάνω. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB.

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | CMYKColor\ | null |  |

### setCMYKCaptionBelowColor(value) {#setcmykcaptionbelowcolor}

Τιμή χρώματος CMYK της λεζάντας κάτω. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB.

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | CMYKColor\ | null |  |

### setCMYKCodetextColor(value) {#setcmykcodetextcolor}

Τιμή χρώματος CMYK του Codetext. Null σημαίνει ότι το χρώμα CMYK δεν χρησιμοποιείται, αντίθετα χρησιμοποιείται το κανονικό χρώμα RGB.

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | CMYKColor\ | null |  |

### setTextAsPath() {#settextaspath}

Χρησιμοποιούνται διαδρομές αντί για κείμενο (χρησιμοποιήστε εάν οι χαρακτήρες Unicode δεν εμφανίζονται) Προεπιλεγμένη τιμή: false.
