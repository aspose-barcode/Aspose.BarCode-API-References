---
title: "Quadrangle"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Αποθηκεύει ένα σύνολο τεσσάρων Points που αντιπροσωπεύουν μια περιοχή Quadrangle."
type: docs
weight: 41
url: /el/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Αποθηκεύει ένα σύνολο από τέσσερα Point που αντιπροσωπεύουν μια περιοχή Quadrangle.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | Αρχικοποιεί ένα νέο στιγμιότυπο της δομής  Quadrangle  με τα περιγραφικά σημεία. |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [EMPTY](#EMPTY) | Αντιπροσωπεύει μια κλάση  Quadrangle  με τις ιδιότητές της μη αρχικοποιημένες. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | Καθορίζει αν το καθορισμένο  Point  περιέχεται μέσα σε αυτήν την κλάση  Quadrangle . |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | Καθορίζει αν το καθορισμένο  Rectangle  περιέχεται ή τέμνει αυτήν την κλάση  Quadrangle . |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | Καθορίζει αν το καθορισμένο  Quadrangle  περιέχεται ή τέμνει αυτήν την κλάση  Quadrangle . |
| [contains(int x, int y)](#contains-int-int-) | Καθορίζει αν το καθορισμένο σημείο περιέχεται μέσα σε αυτήν την κλάση  Quadrangle . |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτό το στιγμιότυπο είναι ίσο με μια καθορισμένη τιμή  Quadrangle . |
| [getBoundingRectangle()](#getBoundingRectangle--) | Δημιουργεί  Rectangle  που περιβάλλει αυτό το  Quadrangle |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Λαμβάνει το αριστερό-κάτω γωνιακό  Point  της περιοχής  Quadrangle |
| [getLeftTop()](#getLeftTop--) | Λαμβάνει το αριστερό-πάνω γωνιακό  Point  της περιοχής  Quadrangle |
| [getRightBottom()](#getRightBottom--) | Λαμβάνει το δεξιό-κάτω γωνιακό  Point  της περιοχής  Quadrangle |
| [getRightTop()](#getRightTop--) | Λαμβάνει το δεξιό-πάνω γωνιακό  Point  της περιοχής  Quadrangle |
| [hashCode()](#hashCode--) | Επιστρέφει τον κώδικα κατακερματισμού για αυτό το αντικείμενο. |
| [isEmpty()](#isEmpty--) | Δοκιμάζει αν όλα τα  Point s αυτής της  Quadrangle  έχουν τιμές μηδέν. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Λαμβάνει το αριστερό-κάτω γωνιακό  Point  της περιοχής  Quadrangle |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Λαμβάνει το αριστερό-πάνω γωνιακό  Point  της περιοχής  Quadrangle |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Λαμβάνει το δεξιό-κάτω γωνιακό  Point  της περιοχής  Quadrangle |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Λαμβάνει το δεξιό-πάνω γωνιακό  Point  της περιοχής  Quadrangle |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτής της  Quadrangle . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της δομής  Quadrangle  με τα περιγραφικά σημεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| leftTop | android.graphics.Point | Ένα  Point  που αντιπροσωπεύει την αριστερή-πάνω γωνία του Quadrangle. |
| rightTop | android.graphics.Point | Ένα  Point  που αντιπροσωπεύει την δεξιά-πάνω γωνία του Quadrangle. |
| rightBottom | android.graphics.Point | Ένα  Point  που αντιπροσωπεύει την δεξιά-κάτω γωνία του Quadrangle. |
| leftBottom | android.graphics.Point | Ένα  Point  που αντιπροσωπεύει την αριστερή-κάτω γωνία του Quadrangle. |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Αντιπροσωπεύει μια κλάση  Quadrangle  με τις ιδιότητές της μη αρχικοποιημένες.

Τιμή:  Quadrangle

### clone() {#clone--}
```
public Quadrangle clone()
```




**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### contains(Point pt) {#contains-android.graphics.Point-}
```
public boolean contains(Point pt)
```


Καθορίζει αν το καθορισμένο  Point  περιέχεται μέσα σε αυτήν την κλάση  Quadrangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | android.graphics.Point | Το  Point  για δοκιμή. |

**Returns:**
boolean - Επιστρέφει  **true**  αν το  Point  περιέχεται μέσα σε αυτήν την κλάση  Quadrangle· διαφορετικά,  **false** .
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


Καθορίζει αν το καθορισμένο  Rectangle  περιέχεται ή τέμνει αυτήν την κλάση  Quadrangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | android.graphics.Rect | Το  Rectangle  για δοκιμή. |

**Returns:**
boolean - Επιστρέφει  **true**  αν το  Rectangle  περιέχεται ή τέμνει αυτήν την κλάση  Quadrangle· διαφορετικά,  **false** .
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
boolean - Επιστρέφει  **true**  αν το  Quadrangle  περιέχεται ή τέμνει αυτήν την κλάση  Quadrangle· διαφορετικά,  **false** .
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Καθορίζει αν το καθορισμένο σημείο περιέχεται μέσα σε αυτήν την κλάση  Quadrangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Η x συντεταγμένη του point. |
| y | int | Η y συντεταγμένη του point. |

**Returns:**
boolean - Επιστρέφει  **true**  αν το point περιέχεται μέσα σε αυτήν την κλάση  Quadrangle· διαφορετικά,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτό το στιγμιότυπο είναι ίσο με μια καθορισμένη τιμή  Quadrangle .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Μια  Quadrangle  τιμή για σύγκριση με αυτήν την περίπτωση. |

**Returns:**
boolean -  **true**  εάν το obj έχει την ίδια τιμή με αυτό το αντικείμενο· διαφορετικά,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


Δημιουργεί  Rectangle  που περιβάλλει αυτό το  Quadrangle

**Returns:**
android.graphics.Rect - επιστρέφει  Rectangle  που περιβάλλει αυτό το  Quadrangle
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

Τιμή: Ένα αριστερό-κάτω γωνιακό  Point  της περιοχής  Quadrangle

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Λαμβάνει το αριστερό-πάνω γωνιακό  Point  της περιοχής  Quadrangle

Τιμή: Ένα αριστερό-πάνω γωνιακό  Point  της περιοχής  Quadrangle

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Λαμβάνει το δεξιό-κάτω γωνιακό  Point  της περιοχής  Quadrangle

Τιμή: Ένα δεξιό-κάτω γωνιακό  Point  της περιοχής  Quadrangle

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Λαμβάνει το δεξιό-πάνω γωνιακό  Point  της περιοχής  Quadrangle

Τιμή: Ένα δεξιό-πάνω γωνιακό Point της περιοχής Quadrangle

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κώδικα κατακερματισμού για αυτό το αντικείμενο.

**Returns:**
int - Ένας 32-bit υπογεγραμμένος ακέραιος κώδικας κατακερματισμού.
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Δοκιμάζει αν όλα τα  Point s αυτής της  Quadrangle  έχουν τιμές μηδέν.

Τιμή: Επιστρέφει **true** εάν όλα τα Point αυτού του Quadrangle έχουν τιμές μηδέν· διαφορετικά, **false**.

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




### setLeftBottom(Point value) {#setLeftBottom-android.graphics.Point-}
```
public void setLeftBottom(Point value)
```


Λαμβάνει το αριστερό-κάτω γωνιακό  Point  της περιοχής  Quadrangle

Τιμή: Ένα αριστερό-κάτω γωνιακό  Point  της περιοχής  Quadrangle

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Λαμβάνει το αριστερό-πάνω γωνιακό  Point  της περιοχής  Quadrangle

Τιμή: Ένα αριστερό-πάνω γωνιακό  Point  της περιοχής  Quadrangle

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Λαμβάνει το δεξιό-κάτω γωνιακό  Point  της περιοχής  Quadrangle

Τιμή: Ένα δεξιό-κάτω γωνιακό  Point  της περιοχής  Quadrangle

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Λαμβάνει το δεξιό-πάνω γωνιακό  Point  της περιοχής  Quadrangle

Τιμή: Ένα δεξιό-πάνω γωνιακό Point της περιοχής Quadrangle

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτής της  Quadrangle .

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το Quadrangle.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
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

