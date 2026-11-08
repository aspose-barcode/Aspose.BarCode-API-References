---
title: "Quadrangle"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "चार पॉइंट्स का सेट संग्रहीत करता है जो एक Quadrangle क्षेत्र का प्रतिनिधित्व करते हैं।"
type: docs
weight: 39
url: /hi/java/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

चार बिंदुओं का एक सेट संग्रहीत करता है जो एक Quadrangle क्षेत्र का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-) | वर्णनात्मक पॉइंट्स के साथ Quadrangle क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [EMPTY](#EMPTY) | Quadrangle क्लास को उसके प्रॉपर्टीज़ अनइनिशियलाइज़्ड छोड़कर दर्शाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | निर्धारित करता है कि निर्दिष्ट Quadrangle इस Quadrangle क्लास में सम्मिलित है या इसका प्रतिच्छेद करता है। |
| [contains(int x, int y)](#contains-int-int-) | निर्धारित करता है कि निर्दिष्ट बिंदु इस Quadrangle क्लास के भीतर सम्मिलित है या नहीं। |
| [contains(Point pt)](#contains-java.awt.Point-) | निर्धारित करता है कि निर्दिष्ट Point इस Quadrangle क्लास के भीतर सम्मिलित है या नहीं। |
| [contains(Rectangle rect)](#contains-java.awt.Rectangle-) | निर्धारित करता है कि निर्दिष्ट Rectangle इस Quadrangle क्लास में सम्मिलित है या इसका प्रतिच्छेद करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट Quadrangle मान के बराबर है या नहीं। |
| [getBoundingRectangle()](#getBoundingRectangle--) | इस Quadrangle को बाउंड करने वाला Rectangle बनाता है |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Quadrangle क्षेत्र का बायें-नीचे कोना Point प्राप्त करता है |
| [getLeftTop()](#getLeftTop--) | Quadrangle क्षेत्र का बायें-ऊपर कोना Point प्राप्त करता है |
| [getRightBottom()](#getRightBottom--) | Quadrangle क्षेत्र का दायें-नीचे कोना Point प्राप्त करता है |
| [getRightTop()](#getRightTop--) | Quadrangle क्षेत्र का दायें-ऊपर कोना Point प्राप्त करता है |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [isEmpty()](#isEmpty--) | परीक्षण करता है कि इस Quadrangle के सभी Point शून्य मान रखते हैं या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-java.awt.Point-) | Quadrangle क्षेत्र का बायें-नीचे कोना Point प्राप्त करता है |
| [setLeftTop(Point value)](#setLeftTop-java.awt.Point-) | Quadrangle क्षेत्र का बायें-ऊपर कोना Point प्राप्त करता है |
| [setRightBottom(Point value)](#setRightBottom-java.awt.Point-) | Quadrangle क्षेत्र का दायें-नीचे कोना Point प्राप्त करता है |
| [setRightTop(Point value)](#setRightTop-java.awt.Point-) | Quadrangle क्षेत्र का दायें-ऊपर कोना Point प्राप्त करता है |
| [toString()](#toString--) | इस  Quadrangle  की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-java.awt.Point-java.awt.Point-java.awt.Point-java.awt.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


वर्णनात्मक पॉइंट्स के साथ Quadrangle क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| leftTop | java.awt.Point | एक  Point  जो Quadrangle के बाएँ-ऊपरी कोने का प्रतिनिधित्व करता है। |
| rightTop | java.awt.Point | एक  Point  जो Quadrangle के दाएँ-ऊपरी कोने का प्रतिनिधित्व करता है। |
| rightBottom | java.awt.Point | एक  Point  जो Quadrangle के दाएँ-निचले कोने का प्रतिनिधित्व करता है। |
| leftBottom | java.awt.Point | एक  Point  जो Quadrangle के बाएँ-निचले कोने का प्रतिनिधित्व करता है। |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


Quadrangle क्लास को उसके प्रॉपर्टीज़ अनइनिशियलाइज़्ड छोड़कर दर्शाता है।

मान:  Quadrangle

### clone() {#clone--}
```
public Quadrangle clone()
```




**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


निर्धारित करता है कि निर्दिष्ट Quadrangle इस Quadrangle क्लास में सम्मिलित है या इसका प्रतिच्छेद करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | परीक्षण के लिए  Quadrangle। |

**Returns:**
boolean - लौटाता है  **true**  यदि  Quadrangle  इस  Quadrangle  वर्ग में सम्मिलित या प्रतिच्छेदित है; अन्यथा,  **false** .
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


निर्धारित करता है कि निर्दिष्ट बिंदु इस Quadrangle क्लास के भीतर सम्मिलित है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| x | int | x बिंदु का निर्देशांक। |
| y | int | y बिंदु का निर्देशांक। |

**Returns:**
boolean - लौटाता है  **true**  यदि point इस  Quadrangle  वर्ग में सम्मिलित है; अन्यथा,  **false** .
### contains(Point pt) {#contains-java.awt.Point-}
```
public boolean contains(Point pt)
```


निर्धारित करता है कि निर्दिष्ट Point इस Quadrangle क्लास के भीतर सम्मिलित है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | java.awt.Point | परीक्षण के लिए  Point। |

**Returns:**
boolean - लौटाता है  **true**  यदि  Point  इस  Quadrangle  वर्ग में सम्मिलित है; अन्यथा,  **false** .
### contains(Rectangle rect) {#contains-java.awt.Rectangle-}
```
public boolean contains(Rectangle rect)
```


निर्धारित करता है कि निर्दिष्ट Rectangle इस Quadrangle क्लास में सम्मिलित है या इसका प्रतिच्छेद करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | java.awt.Rectangle | परीक्षण के लिए  Rectangle। |

**Returns:**
boolean - लौटाता है  **true**  यदि  Rectangle  इस  Quadrangle  वर्ग में सम्मिलित या प्रतिच्छेदित है; अन्यथा,  **false** .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट Quadrangle मान के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | एक  Quadrangle  मान इस उदाहरण से तुलना करने के लिए। |

**Returns:**
boolean -  **true**  यदि obj का मान इस इंस्टेंस के समान है; अन्यथा,  **false** ।
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


इस Quadrangle को बाउंड करने वाला Rectangle बनाता है

**Returns:**
java.awt.Rectangle - इस Quadrangle को घेरने वाला Rectangle लौटाता है
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLeftBottom() {#getLeftBottom--}
```
public Point getLeftBottom()
```


Quadrangle क्षेत्र का बायें-नीचे कोना Point प्राप्त करता है

मान: Quadrangle क्षेत्र का बायाँ-निचला कोना Point

**Returns:**
java.awt.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Quadrangle क्षेत्र का बायें-ऊपर कोना Point प्राप्त करता है

मान: Quadrangle क्षेत्र का बायाँ-ऊपरी कोना Point

**Returns:**
java.awt.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Quadrangle क्षेत्र का दायें-नीचे कोना Point प्राप्त करता है

मान: Quadrangle क्षेत्र का दायाँ-निचला कोना Point

**Returns:**
java.awt.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Quadrangle क्षेत्र का दायें-ऊपर कोना Point प्राप्त करता है

मान: Quadrangle क्षेत्र का दायाँ-ऊपरी कोना Point

**Returns:**
java.awt.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस इंस्टेंस के लिए हैश कोड लौटाता है।

**Returns:**
int - 32-बिट साइन्ड इंटीजर हैश कोड।
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


परीक्षण करता है कि इस Quadrangle के सभी Point शून्य मान रखते हैं या नहीं।

मान: यदि इस Quadrangle के सभी Point शून्य मान रखते हैं तो **true** लौटाता है; अन्यथा, **false**।

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setLeftBottom(Point value) {#setLeftBottom-java.awt.Point-}
```
public void setLeftBottom(Point value)
```


Quadrangle क्षेत्र का बायें-नीचे कोना Point प्राप्त करता है

मान: Quadrangle क्षेत्र का बायाँ-निचला कोना Point

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.awt.Point |  |

### setLeftTop(Point value) {#setLeftTop-java.awt.Point-}
```
public void setLeftTop(Point value)
```


Quadrangle क्षेत्र का बायें-ऊपर कोना Point प्राप्त करता है

मान: Quadrangle क्षेत्र का बायाँ-ऊपरी कोना Point

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.awt.Point |  |

### setRightBottom(Point value) {#setRightBottom-java.awt.Point-}
```
public void setRightBottom(Point value)
```


Quadrangle क्षेत्र का दायें-नीचे कोना Point प्राप्त करता है

मान: Quadrangle क्षेत्र का दायाँ-निचला कोना Point

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.awt.Point |  |

### setRightTop(Point value) {#setRightTop-java.awt.Point-}
```
public void setRightTop(Point value)
```


Quadrangle क्षेत्र का दायें-ऊपर कोना Point प्राप्त करता है

मान: Quadrangle क्षेत्र का दायाँ-ऊपरी कोना Point

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.awt.Point |  |

### toString() {#toString--}
```
public String toString()
```


इस  Quadrangle  की मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस Quadrangle को दर्शाती है।
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

