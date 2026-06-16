---
title: BarcodeParameters
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: बारकोड निर्माण पैरामीटर।
type: docs
weight: 14
url: /hi/androidjava/com.aspose.barcode.generation/barcodeparameters/
---
**Inheritance:**
java.lang.Object
```
public class BarcodeParameters
```

बारकोड निर्माण पैरामीटर।
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAspectRatio()](#getAspectRatio--) |  |
| [getAustralianPost()](#getAustralianPost--) | AustralianPost बारकोड पैरामीटर। |
| [getAztec()](#getAztec--) | Aztec पैरामीटर। |
| [getBarColor()](#getBarColor--) | बार्स का रंग। |
| [getBarHeight()](#getBarHeight--) | 1D बारकोड की बार्स की ऊँचाई [Unit](../../com.aspose.barcode.generation/unit) मान में। |
| [getBarWidthReduction()](#getBarWidthReduction--) | बार्स रिडक्शन वैल्यू प्राप्त करें जो प्रिंटिंग के दौरान इंक स्प्रेड की भरपाई के लिए उपयोग होती है। |
| [getBarcodeType()](#getBarcodeType--) |  |
| [getChecksumAlwaysShow()](#getChecksumAlwaysShow--) | Code128 और GS1Code128 बारकोड के लिए मानव पठनीय पाठ में हमेशा चेकसम अंक प्रदर्शित करें। |
| [getClass()](#getClass--) |  |
| [getCodabar()](#getCodabar--) | Codabar पैरामीटर। |
| [getCodablock()](#getCodablock--) | Codablock पैरामीटर। |
| [getCode128()](#getCode128--) | Code128 पैरामीटर। |
| [getCode16K()](#getCode16K--) | Code16K पैरामीटर। |
| [getCodeText()](#getCodeText--) |  |
| [getCodeTextParameters()](#getCodeTextParameters--) | कोडटेक्स्ट पैरामीटर। |
| [getComplexBarcode()](#getComplexBarcode--) |  |
| [getCoupon()](#getCoupon--) | कूपन पैरामीटर। |
| [getDataBar()](#getDataBar--) | Databar पैरामीटर। |
| [getDataMatrix()](#getDataMatrix--) | DataMatrix पैरामीटर। |
| [getDotCode()](#getDotCode--) | DotCode पैरामीटर। |
| [getEnableEscape()](#getEnableEscape--) | CodeText प्रॉपर्टी में "\\" अक्षर को एस्केप कैरेक्टर के रूप में समझाया जाता है या नहीं, यह दर्शाता है। |
| [getFilledBars()](#getFilledBars--) | बार्स भरे हुए हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [getGS1CompositeBar()](#getGS1CompositeBar--) | GS1 कॉम्पोजिट बार पैरामीटर। |
| [getHanXin()](#getHanXin--) | HanXin पैरामीटर। |
| [getITF()](#getITF--) | ITF पैरामीटर। |
| [getMaxiCode()](#getMaxiCode--) | MaxiCode पैरामीटर। |
| [getPadding()](#getPadding--) | बारकोड पैडिंग्स। |
| [getPatchCode()](#getPatchCode--) | PatchCode पैरामीटर। |
| [getPdf417()](#getPdf417--) | PDF417 पैरामीटर। |
| [getPostal()](#getPostal--) | डाक पैरामीटर। |
| [getQR()](#getQR--) | QR, माइक्रोQR और RectMicroQR पैरामीटर। |
| [getSupplement()](#getSupplement--) | पूरक पैरामीटर। |
| [getThrowExceptionWhenCodeTextIncorrect()](#getThrowExceptionWhenCodeTextIncorrect--) | केवल 1D बारकोड के लिए। |
| [getWideNarrowRatio()](#getWideNarrowRatio--) | वाइड बार्स से नैरो बार्स का अनुपात। |
| [getXDimension()](#getXDimension--) | x-डायमेंशन बारकोड बार या स्पेस की इकाई की सबसे छोटी चौड़ाई है। |
| [hashCode()](#hashCode--) |  |
| [isChecksumEnabled()](#isChecksumEnabled--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarColor(int value)](#setBarColor-int-) | बार्स का रंग। |
| [setBarHeight(Unit value)](#setBarHeight-com.aspose.barcode.generation.Unit-) | 1D बारकोड की बार्स की ऊँचाई [Unit](../../com.aspose.barcode.generation/unit) मान में। |
| [setBarWidthReduction(Unit value)](#setBarWidthReduction-com.aspose.barcode.generation.Unit-) | प्रिंटिंग के दौरान इंक के फैलाव की भरपाई के लिए उपयोग किया जाने वाला बार्स रिडक्शन वैल्यू सेट करता है। |
| [setChecksumAlwaysShow(boolean value)](#setChecksumAlwaysShow-boolean-) | Code128 और GS1Code128 बारकोड के लिए मानव पठनीय पाठ में हमेशा चेकसम अंक प्रदर्शित करें। |
| [setChecksumEnabled(EnableChecksum value)](#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-) |  |
| [setCodeText(String value)](#setCodeText-java.lang.String-) |  |
| [setEnableEscape(boolean value)](#setEnableEscape-boolean-) | CodeText प्रॉपर्टी में "\\" अक्षर को एस्केप कैरेक्टर के रूप में समझाया जाता है या नहीं, यह दर्शाता है। |
| [setFilledBars(boolean value)](#setFilledBars-boolean-) | बार्स भरे हुए हैं या नहीं, यह दर्शाने वाला मान सेट करता है। |
| [setGS1CompositeBar(GS1CompositeBarParameters value)](#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-) | GS1 कॉम्पोजिट बार पैरामीटर। |
| [setThrowExceptionWhenCodeTextIncorrect(boolean value)](#setThrowExceptionWhenCodeTextIncorrect-boolean-) | केवल 1D बारकोड के लिए। |
| [setWideNarrowRatio(float value)](#setWideNarrowRatio-float-) | वाइड बार्स से नैरो बार्स का अनुपात। |
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
### getAspectRatio() {#getAspectRatio--}
```
public final float getAspectRatio()
```




**Returns:**
float
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


बार्स का रंग। डिफ़ॉल्ट मान: Color.Black।

**Returns:**
int
### getBarHeight() {#getBarHeight--}
```
public final Unit getBarHeight()
```


1D बारकोड के बार्स की ऊँचाई [Unit](../../com.aspose.barcode.generation/unit) मान में। यदि BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) प्रॉपर्टी AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट है तो इसे नजरअंदाज किया जाएगा।

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getBarWidthReduction() {#getBarWidthReduction--}
```
public final Unit getBarWidthReduction()
```


प्रिंटिंग के दौरान इंक के फैलाव की भरपाई के लिए उपयोग किया जाने वाला बार्स रिडक्शन वैल्यू प्राप्त करें। डिफ़ॉल्ट मान: 0

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit) - bars reduction value that is used to compensate ink spread while printing.
### getBarcodeType() {#getBarcodeType--}
```
public final BaseEncodeType getBarcodeType()
```




**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype)
### getChecksumAlwaysShow() {#getChecksumAlwaysShow--}
```
public final boolean getChecksumAlwaysShow()
```


Code128 और GS1Code128 बारकोड के लिए मानव पठनीय पाठ में हमेशा चेकसम अंक प्रदर्शित करें।

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
### getCodeText() {#getCodeText--}
```
public final String getCodeText()
```




**Returns:**
java.lang.String
### getCodeTextParameters() {#getCodeTextParameters--}
```
public final CodetextParameters getCodeTextParameters()
```


कोडटेक्स्ट पैरामीटर।

**Returns:**
[CodetextParameters](../../com.aspose.barcode.generation/codetextparameters)
### getComplexBarcode() {#getComplexBarcode--}
```
public final ComplexBarcode getComplexBarcode()
```




**Returns:**
[ComplexBarcode](../../com.aspose.barcode.generation/complexbarcode)
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
### getEnableEscape() {#getEnableEscape--}
```
public final boolean getEnableEscape()
```


CodeText प्रॉपर्टी में "\\" अक्षर को एस्केप कैरेक्टर के रूप में समझाया जाता है या नहीं, यह दर्शाता है। केवल Pdf417, DataMatrix, Code128 के लिए उपयोग किया जाता है। यदि EnableEscape सत्य है, तो "\\" को विशेष एस्केप कैरेक्टर के रूप में समझाया जाएगा। अन्यथा, "\\" सामान्य अक्षर के रूप में कार्य करेगा।

Aspose.BarCode दशमलव ASCII कोड और ASCII कंट्रोल-कोड अक्षरों के लिए म्नेमोनिक इनपुट करने का समर्थन करता है। उदाहरण के लिए, \\013 और \\\\CR CR के लिए खड़े हैं।

**Returns:**
boolean
### getFilledBars() {#getFilledBars--}
```
public final boolean getFilledBars()
```


बार्स भरे हुए हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है। केवल 1D बारकोड के लिए। डिफ़ॉल्ट मान: true।

**Returns:**
boolean - एक मान जो दर्शाता है कि बार्स भरे हुए हैं या नहीं।
### getGS1CompositeBar() {#getGS1CompositeBar--}
```
public final GS1CompositeBarParameters getGS1CompositeBar()
```


GS1 कॉम्पोजिट बार पैरामीटर।

यह उदाहरण दिखाता है कि कैसे एक GS1 कॉम्पोजिट बार इमेज बनाएं और सहेजें। ध्यान दें कि 1D कोडटेक्स्ट और 2D कोडटेक्स्ट को '|' प्रतीक द्वारा अलग किया गया है।

```

 [C#]
   var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 	  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
 	  {
       generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
       generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
       // Aspect ratio of 2D component
       generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
       // X-Dimension of 1D and 2D components
       generator.Parameters.Barcode.XDimension.Pixels = 3;
       // Height of 1D component
       generator.Parameters.Barcode.BarHeight.Pixels = 100;
       generator.Save("test.png");
   }
 	
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


बारकोड पैडिंग्स। डिफ़ॉल्ट मान: 5pt 5pt 5pt 5pt।

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


डाक पैरामीटर। उपयोग किया जाता है: Postnet, Planet।

**Returns:**
[PostalParameters](../../com.aspose.barcode.generation/postalparameters)
### getQR() {#getQR--}
```
public final QrParameters getQR()
```


QR, माइक्रोQR और RectMicroQR पैरामीटर।

**Returns:**
[QrParameters](../../com.aspose.barcode.generation/qrparameters)
### getSupplement() {#getSupplement--}
```
public final SupplementParameters getSupplement()
```


सप्लीमेंट पैरामीटर। Interleaved2of5, Standard2of5, EAN13, EAN8, UPCA, UPCE, ISBN, ISSN, ISMN के लिए उपयोग किया जाता है।

**Returns:**
[SupplementParameters](../../com.aspose.barcode.generation/supplementparameters)
### getThrowExceptionWhenCodeTextIncorrect() {#getThrowExceptionWhenCodeTextIncorrect--}
```
public final boolean getThrowExceptionWhenCodeTextIncorrect()
```


केवल 1D बारकोड के लिए। यदि कोडटेक्स्ट गलत है और मान true पर सेट है - अपवाद फेंका जाएगा। अन्यथा कोडटेक्स्ट को बारकोड की विशिष्टता के अनुसार सुधारा जाएगा। अपवाद हमेशा फेंका जाएगा: Databar सिम्बोलॉजी के लिए यदि कोडटेक्स्ट गलत है। अपवाद कभी नहीं फेंका जाएगा: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 सिम्बोलॉजी के लिए यदि कोडटेक्स्ट गलत है।

**Returns:**
boolean
### getWideNarrowRatio() {#getWideNarrowRatio--}
```
public final float getWideNarrowRatio()
```


वाइड बार्स से नैरो बार्स का अनुपात। डिफ़ॉल्ट मान: 3, अर्थात वाइड बार्स की चौड़ाई नैरो बार्स से 3 गुना है। ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII के लिए उपयोग किया जाता है।

**Returns:**
float
### getXDimension() {#getXDimension--}
```
public final Unit getXDimension()
```


x-dimension बारकोड बार या स्पेस की इकाई की सबसे छोटी चौड़ाई है। इसे बढ़ाने से पूरी बारकोड छवि की चौड़ाई बढ़ जाएगी। यदि BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) प्रॉपर्टी AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट है तो इसे अनदेखा किया जाता है।

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isChecksumEnabled() {#isChecksumEnabled--}
```
public final EnableChecksum isChecksumEnabled()
```


1D बारकोड उत्पन्न करते समय चेकसम सक्षम करें।

डिफ़ॉल्ट रूप से उन सिंबोलॉजी के लिए हाँ माना जाता है जिनमें चेकसम अनिवार्य है, और जहाँ केवल चेकसम संभव है वहाँ नहीं।

चेकसम संभव है: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

चेकसम हमेशा उपयोग किया जाता है: बाकी सिंबोलॉजी

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


बार्स का रंग। डिफ़ॉल्ट मान: Color.Black।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setBarHeight(Unit value) {#setBarHeight-com.aspose.barcode.generation.Unit-}
```
public final void setBarHeight(Unit value)
```


1D बारकोड के बार्स की ऊँचाई [Unit](../../com.aspose.barcode.generation/unit) मान में। यदि BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) प्रॉपर्टी AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट है तो इसे नजरअंदाज किया जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setBarWidthReduction(Unit value) {#setBarWidthReduction-com.aspose.barcode.generation.Unit-}
```
public final void setBarWidthReduction(Unit value)
```


बार्स रिडक्शन वैल्यू सेट करता है जिसका उपयोग प्रिंटिंग के दौरान इंक के फैलाव की भरपाई के लिए किया जाता है। डिफ़ॉल्ट मान: 0

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) | बार्स रिडक्शन वैल्यू जो प्रिंटिंग के दौरान इंक के फैलाव की भरपाई के लिए उपयोग की जाती है। |

### setChecksumAlwaysShow(boolean value) {#setChecksumAlwaysShow-boolean-}
```
public final void setChecksumAlwaysShow(boolean value)
```


Code128 और GS1Code128 बारकोड के लिए मानव पठनीय पाठ में हमेशा चेकसम अंक प्रदर्शित करें।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setChecksumEnabled(EnableChecksum value) {#setChecksumEnabled-com.aspose.barcode.generation.EnableChecksum-}
```
public final void setChecksumEnabled(EnableChecksum value)
```


1D बारकोड उत्पन्न करते समय चेकसम सक्षम करें।

डिफ़ॉल्ट रूप से उन सिंबोलॉजी के लिए हाँ माना जाता है जिनमें चेकसम अनिवार्य है, और जहाँ केवल चेकसम संभव है वहाँ नहीं।

चेकसम संभव है: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN, Codabar

चेकसम हमेशा उपयोग किया जाता है: बाकी सिंबोलॉजी

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [EnableChecksum](../../com.aspose.barcode.generation/enablechecksum) |  |

### setCodeText(String value) {#setCodeText-java.lang.String-}
```
public final void setCodeText(String value)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setEnableEscape(boolean value) {#setEnableEscape-boolean-}
```
public final void setEnableEscape(boolean value)
```


CodeText प्रॉपर्टी में "\\" अक्षर को एस्केप कैरेक्टर के रूप में समझाया जाता है या नहीं, यह दर्शाता है। केवल Pdf417, DataMatrix, Code128 के लिए उपयोग किया जाता है। यदि EnableEscape सत्य है, तो "\\" को विशेष एस्केप कैरेक्टर के रूप में समझाया जाएगा। अन्यथा, "\\" सामान्य अक्षर के रूप में कार्य करेगा।

Aspose.BarCode दशमलव ASCII कोड और ASCII कंट्रोल-कोड अक्षरों के लिए म्नेमोनिक इनपुट करने का समर्थन करता है। उदाहरण के लिए, \\013 और \\\\CR CR के लिए खड़े हैं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setFilledBars(boolean value) {#setFilledBars-boolean-}
```
public final void setFilledBars(boolean value)
```


बार्स भरे हुए हैं या नहीं यह दर्शाने वाला मान सेट करता है। केवल 1D बारकोड के लिए। डिफ़ॉल्ट मान: true।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | एक मान जो दर्शाता है कि बार्स भरे हुए हैं या नहीं। |

### setGS1CompositeBar(GS1CompositeBarParameters value) {#setGS1CompositeBar-com.aspose.barcode.generation.GS1CompositeBarParameters-}
```
public final void setGS1CompositeBar(GS1CompositeBarParameters value)
```


GS1 कॉम्पोजिट बार पैरामीटर।

यह उदाहरण दिखाता है कि कैसे एक GS1 कॉम्पोजिट बार इमेज बनाएं और सहेजें। ध्यान दें कि 1D कोडटेक्स्ट और 2D कोडटेक्स्ट को '|' प्रतीक द्वारा अलग किया गया है।

```

 [C#]
   var codetext = "(01)03212345678906|(21)A1B2C3D4E5F6G7H8";
 	  using (var generator = new BarcodeGenerator(EncodeTypes.GS1CompositeBar, codetext))
 	  {
       generator.Parameters.Barcode.GS1CompositeBar.LinearComponentType = EncodeTypes.GS1Code128;
       generator.Parameters.Barcode.GS1CompositeBar.TwoDComponentType = TwoDComponentType.CC_A;
       // Aspect ratio of 2D component
       generator.Parameters.Barcode.Pdf417.AspectRatio = 3;
       // X-Dimension of 1D and 2D components
       generator.Parameters.Barcode.XDimension.Pixels = 3;
       // Height of 1D component
       generator.Parameters.Barcode.BarHeight.Pixels = 100;
       generator.Save("test.png");
   }
 	
```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [GS1CompositeBarParameters](../../com.aspose.barcode.generation/gs1compositebarparameters) |  |

### setThrowExceptionWhenCodeTextIncorrect(boolean value) {#setThrowExceptionWhenCodeTextIncorrect-boolean-}
```
public final void setThrowExceptionWhenCodeTextIncorrect(boolean value)
```


केवल 1D बारकोड के लिए। यदि कोडटेक्स्ट गलत है और मान true पर सेट है - अपवाद फेंका जाएगा। अन्यथा कोडटेक्स्ट को बारकोड की विशिष्टता के अनुसार सुधारा जाएगा। अपवाद हमेशा फेंका जाएगा: Databar सिम्बोलॉजी के लिए यदि कोडटेक्स्ट गलत है। अपवाद कभी नहीं फेंका जाएगा: AustraliaPost, SingapurePost, Code39FullASCII, Code93, Code16K, Code128 सिम्बोलॉजी के लिए यदि कोडटेक्स्ट गलत है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setWideNarrowRatio(float value) {#setWideNarrowRatio-float-}
```
public final void setWideNarrowRatio(float value)
```


वाइड बार्स से नैरो बार्स का अनुपात। डिफ़ॉल्ट मान: 3, अर्थात वाइड बार्स की चौड़ाई नैरो बार्स से 3 गुना है। ITF, PZN, PharmaCode, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, IATA2of5, VIN, DeutschePost, OPC, Code32, DataLogic2of5, PatchCode, Code39, Code39FullASCII के लिए उपयोग किया जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### setXDimension(Unit value) {#setXDimension-com.aspose.barcode.generation.Unit-}
```
public final void setXDimension(Unit value)
```


x-dimension बारकोड बार या स्पेस की इकाई की सबसे छोटी चौड़ाई है। इसे बढ़ाने से पूरी बारकोड छवि की चौड़ाई बढ़ जाएगी। यदि BaseGenerationParameters.AutoSizeMode ([BaseGenerationParameters.getAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#getAutoSizeMode)/[BaseGenerationParameters.setAutoSizeMode](../../com.aspose.barcode.generation/basegenerationparameters\#setAutoSizeMode)) प्रॉपर्टी AutoSizeMode.Nearest या AutoSizeMode.Interpolation पर सेट है तो इसे अनदेखा किया जाता है।

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

