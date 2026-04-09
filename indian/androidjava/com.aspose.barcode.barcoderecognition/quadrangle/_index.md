---
title: Quadrangle
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: चार पॉइंट्स का सेट संग्रहीत करता है जो एक Quadrangle क्षेत्र का प्रतिनिधित्व करते हैं।
type: docs
weight: 43
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/quadrangle/
---
**Inheritance:**
java.lang.Object
```
public class Quadrangle
```

Stores a set of four  Point s that represent a  Quadrangle  region.
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Quadrangle()](#Quadrangle--) |  |
| [Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)](#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-) | वर्णनात्मक पॉइंट्स के साथ  Quadrangle  संरचना का नया उदाहरण प्रारंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [EMPTY](#EMPTY) | एक  Quadrangle  क्लास का प्रतिनिधित्व करता है जिसकी प्रॉपर्टीज़ अनइनिशियलाइज़्ड रहती हैं। |
## Methods

| Method | विवरण |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(Point pt)](#contains-android.graphics.Point-) | निर्धारित करता है कि निर्दिष्ट  Point  इस  Quadrangle  क्लास के भीतर शामिल है या नहीं। |
| [contains(Rect rect)](#contains-android.graphics.Rect-) | निर्धारित करता है कि निर्दिष्ट  Rectangle  इस  Quadrangle  क्लास में शामिल है या इससे प्रतिच्छेद करता है। |
| [contains(Quadrangle quad)](#contains-com.aspose.barcode.barcoderecognition.Quadrangle-) | निर्धारित करता है कि निर्दिष्ट  Quadrangle  इस  Quadrangle  क्लास में शामिल है या इससे प्रतिच्छेद करता है। |
| [contains(int x, int y)](#contains-int-int-) | निर्धारित करता है कि निर्दिष्ट पॉइंट इस  Quadrangle  क्लास के भीतर शामिल है या नहीं। |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट  Quadrangle  मान के बराबर है या नहीं। |
| [getBoundingRectangle()](#getBoundingRectangle--) | इस  Quadrangle  को सीमित करने वाला  Rectangle  बनाता है |
| [getClass()](#getClass--) |  |
| [getLeftBottom()](#getLeftBottom--) | Quadrangle  क्षेत्र के बाएँ-नीचे कोने का  Point  प्राप्त करता है |
| [getLeftTop()](#getLeftTop--) | Quadrangle क्षेत्र के बाएँ‑ऊपरी कोने का Point प्राप्त करता है |
| [getRightBottom()](#getRightBottom--) | Quadrangle क्षेत्र के दाएँ‑नीचे कोने का Point प्राप्त करता है |
| [getRightTop()](#getRightTop--) | Quadrangle क्षेत्र के दाएँ‑ऊपरी कोने का Point प्राप्त करता है |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isEmpty()](#isEmpty--) | जाँचता है कि इस Quadrangle के सभी Point शून्य मान रखते हैं या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLeftBottom(Point value)](#setLeftBottom-android.graphics.Point-) | Quadrangle  क्षेत्र के बाएँ-नीचे कोने का  Point  प्राप्त करता है |
| [setLeftTop(Point value)](#setLeftTop-android.graphics.Point-) | Quadrangle क्षेत्र के बाएँ‑ऊपरी कोने का Point प्राप्त करता है |
| [setRightBottom(Point value)](#setRightBottom-android.graphics.Point-) | Quadrangle क्षेत्र के दाएँ‑नीचे कोने का Point प्राप्त करता है |
| [setRightTop(Point value)](#setRightTop-android.graphics.Point-) | Quadrangle क्षेत्र के दाएँ‑ऊपरी कोने का Point प्राप्त करता है |
| [toString()](#toString--) | इस Quadrangle का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quadrangle() {#Quadrangle--}
```
public Quadrangle()
```


### Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom) {#Quadrangle-android.graphics.Point-android.graphics.Point-android.graphics.Point-android.graphics.Point-}
```
public Quadrangle(Point leftTop, Point rightTop, Point rightBottom, Point leftBottom)
```


वर्णनात्मक पॉइंट्स के साथ  Quadrangle  संरचना का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| leftTop | android.graphics.Point | एक Point जो Quadrangle के बाएँ‑ऊपरी कोने का प्रतिनिधित्व करता है। |
| rightTop | android.graphics.Point | एक Point जो Quadrangle के दाएँ‑ऊपरी कोने का प्रतिनिधित्व करता है। |
| rightBottom | android.graphics.Point | एक Point जो Quadrangle के दाएँ‑नीचे कोने का प्रतिनिधित्व करता है। |
| leftBottom | android.graphics.Point | एक Point जो Quadrangle के बाएँ‑नीचे कोने का प्रतिनिधित्व करता है। |

### EMPTY {#EMPTY}
```
public static final Quadrangle EMPTY
```


एक  Quadrangle  क्लास का प्रतिनिधित्व करता है जिसकी प्रॉपर्टीज़ अनइनिशियलाइज़्ड रहती हैं।

मान:  Quadrangle

### clone() {#clone--}
```
public Quadrangle clone()
```




**Returns:**
[Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle)
### contains(Point pt) {#contains-android.graphics.Point-}
```
public boolean contains(Point pt)
```


निर्धारित करता है कि निर्दिष्ट  Point  इस  Quadrangle  क्लास के भीतर शामिल है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| pt | android.graphics.Point | परीक्षण के लिए Point। |

**Returns:**
boolean - यदि Point इस Quadrangle वर्ग में सम्मिलित है तो **true** लौटाता है; अन्यथा **false**।
### contains(Rect rect) {#contains-android.graphics.Rect-}
```
public boolean contains(Rect rect)
```


निर्धारित करता है कि निर्दिष्ट  Rectangle  इस  Quadrangle  क्लास में शामिल है या इससे प्रतिच्छेद करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| rect | android.graphics.Rect | परीक्षण के लिए Rectangle। |

**Returns:**
boolean - यदि Rectangle इस Quadrangle वर्ग में सम्मिलित या प्रतिच्छेदित है तो **true** लौटाता है; अन्यथा **false**।
### contains(Quadrangle quad) {#contains-com.aspose.barcode.barcoderecognition.Quadrangle-}
```
public boolean contains(Quadrangle quad)
```


निर्धारित करता है कि निर्दिष्ट  Quadrangle  इस  Quadrangle  क्लास में शामिल है या इससे प्रतिच्छेद करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| quad | [Quadrangle](../../com.aspose.barcode.barcoderecognition/quadrangle) | परीक्षण के लिए Quadrangle। |

**Returns:**
boolean - यदि Quadrangle इस Quadrangle वर्ग में सम्मिलित या प्रतिच्छेदित है तो **true** लौटाता है; अन्यथा **false**।
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


निर्धारित करता है कि निर्दिष्ट पॉइंट इस  Quadrangle  क्लास के भीतर शामिल है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| x | int | x बिंदु निर्देशांक। |
| y | int | y बिंदु निर्देशांक। |

**Returns:**
boolean - यदि बिंदु इस Quadrangle वर्ग में शामिल है तो **true** लौटाता है; अन्यथा, **false**।
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट  Quadrangle  मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस उदाहरण की तुलना करने के लिए एक Quadrangle मान। |

**Returns:**
boolean -  **true**  यदि obj का मान इस उदाहरण के समान है; अन्यथा,  **false** .
### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rect getBoundingRectangle()
```


इस  Quadrangle  को सीमित करने वाला  Rectangle  बनाता है

**Returns:**
android.graphics.Rect - इस Quadrangle को घेरने वाला Rectangle लौटाता है
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


Quadrangle  क्षेत्र के बाएँ-नीचे कोने का  Point  प्राप्त करता है

मान: Quadrangle क्षेत्र का बायाँ-निचला कोना Point

**Returns:**
android.graphics.Point
### getLeftTop() {#getLeftTop--}
```
public Point getLeftTop()
```


Quadrangle क्षेत्र के बाएँ‑ऊपरी कोने का Point प्राप्त करता है

मान: Quadrangle क्षेत्र का बायाँ-ऊपरी कोना Point

**Returns:**
android.graphics.Point
### getRightBottom() {#getRightBottom--}
```
public Point getRightBottom()
```


Quadrangle क्षेत्र के दाएँ‑नीचे कोने का Point प्राप्त करता है

मान: Quadrangle क्षेत्र का दायाँ-निचला कोना Point

**Returns:**
android.graphics.Point
### getRightTop() {#getRightTop--}
```
public Point getRightTop()
```


Quadrangle क्षेत्र के दाएँ‑ऊपरी कोने का Point प्राप्त करता है

मान: Quadrangle क्षेत्र का दायाँ-ऊपरी कोना Point

**Returns:**
android.graphics.Point
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:**
int - एक 32-बिट साइन्ड इंटेजर हैश कोड।
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


जाँचता है कि इस Quadrangle के सभी Point शून्य मान रखते हैं या नहीं।

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




### setLeftBottom(Point value) {#setLeftBottom-android.graphics.Point-}
```
public void setLeftBottom(Point value)
```


Quadrangle  क्षेत्र के बाएँ-नीचे कोने का  Point  प्राप्त करता है

मान: Quadrangle क्षेत्र का बायाँ-निचला कोना Point

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | android.graphics.Point |  |

### setLeftTop(Point value) {#setLeftTop-android.graphics.Point-}
```
public void setLeftTop(Point value)
```


Quadrangle क्षेत्र के बाएँ‑ऊपरी कोने का Point प्राप्त करता है

मान: Quadrangle क्षेत्र का बायाँ-ऊपरी कोना Point

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | android.graphics.Point |  |

### setRightBottom(Point value) {#setRightBottom-android.graphics.Point-}
```
public void setRightBottom(Point value)
```


Quadrangle क्षेत्र के दाएँ‑नीचे कोने का Point प्राप्त करता है

मान: Quadrangle क्षेत्र का दायाँ-निचला कोना Point

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | android.graphics.Point |  |

### setRightTop(Point value) {#setRightTop-android.graphics.Point-}
```
public void setRightTop(Point value)
```


Quadrangle क्षेत्र के दाएँ‑ऊपरी कोने का Point प्राप्त करता है

मान: Quadrangle क्षेत्र का दायाँ-ऊपरी कोना Point

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | android.graphics.Point |  |

### toString() {#toString--}
```
public String toString()
```


इस Quadrangle का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:**
java.lang.String - एक स्ट्रिंग जो इस Quadrangle को दर्शाती है।
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

