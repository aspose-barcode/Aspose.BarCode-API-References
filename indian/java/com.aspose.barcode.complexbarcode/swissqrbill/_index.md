---
title: "SwissQRBill"
second_title: "Aspose.BarCode के लिए Java API Reference"
description: "SwissQR बिल डेटा"
type: docs
weight: 35
url: /hi/java/com.aspose.barcode.complexbarcode/swissqrbill/
---
**Inheritance:**
java.lang.Object
```
public final class SwissQRBill
```

SwissQR बिल डेटा
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [createAndSetCreditorReference(String rawReference)](#createAndSetCreditorReference-java.lang.String-) | कच्ची स्ट्रिंग से ISO11649 क्रेडिटर रेफ़रेंस बनाता और सेट करता है, स्ट्रिंग को \"RF\" से प्रीफ़िक्स करके और modulo 97 चेकसम जोड़कर। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट वर्तमान ऑब्जेक्ट के बराबर है या नहीं। |
| [getAccount()](#getAccount--) | क्रेडिटर का खाता नंबर प्राप्त करता है। |
| [getAlternativeSchemes()](#getAlternativeSchemes--) | वैकल्पिक भुगतान योजनाओं को प्राप्त करता या सेट करता है। |
| [getAmount()](#getAmount--) | भुगतान राशि प्राप्त करता है। |
| [getBillInformation()](#getBillInformation--) | अतिरिक्त संरचित बिल जानकारी प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getCreditor()](#getCreditor--) | क्रेडिटर का पता प्राप्त करता है। |
| [getCurrency()](#getCurrency--) | भुगतान मुद्रा प्राप्त करता है। |
| [getDebtor()](#getDebtor--) | ऋणकर्ता का पता प्राप्त करता है। |
| [getReference()](#getReference--) | क्रेडिटर भुगतान संदर्भ प्राप्त करता है। |
| [getUnstructuredMessage()](#getUnstructuredMessage--) | अतिरिक्त असंरचित संदेश प्राप्त करता है। |
| [getVersion()](#getVersion--) | SwissQR बिल मानक का संस्करण प्राप्त करता है। |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश कोड प्राप्त करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAccount(String value)](#setAccount-java.lang.String-) | क्रेडिटर का खाता नंबर सेट करता है। |
| [setAlternativeSchemes(List<AlternativeScheme> value)](#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--) | वैकल्पिक भुगतान योजनाओं को प्राप्त करता या सेट करता है। |
| [setAmount(double value)](#setAmount-double-) | भुगतान राशि सेट करता है। |
| [setBillInformation(String value)](#setBillInformation-java.lang.String-) | अतिरिक्त संरचित बिल जानकारी सेट करता है। |
| [setCreditor(Address value)](#setCreditor-com.aspose.barcode.complexbarcode.Address-) | क्रेडिटर पता सेट करता है। |
| [setCurrency(String value)](#setCurrency-java.lang.String-) | भुगतान मुद्रा सेट करता है। |
| [setDebtor(Address value)](#setDebtor-com.aspose.barcode.complexbarcode.Address-) | ऋणकर्ता का पता सेट करता है। |
| [setReference(String value)](#setReference-java.lang.String-) | क्रेडिटर भुगतान संदर्भ सेट करता है। |
| [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | अतिरिक्त असंरचित संदेश सेट करता है। |
| [setVersion(QrBillStandardVersion value)](#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-) | SwissQR बिल मानक का संस्करण सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### createAndSetCreditorReference(String rawReference) {#createAndSetCreditorReference-java.lang.String-}
```
public void createAndSetCreditorReference(String rawReference)
```


कच्ची स्ट्रिंग से ISO11649 क्रेडिटर रेफ़रेंस बनाता और सेट करता है, स्ट्रिंग को \"RF\" से प्रीफ़िक्स करके और modulo 97 चेकसम जोड़कर।

संदर्भ से व्हाइटस्पेस हटा दिया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rawReference | java.lang.String | कच्चा संदर्भ। |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट वर्तमान ऑब्जेक्ट के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | वर्तमान ऑब्जेक्ट के साथ तुलना करने के लिए ऑब्जेक्ट। |

**Returns:**
boolean -  true  यदि निर्दिष्ट वस्तु वर्तमान वस्तु के बराबर है; अन्यथा,  false .
### getAccount() {#getAccount--}
```
public String getAccount()
```


क्रेडिटर का खाता नंबर प्राप्त करता है।

खाता नंबर स्विट्ज़रलैंड या लिचेंस्टीन के बैंक के वैध IBAN होने चाहिए। खाता नंबर में स्पेस की अनुमति है।

मान: क्रेडिटर खाता नंबर।

**Returns:**
java.lang.String
### getAlternativeSchemes() {#getAlternativeSchemes--}
```
public List<AlternativeScheme> getAlternativeSchemes()
```


वैकल्पिक भुगतान योजनाओं को प्राप्त करता या सेट करता है।

अधिकतम दो योजनाओं को पैरामीटरों के साथ अनुमति है।

मान: वैकल्पिक भुगतान योजनाएँ।

**Returns:**
java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme>
### getAmount() {#getAmount--}
```
public double getAmount()
```


भुगतान राशि प्राप्त करता है।

वैध मान 0.01 और 999,999,999.99 के बीच हैं।

मान: भुगतान राशि।

**Returns:**
double
### getBillInformation() {#getBillInformation--}
```
public String getBillInformation()
```


अतिरिक्त संरचित बिल जानकारी प्राप्त करता है।

मान: संरचित बिल जानकारी।

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreditor() {#getCreditor--}
```
public Address getCreditor()
```


क्रेडिटर का पता प्राप्त करता है।

मान: क्रेडिटर पता।

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getCurrency() {#getCurrency--}
```
public String getCurrency()
```


भुगतान मुद्रा प्राप्त करता है।

वैध मान "CHF" और "EUR" हैं।

मान: भुगतान मुद्रा।

**Returns:**
java.lang.String
### getDebtor() {#getDebtor--}
```
public Address getDebtor()
```


ऋणकर्ता का पता प्राप्त करता है।

देब्टर वैकल्पिक है। यदि इसे छोड़ दिया जाता है, तो इस फ़ील्ड को  null  पर सेट करना या सभी  null  या खाली मानों के साथ पता सेट करना दोनों ठीक है।

मान: देब्टर पता।

**Returns:**
[Address](../../com.aspose.barcode.complexbarcode/address)
### getReference() {#getReference--}
```
public String getReference()
```


क्रेडिटर भुगतान संदर्भ प्राप्त करता है।

स्विसQR IBANs के लिए संदर्भ अनिवार्य है, i.e.IBANs रेंज CHxx30000xxxxxx से CHxx31999xxxxx तक।

यदि निर्दिष्ट किया गया है, तो संदर्भ या तो वैध स्विसQR संदर्भ (ISR संदर्भ फ़ॉर्म के अनुरूप) या ISO 11649 के अनुसार वैध लेनदार संदर्भ ("RFxxxx") होना चाहिए। दोनों में फ़ॉर्मेटिंग के लिए स्पेस हो सकते हैं।

मान: लेनदार भुगतान संदर्भ।

**Returns:**
java.lang.String
### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public String getUnstructuredMessage()
```


अतिरिक्त असंरचित संदेश प्राप्त करता है।

मान: असंरचित संदेश।

**Returns:**
java.lang.String
### getVersion() {#getVersion--}
```
public QrBillStandardVersion getVersion()
```


SwissQR बिल मानक का संस्करण प्राप्त करता है।

मान: स्विसQR बिल मानक संस्करण।

**Returns:**
[QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion)
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस इंस्टेंस के लिए हैश कोड प्राप्त करता है।

**Returns:**
int - वर्तमान वस्तु के लिए हैश कोड।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAccount(String value) {#setAccount-java.lang.String-}
```
public void setAccount(String value)
```


क्रेडिटर का खाता नंबर सेट करता है।

खाता नंबर स्विट्ज़रलैंड या लिचेंस्टीन के बैंक के वैध IBAN होने चाहिए। खाता नंबर में स्पेस की अनुमति है।

मान: क्रेडिटर खाता नंबर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setAlternativeSchemes(List<AlternativeScheme> value) {#setAlternativeSchemes-java.util.List-com.aspose.barcode.complexbarcode.AlternativeScheme--}
```
public void setAlternativeSchemes(List<AlternativeScheme> value)
```


वैकल्पिक भुगतान योजनाओं को प्राप्त करता या सेट करता है।

अधिकतम दो योजनाओं को पैरामीटरों के साथ अनुमति है।

मान: वैकल्पिक भुगतान योजनाएँ।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.List<com.aspose.barcode.complexbarcode.AlternativeScheme> |  |

### setAmount(double value) {#setAmount-double-}
```
public void setAmount(double value)
```


भुगतान राशि सेट करता है।

वैध मान 0.01 और 999,999,999.99 के बीच हैं।

मान: भुगतान राशि।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public void setBillInformation(String value)
```


अतिरिक्त संरचित बिल जानकारी सेट करता है।

मान: संरचित बिल जानकारी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setCreditor(Address value) {#setCreditor-com.aspose.barcode.complexbarcode.Address-}
```
public void setCreditor(Address value)
```


क्रेडिटर पता सेट करता है।

मान: क्रेडिटर पता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public void setCurrency(String value)
```


भुगतान मुद्रा सेट करता है।

वैध मान "CHF" और "EUR" हैं।

मान: भुगतान मुद्रा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setDebtor(Address value) {#setDebtor-com.aspose.barcode.complexbarcode.Address-}
```
public void setDebtor(Address value)
```


ऋणकर्ता का पता सेट करता है।

देब्टर वैकल्पिक है। यदि इसे छोड़ दिया जाता है, तो इस फ़ील्ड को  null  पर सेट करना या सभी  null  या खाली मानों के साथ पता सेट करना दोनों ठीक है।

मान: देब्टर पता।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Address](../../com.aspose.barcode.complexbarcode/address) |  |

### setReference(String value) {#setReference-java.lang.String-}
```
public void setReference(String value)
```


क्रेडिटर भुगतान संदर्भ सेट करता है।

स्विसQR IBANs के लिए संदर्भ अनिवार्य है, i.e.IBANs रेंज CHxx30000xxxxxx से CHxx31999xxxxx तक।

यदि निर्दिष्ट किया गया है, तो संदर्भ या तो वैध स्विसQR संदर्भ (ISR संदर्भ फ़ॉर्म के अनुरूप) या ISO 11649 के अनुसार वैध लेनदार संदर्भ ("RFxxxx") होना चाहिए। दोनों में फ़ॉर्मेटिंग के लिए स्पेस हो सकते हैं।

मान: लेनदार भुगतान संदर्भ।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public void setUnstructuredMessage(String value)
```


अतिरिक्त असंरचित संदेश सेट करता है।

मान: असंरचित संदेश।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setVersion(QrBillStandardVersion value) {#setVersion-com.aspose.barcode.complexbarcode.QrBillStandardVersion-}
```
public void setVersion(QrBillStandardVersion value)
```


SwissQR बिल मानक का संस्करण सेट करता है।

मान: स्विसQR बिल मानक संस्करण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [QrBillStandardVersion](../../com.aspose.barcode.complexbarcode/qrbillstandardversion) |  |

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

