---
title: "BarcodeParameters"
linktitle: "BarcodeParameters"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "बारकोड जनरेशन पैरामीटर।"
type: docs
weight: 140
url: /hi/nodejs/aspose.barcode/barcodeparameters/
---

## BarcodeParameters class

बारकोड जनरेशन पैरामीटर।

```js
new BarcodeParameters()
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getAustralianPost()](#getaustralianpost) | AustralianPost बारकोड पैरामीटर। |
| [getAztec()](#getaztec) | Aztec पैरामीटर। |
| [getBarColor()](#getbarcolor) | बार्स का रंग। |
| [getBarHeight()](#getbarheight) | 1D बारकोड्स की बार्स की ऊँचाई यूनिट मान में। यदि AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMo पर सेट है तो इसे नजरअंदाज़ किया जाता है। |
| [getBarWidthReduction()](#getbarwidthreduction) | बार्स की कमी मान प्राप्त करें जो प्रिंटिंग के दौरान इंक फैलाव की भरपाई के लिए उपयोग किया जाता है। |
| [getChecksumAlwaysShow()](#getchecksumalwaysshow) | Code128 और GS1Code128 बारकोड्स के लिए मानव-पठनीय टेक्स्ट में हमेशा चेकसम अंक प्रदर्शित करें। |
| [getCodabar()](#getcodabar) | कोडाबार पैरामीटर। |
| [getCodablock()](#getcodablock) | कोडाब्लॉक पैरामीटर। |
| [getCode16K()](#getcode16k) | Code16K पैरामीटर। |
| [getCode128()](#getcode128) | Code128 पैरामीटर। |
| [getCodeTextParameters()](#getcodetextparameters) | कोडटेक्स्ट पैरामीटर। |
| [getCoupon()](#getcoupon) | कूपन पैरामीटर। UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon के लिए उपयोग किया जाता है। |
| [getDataBar()](#getdatabar) | डेटाबार पैरामीटर। |
| [getDataMatrix()](#getdatamatrix) | DataMatrix पैरामीटर। |
| [getDotCode()](#getdotcode) | DotCode पैरामीटर। |
| [getEnableEscape()](#getenableescape) | बताता है कि CodeText प्रॉपर्टी में \"\\\" अक्षर को एस्केप कैरेक्टर के रूप में समझाया जाए या नहीं। Pdf417, DataMatrix, C के लिए उपयोग किया जाता है। |
| [getFilledBars()](#getfilledbars) | बार्स भरे हुए हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है। केवल 1D बारकोड्स के लिए। डिफ़ॉल्ट मान: true। |
| [getGS1CompositeBar()](#getgs1compositebar) | GS1 कॉम्पोजिट बार पैरामीटर। यह उदाहरण दिखाता है कि कैसे GS1 कॉम्पोजिट बार इमेज बनाएं और सहेजें। ध्यान दें कि 1D कोडटेक्स्ट |
| [getHanXin()](#gethanxin) | HanXin पैरामीटर। |
| [getITF()](#getitf) | ITF पैरामीटर। |
| [getMaxiCode()](#getmaxicode) | MaxiCode पैरामीटर। |
| [getPadding()](#getpadding) | बारकोड पैडिंग्स। डिफ़ॉल्ट मान: 5pt 5pt 5pt 5pt। |
| [getPatchCode()](#getpatchcode) | PatchCode पैरामीटर। |
| [getPdf417()](#getpdf417) | PDF417 पैरामीटर। |
| [getPostal()](#getpostal) | डाक पैरामीटर। Postnet, Planet के लिए उपयोग किया जाता है। |
| [getQR()](#getqr) | QR पैरामीटर। |
| [getSupplement()](#getsupplement) | सप्लीमेंट पैरामीटर। Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN के लिए उपयोग किया जाता है। |
| [getWideNarrowRatio()](#getwidenarrowratio) | वाइड बार्स से नैरॉ बार्स का अनुपात। डिफ़ॉल्ट मान: 3, अर्थात वाइड बार्स नैरॉ बार्स से 3 गुना चौड़े होते हैं। ITF के लिए उपयोग किया जाता है। |
| [getXDimension()](#getxdimension) | x-डायमेंशन बारकोड बार्स या स्पेसेस की इकाई की सबसे छोटी चौड़ाई है। इसे बढ़ाने से पूरी बारकोड की चौड़ाई बढ़ेगी। |
| [isChecksumEnabled()](#ischecksumenabled) | 1D बारकोड्स के निर्माण के दौरान चेकसम सक्षम करें। डिफ़ॉल्ट रूप से उन सिम्बोलॉजी के लिए Yes माना जाता है जिनमें चेकसम अनिवार्य है, जैसा कि N |
| [setBarColor(value)](#setbarcolor) | बार्स का रंग। |
| [setBarHeight()](#setbarheight) | 1D बारकोड्स की बार्स की ऊँचाई यूनिट मान में। यदि AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMo पर सेट है तो इसे नजरअंदाज़ किया जाता है। |
| [setBarWidthReduction()](#setbarwidthreduction) | प्रिंटिंग के दौरान इंक फैलाव की भरपाई के लिए उपयोग किया जाने वाला बार्स कमी मान सेट करता है। |
| [setChecksumAlwaysShow()](#setchecksumalwaysshow) | Code128 और GS1Code128 बारकोड्स के लिए मानव-पठनीय टेक्स्ट में हमेशा चेकसम अंक प्रदर्शित करें। |
| [setChecksumEnabled()](#setchecksumenabled) | 1D बारकोड्स के निर्माण के दौरान चेकसम सक्षम करें। डिफ़ॉल्ट रूप से उन सिम्बोलॉजी के लिए Yes माना जाता है जिनमें चेकसम अनिवार्य है, जैसा कि N |
| [setEnableEscape()](#setenableescape) | बताता है कि CodeText प्रॉपर्टी में \"\\\" अक्षर को एस्केप कैरेक्टर के रूप में समझाया जाए या नहीं। Pdf417, DataMatrix, C के लिए उपयोग किया जाता है। |
| [setFilledBars()](#setfilledbars) | बार्स भरे हुए हैं या नहीं, यह दर्शाने वाला मान सेट करता है। केवल 1D बारकोड्स के लिए। डिफ़ॉल्ट मान: true। |
| [setGS1CompositeBar()](#setgs1compositebar) | GS1 कॉम्पोजिट बार पैरामीटर। यह उदाहरण दिखाता है कि कैसे GS1 कॉम्पोजिट बार इमेज बनाएं और सहेजें। ध्यान दें कि 1D कोडटेक्स्ट |
| [setPadding()](#setpadding) | बारकोड पैडिंग्स। डिफ़ॉल्ट मान: 5pt 5pt 5pt 5pt। |
| [setWideNarrowRatio()](#setwidenarrowratio) | वाइड बार्स से नैरॉ बार्स का अनुपात। डिफ़ॉल्ट मान: 3, अर्थात वाइड बार्स नैरॉ बार्स से 3 गुना चौड़े होते हैं। ITF, P के लिए उपयोग किया जाता है। |
| [setXDimension()](#setxdimension) | x-डायमेंशन बारकोड बार्स या स्पेसेस की इकाई की सबसे छोटी चौड़ाई है। इसे बढ़ाने से पूरी बारकोड की चौड़ाई बढ़ेगी। |

### getAustralianPost() {#getaustralianpost}

AustralianPost बारकोड पैरामीटर।

### getAztec() {#getaztec}

Aztec पैरामीटर।

### getBarColor() {#getbarcolor}

बार्स का रंग।

**Returns:** value of Bar color Default value: #000000

### getBarHeight() {#getbarheight}

1D बारकोड्स की बार्स की ऊँचाई यूनिट मान में। यदि AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट है तो इसे नजरअंदाज़ किया जाता है।

**Throws:** BarcodeException

### getBarWidthReduction() {#getbarwidthreduction}

बार्स की कमी मान प्राप्त करें जो प्रिंटिंग के दौरान इंक फैलाव की भरपाई के लिए उपयोग किया जाता है।

**Returns:** Unit value of BarWidthReduction

### getChecksumAlwaysShow() {#getchecksumalwaysshow}

Code128 और GS1Code128 बारकोड्स के लिए मानव-पठनीय टेक्स्ट में हमेशा चेकसम अंक प्रदर्शित करें।

### getCodabar() {#getcodabar}

कोडाबार पैरामीटर।

### getCodablock() {#getcodablock}

कोडाब्लॉक पैरामीटर।

### getCode16K() {#getcode16k}

Code16K पैरामीटर।

### getCode128() {#getcode128}

Code128 पैरामीटर।

### getCodeTextParameters() {#getcodetextparameters}

कोडटेक्स्ट पैरामीटर।

### getCoupon() {#getcoupon}

कूपन पैरामीटर। UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon के लिए उपयोग किया जाता है।

### getDataBar() {#getdatabar}

डेटाबार पैरामीटर।

### getDataMatrix() {#getdatamatrix}

DataMatrix पैरामीटर।

### getDotCode() {#getdotcode}

DotCode पैरामीटर।

### getEnableEscape() {#getenableescape}

बताता है कि CodeText प्रॉपर्टी में \"\\\" अक्षर को एस्केप कैरेक्टर के रूप में समझाया जाए या नहीं। Pdf417, DataMatrix, Code128 के लिए उपयोग किया जाता है। यदि EnableEscape true है, तो \"\\\" को विशेष एस्केप कैरेक्टर माना जाएगा। अन्यथा, \"\\\" सामान्य अक्षर के रूप में कार्य करेगा। Aspose.BarCode दशमलव ASCII कोड और ASCII कंट्रोल-कोड अक्षरों के लिए मीनेमिक इनपुट का समर्थन करता है। उदाहरण के लिए, \\013 और \\\\CR CR के लिए होते हैं।

### getFilledBars() {#getfilledbars}

बार्स भरे हुए हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है। केवल 1D बारकोड्स के लिए। डिफ़ॉल्ट मान: true।

### getGS1CompositeBar() {#getgs1compositebar}

GS1 कॉम्पोजिट बार पैरामीटर। यह उदाहरण दिखाता है कि कैसे GS1 कॉम्पोजिट बार इमेज बनाएं और सहेजें। ध्यान दें कि 1D कोडटेक्स्ट और 2D कोडटेक्स्ट '/' प्रतीक द्वारा अलग किए जाते हैं।

**Returns:** GS1CompositeBarParameters GS1 Composite Bar parameters.

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);
///
// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);
///
generator.save("test.png", BarcodeImageFormat.PNG);
```

