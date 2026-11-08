---
title: "Quadrangle"
second_title: "Aspose.BarCode για Java Αναφορά API"
description: "Αποθηκεύει ένα σύνολο τεσσάρων Points που αντιπροσωπεύουν μια περιοχή Quadrangle."
type: docs
weight: 39
url: /el/java/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Αποθηκεύει ένα σύνολο τεσσάρων Point που αντιπροσωπεύουν μια περιοχή Quadrangle.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-) | Αρχικοποιεί μια νέα παρουσία της κλάσης  Quadrangle  με τα περιγραφικά σημεία. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [EMPTY](#EMPTY) | Αναπαριστά μια κλάση  Quadrangle  με τις ιδιότητές της αμετάβλητες. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Καθορίζει αν το καθορισμένο  Quadrangle  περιέχεται ή τέμνει αυτήν την κλάση  Quadrangle . |
| [contains(int x, int y)](#contains-int-int-) | Καθορίζει αν το καθορισμένο σημείο περιέχεται μέσα σε αυτήν την κλάση  Quadrangle . |
| [contains(Point pt)](#contains-java.awt.Point-) | Καθορίζει αν το καθορισμένο  Point  περιέχεται μέσα σε αυτήν την κλάση  Quadrangle . |
| [contains(Rectangle rect)](#contains-java.awt.Rectangle-) | Καθορίζει αν το καθορισμένο  Rectangle  περιέχεται ή τέμνει αυτήν την κλάση  Quadrangle . |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή  Quadrangle . |
| [getBoundingRectangle()](#getBoundingRectangle--) | Δημιουργεί ένα  Rectangle  που περιβάλλει αυτό το  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Λαμβάνει το αριστερό-κάτω γωνιακό  Point  της περιοχής  Quadrangle |
| [getLeftTop()](#getLeftTop--) | Λαμβάνει το αριστερό-πάνω γωνιακό  Point  της περιοχής  Quadrangle |
| [getRightBottom()](#getRightBottom--) | Λαμβάνει το δεξιό-κάτω γωνιακό  Point  της περιοχής  Quadrangle |
| [getRightTop()](#getRightTop--) | Λαμβάνει το δεξιό-πάνω γωνιακό  Point  της περιοχής  Quadrangle |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [isEmpty()](#isEmpty--) | Δοκιμάζει αν όλα τα  Point  του  Quadrangle  έχουν τιμές μηδέν. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-java.awt.Point-) | Λαμβάνει το αριστερό-κάτω γωνιακό  Point  της περιοχής  Quadrangle |
| [setLeftTop(Point value)](#setLeftTop-java.awt.Point-) | Λαμβάνει το αριστερό-πάνω γωνιακό  Point  της περιοχής  Quadrangle |
| [setRightBottom(Point value)](#setRightBottom-java.awt.Point-) | Λαμβάνει το δεξιό-κάτω γωνιακό  Point  της περιοχής  Quadrangle |
| [setRightTop(Point value)](#setRightTop-java.awt.Point-) | Λαμβάνει το δεξιό-πάνω γωνιακό  Point  της περιοχής  Quadrangle |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του  Quadrangle . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  Quadrangle  με τα περιγραφικά σημεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| leftTop | java.awt.Point | Ένα  Point  που αντιπροσωπεύει την γωνία αριστερά-επάνω του Quadrangle. |
| rightTop | java.awt.Point | Ένα  Point  που αντιπροσωπεύει την γωνία δεξιά-επάνω του Quadrangle. |
| rightBottom | java.awt.Point | Ένα  Point  που αντιπροσωπεύει την γωνία δεξιά-κάτω του Quadrangle. |
| leftBottom | java.awt.Point | Ένα  Point  που αντιπροσωπεύει την γωνία αριστερά-κάτω του Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Αναπαριστά μια κλάση  Quadrangle  με τις ιδιότητές της αμετάβλητες.

Τιμή:  Quadrangle

### clone() {#clone--}
```
public Quadrangle clone()
```




**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


Καθορίζει αν το καθορισμένο  Quadrangle  περιέχεται ή τέμνει αυτήν την κλάση  Quadrangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | Το  Quadrangle  για δοκιμή. |

**Returns:**
boolean - Επιστρέφει  **true**  εάν το  Quadrangle  περιέχεται ή τέμνει αυτήν την κλάση  Quadrangle· διαφορετικά,  **false** .
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Καθορίζει αν το καθορισμένο σημείο περιέχεται μέσα σε αυτήν την κλάση  Quadrangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η συντεταγμένη του σημείου x. |
| y | int | Η συντεταγμένη του σημείου y. |

**Returns:**
boolean - Επιστρέφει  **true**  εάν το σημείο περιέχεται μέσα σε αυτήν την κλάση  Quadrangle· διαφορετικά,  **false** .
### contains(Point pt) {#contains-java.awt.Point-}
```
public boolean contains(Point pt)
```


Καθορίζει αν το καθορισμένο  Point  περιέχεται μέσα σε αυτήν την κλάση  Quadrangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | java.awt.Point | Το  Point  για δοκιμή. |

**Returns:**
boolean - Επιστρέφει  **true**  εάν το  Point  περιέχεται μέσα σε αυτήν την κλάση  Quadrangle· διαφορετικά,  **false** .
### contains(Rectangle rect) {#contains-java.awt.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Καθορίζει αν το καθορισμένο  Rectangle  περιέχεται ή τέμνει αυτήν την κλάση  Quadrangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | java.awt.Rectangle | Το  Rectangle  για δοκιμή. |

**Returns:**
boolean - Επιστρέφει  **true**  εάν το  Rectangle  περιέχεται ή τέμνει αυτήν την κλάση  Quadrangle· διαφορετικά,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή  Quadrangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Μια  Quadrangle  τιμή για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean -  **true**  εάν το obj έχει την ίδια τιμή με αυτήν την παρουσία· διαφορετικά,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Δημιουργεί ένα  Rectangle  που περιβάλλει αυτό το  Quadrangle

**Returns:**
java.awt.Rectangle - επιστρέφει  Rectangle  που περιβάλλει αυτό το Quadrangle
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLeftBottom() {#getLeftBottom--}
```
public Point getLeftBottom()
```


Λαμβάνει το αριστερό-κάτω γωνιακό  Point  της περιοχής  Quadrangle

Τιμή: Ένα αριστερό-κάτω γωνιακό  Point  της περιοχής Quadrangle

**Returns:**
java.awt.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Λαμβάνει το αριστερό-πάνω γωνιακό  Point  της περιοχής  Quadrangle

Τιμή: Ένα αριστερό-πάνω γωνιακό  Point  της περιοχής Quadrangle

**Returns:**
java.awt.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Λαμβάνει το δεξιό-κάτω γωνιακό  Point  της περιοχής  Quadrangle

Τιμή: Ένα δεξιό-κάτω γωνιακό  Point  της περιοχής Quadrangle

**Returns:**
java.awt.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Λαμβάνει το δεξιό-πάνω γωνιακό  Point  της περιοχής  Quadrangle

Τιμή: Ένα δεξιό-πάνω γωνιακό  Point  της περιοχής Quadrangle

**Returns:**
java.awt.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

**Returns:**
int - Ένας 32-bit υπογεγραμμένος ακέραιος κώδικας κατακερματισμού.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Δοκιμάζει αν όλα τα  Point  του  Quadrangle  έχουν τιμές μηδέν.

Τιμή: Επιστρέφει  **true**  εάν όλα τα  Point  αυτού του  Quadrangle  έχουν τιμές μηδέν· διαφορετικά,  **false** .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLeftBottom(Point value) {#setLeftBottom-java.awt.Point-}
```
public void setLeftBottom(Point value)
```


Λαμβάνει το αριστερό-κάτω γωνιακό  Point  της περιοχής  Quadrangle

Τιμή: Ένα αριστερό-κάτω γωνιακό  Point  της περιοχής Quadrangle

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Point |  |

### setLeftTop(Point value) {#setLeftTop-java.awt.Point-}
```
public void setLeftTop(Point value)
```


Λαμβάνει το αριστερό-πάνω γωνιακό  Point  της περιοχής  Quadrangle

Τιμή: Ένα αριστερό-πάνω γωνιακό  Point  της περιοχής Quadrangle

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Point |  |

### setRightBottom(Point value) {#setRightBottom-java.awt.Point-}
```
public void setRightBottom(Point value)
```


Λαμβάνει το δεξιό-κάτω γωνιακό  Point  της περιοχής  Quadrangle

Τιμή: Ένα δεξιό-κάτω γωνιακό  Point  της περιοχής Quadrangle

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Point |  |

### setRightTop(Point value) {#setRightTop-java.awt.Point-}
```
public void setRightTop(Point value)
```


Λαμβάνει το δεξιό-πάνω γωνιακό  Point  της περιοχής  Quadrangle

Τιμή: Ένα δεξιό-πάνω γωνιακό  Point  της περιοχής Quadrangle

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Point |  |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του  Quadrangle .

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το  Quadrangle .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

