---
title: Unit
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Καθορίζει την τιμή μεγέθους σε διαφορετικές μονάδες Pixel Inches κλ..
type: docs
weight: 69
url: /el/androidjava/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

Καθορίζει την τιμή μεγέθους σε διαφορετικές μονάδες (Pixel, Inches κ.λπ.).

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει αν αυτή η παρουσία και ένα καθορισμένο αντικείμενο, το οποίο πρέπει επίσης να είναι ένα  Unit  αντικείμενο, έχουν την ίδια τιμή. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Λαμβάνει την τιμή μεγέθους σε μονάδες εγγράφου. |
| [getInches()](#getInches--) | Λαμβάνει την τιμή μεγέθους σε ίντσες. |
| [getMillimeters()](#getMillimeters--) | Λαμβάνει την τιμή μεγέθους σε χιλιοστά. |
| [getPixels()](#getPixels--) | Λαμβάνει την τιμή μεγέθους σε εικονοστοιχεία. |
| [getPoint()](#getPoint--) | Λαμβάνει την τιμή μεγέθους σε σημείο. |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτό το αντικείμενο. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | Ορίζει την τιμή μεγέθους σε μονάδες εγγράφου. |
| [setInches(float value)](#setInches-float-) | Ορίζει την τιμή μεγέθους σε ίντσες. |
| [setMillimeters(float value)](#setMillimeters-float-) | Ορίζει την τιμή μεγέθους σε χιλιοστά. |
| [setPixels(float value)](#setPixels-float-) | Ορίζει την τιμή μεγέθους σε εικονοστοιχεία. |
| [setPoint(float value)](#setPoint-float-) | Sets size value in point. |
| [toString()](#toString--) | Returns a human-readable string representation of this  Unit . |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Καθορίζει αν αυτή η παρουσία και ένα καθορισμένο αντικείμενο, το οποίο πρέπει επίσης να είναι ένα  Unit  αντικείμενο, έχουν την ίδια τιμή.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | The  Unit  to compare to this instance. |

**Returns:**
boolean - true if obj is a  Unit  and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.
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


Λαμβάνει την τιμή μεγέθους σε μονάδες εγγράφου.

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


Λαμβάνει την τιμή μεγέθους σε ίντσες.

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


Λαμβάνει την τιμή μεγέθους σε χιλιοστά.

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


Λαμβάνει την τιμή μεγέθους σε εικονοστοιχεία.

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


Λαμβάνει την τιμή μεγέθους σε σημείο.

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
int - Ένας 32-bit υπογεγραμμένος ακέραιος κωδικός κατακερματισμού.
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


Ορίζει την τιμή μεγέθους σε μονάδες εγγράφου.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


Ορίζει την τιμή μεγέθους σε ίντσες.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


Ορίζει την τιμή μεγέθους σε χιλιοστά.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


Ορίζει την τιμή μεγέθους σε εικονοστοιχεία.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


Sets size value in point.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this  Unit .

**Returns:**
java.lang.String - A string that represents this  Unit .
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

