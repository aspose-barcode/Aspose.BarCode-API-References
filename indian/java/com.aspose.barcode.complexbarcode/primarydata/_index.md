---
title: "PrimaryData"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "HIBC LIC प्राथमिक डेटा संग्रहीत करने के लिए क्लास।"
type: docs
weight: 33
url: /hi/java/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

HIBC LIC प्राथमिक डेटा संग्रहीत करने के लिए क्लास।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट  PrimaryData  मान के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | लेबलर पहचान कोड की तिथि की पहचान करता है। |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | उत्पाद या कैटलॉग नंबर की पहचान करता है। |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | माप इकाई ID की पहचान करता है। |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | HIBC LIC विनिर्देश के अनुसार स्ट्रिंग प्रारूप से प्राइमरी डेटा को इंस्टैंसिएट करता है। |
| [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | लेबलर पहचान कोड की तिथि की पहचान करता है। |
| [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | उत्पाद या कैटलॉग नंबर की पहचान करता है। |
| [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | माप इकाई ID की पहचान करता है। |
| [toString()](#toString--) | डेटा को HIBC LIC विनिर्देश के अनुसार स्ट्रिंग प्रारूप में परिवर्तित करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrimaryData() {#PrimaryData--}
```
public PrimaryData()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


एक मान लौटाता है जो दर्शाता है कि यह इंस्टेंस निर्दिष्ट  PrimaryData  मान के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस इंस्टेंस की तुलना के लिए एक  PrimaryData  मान। |

**Returns:**
boolean -  **true**  यदि obj का मान इस इंस्टेंस के समान है; अन्यथा,  **false** ।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public String getLabelerIdentificationCode()
```


लेबलर पहचान कोड की तिथि की पहचान करता है। लेबलर पहचान कोड 4 अक्षरों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए, जिसमें पहला अक्षर हमेशा वर्णात्मक होना चाहिए।

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


उत्पाद या कैटलॉग नंबर की पहचान करता है। उत्पाद या कैटलॉग नंबर अधिकतम 18 अक्षरों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।

**Returns:**
java.lang.String
### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public int getUnitOfMeasureID()
```


माप इकाई ID की पहचान करता है। माप इकाई ID 0 से 9 के बीच का पूर्णांक मान होना चाहिए।

**Returns:**
int
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




### parseFromString(String primaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String primaryDataCodetext)
```


HIBC LIC विनिर्देश के अनुसार स्ट्रिंग प्रारूप से प्राइमरी डेटा को इंस्टैंसिएट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | फ़ॉर्मेटेड स्ट्रिंग। |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


लेबलर पहचान कोड की तिथि की पहचान करता है। लेबलर पहचान कोड 4 अक्षरों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए, जिसमें पहला अक्षर हमेशा वर्णात्मक होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


उत्पाद या कैटलॉग नंबर की पहचान करता है। उत्पाद या कैटलॉग नंबर अधिकतम 18 अक्षरों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


माप इकाई ID की पहचान करता है। माप इकाई ID 0 से 9 के बीच का पूर्णांक मान होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

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

