---
title: CodetextParameters
second_title: Référence d'API Aspose.BarCode pour Android via Java
description: Paramètres de texte de code.
type: docs
weight: 27
url: /fr/androidjava/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

Paramètres de texte de code.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CodetextParameters()](#CodetextParameters--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Obtient l'alignement du texte de code. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Spécifie la couleur du texte de code affiché. |
| [getFont()](#getFont--) | Spécifie la police du texte de code affiché. |
| [getFontMode()](#getFontMode--) | Spécifie le mode de police. |
| [getLocation()](#getLocation--) | Spécifie l'emplacement du texte de code affiché, définissez à CodeLocation.None pour masquer le texte de code. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Spécifie les retours à la ligne (césures) dans le texte.
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
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | Espace entre le texte de code et le code-barres en valeur d'unité. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Texte qui sera affiché à la place du texte de code dans les codes-barres 2D. |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne lisible de cet objet CodetextParameters. |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Obtient l'alignement du texte de code. Valeur par défaut : TextAlignment.CENTER.

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


Spécifiez la couleur du texte du code affiché. Valeur par défaut : Color.BLACK.

**Returns:**
int
### getFont() {#getFont--}
```
public FontUnit getFont()
```


Spécifiez la police du texte du code affiché. Valeur par défaut : Arial 5pt régulier. Ignoré si FontMode est défini sur FontMode.AUTO.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


Spécifiez le FontMode. Si FontMode est défini sur Auto, la taille de la police sera calculée automatiquement en fonction de la valeur xDimension. Il est recommandé d’utiliser FontMode.AUTO notamment dans AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION. Valeur par défaut : FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Spécifiez l’emplacement du texte du code affiché, définissez CodeLocation.None pour masquer le texte du code. Valeur par défaut : CodeLocation.BELOW pour les codes-barres 1D et CodeLocation.None pour les codes-barres 2D.

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


Espace entre le texte du code et le code-barres en valeur d’unité. Valeur par défaut : 2pt. Ignoré pour EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


Texte qui sera affiché à la place du texte du code dans les codes-barres 2D. Utilisé pour : Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode.

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


Définit l’alignement du texte du code. Valeur par défaut : TextAlignment.CENTER.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(int value) {#setColor-int-}
```
public void setColor(int value)
```


Spécifiez la couleur du texte du code affiché. Valeur par défaut : Color.BLACK.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


Spécifiez la police du texte du code affiché. Valeur par défaut : Arial 5pt régulier. Ignoré si FontMode est défini sur FontMode.AUTO.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


Spécifiez le FontMode. Si FontMode est défini sur Auto, la taille de la police sera calculée automatiquement en fonction de la valeur xDimension. Il est recommandé d’utiliser FontMode.AUTO notamment dans AutoSizeMode.NEAREST ou AutoSizeMode.INTERPOLATION. Valeur par défaut : FontMode.AUTO.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


Spécifiez l’emplacement du texte du code affiché, définissez CodeLocation.None pour masquer le texte du code. Valeur par défaut : CodeLocation.BELOW pour les codes-barres 1D et CodeLocation.None pour les codes-barres 2D.

**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


Espace entre le texte du code et le code-barres en valeur d’unité. Valeur par défaut : 2pt. Ignoré pour EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Texte qui sera affiché à la place du texte du code dans les codes-barres 2D. Utilisé pour : Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne lisible de cet objet CodetextParameters.

**Returns:**
java.lang.String - Une chaîne qui représente ces CodetextParameters.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

