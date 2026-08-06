---
title: QualitySettings
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: QualitySettings allows to configure recognition quality and speed manually.
type: docs
weight: 44
url: /hi/androidjava/com.aspose.barcode.barcoderecognition/qualitysettings/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
android.os.Parcelable
```
public final class QualitySettings implements Parcelable
```

QualitySettings मैन्युअल रूप से पहचान की गुणवत्ता और गति को कॉन्फ़िगर करने की अनुमति देता है। आप एम्बेडेड प्रीसेट्स के साथ जल्दी से QualitySettings सेट कर सकते हैं: HighPerformance, NormalQuality, HighQuality, MaxQuality या आप अलग-अलग विकल्पों को मैन्युअल रूप से कॉन्फ़िगर कर सकते हैं। QualitySettings का डिफ़ॉल्ट मान NormalQuality है।

--------------------

> ```
> This sample shows how to use QualitySettings with BarCodeReader
>  
>  //set HighPerformance recogition mode
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighQuality recognition mode
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighQuality());
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low sized barcodes
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setXDimension(XDimensionMode.SMALL);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
>  //set HighPerformance recogition mode for low quality barcodes
>  BarCodeReader reader = new BarCodeReader("test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>  {
>      reader.setQualitySettings(QualitySettings.getHighPerformance());
>      reader.getQualitySettings().setBarcodeQuality(BarcodeQualityMode.LOW);
>      for(BarCodeResult result : reader.readBarCodes())
>          System.out.println(result.getCodeText());
>  }
> ```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [QualitySettings()](#QualitySettings--) | QualitySettings कंस्ट्रक्टर |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [CREATOR](#CREATOR) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [describeContents()](#describeContents--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowIncorrectBarcodes()](#getAllowIncorrectBarcodes--) | इंजन को उन बारकोड को पहचानने की अनुमति देता है जिनका चेकसम या मान गलत है। |
| [getBarcodeQuality()](#getBarcodeQuality--) | वह मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने के लिए विधियों को सक्षम करता है। |
| [getClass()](#getClass--) |  |
| [getComplexBackground()](#getComplexBackground--) | वह मोड जो रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है। |
| [getDeconvolution()](#getDeconvolution--) | डिकन्वॉल्यूशन (छवि पुनर्स्थापना) मोड जो छवि क्षय के स्तर को निर्धारित करता है। |
| [getHighPerformance()](#getHighPerformance--) | HighPerformance पहचान गुणवत्ता प्रीसेट। |
| [getHighQuality()](#getHighQuality--) | HighQuality पहचान गुणवत्ता प्रीसेट। |
| [getImageScalingMode()](#getImageScalingMode--) | विशिष्ट ImageScaleMode के साथ छवि को स्केल करने की अनुमति देता है। |
| [getInverseImage()](#getInverseImage--) | वह मोड जो उल्टे रंगों (ल्यूमिनेंस) वाली छवियों पर बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है। |
| [getMaxQuality()](#getMaxQuality--) | MaxQuality पहचान गुणवत्ता प्रीसेट। |
| [getMinimalXDimension()](#getMinimalXDimension--) | UseMinimalXDimension के साथ उपयोग किए जाने वाले XDimension का न्यूनतम आकार पिक्सेल में। |
| [getNormalQuality()](#getNormalQuality--) | NormalQuality पहचान गुणवत्ता प्रीसेट। |
| [getXDimension()](#getXDimension--) | पहचान मोड जो बारकोड के न्यूनतम तत्व का आकार (1 से अनंत तक) निर्धारित करता है: मैट्रिक्स सेल या बार। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowIncorrectBarcodes(boolean value)](#setAllowIncorrectBarcodes-boolean-) | इंजन को उन बारकोड को पहचानने की अनुमति देता है जिनका चेकसम या मान गलत है। |
| [setBarcodeQuality(BarcodeQualityMode value)](#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-) | वह मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने के लिए विधियों को सक्षम करता है। |
| [setComplexBackground(ComplexBackgroundMode value)](#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-) | वह मोड जो रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है। |
| [setDeconvolution(DeconvolutionMode value)](#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-) | डिकन्वॉल्यूशन (छवि पुनर्स्थापना) मोड जो छवि क्षय के स्तर को निर्धारित करता है। |
| [setImageScalingMode(ImageScalingMode value)](#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-) | विशिष्ट ImageScaleMode मान के साथ छवि को स्केल करने की अनुमति देता है: |
| [setInverseImage(InverseImageMode value)](#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-) | वह मोड जो उल्टे रंगों (ल्यूमिनेंस) वाली छवियों पर बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है। |
| [setMinimalXDimension(float value)](#setMinimalXDimension-float-) | UseMinimalXDimension के साथ उपयोग किए जाने वाले XDimension का न्यूनतम आकार पिक्सेल में। |
| [setXDimension(XDimensionMode value)](#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-) | पहचान मोड जो बारकोड के न्यूनतम तत्व का आकार (1 से अनंत तक) निर्धारित करता है: मैट्रिक्स सेल या बार। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeToParcel(Parcel dest, int flags)](#writeToParcel-android.os.Parcel-int-) |  |
### QualitySettings() {#QualitySettings--}
```
public QualitySettings()
```


QualitySettings कंस्ट्रक्टर

### CREATOR {#CREATOR}
```
public static final Parcelable.Creator<QualitySettings> CREATOR
```


### describeContents() {#describeContents--}
```
public int describeContents()
```




**Returns:**
int
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
### getAllowIncorrectBarcodes() {#getAllowIncorrectBarcodes--}
```
public boolean getAllowIncorrectBarcodes()
```


इंजन को उन बारकोड को पहचानने की अनुमति देता है जिनका चेकसम या मान गलत है। इस मोड का उपयोग गलत टेक्स्ट वाले क्षतिग्रस्त बारकोड को पहचानने के लिए किया जा सकता है।

मान: इंजन को गलत बारकोड को पहचानने की अनुमति देता है।

**Returns:**
boolean
### getBarcodeQuality() {#getBarcodeQuality--}
```
public BarcodeQualityMode getBarcodeQuality()
```


वह मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने के लिए विधियों को सक्षम करता है। कम गुणवत्ता वाले बारकोड तत्व को अधिक कठिन विधियों की आवश्यकता होती है जिससे पहचान धीमी हो जाती है।

मान: वह मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने के लिए विधियों को सक्षम करता है।

**Returns:**
[BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComplexBackground() {#getComplexBackground--}
```
public ComplexBackgroundMode getComplexBackground()
```


वह मोड जो रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है।

मान: रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान।

**Returns:**
[ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode)
### getDeconvolution() {#getDeconvolution--}
```
public DeconvolutionMode getDeconvolution()
```


Deconvolution (image restorations) मोड जो छवि क्षय के स्तर को निर्धारित करता है। मूल रूप से डिकन्वॉल्यूशन एक फ़ंक्शन है जो कैमरा द्वारा छवि प्राप्त करने के दौरान ब्लर जैसी किसी भी प्राकृतिक फ़ंक्शन द्वारा क्षतिग्रस्त (कन्वॉल्यूटेड) छवि को पुनर्स्थापित कर सकता है। क्योंकि हम उस छवि फ़ंक्शन का पता नहीं लगा सकते जो छवि को भ्रष्ट करता है, हमें सबसे ज्ञात फ़ंक्शनों जैसे शार्प या गणितीय मॉर्फ़ोलॉजी की जाँच करनी पड़ती है।

मान: Deconvolution मोड जो छवि क्षय के स्तर को निर्धारित करता है।

**Returns:**
[DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode)
### getHighPerformance() {#getHighPerformance--}
```
public static QualitySettings getHighPerformance()
```


HighPerformance पहचान गुणवत्ता प्रीसेट। इस मोड में उच्च गुणवत्ता वाले बारकोड अच्छी तरह से पहचाने जाते हैं।

--------------------

> ```
> This sample shows how to use HighPerformance mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getHighPerformance());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

मान: HighPerformance पहचान गुणवत्ता प्रीसेट।

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getHighQuality() {#getHighQuality--}
```
public static QualitySettings getHighQuality()
```


HighQuality मान्यता गुणवत्ता प्रीसेट। यह प्रीसेट कम गुणवत्ता वाले बारकोड के लिए विकसित किया गया है। यह अत्यधिक क्षतिग्रस्त बारकोड का पता लगाने की अनुमति देता है।

--------------------

> ```
> This sample shows how to use HighQuality mode
>   
> 
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getHighQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

मान: HighQuality मान्यता गुणवत्ता प्रीसेट।

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getImageScalingMode() {#getImageScalingMode--}
```
public ImageScalingMode getImageScalingMode()
```


विशिष्ट ImageScaleMode के साथ छवि को स्केल करने की अनुमति देता है।

**Returns:**
com.aspose.barcode.barcoderecognition.ImageScalingMode
### getInverseImage() {#getInverseImage--}
```
public InverseImageMode getInverseImage()
```


वह मोड जो उल्टे रंगों (ल्यूमिनेंस) वाली छवियों पर बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है।

मान: उल्टे रंगों वाली छवियों पर बारकोड की अतिरिक्त मान्यता

**Returns:**
[InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode)
### getMaxQuality() {#getMaxQuality--}
```
public static QualitySettings getMaxQuality()
```


MaxQuality मान्यता गुणवत्ता प्रीसेट। यह प्रीसेट सभी संभावित बारकोड, यहाँ तक कि गलत बारकोड को पहचानने के लिए विकसित किया गया है।

--------------------

> ```
> This sample shows how to use MaxQuality mode
>   
> 
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getMaxQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

मान: MaxQuality मान्यता गुणवत्ता प्रीसेट।

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getMinimalXDimension() {#getMinimalXDimension--}
```
public float getMinimalXDimension()
```


UseMinimalXDimension के साथ उपयोग किए जाने वाले XDimension का न्यूनतम आकार पिक्सेल में।

मान: XDimension का न्यूनतम आकार पिक्सेल में, जो UseMinimalXDimension के साथ उपयोग किया जाता है।

**Returns:**
float
### getNormalQuality() {#getNormalQuality--}
```
public static QualitySettings getNormalQuality()
```


NormalQuality मान्यता गुणवत्ता प्रीसेट। अधिकांश बारकोड के लिए उपयुक्त

--------------------

> ```
> This sample shows how to use NormalQuality mode
>   
>   BarCodeReader reader = new BarCodeReader("c:\\test.png", DecodeType.CODE_39_EXTENDED, DecodeType.CODE_128);
>   {
>       reader.setQualitySettings(QualitySettings.getNormalQuality());
>       for(BarCodeResult result : reader.readBarCodes())
>           System.out.println(result.getCodeText());
>   }
> ```

मान: NormalQuality मान्यता गुणवत्ता प्रीसेट।

**Returns:**
[QualitySettings](../../com.aspose.barcode.barcoderecognition/qualitysettings)
### getXDimension() {#getXDimension--}
```
public XDimensionMode getXDimension()
```


पहचान मोड जो बारकोड के न्यूनतम तत्व का आकार (1 से अनंत तक) निर्धारित करता है: मैट्रिक्स सेल या बार।

मान: बारकोड के न्यूनतम तत्व का आकार (1 से अनंत तक): मैट्रिक्स सेल या बार।

**Returns:**
[XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAllowIncorrectBarcodes(boolean value) {#setAllowIncorrectBarcodes-boolean-}
```
public void setAllowIncorrectBarcodes(boolean value)
```


इंजन को उन बारकोड को पहचानने की अनुमति देता है जिनका चेकसम या मान गलत है। इस मोड का उपयोग गलत टेक्स्ट वाले क्षतिग्रस्त बारकोड को पहचानने के लिए किया जा सकता है।

मान: इंजन को गलत बारकोड को पहचानने की अनुमति देता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setBarcodeQuality(BarcodeQualityMode value) {#setBarcodeQuality-com.aspose.barcode.barcoderecognition.BarcodeQualityMode-}
```
public void setBarcodeQuality(BarcodeQualityMode value)
```


वह मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने के लिए विधियों को सक्षम करता है। कम गुणवत्ता वाले बारकोड तत्व को अधिक कठिन विधियों की आवश्यकता होती है जिससे पहचान धीमी हो जाती है।

मान: वह मोड जो चयनित गुणवत्ता के साथ बारकोड तत्वों को पहचानने के लिए विधियों को सक्षम करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [BarcodeQualityMode](../../com.aspose.barcode.barcoderecognition/barcodequalitymode) |  |

### setComplexBackground(ComplexBackgroundMode value) {#setComplexBackground-com.aspose.barcode.barcoderecognition.ComplexBackgroundMode-}
```
public void setComplexBackground(ComplexBackgroundMode value)
```


वह मोड जो रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है।

मान: रंगीन छवियों पर रंगीन बारकोड की अतिरिक्त पहचान।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [ComplexBackgroundMode](../../com.aspose.barcode.barcoderecognition/complexbackgroundmode) |  |

### setDeconvolution(DeconvolutionMode value) {#setDeconvolution-com.aspose.barcode.barcoderecognition.DeconvolutionMode-}
```
public void setDeconvolution(DeconvolutionMode value)
```


Deconvolution (image restorations) मोड जो छवि क्षय के स्तर को निर्धारित करता है। मूल रूप से डिकन्वॉल्यूशन एक फ़ंक्शन है जो कैमरा द्वारा छवि प्राप्त करने के दौरान ब्लर जैसी किसी भी प्राकृतिक फ़ंक्शन द्वारा क्षतिग्रस्त (कन्वॉल्यूटेड) छवि को पुनर्स्थापित कर सकता है। क्योंकि हम उस छवि फ़ंक्शन का पता नहीं लगा सकते जो छवि को भ्रष्ट करता है, हमें सबसे ज्ञात फ़ंक्शनों जैसे शार्प या गणितीय मॉर्फ़ोलॉजी की जाँच करनी पड़ती है।

मान: Deconvolution मोड जो छवि क्षय के स्तर को निर्धारित करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [DeconvolutionMode](../../com.aspose.barcode.barcoderecognition/deconvolutionmode) |  |

### setImageScalingMode(ImageScalingMode value) {#setImageScalingMode-com.aspose.barcode.barcoderecognition.ImageScalingMode-}
```
public void setImageScalingMode(ImageScalingMode value)
```


विशिष्ट ImageScaleMode मान के साथ छवि को स्केल करने की अनुमति देता है:

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | com.aspose.barcode.barcoderecognition.ImageScalingMode | ImageScalingMode मान |

### setInverseImage(InverseImageMode value) {#setInverseImage-com.aspose.barcode.barcoderecognition.InverseImageMode-}
```
public void setInverseImage(InverseImageMode value)
```


वह मोड जो उल्टे रंगों (ल्यूमिनेंस) वाली छवियों पर बारकोड की अतिरिक्त पहचान को सक्षम या अक्षम करता है।

मान: उल्टे रंगों वाली छवियों पर बारकोड की अतिरिक्त मान्यता

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [InverseImageMode](../../com.aspose.barcode.barcoderecognition/inverseimagemode) |  |

### setMinimalXDimension(float value) {#setMinimalXDimension-float-}
```
public void setMinimalXDimension(float value)
```


UseMinimalXDimension के साथ उपयोग किए जाने वाले XDimension का न्यूनतम आकार पिक्सेल में।

मान: XDimension का न्यूनतम आकार पिक्सेल में, जो UseMinimalXDimension के साथ उपयोग किया जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### setXDimension(XDimensionMode value) {#setXDimension-com.aspose.barcode.barcoderecognition.XDimensionMode-}
```
public void setXDimension(XDimensionMode value)
```


पहचान मोड जो बारकोड के न्यूनतम तत्व का आकार (1 से अनंत तक) निर्धारित करता है: मैट्रिक्स सेल या बार।

मान: बारकोड के न्यूनतम तत्व का आकार (1 से अनंत तक): मैट्रिक्स सेल या बार।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [XDimensionMode](../../com.aspose.barcode.barcoderecognition/xdimensionmode) |  |

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

### writeToParcel(Parcel dest, int flags) {#writeToParcel-android.os.Parcel-int-}
```
public void writeToParcel(Parcel dest, int flags)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| dest | android.os.Parcel |  |
| flags | int |  |

