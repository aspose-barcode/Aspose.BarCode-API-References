---
title: "CodetextParametersUI"
second_title: "Aspose.BarCode για Java Αναφορά API"
description: "Περιτύλιγμα UI για την κλάση com.aspose.barcode.generation.CodetextParameters."
type: docs
weight: 13
url: /el/java/com.aspose.barcode.barcodecontrol/codetextparametersui/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParametersUI
```

Περιτύλιγμα UI για την κλάση com.aspose.barcode.generation.CodetextParameters.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Αποκτά τη στοίχιση του κειμένου κώδικα. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Καθορίστε το χρώμα του εμφανιζόμενου CodeText. |
| [getFont()](#getFont--) | Καθορίστε τη γραμματοσειρά του εμφανιζόμενου CodeText. |
| [getFontMode()](#getFontMode--) | Καθορίστε το FontMode. |
| [getLocation()](#getLocation--) | Καθορίστε τη θέση του εμφανιζόμενου CodeText, ορίστε σε CodeLocation.None για απόκρυψη του CodeText. |
| [getSpace()](#getSpace--) | Διάστημα μεταξύ του CodeText και του BarCode σε τιμή. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Κείμενο που θα εμφανίζεται αντί για codetext σε 2D barcode. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Ορίζει τη στοίχιση του κειμένου κώδικα. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Καθορίστε το χρώμα του εμφανιζόμενου CodeText. |
| [setFont(Font value)](#setFont-java.awt.Font-) | Καθορίστε τη γραμματοσειρά του εμφανιζόμενου CodeText. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Καθορίστε το FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Καθορίστε τη θέση του εμφανιζόμενου CodeText, ορίστε σε CodeLocation.None για απόκρυψη του CodeText. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Κείμενο που θα εμφανίζεται αντί για codetext σε 2D barcode. |
| [toString()](#toString--) | Επιστρέφει μια αναγνώσιμη από άνθρωπο αναπαράσταση συμβολοσειράς αυτού του CodetextParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Αποκτά τη στοίχιση του κειμένου κώδικα. Προεπιλεγμένη τιμή: StringAlignment.Center.

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
public Color getColor()
```


Καθορίστε το χρώμα του εμφανιζόμενου CodeText. Προεπιλεγμένη τιμή: Color.BLACK.

**Returns:**
java.awt.Color
### getFont() {#getFont--}
```
public Font getFont()
```


Καθορίστε τη γραμματοσειρά του εμφανιζόμενου CodeText. Προεπιλεγμένη τιμή: Arial 5pt regular. Αγνοείται εάν το FontMode οριστεί σε FontMode.AUTO.

**Returns:**
java.awt.Font
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


Καθορίστε το FontMode. Εάν το FontMode οριστεί σε Auto, το μέγεθος γραμματοσειράς θα υπολογιστεί αυτόματα με βάση την τιμή xDimension. Συνιστάται η χρήση του FontMode.AUTO ειδικά σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION. Προεπιλεγμένη τιμή: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Καθορίστε τη θέση του εμφανιζόμενου CodeText, ορίστε σε CodeLocation.None για απόκρυψη του CodeText. Προεπιλεγμένη τιμή: CodeLocation.BELOW για 1D barcode και CodeLocation.None για 2D barcode.

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


Διάστημα μεταξύ του CodeText και του BarCode σε τιμή. Προεπιλεγμένη τιμή: 2pt. Αγνοείται για EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


Κείμενο που θα εμφανίζεται αντί για codetext σε 2D barcode. Χρησιμοποιείται για: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode.

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


Ορίζει τη στοίχιση του κειμένου κώδικα. Προεπιλεγμένη τιμή: StringAlignment.Center.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


Καθορίστε το χρώμα του εμφανιζόμενου CodeText. Προεπιλεγμένη τιμή: Color.BLACK.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Color |  |

### setFont(Font value) {#setFont-java.awt.Font-}
```
public void setFont(Font value)
```


Καθορίστε τη γραμματοσειρά του εμφανιζόμενου CodeText. Προεπιλεγμένη τιμή: Arial 5pt regular. Αγνοείται εάν το FontMode οριστεί σε FontMode.AUTO.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.awt.Font |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


Καθορίστε το FontMode. Εάν το FontMode οριστεί σε Auto, το μέγεθος γραμματοσειράς θα υπολογιστεί αυτόματα με βάση την τιμή xDimension. Συνιστάται η χρήση του FontMode.AUTO ειδικά σε AutoSizeMode.NEAREST ή AutoSizeMode.INTERPOLATION. Προεπιλεγμένη τιμή: FontMode.AUTO.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


Καθορίστε τη θέση του εμφανιζόμενου CodeText, ορίστε σε CodeLocation.None για απόκρυψη του CodeText. Προεπιλεγμένη τιμή: CodeLocation.BELOW για 1D barcode και CodeLocation.None για 2D barcode.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Κείμενο που θα εμφανίζεται αντί για codetext σε 2D barcode. Χρησιμοποιείται για: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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

