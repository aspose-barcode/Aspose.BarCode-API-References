---
title: CodetextParameters
second_title: Aspose.BarCode per Android via Java API Reference
description: Parametri Codetext.
type: docs
weight: 27
url: /it/androidjava/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

Parametri Codetext.
## Constructors

| Constructor | Descrizione |
| --- | --- |
| [CodetextParameters()](#CodetextParameters--) |  |
## Methods

| Method | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Ottiene l'allineamento del testo codificato. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Specifica il colore del CodeText visualizzato. |
| [getFont()](#getFont--) | Specifica il font del CodeText visualizzato. |
| [getFontMode()](#getFontMode--) | Specifica FontMode. |
| [getLocation()](#getLocation--) | Specifica la posizione del CodeText visualizzato, impostala su CodeLocation.None per nascondere il CodeText. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Specifica le interruzioni di riga (a capo) nel testo.
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
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | Spazio tra il CodeText e il BarCode nel valore dell'Unità. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Testo che verrà visualizzato al posto del codetext nei codici a barre 2D. |
| [toString()](#toString--) | Restituisce una rappresentazione stringa leggibile dall'uomo di questi CodetextParameters. |
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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Ottiene l'allineamento del testo codificato. Valore predefinito: TextAlignment.CENTER.

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


Specifica il colore del CodeText visualizzato. Valore predefinito: Color.BLACK.

**Returns:**
int
### getFont() {#getFont--}
```
public FontUnit getFont()
```


Specifica il font del CodeText visualizzato. Valore predefinito: Arial 5pt regular. Ignorato se FontMode è impostato su FontMode.AUTO.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


Specifica FontMode. Se FontMode è impostato su Auto, la dimensione del font verrà calcolata automaticamente in base al valore xDimension. Si consiglia di utilizzare FontMode.AUTO soprattutto in AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. Valore predefinito: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Specifica la posizione del CodeText visualizzato, impostala su CodeLocation.None per nascondere il CodeText. Valore predefinito: CodeLocation.BELOW per i codici a barre 1D e CodeLocation.None per i codici a barre 2D.

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


Spazio tra il CodeText e il BarCode in unità. Valore predefinito: 2pt. Ignorato per EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


Testo che verrà visualizzato al posto del codetext nei codici a barre 2D. Utilizzato per: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

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


Imposta l'allineamento del testo del codice. Valore predefinito: TextAlignment.CENTER.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(int value) {#setColor-int-}
```
public void setColor(int value)
```


Specifica il colore del CodeText visualizzato. Valore predefinito: Color.BLACK.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | int |  |

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


Specifica il font del CodeText visualizzato. Valore predefinito: Arial 5pt regular. Ignorato se FontMode è impostato su FontMode.AUTO.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


Specifica FontMode. Se FontMode è impostato su Auto, la dimensione del font verrà calcolata automaticamente in base al valore xDimension. Si consiglia di utilizzare FontMode.AUTO soprattutto in AutoSizeMode.NEAREST o AutoSizeMode.INTERPOLATION. Valore predefinito: FontMode.AUTO.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


Specifica la posizione del CodeText visualizzato, impostala su CodeLocation.None per nascondere il CodeText. Valore predefinito: CodeLocation.BELOW per i codici a barre 1D e CodeLocation.None per i codici a barre 2D.

**Parameters:**
| Parameter | Type | Descrizione |
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
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


Spazio tra il CodeText e il BarCode in unità. Valore predefinito: 2pt. Ignorato per EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Testo che verrà visualizzato al posto del codetext nei codici a barre 2D. Utilizzato per: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Restituisce una rappresentazione stringa leggibile dall'uomo di questi CodetextParameters.

**Returns:**
java.lang.String - Una stringa che rappresenta questo CodetextParameters.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

