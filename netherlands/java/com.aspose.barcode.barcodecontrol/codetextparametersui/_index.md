---
title: "CodetextParametersUI"
second_title: "Aspose.BarCode for Java API-referentie"
description: "UI-wrapper voor de klasse com.aspose.barcode.generation.CodetextParameters."
type: docs
weight: 13
url: /nl/java/com.aspose.barcode.barcodecontrol/codetextparametersui/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParametersUI
```

UI-wrapper voor de klasse com.aspose.barcode.generation.CodetextParameters.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Haalt de uitlijning van de code-tekst op. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Specificeer de kleur van de weergegeven CodeText. |
| [getFont()](#getFont--) | Specificeer het lettertype van de weergegeven CodeText. |
| [getFontMode()](#getFontMode--) | Specificeer FontMode. |
| [getLocation()](#getLocation--) | Specificeer de locatie van de weergegeven CodeText, stel in op CodeLocation.None om CodeText te verbergen. |
| [getSpace()](#getSpace--) | Ruimte tussen de CodeText en de BarCode in  waarde. |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | Tekst die wordt weergegeven in plaats van codetext in 2D-streepjescodes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | Stelt de uitlijning van de code-tekst in. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Specificeer de kleur van de weergegeven CodeText. |
| [setFont(Font value)](#setFont-java.awt.Font-) | Specificeer het lettertype van de weergegeven CodeText. |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | Specificeer FontMode. |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | Specificeer de locatie van de weergegeven CodeText, stel in op CodeLocation.None om CodeText te verbergen. |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | Tekst die wordt weergegeven in plaats van codetext in 2D-streepjescodes. |
| [toString()](#toString--) | Retourneert een menselijk leesbare tekenreeksrepresentatie van deze CodetextParameters . |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


Haalt de uitlijning van de code-tekst op. Standaardwaarde: StringAlignment.Center.

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


Specificeer de kleur van de weergegeven CodeText. Standaardwaarde: Color.BLACK.

**Returns:**
java.awt.Color
### getFont() {#getFont--}
```
public Font getFont()
```


Specificeer het lettertype van de weergegeven CodeText. Standaardwaarde: Arial 5pt regular. Genegeerd als FontMode is ingesteld op FontMode.AUTO.

**Returns:**
java.awt.Font
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


Specificeer de locatie van de weergegeven CodeText, stel in op CodeLocation.None om CodeText te verbergen. Standaardwaarde: CodeLocation.BELOW voor 1D-streepjescodes en CodeLocation.None voor 2D-streepjescodes.

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


Ruimte tussen de CodeText en de BarCode in  waarde. Standaardwaarde: 2pt. Genegeerd voor EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon.

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


Tekst die wordt weergegeven in plaats van codetext in 2D-streepjescodes. Gebruikt voor: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

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


Stelt de uitlijning van de code-tekst in. Standaardwaarde: StringAlignment.Center.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


Specificeer de kleur van de weergegeven CodeText. Standaardwaarde: Color.BLACK.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.awt.Color |  |

### setFont(Font value) {#setFont-java.awt.Font-}
```
public void setFont(Font value)
```


Specificeer het lettertype van de weergegeven CodeText. Standaardwaarde: Arial 5pt regular. Genegeerd als FontMode is ingesteld op FontMode.AUTO.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.awt.Font |  |

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


Specificeer de locatie van de weergegeven CodeText, stel in op CodeLocation.None om CodeText te verbergen. Standaardwaarde: CodeLocation.BELOW voor 1D-streepjescodes en CodeLocation.None voor 2D-streepjescodes.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


Tekst die wordt weergegeven in plaats van codetext in 2D-streepjescodes. Gebruikt voor: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Retourneert een menselijk leesbare tekenreeksrepresentatie van deze CodetextParameters .

**Returns:**
java.lang.String - Een string die deze CodetextParameters vertegenwoordigt .
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
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

