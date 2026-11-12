---
title: "QualitySettings"
linktitle: "QualitySettings"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "QualitySettings मान्यता गुणवत्ता और गति को मैन्युअल रूप से कॉन्फ़िगर करने की अनुमति देता है।"
type: docs
weight: 860
url: /hi/nodejs/aspose.barcode/qualitysettings/
---

## QualitySettings class

QualitySettings मान्यता गुणवत्ता और गति को मैन्युअल रूप से कॉन्फ़िगर करने की अनुमति देता है। आप एम्बेडेड प्रीसेट्स: HighPerformance, NormalQuality, HighQuality, MaxBarCodes का उपयोग करके जल्दी से QualitySettings सेट कर सकते हैं या आप अलग-अलग विकल्पों को मैन्युअल रूप से कॉन्फ़िगर कर सकते हैं। QualitySettings का डिफ़ॉल्ट मान NormalQuality है।

```js
new QualitySettings()
```

**Example:**

```js
//This sample shows how to use QualitySettings with BarCodeReader
let reader = new BarCodeReader("test.png", null,  [ DecodeType.CODE_39, DecodeType.CODE_128 ]);
//set high performance mode
reader.setQualitySettings(QualitySettings.getHighPerformance());
let results = reader.readBarCodes();
for(let i = 0; i < results.length; i++)
{
   let result = results[i];
   console.log("BarCode CodeText: " + result.getCodeText());
}
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getHighPerformance()](#gethighperformance) *(static)* | HighPerformance मान्यता गुणवत्ता प्रीसेट। इस मोड में उच्च गुणवत्ता वाले बारकोड अच्छी तरह से पहचाने जाते हैं। |
| [getHighQuality()](#gethighquality) *(static)* | HighQuality मान्यता गुणवत्ता प्रीसेट। यह प्रीसेट कम गुणवत्ता वाले बारकोड के लिए विकसित किया गया है। |
| [getMaxQuality()](#getmaxquality) *(static)* | MaxQuality मान्यता गुणवत्ता प्रीसेट। यह प्रीसेट सभी संभावित बारकोड, यहाँ तक कि गलत बारकोड को भी पहचानने के लिए विकसित किया गया है। |
| [getNormalQuality()](#getnormalquality) *(static)* | NormalQuality मान्यता गुणवत्ता प्रीसेट। अधिकांश बारकोड के लिए उपयुक्त। |
| [getAllowIncorrectBarcodes()](#getallowincorrectbarcodes) | इंजन को उन बारकोड को पहचानने की अनुमति देता है जिनका चेकसम या मान गलत है। इस मोड का उपयोग दोषपूर्ण बारकोड को पहचानने के लिए किया जा सकता है। |
| [getBarcodeQuality()](#getbarcodequality) | ऐसा मोड जो चयनित क्वालिटी के साथ बारकोड एलिमेंट्स को पहचानने की मेथड्स को सक्षम करता है। कम क्वालिटी वाले बारकोड एलिमेंट r |
| [getComplexBackground()](#getcomplexbackground) | रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करने वाला मोड। |
| [getDeconvolution()](#getdeconvolution) | डिकन्वॉल्यूशन (छवि पुनर्स्थापना) मोड जो छवि क्षरण के स्तर को परिभाषित करता है। मूल रूप से डिकन्वॉल्यूशन एक फ़ंक्शन है |
| [getInverseImage()](#getinverseimage) | वह मोड जो उल्टे रंगों (ल्यूमिनेंस) वाली छवियों पर बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है। |
| [getMinimalXDimension()](#getminimalxdimension) | UseMinimalXDimension के साथ उपयोग की जाने वाली XDimension का न्यूनतम आकार पिक्सेल में। |
| [getXDimension()](#getxdimension) | पहचान मोड जो बारकोड के न्यूनतम तत्व (मैट्रिक्स सेल या बार) का आकार (1 से अनंत तक) निर्धारित करता है। |
| [setAllowIncorrectBarcodes(value)](#setallowincorrectbarcodes) | इंजन को उन बारकोड को पहचानने की अनुमति देता है जिनका चेकसम या मान गलत है। इस मोड का उपयोग दोषपूर्ण बारकोड को पहचानने के लिए किया जा सकता है। |
| [setBarcodeQuality(value)](#setbarcodequality) | ऐसा मोड जो चयनित क्वालिटी के साथ बारकोड एलिमेंट्स को पहचानने की मेथड्स को सक्षम करता है। कम क्वालिटी वाले बारकोड एलिमेंट r |
| [setComplexBackground(value)](#setcomplexbackground) | रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करने वाला मोड। |
| [setDeconvolution(value)](#setdeconvolution) | डिकन्वॉल्यूशन (छवि पुनर्स्थापना) मोड जो छवि क्षरण के स्तर को परिभाषित करता है। मूल रूप से डिकन्वॉल्यूशन एक फ़ंक्शन है |
| [setInverseImage(value)](#setinverseimage) | वह मोड जो उल्टे रंगों (ल्यूमिनेंस) वाली छवियों पर बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है। |
| [setMinimalXDimension(value)](#setminimalxdimension) | UseMinimalXDimension के साथ उपयोग की जाने वाली XDimension का न्यूनतम आकार पिक्सेल में। |
| [setXDimension(value)](#setxdimension) | पहचान मोड जो बारकोड के न्यूनतम तत्व (मैट्रिक्स सेल या बार) का आकार (1 से अनंत तक) निर्धारित करता है। |

### getHighPerformance() (static) {#gethighperformance}

HighPerformance मान्यता गुणवत्ता प्रीसेट। इस मोड में उच्च गुणवत्ता वाले बारकोड अच्छी तरह से पहचाने जाते हैं।

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighPerformance());
```

