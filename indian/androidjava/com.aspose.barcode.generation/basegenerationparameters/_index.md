---
title: "BaseGenerationParameters"
second_title: "Aspose.BarCode के लिए Android via Java API संदर्भ"
description: "बारकोड इमेज जनरेशन पैरामीटर।"
type: docs
weight: 17
url: /hi/androidjava/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

बारकोड इमेज जनरेशन पैरामीटर।
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | स्वचालित आकार मोड के विभिन्न प्रकार निर्दिष्ट करता है। |
| [getBackColor()](#getBackColor--) | बारकोड छवि की पृष्ठभूमि रंग। |
| [getBarcode()](#getBarcode--) | BarcodeParameters प्राप्त करता है जो सभी बारकोड गुणों को सम्मिलित करता है। |
| [getBorder()](#getBorder--) | BorderParameters प्राप्त करता है जो बारकोड बॉर्डर के सभी विन्यास गुणों को सम्मिलित करता है। |
| [getCaptionAbove()](#getCaptionAbove--) | बारकोड छवि के ऊपर कैप्शन। |
| [getCaptionBelow()](#getCaptionBelow--) | बारकोड छवि के नीचे कैप्शन। |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | छवि पैरामीटर। |
| [getImageHeight()](#getImageHeight--) | जब AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट हो, तब बारकोड छवि की ऊँचाई। |
| [getImageWidth()](#getImageWidth--) | जब AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट हो, तब बारकोड छवि की चौड़ाई। |
| [getResolution()](#getResolution--) | बारकोड छवि का रिज़ॉल्यूशन प्राप्त करता है। |
| [getRotationAngle()](#getRotationAngle--) | बारकोड छवि का घूर्णन कोण, डिग्री में मापा गया, उदाहरण के लिए। |
| [getUseAntiAlias()](#getUseAntiAlias--) | छवि को रेंडर करने के लिए एंटी-एलियासिंग मोड उपयोग किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | स्वचालित आकार मोड के विभिन्न प्रकार निर्दिष्ट करता है। |
| [setBackColor(int value)](#setBackColor-int-) | बारकोड छवि की पृष्ठभूमि रंग। |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | जब AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट हो, तब बारकोड छवि की ऊँचाई। |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | जब AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट हो, तब बारकोड छवि की चौड़ाई। |
| [setResolution(float value)](#setResolution-float-) | बारकोड छवि का रिज़ॉल्यूशन सेट करता है। |
| [setRotationAngle(float value)](#setRotationAngle-float-) | बारकोड छवि का घूर्णन कोण, डिग्री में मापा गया, उदाहरण के लिए। |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | छवि को रेंडर करने के लिए एंटी-एलियासिंग मोड उपयोग किया गया है या नहीं, यह दर्शाने वाला मान सेट करता है। |
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
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


स्वचालित आकार मोड के विभिन्न प्रकार निर्दिष्ट करता है। डिफ़ॉल्ट मान: AutoSizeMode.NONE।

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public int getBackColor()
```


बारकोड छवि की पृष्ठभूमि रंग। डिफ़ॉल्ट मान: Color.White। देखें Color।

**Returns:**
int
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


BarcodeParameters प्राप्त करता है जो सभी बारकोड गुणों को सम्मिलित करता है।

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


BorderParameters प्राप्त करता है जो बारकोड बॉर्डर के सभी विन्यास गुणों को सम्मिलित करता है।

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


बारकोड छवि के ऊपर कैप्शन। देखें CaptionParameters।

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


बारकोड छवि के नीचे कैप्शन। देखें CaptionParameters।

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getImage() {#getImage--}
```
public ImageParameters getImage()
```


छवि पैरामीटर। देखें।

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


जब AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट हो, तब बारकोड छवि की ऊँचाई।

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


जब AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट हो, तब बारकोड छवि की चौड़ाई।

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


बारकोड छवि का रिज़ॉल्यूशन प्राप्त करता है। दोनों आयामों के लिए एक मान। डिफ़ॉल्ट मान: 96 dpi।

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


बारकोड छवि का घूर्णन कोण, डिग्री में मापा गया, उदाहरण के लिए RotationAngle = 0 या RotationAngle = 360 का अर्थ कोई घूर्णन नहीं है। यदि RotationAngle 90, 180, 270 या 0 के बराबर नहीं है, तो यह स्कैनर के लिए छवि पढ़ना कठिन बना सकता है। डिफ़ॉल्ट मान: 0।

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Returns:**
float
### getUseAntiAlias() {#getUseAntiAlias--}
```
public boolean getUseAntiAlias()
```


छवि को रेंडर करने के लिए एंटी-एलियासिंग मोड उपयोग किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है।

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setAutoSizeMode(AutoSizeMode value) {#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-}
```
public void setAutoSizeMode(AutoSizeMode value)
```


स्वचालित आकार मोड के विभिन्न प्रकार निर्दिष्ट करता है। डिफ़ॉल्ट मान: AutoSizeMode.NONE।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(int value) {#setBackColor-int-}
```
public void setBackColor(int value)
```


बारकोड छवि की पृष्ठभूमि रंग। डिफ़ॉल्ट मान: Color.White। देखें Color।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


जब AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट हो, तब बारकोड छवि की ऊँचाई।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


जब AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट हो, तब बारकोड छवि की चौड़ाई।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


बारकोड छवि का रिज़ॉल्यूशन सेट करता है। दोनों आयामों के लिए एक मान। डिफ़ॉल्ट मान: 96 dpi।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


बारकोड छवि का घूर्णन कोण, डिग्री में मापा गया, उदाहरण के लिए RotationAngle = 0 या RotationAngle = 360 का अर्थ कोई घूर्णन नहीं है। यदि RotationAngle 90, 180, 270 या 0 के बराबर नहीं है, तो यह स्कैनर के लिए छवि पढ़ना कठिन बना सकता है। डिफ़ॉल्ट मान: 0।

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


छवि को रेंडर करने के लिए एंटी-एलियासिंग मोड उपयोग किया गया है या नहीं, यह दर्शाने वाला मान सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean |  |

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

