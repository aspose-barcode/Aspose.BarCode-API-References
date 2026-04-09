---
title: इकाई
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: विभिन्न इकाइयों (पिक्सेल, इंच आदि) में आकार मान निर्दिष्ट करता है।
type: docs
weight: 69
url: /hi/androidjava/com.aspose.barcode.generation/unit/
---
**Inheritance:**
java.lang.Object
```
public final class Unit
```

विभिन्न इकाइयों (पिक्सेल, इंच, आदि) में आकार मान को निर्दिष्ट करता है।

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.CODE_128);
>  	  generator.getParameters().getBarcode().getBarHeight().setMillimeters(10);
>     generator.save("test.png");
> ```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Unit(Unit source)](#Unit-com.aspose.barcode.generation.Unit-) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि यह इंस्टेंस और निर्दिष्ट ऑब्जेक्ट, जो भी एक  Unit  ऑब्जेक्ट होना चाहिए, का मान समान है या नहीं। |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | दस्तावेज़ इकाइयों में आकार मान प्राप्त करता है। |
| [getInches()](#getInches--) | इंच में आकार मान प्राप्त करता है। |
| [getMillimeters()](#getMillimeters--) | मिलीमीटर में आकार मान प्राप्त करता है। |
| [getPixels()](#getPixels--) | पिक्सेल में आकार मान प्राप्त करता है। |
| [getPoint()](#getPoint--) | पॉइंट में आकार मान प्राप्त करता है। |
| [getResolution()](#getResolution--) |  |
| [hashCode()](#hashCode--) | इस ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDocument(float value)](#setDocument-float-) | दस्तावेज़ इकाइयों में आकार मान सेट करता है। |
| [setInches(float value)](#setInches-float-) | इंच में आकार मान सेट करता है। |
| [setMillimeters(float value)](#setMillimeters-float-) | मिलीमीटर में आकार मान सेट करता है। |
| [setPixels(float value)](#setPixels-float-) | पिक्सेल में आकार मान सेट करता है। |
| [setPoint(float value)](#setPoint-float-) | Sets size value in point. |
| [toString()](#toString--) | Returns a human-readable string representation of this  Unit . |
| [updateResolution(float dpi)](#updateResolution-float-) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Unit(Unit source) {#Unit-com.aspose.barcode.generation.Unit-}
```
public Unit(Unit source)
```


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| source | [Unit](../../com.aspose.barcode.generation/unit) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि यह इंस्टेंस और निर्दिष्ट ऑब्जेक्ट, जो भी एक  Unit  ऑब्जेक्ट होना चाहिए, का मान समान है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | The  Unit  to compare to this instance. |

**Returns:**
boolean - true if obj is a  Unit  and its value is the same as this instance; otherwise, false. If obj is null, the method returns false.
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


मिलीमीटर में आकार मान प्राप्त करता है।

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
int - एक 32-बिट साइन्ड इंटेजर हैश कोड।
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
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### setInches(float value) {#setInches-float-}
```
public void setInches(float value)
```


इंच में आकार मान सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### setMillimeters(float value) {#setMillimeters-float-}
```
public void setMillimeters(float value)
```


मिलीमीटर में आकार मान सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### setPixels(float value) {#setPixels-float-}
```
public void setPixels(float value)
```


पिक्सेल में आकार मान सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### setPoint(float value) {#setPoint-float-}
```
public void setPoint(float value)
```


Sets size value in point.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### toString() {#toString--}
```
public String toString()
```


Returns a human-readable string representation of this  Unit .

**Returns:**
java.lang.String - A string that represents this  Unit .
### updateResolution(float dpi) {#updateResolution-float-}
```
public void updateResolution(float dpi)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| dpi | float |  |

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

