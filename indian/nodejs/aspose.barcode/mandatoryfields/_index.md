---
title: "अनिवार्य फ़ील्ड्स"
linktitle: "अनिवार्य फ़ील्ड्स"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "कार्ड के अनिवार्य तत्व (फ़ील्ड)।"
type: docs
weight: 590
url: /hi/nodejs/aspose.barcode/mandatoryfields/
---

## MandatoryFields class

कार्ड के अनिवार्य तत्व (फ़ील्ड)।

```js
new MandatoryFields()
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getAddressCity()](#getaddresscity) | DAI, कार्डधारक पते का शहर भाग, DL/ID, V20ANS |
| [getAddressPostalCode()](#getaddresspostalcode) | DAK, संयुक्त राज्य और कनाडा में कार्डधारक पते का पोस्टल कोड भाग। यदि पोस्टल कोड का अंतिम भाग में |
| [getAddressState()](#getaddressstate) | DAJ, कार्डधारक पते का राज्य भाग, DL/ID, F2A |
| [getAddressStreet1()](#getaddressstreet1) | DAG, कार्डधारक पते का सड़क भाग, DL/ID, V35ANS |
| [getCountryIdentification()](#getcountryidentification) | DCG, वह देश जहाँ DL/ID जारी किया जाता है। U.S. = USA, Canada = CAN, DL/ID, F3A |
| [getCustomerIDNumber()](#getcustomeridnumber) | DAQ, जारी करने वाले प्राधिकरण द्वारा निर्धारित या गणना किया गया संख्या, DL/ID, V25ANS |
| [getDateOfBirth()](#getdateofbirth) | DBB, वह तिथि जब दस्तावेज जारी किया गया था, U.S. के लिए MMDDCCYY, Canada के लिए CCYYMMDD, DL/ID, F8N |
| [getDocumentDiscriminator()](#getdocumentdiscriminator) | DCF, संख्या को उस ग्राहक को जारी किए गए विशिष्ट दस्तावेज़ को अन्य जारी किए गए दस्तावेज़ों से अद्वितीय रूप से पहचानना चाहिए। |
| [getEndorsementCodes()](#getendorsementcodes) | DCD, अधिकार क्षेत्र विशिष्ट समर्थन कोड, DL, V5ANS |
| [getEyeColor()](#geteyecolor) | DAY, कार्डधारक की आँखों का रंग। (ANSI D-20 कोड)। DL/ID, F3A |
| [getFamilyName()](#getfamilyname) | DCS, कार्डधारक का पारिवारिक नाम, DL/ID, V40ANS |
| [getFamilyNameTruncation()](#getfamilynametruncation) | DDE, एक कोड जो दर्शाता है कि कोई फ़ील्ड छोटा किया गया है (T), छोटा नहीं किया गया है (N), या यह अज्ञात है कि छोटा किया गया है या नहीं |
| [getFirstName()](#getfirstname) | DAC, कार्डधारक का पहला नाम, DL/ID, V40ANS |
| [getFirstNameTruncation()](#getfirstnametruncation) | DDF, एक कोड जो दर्शाता है कि कोई फ़ील्ड छोटा किया गया है (T), छोटा नहीं किया गया है (N), या यह अज्ञात है कि छोटा किया गया है या नहीं |
| [getHeight()](#getheight) | DAU, कार्डधारक की ऊँचाई। इंच (in): इंच की संख्या के बाद " in" लिखा जाता है, उदाहरण 6'1'' = "073 in" सेंटीमीटर (cm): सेंटीमीटर की संख्या |
| [getMiddleName()](#getmiddlename) | DAD, कार्डधारक के मध्य नाम। यदि कई मध्य नाम हों तो उन्हें कॉमा "," से अलग किया जाएगा। , DL |
| [getMiddleNameTruncation()](#getmiddlenametruncation) | DDG, एक कोड जो दर्शाता है कि कोई फ़ील्ड छोटा किया गया है (T), छोटा नहीं किया गया है (N), या यह अज्ञात है कि छोटा किया गया है या नहीं |
| [getRestrictionCodes()](#getrestrictioncodes) | DCB, अधिकार क्षेत्र-विशिष्ट प्रतिबंध कोड, DL, V12ANS |
| [getSex()](#getsex) | DBC, कार्डधारक का लिंग। 1 = पुरुष, 2 = महिला, 9 = निर्दिष्ट नहीं, DL/ID, F1N |
| [getVehicleClass()](#getvehicleclass) | DCA, अधिकार क्षेत्र-विशिष्ट वाहन वर्ग / समूह कोड, DL, V6ANS |
| [setAddressCity()](#setaddresscity) | DAI, कार्डधारक पते का शहर भाग, DL/ID, V20ANS |
| [setAddressPostalCode()](#setaddresspostalcode) | DAK, संयुक्त राज्य और कनाडा में कार्डधारक पते का पोस्टल कोड भाग। यदि पोस्टल कोड का अंतिम भाग में |
| [setAddressState()](#setaddressstate) | DAJ, कार्डधारक पते का राज्य भाग, DL/ID, F2A |
| [setAddressStreet1()](#setaddressstreet1) | DAG, कार्डधारक पते का सड़क भाग, DL/ID, V35ANS |
| [setCountryIdentification()](#setcountryidentification) | DCG, वह देश जहाँ DL/ID जारी किया जाता है। U.S. = USA, Canada = CAN, DL/ID, F3A |
| [setCustomerIDNumber()](#setcustomeridnumber) | DAQ, जारी करने वाले प्राधिकरण द्वारा निर्धारित या गणना किया गया संख्या, DL/ID, V25ANS |
| [setDateOfBirth()](#setdateofbirth) | DBB, वह तिथि जब दस्तावेज जारी किया गया था, U.S. के लिए MMDDCCYY, Canada के लिए CCYYMMDD, DL/ID, F8N |
| [setDocumentDiscriminator()](#setdocumentdiscriminator) | DCF, संख्या को उस ग्राहक को जारी किए गए विशिष्ट दस्तावेज़ को अन्य जारी किए गए दस्तावेज़ों से अद्वितीय रूप से पहचानना चाहिए। |
| [setEndorsementCodes()](#setendorsementcodes) | DCD, अधिकार क्षेत्र विशिष्ट समर्थन कोड, DL, V5ANS |
| [setEyeColor()](#seteyecolor) | DAY, कार्डधारक की आँखों का रंग। (ANSI D-20 कोड)। DL/ID, F3A |
| [setFamilyName()](#setfamilyname) | DCS, कार्डधारक का पारिवारिक नाम, DL/ID, V40ANS |
| [setFamilyNameTruncation()](#setfamilynametruncation) | DDE, एक कोड जो दर्शाता है कि कोई फ़ील्ड छोटा किया गया है (T), छोटा नहीं किया गया है (N), या यह अज्ञात है कि छोटा किया गया है या नहीं |
| [setFirstName()](#setfirstname) | DAC, कार्डधारक का पहला नाम, DL/ID, V40ANS |
| [setFirstNameTruncation()](#setfirstnametruncation) | DDF, एक कोड जो दर्शाता है कि कोई फ़ील्ड छोटा किया गया है (T), छोटा नहीं किया गया है (N), या यह अज्ञात है कि छोटा किया गया है या नहीं |
| [setHeight()](#setheight) | DAU, कार्डधारक की ऊँचाई। इंच (in): इंच की संख्या के बाद " in" लिखा जाता है, उदाहरण 6'1'' = "073 in" सेंटीमीटर (cm): सेंटीमीटर की संख्या |
| [setMiddleName()](#setmiddlename) | DAD, कार्डधारक के मध्य नाम। यदि कई मध्य नाम हों तो उन्हें कॉमा "," से अलग किया जाएगा। , DL |
| [setMiddleNameTruncation()](#setmiddlenametruncation) | DDG, एक कोड जो दर्शाता है कि कोई फ़ील्ड छोटा किया गया है (T), छोटा नहीं किया गया है (N), या यह अज्ञात है कि छोटा किया गया है या नहीं |
| [setRestrictionCodes()](#setrestrictioncodes) | DCB, अधिकार क्षेत्र-विशिष्ट प्रतिबंध कोड, DL, V12ANS |
| [setSex()](#setsex) | DBC, कार्डधारक का लिंग। 1 = पुरुष, 2 = महिला, 9 = निर्दिष्ट नहीं, DL/ID, F1N |
| [setVehicleClass()](#setvehicleclass) | DCA, अधिकार क्षेत्र-विशिष्ट वाहन वर्ग / समूह कोड, DL, V6ANS |

### getAddressCity() {#getaddresscity}

DAI, कार्डधारक पते का शहर भाग, DL/ID, V20ANS

### getAddressPostalCode() {#getaddresspostalcode}

DAK, U.S. और Canada में कार्डधारक के पते का पोस्टल कोड भाग। यदि U.S. में पोस्टल कोड का अंतिम भाग ज्ञात नहीं है, तो 9 अंकों तक शून्य से भर दिया जाएगा, DL/ID, F11ANS

### getAddressState() {#getaddressstate}

DAJ, कार्डधारक पते का राज्य भाग, DL/ID, F2A

### getAddressStreet1() {#getaddressstreet1}

DAG, कार्डधारक पते का सड़क भाग, DL/ID, V35ANS

### getCountryIdentification() {#getcountryidentification}

DCG, वह देश जहाँ DL/ID जारी किया जाता है। U.S. = USA, Canada = CAN, DL/ID, F3A

### getCustomerIDNumber() {#getcustomeridnumber}

DAQ, जारी करने वाले प्राधिकरण द्वारा निर्धारित या गणना किया गया संख्या, DL/ID, V25ANS

### getDateOfBirth() {#getdateofbirth}

DBB, वह तिथि जब दस्तावेज जारी किया गया था, U.S. के लिए MMDDCCYY, Canada के लिए CCYYMMDD, DL/ID, F8N

### getDocumentDiscriminator() {#getdocumentdiscriminator}

DCF, संख्या को उस ग्राहक को जारी किए गए विशिष्ट दस्तावेज़ को पिछले जारी किए गए अन्य दस्तावेज़ों से अद्वितीय रूप से पहचानना चाहिए। यह संख्या दस्तावेज़ विभेद, ऑडिट जानकारी संख्या, और/या इन्वेंट्री नियंत्रण जैसे कई उद्देश्यों के लिए उपयोग की जा सकती है, DL/ID, V25ANS

### getEndorsementCodes() {#getendorsementcodes}

DCD, अधिकार क्षेत्र विशिष्ट समर्थन कोड, DL, V5ANS

### getEyeColor() {#geteyecolor}

DAY, कार्डधारक की आँखों का रंग। (ANSI D-20 कोड)। DL/ID, F3A

### getFamilyName() {#getfamilyname}

DCS, कार्डधारक का पारिवारिक नाम, DL/ID, V40ANS

### getFamilyNameTruncation() {#getfamilynametruncation}

DDE, एक कोड जो दर्शाता है कि कोई फ़ील्ड छोटा किया गया है (T), छोटा नहीं किया गया है (N), या यह अज्ञात है कि छोटा किया गया है (U), DL/ID, F1A

### getFirstName() {#getfirstname}

DAC, कार्डधारक का पहला नाम, DL/ID, V40ANS

### getFirstNameTruncation() {#getfirstnametruncation}

DDF, एक कोड जो दर्शाता है कि कोई फ़ील्ड छोटा किया गया है (T), छोटा नहीं किया गया है (N), या यह अज्ञात है कि छोटा किया गया है (U), DL/ID, F1A

### getHeight() {#getheight}

DAU, कार्डधारक की ऊँचाई। इंच (in): इंच की संख्या के बाद " in" लिखा जाता है, उदाहरण 6'1'' = "073 in" सेंटीमीटर (cm): सेंटीमीटर की संख्या के बाद " cm" लिखा जाता है, उदाहरण 181 सेंटीमीटर = "181 cm" , DL/ID, F6ANS

### getMiddleName() {#getmiddlename}

DAD, कार्डधारक के मध्य नाम। यदि कई मध्य नाम हों तो उन्हें कॉमा "," से अलग किया जाएगा। , DL/ID, V40ANS

### getMiddleNameTruncation() {#getmiddlenametruncation}

DDG, एक कोड जो दर्शाता है कि कोई फ़ील्ड छोटा किया गया है (T), छोटा नहीं किया गया है (N), या यह अज्ञात है कि छोटा किया गया है (U), DL/ID, F1A

### getRestrictionCodes() {#getrestrictioncodes}

DCB, अधिकार क्षेत्र-विशिष्ट प्रतिबंध कोड, DL, V12ANS

### getSex() {#getsex}

DBC, कार्डधारक का लिंग। 1 = पुरुष, 2 = महिला, 9 = निर्दिष्ट नहीं, DL/ID, F1N

### getVehicleClass() {#getvehicleclass}

DCA, अधिकार क्षेत्र-विशिष्ट वाहन वर्ग / समूह कोड, DL, V6ANS

### setAddressCity() {#setaddresscity}

DAI, कार्डधारक पते का शहर भाग, DL/ID, V20ANS

### setAddressPostalCode() {#setaddresspostalcode}

DAK, U.S. और Canada में कार्डधारक के पते का पोस्टल कोड भाग। यदि U.S. में पोस्टल कोड का अंतिम भाग ज्ञात नहीं है, तो 9 अंकों तक शून्य से भर दिया जाएगा, DL/ID, F11ANS

### setAddressState() {#setaddressstate}

DAJ, कार्डधारक पते का राज्य भाग, DL/ID, F2A

### setAddressStreet1() {#setaddressstreet1}

DAG, कार्डधारक पते का सड़क भाग, DL/ID, V35ANS

### setCountryIdentification() {#setcountryidentification}

DCG, वह देश जहाँ DL/ID जारी किया जाता है। U.S. = USA, Canada = CAN, DL/ID, F3A

### setCustomerIDNumber() {#setcustomeridnumber}

DAQ, जारी करने वाले प्राधिकरण द्वारा निर्धारित या गणना किया गया संख्या, DL/ID, V25ANS

### setDateOfBirth() {#setdateofbirth}

DBB, वह तिथि जब दस्तावेज जारी किया गया था, U.S. के लिए MMDDCCYY, Canada के लिए CCYYMMDD, DL/ID, F8N

### setDocumentDiscriminator() {#setdocumentdiscriminator}

DCF, संख्या को उस ग्राहक को जारी किए गए विशिष्ट दस्तावेज़ को पिछले जारी किए गए अन्य दस्तावेज़ों से अद्वितीय रूप से पहचानना चाहिए। यह संख्या दस्तावेज़ विभेद, ऑडिट जानकारी संख्या, और/या इन्वेंट्री नियंत्रण जैसे कई उद्देश्यों के लिए उपयोग की जा सकती है, DL/ID, V25ANS

### setEndorsementCodes() {#setendorsementcodes}

DCD, अधिकार क्षेत्र विशिष्ट समर्थन कोड, DL, V5ANS

### setEyeColor() {#seteyecolor}

DAY, कार्डधारक की आँखों का रंग। (ANSI D-20 कोड)। DL/ID, F3A

### setFamilyName() {#setfamilyname}

DCS, कार्डधारक का पारिवारिक नाम, DL/ID, V40ANS

### setFamilyNameTruncation() {#setfamilynametruncation}

DDE, एक कोड जो दर्शाता है कि कोई फ़ील्ड छोटा किया गया है (T), छोटा नहीं किया गया है (N), या यह अज्ञात है कि छोटा किया गया है (U), DL/ID, F1A

### setFirstName() {#setfirstname}

DAC, कार्डधारक का पहला नाम, DL/ID, V40ANS

### setFirstNameTruncation() {#setfirstnametruncation}

DDF, एक कोड जो दर्शाता है कि कोई फ़ील्ड छोटा किया गया है (T), छोटा नहीं किया गया है (N), या यह अज्ञात है कि छोटा किया गया है (U), DL/ID, F1A

### setHeight() {#setheight}

DAU, कार्डधारक की ऊँचाई। इंच (in): इंच की संख्या के बाद " in" लिखा जाता है, उदाहरण 6'1'' = "073 in" सेंटीमीटर (cm): सेंटीमीटर की संख्या के बाद " cm" लिखा जाता है, उदाहरण 181 सेंटीमीटर = "181 cm" , DL/ID, F6ANS

### setMiddleName() {#setmiddlename}

DAD, कार्डधारक के मध्य नाम। यदि कई मध्य नाम हों तो उन्हें कॉमा "," से अलग किया जाएगा। , DL/ID, V40ANS

### setMiddleNameTruncation() {#setmiddlenametruncation}

DDG, एक कोड जो दर्शाता है कि कोई फ़ील्ड छोटा किया गया है (T), छोटा नहीं किया गया है (N), या यह अज्ञात है कि छोटा किया गया है (U), DL/ID, F1A

### setRestrictionCodes() {#setrestrictioncodes}

DCB, अधिकार क्षेत्र-विशिष्ट प्रतिबंध कोड, DL, V12ANS

### setSex() {#setsex}

DBC, कार्डधारक का लिंग। 1 = पुरुष, 2 = महिला, 9 = निर्दिष्ट नहीं, DL/ID, F1N

### setVehicleClass() {#setvehicleclass}

DCA, अधिकार क्षेत्र-विशिष्ट वाहन वर्ग / समूह कोड, DL, V6ANS
