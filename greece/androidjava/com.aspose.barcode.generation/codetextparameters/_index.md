---
title: CodetextParameters
second_title: Aspose.BarCode για Android μέσω Java API Reference
description: Codetext parameters.
type: docs
weight: 27
url: /el/androidjava/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

Codetext parameters.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [CodetextParameters()](#CodetextParameters--) |  |
## Methods

| Method | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Λαμβάνει την ευθυγράμμιση του κειμένου κώδικα. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Καθορίστε το χρώμα εμφάνισης του CodeText. |
| [getFont()](#getFont--) | Καθορίστε τη γραμματοσειρά εμφάνισης του CodeText. |
| [getFontMode()](#getFontMode--) | Καθορίστε το FontMode. |
| [getLocation()](#getLocation--) | Καθορίστε τη θέση εμφάνισης του CodeText, ορίστε σε CodeLocation.None για απόκρυψη του CodeText. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Καθορίστε τις αναδιπλώσεις λέξεων (αλλαγές γραμμής) μέσα στο κείμενο.
``` |
| [getSpace()](#getSpace--) | Space between the CodeText and the BarCode in  Unit  value. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Text that will be displayed instead of codetext in 2D barcodes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Sets the alignment of the code text. |
| [setColor(int value)](#setColor-int-) | Specify the displaying CodeText's Color. |
| [setFont(FontUnit value)](#setFont-com.aspose.barcode.generation.FontUnit-) | Specify the displaying CodeText's font. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Specify FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Specify the displaying CodeText Location, set to CodeLocation.None to hide CodeText. |
| [setNoWrap(boolean value)](#setNoWrap-boolean-) | ```
Specify word wraps (line breaks) within text
``` |
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | Διάστημα μεταξύ του CodeText και του BarCode σε τιμή μονάδας. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Κείμενο που θα εμφανίζεται αντί για codetext σε 2D barcode. |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του CodetextParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CodetextParameters() {#CodetextParameters--}
```
public CodetextParameters()
```


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
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Λαμβάνει την ευθυγράμιση του κειμένου κώδικα. Προεπιλεγμένη τιμή: TextAlignment.CENTER.

**Returns:**
[TextAlignment](../../com.aspose.barcode.generation/textalignment)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public int getColor()
```


Καθορίστε το χρώμα του εμφανιζόμενου CodeText. Προεπιλεγμένη τιμή: Color.BLACK.

**Returns:**
int
### getFont() {#getFont--}
```
public FontUnit getFont()
```


Καθορίστε τη γραμματοσειρά του εμφανιζόμενου CodeText. Προεπιλεγμένη τιμή: Arial 5pt regular. Αγνοείται εάν το FontMode έχει οριστεί σε FontMode.AUTO.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


Καθορίστε το FontMode. Εάν το FontMode οριστεί σε Auto, το μέγεθος γραμματοσειράς θα υπολογιστεί αυτόματα βάσει της τιμής xDimension. Συνιστάται η χρήση του FontMode.AUTO ειδικά σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION. Προεπιλεγμένη τιμή: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Καθορίστε τη θέση του εμφανιζόμενου CodeText, ορίστε σε CodeLocation.None για απόκρυψη του CodeText. Προεπιλεγμένη τιμή: CodeLocation.BELOW για 1D barcode και CodeLocation.None για 2D barcode.

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getNoWrap() {#getNoWrap--}
```
public boolean getNoWrap()
```


```
Specify word wraps (line breaks) within text.
 Default value: false.
```

**Returns:**
boolean
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


Διάστημα μεταξύ του CodeText και του BarCode σε μονάδες τιμής. Προεπιλεγμένη τιμή: 2pt. Αγνοείται για EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


Κείμενο που θα εμφανίζεται αντί του codetext σε 2D barcode. Χρησιμοποιείται για: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Returns:**
java.lang.String
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




### setAlignment(TextAlignment value) {#setAlignment-com.aspose.barcode.generation.TextAlignment-}
```
public void setAlignment(TextAlignment value)
```


Ορίζει την ευθυγράμμιση του κειμένου κώδικα. Προεπιλεγμένη τιμή: TextAlignment.CENTER.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(int value) {#setColor-int-}
```
public void setColor(int value)
```


Καθορίστε το χρώμα του εμφανιζόμενου CodeText. Προεπιλεγμένη τιμή: Color.BLACK.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


Καθορίστε τη γραμματοσειρά του εμφανιζόμενου CodeText. Προεπιλεγμένη τιμή: Arial 5pt regular. Αγνοείται εάν το FontMode έχει οριστεί σε FontMode.AUTO.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


Καθορίστε το FontMode. Εάν το FontMode οριστεί σε Auto, το μέγεθος γραμματοσειράς θα υπολογιστεί αυτόματα βάσει της τιμής xDimension. Συνιστάται η χρήση του FontMode.AUTO ειδικά σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION. Προεπιλεγμένη τιμή: FontMode.AUTO.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


Καθορίστε τη θέση του εμφανιζόμενου CodeText, ορίστε σε CodeLocation.None για απόκρυψη του CodeText. Προεπιλεγμένη τιμή: CodeLocation.BELOW για 1D barcode και CodeLocation.None για 2D barcode.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setNoWrap(boolean value) {#setNoWrap-boolean-}
```
public void setNoWrap(boolean value)
```


```
Specify word wraps (line breaks) within text
```

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


Διάστημα μεταξύ του CodeText και του BarCode σε μονάδες τιμής. Προεπιλεγμένη τιμή: 2pt. Αγνοείται για EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Κείμενο που θα εμφανίζεται αντί του codetext σε 2D barcode. Χρησιμοποιείται για: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του CodetextParameters.

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει αυτό το CodetextParameters.
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