### getHanXin() {#gethanxin}

HanXin पैरामीटर।

### getITF() {#getitf}

ITF पैरामीटर।

### getMaxiCode() {#getmaxicode}

MaxiCode पैरामीटर।

### getPadding() {#getpadding}

बारकोड पैडिंग्स। डिफ़ॉल्ट मान: 5pt 5pt 5pt 5pt।

### getPatchCode() {#getpatchcode}

PatchCode पैरामीटर।

### getPdf417() {#getpdf417}

PDF417 पैरामीटर।

### getPostal() {#getpostal}

डाक पैरामीटर। Postnet, Planet के लिए उपयोग किया जाता है।

### getQR() {#getqr}

QR पैरामीटर।

### getSupplement() {#getsupplement}

सप्लीमेंट पैरामीटर। Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN के लिए उपयोग किया जाता है।

### getWideNarrowRatio() {#getwidenarrowratio}

वाइड बार्स से नैरॉ बार्स का अनुपात। डिफ़ॉल्ट मान: 3, अर्थात वाइड बार्स नैरॉ बार्स से 3 गुना चौड़े होते हैं। ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard के लिए उपयोग किया जाता है। WideNarrowRatio पैरामीटर मान 0 से कम या बराबर नहीं हो सकता।

### getXDimension() {#getxdimension}

