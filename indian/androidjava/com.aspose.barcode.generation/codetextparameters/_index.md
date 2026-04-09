---
title: CodetextParameters
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: कोडटेक्स्ट पैरामीटर।
type: docs
weight: 27
url: /hi/androidjava/com.aspose.barcode.generation/codetextparameters/
---
**Inheritance:**
java.lang.Object
```
public class CodetextParameters
```

कोडटेक्स्ट पैरामीटर।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [CodetextParameters()](#CodetextParameters--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | कोड टेक्स्ट का संरेखण प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | प्रदर्शित कोडटेक्स्ट का रंग निर्दिष्ट करें। |
| [getFont()](#getFont--) | प्रदर्शित कोडटेक्स्ट का फ़ॉन्ट निर्दिष्ट करें। |
| [getFontMode()](#getFontMode--) | फ़ॉन्ट मोड निर्दिष्ट करें। |
| [getLocation()](#getLocation--) | प्रदर्शित कोडटेक्स्ट का स्थान निर्दिष्ट करें, कोडटेक्स्ट को छिपाने के लिए CodeLocation.None सेट करें। |
|  | [getNoWrap()](#getNoWrap--) | ``` |
पाठ के भीतर शब्द रैप (लाइन ब्रेक) निर्दिष्ट करें।
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
| [setSpace(Unit value)](#setSpace-com.aspose.barcode.generation.Unit-) | इकाई मान में कोडटेक्स्ट और बारकोड के बीच की दूरी। |
| [setTwoDDisplayText(String value)](#setTwoDDisplayText-java.lang.String-) | 2D बारकोड में कोडटेक्स्ट के बजाय प्रदर्शित किया जाने वाला पाठ। |
| [toString()](#toString--) | इस CodetextParameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlignment() {#getAlignment--}
```
public TextAlignment getAlignment()
```


कोड टेक्स्ट का संरेखण प्राप्त करता है। डिफ़ॉल्ट मान: TextAlignment.CENTER।

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


कोडटेक्स्ट के प्रदर्शित रंग को निर्दिष्ट करें। डिफ़ॉल्ट मान: Color.BLACK.

**Returns:**
int
### getFont() {#getFont--}
```
public FontUnit getFont()
```


कोडटेक्स्ट के प्रदर्शित फ़ॉन्ट को निर्दिष्ट करें। डिफ़ॉल्ट मान: Arial 5pt regular। यदि FontMode को FontMode.AUTO पर सेट किया गया है तो इसे अनदेखा किया जाएगा।

**Returns:**
[FontUnit](../../com.aspose.barcode.generation/fontunit)
### getFontMode() {#getFontMode--}
```
public FontMode getFontMode()
```


FontMode को निर्दिष्ट करें। यदि FontMode को Auto पर सेट किया जाता है, तो फ़ॉन्ट आकार xDimension मान के आधार पर स्वचालित रूप से गणना किया जाएगा। AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION में विशेष रूप से FontMode.AUTO का उपयोग करने की सलाह दी जाती है। डिफ़ॉल्ट मान: FontMode.AUTO.

**Returns:**
[FontMode](../../com.aspose.barcode.generation/fontmode)
### getLocation() {#getLocation--}
```
public CodeLocation getLocation()
```


कोडटेक्स्ट के प्रदर्शित स्थान को निर्दिष्ट करें, कोडटेक्स्ट को छिपाने के लिए CodeLocation.None सेट करें। डिफ़ॉल्ट मान: 1D बारकोड के लिए CodeLocation.BELOW और 2D बारकोड के लिए CodeLocation.None।

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


कोडटेक्स्ट और बारकोड के बीच की दूरी यूनिट मान में। डिफ़ॉल्ट मान: 2pt। EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon के लिए इसे अनदेखा किया जाता है।

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getTwoDDisplayText() {#getTwoDDisplayText--}
```
public String getTwoDDisplayText()
```


2D बारकोड में कोडटेक्स्ट के बजाय प्रदर्शित होने वाला पाठ। उपयोग किया जाता है: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode।

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


कोड टेक्स्ट की संरेखण सेट करता है। डिफ़ॉल्ट मान: TextAlignment.CENTER.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [TextAlignment](../../com.aspose.barcode.generation/textalignment) |  |

### setColor(int value) {#setColor-int-}
```
public void setColor(int value)
```


कोडटेक्स्ट के प्रदर्शित रंग को निर्दिष्ट करें। डिफ़ॉल्ट मान: Color.BLACK.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setFont(FontUnit value) {#setFont-com.aspose.barcode.generation.FontUnit-}
```
public void setFont(FontUnit value)
```


कोडटेक्स्ट के प्रदर्शित फ़ॉन्ट को निर्दिष्ट करें। डिफ़ॉल्ट मान: Arial 5pt regular। यदि FontMode को FontMode.AUTO पर सेट किया गया है तो इसे अनदेखा किया जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### setFontMode(FontMode value) {#setFontMode-com.aspose.barcode.generation.FontMode-}
```
public void setFontMode(FontMode value)
```


FontMode को निर्दिष्ट करें। यदि FontMode को Auto पर सेट किया जाता है, तो फ़ॉन्ट आकार xDimension मान के आधार पर स्वचालित रूप से गणना किया जाएगा। AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION में विशेष रूप से FontMode.AUTO का उपयोग करने की सलाह दी जाती है। डिफ़ॉल्ट मान: FontMode.AUTO.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [FontMode](../../com.aspose.barcode.generation/fontmode) |  |

### setLocation(CodeLocation value) {#setLocation-com.aspose.barcode.generation.CodeLocation-}
```
public void setLocation(CodeLocation value)
```


कोडटेक्स्ट के प्रदर्शित स्थान को निर्दिष्ट करें, कोडटेक्स्ट को छिपाने के लिए CodeLocation.None सेट करें। डिफ़ॉल्ट मान: 1D बारकोड के लिए CodeLocation.BELOW और 2D बारकोड के लिए CodeLocation.None।

**Parameters:**
| Parameter | Type | विवरण |
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setSpace(Unit value) {#setSpace-com.aspose.barcode.generation.Unit-}
```
public void setSpace(Unit value)
```


कोडटेक्स्ट और बारकोड के बीच की दूरी यूनिट मान में। डिफ़ॉल्ट मान: 2pt। EAN8, EAN13, UPCE, UPCA, ISBN, ISMN, ISSN, UpcaGs1DatabarCoupon के लिए इसे अनदेखा किया जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setTwoDDisplayText(String value) {#setTwoDDisplayText-java.lang.String-}
```
public void setTwoDDisplayText(String value)
```


2D बारकोड में कोडटेक्स्ट के बजाय प्रदर्शित होने वाला पाठ। उपयोग किया जाता है: Aztec, Pdf417, DataMatrix, QR, MaxiCode, DotCode।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


इस CodetextParameters की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस CodetextParameters को दर्शाती है।
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | लॉन्ग |  |
| arg1 | int |  |

