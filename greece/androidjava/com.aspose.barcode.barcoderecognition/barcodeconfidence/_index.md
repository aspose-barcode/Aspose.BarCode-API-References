---
title: BarCodeConfidence
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Περιέχει το επίπεδο εμπιστοσύνης της αναγνώρισης
type: docs
weight: 13
url: /el/androidjava/com.aspose.barcode.barcoderecognition/barcodeconfidence/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeConfidence
```

Περιέχει το επίπεδο εμπιστοσύνης της αναγνώρισης

--------------------

> ```
> This sample shows how BarCodeConfidence changed, depending on barcode type
>  
>  //Moderate confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.CODE_128);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
>  //Strong confidence
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.QR, "12345");
>  generator.save("test.png");
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_STANDARD, DecodeType.QR);
>      for(BarCodeResult result : reader.readBarCodes())
>      {
>          System.out.println("BarCode Type: " + result.getCodeTypeName());
>          System.out.println("BarCode CodeText: " + result.getCodeText());
>          System.out.println("BarCode Confidence: " + result.getConfidence());
>          System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      }
> ```
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [MODERATE](#MODERATE) | Βεβαιότητα αναγνώρισης του barcode (κυρίως 1D barcodes) με αδύναμο checksumm ή ακόμη και χωρίς αυτό. |
| [NONE](#NONE) | Βεβαιότητα αναγνώρισης του barcode όπου το κείμενο κώδικα δεν αναγνωρίστηκε σωστά ή το barcode εντοπίστηκε ως πιθανό fakeBarCodeExtendedParameters |
| [STRONG](#STRONG) | Βεβαιότητα αναγνώρισης που επιβεβαιώθηκε με κώδικες BCH όπως Reed\\u2013Solomon. |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MODERATE {#MODERATE}
```
public static final int MODERATE
```


Βεβαιότητα αναγνώρισης του barcode (κυρίως 1D barcodes) με αδύναμο checksumm ή ακόμη και χωρίς αυτό. Μπορεί να περιέχει κάποιες λανθασμένες αναγνώσεις στο κείμενο κώδικα ή ακόμη και ψεύτικες αναγνώσεις εάν είναι χαμηλή.

### NONE {#NONE}
```
public static final int NONE
```


Βεβαιότητα αναγνώρισης του barcode όπου το κείμενο κώδικα δεν αναγνωρίστηκε σωστά ή το barcode εντοπίστηκε ως πιθανό fakeBarCodeExtendedParameters

### STRONG {#STRONG}
```
public static final int STRONG
```


Βεβαιότητα αναγνώρισης που επιβεβαιώθηκε με κώδικες BCH όπως Reed\\u2013Solomon. Δεν πρέπει να υπάρχουν σφάλματα στο αναγνωσμένο κείμενο κώδικα ή ψεύτικες αναγνώσεις.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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




**Returns:**
java.lang.String
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

