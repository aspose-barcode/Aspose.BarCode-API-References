---
title: "OptionalFields"
linktitle: "OptionalFields"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "कार्ड के वैकल्पिक तत्व (फ़ील्ड)।"
type: docs
weight: 730
url: /hi/nodejs/aspose.barcode/optionalfields/
---

## OptionalFields class

कार्ड के वैकल्पिक तत्व (फ़ील्ड)।

```js
new OptionalFields()
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [getAliasAKAFamilyName()](#getaliasakafamilyname) | DBN, कार्डधारक के ज्ञात अन्य पारिवारिक नाम, DL/ID, V10ANS |
| [getAliasAKAGivenName()](#getaliasakagivenname) | DBG, कार्डधारक के ज्ञात अन्य दिया गया नाम, DL/ID, V15ANS |
| [getAliasAKASuffixName()](#getaliasakasuffixname) | DBS, कार्डधारक के ज्ञात अन्य उपसर्ग, DL/ID, V5ANS |
| [getAuditInformation()](#getauditinformation) | DCJ, अक्षरों और/या संख्याओं की एक स्ट्रिंग जो यह पहचानती है कि ड्राइवर लाइसेंस/आईडी कार्ड कब, कहाँ और किस द्वारा बनाया गया था। यदि एक |
| [getCardRevisionDate()](#getcardrevisiondate) | DDB, DHS आवश्यक फ़ील्ड जो सबसे हालिया संस्करण परिवर्तन या दृश्यमान फ़ॉर्मेट में संशोधन की तिथि दर्शाता है |
| [getComplianceType()](#getcompliancetype) | DDA, DHS आवश्यक फ़ील्ड जो अनुपालन दर्शाता है: “F” = अनुपालन; और, “N” = गैर-अनुपालन, DL/ID, F1A |
| [getEndorsementCodeDescription()](#getendorsementcodedescription) | DCQ, वह पाठ जो अधिकार क्षेत्र-विशिष्ट कोड(स) को समझाता है जो चालक को अतिरिक्त ड्राइविंग विशेषाधिकार प्रदान करता है |
| [getHairColor()](#gethaircolor) | DAZ, गंजा, काला, सुनहरा, भूरा, ग्रे, लाल/ऑबर्न, रेतिया, सफेद, अज्ञात। यदि जारी करने वाला अधिकार क्षेत्र संक्षिप्त करना चाहता है |
| [getHAZMATEndorsementExpDate()](#gethazmatendorsementexpdate) | DDC, वह तिथि जब दस्तावेज़ द्वारा प्रदान किया गया खतरनाक सामग्री endorsement अब मान्य नहीं रहता। (MMDDCCYY यू.एस. के लिए, CC |
| [getInventoryControlNumber()](#getinventorycontrolnumber) | DCK, अक्षरों और/या संख्याओं की एक स्ट्रिंग जो कच्ची सामग्री (कार्ड स्टॉक, लैमिनेट, आदि) पर चिपकाई जाती है जिसका उपयोग उत्पादन में किया जाता है |
| [getLimitedDurationDocIndicator()](#getlimiteddurationdocindicator) | DDD, DHS आवश्यक फ़ील्ड जो दर्शाता है कि कार्डधारक की अस्थायी वैध स्थिति है = “1”, DL/ID, F1N |
| [getNameSuffix()](#getnamesuffix) | DCU, नाम प्रत्यय (यदि अधिकार क्षेत्र उन प्रणालियों में भाग लेता है जिनमें नाम प्रत्यय की आवश्यकता होती है (PDPS, CDLIS, आदि), तो प्रत्यय होना चाहिए |
| [getOrganDonorIndicator()](#getorgandonorindicator) | DDK, फ़ील्ड जो दर्शाता है कि कार्डधारक अंग दाता है = “1”, DL/ID, F1N |
| [getPlaceOfBirth()](#getplaceofbirth) | DCI, देश और नगरपालिका और/या राज्य/प्रांत, DL/ID, V33A |
| [getRaceEthnicity()](#getraceethnicity) | DCL, कार्डधारक की जाति या जातीयता के कोड, जैसा कि AAMVA D20 में परिभाषित है, DL/ID, V3A |
| [getRestrictionCodeDescription()](#getrestrictioncodedescription) | DCR, वह पाठ जो अधिकार क्षेत्र-विशिष्ट प्रतिबंध कोड(स) का वर्णन करता है जो ड्राइविंग विशेषाधिकार को सीमित करता है, DL, V50ANS |
| [getStandardEndorsementCode()](#getstandardendorsementcode) | DCN, कार्डधारक के लिए मानक endorsement कोड(स)। D20 में कोड देखें। यह डेटा तत्व भविष्य के प्रयासों के लिए एक प्लेसहोल्डर है |
| [getStandardRestrictionCode()](#getstandardrestrictioncode) | DCO, कार्डधारक के लिए मानक प्रतिबंध कोड(स)। D20 में कोड देखें। यह डेटा तत्व भविष्य के प्रयासों के लिए एक प्लेसहोल्डर है |
| [getStandardVehClassification()](#getstandardvehclassification) | DCM, कार्डधारक के लिए मानक वाहन वर्गीकरण कोड(स)। यह डेटा तत्व भविष्य के प्रयासों के लिए एक प्लेसहोल्डर है |
| [getUnder18Until()](#getunder18until) | DDH, वह तिथि जब कार्डधारक की आयु 18 वर्ष हो जाती है। (MMDDCCYY यू.एस. के लिए, CCYYMMDD कनाडा के लिए), DL/ID, F8N |
| [getUnder21Until()](#getunder21until) | DDJ, वह तिथि जब कार्डधारक की आयु 21 वर्ष हो जाती है। (MMDDCCYY यू.एस. के लिए, CCYYMMDD कनाडा के लिए), DL/ID, F8N |
| [getVehClassDescription()](#getvehclassdescription) | DCP, वह पाठ जो अधिकार क्षेत्र-विशिष्ट कोड(स) को समझाता है जो उन वाहन वर्गीकरणों के लिए है जिनके संचालन की अनुमति कार्डधारक को है |
| [getVeteranIndicator()](#getveteranindicator) | DDL, फ़ील्ड जो दर्शाता है कि कार्डधारक एक दिग्गज है = “1”, DL/ID, F1N |
| [getWeightKilograms()](#getweightkilograms) | DAX, कार्डधारक का वजन किलोग्राम में, उदाहरण: 84 किग्रा = “084”, DL/ID, F3N |
| [getWeightPounds()](#getweightpounds) | DAW, कार्डधारक का वजन पाउंड में, उदाहरण: 185 पाउंड = “185”, DL/ID, F3N |
| [getWeightRange()](#getweightrange) | DCE, कार्डधारक के अनुमानित वजन सीमा को दर्शाता है: 0 = 31 किग्रा तक (70 पाउंड तक), 1 = 32 – 45 किग्रा (71 – 100 पाउंड |
| [setAddressStreet2()](#setaddressstreet2) | DAH, कार्डधारक के पते के सड़क भाग की दूसरी पंक्ति, DL/ID, V35ANS |
| [setAliasAKAFamilyName()](#setaliasakafamilyname) | DBN, कार्डधारक के ज्ञात अन्य पारिवारिक नाम, DL/ID, V10ANS |
| [setAliasAKAGivenName()](#setaliasakagivenname) | DBG, कार्डधारक के ज्ञात अन्य दिया गया नाम, DL/ID, V15ANS |
| [setAliasAKASuffixName()](#setaliasakasuffixname) | DBS, कार्डधारक के ज्ञात अन्य उपसर्ग, DL/ID, V5ANS |
| [setAuditInformation()](#setauditinformation) | DCJ, अक्षरों और/या संख्याओं की एक स्ट्रिंग जो यह पहचानती है कि ड्राइवर लाइसेंस/आईडी कार्ड कब, कहाँ और किस द्वारा बनाया गया था। यदि एक |
| [setCardRevisionDate()](#setcardrevisiondate) | DDB, DHS आवश्यक फ़ील्ड जो सबसे हालिया संस्करण परिवर्तन या दृश्यमान फ़ॉर्मेट में संशोधन की तिथि दर्शाता है |
| [setComplianceType()](#setcompliancetype) | DDA, DHS आवश्यक फ़ील्ड जो अनुपालन दर्शाता है: “F” = अनुपालन; और, “N” = गैर-अनुपालन, DL/ID, F1A |
| [setEndorsementCodeDescription()](#setendorsementcodedescription) | DCQ, वह पाठ जो अधिकार क्षेत्र-विशिष्ट कोड(स) को समझाता है जो चालक को अतिरिक्त ड्राइविंग विशेषाधिकार प्रदान करता है |
| [setHairColor()](#sethaircolor) | DAZ, गंजा, काला, सुनहरा, भूरा, ग्रे, लाल/ऑबर्न, रेतिया, सफेद, अज्ञात। यदि जारी करने वाला अधिकार क्षेत्र संक्षिप्त करना चाहता है |
| [setInventoryControlNumber()](#setinventorycontrolnumber) | DCK, अक्षरों और/या संख्याओं की एक स्ट्रिंग जो कच्ची सामग्री (कार्ड स्टॉक, लैमिनेट, आदि) पर चिपकाई जाती है जिसका उपयोग उत्पादन में किया जाता है |
| [setLimitedDurationDocIndicator()](#setlimiteddurationdocindicator) | DDD, DHS आवश्यक फ़ील्ड जो दर्शाता है कि कार्डधारक की अस्थायी वैध स्थिति है = “1”, DL/ID, F1N |
| [setNameSuffix()](#setnamesuffix) | DCU, नाम प्रत्यय (यदि अधिकार क्षेत्र उन प्रणालियों में भाग लेता है जिनमें नाम प्रत्यय की आवश्यकता होती है (PDPS, CDLIS, आदि), तो प्रत्यय होना चाहिए |
| [setOrganDonorIndicator()](#setorgandonorindicator) | DDK, फ़ील्ड जो दर्शाता है कि कार्डधारक अंग दाता है = “1”, DL/ID, F1N |
| [setPlaceOfBirth()](#setplaceofbirth) | DCI, देश और नगरपालिका और/या राज्य/प्रांत, DL/ID, V33A |
| [setRaceEthnicity()](#setraceethnicity) | DCL, कार्डधारक की जाति या जातीयता के कोड, जैसा कि AAMVA D20 में परिभाषित है, DL/ID, V3A |
| [setRestrictionCodeDescription()](#setrestrictioncodedescription) | DCR, वह पाठ जो अधिकार क्षेत्र-विशिष्ट प्रतिबंध कोड(स) का वर्णन करता है जो ड्राइविंग विशेषाधिकार को सीमित करता है, DL, V50ANS |
| [setStandardEndorsementCode()](#setstandardendorsementcode) | DCN, कार्डधारक के लिए मानक endorsement कोड(स)। D20 में कोड देखें। यह डेटा तत्व भविष्य के प्रयासों के लिए एक प्लेसहोल्डर है |
| [setStandardRestrictionCode()](#setstandardrestrictioncode) | DCO, कार्डधारक के लिए मानक प्रतिबंध कोड(स)। D20 में कोड देखें। यह डेटा तत्व भविष्य के प्रयासों के लिए एक प्लेसहोल्डर है |
| [setStandardVehClassification()](#setstandardvehclassification) | DCM, कार्डधारक के लिए मानक वाहन वर्गीकरण कोड(स)। यह डेटा तत्व भविष्य के प्रयासों के लिए एक प्लेसहोल्डर है |
| [setUnder18Until()](#setunder18until) | DDI, वह तिथि जब कार्डधारक की आयु 19 वर्ष हो जाती है। (MMDDCCYY यू.एस. के लिए, CCYYMMDD कनाडा के लिए), DL/ID, F8N |
| [setUnder19Until()](#setunder19until) | DDI, वह तिथि जब कार्डधारक की आयु 19 वर्ष हो जाती है। (MMDDCCYY यू.एस. के लिए, CCYYMMDD कनाडा के लिए), DL/ID, F8N |
| [setUnder21Until()](#setunder21until) | DDJ, वह तिथि जब कार्डधारक की आयु 21 वर्ष हो जाती है। (MMDDCCYY यू.एस. के लिए, CCYYMMDD कनाडा के लिए), DL/ID, F8N |
| [setVehClassDescription()](#setvehclassdescription) | DCP, वह पाठ जो अधिकार क्षेत्र-विशिष्ट कोड(स) को समझाता है जो उन वाहन वर्गीकरणों के लिए है जिनके संचालन की अनुमति कार्डधारक को है |
| [setVeteranIndicator()](#setveteranindicator) | DDL, फ़ील्ड जो दर्शाता है कि कार्डधारक एक दिग्गज है = “1”, DL/ID, F1N |
| [setWeightKilograms()](#setweightkilograms) | DAX, कार्डधारक का वजन किलोग्राम में, उदाहरण: 84 किग्रा = “084”, DL/ID, F3N |
| [setWeightPounds()](#setweightpounds) | DAW, कार्डधारक का वजन पाउंड में, उदाहरण: 185 पाउंड = “185”, DL/ID, F3N |
| [setWeightRange()](#setweightrange) | DCE, कार्डधारक के अनुमानित वजन सीमा को दर्शाता है: 0 = 31 किग्रा तक (70 पाउंड तक), 1 = 32 – 45 किग्रा (71 – 100 पाउंड |

### getAliasAKAFamilyName() {#getaliasakafamilyname}

DBN, कार्डधारक के ज्ञात अन्य पारिवारिक नाम, DL/ID, V10ANS

### getAliasAKAGivenName() {#getaliasakagivenname}

DBG, कार्डधारक के ज्ञात अन्य दिया गया नाम, DL/ID, V15ANS

### getAliasAKASuffixName() {#getaliasakasuffixname}

DBS, कार्डधारक के ज्ञात अन्य उपसर्ग, DL/ID, V5ANS

### getAuditInformation() {#getauditinformation}

DCJ, अक्षरों और/या संख्याओं की एक स्ट्रिंग जो पहचानती है कि ड्राइवर लाइसेंस/आईडी कार्ड कब, कहाँ, और किस द्वारा बनाया गया था। यदि ऑडिट जानकारी कार्ड या MRT पर उपयोग नहीं की गई है, तो इसे ड्राइवर रिकॉर्ड में शामिल किया जाना चाहिए, DL/ID, V25ANS

### getCardRevisionDate() {#getcardrevisiondate}

DDB, DHS द्वारा आवश्यक फ़ील्ड जो DL/ID के दृश्यमान फ़ॉर्मेट में सबसे हालिया संस्करण परिवर्तन या संशोधन की तिथि दर्शाता है। (U.S. के लिए MMDDCCYY, Canada के लिए CCYYMMDD), DL/ID, F8N

### getComplianceType() {#getcompliancetype}

DDA, DHS आवश्यक फ़ील्ड जो अनुपालन दर्शाता है: “F” = अनुपालन; और, “N” = गैर-अनुपालन, DL/ID, F1A

### getEndorsementCodeDescription() {#getendorsementcodedescription}

DCQ, वह पाठ जो अधिकार क्षेत्र-विशिष्ट कोड(s) को समझाता है जो वाहन वर्ग से परे कार्डधारक को प्रदान किए गए अतिरिक्त ड्राइविंग विशेषाधिकारों को दर्शाता है, DL, V50ANS

### getHairColor() {#gethaircolor}

DAZ, गंजा, काला, सुनहरा, भूरा, ग्रे, लाल/ऑबर्न, रेतिया, सफ़ेद, अज्ञात। यदि जारी करने वाला अधिकार क्षेत्र रंगों को संक्षिप्त करना चाहता है, तो AAMVA D20 में प्रदान किए गए तीन-अक्षर कोड का उपयोग करना अनिवार्य है, DL/ID, V12A

### getHAZMATEndorsementExpDate() {#gethazmatendorsementexpdate}

DDC, वह तिथि जिस दिन दस्तावेज़ द्वारा प्रदान किया गया खतरनाक सामग्री endorsement अब मान्य नहीं रहता। (U.S. के लिए MMDDCCYY, Canada के लिए CCYYMMDD), DL, F8N

### getInventoryControlNumber() {#getinventorycontrolnumber}

DCK, अक्षरों और/या संख्याओं की एक स्ट्रिंग जो ड्राइवर लाइसेंस और ID कार्ड बनाने में उपयोग किए जाने वाले कच्चे सामग्री (कार्ड स्टॉक, लैमिनेट आदि) पर चिपकाई जाती है। (DHS द्वारा अनुशंसित फ़ील्ड), DL/ID, V25ANS

### getLimitedDurationDocIndicator() {#getlimiteddurationdocindicator}

DDD, DHS आवश्यक फ़ील्ड जो दर्शाता है कि कार्डधारक की अस्थायी वैध स्थिति है = “1”, DL/ID, F1N

### getNameSuffix() {#getnamesuffix}

DCU, नाम प्रत्यय (यदि अधिकार क्षेत्र उन प्रणालियों में भाग लेता है जो नाम प्रत्यय (PDPS, CDLIS आदि) की आवश्यकता रखते हैं, तो प्रत्यय को DL/ID और MRT में एकत्रित और प्रदर्शित किया जाना चाहिए)। JR (Junior), SR (Senior), 1ST या I (First), 9TH या IX (Ninth) तक, DL/ID, V5ANS

### getOrganDonorIndicator() {#getorgandonorindicator}

DDK, फ़ील्ड जो दर्शाता है कि कार्डधारक अंग दाता है = “1”, DL/ID, F1N

### getPlaceOfBirth() {#getplaceofbirth}

DCI, देश और नगरपालिका और/या राज्य/प्रांत, DL/ID, V33A

### getRaceEthnicity() {#getraceethnicity}

DCL, कार्डधारक की जाति या जातीयता के कोड, जैसा कि AAMVA D20 में परिभाषित है, DL/ID, V3A

### getRestrictionCodeDescription() {#getrestrictioncodedescription}

DCR, वह पाठ जो अधिकार क्षेत्र-विशिष्ट प्रतिबंध कोड(स) का वर्णन करता है जो ड्राइविंग विशेषाधिकार को सीमित करता है, DL, V50ANS

### getStandardEndorsementCode() {#getstandardendorsementcode}

DCN, कार्डधारक के लिए मानक endorsement कोड(s)। D20 में कोड देखें। यह डेटा तत्व भविष्य में endorsement कोड को मानकीकृत करने के प्रयासों के लिए एक प्लेसहोल्डर है, DL, F5AN

### getStandardRestrictionCode() {#getstandardrestrictioncode}

DCO, कार्डधारक के लिए मानक restriction कोड(s)। D20 में कोड देखें। यह डेटा तत्व भविष्य में restriction कोड को मानकीकृत करने के प्रयासों के लिए एक प्लेसहोल्डर है, DL, F12AN

### getStandardVehClassification() {#getstandardvehclassification}

DCM, कार्डधारक के लिए मानक वाहन वर्गीकरण कोड(s)। यह डेटा तत्व भविष्य में वाहन वर्गीकरण को मानकीकृत करने के प्रयासों के लिए एक प्लेसहोल्डर है, DL, F4AN

### getUnder18Until() {#getunder18until}

DDH, वह तिथि जब कार्डधारक की आयु 18 वर्ष हो जाती है। (MMDDCCYY यू.एस. के लिए, CCYYMMDD कनाडा के लिए), DL/ID, F8N

### getUnder21Until() {#getunder21until}

DDJ, वह तिथि जब कार्डधारक की आयु 21 वर्ष हो जाती है। (MMDDCCYY यू.एस. के लिए, CCYYMMDD कनाडा के लिए), DL/ID, F8N

### getVehClassDescription() {#getvehclassdescription}

DCP, वह पाठ जो अधिकार क्षेत्र-विशिष्ट कोड(s) को समझाता है जो उन वाहन वर्गीकरणों को दर्शाते हैं जिन्हें कार्डधारक चलाने के लिए अधिकृत है, DL, V50ANS

### getVeteranIndicator() {#getveteranindicator}

DDL, फ़ील्ड जो दर्शाता है कि कार्डधारक एक दिग्गज है = “1”, DL/ID, F1N

### getWeightKilograms() {#getweightkilograms}

DAX, कार्डधारक का वजन किलोग्राम में, उदाहरण: 84 किग्रा = “084”, DL/ID, F3N

### getWeightPounds() {#getweightpounds}

DAW, कार्डधारक का वजन पाउंड में, उदाहरण: 185 पाउंड = “185”, DL/ID, F3N

### getWeightRange() {#getweightrange}

DCE, कार्डधारक के अनुमानित वजन सीमा को दर्शाता है: 0 = 31 किग्रा तक (70 पाउंड तक), 1 = 32 – 45 किग्रा (71 – 100 पाउंड), 2 = 46 - 59 किग्रा (101 – 130 पाउंड), 3 = 60 - 70 किग्रा (131 – 160 पाउंड), 4 = 71 - 86 किग्रा (161 – 190 पाउंड), 5 = 87 - 100 किग्रा (191 – 220 पाउंड), 6 = 101 - 113 किग्रा (221 – 250 पाउंड), 7 = 114 - 127 किग्रा (251 – 280 पाउंड), 8 = 128 – 145 किग्रा (281 – 320 पाउंड), 9 = 146+ किग्रा (321+ पाउंड), DL/ID, F1N

### setAddressStreet2() {#setaddressstreet2}

DAH, कार्डधारक के पते के सड़क भाग की दूसरी पंक्ति, DL/ID, V35ANS

### setAliasAKAFamilyName() {#setaliasakafamilyname}

DBN, कार्डधारक के ज्ञात अन्य पारिवारिक नाम, DL/ID, V10ANS

### setAliasAKAGivenName() {#setaliasakagivenname}

DBG, कार्डधारक के ज्ञात अन्य दिया गया नाम, DL/ID, V15ANS

### setAliasAKASuffixName() {#setaliasakasuffixname}

DBS, कार्डधारक के ज्ञात अन्य उपसर्ग, DL/ID, V5ANS

### setAuditInformation() {#setauditinformation}

DCJ, अक्षरों और/या संख्याओं की एक स्ट्रिंग जो पहचानती है कि ड्राइवर लाइसेंस/आईडी कार्ड कब, कहाँ, और किस द्वारा बनाया गया था। यदि ऑडिट जानकारी कार्ड या MRT पर उपयोग नहीं की गई है, तो इसे ड्राइवर रिकॉर्ड में शामिल किया जाना चाहिए, DL/ID, V25ANS

### setCardRevisionDate() {#setcardrevisiondate}

DDB, DHS द्वारा आवश्यक फ़ील्ड जो DL/ID के दृश्यमान फ़ॉर्मेट में सबसे हालिया संस्करण परिवर्तन या संशोधन की तिथि दर्शाता है। (U.S. के लिए MMDDCCYY, Canada के लिए CCYYMMDD), DL/ID, F8N

### setComplianceType() {#setcompliancetype}

DDA, DHS आवश्यक फ़ील्ड जो अनुपालन दर्शाता है: “F” = अनुपालन; और, “N” = गैर-अनुपालन, DL/ID, F1A

### setEndorsementCodeDescription() {#setendorsementcodedescription}

DCQ, वह पाठ जो अधिकार क्षेत्र-विशिष्ट कोड(s) को समझाता है जो वाहन वर्ग से परे कार्डधारक को प्रदान किए गए अतिरिक्त ड्राइविंग विशेषाधिकारों को दर्शाता है, DL, V50ANS

### setHairColor() {#sethaircolor}

DAZ, गंजा, काला, सुनहरा, भूरा, ग्रे, लाल/ऑबर्न, रेतिया, सफ़ेद, अज्ञात। यदि जारी करने वाला अधिकार क्षेत्र रंगों को संक्षिप्त करना चाहता है, तो AAMVA D20 में प्रदान किए गए तीन-अक्षर कोड का उपयोग करना अनिवार्य है, DL/ID, V12A

### setInventoryControlNumber() {#setinventorycontrolnumber}

DCK, अक्षरों और/या संख्याओं की एक स्ट्रिंग जो ड्राइवर लाइसेंस और ID कार्ड बनाने में उपयोग किए जाने वाले कच्चे सामग्री (कार्ड स्टॉक, लैमिनेट आदि) पर चिपकाई जाती है। (DHS द्वारा अनुशंसित फ़ील्ड), DL/ID, V25ANS

### setLimitedDurationDocIndicator() {#setlimiteddurationdocindicator}

DDD, DHS आवश्यक फ़ील्ड जो दर्शाता है कि कार्डधारक की अस्थायी वैध स्थिति है = “1”, DL/ID, F1N

### setNameSuffix() {#setnamesuffix}

DCU, नाम प्रत्यय (यदि अधिकार क्षेत्र उन प्रणालियों में भाग लेता है जो नाम प्रत्यय (PDPS, CDLIS आदि) की आवश्यकता रखते हैं, तो प्रत्यय को DL/ID और MRT में एकत्रित और प्रदर्शित किया जाना चाहिए)। JR (Junior), SR (Senior), 1ST या I (First), 9TH या IX (Ninth) तक, DL/ID, V5ANS

### setOrganDonorIndicator() {#setorgandonorindicator}

DDK, फ़ील्ड जो दर्शाता है कि कार्डधारक अंग दाता है = “1”, DL/ID, F1N

### setPlaceOfBirth() {#setplaceofbirth}

DCI, देश और नगरपालिका और/या राज्य/प्रांत, DL/ID, V33A

### setRaceEthnicity() {#setraceethnicity}

DCL, कार्डधारक की जाति या जातीयता के कोड, जैसा कि AAMVA D20 में परिभाषित है, DL/ID, V3A

### setRestrictionCodeDescription() {#setrestrictioncodedescription}

DCR, वह पाठ जो अधिकार क्षेत्र-विशिष्ट प्रतिबंध कोड(स) का वर्णन करता है जो ड्राइविंग विशेषाधिकार को सीमित करता है, DL, V50ANS

### setStandardEndorsementCode() {#setstandardendorsementcode}

DCN, कार्डधारक के लिए मानक endorsement कोड(s)। D20 में कोड देखें। यह डेटा तत्व भविष्य में endorsement कोड को मानकीकृत करने के प्रयासों के लिए एक प्लेसहोल्डर है, DL, F5AN

### setStandardRestrictionCode() {#setstandardrestrictioncode}

DCO, कार्डधारक के लिए मानक restriction कोड(s)। D20 में कोड देखें। यह डेटा तत्व भविष्य में restriction कोड को मानकीकृत करने के प्रयासों के लिए एक प्लेसहोल्डर है, DL, F12AN

### setStandardVehClassification() {#setstandardvehclassification}

DCM, कार्डधारक के लिए मानक वाहन वर्गीकरण कोड(s)। यह डेटा तत्व भविष्य में वाहन वर्गीकरण को मानकीकृत करने के प्रयासों के लिए एक प्लेसहोल्डर है, DL, F4AN

### setUnder18Until() {#setunder18until}

DDI, वह तिथि जब कार्डधारक की आयु 19 वर्ष हो जाती है। (MMDDCCYY यू.एस. के लिए, CCYYMMDD कनाडा के लिए), DL/ID, F8N

### setUnder19Until() {#setunder19until}

DDI, वह तिथि जब कार्डधारक की आयु 19 वर्ष हो जाती है। (MMDDCCYY यू.एस. के लिए, CCYYMMDD कनाडा के लिए), DL/ID, F8N

### setUnder21Until() {#setunder21until}

DDJ, वह तिथि जब कार्डधारक की आयु 21 वर्ष हो जाती है। (MMDDCCYY यू.एस. के लिए, CCYYMMDD कनाडा के लिए), DL/ID, F8N

### setVehClassDescription() {#setvehclassdescription}

DCP, वह पाठ जो अधिकार क्षेत्र-विशिष्ट कोड(s) को समझाता है जो उन वाहन वर्गीकरणों को दर्शाते हैं जिन्हें कार्डधारक चलाने के लिए अधिकृत है, DL, V50ANS

### setVeteranIndicator() {#setveteranindicator}

DDL, फ़ील्ड जो दर्शाता है कि कार्डधारक एक दिग्गज है = “1”, DL/ID, F1N

### setWeightKilograms() {#setweightkilograms}

DAX, कार्डधारक का वजन किलोग्राम में, उदाहरण: 84 किग्रा = “084”, DL/ID, F3N

### setWeightPounds() {#setweightpounds}

DAW, कार्डधारक का वजन पाउंड में, उदाहरण: 185 पाउंड = “185”, DL/ID, F3N

### setWeightRange() {#setweightrange}

DCE, कार्डधारक के अनुमानित वजन सीमा को दर्शाता है: 0 = 31 किग्रा तक (70 पाउंड तक), 1 = 32 – 45 किग्रा (71 – 100 पाउंड), 2 = 46 - 59 किग्रा (101 – 130 पाउंड), 3 = 60 - 70 किग्रा (131 – 160 पाउंड), 4 = 71 - 86 किग्रा (161 – 190 पाउंड), 5 = 87 - 100 किग्रा (191 – 220 पाउंड), 6 = 101 - 113 किग्रा (221 – 250 पाउंड), 7 = 114 - 127 किग्रा (251 – 280 पाउंड), 8 = 128 – 145 किग्रा (281 – 320 पाउंड), 9 = 146+ किग्रा (321+ पाउंड), DL/ID, F1N
