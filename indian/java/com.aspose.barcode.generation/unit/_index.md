---
title: "Unit"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "विभिन्न इकाइयों जैसे पिक्सेल, इंच आदि में आकार मान निर्दिष्ट करता है।"
type: docs
weight: 67
url: /hi/java/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

विभिन्न इकाइयों (पिक्सेल, इंच आदि) में आकार मान निर्दिष्ट करता है।

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि यह इंस्टेंस और एक निर्दिष्ट ऑब्जेक्ट, जो भी एक  Unit  ऑब्जेक्ट होना चाहिए, का मान समान है या नहीं। |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | दस्तावेज़ इकाइयों में आकार मान प्राप्त करता है। |
| [getInches()](#getInches--) | इंच में आकार मान प्राप्त करता है। |
| [getMillimeters()](#getMillimeters--) | मिलिमीटर में आकार मान प्राप्त करता है। |
| [getPixels()](#getPixels--) | पिक्सेल में आकार मान प्राप्त करता है। |
| [getPoint()](#getPoint--) | पॉइंट में आकार मान प्राप्त करता है। |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | इस ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | दस्तावेज़ इकाइयों में आकार मान सेट करता है। |
| [setInches(float value)](#setInches-float-) | इंच में आकार मान सेट करता है। |
| [setMillimeters(float value)](#setMillimeters-float-) | मिलिमीटर में आकार मान सेट करता है। |
| [setPixels(float value)](#setPixels-float-) | पिक्सेल में आकार मान सेट करता है। |
| [setPoint(float value)](#setPoint-float-) | पॉइंट में आकार मान सेट करता है। |
| [toString()](#toString--) | इस  Unit  की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि यह इंस्टेंस और एक निर्दिष्ट ऑब्जेक्ट, जो भी एक  Unit  ऑब्जेक्ट होना चाहिए, का मान समान है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस इंस्टेंस से तुलना करने के लिए  Unit . |

**Returns:**
boolean - true यदि obj एक  Unit  है और उसका मान इस इंस्टेंस के समान है; अन्यथा false। यदि obj null है, तो मेथड false लौटाता है।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public float getDocument()
```


दस्तावेज़ इकाइयों में आकार मान प्राप्त करता है।

**Returns:**
float
### getInches() {#getInches--}
```
public float getInches()
```


इंच में आकार मान प्राप्त करता है।

**Returns:**
float
### getMillimeters() {#getMillimeters--}
```
public float getMillimeters()
```


मिलिमीटर में आकार मान प्राप्त करता है।

**Returns:**
float
### getPixels() {#getPixels--}
```
public float getPixels()
```


पिक्सेल में आकार मान प्राप्त करता है।

**Returns:**
float
### getPoint() {#getPoint--}
```
public float getPoint()
```


पॉइंट में आकार मान प्राप्त करता है।

**Returns:**
float
### getResolution() {#getResolution--}
```
public float getResolution()
```




**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस ऑब्जेक्ट के लिए हैश कोड लौटाता है।

**Returns:**
int - 32-बिट साइन्ड इंटीजर हैश कोड।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDocument(float value) {#setDocument-float-}
```
public void setDocument(float value)
```


दस्तावेज़ इकाइयों में आकार मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


इंच में आकार मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


मिलिमीटर में आकार मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


पिक्सेल में आकार मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


पॉइंट में आकार मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### toString() {#toString--}
```
public String toString()
```


इस  Unit  की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस  Unit  का प्रतिनिधित्व करती है।
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dpi | float |  |

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