### getHighQuality() (static) {#gethighquality}

HighQuality मान्यता गुणवत्ता प्रीसेट। यह प्रीसेट कम गुणवत्ता वाले बारकोड के लिए विकसित किया गया है।

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getHighQuality());
```

### getMaxQuality() (static) {#getmaxquality}

MaxQuality पहचान गुणवत्ता प्रीसेट। यह प्रीसेट सभी संभावित बारकोड, यहाँ तक कि गलत बारकोड को पहचानने के लिए विकसित किया गया है। यह उदाहरण दिखाता है कि MaxQuality मोड का उपयोग कैसे करें reader = new BarCodeReader("test.png"null, null, DecodeType.CODE_39_FULL_ASCII, DecodeType.CODE_128); { reader.setQualitySettings(QualitySettings.getMaxQuality()); for(let i = 0; i < reader.readBarCodes().length; i++) echo (reader.getFoundBarcodes()[i].getCodeText()); } मान: MaxQuality पहचान गुणवत्ता प्रीसेट।

### getNormalQuality() (static) {#getnormalquality}

NormalQuality मान्यता गुणवत्ता प्रीसेट। अधिकांश बारकोड के लिए उपयुक्त।

**Example:**

```js
let reader = new BarCodeReader("test.png");
reader.setQualitySettings(QualitySettings.getNormalQuality());
```

### getAllowIncorrectBarcodes() {#getallowincorrectbarcodes}

इंजन को उन बारकोड को पहचानने की अनुमति देता है जिनका चेकसम या मान गलत है। यह मोड गलत टेक्स्ट वाले क्षतिग्रस्त बारकोड को पहचानने के लिए उपयोग किया जा सकता है।

**Returns:** Allows engine to recognize incorrect barcodes.

### getBarcodeQuality() {#getbarcodequality}

वह मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने की विधियों को सक्षम करता है। कम गुणवत्ता वाले बारकोड तत्व को अधिक जटिल विधियों की आवश्यकता होती है, जिससे पहचान धीमी हो जाती है।

**Returns:** Mode which enables methods to recognize barcode elements with the selected quality.

### getComplexBackground() {#getcomplexbackground}

रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करने वाला मोड।

**Returns:** Additional recognition of color barcodes on color images.

### getDeconvolution() {#getdeconvolution}

Deconvolution (छवि पुनर्स्थापन) मोड जो छवि क्षीणन के स्तर को निर्धारित करता है। मूल रूप से Deconvolution एक फ़ंक्शन है जो कैमरे द्वारा छवि प्राप्त करने के दौरान ब्लर जैसी किसी भी प्राकृतिक फ़ंक्शन द्वारा क्षीणित (कन्वॉल्यूटेड) छवि को पुनर्स्थापित कर सकता है। क्योंकि हम उस छवि फ़ंक्शन का पता नहीं लगा सकते जो छवि को भ्रष्ट करता है, हमें सबसे ज्ञात फ़ंक्शन जैसे sharp या गणितीय रूपविज्ञान की जाँच करनी पड़ती है।

**Returns:** Deconvolution mode which defines level of image degradation.

### getInverseImage() {#getinverseimage}

वह मोड जो उल्टे रंगों (ल्यूमिनेंस) वाली छवियों पर बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है।

**Returns:** Additional recognition of barcodes on images with inverse colors

### getMinimalXDimension() {#getminimalxdimension}

UseMinimalXDimension के साथ उपयोग की जाने वाली XDimension का न्यूनतम आकार पिक्सेल में।

**Returns:** Minimal size of XDimension in pixels which is used with UseMinimalXDimension.

### getXDimension() {#getxdimension}

पहचान मोड जो बारकोड के न्यूनतम तत्व (मैट्रिक्स सेल या बार) का आकार (1 से अनंत तक) निर्धारित करता है।

**Returns:** size (from 1 to infinity) of barcode minimal element: matrix cell or bar.

### setAllowIncorrectBarcodes(value) {#setallowincorrectbarcodes}

इंजन को उन बारकोड को पहचानने की अनुमति देता है जिनका चेकसम या मान गलत है। यह मोड गलत टेक्स्ट वाले क्षतिग्रस्त बारकोड को पहचानने के लिए उपयोग किया जा सकता है।

| पैरामीटर | विवरण |
| --- | --- |
| मान | इंजन को गलत बारकोड पहचानने की अनुमति देता है। |

### setBarcodeQuality(value) {#setbarcodequality}

वह मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने की विधियों को सक्षम करता है। कम गुणवत्ता वाले बारकोड तत्व को अधिक जटिल विधियों की आवश्यकता होती है, जिससे पहचान धीमी हो जाती है।

| पैरामीटर | विवरण |
| --- | --- |
| मान | वह मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने की विधियों को सक्षम करता है। |

### setComplexBackground(value) {#setcomplexbackground}

रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करने वाला मोड।

| पैरामीटर | विवरण |
| --- | --- |
| मान | रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान। |

### setDeconvolution(value) {#setdeconvolution}

Deconvolution (छवि पुनर्स्थापन) मोड जो छवि क्षीणन के स्तर को निर्धारित करता है। मूल रूप से Deconvolution एक फ़ंक्शन है जो कैमरे द्वारा छवि प्राप्त करने के दौरान ब्लर जैसी किसी भी प्राकृतिक फ़ंक्शन द्वारा क्षीणित (कन्वॉल्यूटेड) छवि को पुनर्स्थापित कर सकता है। क्योंकि हम उस छवि फ़ंक्शन का पता नहीं लगा सकते जो छवि को भ्रष्ट करता है, हमें सबसे ज्ञात फ़ंक्शन जैसे sharp या गणितीय रूपविज्ञान की जाँच करनी पड़ती है।

| पैरामीटर | विवरण |
| --- | --- |
| मान | Deconvolution मोड जो छवि क्षीणन के स्तर को निर्धारित करता है। |

### setInverseImage(value) {#setinverseimage}

वह मोड जो उल्टे रंगों (ल्यूमिनेंस) वाली छवियों पर बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है।

| पैरामीटर | विवरण |
| --- | --- |
| मान | उल्टे रंगों वाली छवियों पर बारकोड की अतिरिक्त पहचान |

### setMinimalXDimension(value) {#setminimalxdimension}

UseMinimalXDimension के साथ उपयोग की जाने वाली XDimension का न्यूनतम आकार पिक्सेल में।

| पैरामीटर | विवरण |
| --- | --- |
| मान | UseMinimalXDimension के साथ उपयोग की जाने वाली XDimension का न्यूनतम आकार पिक्सेल में। |

### setXDimension(value) {#setxdimension}

पहचान मोड जो बारकोड के न्यूनतम तत्व (मैट्रिक्स सेल या बार) का आकार (1 से अनंत तक) निर्धारित करता है।

| पैरामीटर | विवरण |
| --- | --- |
| मान | (1 से अनंत तक) बारकोड के न्यूनतम तत्व: मैट्रिक्स सेल या बार। |
