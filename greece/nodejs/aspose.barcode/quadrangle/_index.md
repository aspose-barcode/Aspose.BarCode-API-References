---
title: "Quadrangle"
linktitle: "Quadrangle"
second_title: "Αναφορά API του Aspose.BarCode για Node.js μέσω Java"
description: "Αποθηκεύει ένα σύνολο τεσσάρων Points που αντιπροσωπεύουν μια περιοχή Quadrangle."
type: docs
weight: 850
url: /el/nodejs/aspose.barcode/quadrangle/
---

## Quadrangle class

Αποθηκεύει ένα σύνολο τεσσάρων Points που αντιπροσωπεύουν μια περιοχή Quadrangle.

```js
new Quadrangle(leftTop, rightTop, rightBottom, leftBottom)
```

Αρχικοποιεί μια νέα παρουσία της δομής Quadrangle με τα περιγραφικά σημεία.

| Παράμετρος | Περιγραφή |
| --- | --- |
| leftTop | Ένα Point που αντιπροσωπεύει την αριστερή-πάνω γωνία του Quadrangle. |
| rightTop | Ένα Point που αντιπροσωπεύει τη δεξιά-πάνω γωνία του Quadrangle. |
| rightBottom | Ένα Point που αντιπροσωπεύει τη δεξιά-κάτω γωνία του Quadrangle. |
| leftBottom | Ένα Point που αντιπροσωπεύει την αριστερή-κάτω γωνία του Quadrangle. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [contains(pt)](#contains) | Καθορίζει εάν το συγκεκριμένο Point περιέχεται μέσα σε αυτή τη δομή Quadrangle. |
| [containsPoint(x, y)](#containspoint) | Καθορίζει εάν το συγκεκριμένο point περιέχεται μέσα σε αυτή τη δομή Quadrangle. |
| [containsQuadrangle(quad)](#containsquadrangle) | Καθορίζει εάν το συγκεκριμένο Quadrangle περιέχεται ή τέμνει αυτή τη δομή Quadrangle. |
| [containsRectangle(rect)](#containsrectangle) | Καθορίζει εάν το συγκεκριμένο Rectangle περιέχεται ή τέμνει αυτή τη δομή Quadrangle. |
| [equals(other)](#equals) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια συγκεκριμένη τιμή Quadrangle. |
| [getBoundingRectangle()](#getboundingrectangle) | Δημιουργεί Rectangle που περιβάλλει αυτό το Quadrangle |
| [getLeftBottom()](#getleftbottom) | Λαμβάνει το Point της αριστερής-κάτω γωνίας του Quadrangle regionValue: Ένα Point της αριστερής-κάτω γωνίας του Quadrangle region |
| [getLeftTop()](#getlefttop) | Λαμβάνει το Point της αριστερής-πάνω γωνίας του Quadrangle regionValue: Ένα Point της αριστερής-πάνω γωνίας του Quadrangle region |
| [getRightBottom()](#getrightbottom) | Λαμβάνει το Point της δεξιάς-κάτω γωνίας του Quadrangle regionValue: Ένα Point της δεξιάς-κάτω γωνίας του Quadrangle region |
| [getRightTop()](#getrighttop) | Λαμβάνει το Point της δεξιάς-πάνω γωνίας του Quadrangle regionValue: Ένα Point της δεξιάς-πάνω γωνίας του Quadrangle region |
| [hashCode()](#hashcode) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [isEmpty()](#isempty) | Δοκιμάζει εάν όλα τα σημεία αυτού του τετράγωνου έχουν τιμές μηδέν.Τιμή: Επιστρέφει true εάν όλα τα σημεία αυτού του τετράγωνου έχουν |
| [setLeftBottom()](#setleftbottom) | Ορίζει το αριστερό-κάτω σημείο γωνίας της περιοχής του τετράγωνουΤιμή: Ένα αριστερό-κάτω σημείο γωνίας της περιοχής του τετράγωνου |
| [setLeftTop()](#setlefttop) | Ορίζει το αριστερό-πάνω σημείο γωνίας της περιοχής του τετράγωνουΤιμή: Ένα αριστερό-πάνω σημείο γωνίας της περιοχής του τετράγωνου |
| [setRightBottom()](#setrightbottom) | Ορίζει το δεξιό-κάτω σημείο γωνίας της περιοχής του τετράγωνουΤιμή: Ένα δεξιό-κάτω σημείο γωνίας της περιοχής του τετράγωνου |
| [setRightTop()](#setrighttop) | Ορίζει το δεξιό-πάνω σημείο γωνίας της περιοχής του τετράγωνουΤιμή: Ένα δεξιό-πάνω σημείο γωνίας της περιοχής του τετράγωνου |
| [toString()](#tostring) | Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά αναπαράστασης αυτού του τετράγωνου. |

### contains(pt) {#contains}

Καθορίζει εάν το συγκεκριμένο Point περιέχεται μέσα σε αυτή τη δομή Quadrangle.

| Παράμετρος | Περιγραφή |
| --- | --- |
| pt | Το σημείο για δοκιμή. |

**Returns:** true if Point is contained within this Quadrangle structure; otherwise, false.

### containsPoint(x, y) {#containspoint}

Καθορίζει εάν το συγκεκριμένο point περιέχεται μέσα σε αυτή τη δομή Quadrangle.

| Παράμετρος | Περιγραφή |
| --- | --- |
| x | Η συντεταγμένη x του σημείου. |
| y | Η συντεταγμένη y του σημείου. |

**Returns:** Returns true if point is contained within this Quadrangle structure; otherwise, false.

### containsQuadrangle(quad) {#containsquadrangle}

Καθορίζει εάν το συγκεκριμένο Quadrangle περιέχεται ή τέμνει αυτή τη δομή Quadrangle.

| Παράμετρος | Περιγραφή |
| --- | --- |
| quad | Το τετράγωνο για δοκιμή. |

**Returns:** Returns true if Quadrangle is contained or intersect this Quadrangle structure; otherwise, false.

### containsRectangle(rect) {#containsrectangle}

Καθορίζει εάν το συγκεκριμένο Rectangle περιέχεται ή τέμνει αυτή τη δομή Quadrangle.

| Παράμετρος | Περιγραφή |
| --- | --- |
| rect | Το ορθογώνιο για δοκιμή. |

**Returns:** Returns true if Rectangle is contained or intersect this Quadrangle structure; otherwise, false.

### equals(other) {#equals}

Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια συγκεκριμένη τιμή Quadrangle.

| Παράμετρος | Περιγραφή |
| --- | --- |
| άλλο | Μια τιμή τετράγωνου για σύγκριση με αυτήν την παρουσία. |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getBoundingRectangle() {#getboundingrectangle}

Δημιουργεί Rectangle που περιβάλλει αυτό το Quadrangle

**Returns:** returns Rectangle bounding this Quadrangle

### getLeftBottom() {#getleftbottom}

Λαμβάνει το Point της αριστερής-κάτω γωνίας του Quadrangle regionValue: Ένα Point της αριστερής-κάτω γωνίας του Quadrangle region

### getLeftTop() {#getlefttop}

Λαμβάνει το Point της αριστερής-πάνω γωνίας του Quadrangle regionValue: Ένα Point της αριστερής-πάνω γωνίας του Quadrangle region

### getRightBottom() {#getrightbottom}

Λαμβάνει το Point της δεξιάς-κάτω γωνίας του Quadrangle regionValue: Ένα Point της δεξιάς-κάτω γωνίας του Quadrangle region

### getRightTop() {#getrighttop}

Λαμβάνει το Point της δεξιάς-πάνω γωνίας του Quadrangle regionValue: Ένα Point της δεξιάς-πάνω γωνίας του Quadrangle region

### hashCode() {#hashcode}

Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

Δοκιμάζει εάν όλα τα σημεία αυτού του τετράγωνου έχουν τιμές μηδέν.Τιμή: Επιστρέφει true εάν όλα τα σημεία αυτού του τετράγωνου έχουν τιμές μηδέν· διαφορετικά, false.

### setLeftBottom() {#setleftbottom}

Ορίζει το αριστερό-κάτω σημείο γωνίας της περιοχής του τετράγωνουΤιμή: Ένα αριστερό-κάτω σημείο γωνίας της περιοχής του τετράγωνου

### setLeftTop() {#setlefttop}

Ορίζει το αριστερό-πάνω σημείο γωνίας της περιοχής του τετράγωνουΤιμή: Ένα αριστερό-πάνω σημείο γωνίας της περιοχής του τετράγωνου

### setRightBottom() {#setrightbottom}

Ορίζει το δεξιό-κάτω σημείο γωνίας της περιοχής του τετράγωνουΤιμή: Ένα δεξιό-κάτω σημείο γωνίας της περιοχής του τετράγωνου

### setRightTop() {#setrighttop}

Ορίζει το δεξιό-πάνω σημείο γωνίας της περιοχής του τετράγωνουΤιμή: Ένα δεξιό-πάνω σημείο γωνίας της περιοχής του τετράγωνου

### toString() {#tostring}

Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά αναπαράστασης αυτού του τετράγωνου.

**Returns:** A string that represents this Quadrangle.
