---
title: "SecondaryAndAdditionalData"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "HIBC LIC द्वितीयक और अतिरिक्त डेटा संग्रहीत करने के लिए क्लास।"
type: docs
weight: 34
url: /hi/java/com.aspose.barcode.complexbarcode/secondaryandadditionaldata/
---
**Inheritance:**
java.lang.Object
```
public class SecondaryAndAdditionalData
```

HIBC LIC द्वितीयक और अतिरिक्त डेटा संग्रहीत करने के लिए क्लास।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [SecondaryAndAdditionalData()](#SecondaryAndAdditionalData--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट SecondaryAndAdditionalData मान के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getDateOfManufacture()](#getDateOfManufacture--) | निर्माण तिथि की पहचान करता है। |
| [getExpiryDate()](#getExpiryDate--) | समाप्ति तिथि की पहचान करता है। |
| [getExpiryDateFormat()](#getExpiryDateFormat--) | समाप्ति तिथि के प्रारूप की पहचान करता है। |
| [getLotNumber()](#getLotNumber--) | लॉट या बैच नंबर की पहचान करता है। |
| [getQuantity()](#getQuantity--) | मात्रा की पहचान करता है, जो 0 से 500 के बीच पूर्णांक मान होना चाहिए। |
| [getSerialNumber()](#getSerialNumber--) | सीरियल नंबर की पहचान करता है। |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String secondaryDataCodetext)](#parseFromString-java.lang.String-) | HIBC LIC विनिर्देश के अनुसार स्ट्रिंग प्रारूप से द्वितीयक और अतिरिक्त पूरक डेटा को इंस्टैंसिएट करता है। |
| [setDateOfManufacture(LocalDateTime value)](#setDateOfManufacture-java.time.LocalDateTime-) | निर्माण तिथि की पहचान करता है। |
| [setExpiryDate(LocalDateTime value)](#setExpiryDate-java.time.LocalDateTime-) | समाप्ति तिथि की पहचान करता है। |
| [setExpiryDateFormat(HIBCLICDateFormat value)](#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-) | समाप्ति तिथि के प्रारूप की पहचान करता है। |
| [setLotNumber(String value)](#setLotNumber-java.lang.String-) | लॉट या बैच नंबर की पहचान करता है। |
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


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट SecondaryAndAdditionalData मान के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस इंस्टेंस की तुलना के लिए एक  SecondaryAndAdditionalData  मान। |

**Returns:**
boolean -  **true**  यदि obj का मान इस इंस्टेंस के समान है; अन्यथा,  **false** ।
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


निर्माण तिथि की पहचान करता है। इस फ़ील्ड का उपयोग न करने के लिए निर्माण तिथि को DateTime.MinValue पर सेट किया जा सकता है। डिफ़ॉल्ट मान: DateTime.MinValue

**Returns:**
java.time.LocalDateTime
### getExpiryDate() {#getExpiryDate--}
```
public LocalDateTime getExpiryDate()
```


समाप्ति तिथि की पहचान करता है। यदि ExpiryDateFormat को None पर सेट नहीं किया गया है तो इसका उपयोग किया जाएगा।

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


लॉट या बैच नंबर की पहचान करता है। लॉट/बैच नंबर को 18 प्रतीकों की अधिकतम लंबाई वाला अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।

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


सीरियल नंबर की पहचान करता है। सीरियल नंबर को 18 प्रतीकों की अधिकतम लंबाई वाला अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस इंस्टेंस के लिए हैश कोड लौटाता है।

**Returns:**
int - 32-बिट साइन्ड इंटीजर हैश कोड।
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


HIBC LIC विनिर्देश के अनुसार स्ट्रिंग प्रारूप से द्वितीयक और अतिरिक्त पूरक डेटा को इंस्टैंसिएट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| secondaryDataCodetext | java.lang.String | फ़ॉर्मेटेड स्ट्रिंग। |

### setDateOfManufacture(LocalDateTime value) {#setDateOfManufacture-java.time.LocalDateTime-}
```
public void setDateOfManufacture(LocalDateTime value)
```


निर्माण तिथि की पहचान करता है। इस फ़ील्ड का उपयोग न करने के लिए निर्माण तिथि को DateTime.MinValue पर सेट किया जा सकता है। डिफ़ॉल्ट मान: DateTime.MinValue

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.time.LocalDateTime |  |

### setExpiryDate(LocalDateTime value) {#setExpiryDate-java.time.LocalDateTime-}
```
public void setExpiryDate(LocalDateTime value)
```


समाप्ति तिथि की पहचान करता है। यदि ExpiryDateFormat को None पर सेट नहीं किया गया है तो इसका उपयोग किया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.time.LocalDateTime |  |

### setExpiryDateFormat(HIBCLICDateFormat value) {#setExpiryDateFormat-com.aspose.barcode.complexbarcode.HIBCLICDateFormat-}
```
public void setExpiryDateFormat(HIBCLICDateFormat value)
```


समाप्ति तिथि के प्रारूप की पहचान करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [HIBCLICDateFormat](../../com.aspose.barcode.complexbarcode/hibclicdateformat) |  |

### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public void setLotNumber(String value)
```


लॉट या बैच नंबर की पहचान करता है। लॉट/बैच नंबर को 18 प्रतीकों की अधिकतम लंबाई वाला अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setQuantity(int value) {#setQuantity-int-}
```
public void setQuantity(int value)
```


मात्रा की पहचान करता है, जो 0 से 500 के बीच पूर्णांक मान होना चाहिए। इस फ़ील्ड का उपयोग न करने के लिए मात्रा को -1 पर सेट किया जा सकता है। डिफ़ॉल्ट मान: -1

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public void setSerialNumber(String value)
```


सीरियल नंबर की पहचान करता है। सीरियल नंबर को 18 प्रतीकों की अधिकतम लंबाई वाला अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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

