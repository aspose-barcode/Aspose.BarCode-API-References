---
title: CodetextParameters
second_title: Aspose.BarCode for Android via Java API-referentie
description: Codetekstparameters.
type: docs
weight: 27
url: /nl/androidjava/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

Codetekstparameters.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CodetextParameters()](#CodetextParameters--) |  |
## Methods

| Method | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Haalt de uitlijning van de codetekst op. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Specificeer de kleur van de weergegeven CodeText. |
| [getFont()](#getFont--) | Specificeer het lettertype van de weergegeven CodeText. |
| [getFontMode()](#getFontMode--) | Specificeer FontMode. |
| [getLocation()](#getLocation--) | Specificeer de weergavepositie van CodeText, stel in op CodeLocation.None om CodeText te verbergen. |
|  | [getNoWrap()](#getNoWrap--) | ``` |
Specificeer woordomslag (regeleinden) binnen de tekst.
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
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | Ruimte tussen de CodeText en de BarCode in een eenheidswaarde. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Tekst die wordt weergegeven in plaats van codetekst in 2D-streepjescodes. |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze CodetextParameters. |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


Haalt de uitlijning van de codetekst op. Standaardwaarde: TextAlignment.CENTER.

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


Specificeer de weergavekleur van de CodeText. Standaardwaarde: Color.BLACK.

**Returns:**
int
### getFont() {#getFont--}
```
public FontUnit getFont()
```


Specificeer het lettertype van de weergave van CodeText. Standaardwaarde: Arial 5pt regular. Wordt genegeerd als FontMode is ingesteld op FontMode.AUTO.

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


Specificeer FontMode. Als FontMode is ingesteld op Auto, wordt de lettergrootte automatisch berekend op basis van de xDimension-waarde. Het wordt aanbevolen om FontMode.AUTO te gebruiken, vooral in AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION. Standaardwaarde: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


Specificeer de weergavelocatie van CodeText, stel in op CodeLocation.None om CodeText te verbergen. Standaardwaarde: CodeLocation.BELOW voor 1D-barcode en CodeLocation.None voor 2D-barcode.

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


Ruimte tussen de CodeText en de BarCode in eenheidswaarde. Standaardwaarde: 2pt. Genegeerd voor EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


Tekst die wordt weergegeven in plaats van codetext in 2D-barcode. Gebruikt voor: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

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


Stelt de uitlijning van de code-tekst in. Standaardwaarde: TextAlignment.CENTER.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(int value) {#setColor-int-}
```
public void setColor(int value)
```


Specificeer de weergavekleur van de CodeText. Standaardwaarde: Color.BLACK.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


Specificeer het lettertype van de weergave van CodeText. Standaardwaarde: Arial 5pt regular. Wordt genegeerd als FontMode is ingesteld op FontMode.AUTO.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


Specificeer FontMode. Als FontMode is ingesteld op Auto, wordt de lettergrootte automatisch berekend op basis van de xDimension-waarde. Het wordt aanbevolen om FontMode.AUTO te gebruiken, vooral in AutoSizeMode.NEAREST of AutoSizeMode.INTERPOLATION. Standaardwaarde: FontMode.AUTO.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


Specificeer de weergavelocatie van CodeText, stel in op CodeLocation.None om CodeText te verbergen. Standaardwaarde: CodeLocation.BELOW voor 1D-barcode en CodeLocation.None voor 2D-barcode.

**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


Ruimte tussen de CodeText en de BarCode in eenheidswaarde. Standaardwaarde: 2pt. Genegeerd voor EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Tekst die wordt weergegeven in plaats van codetext in 2D-barcode. Gebruikt voor: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze CodetextParameters.

**Returns:**
java.lang.String - Een string die deze CodetextParameters vertegenwoordigt.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

