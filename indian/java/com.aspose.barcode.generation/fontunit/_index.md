---
title: "FontUnit"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "टेक्स्ट के लिए एक विशिष्ट प्रारूप परिभाषित करता है जिसमें फ़ॉन्ट फ़ेस आकार और शैली गुण शामिल हैं, जहाँ आकार Unit मान प्रॉपर्टी में होता है।"
type: docs
weight: 42
url: /hi/java/com.aspose.barcode.generation/fontunit/
---
**Inheritance:**
java.lang.Object
```
public final class FontUnit
```

टेक्स्ट के लिए एक विशिष्ट फ़ॉर्मेट परिभाषित करता है, जिसमें फ़ॉन्ट फ़ेस, आकार, और शैली गुण शामिल हैं जहाँ आकार यूनिट वैल्यू प्रॉपर्टी में होता है।

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>          BarCodeGenerator generator = new BarCodeGenerator(EncodeTypes.CODE_128);
>          generator.getCodeTextStyle().getFont().setStyle(FontStyle.ITALIC);
>          generator.getCodeTextStyle().getFont().getSize().setPoint(18);
>          generator.save("test.png");
> ```
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFamilyName()](#getFamilyName--) | इस फ़ॉन्ट का फ़ेस नाम प्राप्त करता है। |
| [getSize()](#getSize--) | इस FontUnit का आकार Unit मान में प्राप्त करता है। |
| [getStyle()](#getStyle--) | इस FontUnit के लिए शैली जानकारी प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | इस फ़ॉन्ट का फ़ेस नाम सेट करता है। |
| [setStyle(int value)](#setStyle-int-) | इस FontUnit के लिए शैली जानकारी सेट करता है। |
| [toString()](#toString--) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


इस फ़ॉन्ट का फ़ेस नाम प्राप्त करता है।

**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public Unit getSize()
```


इस FontUnit का आकार Unit मान में प्राप्त करता है।

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getStyle() {#getStyle--}
```
public int getStyle()
```


इस FontUnit के लिए शैली जानकारी प्राप्त करता है।

**Returns:**
int
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




### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


इस फ़ॉन्ट का फ़ेस नाम सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setStyle(int value) {#setStyle-int-}
```
public void setStyle(int value)
```


इस FontUnit के लिए शैली जानकारी सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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

