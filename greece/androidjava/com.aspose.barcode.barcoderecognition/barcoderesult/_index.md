---
title: "BarCodeResult"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Αποθηκεύει τα αναγνωρισμένα δεδομένα γραμμωτού κώδικα όπως τύπο SingleDecodeType, συμβολοσειρά codetext, παραμέτρους BarCodeRegionParameters region και άλλες παραμέτρους."
type: docs
weight: 17
url: /el/androidjava/com.aspose.barcode.barcoderecognition/barcoderesult/
---
**Inheritance:**
java.lang.Object
```
public final class BarCodeResult
```

Αποθηκεύει δεδομένα του αναγνωρισμένου barcode όπως ο τύπος SingleDecodeType, η συμβολοσειρά codetext, η BarCodeRegionParameters περιοχή και άλλες παραμέτρους

--------------------

> ```
> This sample shows how to obtain BarCodeResult.
>  
>  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128, "12345");
>  generator.save("c:\\test.png");
>  BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39, DecodeType.CODE_128);
>  for(BarCodeResult result : reader.readBarCodes())
>  {
>      System.out.println("BarCode Type: " + result.getCodeTypeName());
>      System.out.println("BarCode CodeText: " + result.getCodeText());
>      System.out.println("BarCode Confidence: " + result.getConfidence());
>      System.out.println("BarCode ReadingQuality: " + result.getReadingQuality());
>      System.out.println("BarCode Angle: " + result.getRegion().getAngle());
>  }
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [BarCodeResult(BarCodeResult result)](#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-) | Δημιουργεί ένα αντίγραφο της  BarCodeResult  κλάσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [deepClone()](#deepClone--) | Δημιουργεί ένα αντίγραφο της  BarCodeResult  κλάσης. |
| [equals(Object obj)](#equals-java.lang.Object-) | Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή  BarCodeResult . |
| [getClass()](#getClass--) |  |
| [getCodeBytes()](#getCodeBytes--) | Αποκτά τα κωδικοποιημένα bytes του κώδικα. |
| [getCodeText()](#getCodeText--) | Αποκτά το κείμενο του κώδικα. |
| [getCodeText(Charset charset)](#getCodeText-java.nio.charset.Charset-) | Αποκτά το κείμενο του κώδικα με κωδικοποίηση. |
| [getCodeType()](#getCodeType--) | Αποκτά τον τύπο του barcode. |
| [getCodeTypeName()](#getCodeTypeName--) | Αποκτά το όνομα του τύπου του barcode. |
| [getConfidence()](#getConfidence--) | Αποκτά το επίπεδο εμπιστοσύνης αναγνώρισης του αναγνωρισμένου barcode. |
| [getExtended()](#getExtended--) | Αποκτά τις επεκταμένες παραμέτρους του αναγνωρισμένου barcode. |
| [getReadingQuality()](#getReadingQuality--) | Αποκτά την ποιότητα ανάγνωσης. |
| [getRegion()](#getRegion--) | Αποκτά την περιοχή του barcode. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κώδικα κατακερματισμού για αυτό το αντικείμενο. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του  BarCodeResult . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BarCodeResult(BarCodeResult result) {#BarCodeResult-com.aspose.barcode.barcoderecognition.BarCodeResult-}
```
public BarCodeResult(BarCodeResult result)
```


Δημιουργεί ένα αντίγραφο της  BarCodeResult  κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| result | [BarCodeResult](../../com.aspose.barcode.barcoderecognition/barcoderesult) | Ένα αντίγραφο της παρουσίας  BarCodeResult . |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Δημιουργεί ένα αντίγραφο της  BarCodeResult  κλάσης.

**Returns:**
java.lang.Object - Επιστρέφει αντίγραφο της  BarCodeResult  κλάσης.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Επιστρέφει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι ίση με μια καθορισμένη τιμή  BarCodeResult .

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| obj | java.lang.Object | Μια τιμή  BarCodeResult  για σύγκριση με αυτή την παρουσία. |

**Returns:**
boolean -  **true**  εάν το obj έχει την ίδια τιμή με αυτό το αντικείμενο· διαφορετικά,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodeBytes() {#getCodeBytes--}
```
public byte[] getCodeBytes()
```


Αποκτά τα κωδικοποιημένα bytes του κώδικα.

Τιμή: Τα bytes του κώδικα του barcode

**Returns:**
byte[]
### getCodeText() {#getCodeText--}
```
public String getCodeText()
```


Αποκτά το κείμενο του κώδικα.

Τιμή: Το κείμενο του κώδικα του barcode

**Returns:**
java.lang.String
### getCodeText(Charset charset) {#getCodeText-java.nio.charset.Charset-}
```
public String getCodeText(Charset charset)
```


Αποκτά το κείμενο του κώδικα με κωδικοποίηση.

--------------------

> ```
> This example shows how to use ```
> GetCodeText
> ```:
>   
>   BarcodeGenerator gen = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	gen.setCodeText("\u8eca\u7a2e\u540d", Charset.forName("932"));
>  	gen.save("barcode.png", BarCodeImageFormat.PNG);
> 
>  	BarCodeReader reader = new BarCodeReader("barcode.png", DecodeType.DATA_MATRIX);
>   for(BarCodeResult result : reader.readBarCodes())
>      System.out.println("BarCode CodeText: " + result.getCodeText(Charset.forName("932")));
> ```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| charset | java.nio.charset.Charset | Η κωδικοποίηση για το κείμενο κώδικα. |

**Returns:**
java.lang.String - Μια συμβολοσειρά που περιέχει το αναγνωρισμένο κείμενο κώδικα.
### getCodeType() {#getCodeType--}
```
public SingleDecodeType getCodeType()
```


Αποκτά τον τύπο του barcode.

Τιμή: Οι πληροφορίες τύπου του αναγνωρισμένου barcode

**Returns:**
[SingleDecodeType](../../com.aspose.barcode.barcoderecognition/singledecodetype)
### getCodeTypeName() {#getCodeTypeName--}
```
public String getCodeTypeName()
```


Αποκτά το όνομα του τύπου του barcode.

Τιμή: Το όνομα τύπου του αναγνωρισμένου barcode

**Returns:**
java.lang.String
### getConfidence() {#getConfidence--}
```
public BarCodeConfidence getConfidence()
```


Αποκτά το επίπεδο εμπιστοσύνης αναγνώρισης του αναγνωρισμένου barcode.

Τιμή:  BarCodeConfidence.Strong  δεν έχει ψεύτικα ή λανθασμένες αναγνώσεις,  BarCodeConfidence.Moderate  μπορεί μερικές φορές να έχει ψεύτικα ή λανθασμένο κείμενο κώδικα επειδή αυτό το επίπεδο εμπιστοσύνης για barcodews με αδύναμο έλεγχο αθροίσματος ή ακόμη και χωρίς αυτό,  BarCodeConfidence.None  πάντα έχει λανθασμένο κείμενο κώδικα και μπορεί να είναι ψεύτικες αναγνώσεις

**Returns:**
[BarCodeConfidence](../../com.aspose.barcode.barcoderecognition/barcodeconfidence)
### getExtended() {#getExtended--}
```
public BarCodeExtendedParameters getExtended()
```


Αποκτά τις επεκταμένες παραμέτρους του αναγνωρισμένου barcode.

Τιμή: Οι εκτεταμένες παράμετροι του αναγνωρισμένου barcode

**Returns:**
[BarCodeExtendedParameters](../../com.aspose.barcode.barcoderecognition/barcodeextendedparameters)
### getReadingQuality() {#getReadingQuality--}
```
public double getReadingQuality()
```


Λαμβάνει την ποιότητα ανάγνωσης. Λειτουργεί για 1D και ταχυδρομικούς barcode.

Τιμή: Το ποσοστό ποιότητας ανάγνωσης

**Returns:**
double
### getRegion() {#getRegion--}
```
public BarCodeRegionParameters getRegion()
```


Αποκτά την περιοχή του barcode.

Τιμή: Η περιοχή του αναγνωρισμένου barcode

**Returns:**
[BarCodeRegionParameters](../../com.aspose.barcode.barcoderecognition/barcoderegionparameters)
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


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του  BarCodeResult .

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το  BarCodeResult .
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

