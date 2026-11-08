---
title: "CodetextParametersUI"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "UI रैपर for com.aspose.barcode.generation.CodetextParameters क्लास."
type: docs
weight: 13
url: /hi/java/com.aspose.barcode.barcodecontrol/codetextparametersui/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParametersUI
```

UI रैपर for com.aspose.barcode.generation.CodetextParameters क्लास.
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | कोड टेक्स्ट का संरेखण प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | CodeText के प्रदर्शित रंग को निर्दिष्ट करें। |
| [getFont()](#getFont--) | CodeText के प्रदर्शित फ़ॉन्ट को निर्दिष्ट करें। |
| [getFontMode()](#getFontMode--) | FontMode निर्दिष्ट करें। |
| [getLocation()](#getLocation--) | CodeText के प्रदर्शित स्थान को निर्दिष्ट करें, CodeText को छिपाने के लिए CodeLocation.None सेट करें। |
| [getSpace()](#getSpace--) | CodeText और BarCode के बीच का अंतराल  मान में। |
| [getTwoDDisplayText()](#getTwoDDisplayText--) | 2D बारकोड में कोडटेक्स्ट के स्थान पर प्रदर्शित होने वाला टेक्स्ट। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(TextAlignment value)](#setAlignment-com.aspose.barcode.generation.TextAlignment-) | कोड टेक्स्ट का संरेखण सेट करता है। |
| [setColor(Color value)](#setColor-java.awt.Color-) | CodeText के प्रदर्शित रंग को निर्दिष्ट करें। |
| [setFont(Font value)](#setFont-java.awt.Font-) | CodeText के प्रदर्शित फ़ॉन्ट को निर्दिष्ट करें। |
| [setFontMode(FontMode value)](#setFontMode-com.aspose.barcode.generation.FontMode-) | FontMode निर्दिष्ट करें। |
| [setLocation(CodeLocation value)](#setLocation-com.aspose.barcode.generation.CodeLocation-) | CodeText के प्रदर्शित स्थान को निर्दिष्ट करें, CodeText को छिपाने के लिए CodeLocation.None सेट करें। |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | 2D बारकोड में कोडटेक्स्ट के स्थान पर प्रदर्शित होने वाला टेक्स्ट। |
| [toString()](#toString--) | इस CodetextParameters का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


कोड टेक्स्ट का संरेखण प्राप्त करता है। डिफ़ॉल्ट मान: StringAlignment.Center।

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


CodeText के प्रदर्शित रंग को निर्दिष्ट करें। डिफ़ॉल्ट मान: Color.BLACK।

**Returns:**
java.awt.Color
### getFont() {#getFont--}
```
public Font getFont()
```


CodeText के प्रदर्शित फ़ॉन्ट को निर्दिष्ट करें। डिफ़ॉल्ट मान: Arial 5pt regular। यदि FontMode को FontMode.AUTO पर सेट किया गया है तो यह अनदेखा किया जाएगा।

**Returns:**
java.awt.Font
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


FontMode निर्दिष्ट करें। यदि FontMode को Auto पर सेट किया जाता है, तो फ़ॉन्ट आकार xDimension मान के आधार पर स्वचालित रूप से गणना किया जाएगा। AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION में विशेष रूप से FontMode.AUTO का उपयोग करने की सलाह दी जाती है। डिफ़ॉल्ट मान: FontMode.AUTO।

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


CodeText के प्रदर्शित स्थान को निर्दिष्ट करें, CodeText को छिपाने के लिए CodeLocation.None सेट करें। डिफ़ॉल्ट मान: 1D बारकोड के लिए CodeLocation.BELOW और 2D बारकोड के लिए CodeLocation.None।

**Returns:**
[CodeLocation](../../com.aspose.barcode.generation/codelocation)
### getSpace() {#getSpace--}
```
public Unit getSpace()
```


CodeText और BarCode के बीच का अंतराल  मान में। डिफ़ॉल्ट मान: 2pt। EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon के लिए अनदेखा किया जाता है।

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


2D बारकोड में कोडटेक्स्ट के स्थान पर प्रदर्शित होने वाला टेक्स्ट। उपयोग किया जाता है: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode के लिए।

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


कोड टेक्स्ट का संरेखण सेट करता है। डिफ़ॉल्ट मान: StringAlignment.Center।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(Color value) {#setColor-java.awt.Color-}
```
public void setColor(Color value)
```


CodeText के प्रदर्शित रंग को निर्दिष्ट करें। डिफ़ॉल्ट मान: Color.BLACK।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.awt.Color |  |

### setFont(Font value) {#setFont-java.awt.Font-}
```
public void setFont(Font value)
```


CodeText के प्रदर्शित फ़ॉन्ट को निर्दिष्ट करें। डिफ़ॉल्ट मान: Arial 5pt regular। यदि FontMode को FontMode.AUTO पर सेट किया गया है तो यह अनदेखा किया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.awt.Font |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


FontMode निर्दिष्ट करें। यदि FontMode को Auto पर सेट किया जाता है, तो फ़ॉन्ट आकार xDimension मान के आधार पर स्वचालित रूप से गणना किया जाएगा। AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION में विशेष रूप से FontMode.AUTO का उपयोग करने की सलाह दी जाती है। डिफ़ॉल्ट मान: FontMode.AUTO।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


CodeText के प्रदर्शित स्थान को निर्दिष्ट करें, CodeText को छिपाने के लिए CodeLocation.None सेट करें। डिफ़ॉल्ट मान: 1D बारकोड के लिए CodeLocation.BELOW और 2D बारकोड के लिए CodeLocation.None।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [CodeLocation](../../com.aspose.barcode.generation/codelocation) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


2D बारकोड में कोडटेक्स्ट के स्थान पर प्रदर्शित होने वाला टेक्स्ट। उपयोग किया जाता है: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode के लिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


इस CodetextParameters का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस CodetextParameters का प्रतिनिधित्व करती है।
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

