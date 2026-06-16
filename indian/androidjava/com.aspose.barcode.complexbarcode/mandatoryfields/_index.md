---
title: USADriveIdCodetext.MandatoryFields
second_title: Aspose.BarCode एंड्रॉइड के लिए जावा API रेफ़रेंस
description: कार्ड के अनिवार्य तत्व फ़ील्ड्स
type: docs
weight: 10
url: /hi/androidjava/com.aspose.barcode.complexbarcode/usadriveidcodetext.mandatoryfields/
---
**Inheritance:**
java.lang.Object
```
public static class USADriveIdCodetext.MandatoryFields
```

कार्ड के अनिवार्य तत्व (फ़ील्ड)।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [MandatoryFields()](#MandatoryFields--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressCity()](#getAddressCity--) | DAI, कार्डधारक पते का शहर भाग, DL/ID, V20ANS |
| [getAddressPostalCode()](#getAddressPostalCode--) | DAK, यू.एस. और कनाडा में कार्डधारक पते का पोस्टल कोड भाग। |
| [getAddressState()](#getAddressState--) | DAJ, कार्डधारक पते का राज्य भाग, DL/ID, F2A |
| [getAddressStreet1()](#getAddressStreet1--) | DAG, कार्डधारक पते का सड़क भाग, DL/ID, V35ANS |
| [getClass()](#getClass--) |  |
| [getCountryIdentification()](#getCountryIdentification--) | DCG, वह देश जिसमें DL/ID जारी किया गया है। |
| [getCustomerIDNumber()](#getCustomerIDNumber--) | DAQ, जारी करने वाले प्राधिकरण द्वारा निर्धारित या गणना किया गया संख्या, DL/ID, V25ANS |
| [getDateOfBirth()](#getDateOfBirth--) | DBB, दस्तावेज़ जारी होने की तिथि, यू.एस. के लिए MMDDCCYY, कनाडा के लिए CCYYMMDD, DL/ID, F8N |
| [getDocumentDiscriminator()](#getDocumentDiscriminator--) | DCF, संख्या को उस ग्राहक को जारी किए गए विशिष्ट दस्तावेज़ को अन्य पूर्व में जारी किए गए दस्तावेज़ों से अनन्य रूप से पहचानना चाहिए। |
| [getEndorsementCodes()](#getEndorsementCodes--) | DCD, अधिकार क्षेत्र विशिष्ट समर्थन कोड, DL, V5ANS |
| [getEyeColor()](#getEyeColor--) | DAY, कार्डधारक की आँखों का रंग। |
| [getFamilyName()](#getFamilyName--) | DCS, कार्डधारक का पारिवारिक नाम, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getFamilyNameTruncation--) | DDE, एक कोड जो दर्शाता है कि कोई फ़ील्ड ट्रंकेट किया गया है (T), नहीं किया गया है (N), या ट्रंकेट किया गया है या नहीं अज्ञात है (U), DL/ID, F1A |
| [getFirstName()](#getFirstName--) | DAC, कार्डधारक का पहला नाम, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getFirstNameTruncation--) | DDF, एक कोड जो दर्शाता है कि कोई फ़ील्ड ट्रंकेट किया गया है (T), नहीं किया गया है (N), या ट्रंकेट किया गया है या नहीं अज्ञात है (U), DL/ID, F1A |
| [getHeight()](#getHeight--) | DAU, कार्डधारक की ऊँचाई। |
| [getMiddleName()](#getMiddleName--) | DAD, कार्डधारक के मध्य नाम। |
| [getMiddleNameTruncation()](#getMiddleNameTruncation--) | DDG, एक कोड जो दर्शाता है कि कोई फ़ील्ड ट्रंकेट किया गया है (T), नहीं किया गया है (N), या ट्रंकेट किया गया है या नहीं अज्ञात है (U), DL/ID, F1A |
| [getRestrictionCodes()](#getRestrictionCodes--) | DCB, अधिकार क्षेत्र-विशिष्ट प्रतिबंध कोड, DL, V12ANS |
| [getSex()](#getSex--) | DBC, कार्डधारक का लिंग। |
| [getVehicleClass()](#getVehicleClass--) | DCA, अधिकार क्षेत्र-विशिष्ट वाहन वर्ग / समूह कोड, DL, V6ANS |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAddressCity(String value)](#setAddressCity-java.lang.String-) | DAI, कार्डधारक पते का शहर भाग, DL/ID, V20ANS |
| [setAddressPostalCode(String value)](#setAddressPostalCode-java.lang.String-) | DAK, यू.एस. और कनाडा में कार्डधारक पते का पोस्टल कोड भाग। |
| [setAddressState(String value)](#setAddressState-java.lang.String-) | DAJ, कार्डधारक पते का राज्य भाग, DL/ID, F2A |
| [setAddressStreet1(String value)](#setAddressStreet1-java.lang.String-) | DAG, कार्डधारक पते का सड़क भाग, DL/ID, V35ANS |
| [setCountryIdentification(USADriveIdCountry value)](#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-) | DCG, वह देश जिसमें DL/ID जारी किया गया है। |
| [setCustomerIDNumber(String value)](#setCustomerIDNumber-java.lang.String-) | DAQ, जारी करने वाले प्राधिकरण द्वारा निर्धारित या गणना किया गया संख्या, DL/ID, V25ANS |
| [setDateOfBirth(LocalDate value)](#setDateOfBirth-java.time.LocalDate-) | DBB, दस्तावेज़ जारी होने की तिथि, यू.एस. के लिए MMDDCCYY, कनाडा के लिए CCYYMMDD, DL/ID, F8N |
| [setDocumentDiscriminator(String value)](#setDocumentDiscriminator-java.lang.String-) | DCF, संख्या को उस ग्राहक को जारी किए गए विशिष्ट दस्तावेज़ को अन्य पूर्व में जारी किए गए दस्तावेज़ों से अनन्य रूप से पहचानना चाहिए। |
| [setEndorsementCodes(String value)](#setEndorsementCodes-java.lang.String-) | DCD, अधिकार क्षेत्र विशिष्ट समर्थन कोड, DL, V5ANS |
| [setEyeColor(USADriveIdEyeColor value)](#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-) | DAY, कार्डधारक की आँखों का रंग। |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | DCS, कार्डधारक का पारिवारिक नाम, DL/ID, V40ANS |
| [setFamilyNameTruncation(String value)](#setFamilyNameTruncation-java.lang.String-) | DDE, एक कोड जो दर्शाता है कि कोई फ़ील्ड ट्रंकेट किया गया है (T), नहीं किया गया है (N), या ट्रंकेट किया गया है या नहीं अज्ञात है (U), DL/ID, F1A |
| [setFirstName(String value)](#setFirstName-java.lang.String-) | DAC, कार्डधारक का पहला नाम, DL/ID, V40ANS |
| [setFirstNameTruncation(String value)](#setFirstNameTruncation-java.lang.String-) | DDF, एक कोड जो दर्शाता है कि कोई फ़ील्ड ट्रंकेट किया गया है (T), नहीं किया गया है (N), या ट्रंकेट किया गया है या नहीं अज्ञात है (U), DL/ID, F1A |
| [setHeight(String value)](#setHeight-java.lang.String-) | DAU, कार्डधारक की ऊँचाई। |
| [setMiddleName(String value)](#setMiddleName-java.lang.String-) | DAD, कार्डधारक के मध्य नाम। |
| [setMiddleNameTruncation(String value)](#setMiddleNameTruncation-java.lang.String-) | DDG, एक कोड जो दर्शाता है कि कोई फ़ील्ड ट्रंकेट किया गया है (T), नहीं किया गया है (N), या ट्रंकेट किया गया है या नहीं अज्ञात है (U), DL/ID, F1A |
| [setRestrictionCodes(String value)](#setRestrictionCodes-java.lang.String-) | DCB, अधिकार क्षेत्र-विशिष्ट प्रतिबंध कोड, DL, V12ANS |
| [setSex(USADriveIdSex value)](#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-) | DBC, कार्डधारक का लिंग। |
| [setVehicleClass(String value)](#setVehicleClass-java.lang.String-) | DCA, अधिकार क्षेत्र-विशिष्ट वाहन वर्ग / समूह कोड, DL, V6ANS |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MandatoryFields() {#MandatoryFields--}
```
public MandatoryFields()
```


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
### getAddressCity() {#getAddressCity--}
```
public final String getAddressCity()
```


DAI, कार्डधारक पते का शहर भाग, DL/ID, V20ANS

**Returns:**
java.lang.String
### getAddressPostalCode() {#getAddressPostalCode--}
```
public final String getAddressPostalCode()
```


DAK, यू.एस. और कनाडा में कार्डधारक पते का पोस्टल कोड भाग। यदि यू.एस. में पोस्टल कोड का अंतिम भाग ज्ञात नहीं है, तो शून्य का उपयोग करके अंतिम संख्या सेट को 9 अंकों तक भरा जाएगा, DL/ID, F11ANS

**Returns:**
java.lang.String
### getAddressState() {#getAddressState--}
```
public final String getAddressState()
```


DAJ, कार्डधारक पते का राज्य भाग, DL/ID, F2A

**Returns:**
java.lang.String
### getAddressStreet1() {#getAddressStreet1--}
```
public final String getAddressStreet1()
```


DAG, कार्डधारक पते का सड़क भाग, DL/ID, V35ANS

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCountryIdentification() {#getCountryIdentification--}
```
public final USADriveIdCountry getCountryIdentification()
```


DCG, वह देश जिसमें DL/ID जारी किया जाता है। U.S. = USA, Canada = CAN, DL/ID, F3A

**Returns:**
[USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry)
### getCustomerIDNumber() {#getCustomerIDNumber--}
```
public final String getCustomerIDNumber()
```


DAQ, जारी करने वाले प्राधिकरण द्वारा निर्धारित या गणना किया गया संख्या, DL/ID, V25ANS

**Returns:**
java.lang.String
### getDateOfBirth() {#getDateOfBirth--}
```
public final LocalDate getDateOfBirth()
```


DBB, दस्तावेज़ जारी होने की तिथि, यू.एस. के लिए MMDDCCYY, कनाडा के लिए CCYYMMDD, DL/ID, F8N

**Returns:**
java.time.LocalDate
### getDocumentDiscriminator() {#getDocumentDiscriminator--}
```
public final String getDocumentDiscriminator()
```


DCF, संख्या को उस ग्राहक को जारी किए गए विशिष्ट दस्तावेज़ को अन्य पिछले जारी किए गए दस्तावेज़ों से अद्वितीय रूप से पहचानना चाहिए। यह संख्या दस्तावेज़ भेद, ऑडिट जानकारी संख्या, और/या इन्वेंट्री नियंत्रण जैसे कई उद्देश्यों के लिए उपयोग की जा सकती है, DL/ID, V25ANS

**Returns:**
java.lang.String
### getEndorsementCodes() {#getEndorsementCodes--}
```
public final String getEndorsementCodes()
```


DCD, अधिकार क्षेत्र विशिष्ट समर्थन कोड, DL, V5ANS

**Returns:**
java.lang.String
### getEyeColor() {#getEyeColor--}
```
public final USADriveIdEyeColor getEyeColor()
```


DAY, कार्डधारक की आँखों का रंग। (ANSI D-20 कोड)। DL/ID, F3A

**Returns:**
[USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor)
### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


DCS, कार्डधारक का पारिवारिक नाम, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFamilyNameTruncation() {#getFamilyNameTruncation--}
```
public final String getFamilyNameTruncation()
```


DDE, एक कोड जो दर्शाता है कि कोई फ़ील्ड ट्रंकेट किया गया है (T), नहीं किया गया है (N), या ट्रंकेट किया गया है या नहीं अज्ञात है (U), DL/ID, F1A

**Returns:**
java.lang.String
### getFirstName() {#getFirstName--}
```
public final String getFirstName()
```


DAC, कार्डधारक का पहला नाम, DL/ID, V40ANS

**Returns:**
java.lang.String
### getFirstNameTruncation() {#getFirstNameTruncation--}
```
public final String getFirstNameTruncation()
```


DDF, एक कोड जो दर्शाता है कि कोई फ़ील्ड ट्रंकेट किया गया है (T), नहीं किया गया है (N), या ट्रंकेट किया गया है या नहीं अज्ञात है (U), DL/ID, F1A

**Returns:**
java.lang.String
### getHeight() {#getHeight--}
```
public final String getHeight()
```


DAU, कार्डधारक की ऊँचाई। इंच (in): इंच की संख्या के बाद " in" लिखा जाता है, उदाहरण 6'1'' = "073 in" सेंटीमीटर (cm): सेंटीमीटर की संख्या के बाद " cm" लिखा जाता है, उदाहरण 181 सेंटीमीटर = "181 cm" , DL/ID, F6ANS

**Returns:**
java.lang.String
### getMiddleName() {#getMiddleName--}
```
public final String getMiddleName()
```


DAD, कार्डधारक के मध्यनाम(नाम)। यदि कई मध्यनाम हों तो उन्हें कॉमा "," से अलग किया जाएगा। , DL/ID, V40ANS

**Returns:**
java.lang.String
### getMiddleNameTruncation() {#getMiddleNameTruncation--}
```
public final String getMiddleNameTruncation()
```


DDG, एक कोड जो दर्शाता है कि कोई फ़ील्ड ट्रंकेट किया गया है (T), नहीं किया गया है (N), या ट्रंकेट किया गया है या नहीं अज्ञात है (U), DL/ID, F1A

**Returns:**
java.lang.String
### getRestrictionCodes() {#getRestrictionCodes--}
```
public final String getRestrictionCodes()
```


DCB, अधिकार क्षेत्र-विशिष्ट प्रतिबंध कोड, DL, V12ANS

**Returns:**
java.lang.String
### getSex() {#getSex--}
```
public final USADriveIdSex getSex()
```


DBC, कार्डधारक का लिंग। 1 = पुरुष, 2 = महिला, 9 = निर्दिष्ट नहीं, DL/ID, F1N

**Returns:**
[USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex)
### getVehicleClass() {#getVehicleClass--}
```
public final String getVehicleClass()
```


DCA, अधिकार क्षेत्र-विशिष्ट वाहन वर्ग / समूह कोड, DL, V6ANS

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAddressCity(String value) {#setAddressCity-java.lang.String-}
```
public final void setAddressCity(String value)
```


DAI, कार्डधारक पते का शहर भाग, DL/ID, V20ANS

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setAddressPostalCode(String value) {#setAddressPostalCode-java.lang.String-}
```
public final void setAddressPostalCode(String value)
```


DAK, यू.एस. और कनाडा में कार्डधारक पते का पोस्टल कोड भाग। यदि यू.एस. में पोस्टल कोड का अंतिम भाग ज्ञात नहीं है, तो शून्य का उपयोग करके अंतिम संख्या सेट को 9 अंकों तक भरा जाएगा, DL/ID, F11ANS

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setAddressState(String value) {#setAddressState-java.lang.String-}
```
public final void setAddressState(String value)
```


DAJ, कार्डधारक पते का राज्य भाग, DL/ID, F2A

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setAddressStreet1(String value) {#setAddressStreet1-java.lang.String-}
```
public final void setAddressStreet1(String value)
```


DAG, कार्डधारक पते का सड़क भाग, DL/ID, V35ANS

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setCountryIdentification(USADriveIdCountry value) {#setCountryIdentification-com.aspose.barcode.complexbarcode.USADriveIdCountry-}
```
public final void setCountryIdentification(USADriveIdCountry value)
```


DCG, वह देश जिसमें DL/ID जारी किया जाता है। U.S. = USA, Canada = CAN, DL/ID, F3A

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [USADriveIdCountry](../../com.aspose.barcode.complexbarcode/usadriveidcountry) |  |

### setCustomerIDNumber(String value) {#setCustomerIDNumber-java.lang.String-}
```
public final void setCustomerIDNumber(String value)
```


DAQ, जारी करने वाले प्राधिकरण द्वारा निर्धारित या गणना किया गया संख्या, DL/ID, V25ANS

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setDateOfBirth(LocalDate value) {#setDateOfBirth-java.time.LocalDate-}
```
public final void setDateOfBirth(LocalDate value)
```


DBB, दस्तावेज़ जारी होने की तिथि, यू.एस. के लिए MMDDCCYY, कनाडा के लिए CCYYMMDD, DL/ID, F8N

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.time.LocalDate |  |

### setDocumentDiscriminator(String value) {#setDocumentDiscriminator-java.lang.String-}
```
public final void setDocumentDiscriminator(String value)
```


DCF, संख्या को उस ग्राहक को जारी किए गए विशिष्ट दस्तावेज़ को अन्य पिछले जारी किए गए दस्तावेज़ों से अद्वितीय रूप से पहचानना चाहिए। यह संख्या दस्तावेज़ भेद, ऑडिट जानकारी संख्या, और/या इन्वेंट्री नियंत्रण जैसे कई उद्देश्यों के लिए उपयोग की जा सकती है, DL/ID, V25ANS

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setEndorsementCodes(String value) {#setEndorsementCodes-java.lang.String-}
```
public final void setEndorsementCodes(String value)
```


DCD, अधिकार क्षेत्र विशिष्ट समर्थन कोड, DL, V5ANS

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setEyeColor(USADriveIdEyeColor value) {#setEyeColor-com.aspose.barcode.complexbarcode.USADriveIdEyeColor-}
```
public final void setEyeColor(USADriveIdEyeColor value)
```


DAY, कार्डधारक की आँखों का रंग। (ANSI D-20 कोड)। DL/ID, F3A

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [USADriveIdEyeColor](../../com.aspose.barcode.complexbarcode/usadriveideyecolor) |  |

### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public final void setFamilyName(String value)
```


DCS, कार्डधारक का पारिवारिक नाम, DL/ID, V40ANS

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setFamilyNameTruncation(String value) {#setFamilyNameTruncation-java.lang.String-}
```
public final void setFamilyNameTruncation(String value)
```


DDE, एक कोड जो दर्शाता है कि कोई फ़ील्ड ट्रंकेट किया गया है (T), नहीं किया गया है (N), या ट्रंकेट किया गया है या नहीं अज्ञात है (U), DL/ID, F1A

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setFirstName(String value) {#setFirstName-java.lang.String-}
```
public final void setFirstName(String value)
```


DAC, कार्डधारक का पहला नाम, DL/ID, V40ANS

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setFirstNameTruncation(String value) {#setFirstNameTruncation-java.lang.String-}
```
public final void setFirstNameTruncation(String value)
```


DDF, एक कोड जो दर्शाता है कि कोई फ़ील्ड ट्रंकेट किया गया है (T), नहीं किया गया है (N), या ट्रंकेट किया गया है या नहीं अज्ञात है (U), DL/ID, F1A

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setHeight(String value) {#setHeight-java.lang.String-}
```
public final void setHeight(String value)
```


DAU, कार्डधारक की ऊँचाई। इंच (in): इंच की संख्या के बाद " in" लिखा जाता है, उदाहरण 6'1'' = "073 in" सेंटीमीटर (cm): सेंटीमीटर की संख्या के बाद " cm" लिखा जाता है, उदाहरण 181 सेंटीमीटर = "181 cm" , DL/ID, F6ANS

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setMiddleName(String value) {#setMiddleName-java.lang.String-}
```
public final void setMiddleName(String value)
```


DAD, कार्डधारक के मध्यनाम(नाम)। यदि कई मध्यनाम हों तो उन्हें कॉमा "," से अलग किया जाएगा। , DL/ID, V40ANS

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setMiddleNameTruncation(String value) {#setMiddleNameTruncation-java.lang.String-}
```
public final void setMiddleNameTruncation(String value)
```


DDG, एक कोड जो दर्शाता है कि कोई फ़ील्ड ट्रंकेट किया गया है (T), नहीं किया गया है (N), या ट्रंकेट किया गया है या नहीं अज्ञात है (U), DL/ID, F1A

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setRestrictionCodes(String value) {#setRestrictionCodes-java.lang.String-}
```
public final void setRestrictionCodes(String value)
```


DCB, अधिकार क्षेत्र-विशिष्ट प्रतिबंध कोड, DL, V12ANS

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setSex(USADriveIdSex value) {#setSex-com.aspose.barcode.complexbarcode.USADriveIdSex-}
```
public final void setSex(USADriveIdSex value)
```


DBC, कार्डधारक का लिंग। 1 = पुरुष, 2 = महिला, 9 = निर्दिष्ट नहीं, DL/ID, F1N

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [USADriveIdSex](../../com.aspose.barcode.complexbarcode/usadriveidsex) |  |

### setVehicleClass(String value) {#setVehicleClass-java.lang.String-}
```
public final void setVehicleClass(String value)
```


DCA, अधिकार क्षेत्र-विशिष्ट वाहन वर्ग / समूह कोड, DL, V6ANS

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

