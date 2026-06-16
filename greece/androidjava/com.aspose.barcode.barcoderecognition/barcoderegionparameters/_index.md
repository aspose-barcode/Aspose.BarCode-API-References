---
title: BarCodeRegionParameters
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Αντιπροσωπεύει την περιοχή των αναγνωρισμένων barcodes και τη γωνία του barcode
type: docs
weight: 17
url: /el/androidjava/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

Αναπαριστά την περιοχή του αναγνωρισμένου barcode και τη γωνία του barcode

--------------------

> ```
> This sample shows how to get barcode Angle and bounding quadrangle values
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.Code128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>     System.out.println("BarCode CodeText: " + result.getCodeText());
>     System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>     System.out.println("BarCode Quadrangle: " + result.getRegion().getQuadrangle());
>  }
> ```
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή  BarCodeRegionParameters . |
| [getAngle()](#getAngle--) | Αποκτά τη γωνία του barcode (0-360). |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | Λαμβάνει  Point s πίνακα που οριοθετεί την περιοχή του barcode |
| [getQuadrangle()](#getQuadrangle--) | Λαμβάνει  Aspose.BarCode.BarCodeRecognition.Quadrangle που οριοθετεί την περιοχή του barcode |
| [getRectangle()](#getRectangle--) | Λαμβάνει  System.Drawing.Rectangle που οριοθετεί την περιοχή του barcode |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά που αντιπροσωπεύει αυτό το  BarCodeRegionParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή  BarCodeRegionParameters .

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Μια τιμή System.Object για σύγκριση με αυτήν την παρουσία. |

**Returns:**
boolean -  **true**  εάν το obj έχει την ίδια τιμή με αυτήν την παρουσία· διαφορετικά,  **false** .
### getAngle() {#getAngle--}
```
public double getAngle()
```


Αποκτά τη γωνία του barcode (0-360).

Τιμή: Η γωνία για το barcode (0-360).

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getPoints() {#getPoints--}
```
public Point[] getPoints()
```


Λαμβάνει  Point s πίνακα που οριοθετεί την περιοχή του barcode

Τιμή: Επιστρέφει  Point s πίνακα που οριοθετεί την περιοχή του barcode

**Returns:**
android.graphics.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


Λαμβάνει  Aspose.BarCode.BarCodeRecognition.Quadrangle που οριοθετεί την περιοχή του barcode

Τιμή: Επιστρέφει  Aspose.BarCode.BarCodeRecognition.Quadrangle που οριοθετεί την περιοχή του barcode

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rect getRectangle()
```


Λαμβάνει  System.Drawing.Rectangle που οριοθετεί την περιοχή του barcode

Τιμή: Επιστρέφει  System.Drawing.Rectangle που οριοθετεί την περιοχή του barcode

**Returns:**
android.graphics.Rect
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία.

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




### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο συμβολοσειρά που αντιπροσωπεύει αυτό το  BarCodeRegionParameters .

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το  BarCodeRegionParameters .
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

