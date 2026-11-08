---
title: "BaseGenerationParameters"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "बारकोड इमेज जनरेशन पैरामीटर."
type: docs
weight: 17
url: /hi/java/com.aspose.barcode.generation/basegenerationparameters/
---
**Inheritance:**
java.lang.Object
```
public class BaseGenerationParameters
```

बारकोड इमेज जनरेशन पैरामीटर.
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAutoSizeMode()](#getAutoSizeMode--) | स्वचालित आकार मोड के विभिन्न प्रकार निर्दिष्ट करता है। |
| [getBackColor()](#getBackColor--) | बारकोड इमेज का बैकग्राउंड रंग। |
| [getBarcode()](#getBarcode--) | सभी बारकोड गुणों को शामिल करने वाले BarcodeParameters को प्राप्त करता है। |
| [getBorder()](#getBorder--) | बारकोड बॉर्डर के सभी कॉन्फ़िगरेशन गुणों को शामिल करने वाले BorderParameters को प्राप्त करता है। |
| [getCaptionAbove()](#getCaptionAbove--) | BarCode इमेज के ऊपर कैप्शन। |
| [getCaptionBelow()](#getCaptionBelow--) | BarCode छवि के नीचे कैप्शन। |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | इमेज पैरामीटर। |
| [getImageHeight()](#getImageHeight--) | जब AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट हो, तो BarCode छवि की ऊँचाई। |
| [getImageWidth()](#getImageWidth--) | जब AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट हो, तो BarCode छवि की चौड़ाई। |
| [getResolution()](#getResolution--) | BarCode इमेज का रिज़ॉल्यूशन प्राप्त करता है। |
| [getRotationAngle()](#getRotationAngle--) | BarCode इमेज का घूर्णन कोण, डिग्री में मापा जाता है, जैसे कि। |
| [getUseAntiAlias()](#getUseAntiAlias--) | छवि रेंडर करने के लिए एंटी-एलियासिंग मोड का उपयोग किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAutoSizeMode(AutoSizeMode value)](#setAutoSizeMode-com.aspose.barcode.generation.AutoSizeMode-) | स्वचालित आकार मोड के विभिन्न प्रकार निर्दिष्ट करता है। |
| [setBackColor(Color value)](#setBackColor-java.awt.Color-) | बारकोड इमेज का बैकग्राउंड रंग। |
| [setImageHeight(Unit value)](#setImageHeight-com.aspose.barcode.generation.Unit-) | जब AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट हो, तो BarCode छवि की ऊँचाई। |
| [setImageWidth(Unit value)](#setImageWidth-com.aspose.barcode.generation.Unit-) | जब AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट हो, तो BarCode छवि की चौड़ाई। |
| [setResolution(float value)](#setResolution-float-) | BarCode इमेज का रिज़ॉल्यूशन सेट करता है। |
| [setRotationAngle(float value)](#setRotationAngle-float-) | BarCode इमेज का घूर्णन कोण, डिग्री में मापा जाता है, जैसे कि। |
| [setUseAntiAlias(boolean value)](#setUseAntiAlias-boolean-) | एक मान सेट करता है जो यह दर्शाता है कि इमेज रेंडर करने के लिए एंटी-एलियासिंग मोड उपयोग किया गया है या नहीं |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAutoSizeMode() {#getAutoSizeMode--}
```
public AutoSizeMode getAutoSizeMode()
```


स्वचालित आकार निर्धारण मोड के विभिन्न प्रकार निर्दिष्ट करता है। डिफ़ॉल्ट मान: AutoSizeMode.NONE.

**Returns:**
[AutoSizeMode](../../com.aspose.barcode.generation/autosizemode)
### getBackColor() {#getBackColor--}
```
public Color getBackColor()
```


बारकोड इमेज की पृष्ठभूमि रंग। डिफ़ॉल्ट मान: Color.White। देखें Color।

**Returns:**
java.awt.Color
### getBarcode() {#getBarcode--}
```
public BarcodeParameters getBarcode()
```


सभी बारकोड गुणों को शामिल करने वाले BarcodeParameters को प्राप्त करता है।

**Returns:**
[BarcodeParameters](../../com.aspose.barcode.generation/barcodeparameters)
### getBorder() {#getBorder--}
```
public BorderParameters getBorder()
```


बारकोड बॉर्डर के सभी कॉन्फ़िगरेशन गुणों को शामिल करने वाले BorderParameters को प्राप्त करता है।

**Returns:**
[BorderParameters](../../com.aspose.barcode.generation/borderparameters)
### getCaptionAbove() {#getCaptionAbove--}
```
public CaptionParameters getCaptionAbove()
```


बारकोड इमेज के ऊपर कैप्शन। देखें CaptionParameters।

**Returns:**
[CaptionParameters](../../com.aspose.barcode.generation/captionparameters)
### getCaptionBelow() {#getCaptionBelow--}
```
public CaptionParameters getCaptionBelow()
```


बारकोड इमेज के नीचे कैप्शन। देखें CaptionParameters।

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


इमेज पैरामीटर। देखें।

**Returns:**
[ImageParameters](../../com.aspose.barcode.generation/imageparameters) - 
### getImageHeight() {#getImageHeight--}
```
public Unit getImageHeight()
```


जब AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट हो, तो BarCode छवि की ऊँचाई।

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getImageWidth() {#getImageWidth--}
```
public Unit getImageWidth()
```


जब AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट हो, तो BarCode छवि की चौड़ाई।

**Returns:**
[Unit](../../com.aspose.barcode.generation/unit)
### getResolution() {#getResolution--}
```
public float getResolution()
```


BarCode छवि की रिज़ॉल्यूशन प्राप्त करता है। दोनों आयामों के लिए एक मान। डिफ़ॉल्ट मान: 96 dpi।

**Returns:**
float
### getRotationAngle() {#getRotationAngle--}
```
public float getRotationAngle()
```


बारकोड इमेज का घूर्णन कोण, डिग्री में मापा जाता है, उदाहरण के लिए RotationAngle = 0 या RotationAngle = 360 का अर्थ कोई घूर्णन नहीं है। यदि RotationAngle 90, 180, 270 या 0 के बराबर नहीं है, तो यह स्कैनर के लिए इमेज पढ़ना कठिन बना सकता है। डिफ़ॉल्ट मान: 0.

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


छवि रेंडर करने के लिए एंटी-एलियासिंग मोड का उपयोग किया गया है या नहीं, यह दर्शाने वाला मान प्राप्त करता है।

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


स्वचालित आकार निर्धारण मोड के विभिन्न प्रकार निर्दिष्ट करता है। डिफ़ॉल्ट मान: AutoSizeMode.NONE.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [AutoSizeMode](../../com.aspose.barcode.generation/autosizemode) |  |

### setBackColor(Color value) {#setBackColor-java.awt.Color-}
```
public void setBackColor(Color value)
```


बारकोड इमेज की पृष्ठभूमि रंग। डिफ़ॉल्ट मान: Color.White। देखें Color।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.awt.Color |  |

### setImageHeight(Unit value) {#setImageHeight-com.aspose.barcode.generation.Unit-}
```
public void setImageHeight(Unit value)
```


जब AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट हो, तो BarCode छवि की ऊँचाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setImageWidth(Unit value) {#setImageWidth-com.aspose.barcode.generation.Unit-}
```
public void setImageWidth(Unit value)
```


जब AutoSizeMode प्रॉपर्टी AutoSizeMode.NEAREST या AutoSizeMode.INTERPOLATION पर सेट हो, तो BarCode छवि की चौड़ाई।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Unit](../../com.aspose.barcode.generation/unit) |  |

### setResolution(float value) {#setResolution-float-}
```
public void setResolution(float value)
```


BarCode छवि की रिज़ॉल्यूशन सेट करता है। दोनों आयामों के लिए एक ही मान। डिफ़ॉल्ट मान: 96 dpi।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public void setRotationAngle(float value)
```


बारकोड इमेज का घूर्णन कोण, डिग्री में मापा जाता है, उदाहरण के लिए RotationAngle = 0 या RotationAngle = 360 का अर्थ कोई घूर्णन नहीं है। यदि RotationAngle 90, 180, 270 या 0 के बराबर नहीं है, तो यह स्कैनर के लिए इमेज पढ़ना कठिन बना सकता है। डिफ़ॉल्ट मान: 0.

--------------------

> ```
> This sample shows how to create and save a BarCode image.
>   
>  	  BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.DATA_MATRIX);
>  	  generator.getParameters().setRotationAngle(7f);
>     generator.save("test.png");
> ```

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float |  |

### setUseAntiAlias(boolean value) {#setUseAntiAlias-boolean-}
```
public void setUseAntiAlias(boolean value)
```


एक मान सेट करता है जो यह दर्शाता है कि इमेज रेंडर करने के लिए एंटी-एलियासिंग मोड उपयोग किया गया है या नहीं

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
public final native void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

