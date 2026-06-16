---
title: PrimaryData
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: HIBC LIC प्राथमिक डेटा को संग्रहीत करने के लिए क्लास।
type: docs
weight: 34
url: /hi/androidjava/com.aspose.barcode.complexbarcode/primarydata/
---
**Inheritance:**
java.lang.Object
```
public class PrimaryData
```

HIBC LIC प्राथमिक डेटा को संग्रहीत करने के लिए क्लास।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [PrimaryData()](#PrimaryData--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट  PrimaryData  मान के बराबर है या नहीं। |
| [getClass()](#getClass--) |  |
| [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | लेबलर पहचान कोड की तिथि की पहचान करता है। |
| [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | उत्पाद या कैटलॉग नंबर की पहचान करता है। |
| [getUnitOfMeasureID()](#getUnitOfMeasureID--) | माप इकाई ID की पहचान करता है। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseFromString(String primaryDataCodetext)](#parseFromString-java.lang.String-) | HIBC LIC विनिर्देशन के अनुसार स्ट्रिंग फ़ॉर्मेट से प्राथमिक डेटा को इंस्टैंसिएट करता है। |
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


एक मान लौटाता है जो दर्शाता है कि यह उदाहरण निर्दिष्ट  PrimaryData  मान के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस इंस्टेंस की तुलना के लिए एक PrimaryData मान। |

**Returns:**
boolean -  **true**  यदि obj का मान इस उदाहरण के समान है; अन्यथा,  **false** .
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


लेबलर पहचान कोड की तिथि की पहचान करता है। लेबलर पहचान कोड 4 प्रतीकों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए, जिसमें पहला अक्षर हमेशा अक्षरात्मक होना चाहिए।

**Returns:**
java.lang.String
### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public String getProductOrCatalogNumber()
```


उत्पाद या कैटलॉग नंबर की पहचान करता है। उत्पाद या कैटलॉग नंबर अधिकतम 18 प्रतीकों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।

**Returns:**
java.lang.String
### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public int getUnitOfMeasureID()
```


माप इकाई ID की पहचान करता है। माप इकाई ID 0 से 9 तक का पूर्णांक मान होना चाहिए।

**Returns:**
int
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




### parseFromString(String primaryDataCodetext) {#parseFromString-java.lang.String-}
```
public void parseFromString(String primaryDataCodetext)
```


HIBC LIC विनिर्देशन के अनुसार स्ट्रिंग फ़ॉर्मेट से प्राथमिक डेटा को इंस्टैंसिएट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| primaryDataCodetext | java.lang.String | फ़ॉर्मेटेड स्ट्रिंग। |

### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public void setLabelerIdentificationCode(String value)
```


लेबलर पहचान कोड की तिथि की पहचान करता है। लेबलर पहचान कोड 4 प्रतीकों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए, जिसमें पहला अक्षर हमेशा अक्षरात्मक होना चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public void setProductOrCatalogNumber(String value)
```


उत्पाद या कैटलॉग नंबर की पहचान करता है। उत्पाद या कैटलॉग नंबर अधिकतम 18 प्रतीकों की अल्फ़ान्यूमेरिक स्ट्रिंग होना चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public void setUnitOfMeasureID(int value)
```


माप इकाई ID की पहचान करता है। माप इकाई ID 0 से 9 तक का पूर्णांक मान होना चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
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

