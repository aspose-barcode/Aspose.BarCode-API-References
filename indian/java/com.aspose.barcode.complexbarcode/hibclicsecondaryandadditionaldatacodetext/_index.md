---
title: "HIBCLICSecondaryAndAdditionalDataCodetext"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "द्वितीयक डेटा संग्रहीत करने वाले HIBC LIC कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।"
type: docs
weight: 17
url: /hi/java/com.aspose.barcode.complexbarcode/hibclicsecondaryandadditionaldatacodetext/
---
**Inheritance:**
java.lang.Object, [com.aspose.barcode.complexbarcode.HIBCLICComplexCodetext](../../com.aspose.barcode.complexbarcode/hibcliccomplexcodetext)
```
public class HIBCLICSecondaryAndAdditionalDataCodetext extends HIBCLICComplexCodetext
```

द्वितीयक डेटा संग्रहीत करने वाले HIBC LIC कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [HIBCLICSecondaryAndAdditionalDataCodetext()](#HIBCLICSecondaryAndAdditionalDataCodetext--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट HIBCLICSecondaryAndAdditionalDataCodetext मान के बराबर है या नहीं। |
| [getBarcodeType()](#getBarcodeType--) | बारकोड प्रकार को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getConstructedCodetext()](#getConstructedCodetext--) | कोडटेक्स्ट बनाता है। |
| [getData()](#getData--) | द्वितीयक और अतिरिक्त पूरक डेटा की पहचान करता है। |
| [getLinkCharacter()](#getLinkCharacter--) | लिंक कैरेक्टर की पहचान करता है। |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
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


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट HIBCLICSecondaryAndAdditionalDataCodetext मान के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस इंस्टेंस से तुलना करने के लिए एक HIBCLICSecondaryAndAdditionalDataCodetext मान। |

**Returns:**
boolean -  **true**  यदि obj का मान इस इंस्टेंस के समान है; अन्यथा,  **false** ।
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


बारकोड प्रकार को प्राप्त करता है या सेट करता है। HIBC LIC कोडटेक्स्ट को HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC और HIBCQRLIC एन्कोड प्रकारों का उपयोग करके एन्कोड किया जा सकता है। डिफ़ॉल्ट मान: HIBCCode39LIC।

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


इस इंस्टेंस के लिए हैश कोड लौटाता है।

**Returns:**
int - 32-बिट साइन्ड इंटीजर हैश कोड।
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


निर्मित कोडटेक्स्ट से इंस्टेंस को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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


बारकोड प्रकार को प्राप्त करता है या सेट करता है। HIBC LIC कोडटेक्स्ट को HIBCCode39LIC, HIBCCode128LIC, HIBCAztecLIC, HIBCDataMatrixLIC और HIBCQRLIC एन्कोड प्रकारों का उपयोग करके एन्कोड किया जा सकता है। डिफ़ॉल्ट मान: HIBCCode39LIC।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) |  |

### setData(SecondaryAndAdditionalData value) {#setData-com.aspose.barcode.complexbarcode.SecondaryAndAdditionalData-}
```
public void setData(SecondaryAndAdditionalData value)
```


द्वितीयक और अतिरिक्त पूरक डेटा की पहचान करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [SecondaryAndAdditionalData](../../com.aspose.barcode.complexbarcode/secondaryandadditionaldata) |  |

### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public void setLinkCharacter(char value)
```


लिंक कैरेक्टर की पहचान करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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

