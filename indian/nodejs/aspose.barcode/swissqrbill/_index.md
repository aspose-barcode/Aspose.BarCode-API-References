---
title: "SwissQRBill"
linktitle: "SwissQRBill"
second_title: "Aspose.BarCode के लिए Node.js via Java API संदर्भ"
description: "SwissQR बिल डेटा"
type: docs
weight: 920
url: /hi/nodejs/aspose.barcode/swissqrbill/
---

## SwissQRBill class

SwissQR बिल डेटा

```js
new SwissQRBill()
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [createAndSetCreditorReference(rawReference)](#createandsetcreditorreference) | एक कच्ची स्ट्रिंग से ISO11649 क्रेडिटर रेफ़रेंस बनाता और सेट करता है, स्ट्रिंग को "RF" से प्रीफ़िक्स करके और मॉड्यूलो 97 चेक जोड़कर। |
| [equals(obj)](#equals) | निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट वर्तमान ऑब्जेक्ट के बराबर है या नहीं। |
| [getAccount()](#getaccount) | क्रेडिटर का खाता नंबर प्राप्त करता है। खाता नंबर स्विट्ज़रलैंड या लिचेंस्टीन के बैंक के वैध IBAN होने चाहिए। स्पेस |
| [getAlternativeSchemes()](#getalternativeschemes) | वैकल्पिक भुगतान योजनाओं को प्राप्त करता या सेट करता है। अधिकतम दो योजनाओं को पैरामीटर के साथ अनुमति है। |
| [getAmount()](#getamount) | भुगतान राशि प्राप्त करता है। मान्य मान 0.01 से 999,999,999.99 के बीच हैं। |
| [getBillInformation()](#getbillinformation) | अतिरिक्त संरचित बिल जानकारी प्राप्त करता है। |
| [getCreditor()](#getcreditor) | क्रेडिटर का पता प्राप्त करता है। |
| [getCurrency()](#getcurrency) | भुगतान मुद्रा प्राप्त करता है। मान्य मान "CHF" और "EUR" हैं। |
| [getDebtor()](#getdebtor) | लेनदार का पता प्राप्त करता है। लेनदार वैकल्पिक है। यदि इसे छोड़ दिया जाता है, तो इस फ़ील्ड को null सेट करना या पता सेट करना दोनों संभव है। |
| [getReference()](#getreference) | लेनदाता भुगतान संदर्भ प्राप्त करता है। यह संदर्भ SwissQR IBANs के लिए अनिवार्य है, अर्थात CHxx30000xxxxx रेंज के IBANs। |
| [getUnstructuredMessage()](#getunstructuredmessage) | अतिरिक्त असंरचित संदेश प्राप्त करता है। |
| [getVersion()](#getversion) | SwissQR बिल मानक का संस्करण प्राप्त करता है। |
| [hashCode()](#hashcode) | इस उदाहरण के लिए हैश कोड प्राप्त करता है। |
| [setAccount(value:)](#setaccount) | लेनदाता का खाता नंबर सेट करता है। खाता नंबर स्विट्ज़रलैंड या लिचेंस्टीन के बैंक के वैध IBANs होने चाहिए। स्पेस |
| [setAlternativeSchemes(value:)](#setalternativeschemes) | वैकल्पिक भुगतान योजनाओं को प्राप्त या सेट करता है। अधिकतम दो योजनाएँ पैरामीटर के साथ अनुमति हैं। |
| [setAmount(value)](#setamount) | भुगतान राशि सेट करता है। मान्य मान 0.01 से 999,999,999.99 के बीच हैं। |
| [setBillInformation(value:)](#setbillinformation) | अतिरिक्त संरचित बिल जानकारी सेट करता है। |
| [setCreditor(value:)](#setcreditor) | लेनदाता का पता सेट करता है। |
| [setCurrency(value)](#setcurrency) | भुगतान मुद्रा सेट करता है। |
| [setDebtor(value:)](#setdebtor) | लेनदार का पता सेट करता है। लेनदार वैकल्पिक है। यदि इसे छोड़ दिया जाता है, तो इस फ़ील्ड को null सेट करना या पता सेट करना दोनों संभव है। |
| [setReference(value)](#setreference) | लेनदाता भुगतान संदर्भ सेट करता है। यह संदर्भ SwissQR IBANs के लिए अनिवार्य है, अर्थात CHxx30000xxxxx रेंज के IBANs। |
| [setUnstructuredMessage(value:)](#setunstructuredmessage) | अतिरिक्त असंरचित संदेश सेट करता है। |
| [setVersion(value)](#setversion) | SwissQR बिल मानक का संस्करण सेट करता है। |

### createAndSetCreditorReference(rawReference) {#createandsetcreditorreference}

कच्ची स्ट्रिंग से ISO11649 लेनदाता संदर्भ बनाता और सेट करता है, स्ट्रिंग के पहले "RF" जोड़कर और modulo 97 चेकसम लागू करके। संदर्भ से व्हाइटस्पेस हटा दिया जाता है।

| पैरामीटर | विवरण |
| --- | --- |
| rawReference | कच्चा संदर्भ। |

**Throws:** ArgumentException rawReference contains invalid characters.

### equals(obj) {#equals}

निर्धारित करता है कि निर्दिष्ट ऑब्जेक्ट वर्तमान ऑब्जेक्ट के बराबर है या नहीं।

| पैरामीटर | विवरण |
| --- | --- |
| obj | वर्तमान ऑब्जेक्ट के साथ तुलना करने के लिए ऑब्जेक्ट। |

**Returns:** true if the specified object is equal to the current object; otherwise, false.

### getAccount() {#getaccount}

लेनदाता का खाता नंबर प्राप्त करता है। खाता नंबर स्विट्ज़रलैंड या लिचेंस्टीन के बैंक के वैध IBANs होने चाहिए। खाते के नंबर में स्पेस की अनुमति है।

**Returns:** The creditor account number.

### getAlternativeSchemes() {#getalternativeschemes}

वैकल्पिक भुगतान योजनाओं को प्राप्त करता या सेट करता है। अधिकतम दो योजनाओं को पैरामीटर के साथ अनुमति है।

**Returns:** The alternative payment schemes.

### getAmount() {#getamount}

भुगतान राशि प्राप्त करता है। मान्य मान 0.01 से 999,999,999.99 के बीच हैं।

**Returns:** The payment amount.

### getBillInformation() {#getbillinformation}

अतिरिक्त संरचित बिल जानकारी प्राप्त करता है।

**Returns:** The structured bill information.

### getCreditor() {#getcreditor}

क्रेडिटर का पता प्राप्त करता है।

**Returns:** The creditor address.

### getCurrency() {#getcurrency}

भुगतान मुद्रा प्राप्त करता है। मान्य मान "CHF" और "EUR" हैं।

**Returns:** The payment currency.

### getDebtor() {#getdebtor}

लेनदार का पता प्राप्त करता है। लेनदार वैकल्पिक है। यदि इसे छोड़ दिया जाता है, तो इस फ़ील्ड को null सेट करना या सभी null या खाली मानों के साथ पता सेट करना दोनों ठीक है।

**Returns:** The debtor address.

### getReference() {#getreference}

लेनदाता भुगतान संदर्भ प्राप्त करता है। यह संदर्भ SwissQR IBANs के लिए अनिवार्य है, अर्थात CHxx30000xxxxxx से CHxx31999xxxxx रेंज के IBANs। यदि निर्दिष्ट किया गया है, तो संदर्भ या तो वैध SwissQR संदर्भ (ISR संदर्भ रूप के अनुरूप) या ISO 11649 के अनुसार वैध लेनदाता संदर्भ ("RFxxxx") होना चाहिए। दोनों में फ़ॉर्मेटिंग के लिए स्पेस हो सकते हैं।

**Returns:** The creditor payment reference.

### getUnstructuredMessage() {#getunstructuredmessage}

अतिरिक्त असंरचित संदेश प्राप्त करता है।

**Returns:** The unstructured message.

### getVersion() {#getversion}

SwissQR बिल मानक का संस्करण प्राप्त करता है।

**Returns:** The SwissQR bill standard version.

### hashCode() {#hashcode}

इस उदाहरण के लिए हैश कोड प्राप्त करता है।

**Returns:** A hash code for the current object.

### setAccount(value:) {#setaccount}

लेनदाता का खाता नंबर सेट करता है। खाता नंबर स्विट्ज़रलैंड या लिचेंस्टीन के बैंक के वैध IBANs होने चाहिए। खाते के नंबर में स्पेस की अनुमति है।

| पैरामीटर | विवरण |
| --- | --- |
| मान: | लेनदाता खाता नंबर। |

### setAlternativeSchemes(value:) {#setalternativeschemes}

वैकल्पिक भुगतान योजनाओं को प्राप्त या सेट करता है। अधिकतम दो योजनाएँ पैरामीटर के साथ अनुमति हैं।

| पैरामीटर | विवरण |
| --- | --- |
| मान: | वैकल्पिक भुगतान योजनाएँ। |

### setAmount(value) {#setamount}

भुगतान राशि सेट करता है। मान्य मान 0.01 से 999,999,999.99 के बीच हैं।

| पैरामीटर | विवरण |
| --- | --- |
| मान | भुगतान राशि। |

### setBillInformation(value:) {#setbillinformation}

अतिरिक्त संरचित बिल जानकारी सेट करता है।

| पैरामीटर | विवरण |
| --- | --- |
| मान: | संरचित बिल जानकारी। |

### setCreditor(value:) {#setcreditor}

लेनदाता का पता सेट करता है।

| पैरामीटर | विवरण |
| --- | --- |
| मान: | लेनदार का पता। |

### setCurrency(value) {#setcurrency}

भुगतान मुद्रा सेट करता है।

| पैरामीटर | विवरण |
| --- | --- |
| मान | मान्य मान "CHF" और "EUR" हैं। |

### setDebtor(value:) {#setdebtor}

लेनदार का पता सेट करता है। लेनदार वैकल्पिक है। यदि इसे छोड़ दिया जाता है, तो इस फ़ील्ड को null सेट करना या सभी null या खाली मानों के साथ पता सेट करना दोनों ही ठीक है।

| पैरामीटर | विवरण |
| --- | --- |
| मान: | लेनदार का पता। |

### setReference(value) {#setreference}

लेनदार भुगतान संदर्भ सेट करता है। यह संदर्भ SwissQR IBANs के लिए अनिवार्य है, अर्थात CHxx30000xxxxxx से CHxx31999xxxxx तक की रेंज वाले IBANs। यदि निर्दिष्ट किया गया है, तो यह या तो एक मान्य SwissQR संदर्भ (ISR संदर्भ फ़ॉर्म के अनुरूप) या ISO 11649 ("RFxxxx") के अनुसार एक मान्य लेनदार संदर्भ होना चाहिए। दोनों में फ़ॉर्मेटिंग के लिए स्पेस हो सकते हैं।

| पैरामीटर | विवरण |
| --- | --- |
| मान | लेनदार भुगतान संदर्भ। |

### setUnstructuredMessage(value:) {#setunstructuredmessage}

अतिरिक्त असंरचित संदेश सेट करता है।

| पैरामीटर | विवरण |
| --- | --- |
| मान: | असंरचित संदेश। |

### setVersion(value) {#setversion}

SwissQR बिल मानक का संस्करण सेट करता है।

| पैरामीटर | विवरण |
| --- | --- |
| मान | SwissQR बिल मानक संस्करण। |
