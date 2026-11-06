---
title: "BarCodeRegionParameters"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Αναπαριστά την περιοχή των αναγνωρισμένων barcode και τη γωνία του barcode"
type: docs
weight: 16
url: /el/androidjava/com.aspose.barcode.barcoderecognition/barcoderegionparameters/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeRegionParameters
```

Αντιπροσωπεύει την περιοχή του αναγνωρισμένου barcode και τη γωνία του barcode

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
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή του  BarCodeRegionParameters . |
| [getAngle()](#getAngle--) | Λαμβάνει τη γωνία του barcode (0-360). |
| [getClass()](#getClass--) |  |
| [getPoints()](#getPoints--) | Λαμβάνει τον πίνακα Point που περιβάλλει την περιοχή του barcode |
| [getQuadrangle()](#getQuadrangle--) | Λαμβάνει το Aspose.BarCode.BarCodeRecognition.Quadrangle που περιβάλλει την περιοχή του barcode |
| [getRectangle()](#getRectangle--) | Λαμβάνει το System.Drawing.Rectangle που περιβάλλει την περιοχή του barcode |
| [hashCode()](#hashCode--) | Επιστρέφει τον κώδικα κατακερματισμού για αυτό το αντικείμενο. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του  BarCodeRegionParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή του  BarCodeRegionParameters .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Μια τιμή System.Object για σύγκριση με αυτό το αντικείμενο. |

**Returns:**
boolean -  **true**  εάν το obj έχει την ίδια τιμή με αυτό το αντικείμενο· διαφορετικά,  **false** .
### getAngle() {#getAngle--}
```
public double getAngle()
```


Λαμβάνει τη γωνία του barcode (0-360).

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


Λαμβάνει τον πίνακα Point που περιβάλλει την περιοχή του barcode

Τιμή: Επιστρέφει τον πίνακα Point που περιβάλλει την περιοχή του barcode

**Returns:**
android.graphics.Point[]
### getQuadrangle() {#getQuadrangle--}
```
public Quadrangle getQuadrangle()
```


Λαμβάνει το Aspose.BarCode.BarCodeRecognition.Quadrangle που περιβάλλει την περιοχή του barcode

Τιμή: Επιστρέφει το Aspose.BarCode.BarCodeRecognition.Quadrangle που περιβάλλει την περιοχή του barcode

**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### getRectangle() {#getRectangle--}
```
public Rect getRectangle()
```


Λαμβάνει το System.Drawing.Rectangle που περιβάλλει την περιοχή του barcode

Τιμή: Επιστρέφει το System.Drawing.Rectangle που περιβάλλει την περιοχή του barcode

**Returns:**
android.graphics.Rect
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κώδικα κατακερματισμού για αυτό το αντικείμενο.

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




### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του  BarCodeRegionParameters .

**Returns:**
java.lang.String - Μια συμβολοσειρά που αναπαριστά αυτό το  BarCodeRegionParameters .
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

