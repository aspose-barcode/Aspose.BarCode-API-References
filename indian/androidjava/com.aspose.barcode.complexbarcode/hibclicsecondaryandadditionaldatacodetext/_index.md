---
title: HIBCLICSecondaryAndAdditionalDataCodetext
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: HIBC LIC कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास जो द्वितीयक डेटा संग्रहीत करता है।
type: docs
weight: 17
url: /hi/androidjava/com.aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext)
```
public class HIBCLICSecondaryAndAdditionalDataCodetext extends HIBCLICComplexCodetext
```

HIBC LIC कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास जो द्वितीयक डेटा संग्रहीत करता है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [HIBCLICSecondaryAndAdditionalDataCodetext()](#HIBCLICSecondaryAndAdditionalDataCodetext--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | यह दर्शाने वाला मान लौटाता है कि यह इंस्टेंस निर्दिष्ट HIBCLICSecondaryAndAdditionalDataCodetext मान के बराबर है या नहीं। |
| [getBarcodeType()](#getBarcodeType--) | बारकोड प्रकार को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | कोडटेक्स्ट बनाता है। |
| [getData()](#getData--) | द्वितीयक और अतिरिक्त पूरक डेटा की पहचान करता है। |
| [getLinkCharacter()](#getLinkCharacter--) | लिंक कैरेक्टर की पहचान करता है। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | निर्मित कोडटेक्स्ट से इंस्टेंस को प्रारंभ करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBarcodeType(BaseEncodeType value)](#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-) | बारकोड प्रकार को प्राप्त करता है या सेट करता है। |
| [setData(SecondaryAndAdditionalData value)](#setData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-) | द्वितीयक और अतिरिक्त पूरक डेटा की पहचान करता है। |
| [setLinkCharacter(char value)](#setLinkCharacter-char-) | लिंक कैरेक्टर की पहचान करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HIBCLICSecondaryAndAdditionalDataCodetext() {#HIBCLICSecondaryAndAdditionalDataCodetext--}
```
public HIBCLICSecondaryAndAdditionalDataCodetext()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


यह दर्शाने वाला मान लौटाता है कि यह इंस्टेंस निर्दिष्ट HIBCLICSecondaryAndAdditionalDataCodetext मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | एक HIBCLICSecondaryAndAdditionalDataCodetext मान इस उदाहरण से तुलना करने के लिए। |

**Returns:**
boolean -  **true**  यदि obj का मान इस उदाहरण के समान है; अन्यथा,  **false** .
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


बारकोड प्रकार को प्राप्त करता है या सेट करता है। HIBC LIC कोडटेक्स्ट को HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC और HIBCQRLIC एन्कोड प्रकारों का उपयोग करके एन्कोड किया जा सकता है। डिफ़ॉल्ट मान: HIBCCode39LIC.

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


कोडटेक्स्ट बनाता है।

**Returns:**
java.lang.String - निर्मित कोडटेक्स्ट
### getData() {#getData--}
```
public SecondaryAndAdditionalData getData()
```


द्वितीयक और अतिरिक्त पूरक डेटा की पहचान करता है।

**Returns:**
[SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata)
### getLinkCharacter() {#getLinkCharacter--}
```
public char getLinkCharacter()
```


लिंक कैरेक्टर की पहचान करता है।

**Returns:**
char
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:**
int - एक 32-बिट साइन्ड इंटेजर हैश कोड।
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


निर्मित कोडटेक्स्ट से इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| constructedCodetext | java.lang.String | निर्मित कोडटेक्स्ट। |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBarcodeType(BaseEncodeType value) {#setBarcodeType-com.aspose.barcode.generation.BaseEncodeType-}
```
public void setBarcodeType(BaseEncodeType value)
```


बारकोड प्रकार को प्राप्त करता है या सेट करता है। HIBC LIC कोडटेक्स्ट को HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC और HIBCQRLIC एन्कोड प्रकारों का उपयोग करके एन्कोड किया जा सकता है। डिफ़ॉल्ट मान: HIBCCode39LIC.

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setData(SecondaryAndAdditionalData value) {#setData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-}
```
public void setData(SecondaryAndAdditionalData value)
```


द्वितीयक और अतिरिक्त पूरक डेटा की पहचान करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata) |  |

### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public void setLinkCharacter(char value)
```


लिंक कैरेक्टर की पहचान करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | char |  |

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