x-डायमेंशन बारकोड बार्स या स्पेसेस की इकाई की सबसे छोटी चौड़ाई है। इसे बढ़ाने से पूरी बारकोड इमेज की चौड़ाई बढ़ेगी। यदि AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट है तो इसे नजरअंदाज़ किया जाता है।

### isChecksumEnabled() {#ischecksumenabled}

1D बारकोड उत्पन्न करते समय चेकसम सक्षम करें। डिफ़ॉल्ट रूप से उन सिंबोलॉजी के लिए हाँ माना जाता है जिनमें चेकसम अनिवार्य है, और जहाँ केवल चेकसम संभव है वहाँ नहीं। चेकसम संभव है: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar। चेकसम हमेशा उपयोग किया जाता है: शेष सिंबोलॉजी।

### setBarColor(value) {#setbarcolor}

बार्स का रंग।

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | String | बार रंग के लिए डिफ़ॉल्ट मान: #000000। |

### setBarHeight() {#setbarheight}

1D बारकोड्स की बार्स की ऊँचाई यूनिट मान में। यदि AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट है तो इसे नजरअंदाज़ किया जाता है।

**Throws:** BarcodeException

### setBarWidthReduction() {#setbarwidthreduction}

प्रिंटिंग के दौरान इंक फैलाव की भरपाई के लिए उपयोग किया जाने वाला बार्स कमी मान सेट करता है।

