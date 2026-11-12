---
title: "Unit"
linktitle: "Unit"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Καθορίζει την τιμή μεγέθους σε διαφορετικές μονάδες (Pixel, Inches, κ.λπ.)."
type: docs
weight: 960
url: /el/nodejs/aspose.barcode/unit/
---

## Unit class

Καθορίζει την τιμή μεγέθους σε διαφορετικές μονάδες (Pixel, Inches, κ.λπ.).

```js
new Unit()
```

**Example:**

```js
//This sample shows how to create and save a BarCode image.
   let generator = new BarcodeGenerator(EncodeTypes.CODE_128);
   generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
   generator.save("test.png", BarcodeImageFormat.PNG);
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals(obj)](#equals) | Καθορίζει εάν αυτή η παρουσία και ένα καθορισμένο αντικείμενο, το οποίο πρέπει επίσης να είναι αντικείμενο Unit, έχουν την ίδια τιμή. |
| [getDocument()](#getdocument) | Λαμβάνει την τιμή μεγέθους σε μονάδες εγγράφου. |
| [getInches()](#getinches) | Λαμβάνει την τιμή μεγέθους σε ίντσες. |
| [getMillimeters()](#getmillimeters) | Λαμβάνει την τιμή μεγέθους σε χιλιοστά. |
| [getPixels()](#getpixels) | Λαμβάνει την τιμή μεγέθους σε εικονοστοιχεία. |
| [getPoint()](#getpoint) | Λαμβάνει την τιμή μεγέθους σε σημεία. |
| [setDocument()](#setdocument) | Ορίζει την τιμή μεγέθους σε μονάδες εγγράφου. |
| [setInches()](#setinches) | Ορίζει την τιμή μεγέθους σε ίντσες. |
| [setMillimeters()](#setmillimeters) | Ορίζει την τιμή μεγέθους σε χιλιοστά. |
| [setPixels()](#setpixels) | Ορίζει την τιμή μεγέθους σε εικονοστοιχεία. |
| [setPoint()](#setpoint) | Ορίζει την τιμή μεγέθους σε σημεία. |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη αναπαράσταση συμβολοσειράς αυτού του Unit. |

### equals(obj) {#equals}

Καθορίζει εάν αυτή η παρουσία και ένα καθορισμένο αντικείμενο, το οποίο πρέπει επίσης να είναι αντικείμενο Unit, έχουν την ίδια τιμή.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Το Unit για σύγκριση με αυτή την παρουσία. |

**Returns:** true if obj is a Unit and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.

### getDocument() {#getdocument}

Λαμβάνει την τιμή μεγέθους σε μονάδες εγγράφου.

### getInches() {#getinches}

Λαμβάνει την τιμή μεγέθους σε ίντσες.

### getMillimeters() {#getmillimeters}

Λαμβάνει την τιμή μεγέθους σε χιλιοστά.

### getPixels() {#getpixels}

Λαμβάνει την τιμή μεγέθους σε εικονοστοιχεία.

### getPoint() {#getpoint}

Λαμβάνει την τιμή μεγέθους σε σημεία.

### setDocument() {#setdocument}

Ορίζει την τιμή μεγέθους σε μονάδες εγγράφου.

### setInches() {#setinches}

Ορίζει την τιμή μεγέθους σε ίντσες.

### setMillimeters() {#setmillimeters}

Ορίζει την τιμή μεγέθους σε χιλιοστά.

### setPixels() {#setpixels}

Ορίζει την τιμή μεγέθους σε εικονοστοιχεία.

### setPoint() {#setpoint}

Ορίζει την τιμή μεγέθους σε σημεία.

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη αναπαράσταση συμβολοσειράς αυτού του Unit.

**Returns:** A string that represents this Unit.
