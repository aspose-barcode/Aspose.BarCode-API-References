---
title: "Unit"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Καθορίζει την τιμή μεγέθους σε διαφορετικές μονάδες Pixel, Inches κ.λπ.."
type: docs
weight: 67
url: /el/androidjava/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

Καθορίζει την τιμή μεγέθους σε διαφορετικές μονάδες (Pixel, ίντσες, κλπ.).

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν αυτή η παρουσία και ένα καθορισμένο αντικείμενο, το οποίο πρέπει επίσης να είναι ένα αντικείμενο Unit, έχουν την ίδια τιμή. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Λαμβάνει την τιμή του μεγέθους σε μονάδες εγγράφου. |
| [getInches()](#getInches--) | Λαμβάνει την τιμή του μεγέθους σε ίντσες. |
| [getMillimeters()](#getMillimeters--) | Λαμβάνει την τιμή του μεγέθους σε χιλιοστά. |
| [getPixels()](#getPixels--) | Λαμβάνει την τιμή του μεγέθους σε εικονοστοιχεία. |
| [getPoint()](#getPoint--) | Λαμβάνει την τιμή του μεγέθους σε σημεία. |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτό το αντικείμενο. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | Ορίζει την τιμή του μεγέθους σε μονάδες εγγράφου. |
| [setInches(float value)](#setInches-float-) | Ορίζει την τιμή του μεγέθους σε ίντσες. |
| [setMillimeters(float value)](#setMillimeters-float-) | Ορίζει την τιμή του μεγέθους σε χιλιοστά. |
| [setPixels(float value)](#setPixels-float-) | Ορίζει την τιμή του μεγέθους σε εικονοστοιχεία. |
| [setPoint(float value)](#setPoint-float-) | Ορίζει την τιμή του μεγέθους σε σημεία. |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του  Unit . |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει εάν αυτή η παρουσία και ένα καθορισμένο αντικείμενο, το οποίο πρέπει επίσης να είναι ένα αντικείμενο Unit, έχουν την ίδια τιμή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Το  Unit  για σύγκριση με αυτήν την περίπτωση. |

**Returns:**
boolean - true εάν το obj είναι ένα  Unit  και η τιμή του είναι η ίδια με αυτήν την περίπτωση· διαφορετικά, false. Εάν το obj είναι null, η μέθοδος επιστρέφει false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public float getDocument()
```


Λαμβάνει την τιμή του μεγέθους σε μονάδες εγγράφου.

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


Λαμβάνει την τιμή του μεγέθους σε ίντσες.

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


Λαμβάνει την τιμή του μεγέθους σε χιλιοστά.

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


Λαμβάνει την τιμή του μεγέθους σε εικονοστοιχεία.

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


Λαμβάνει την τιμή του μεγέθους σε σημεία.

**Returns:**
float
### getResolution() {#getResolution--}
```
public float getResolution()
```




**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για αυτό το αντικείμενο.

**Returns:**
int - Ένας 32-bit υπογεγραμμένος ακέραιος κώδικας κατακερματισμού.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDocument(float value) {#setDocument-float-}
```
public void setDocument(float value)
```


Ορίζει την τιμή του μεγέθους σε μονάδες εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


Ορίζει την τιμή του μεγέθους σε ίντσες.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


Ορίζει την τιμή του μεγέθους σε χιλιοστά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


Ορίζει την τιμή του μεγέθους σε εικονοστοιχεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


Ορίζει την τιμή του μεγέθους σε σημεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του  Unit .

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το  Unit .
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| dpi | float |  |

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

