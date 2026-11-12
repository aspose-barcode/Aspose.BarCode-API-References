---
title: "CodetextParameters"
linktitle: "CodetextParameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Παράμετροι Codetext."
type: docs
weight: 270
url: /el/nodejs/aspose.barcode/codetextparameters/
---

## CodetextParameters class

Παράμετροι Codetext.

```js
new CodetextParameters()
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getAlignment()](#getalignment) | Λαμβάνει την ευθυγράμμιση του κειμένου κώδικα. Προεπιλεγμένη τιμή: TextAlignment.CENTER. |
| [getColor()](#getcolor) | Καθορίστε το χρώμα εμφάνισης του CodeText. Προεπιλεγμένη τιμή BLACK. |
| [getFont()](#getfont) | Καθορίστε τη γραμματοσειρά εμφάνισης του CodeText. Προεπιλεγμένη τιμή: Arial 5pt regular. Αγνοείται εάν το FontMode οριστεί σε FontMode.AUTO. |
| [getFontMode()](#getfontmode) | Καθορίστε το FontMode. Εάν το FontMode οριστεί σε Auto, το μέγεθος γραμματοσειράς θα υπολογιστεί αυτόματα βάσει της τιμής xDimension. It i |
| [getLocation()](#getlocation) | Καθορίστε τη θέση εμφάνισης του CodeText, ορίστε σε CodeLocation.NONE για απόκρυψη του CodeText. Προεπιλεγμένη τιμή: CodeLocation.BELOW. |
| [getNoWrap()](#getnowrap) | Καθορίστε την αναδίπλωση λέξεων (αλλαγές γραμμής) μέσα στο κείμενο. Προεπιλεγμένη τιμή: false. |
| [getSpace()](#getspace) | Απόσταση μεταξύ του CodeText και του BarCode σε μονάδες. Προεπιλεγμένη τιμή: 2pt. Αγνοείται για EAN8, EAN13, UPCE, UPCA, ISBN, |
| [getTwoDDisplayText()](#gettwoddisplaytext) | Κείμενο που θα εμφανίζεται αντί του codetext σε 2D γραμμωτούς κώδικες. Χρησιμοποιείται για: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [setAlignment()](#setalignment) | Ορίζει την ευθυγράμμιση του κειμένου κώδικα. Προεπιλεγμένη τιμή: TextAlignment.CENTER. |
| [setColor()](#setcolor) | Καθορίστε το χρώμα εμφάνισης του CodeText. Προεπιλεγμένη τιμή BLACK. |
| [setFont()](#setfont) | Καθορίστε τη γραμματοσειρά εμφάνισης του CodeText. Προεπιλεγμένη τιμή: Arial 5pt regular. Αγνοείται εάν το FontMode οριστεί σε FontMode.AUTO. |
| [setFontMode()](#setfontmode) | Καθορίστε το FontMode. Εάν το FontMode οριστεί σε Auto, το μέγεθος γραμματοσειράς θα υπολογιστεί αυτόματα βάσει της τιμής xDimension. It i |
| [setLocation()](#setlocation) | Καθορίστε τη θέση εμφάνισης του CodeText, ορίστε σε CodeLocation.NONE για απόκρυψη του CodeText. Προεπιλεγμένη τιμή: CodeLocation.NONE. |
| [setNoWrap()](#setnowrap) | Καθορίστε την αναδίπλωση λέξεων (αλλαγές γραμμής) μέσα στο κείμενο. Προεπιλεγμένη τιμή: false. |
| [setSpace()](#setspace) | Απόσταση μεταξύ του CodeText και του BarCode σε μονάδες. Προεπιλεγμένη τιμή: 2pt. Αγνοείται για EAN8, EAN13, UPCE, UPCA, ISBN, |
| [setTwoDDisplayText()](#settwoddisplaytext) | Κείμενο που θα εμφανίζεται αντί του codetext σε 2D γραμμωτούς κώδικες. Χρησιμοποιείται για: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCo |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του CodetextParameters. |

### getAlignment() {#getalignment}

Λαμβάνει την ευθυγράμμιση του κειμένου κώδικα. Προεπιλεγμένη τιμή: TextAlignment.CENTER.

### getColor() {#getcolor}

Καθορίστε το χρώμα εμφάνισης του CodeText. Προεπιλεγμένη τιμή BLACK.

### getFont() {#getfont}

Καθορίστε τη γραμματοσειρά εμφάνισης του CodeText. Προεπιλεγμένη τιμή: Arial 5pt regular. Αγνοείται εάν το FontMode οριστεί σε FontMode.AUTO.

### getFontMode() {#getfontmode}

Καθορίστε το FontMode. Εάν το FontMode οριστεί σε Auto, το μέγεθος γραμματοσειράς θα υπολογιστεί αυτόματα βάσει της τιμής xDimension. Συνιστάται η χρήση του FontMode.AUTO ειδικά σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION. Προεπιλεγμένη τιμή: FontMode.AUTO.

### getLocation() {#getlocation}

Καθορίστε τη θέση εμφάνισης του CodeText, ορίστε σε CodeLocation.NONE για απόκρυψη του CodeText. Προεπιλεγμένη τιμή: CodeLocation.BELOW.

### getNoWrap() {#getnowrap}

Καθορίστε την αναδίπλωση λέξεων (αλλαγές γραμμής) μέσα στο κείμενο. Προεπιλεγμένη τιμή: false.

### getSpace() {#getspace}

Απόσταση μεταξύ του CodeText και του BarCode σε μονάδες. Προεπιλεγμένη τιμή: 2pt. Αγνοείται για EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

### getTwoDDisplayText() {#gettwoddisplaytext}

Κείμενο που θα εμφανίζεται αντί για codetext σε 2D barcode. Χρησιμοποιείται για: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### setAlignment() {#setalignment}

Ορίζει την ευθυγράμμιση του κειμένου κώδικα. Προεπιλεγμένη τιμή: TextAlignment.CENTER.

### setColor() {#setcolor}

Καθορίστε το χρώμα εμφάνισης του CodeText. Προεπιλεγμένη τιμή BLACK.

### setFont() {#setfont}

Καθορίστε τη γραμματοσειρά εμφάνισης του CodeText. Προεπιλεγμένη τιμή: Arial 5pt regular. Αγνοείται εάν το FontMode οριστεί σε FontMode.AUTO.

### setFontMode() {#setfontmode}

Καθορίστε το FontMode. Εάν το FontMode οριστεί σε Auto, το μέγεθος γραμματοσειράς θα υπολογιστεί αυτόματα βάσει της τιμής xDimension. Συνιστάται η χρήση του FontMode.AUTO ειδικά σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION. Προεπιλεγμένη τιμή: FontMode.AUTO.

### setLocation() {#setlocation}

Καθορίστε τη θέση εμφάνισης του CodeText, ορίστε σε CodeLocation.NONE για απόκρυψη του CodeText. Προεπιλεγμένη τιμή: CodeLocation.NONE.

### setNoWrap() {#setnowrap}

Καθορίστε την αναδίπλωση λέξεων (αλλαγές γραμμής) μέσα στο κείμενο. Προεπιλεγμένη τιμή: false.

### setSpace() {#setspace}

Απόσταση μεταξύ του CodeText και του BarCode σε μονάδες. Προεπιλεγμένη τιμή: 2pt. Αγνοείται για EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

### setTwoDDisplayText() {#settwoddisplaytext}

Κείμενο που θα εμφανίζεται αντί για codetext σε 2D barcode. Χρησιμοποιείται για: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του CodetextParameters.

**Returns:** A string that represents this CodetextParameters.
