---
title: "CodetextParametersUI"
second_title: "Riferimento API di Aspose.BarCode per Java"
description: "Wrapper UI per la classe com.aspose.barcode.generation.CodetextParameters."
type: docs
weight: 13
url: /it/java/com.aspose.barcode.barcodecontrol/codetextparametersui/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParametersUI
```

Wrapper UI per la classe com.aspose.barcode.generation.CodetextParameters.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Ottiene l'allineamento del testo del codice. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Specifica il colore del CodeText visualizzato. |
| [getFont()](#getFont--) | Specifica il carattere del CodeText visualizzato. |
| [getFontMode()](#getFontMode--) | Specifica FontMode. |
| [getLocation()](#getLocation--) | Specifica la posizione del CodeText visualizzato, impostala su CodeLocation.None per nascondere il CodeText. |
| [getSpace()](#getSpace--) | Spazio tra il CodeText e il BarCode nel valore. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Testo che verrà visualizzato al posto del codetext nei codici a barre 2D. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Imposta l'allineamento del testo del codice. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Specifica il colore del CodeText visualizzato. |
| [setFont(Font value)](#setFont-java.awt.Font-) | Specifica il carattere del CodeText visualizzato. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Specifica FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Specifica la posizione del CodeText visualizzato, impostala su CodeLocation.None per nascondere il CodeText. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Testo che verrà visualizzato al posto del codetext nei codici a barre 2D. |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questo CodetextParameters. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


Ottiene l'allineamento del testo del codice. Valore predefinito: StringAlignment.Center.

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


Specifica il colore del CodeText visualizzato. Valore predefinito: Color.BLACK.

**Returns:**
java.awt.Color
### getFont() {#getFont--}
```
public Font getFont()
```


Specifica il carattere del CodeText visualizzato. Valore predefinito: Arial 5pt regular. Ignorato se FontMode è impostato su FontMode.AUTO.

**Returns:**
java.awt.Font
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


Specifica FontMode. Se FontMode è impostato su Auto, la dimensione del carattere verrà calcolata automaticamente in base al valore xDimension. Si consiglia di utilizzare FontMode.AUTO soprattutto in AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. Valore predefinito: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Specifica la posizione del CodeText visualizzato, impostala su CodeLocation.None per nascondere il CodeText. Valore predefinito: CodeLocation.BELOW per i codici a barre 1D e CodeLocation.None per i codici a barre 2D.

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


Spazio tra il CodeText e il BarCode nel valore. Valore predefinito: 2pt. Ignorato per EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


Testo che verrà visualizzato al posto del codetext nei codici a barre 2D. Utilizzato per: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode.

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


Imposta l'allineamento del testo del codice. Valore predefinito: StringAlignment.Center.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


Specifica il colore del CodeText visualizzato. Valore predefinito: Color.BLACK.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Color |  |

### setFont(Font value) {#setFont-java.awt.Font-}
```
public void setFont(Font value)
```


Specifica il carattere del CodeText visualizzato. Valore predefinito: Arial 5pt regular. Ignorato se FontMode è impostato su FontMode.AUTO.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.awt.Font |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


Specifica FontMode. Se FontMode è impostato su Auto, la dimensione del carattere verrà calcolata automaticamente in base al valore xDimension. Si consiglia di utilizzare FontMode.AUTO soprattutto in AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. Valore predefinito: FontMode.AUTO.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


Specifica la posizione del CodeText visualizzato, impostala su CodeLocation.None per nascondere il CodeText. Valore predefinito: CodeLocation.BELOW per i codici a barre 1D e CodeLocation.None per i codici a barre 2D.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Testo che verrà visualizzato al posto del codetext nei codici a barre 2D. Utilizzato per: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa leggibile dall'uomo di questo CodetextParameters.

**Returns:**
java.lang.String - Una stringa che rappresenta questo CodetextParameters.
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

