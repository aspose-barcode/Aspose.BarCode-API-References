---
title: "CMYKColor"
linktitle: "CMYKColor"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "CMYK रंग के लिए क्लास।"
type: docs
weight: 180
url: /hi/nodejs/aspose.barcode/cmykcolor/
---

## CMYKColor class

CMYK रंग के लिए क्लास। एक नल इंस्टेंस का मतलब है कि CMYK उपयोग नहीं किया गया है, और डिफ़ॉल्ट RGB रंग उपयोग में है।

```js
new CMYKColor(c, m, y, k)
```

CMYK मानों से CMYKColor क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। CMYK मान 0–100 की सीमा में अपेक्षित हैं।

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| c | संख्या | – सियान मान [0, 100] |
| m | संख्या | – मैजेंटा मान [0, 100] |
| y | संख्या | – येलो मान [0, 100] |
| k | संख्या | – ब्लैक मान [0, 100] |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [parseCMYK(str)](#parsecmyk) *(static)* | फ़ॉर्म "C_M_Y_K" वाली CMYK स्ट्रिंग को CMYKColor इंस्टेंस में पार्स करें। |
| [formatCMYK()](#formatcmyk) | इस CMYKColor को स्ट्रिंग "C_M_Y_K" में फ़ॉर्मेट करें, प्रत्येक आंतरिक घटक (0–1) को 100 से गुणा करके और राउंड करके। |
| [toString()](#tostring) | वैकल्पिक: एक मानव-पठनीय प्रतिनिधित्व। |

### parseCMYK(str) (static) {#parsecmyk}

फ़ॉर्म "C_M_Y_K" वाली CMYK स्ट्रिंग को CMYKColor इंस्टेंस में पार्स करें।

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | स्ट्रिंग | – "30_100_0_30" जैसी स्ट्रिंग |

**Returns:** CMYKColor

### formatCMYK() {#formatcmyk}

इस CMYKColor को स्ट्रिंग "C_M_Y_K" में फ़ॉर्मेट करें, प्रत्येक आंतरिक घटक (0–1) को 100 से गुणा करके और राउंड करके।

**Returns:** string — e.g. "30_100_0_30"

### toString() {#tostring}

वैकल्पिक: एक मानव-पठनीय प्रतिनिधित्व।
