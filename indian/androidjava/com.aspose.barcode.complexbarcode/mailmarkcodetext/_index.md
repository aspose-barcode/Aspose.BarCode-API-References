---
title: MailmarkCodetext
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: 4-स्टेट Royal Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।
type: docs
weight: 24
url: /hi/androidjava/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

4-स्टेट Royal Mailmark कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | MailmarkCodetext क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | बारकोड प्रकार प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | "0" - नल या टेस्ट "1" - 1C (रिटेल) "2" - 2C (रिटेल) "3" - 3C (रिटेल) "4" - प्रिमियम (RetailPublishing Mail) (भविष्य में संभावित उपयोग के लिए) "5" - स्थगित (रिटेल) "6" - एयर (रिटेल) (भविष्य में संभावित उपयोग के लिए) "7" - सर्फेस (रिटेल) (भविष्य में संभावित उपयोग के लिए) "8" - प्रिमियम (नेटवर्क एक्सेस) "9" - स्टैंडर्ड (नेटवर्क एक्सेस) |
| [getConstructedCodetext()](#getConstructedCodetext--) | Mailmark डेटा से कोडटेक्स्ट बनाएं। |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | PC और DP को PAF फ़ॉर्मेट के अनुरूप होना चाहिए। |
| [getFormat()](#getFormat--) | "0" \u2013 नल या टेस्ट "1" \u2013 अक्षर "2" \u2013 बड़ा अक्षर |
| [getItemID()](#getItemID--) | अधिकतम मान 99999999 है। |
| [getSupplychainID()](#getSupplychainID--) | बारकोड C के लिए अधिकतम मान 99 है और बारकोड L के लिए 999999 है। |
| [getVersionID()](#getVersionID--) | वर्तमान में "1" \u2013 Mailmark बारकोड के लिए (0 और 2 से 9 तथा A से Z भविष्य में उपयोग के लिए आरक्षित) |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | निर्मित कोडटेक्स्ट से Mailmark डेटा इनिशियलाइज़ करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | "0" - नल या टेस्ट "1" - 1C (रिटेल) "2" - 2C (रिटेल) "3" - 3C (रिटेल) "4" - प्रिमियम (RetailPublishing Mail) (भविष्य में संभावित उपयोग के लिए) "5" - स्थगित (रिटेल) "6" - एयर (रिटेल) (भविष्य में संभावित उपयोग के लिए) "7" - सर्फेस (रिटेल) (भविष्य में संभावित उपयोग के लिए) "8" - प्रिमियम (नेटवर्क एक्सेस) "9" - स्टैंडर्ड (नेटवर्क एक्सेस) |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | PC और DP को PAF फ़ॉर्मेट के अनुरूप होना चाहिए। |
| [setFormat(int value)](#setFormat-int-) | "0" \u2013 नल या टेस्ट "1" \u2013 अक्षर "2" \u2013 बड़ा अक्षर |
| [setItemID(int value)](#setItemID-int-) | अधिकतम मान 99999999 है। |
| [setSupplychainID(int value)](#setSupplychainID-int-) | बारकोड C के लिए अधिकतम मान 99 है और बारकोड L के लिए 999999 है। |
| [setVersionID(int value)](#setVersionID-int-) | वर्तमान में "1" \u2013 Mailmark बारकोड के लिए (0 और 2 से 9 तथा A से Z भविष्य में उपयोग के लिए आरक्षित) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


MailmarkCodetext क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

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
### getBarcodeType() {#getBarcodeType--}
```
public BaseEncodeType getBarcodeType()
```


बारकोड प्रकार प्राप्त करता है।

**Returns:**
[BaseEncodeType](../../com.aspose.barcode.generation/baseencodetype) - Barcode type.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClass_() {#getClass---}
```
public String getClass_()
```


"0" - नल या टेस्ट "1" - 1C (रिटेल) "2" - 2C (रिटेल) "3" - 3C (रिटेल) "4" - प्रिमियम (RetailPublishing Mail) (भविष्य में संभावित उपयोग के लिए) "5" - स्थगित (रिटेल) "6" - एयर (रिटेल) (भविष्य में संभावित उपयोग के लिए) "7" - सर्फेस (रिटेल) (भविष्य में संभावित उपयोग के लिए) "8" - प्रिमियम (नेटवर्क एक्सेस) "9" - स्टैंडर्ड (नेटवर्क एक्सेस)

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Mailmark डेटा से कोडटेक्स्ट बनाएं।

**Returns:**
java.lang.String - निर्मित कोडटेक्स्ट
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


PC और DP को PAF फ़ॉर्मेट के अनुरूप होना चाहिए। नौ अक्षरों की स्ट्रिंग जो अंतर्राष्ट्रीय "XY11 " को दर्शाती है (ध्यान दें कि 5 trailing spaces हैं) या एक पैटर्न जो घरेलू सॉर्टिंग कोड को दर्शाता है। एक घरेलू सॉर्टिंग कोड में आउटवर्ड पोस्टकोड, इनवर्ड पोस्टकोड, और डिलीवरी पॉइंट सफ़िक्स शामिल होते हैं।

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


"0" \u2013 नल या टेस्ट "1" \u2013 अक्षर "2" \u2013 बड़ा अक्षर

**Returns:**
int
### getItemID() {#getItemID--}
```
public int getItemID()
```


अधिकतम मान 99999999 है।

**Returns:**
int
### getSupplychainID() {#getSupplychainID--}
```
public int getSupplychainID()
```


बारकोड C के लिए अधिकतम मान 99 है और बारकोड L के लिए 999999 है।

**Returns:**
int
### getVersionID() {#getVersionID--}
```
public int getVersionID()
```


वर्तमान में "1" \u2013 Mailmark बारकोड के लिए (0 और 2 से 9 तथा A से Z भविष्य में उपयोग के लिए आरक्षित)

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initFromString(String constructedCodetext) {#initFromString-java.lang.String-}
```
public void initFromString(String constructedCodetext)
```


निर्मित कोडटेक्स्ट से Mailmark डेटा इनिशियलाइज़ करता है।

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




### setClass(String value) {#setClass-java.lang.String-}
```
public void setClass(String value)
```


"0" - नल या टेस्ट "1" - 1C (रिटेल) "2" - 2C (रिटेल) "3" - 3C (रिटेल) "4" - प्रिमियम (RetailPublishing Mail) (भविष्य में संभावित उपयोग के लिए) "5" - स्थगित (रिटेल) "6" - एयर (रिटेल) (भविष्य में संभावित उपयोग के लिए) "7" - सर्फेस (रिटेल) (भविष्य में संभावित उपयोग के लिए) "8" - प्रिमियम (नेटवर्क एक्सेस) "9" - स्टैंडर्ड (नेटवर्क एक्सेस)

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


PC और DP को PAF फ़ॉर्मेट के अनुरूप होना चाहिए। नौ अक्षरों की स्ट्रिंग जो अंतर्राष्ट्रीय "XY11 " को दर्शाती है (ध्यान दें कि 5 trailing spaces हैं) या एक पैटर्न जो घरेलू सॉर्टिंग कोड को दर्शाता है। एक घरेलू सॉर्टिंग कोड में आउटवर्ड पोस्टकोड, इनवर्ड पोस्टकोड, और डिलीवरी पॉइंट सफ़िक्स शामिल होते हैं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


"0" \u2013 नल या टेस्ट "1" \u2013 अक्षर "2" \u2013 बड़ा अक्षर

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


अधिकतम मान 99999999 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


बारकोड C के लिए अधिकतम मान 99 है और बारकोड L के लिए 999999 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


वर्तमान में "1" \u2013 Mailmark बारकोड के लिए (0 और 2 से 9 तथा A से Z भविष्य में उपयोग के लिए आरक्षित)

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | int |  |

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

