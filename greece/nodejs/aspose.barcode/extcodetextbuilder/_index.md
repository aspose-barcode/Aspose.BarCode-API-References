---
title: "ExtCodetextBuilder"
linktitle: "ExtCodetextBuilder"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Βοηθητική κλάση για αυτόματη δημιουργία κώδικα κειμένου του Extended Codetext Mode"
type: docs
weight: 400
url: /el/nodejs/aspose.barcode/extcodetextbuilder/
---

## ExtCodetextBuilder class

Βοηθητική κλάση για αυτόματη δημιουργία κώδικα κειμένου του Extended Codetext Mode

```js
new ExtCodetextBuilder()
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addECICodetext(ECIEncoding, codetext)](#addecicodetext) | Προσθέτει κείμενο κώδικα με Αναγνωριστικό Επεκταμένου Καναλιού |
| [addPlainCodetext(codetext)](#addplaincodetext) | Προσθέτει απλό κείμενο κώδικα στα στοιχεία επεκταμένου κώδικα |
| [clear()](#clear) | Καθαρίζει τα στοιχεία επεκταμένου κώδικα |
| [getExtendedCodetext()](#getextendedcodetext) | Δημιουργεί επεκταμένο κείμενο κώδικα από τη λίστα στοιχείων δημιουργίας |

### addECICodetext(ECIEncoding, codetext) {#addecicodetext}

Προσθέτει κείμενο κώδικα με Αναγνωριστικό Επεκταμένου Καναλιού

| Παράμετρος | Περιγραφή |
| --- | --- |
| ECIEncoding | Extended Channel Identifier |
| codetext | Κείμενο κώδικα σε Unicode για προσθήκη ως στοιχείο επεκταμένου κώδικα με Αναγνωριστικό Επεκταμένου Καναλιού |

### addPlainCodetext(codetext) {#addplaincodetext}

Προσθέτει απλό κείμενο κώδικα στα στοιχεία επεκταμένου κώδικα

| Παράμετρος | Περιγραφή |
| --- | --- |
| codetext | Codetext σε unicode για προσθήκη ως στοιχείο εκτεταμένου codetext |

### clear() {#clear}

Καθαρίζει τα στοιχεία επεκταμένου κώδικα

### getExtendedCodetext() {#getextendedcodetext}

Δημιουργεί επεκταμένο κείμενο κώδικα από τη λίστα στοιχείων δημιουργίας

**Returns:** Return string of extended codetext
