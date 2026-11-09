---
title: "CaptionParameters"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Parametri della didascalia."
type: docs
weight: 20
url: /it/java/com.aspose.barcode.generation/captionparameters/
---
**Inheritance:**
java.lang.Object
```
public class CaptionParameters
```

Parametri della didascalia.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CaptionParameters()](#CaptionParameters--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Allineamento orizzontale del test della didascalia. |
| [getClass()](#getClass--) |  |
| [getFont()](#getFont--) | Carattere della didascalia. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Specifica le interruzioni di riga (a capo) all'interno del testo.
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
| [setPadding(Padding value)](#setPadding-com.aspose.barcode.generation.Padding-) | Spaziatura delle didascalie. |
| [setText(String value)](#setText-java.lang.String-) | Testo della didascalia. |
| [setTextColor(Color value)](#setTextColor-java.awt.Color-) | Colore del testo della didascalia. |
| [setVisible(boolean value)](#setVisible-boolean-) | Visibilità del testo della didascalia. |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Allineamento orizzontale del test della didascalia. Valore predefinito: StringAlignment.Center.

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


Carattere della didascalia. Valore predefinito: Arial 8pt regular.

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


Spaziatura delle didascalie. Valore predefinito per CaptionAbove: 5pt 5pt 0 5pt. Valore predefinito per CaptionBelow: 0 5pt 5pt 5pt.

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getText() {#getText--}
```
public String getText()
```


Testo della didascalia. Valore predefinito: stringa vuota.

**Returns:**
java.lang.String
### getTextColor() {#getTextColor--}
```
public Color getTextColor()
```


Colore del testo della didascalia. Valore predefinito: Color.BLACK.

**Returns:**
java.awt.Color
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


Visibilità del testo della didascalia. Valore predefinito: false.

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


Allineamento orizzontale del test della didascalia. Valore predefinito: StringAlignment.Center.

**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setPadding(Padding value) {#setPadding-com.aspose.barcode.generation.Padding-}
```
public void setPadding(Padding value)
```


Spaziatura delle didascalie. Valore predefinito per CaptionAbove: 5pt 5pt 0 5pt. Valore predefinito per CaptionBelow: 0 5pt 5pt 5pt.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Padding](../../com.aspose.barcode.generation/padding) |  |

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Testo della didascalia. Valore predefinito: stringa vuota.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### setTextColor(Color value) {#setTextColor-java.awt.Color-}
```
public void setTextColor(Color value)
```


Colore del testo della didascalia. Valore predefinito: Color.BLACK.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Color |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


Visibilità del testo della didascalia. Valore predefinito: false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

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
public final native void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

