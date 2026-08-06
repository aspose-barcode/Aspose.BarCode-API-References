---
title: SecondaryAndAdditionalData
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: HIBC LIC द्वितीयक और अतिरिक्त डेटा को संग्रहीत करने के लिए क्लास।
type: docs
weight: 35
url: /hi/androidjava/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

HIBC LIC द्वितीयक और अतिरिक्त डेटा को संग्रहीत करने के लिए क्लास।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट  SecondaryAndAdditionalData  मान के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | निर्माण तिथि की पहचान करता है। |
| [getExpiryDate()](#getExpiryDate--) | समाप्ति तिथि की पहचान करता है। |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | समाप्ति तिथि के प्रारूप की पहचान करता है। |
| [getLotNumber()](#getLotNumber--) | लॉट या बैच संख्या की पहचान करता है। |
| [getQuantity()](#getQuantity--) | मात्रा की पहचान करता है, जो 0 से 500 के बीच पूर्णांक मान होना चाहिए। |
| [getSerialNumber()](#getSerialNumber--) | सीरियल नंबर की पहचान करता है। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | HIBC LIC विनिर्देश के अनुसार स्ट्रिंग प्रारूप से द्वितीयक और अतिरिक्त पूरक डेटा को इंस्टैंशिएट करता है। |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | निर्माण तिथि की पहचान करता है। |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | समाप्ति तिथि की पहचान करता है। |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | समाप्ति तिथि के प्रारूप की पहचान करता है। |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | लॉट या बैच संख्या की पहचान करता है। |
| [setQuantity(int value)](#setQuantity-int-) | मात्रा की पहचान करता है, जो 0 से 500 के बीच पूर्णांक मान होना चाहिए। |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | सीरियल नंबर की पहचान करता है। |
| [toString()](#toString--) | डेटा को HIBC LIC विनिर्देश के अनुसार स्ट्रिंग प्रारूप में परिवर्तित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SecondaryAndAdditionalData() {#SecondaryAndAdditionalData--}
```
public SecondaryAndAdditionalData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट  SecondaryAndAdditionalData  मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस उदाहरण की तुलना के लिए एक  SecondaryAndAdditionalData  मान। |

**Returns:**
boolean -  **true**  यदि obj का मान इस उदाहरण के समान है; अन्यथा,  **false** .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDateOfManufacture() {#getDateOfManufacture--}
```
public LocalDateTime getDateOfManufacture()
```


निर्माण तिथि की पहचान करता है। निर्माण तिथि को इस फ़ील्ड का उपयोग न करने के लिए DateTime.MinValue पर सेट किया जा सकता है। डिफ़ॉल्ट मान: DateTime.MinValue

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


समाप्ति तिथि की पहचान करता है। यदि ExpiryDateFormat को None पर सेट नहीं किया गया है तो यह उपयोग किया जाएगा।

**Returns:**
java.time.LocalDateTime
### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public HIBCLICDateFormat getExpiryDateFormat()
```


समाप्ति तिथि के प्रारूप की पहचान करता है।

**Returns:**
[HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat)
### getLotNumber() {#getLotNumber--}
```
public String getLotNumber()
```


लॉट या बैच संख्या की पहचान करता है। लॉट/बैच संख्या को अधिकतम 18 अक्षरों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।

**Returns:**
java.lang.String
### getQuantity() {#getQuantity--}
```
public int getQuantity()
```


मात्रा की पहचान करता है, जो 0 से 500 के बीच पूर्णांक मान होना चाहिए। इस फ़ील्ड का उपयोग न करने के लिए मात्रा को -1 पर सेट किया जा सकता है। डिफ़ॉल्ट मान: -1

**Returns:**
int
### getSerialNumber() {#getSerialNumber--}
```
public String getSerialNumber()
```


सीरियल नंबर की पहचान करता है। सीरियल नंबर को अधिकतम 18 अक्षरों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:**
int - एक 32-बिट साइन्ड इंटेजर हैश कोड।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### parseFromString(String secondaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String secondaryDataCodetext)
```


HIBC LIC विनिर्देश के अनुसार स्ट्रिंग प्रारूप से द्वितीयक और अतिरिक्त पूरक डेटा को इंस्टैंशिएट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | फ़ॉर्मेटेड स्ट्रिंग। |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


निर्माण तिथि की पहचान करता है। निर्माण तिथि को इस फ़ील्ड का उपयोग न करने के लिए DateTime.MinValue पर सेट किया जा सकता है। डिफ़ॉल्ट मान: DateTime.MinValue

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


समाप्ति तिथि की पहचान करता है। यदि ExpiryDateFormat को None पर सेट नहीं किया गया है तो यह उपयोग किया जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


समाप्ति तिथि के प्रारूप की पहचान करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


लॉट या बैच संख्या की पहचान करता है। लॉट/बैच संख्या को अधिकतम 18 अक्षरों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


मात्रा की पहचान करता है, जो 0 से 500 के बीच पूर्णांक मान होना चाहिए। इस फ़ील्ड का उपयोग न करने के लिए मात्रा को -1 पर सेट किया जा सकता है। डिफ़ॉल्ट मान: -1

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


सीरियल नंबर की पहचान करता है। सीरियल नंबर को अधिकतम 18 अक्षरों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


डेटा को HIBC LIC विनिर्देश के अनुसार स्ट्रिंग प्रारूप में परिवर्तित करता है।

**Returns:**
java.lang.String - फ़ॉर्मेटेड स्ट्रिंग।
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

