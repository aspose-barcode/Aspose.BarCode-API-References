---
title: "ComplexBarcodeGenerator"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "ComplexBarcodeGenerator για backend σύνθετο barcode π.χ."
type: docs
weight: 12
url: /el/androidjava/com.aspose.barcode.complexbarcode/complexbarcodegenerator/
---
**Inheritance:**
java.lang.Object
```
public final class ComplexBarcodeGenerator
```

ComplexBarcodeGenerator για δημιουργία εικόνων backend σύνθετου barcode (π.χ. SwissQR).

--------------------

> ```
> This sample shows how to create and save a SwissQR image.
>   
>     SwissQRCodetext swissQRCodetext = new SwissQRCodetext();
>     swissQRCodetext.getBill().setAccount("Account");
>     swissQRCodetext.getBill().setBillInformation("BillInformation");
>     // init rest of the fields
>     ComplexBarcodeGenerator cg = new ComplexBarcodeGenerator(swissQRCodetext);
>     BufferedImage res = cg.generateBarCodeImage();
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ComplexBarcodeGenerator(IComplexCodetext complexCodetext)](#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-) | Δημιουργεί μια παρουσία του ComplexBarcodeGenerator. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [dispose()](#dispose--) | Καθαρίζει τυχόν πόρους που χρησιμοποιούνται. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateBarCodeImage()](#generateBarCodeImage--) | Δημιουργεί εικόνα σύνθετου barcode με τις τρέχουσες ρυθμίσεις. |
| [getClass()](#getClass--) |  |
| [getParameters()](#getParameters--) | Παράμετροι δημιουργίας. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, BarCodeImageFormat format)](#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-) | Δημιουργεί και αποθηκεύει εικόνα σύνθετου barcode με τις τρέχουσες ρυθμίσεις. |
| [save(String filename)](#save-java.lang.String-) | Δημιουργεί και αποθηκεύει εικόνα σύνθετου barcode με τις τρέχουσες ρυθμίσεις. |
| [save(String filename, BarCodeImageFormat format)](#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-) | Δημιουργεί και αποθηκεύει εικόνα σύνθετου barcode με τις τρέχουσες ρυθμίσεις. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ComplexBarcodeGenerator(IComplexCodetext complexCodetext) {#ComplexBarcodeGenerator-com.aspose.barcode.complexbarcode.IComplexCodetext-}
```
public ComplexBarcodeGenerator(IComplexCodetext complexCodetext)
```


Δημιουργεί μια παρουσία του ComplexBarcodeGenerator.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| complexCodetext | [IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext) | Σύνθετο κείμενο κώδικα |

### dispose() {#dispose--}
```
public void dispose()
```


Καθαρίζει τυχόν πόρους που χρησιμοποιούνται.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateBarCodeImage() {#generateBarCodeImage--}
```
public Bitmap generateBarCodeImage()
```


Δημιουργεί εικόνα σύνθετου barcode με τις τρέχουσες ρυθμίσεις.

**Returns:**
android.graphics.Bitmap - Εικόνα barcode. Δείτε το Bitmap.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getParameters() {#getParameters--}
```
public BaseGenerationParameters getParameters()
```


Παράμετροι δημιουργίας.

**Returns:**
[BaseGenerationParameters](../../com.aspose.barcode.generation/basegenerationparameters)
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




### save(OutputStream stream, BarCodeImageFormat format) {#save-java.io.OutputStream-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(OutputStream stream, BarCodeImageFormat format)
```


Δημιουργεί και αποθηκεύει εικόνα σύνθετου barcode με τις τρέχουσες ρυθμίσεις.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | java.io.OutputStream | Έξοδος System.IO.Stream. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Καθορίζει τη μορφή αρχείου της εξόδου εικόνας. |

### save(String filename) {#save-java.lang.String-}
```
public void save(String filename)
```


Δημιουργεί και αποθηκεύει εικόνα σύνθετου barcode με τις τρέχουσες ρυθμίσεις.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | java.lang.String | Διαδρομή αποθήκευσης. |

### save(String filename, BarCodeImageFormat format) {#save-java.lang.String-com.aspose.barcode.generation.BarCodeImageFormat-}
```
public void save(String filename, BarCodeImageFormat format)
```


Δημιουργεί και αποθηκεύει εικόνα σύνθετου barcode με τις τρέχουσες ρυθμίσεις.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | java.lang.String | Διαδρομή αποθήκευσης. |
| format | [BarCodeImageFormat](../../com.aspose.barcode.generation/barcodeimageformat) | Καθορίζει τη μορφή αρχείου της εξόδου εικόνας. |

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

