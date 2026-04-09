---
title: FontUnit
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: पाठ के लिए एक विशिष्ट प्रारूप को परिभाषित करता है जिसमें फ़ॉन्ट फ़ेस आकार और शैली गुण शामिल होते हैं, जहाँ आकार यूनिट वैल्यू प्रॉपर्टी में होता है।
type: docs
weight: 44
url: /hi/androidjava/com.aspose.barcode.generation/fontunit/
---
**Inheritance:**
java.lang.Object
```
public final class FontUnit
```

पाठ के लिए एक विशिष्ट स्वरूप को परिभाषित करता है, जिसमें फ़ॉन्ट फ़ेस, आकार, और शैली गुण शामिल हैं जहाँ आकार Unit value प्रॉपर्टी में होता है।

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>          BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>          generator.getCodeTextStyle().getFont().setStyle(FontStyle.ITALIC);
>          generator.getCodeTextStyle().getFont().getSize().setPoint(18);
>          generator.save("test.png");
> ```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [FontUnit(FontUnit source)](#FontUnit-com.aspose.barcode.generation.FontUnit-) |  |
| [FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi)](#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-) |  |
| [FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi, int style)](#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-int-) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFamilyName()](#getFamilyName--) | इस फ़ॉन्ट का फ़ेस नाम प्राप्त करता है। |
| [getSize()](#getSize--) | इस फ़ॉन्टयूनिट का आकार यूनिट वैल्यू में प्राप्त करता है। |
| [getStateHash()](#getStateHash--) |  |
| [getStyle()](#getStyle--) | इस फ़ॉन्टयूनिट के लिए शैली जानकारी प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFamilyName(Typeface value)](#setFamilyName-android.graphics.Typeface-) | इस फ़ॉन्ट का फ़ेस नाम सेट करता है। |
| [setStyle(int value)](#setStyle-int-) | इस फ़ॉन्टयूनिट के लिए शैली जानकारी सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontUnit(FontUnit source) {#FontUnit-com.aspose.barcode.generation.FontUnit-}
```
public FontUnit(FontUnit source)
```


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| source | [FontUnit](../../com.aspose.barcode.generation/fontunit) |  |

### FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi) {#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-}
```
public FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi)
```


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| familyName | android.graphics.Typeface |  |
| sizeValue | float |  |
| graphicsUnit | [GraphicsUnit](../../com.aspose.barcode.generation/graphicsunit) |  |
| dpi | float |  |

### FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi, int style) {#FontUnit-android.graphics.Typeface-float-com.aspose.barcode.generation.GraphicsUnit-float-int-}
```
public FontUnit(Typeface familyName, float sizeValue, GraphicsUnit graphicsUnit, float dpi, int style)
```


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| familyName | android.graphics.Typeface |  |
| sizeValue | float |  |
| graphicsUnit | [GraphicsUnit](../../com.aspose.barcode.generation/graphicsunit) |  |
| dpi | float |  |
| style | int |  |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFamilyName() {#getFamilyName--}
```
public Typeface getFamilyName()
```


इस फ़ॉन्ट का फ़ेस नाम प्राप्त करता है।

**Returns:**
android.graphics.Typeface
### getSize() {#getSize--}
```
public Unit getSize()
```


इस फ़ॉन्टयूनिट का आकार यूनिट वैल्यू में प्राप्त करता है।

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getStateHash() {#getStateHash--}
```
public int getStateHash()
```




**Returns:**
int
### getStyle() {#getStyle--}
```
public int getStyle()
```


इस फ़ॉन्टयूनिट के लिए शैली जानकारी प्राप्त करता है।

**Returns:**
int
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




### setFamilyName(Typeface value) {#setFamilyName-android.graphics.Typeface-}
```
public void setFamilyName(Typeface value)
```


इस फ़ॉन्ट का फ़ेस नाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | android.graphics.Typeface |  |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


इस फ़ॉन्टयूनिट के लिए शैली जानकारी सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

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

