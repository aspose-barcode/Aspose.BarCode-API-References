---
title: "पता"
second_title: "Aspose.BarCode के लिए Android via Java API संदर्भ"
description: "ऋणदाता या उधारकर्ता का पता।"
type: docs
weight: 10
url: /hi/androidjava/com.aspose.barcode.complexbarcode/address/
---
**Inheritance:**
java.lang.Object
```
public final class Address
```

ऋणदाता या उधारकर्ता का पता।

आप या तो सड़क, घर नंबर, पोस्टल कोड और शहर सेट कर सकते हैं (type  *structured address* ) या पता पंक्ति 1 और 2 (type  *combined address elements* ). प्रकार स्वचालित रूप से सेट हो जाता है जब इन फ़ील्डों में से कोई भी सेट किया जाता है। फ़ील्ड सेट करने से पहले, पता प्रकार  *undetermined* है। यदि दोनों प्रकार की फ़ील्डें सेट की जाती हैं, तो पता प्रकार  *conflicting* हो जाता है। नाम और देश कोड हमेशा सेट होना चाहिए जब तक सभी फ़ील्ड खाली न हों।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Address()](#Address--) | Address का उदाहरण बनाता है |
## Methods

| Method | विवरण |
| --- | --- |
| [clear()](#clear--) | सभी फ़ील्ड साफ़ करता है और प्रकार को  AddressType.Undetermined पर सेट करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट वर्तमान ऑब्जेक्ट के बराबर है या नहीं। |
| [getAddressLine1()](#getAddressLine1--) | पता पंक्ति 1 प्राप्त करता है। |
| [getAddressLine2()](#getAddressLine2--) | पता पंक्ति 2 प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getCountryCode()](#getCountryCode--) | दो-अक्षरीय ISO देश कोड प्राप्त करता है। |
| [getHouseNo()](#getHouseNo--) | घर नंबर प्राप्त करता है। |
| [getName()](#getName--) | नाम प्राप्त करता है, चाहे वह प्राकृतिक व्यक्ति का पहला और अंतिम नाम हो या कानूनी व्यक्ति का कंपनी नाम। |
| [getPostalCode()](#getPostalCode--) | डाक कोड प्राप्त करता है। |
| [getStreet()](#getStreet--) | सड़क प्राप्त करता है। |
| [getTown()](#getTown--) | शहर या कस्बा प्राप्त करता है। |
| [getType()](#getType--) | पते का प्रकार प्राप्त करता है। |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश कोड प्राप्त करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | पता पंक्ति 1 सेट करता है। |
| [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | पता पंक्ति 2 सेट करता है। |
| [setCountryCode(String value)](#setCountryCode-java.lang.String-) | दो-अक्षरीय ISO देश कोड सेट करता है। |
| [setHouseNo(String value)](#setHouseNo-java.lang.String-) | घर नंबर सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है, चाहे वह प्राकृतिक व्यक्ति का पहला और अंतिम नाम हो या कानूनी व्यक्ति का कंपनी नाम। |
| [setPostalCode(String value)](#setPostalCode-java.lang.String-) | डाक कोड सेट करता है। |
| [setStreet(String value)](#setStreet-java.lang.String-) | सड़क सेट करता है। |
| [setTown(String value)](#setTown-java.lang.String-) | शहर या कस्बा सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Address() {#Address--}
```
public Address()
```


Address का उदाहरण बनाता है

### clear() {#clear--}
```
public void clear()
```


सभी फ़ील्ड साफ़ करता है और प्रकार को  AddressType.Undetermined पर सेट करता है।

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट वर्तमान ऑब्जेक्ट के बराबर है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | वर्तमान ऑब्जेक्ट के साथ तुलना करने के लिए ऑब्जेक्ट। |

**Returns:**
बूलियन -  true  यदि निर्दिष्ट ऑब्जेक्ट वर्तमान ऑब्जेक्ट के बराबर है; अन्यथा,  false .
### getAddressLine1() {#getAddressLine1--}
```
public String getAddressLine1()
```


पता पंक्ति 1 प्राप्त करता है।

पता पंक्ति 1 में सड़क का नाम, घर नंबर या पी.ओ. बॉक्स शामिल है।

इस फ़ील्ड को सेट करने से पता प्रकार  AddressType.CombinedElements  हो जाता है, जब तक कि यह पहले से  AddressType.Structured  न हो, ऐसे में यह  AddressType.Conflicting  बन जाता है।

यह फ़ील्ड केवल संयुक्त तत्वों वाले पते के लिए उपयोग किया जाता है और वैकल्पिक है।

मान: पता पंक्ति 1।

**Returns:**
java.lang.String
### getAddressLine2() {#getAddressLine2--}
```
public String getAddressLine2()
```


पता पंक्ति 2 प्राप्त करता है।

पता पंक्ति 2 में डाक कोड और शहर शामिल है।

इस फ़ील्ड को सेट करने से पता प्रकार  AddressType.CombinedElements  हो जाता है, जब तक कि यह पहले से  AddressType.Structured  न हो, ऐसे में यह  AddressType.Conflicting  बन जाता है।

यह फ़ील्ड केवल संयुक्त तत्वों वाले पते के लिए उपयोग किया जाता है। इस प्रकार के लिए यह अनिवार्य है।

मान: पता पंक्ति 2।

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryCode() {#getCountryCode--}
```
public String getCountryCode()
```


दो-अक्षरीय ISO देश कोड प्राप्त करता है।

देश कोड अनिवार्य है जब तक कि पूरा पता  null  या emtpy मान न रखे।

मान: ISO देश कोड।

**Returns:**
java.lang.String
### getHouseNo() {#getHouseNo--}
```
public String getHouseNo()
```


घर नंबर प्राप्त करता है।

इस फ़ील्ड को सेट करने से पता प्रकार  AddressType.Structured  हो जाता है, जब तक कि यह पहले से  AddressType.CombinedElements  न हो, ऐसे में यह  AddressType.Conflicting  बन जाता है।

यह फ़ील्ड केवल संरचित पतों के लिए उपयोग किया जाता है और वैकल्पिक है।

मान: घर नंबर।

**Returns:**
java.lang.String
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है, चाहे वह प्राकृतिक व्यक्ति का पहला और अंतिम नाम हो या कानूनी व्यक्ति का कंपनी नाम।

मान: नाम।

**Returns:**
java.lang.String
### getPostalCode() {#getPostalCode--}
```
public String getPostalCode()
```


डाक कोड प्राप्त करता है।

इस फ़ील्ड को सेट करने से पता प्रकार  AddressType.Structured  हो जाता है, जब तक कि यह पहले से  AddressType.CombinedElements  न हो, ऐसे में यह  AddressType.Conflicting  बन जाता है।

यह फ़ील्ड केवल संरचित पतों के लिए उपयोग किया जाता है। इस प्रकार के लिए, यह अनिवार्य है।

मान: डाक कोड।

**Returns:**
java.lang.String
### getStreet() {#getStreet--}
```
public String getStreet()
```


सड़क प्राप्त करता है।

सड़क को घर नंबर के बिना निर्दिष्ट किया जाना चाहिए।

इस फ़ील्ड को सेट करने से पता प्रकार  AddressType.Structured  हो जाता है, जब तक कि यह पहले से  AddressType.CombinedElements  न हो, ऐसे में यह  AddressType.Conflicting  बन जाता है।

यह फ़ील्ड केवल संरचित पतों के लिए उपयोग किया जाता है और वैकल्पिक है।

मान: सड़क।

**Returns:**
java.lang.String
### getTown() {#getTown--}
```
public String getTown()
```


शहर या कस्बा प्राप्त करता है।

इस फ़ील्ड को सेट करने से पता प्रकार  AddressType.Structured  हो जाता है, जब तक कि यह पहले से  AddressType.CombinedElements  न हो, ऐसे में यह  AddressType.Conflicting  बन जाता है।

यह फ़ील्ड केवल संरचित पतों के लिए उपयोग किया जाता है। इस प्रकार के लिए, यह अनिवार्य है।

मान: शहर या कस्बा।

**Returns:**
java.lang.String
### getType() {#getType--}
```
public AddressType getType()
```


पते का प्रकार प्राप्त करता है।

पता प्रकार स्वचालित रूप से सेट किया जाता है जब आप या तो सड़क / घर नंबर या पता पंक्ति 1 और 2 सेट करते हैं। फ़ील्ड सेट करने से पहले, पता प्रकार  *Undetermined* है। यदि दोनों प्रकार के फ़ील्ड सेट किए जाते हैं, तो पता प्रकार  *Conflicting* हो जाता है।

मान: पता प्रकार।

**Returns:**
[AddressType](../../com.aspose.barcode.complexbarcode/addresstype)
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस इंस्टेंस के लिए हैश कोड प्राप्त करता है।

**Returns:**
int - वर्तमान ऑब्जेक्ट के लिए हैश कोड।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public void setAddressLine1(String value)
```


पता पंक्ति 1 सेट करता है।

पता पंक्ति 1 में सड़क का नाम, घर नंबर या पी.ओ. बॉक्स शामिल है।

इस फ़ील्ड को सेट करने से पता प्रकार  AddressType.CombinedElements  हो जाता है, जब तक कि यह पहले से  AddressType.Structured  न हो, ऐसे में यह  AddressType.Conflicting  बन जाता है।

यह फ़ील्ड केवल संयुक्त तत्वों वाले पते के लिए उपयोग किया जाता है और वैकल्पिक है।

मान: पता पंक्ति 1।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public void setAddressLine2(String value)
```


पता पंक्ति 2 सेट करता है।

पता पंक्ति 2 में डाक कोड और शहर शामिल है।

इस फ़ील्ड को सेट करने से पता प्रकार  AddressType.CombinedElements  हो जाता है, जब तक कि यह पहले से  AddressType.Structured  न हो, ऐसे में यह  AddressType.Conflicting  बन जाता है।

यह फ़ील्ड केवल संयुक्त तत्वों वाले पते के लिए उपयोग किया जाता है। इस प्रकार के लिए यह अनिवार्य है।

मान: पता पंक्ति 2।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public void setCountryCode(String value)
```


दो-अक्षरीय ISO देश कोड सेट करता है।

देश कोड अनिवार्य है जब तक कि पूरा पता  null  या emtpy मान न रखे।

मान: ISO देश कोड।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public void setHouseNo(String value)
```


घर नंबर सेट करता है।

इस फ़ील्ड को सेट करने से पता प्रकार  AddressType.Structured  हो जाता है, जब तक कि यह पहले से  AddressType.CombinedElements  न हो, ऐसे में यह  AddressType.Conflicting  बन जाता है।

यह फ़ील्ड केवल संरचित पतों के लिए उपयोग किया जाता है और वैकल्पिक है।

मान: घर नंबर।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है, चाहे वह प्राकृतिक व्यक्ति का पहला और अंतिम नाम हो या कानूनी व्यक्ति का कंपनी नाम।

मान: नाम।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public void setPostalCode(String value)
```


डाक कोड सेट करता है।

इस फ़ील्ड को सेट करने से पता प्रकार  AddressType.Structured  हो जाता है, जब तक कि यह पहले से  AddressType.CombinedElements  न हो, ऐसे में यह  AddressType.Conflicting  बन जाता है।

यह फ़ील्ड केवल संरचित पतों के लिए उपयोग किया जाता है। इस प्रकार के लिए, यह अनिवार्य है।

मान: डाक कोड।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setStreet(String value) {#setStreet-java.lang.String-}
```
public void setStreet(String value)
```


सड़क सेट करता है।

सड़क को घर नंबर के बिना निर्दिष्ट किया जाना चाहिए।

इस फ़ील्ड को सेट करने से पता प्रकार  AddressType.Structured  हो जाता है, जब तक कि यह पहले से  AddressType.CombinedElements  न हो, ऐसे में यह  AddressType.Conflicting  बन जाता है।

यह फ़ील्ड केवल संरचित पतों के लिए उपयोग किया जाता है और वैकल्पिक है।

मान: सड़क।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setTown(String value) {#setTown-java.lang.String-}
```
public void setTown(String value)
```


शहर या कस्बा सेट करता है।

इस फ़ील्ड को सेट करने से पता प्रकार  AddressType.Structured  हो जाता है, जब तक कि यह पहले से  AddressType.CombinedElements  न हो, ऐसे में यह  AddressType.Conflicting  बन जाता है।

यह फ़ील्ड केवल संरचित पतों के लिए उपयोग किया जाता है। इस प्रकार के लिए, यह अनिवार्य है।

मान: शहर या कस्बा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

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

