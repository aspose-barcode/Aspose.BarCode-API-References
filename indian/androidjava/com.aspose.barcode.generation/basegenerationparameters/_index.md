---
title: BaseGenerationParameters
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: बारकोड छवि निर्माण पैरामीटर।
type: docs
weight: 17
url: /hi/androidjava/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

बारकोड छवि निर्माण पैरामीटर।
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | स्वचालित आकार निर्धारण मोड के विभिन्न प्रकारों को निर्दिष्ट करता है। |
| [getBackColor()](#getBackColor--) | बारकोड छवि का पृष्ठभूमि रंग। |
| [getBarcode()](#getBarcode--) | बारकोड के सभी गुणों को शामिल करने वाले  BarcodeParameters  प्राप्त करता है। |
| [getBorder()](#getBorder--) | बारकोड बॉर्डर के लिए सभी कॉन्फ़िगरेशन गुणों को शामिल करने वाले  BorderParameters  प्राप्त करता है। |
| [getCaptionAbove()](#getCaptionAbove--) | BarCode छवि के ऊपर कैप्शन। |
| [getCaptionBelow()](#getCaptionBelow--) | BarCode छवि के नीचे कैप्शन। |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | छवि पैरामीटर। |
| [getImageHeight()](#getImageHeight--) | BarCode छवि की ऊँचाई जब AutoSizeMode प्रॉपर्टी को AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट किया जाता है। |
| [getImageWidth()](#getImageWidth--) | BarCode छवि की चौड़ाई जब AutoSizeMode प्रॉपर्टी को AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट किया जाता है। |
| [getResolution()](#getResolution--) | BarCode छवि का रिज़ॉल्यूशन प्राप्त करता है। |
| [getRotationAngle()](#getRotationAngle--) | BarCode छवि का घूर्णन कोण, डिग्री में मापा गया, उदाहरण के लिए। |
| [getUseAntiAlias()](#getUseAntiAlias--) | छवि को रेंडर करने के लिए anti-aliasing मोड उपयोग किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | स्वचालित आकार निर्धारण मोड के विभिन्न प्रकारों को निर्दिष्ट करता है। |
| [setBackColor(int value)](#setBackColor-int-) | बारकोड छवि का पृष्ठभूमि रंग। |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | BarCode छवि की ऊँचाई जब AutoSizeMode प्रॉपर्टी को AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट किया जाता है। |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | BarCode छवि की चौड़ाई जब AutoSizeMode प्रॉपर्टी को AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट किया जाता है। |
| [setResolution(float value)](#setResolution-float-) | BarCode छवि का रिज़ॉल्यूशन सेट करता है। |
| [setRotationAngle(float value)](#setRotationAngle-float-) | BarCode छवि का घूर्णन कोण, डिग्री में मापा गया, उदाहरण के लिए। |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | छवि को रेंडर करने के लिए anti-aliasing मोड उपयोग किया गया है या नहीं, यह दर्शाने वाला मान सेट करता है। |
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


ऑटोमैटिक साइजिंग मोड के विभिन्न प्रकार निर्दिष्ट करता है। डिफ़ॉल्ट मान: AutoSizeMode.NONE।

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public int getBackColor()
```


बारकोड छवि का बैकग्राउंड रंग। डिफ़ॉल्ट मान: Color.White। देखें Color।

**Returns:**
int
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


बारकोड के सभी गुणों को शामिल करने वाले  BarcodeParameters  प्राप्त करता है।

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


बारकोड बॉर्डर के लिए सभी कॉन्फ़िगरेशन गुणों को शामिल करने वाले  BorderParameters  प्राप्त करता है।

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


BarCode छवि के ऊपर कैप्शन। देखें CaptionParameters।

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


BarCode छवि के नीचे कैप्शन। देखें CaptionParameters।

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


BarCode छवि की ऊँचाई जब AutoSizeMode प्रॉपर्टी को AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट किया जाता है।

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


BarCode छवि की चौड़ाई जब AutoSizeMode प्रॉपर्टी को AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट किया जाता है।

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


BarCode छवि का रिज़ॉल्यूशन प्राप्त करता है। दोनों आयामों के लिए एक ही मान। डिफ़ॉल्ट मान: 96 dpi।

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


BarCode छवि का घूर्णन कोण, डिग्री में मापा गया, उदाहरण के लिए RotationAngle = 0 या RotationAngle = 360 का अर्थ कोई घूर्णन नहीं है। यदि RotationAngle 90, 180, 270 या 0 के बराबर नहीं है, तो यह स्कैनर के लिए छवि पढ़ना कठिन बना सकता है। डिफ़ॉल्ट मान: 0।

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


छवि को रेंडर करने के लिए anti-aliasing मोड उपयोग किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है।

**Returns:**
boolean
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




### setAutoSizeMode(AutoSizeMode value) {#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-}
```
public void setAutoSizeMode(AutoSizeMode value)
```


ऑटोमैटिक साइजिंग मोड के विभिन्न प्रकार निर्दिष्ट करता है। डिफ़ॉल्ट मान: AutoSizeMode.NONE।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(int value) {#setBackColor-int-}
```
public void setBackColor(int value)
```


बारकोड छवि का बैकग्राउंड रंग। डिफ़ॉल्ट मान: Color.White। देखें Color।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


BarCode छवि की ऊँचाई जब AutoSizeMode प्रॉपर्टी को AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट किया जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


BarCode छवि की चौड़ाई जब AutoSizeMode प्रॉपर्टी को AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट किया जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


BarCode छवि का रिज़ॉल्यूशन सेट करता है। दोनों आयामों के लिए एक ही मान। डिफ़ॉल्ट मान: 96 dpi।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


BarCode छवि का घूर्णन कोण, डिग्री में मापा गया, उदाहरण के लिए RotationAngle = 0 या RotationAngle = 360 का अर्थ कोई घूर्णन नहीं है। यदि RotationAngle 90, 180, 270 या 0 के बराबर नहीं है, तो यह स्कैनर के लिए छवि पढ़ना कठिन बना सकता है। डिफ़ॉल्ट मान: 0।

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


छवि को रेंडर करने के लिए anti-aliasing मोड उपयोग किया गया है या नहीं, यह दर्शाने वाला मान सेट करता है।

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

