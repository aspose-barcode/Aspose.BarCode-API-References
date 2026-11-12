---
title: "Quadrangle"
linktitle: "Quadrangle"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "एक क्वाड्रैंगल क्षेत्र का प्रतिनिधित्व करने वाले चार पॉइंट्स का सेट संग्रहीत करता है"
type: docs
weight: 850
url: /hi/nodejs/aspose.barcode/quadrangle/
---

## Quadrangle class

एक क्वाड्रैंगल क्षेत्र का प्रतिनिधित्व करने वाले चार पॉइंट्स का सेट संग्रहीत करता है

```js
new Quadrangle(leftTop, rightTop, rightBottom, leftBottom)
```

वर्णनात्मक बिंदुओं के साथ Quadrangle संरचना का नया इंस्टेंस इनिशियलाइज़ करता है।

| पैरामीटर | विवरण |
| --- | --- |
| leftTop | एक Point जो Quadrangle के बाएँ-ऊपरी कोने का प्रतिनिधित्व करता है। |
| rightTop | एक Point जो Quadrangle के दाएँ-ऊपरी कोने का प्रतिनिधित्व करता है। |
| rightBottom | एक Point जो Quadrangle के दाएँ-निचले कोने का प्रतिनिधित्व करता है। |
| leftBottom | एक Point जो Quadrangle के बाएँ-निचले कोने का प्रतिनिधित्व करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [contains(pt)](#contains) | निर्धारित करता है कि निर्दिष्ट Point इस Quadrangle संरचना के भीतर सम्मिलित है या नहीं। |
| [containsPoint(x, y)](#containspoint) | निर्धारित करता है कि निर्दिष्ट point इस Quadrangle संरचना के भीतर सम्मिलित है या नहीं। |
| [containsQuadrangle(quad)](#containsquadrangle) | निर्धारित करता है कि निर्दिष्ट Quadrangle इस Quadrangle संरचना में सम्मिलित है या इसका प्रतिच्छेदन करता है। |
| [containsRectangle(rect)](#containsrectangle) | निर्धारित करता है कि निर्दिष्ट Rectangle इस Quadrangle संरचना में सम्मिलित है या इसका प्रतिच्छेदन करता है। |
| [equals(other)](#equals) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट Quadrangle मान के बराबर है या नहीं। |
| [getBoundingRectangle()](#getboundingrectangle) | इस Quadrangle को बाउंड करने वाला Rectangle बनाता है |
| [getLeftBottom()](#getleftbottom) | Quadrangle क्षेत्र का बाएँ-निचला कोना Point प्राप्त करता हैValue: Quadrangle क्षेत्र का बाएँ-निचला कोना Point |
| [getLeftTop()](#getlefttop) | Quadrangle क्षेत्र का बाएँ-ऊपरी कोना Point प्राप्त करता हैValue: Quadrangle क्षेत्र का बाएँ-ऊपरी कोना Point |
| [getRightBottom()](#getrightbottom) | Quadrangle क्षेत्र का दाएँ-निचला कोना Point प्राप्त करता हैValue: Quadrangle क्षेत्र का दाएँ-निचला कोना Point |
| [getRightTop()](#getrighttop) | Quadrangle क्षेत्र का दाएँ-ऊपरी कोना Point प्राप्त करता हैValue: Quadrangle क्षेत्र का दाएँ-ऊपरी कोना Point |
| [hashCode()](#hashcode) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isEmpty()](#isempty) | जाँचता है कि इस Quadrangle के सभी Points के मान शून्य हैं। मान: यदि इस Quadrangle के सभी Points के मान शून्य हैं तो true लौटाता है |
| [setLeftBottom()](#setleftbottom) | Quadrangle क्षेत्र के बाएँ-नीचे कोने का Point सेट करता है। मान: Quadrangle क्षेत्र का बाएँ-नीचे कोने का Point |
| [setLeftTop()](#setlefttop) | Quadrangle क्षेत्र के बाएँ-ऊपर कोने का Point सेट करता है। मान: Quadrangle क्षेत्र का बाएँ-ऊपर कोने का Point |
| [setRightBottom()](#setrightbottom) | Quadrangle क्षेत्र के दाएँ-नीचे कोने का Point सेट करता है। मान: Quadrangle क्षेत्र का दाएँ-नीचे कोने का Point |
| [setRightTop()](#setrighttop) | Quadrangle क्षेत्र के दाएँ-ऊपर कोने का Point सेट करता है। मान: Quadrangle क्षेत्र का दाएँ-ऊपर कोने का Point |
| [toString()](#tostring) | इस Quadrangle का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है। |

### contains(pt) {#contains}

निर्धारित करता है कि निर्दिष्ट Point इस Quadrangle संरचना के भीतर सम्मिलित है या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| pt | परीक्षण के लिए Point। |

**Returns:** true if Point is contained within this Quadrangle structure; otherwise, false.

### containsPoint(x, y) {#containspoint}

निर्धारित करता है कि निर्दिष्ट point इस Quadrangle संरचना के भीतर सम्मिलित है या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| x | x बिंदु का निर्देशांक। |
| y | y बिंदु का निर्देशांक। |

**Returns:** Returns true if point is contained within this Quadrangle structure; otherwise, false.

### containsQuadrangle(quad) {#containsquadrangle}

निर्धारित करता है कि निर्दिष्ट Quadrangle इस Quadrangle संरचना में सम्मिलित है या इसका प्रतिच्छेदन करता है।

| पैरामीटर | विवरण |
| --- | --- |
| quad | परीक्षण के लिए Quadrangle। |

**Returns:** Returns true if Quadrangle is contained or intersect this Quadrangle structure; otherwise, false.

### containsRectangle(rect) {#containsrectangle}

निर्धारित करता है कि निर्दिष्ट Rectangle इस Quadrangle संरचना में सम्मिलित है या इसका प्रतिच्छेदन करता है।

| पैरामीटर | विवरण |
| --- | --- |
| rect | परीक्षण के लिए Rectangle। |

**Returns:** Returns true if Rectangle is contained or intersect this Quadrangle structure; otherwise, false.

### equals(other) {#equals}

एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट Quadrangle मान के बराबर है या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| अन्य | इस उदाहरण से तुलना करने के लिए एक Quadrangle मान। |

**Returns:** true if obj has the same value as this instance; otherwise, false.

### getBoundingRectangle() {#getboundingrectangle}

इस Quadrangle को बाउंड करने वाला Rectangle बनाता है

**Returns:** returns Rectangle bounding this Quadrangle

### getLeftBottom() {#getleftbottom}

Quadrangle क्षेत्र का बाएँ-निचला कोना Point प्राप्त करता हैValue: Quadrangle क्षेत्र का बाएँ-निचला कोना Point

### getLeftTop() {#getlefttop}

Quadrangle क्षेत्र का बाएँ-ऊपरी कोना Point प्राप्त करता हैValue: Quadrangle क्षेत्र का बाएँ-ऊपरी कोना Point

### getRightBottom() {#getrightbottom}

Quadrangle क्षेत्र का दाएँ-निचला कोना Point प्राप्त करता हैValue: Quadrangle क्षेत्र का दाएँ-निचला कोना Point

### getRightTop() {#getrighttop}

Quadrangle क्षेत्र का दाएँ-ऊपरी कोना Point प्राप्त करता हैValue: Quadrangle क्षेत्र का दाएँ-ऊपरी कोना Point

### hashCode() {#hashcode}

इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:** A 32-bit signed integer hash code.

### isEmpty() {#isempty}

जाँचता है कि इस Quadrangle के सभी Points के मान शून्य हैं। मान: यदि इस Quadrangle के सभी Points के मान शून्य हैं तो true लौटाता है; अन्यथा false।

### setLeftBottom() {#setleftbottom}

Quadrangle क्षेत्र के बाएँ-नीचे कोने का Point सेट करता है। मान: Quadrangle क्षेत्र का बाएँ-नीचे कोने का Point

### setLeftTop() {#setlefttop}

Quadrangle क्षेत्र के बाएँ-ऊपर कोने का Point सेट करता है। मान: Quadrangle क्षेत्र का बाएँ-ऊपर कोने का Point

### setRightBottom() {#setrightbottom}

Quadrangle क्षेत्र के दाएँ-नीचे कोने का Point सेट करता है। मान: Quadrangle क्षेत्र का दाएँ-नीचे कोने का Point

### setRightTop() {#setrighttop}

Quadrangle क्षेत्र के दाएँ-ऊपर कोने का Point सेट करता है। मान: Quadrangle क्षेत्र का दाएँ-ऊपर कोने का Point

### toString() {#tostring}

इस Quadrangle का मानव-पठनीय स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Returns:** A string that represents this Quadrangle.
