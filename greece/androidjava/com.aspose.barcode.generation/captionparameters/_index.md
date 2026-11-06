---
title: "CaptionParameters"
second_title: "Αναφορά API του Aspose.BarCode για Android μέσω Java"
description: "Παράμετροι λεζάντας."
type: docs
weight: 20
url: /el/androidjava/com.aspose.barcode.generation/captionparameters/
---
**Inheritance:**
java.lang.Object
```
public class CaptionParameters
```

Παράμετροι λεζάντας.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CaptionParameters()](#CaptionParameters--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Οριζόντια στοίχιση του Caption test. |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | Γραμματοσειρά Caption. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Καθορίστε τις αναδιπλώσεις λέξεων (διακοπές γραμμής) μέσα στο κείμενο.
``` |
| [getPadding()](#getPadding--) | Captions paddings. |
| [getText()](#getText--) | Caption text. |
| [getTextColor()](#getTextColor--) | Caption text color. |
| [getVisible()](#getVisible--) | Caption text visibility. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Caption test horizontal alignment. |
| [setNoWrap(boolean value)](#setNoWrap-boolean-) | ```
Specify word wraps (line breaks) within text
``` |
| [setPadding(Padding value)](#setPadding-com.aspose.barcode.generation.Padding-) | Περιθώρια Captions. |
| [setText(String value)](#setText-java.lang.String-) | Κείμενο Caption. |
| [setTextColor(int value)](#setTextColor-int-) | Χρώμα κειμένου Caption. |
| [setVisible(boolean value)](#setVisible-boolean-) | Ορατότητα κειμένου Caption. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CaptionParameters() {#CaptionParameters--}
```
public CaptionParameters()
```


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


Οριζόντια στοίχιση του Caption test. Προεπιλεγμένη τιμή: StringAlignment.Center.

**Returns:**
[TextAlignment](../../com.aspose.barcode.generation/textalignment)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFont() {#getFont--}
```
public FontUnit getFont()
```


Γραμματοσειρά Caption. Προεπιλεγμένη τιμή: Arial 8pt regular.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
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
### getPadding() {#getPadding--}
```
public Padding getPadding()
```


Αποστάσεις τίτλων. Προεπιλεγμένη τιμή για CaptionAbove: 5pt 5pt 0 5pt. Προεπιλεγμένη τιμή για CaptionBelow: 0 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getText() {#getText--}
```
public String getText()
```


Κείμενο τίτλου. Προεπιλεγμένη τιμή: κενή συμβολοσειρά.

**Returns:**
java.lang.String
### getTextColor() {#getTextColor--}
```
public int getTextColor()
```


Χρώμα κειμένου τίτλου. Προεπιλεγμένη τιμή: Color.BLACK.

**Returns:**
int
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Ορατότητα κειμένου τίτλου. Προεπιλεγμένη τιμή: false.

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
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


Οριζόντια στοίχιση του Caption test. Προεπιλεγμένη τιμή: StringAlignment.Center.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setNoWrap(boolean value) {#setNoWrap-boolean-}
```
public void setNoWrap(boolean value)
```


```
Specify word wraps (line breaks) within text
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### setPadding(Padding value) {#setPadding-com.aspose.barcode.generation.Padding-}
```
public void setPadding(Padding value)
```


Αποστάσεις τίτλων. Προεπιλεγμένη τιμή για CaptionAbove: 5pt 5pt 0 5pt. Προεπιλεγμένη τιμή για CaptionBelow: 0 5pt 5pt 5pt.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Padding](../../com.aspose.barcode.generation/padding) |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Κείμενο τίτλου. Προεπιλεγμένη τιμή: κενή συμβολοσειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String |  |

### setTextColor(int value) {#setTextColor-int-}
```
public void setTextColor(int value)
```


Χρώμα κειμένου τίτλου. Προεπιλεγμένη τιμή: Color.BLACK.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Ορατότητα κειμένου τίτλου. Προεπιλεγμένη τιμή: false.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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

