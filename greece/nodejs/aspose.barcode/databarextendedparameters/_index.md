---
title: "DataBarExtendedParameters"
linktitle: "DataBarExtendedParameters"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Αποθηκεύει πρόσθετες πληροφορίες DataBar του αναγνωρισμένου barcode"
type: docs
weight: 310
url: /el/nodejs/aspose.barcode/databarextendedparameters/
---

## DataBarExtendedParameters class

Αποθηκεύει πρόσθετες πληροφορίες DataBar του αναγνωρισμένου barcode

```js
new DataBarExtendedParameters()
```

**Example:**

```js
let reader = new BarCodeReader("test.png", DecodeType.DATABAR_OMNI_DIRECTIONAL);
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode Type: " + result.getCodeTypeName());
   console.log("BarCode CodeText: " + result.getCodeText());
   console.log("QR Structured Append Quantity: " + result.getExtended().getQR().getQRStructuredAppendModeBarCodesQuantity());
}
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals(obj)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή DataBarExtendedParameters. |
| [hashCode()](#hashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [is2DCompositeComponent()](#is2dcompositecomponent) | Λαμβάνει τη σημαία του σύνθετου στοιχείου DataBar 2D. Η προεπιλεγμένη τιμή είναι ψευδής. |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού. |

### equals(obj) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή DataBarExtendedParameters.

| Παράμετρος | Περιγραφή |
| --- | --- |
| obj | Τιμή DataBarExtendedParameters για σύγκριση με αυτήν την παρουσία. |

**Returns:** true if obj has the same value as this instance; otherwise, false .

### hashCode() {#hashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A 32-bit signed integer hash code.

### is2DCompositeComponent() {#is2dcompositecomponent}

Λαμβάνει τη σημαία του σύνθετου στοιχείου DataBar 2D. Η προεπιλεγμένη τιμή είναι ψευδής.

**Returns:** The DataBar 2D composite component flag.

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού.

**Returns:** A string that represents this .
