---
title: "BarCodeRegionParameters"
linktitle: "BarCodeRegionParameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Αντιπροσωπεύει την περιοχή του αναγνωρισμένου γραμμωτού κώδικα και τη γωνία του"
type: docs
weight: 100
url: /el/nodejs/aspose.barcode/barcoderegionparameters/
---

## BarCodeRegionParameters class

Αντιπροσωπεύει την περιοχή του αναγνωρισμένου γραμμωτού κώδικα και τη γωνία του

```js
new BarCodeRegionParameters()
```

**Example:**

```js
//This sample shows how to get barcode Angle and bounding quadrangle values
let generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
generator.save("test.png");
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("BarCode Angle: " + result.getRegion().getAngle());
   console.log("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
}
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals(obj)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η περίπτωση είναι ίση με μια καθορισμένη τιμή BarCodeRegionParameters. |
| [getAngle()](#getangle) | Λαμβάνει τη γωνία του barcode (0-360). Τιμή: Η γωνία για το barcode (0-360). |
| [getPoints()](#getpoints) | Λαμβάνει τον πίνακα Points που οριοθετεί την περιοχή του barcode. Τιμή: Επιστρέφει τον πίνακα Points που οριοθετεί την περιοχή του barcode. |
| [getQuadrangle()](#getquadrangle) | Λαμβάνει το Quadrangle που οριοθετεί την περιοχή του barcode. Τιμή: Επιστρέφει το Quadrangle που οριοθετεί την περιοχή του barcode. |
| [getRectangle()](#getrectangle) | Λαμβάνει το Rectangle που οριοθετεί την περιοχή του barcode. Τιμή: Επιστρέφει το Rectangle που οριοθετεί την περιοχή του barcode. |
| [hashCode()](#hashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά που αντιπροσωπεύει αυτό το BarCodeRegionParameters. |

### equals(obj) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η περίπτωση είναι ίση με μια καθορισμένη τιμή BarCodeRegionParameters.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Μια τιμή System.Object για σύγκριση με αυτήν την παρουσία. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getAngle() {#getangle}

Λαμβάνει τη γωνία του barcode (0-360). Τιμή: Η γωνία για το barcode (0-360).

### getPoints() {#getpoints}

Λαμβάνει τον πίνακα Points που οριοθετεί την περιοχή του barcode. Τιμή: Επιστρέφει τον πίνακα Points που οριοθετεί την περιοχή του barcode.

### getQuadrangle() {#getquadrangle}

Λαμβάνει το Quadrangle που οριοθετεί την περιοχή του barcode. Τιμή: Επιστρέφει το Quadrangle που οριοθετεί την περιοχή του barcode.

### getRectangle() {#getrectangle}

Λαμβάνει το Rectangle που οριοθετεί την περιοχή του barcode. Τιμή: Επιστρέφει το Rectangle που οριοθετεί την περιοχή του barcode.

### hashCode() {#hashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A 32-bit signed integer hash code.

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά που αντιπροσωπεύει αυτό το BarCodeRegionParameters.

**Returns:** A string that represents this BarCodeRegionParameters.
