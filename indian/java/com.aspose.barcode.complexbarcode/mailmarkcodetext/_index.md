---
title: "MailmarkCodetext"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "4-स्टेट रॉयल मेलमार्क कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।"
type: docs
weight: 24
url: /hi/java/com.aspose.barcode.complexbarcode/mailmarkcodetext/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.barcode.complexbarcode.IComplexCodetext](../../com.aspose.barcode.complexbarcode/icomplexcodetext)
```
public final class MailmarkCodetext implements IComplexCodetext
```

4-स्टेट रॉयल मेलमार्क कोड में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MailmarkCodetext()](#MailmarkCodetext--) | MailmarkCodetext क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBarcodeType()](#getBarcodeType--) | बारकोड प्रकार प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getClass_()](#getClass---) | \"0\" - नल या परीक्षण \"1\" - 1C (रिटेल) \"2\" - 2C (रिटेल) \"3\" - 3C (रिटेल) \"4\" - प्रिमियम (RetailPublishing Mail) (भविष्य में संभावित उपयोग के लिए) \"5\" - स्थगित (रिटेल) \"6\" - एयर (रिटेल) (भविष्य में संभावित उपयोग के लिए) \"7\" - सतह (रिटेल) (भविष्य में संभावित उपयोग के लिए) \"8\" - प्रिमियम (नेटवर्क एक्सेस) \"9\" - स्टैंडर्ड (नेटवर्क एक्सेस) |
| [getConstructedCodetext()](#getConstructedCodetext--) | Mailmark डेटा से codetext बनाएं। |
| [getDestinationPostCodePlusDPS()](#getDestinationPostCodePlusDPS--) | PC और DP को PAF फ़ॉर्मेट के अनुरूप होना चाहिए। |
| [getFormat()](#getFormat--) | \"0\" \\u2013 नल या परीक्षण \"1\" \\u2013 लेटर \"2\" \\u2013 बड़ा लेटर |
| [getItemID()](#getItemID--) | अधिकतम मान 99999999 है। |
| [getSupplychainID()](#getSupplychainID--) | बारकोड C के लिए अधिकतम मान 99 है और बारकोड L के लिए 999999 है। |
| [getVersionID()](#getVersionID--) | वर्तमान में \"1\" \\u2013 Mailmark बारकोड के लिए (0 और 2 से 9 तथा A से Z भविष्य उपयोग के लिए आरक्षित) |
| [hashCode()](#hashCode--) |  |
| [initFromString(String constructedCodetext)](#initFromString-java.lang.String-) | निर्मित कोडटेक्स्ट से Mailmark डेटा को इनिशियलाइज़ करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setClass(String value)](#setClass-java.lang.String-) | \"0\" - नल या परीक्षण \"1\" - 1C (रिटेल) \"2\" - 2C (रिटेल) \"3\" - 3C (रिटेल) \"4\" - प्रिमियम (RetailPublishing Mail) (भविष्य में संभावित उपयोग के लिए) \"5\" - स्थगित (रिटेल) \"6\" - एयर (रिटेल) (भविष्य में संभावित उपयोग के लिए) \"7\" - सतह (रिटेल) (भविष्य में संभावित उपयोग के लिए) \"8\" - प्रिमियम (नेटवर्क एक्सेस) \"9\" - स्टैंडर्ड (नेटवर्क एक्सेस) |
| [setDestinationPostCodePlusDPS(String value)](#setDestinationPostCodePlusDPS-java.lang.String-) | PC और DP को PAF फ़ॉर्मेट के अनुरूप होना चाहिए। |
| [setFormat(int value)](#setFormat-int-) | \"0\" \\u2013 नल या परीक्षण \"1\" \\u2013 लेटर \"2\" \\u2013 बड़ा लेटर |
| [setItemID(int value)](#setItemID-int-) | अधिकतम मान 99999999 है। |
| [setSupplychainID(int value)](#setSupplychainID-int-) | बारकोड C के लिए अधिकतम मान 99 है और बारकोड L के लिए 999999 है। |
| [setVersionID(int value)](#setVersionID-int-) | वर्तमान में \"1\" \\u2013 Mailmark बारकोड के लिए (0 और 2 से 9 तथा A से Z भविष्य उपयोग के लिए आरक्षित) |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailmarkCodetext() {#MailmarkCodetext--}
```
public MailmarkCodetext()
```


MailmarkCodetext क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

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


\"0\" - नल या परीक्षण \"1\" - 1C (रिटेल) \"2\" - 2C (रिटेल) \"3\" - 3C (रिटेल) \"4\" - प्रिमियम (RetailPublishing Mail) (भविष्य में संभावित उपयोग के लिए) \"5\" - स्थगित (रिटेल) \"6\" - एयर (रिटेल) (भविष्य में संभावित उपयोग के लिए) \"7\" - सतह (रिटेल) (भविष्य में संभावित उपयोग के लिए) \"8\" - प्रिमियम (नेटवर्क एक्सेस) \"9\" - स्टैंडर्ड (नेटवर्क एक्सेस)

**Returns:**
java.lang.String
### getConstructedCodetext() {#getConstructedCodetext--}
```
public String getConstructedCodetext()
```


Mailmark डेटा से codetext बनाएं।

**Returns:**
java.lang.String - निर्मित कोडटेक्स्ट
### getDestinationPostCodePlusDPS() {#getDestinationPostCodePlusDPS--}
```
public String getDestinationPostCodePlusDPS()
```


PC और DP को PAF फ़ॉर्मेट का पालन करना चाहिए। नौ अक्षरों की स्ट्रिंग जो अंतरराष्ट्रीय \"XY11 \" को दर्शाती है (ध्यान दें 5 अंत में स्पेस) या एक पैटर्न जो घरेलू सॉर्टिंग कोड को दर्शाता है। एक घरेलू सॉर्टिंग कोड में outward postcode, inward postcode, और Delivery Point Suffix शामिल होते हैं।

**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public int getFormat()
```


\"0\" \\u2013 नल या परीक्षण \"1\" \\u2013 लेटर \"2\" \\u2013 बड़ा लेटर

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


वर्तमान में \"1\" \\u2013 Mailmark बारकोड के लिए (0 और 2 से 9 तथा A से Z भविष्य उपयोग के लिए आरक्षित)

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


निर्मित कोडटेक्स्ट से Mailmark डेटा को इनिशियलाइज़ करता है।

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




### setClass(String value) {#setClass-java.lang.String-}
```
public void setClass(String value)
```


\"0\" - नल या परीक्षण \"1\" - 1C (रिटेल) \"2\" - 2C (रिटेल) \"3\" - 3C (रिटेल) \"4\" - प्रिमियम (RetailPublishing Mail) (भविष्य में संभावित उपयोग के लिए) \"5\" - स्थगित (रिटेल) \"6\" - एयर (रिटेल) (भविष्य में संभावित उपयोग के लिए) \"7\" - सतह (रिटेल) (भविष्य में संभावित उपयोग के लिए) \"8\" - प्रिमियम (नेटवर्क एक्सेस) \"9\" - स्टैंडर्ड (नेटवर्क एक्सेस)

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setDestinationPostCodePlusDPS(String value) {#setDestinationPostCodePlusDPS-java.lang.String-}
```
public void setDestinationPostCodePlusDPS(String value)
```


PC और DP को PAF फ़ॉर्मेट का पालन करना चाहिए। नौ अक्षरों की स्ट्रिंग जो अंतरराष्ट्रीय \"XY11 \" को दर्शाती है (ध्यान दें 5 अंत में स्पेस) या एक पैटर्न जो घरेलू सॉर्टिंग कोड को दर्शाता है। एक घरेलू सॉर्टिंग कोड में outward postcode, inward postcode, और Delivery Point Suffix शामिल होते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setFormat(int value) {#setFormat-int-}
```
public void setFormat(int value)
```


\"0\" \\u2013 नल या परीक्षण \"1\" \\u2013 लेटर \"2\" \\u2013 बड़ा लेटर

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setItemID(int value) {#setItemID-int-}
```
public void setItemID(int value)
```


अधिकतम मान 99999999 है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSupplychainID(int value) {#setSupplychainID-int-}
```
public void setSupplychainID(int value)
```


बारकोड C के लिए अधिकतम मान 99 है और बारकोड L के लिए 999999 है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setVersionID(int value) {#setVersionID-int-}
```
public void setVersionID(int value)
```


वर्तमान में \"1\" \\u2013 Mailmark बारकोड के लिए (0 और 2 से 9 तथा A से Z भविष्य उपयोग के लिए आरक्षित)

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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