### setChecksumAlwaysShow() {#setchecksumalwaysshow}

Code128 और GS1Code128 बारकोड्स के लिए मानव-पठनीय टेक्स्ट में हमेशा चेकसम अंक प्रदर्शित करें।

### setChecksumEnabled() {#setchecksumenabled}

1D बारकोड उत्पन्न करते समय चेकसम सक्षम करें। डिफ़ॉल्ट रूप से उन सिंबोलॉजी के लिए हाँ माना जाता है जिनमें चेकसम अनिवार्य है, और जहाँ केवल चेकसम संभव है वहाँ नहीं। चेकसम संभव है: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar। चेकसम हमेशा उपयोग किया जाता है: शेष सिंबोलॉजी।

### setEnableEscape() {#setenableescape}

यह दर्शाता है कि CodeText प्रॉपर्टी में \"\\\" अक्षर को एस्केप कैरेक्टर के रूप में समझाया जाए या नहीं। केवल Pdf417, DataMatrix, Code128 के लिए उपयोग किया जाता है। यदि EnableEscape सत्य है, तो \"\\\" को एक विशेष एस्केप कैरेक्टर के रूप में समझाया जाएगा। अन्यथा, \"\\\" सामान्य अक्षर के रूप में कार्य करेगा। Aspose.BarCode दशमलव ASCII कोड और ASCII कंट्रोल-कोड अक्षरों के लिए स्मरणीय (mnemonic) का समर्थन करता है। उदाहरण के लिए, \\013 और \\\\CR का अर्थ CR है।

### setFilledBars() {#setfilledbars}

बार्स भरे हुए हैं या नहीं, यह दर्शाने वाला मान सेट करता है। केवल 1D बारकोड्स के लिए। डिफ़ॉल्ट मान: true।

### setGS1CompositeBar() {#setgs1compositebar}

GS1 कॉम्पोजिट बार पैरामीटर। यह उदाहरण दिखाता है कि कैसे GS1 कॉम्पोजिट बार इमेज बनाएं और सहेजें। ध्यान दें कि 1D कोडटेक्स्ट और 2D कोडटेक्स्ट '/' प्रतीक द्वारा अलग किए जाते हैं।

**Example:**

```js
let codetext = "(01)03212345678906/(21)A1B2C3D4E5F6G7H8";
let generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR, codetext);

generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

// Aspect ratio of 2D component
generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

// X-Dimension of 1D and 2D components
generator.getParameters().getBarcode().getXDimension().setPixels(3);

// Height of 1D component
generator.getParameters().getBarcode().getBarHeight().setPixels(100);

generator.save("test.png", BarcodeImageFormat.PNG);
```

### setPadding() {#setpadding}

बारकोड पैडिंग्स। डिफ़ॉल्ट मान: 5pt 5pt 5pt 5pt।

### setWideNarrowRatio() {#setwidenarrowratio}

वाइड बार और नॅरो बार का अनुपात। डिफ़ॉल्ट मान: 3, अर्थात वाइड बार नॅरो बार से 3 गुना चौड़े होते हैं। ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39Extended, Code39Standard के लिए उपयोग किया जाता है। WideNarrowRatio पैरामीटर मान 0 से कम या बराबर है।

### setXDimension() {#setxdimension}

x-डायमेंशन बारकोड बार्स या स्पेसेस की इकाई की सबसे छोटी चौड़ाई है। इसे बढ़ाने से पूरी बारकोड इमेज की चौड़ाई बढ़ेगी। यदि AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट है तो इसे नजरअंदाज़ किया जाता है।

**Throws:** BarcodeException
