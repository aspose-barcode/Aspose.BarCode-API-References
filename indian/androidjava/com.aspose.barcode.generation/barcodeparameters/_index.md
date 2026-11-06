---
title: "BarcodeParameters"
second_title: "Aspose.BarCode के लिए Android via Java API संदर्भ"
description: "बारकोड जनरेशन पैरामीटर।"
type: docs
weight: 14
url: /hi/androidjava/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

बारकोड जनरेशन पैरामीटर।
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAustralianPost()](#getAustralianPost--) | AustralianPost बारकोड पैरामीटर। |
| [getAztec()](#getAztec--) | Aztec पैरामीटर। |
| [getBarColor()](#getBarColor--) | बारों का रंग। |
| [getBarHeight()](#getBarHeight--) | 1D बारकोड की बार की ऊँचाई [Unit](../../com.aspose.barcode.generation/unit) मान में। |
| [getBarWidthReduction()](#getBarWidthReduction--) | प्रिंटिंग के दौरान इंक के फैलाव की भरपाई के लिए उपयोग किए जाने वाले बार कमी मान को प्राप्त करें। |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Code128 और GS1Code128 बारकोड के मानव-पठनीय पाठ में हमेशा चेकसम अंक दिखाएँ। |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Codabar पैरामीटर। |
| [getCodablock()](#getCodablock--) | Codablock पैरामीटर। |
| [getCode128()](#getCode128--) | Code128 पैरामीटर। |
| [getCode16K()](#getCode16K--) | Code16K पैरामीटर। |
| [getCodeTextParameters()](#getCodeTextParameters--) | Codetext पैरामीटर। |
| [getCoupon()](#getCoupon--) | कूपन पैरामीटर। |
| [getDataBar()](#getDataBar--) | Databar पैरामीटर। |
| [getDataMatrix()](#getDataMatrix--) | DataMatrix पैरामीटर। |
| [getDotCode()](#getDotCode--) | DotCode पैरामीटर। |
| [getFilledBars()](#getFilledBars--) | बार भरे हुए हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | GS1 कॉम्पोजिट बार पैरामीटर। |
| [getHanXin()](#getHanXin--) | HanXin पैरामीटर। |
| [getITF()](#getITF--) | ITF पैरामीटर। |
| [getMaxiCode()](#getMaxiCode--) | MaxiCode पैरामीटर। |
| [getPadding()](#getPadding--) | बारकोड पैडिंग। |
| [getPatchCode()](#getPatchCode--) | PatchCode पैरामीटर। |
| [getPdf417()](#getPdf417--) | PDF417 पैरामीटर। |
| [getPostal()](#getPostal--) | डाक पैरामीटर। |
| [getQR()](#getQR--) | QR, माइक्रोQR और रेक्टमाइक्रोQR पैरामीटर। |
| [getSupplement()](#getSupplement--) | पूरक पैरामीटर। |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | केवल 1D बारकोड के लिए। |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | वाइड बार से नॉरर बार का अनुपात। |
| [getXDimension()](#getXDimension--) | x-डायमेंशन बारकोड बार या स्पेस की इकाई की सबसे छोटी चौड़ाई है। |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(int value)](#setBarColor-int-) | बारों का रंग। |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | 1D बारकोड की बार की ऊँचाई [Unit](../../com.aspose.barcode.generation/unit) मान में। |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | प्रिंटिंग के दौरान इंक के फैलाव की भरपाई के लिए उपयोग किए जाने वाले बार कमी मान को सेट करता है। |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Code128 और GS1Code128 बारकोड के मानव-पठनीय पाठ में हमेशा चेकसम अंक दिखाएँ। |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | बार भरे हुए हैं या नहीं, यह दर्शाने वाला मान सेट करता है। |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | GS1 कॉम्पोजिट बार पैरामीटर। |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | केवल 1D बारकोड के लिए। |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | वाइड बार से नॉरर बार का अनुपात। |
| [setXDimension(Unit value)](#setXDimension-com.aspose.barcode.generation.Unit-) | x-डायमेंशन बारकोड बार या स्पेस की इकाई की सबसे छोटी चौड़ाई है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAustralianPost() {#getAustralianPost--}
```
public final AustralianPostParameters getAustralianPost()
```


AustralianPost बारकोड पैरामीटर।

**Returns:**
[AustralianPostParameters](../../com.aspose.barcode.generation/australianpostparameters)
### getAztec() {#getAztec--}
```
public final AztecParameters getAztec()
```


Aztec पैरामीटर।

**Returns:**
[AztecParameters](../../com.aspose.barcode.generation/aztecparameters)
### getBarColor() {#getBarColor--}
```
public final int getBarColor()
```


बारों का रंग। डिफ़ॉल्ट मान: Color.Black।

**Returns:**
int
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


1D बारकोड की बारों की ऊँचाई [Unit](../../com.aspose.barcode.generation/unit) मान में। यदि BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) प्रॉपर्टी AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट है तो इसे अनदेखा किया जाता है।

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


बारों की कमी मान प्राप्त करें जो प्रिंटिंग के दौरान इंक के फैलाव की भरपाई के लिए उपयोग किया जाता है। डिफ़ॉल्ट मान: 0

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - bars reduction value that is used to compensate ink spread while printing.
### getChecksumAlwaysShow() {#getChecksumAlwaysShow--}
```
public final boolean getChecksumAlwaysShow()
```


Code128 और GS1Code128 बारकोड के मानव-पठनीय पाठ में हमेशा चेकसम अंक दिखाएँ।

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodabar() {#getCodabar--}
```
public final CodabarParameters getCodabar()
```


Codabar पैरामीटर।

**Returns:**
[CodabarParameters](../../com.aspose.barcode.generation/codabarparameters)
### getCodablock() {#getCodablock--}
```
public final CodablockParameters getCodablock()
```


Codablock पैरामीटर।

**Returns:**
[CodablockParameters](../../com.aspose.barcode.generation/codablockparameters)
### getCode128() {#getCode128--}
```
public final Code128Parameters getCode128()
```


Code128 पैरामीटर।

**Returns:**
[Code128Parameters](../../com.aspose.barcode.generation/code128parameters)
### getCode16K() {#getCode16K--}
```
public final Code16KParameters getCode16K()
```


Code16K पैरामीटर।

**Returns:**
[Code16KParameters](../../com.aspose.barcode.generation/code16kparameters)
### getCodeTextParameters() {#getCodeTextParameters--}
```
public final CodetextParameters getCodeTextParameters()
```


Codetext पैरामीटर।

**Returns:**
[CodetextParameters](../../com.aspose.barcode.generation/codetextparameters)
### getCoupon() {#getCoupon--}
```
public final CouponParameters getCoupon()
```


कूपन पैरामीटर। UpcaGs1DatabarCoupon, UpcaGs1Code128Coupon के लिए उपयोग किया जाता है।

**Returns:**
[CouponParameters](../../com.aspose.barcode.generation/couponparameters)
### getDataBar() {#getDataBar--}
```
public final DataBarParameters getDataBar()
```


Databar पैरामीटर।

**Returns:**
[DataBarParameters](../../com.aspose.barcode.generation/databarparameters)
### getDataMatrix() {#getDataMatrix--}
```
public final DataMatrixParameters getDataMatrix()
```


DataMatrix पैरामीटर।

**Returns:**
[DataMatrixParameters](../../com.aspose.barcode.generation/datamatrixparameters)
### getDotCode() {#getDotCode--}
```
public final DotCodeParameters getDotCode()
```


DotCode पैरामीटर।

**Returns:**
[DotCodeParameters](../../com.aspose.barcode.generation/dotcodeparameters)
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


एक मान प्राप्त करता है जो दर्शाता है कि बार भरे हुए हैं या नहीं। केवल 1D बारकोड के लिए। डिफ़ॉल्ट मान: true.

**Returns:**
boolean - एक मान जो दर्शाता है कि बार भरे हुए हैं या नहीं।
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


GS1 कॉम्पोजिट बार पैरामीटर।

यह उदाहरण दिखाता है कि कैसे एक GS1 कॉम्पोज़िट बार इमेज बनाएं और सहेजें। ध्यान दें कि 1D कोडटेक्स्ट और 2D कोडटेक्स्ट को '|' प्रतीक द्वारा अलग किया गया है।

```

 String codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR,codetext);

 generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
 generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

 // Aspect ratio of 2D component
 generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

 // X-Dimension of 1D and 2D components
 generator.getParameters().getBarcode().getXDimension().setPixels(3);

 // Height of 1D component
 generator.getParameters().getBarcode().getBarHeight().setPixels(100);

 generator.save("test.png");
 
```

**Returns:**
[GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters)
### getHanXin() {#getHanXin--}
```
public final HanXinParameters getHanXin()
```


HanXin पैरामीटर।

**Returns:**
[HanXinParameters](../../com.aspose.barcode.generation/hanxinparameters)
### getITF() {#getITF--}
```
public final ITFParameters getITF()
```


ITF पैरामीटर।

**Returns:**
[ITFParameters](../../com.aspose.barcode.generation/itfparameters)
### getMaxiCode() {#getMaxiCode--}
```
public final MaxiCodeParameters getMaxiCode()
```


MaxiCode पैरामीटर।

**Returns:**
[MaxiCodeParameters](../../com.aspose.barcode.generation/maxicodeparameters)
### getPadding() {#getPadding--}
```
public final Padding getPadding()
```


बारकोड पैडिंग। डिफ़ॉल्ट मान: 5pt 5pt 5pt 5pt।

**Returns:**
[Padding](../../com.aspose.barcode.generation/padding)
### getPatchCode() {#getPatchCode--}
```
public final PatchCodeParameters getPatchCode()
```


PatchCode पैरामीटर।

**Returns:**
[PatchCodeParameters](../../com.aspose.barcode.generation/patchcodeparameters)
### getPdf417() {#getPdf417--}
```
public final Pdf417Parameters getPdf417()
```


PDF417 पैरामीटर।

**Returns:**
[Pdf417Parameters](../../com.aspose.barcode.generation/pdf417parameters)
### getPostal() {#getPostal--}
```
public final PostalParameters getPostal()
```


डाक पैरामीटर। Postnet, Planet के लिए उपयोग किया जाता है।

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public final QrParameters getQR()
```


QR, माइक्रोQR और रेक्टमाइक्रोQR पैरामीटर।

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


पूरक पैरामीटर। Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN के लिए उपयोग किया जाता है।

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


केवल 1D बारकोड के लिए। यदि कोडटेक्स्ट गलत है और मान true पर सेट है - अपवाद फेंका जाएगा। अन्यथा कोडटेक्स्ट को बारकोड की विशिष्टता के अनुसार सुधारा जाएगा। अपवाद हमेशा फेंका जाएगा: Databar सिम्बोलॉजी यदि कोडटेक्स्ट गलत है। अपवाद हमेशा नहीं फेंका जाएगा: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 सिम्बोलॉजी यदि कोडटेक्स्ट गलत है।

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


वाइड बारों से नॉर्‍ड बारों का अनुपात। डिफ़ॉल्ट मान: 3, अर्थात वाइड बार नॉर्‍ड बारों से 3 गुना चौड़े होते हैं। ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII के लिए उपयोग किया जाता है।

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


x-डायमेंशन बारकोड बार या स्पेस की इकाई की सबसे छोटी चौड़ाई है। इसे बढ़ाने से पूरी बारकोड इमेज की चौड़ाई बढ़ेगी। यदि BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) प्रॉपर्टी AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट है तो इसे अनदेखा किया जाता है।

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### isChecksumEnabled() {#isChecksumEnabled--}
```
public final EnableChecksum isChecksumEnabled()
```


1D बारकोड उत्पन्न करते समय चेकसम सक्षम करें।

डिफ़ॉल्ट रूप से उन सिम्बोलॉजी के लिए Yes माना जाता है जिनमें चेकसम अनिवार्य है, और उन मामलों में जहाँ चेकसम केवल संभव है, No माना जाता है।

चेकसम संभव है: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

चेकसम हमेशा उपयोग किया जाता है: बाकी सिम्बोलॉजी

**Returns:**
[EnableChecksum](../../com.aspose.barcode.generation/enablechecksum)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarColor(int value) {#setBarColor-int-}
```
public final void setBarColor(int value)
```


बारों का रंग। डिफ़ॉल्ट मान: Color.Black।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


1D बारकोड की बारों की ऊँचाई [Unit](../../com.aspose.barcode.generation/unit) मान में। यदि BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) प्रॉपर्टी AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट है तो इसे अनदेखा किया जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


बारों की कमी मान सेट करता है जो प्रिंटिंग के दौरान इंक के फैलाव की भरपाई के लिए उपयोग किया जाता है। डिफ़ॉल्ट मान: 0

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | बारों की कमी मान जो प्रिंटिंग के दौरान इंक के फैलाव की भरपाई के लिए उपयोग किया जाता है। |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Code128 और GS1Code128 बारकोड के मानव-पठनीय पाठ में हमेशा चेकसम अंक दिखाएँ।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


1D बारकोड उत्पन्न करते समय चेकसम सक्षम करें।

डिफ़ॉल्ट रूप से उन सिम्बोलॉजी के लिए Yes माना जाता है जिनमें चेकसम अनिवार्य है, और उन मामलों में जहाँ चेकसम केवल संभव है, No माना जाता है।

चेकसम संभव है: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

चेकसम हमेशा उपयोग किया जाता है: बाकी सिम्बोलॉजी

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि बार भरे हुए हैं या नहीं। केवल 1D बारकोड के लिए। डिफ़ॉल्ट मान: true.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | एक मान जो दर्शाता है कि बार भरे हुए हैं या नहीं। |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


GS1 कॉम्पोजिट बार पैरामीटर।

यह उदाहरण दिखाता है कि कैसे एक GS1 कॉम्पोज़िट बार इमेज बनाएं और सहेजें। ध्यान दें कि 1D कोडटेक्स्ट और 2D कोडटेक्स्ट को '|' प्रतीक द्वारा अलग किया गया है।

```

 String codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.GS_1_COMPOSITE_BAR,codetext);

 generator.getParameters().getBarcode().getGS1CompositeBar().setLinearComponentType(EncodeTypes.GS_1_CODE_128);
 generator.getParameters().getBarcode().getGS1CompositeBar().setTwoDComponentType(TwoDComponentType.CC_A);

 // Aspect ratio of 2D component
 generator.getParameters().getBarcode().getPdf417().setAspectRatio(3);

 // X-Dimension of 1D and 2D components
 generator.getParameters().getBarcode().getXDimension().setPixels(3);

 // Height of 1D component
 generator.getParameters().getBarcode().getBarHeight().setPixels(100);

 generator.save("test.png");
 
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


केवल 1D बारकोड के लिए। यदि कोडटेक्स्ट गलत है और मान true पर सेट है - अपवाद फेंका जाएगा। अन्यथा कोडटेक्स्ट को बारकोड की विशिष्टता के अनुसार सुधारा जाएगा। अपवाद हमेशा फेंका जाएगा: Databar सिम्बोलॉजी यदि कोडटेक्स्ट गलत है। अपवाद हमेशा नहीं फेंका जाएगा: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 सिम्बोलॉजी यदि कोडटेक्स्ट गलत है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


वाइड बारों से नॉर्‍ड बारों का अनुपात। डिफ़ॉल्ट मान: 3, अर्थात वाइड बार नॉर्‍ड बारों से 3 गुना चौड़े होते हैं। ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII के लिए उपयोग किया जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


x-डायमेंशन बारकोड बार या स्पेस की इकाई की सबसे छोटी चौड़ाई है। इसे बढ़ाने से पूरी बारकोड इमेज की चौड़ाई बढ़ेगी। यदि BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) प्रॉपर्टी AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट है तो इसे अनदेखा किया जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

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
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

