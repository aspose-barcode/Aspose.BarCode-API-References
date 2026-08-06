---
title: ExtCodetextBuilder
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: विस्तारित कोडटेक्स्ट मोड के स्वचालित कोडटेक्स्ट जनरेशन के लिए हेल्पर क्लास
type: docs
weight: 40
url: /hi/androidjava/com.aspose.barcode.generation/extcodetextbuilder/
---
**Inheritance:**
java.lang.Object
```
public abstract class ExtCodetextBuilder
```

विस्तारित कोडटेक्स्ट मोड के स्वचालित कोडटेक्स्ट जनरेशन के लिए हेल्पर क्लास
## Constructors

| Constructor | विवरण |
| --- | --- |
| [ExtCodetextBuilder()](#ExtCodetextBuilder--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [addECICodetext(int ECIEncoding, String codetext)](#addECICodetext-int-java.lang.String-) | Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है। |
| [addPlainCodetext(String codetext)](#addPlainCodetext-java.lang.String-) | सामान्य कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है |
| [clear()](#clear--) | विस्तारित कोडटेक्स्ट आइटम्स को साफ़ करता है |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtendedCodetext()](#getExtendedCodetext--) | जनरेशन आइटम सूची से विस्तारित कोडटेक्स्ट उत्पन्न करें। |
| [hashCode()](#hashCode--) |  |
| [isNeedToShieldItemFromPrevECI(int Index)](#isNeedToShieldItemFromPrevECI-int-) | पिछले आइटम को "\\000000" द्वारा शील्ड करने की आवश्यकता की जाँच करता है |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ExtCodetextBuilder() {#ExtCodetextBuilder--}
```
public ExtCodetextBuilder()
```


### addECICodetext(int ECIEncoding, String codetext) {#addECICodetext-int-java.lang.String-}
```
public void addECICodetext(int ECIEncoding, String codetext)
```


Extended Channel Identifier के साथ कोडटेक्स्ट जोड़ता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| ECIEncoding | int | विस्तारित चैनल पहचानकर्ता |
| कोडटेक्स्ट | java.lang.String | विस्तारित चैनल पहचानकर्ता के साथ विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ने के लिए यूनिकोड में कोडटेक्स्ट |

### addPlainCodetext(String codetext) {#addPlainCodetext-java.lang.String-}
```
public void addPlainCodetext(String codetext)
```


सामान्य कोडटेक्स्ट को विस्तारित कोडटेक्स्ट आइटम्स में जोड़ता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| कोडटेक्स्ट | java.lang.String | विस्तारित कोडटेक्स्ट आइटम के रूप में जोड़ने के लिए यूनिकोड में कोडटेक्स्ट |

### clear() {#clear--}
```
public void clear()
```


विस्तारित कोडटेक्स्ट आइटम्स को साफ़ करता है

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtendedCodetext() {#getExtendedCodetext--}
```
public abstract String getExtendedCodetext()
```


जनरेशन आइटम सूची से विस्तारित कोडटेक्स्ट उत्पन्न करें।

**Returns:**
java.lang.String - विस्तारित कोडटेक्स्ट की स्ट्रिंग लौटाता है।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNeedToShieldItemFromPrevECI(int Index) {#isNeedToShieldItemFromPrevECI-int-}
```
public boolean isNeedToShieldItemFromPrevECI(int Index)
```


पिछले आइटम को "\\000000" द्वारा शील्ड करने की आवश्यकता की जाँच करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| सूचकांक | int | m\_List में सूचकांक |

**Returns:**
boolean - शील्ड करने की आवश्यकता
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

