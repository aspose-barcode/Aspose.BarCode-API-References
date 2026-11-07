---
title: "विधि"
linktitle: "CleanValue"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड। स्ट्रिंग वैल्यू को साफ करता है ताकि वह स्विस पेमेंट स्टैंडर्ड्स 2018 के लिए C++ में उपयुक्त हो।"
type: docs
weight: 100
url: /hi/cpp/aspose.barcode.complexbarcode/payments/cleanvalue/
---
## Payments::CleanValue method


एक स्ट्रिंग मान को साफ़ करता है ताकि वह स्विस पेमेंट मानक 2018 के लिए उपयुक्त हो सके।

```cpp
static void Aspose::BarCode::ComplexBarcode::Payments::CleanValue(System::String value, Payments::CleaningResult &result)
```


| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | System::String | साफ करने के लिए स्ट्रिंग वैल्यू। |
| result | Payments::CleaningResult\& | परिणाम जिसे साफ की गई स्ट्रिंग और फ़्लैग से भरा जाएगा। |
## टिप्पणियाँ


असमर्थित अक्षर (स्विस पेमेंट स्टैंडर्ड्स 2018, च. 2.4.1 और परिशिष्ट D के अनुसार) को स्पेसेस (असमर्थित व्हाइटस्पेस) या डॉट्स (सभी अन्य असमर्थित अक्षर) से बदल दिया जाता है। अग्रणी और अनुक्रमिक व्हाइटस्पेस हटा दिया जाता है।

यदि 0xff से आगे के अक्षर पाए जाते हैं, तो स्ट्रिंग को पहले सामान्यीकृत किया जाता है ताकि दो कोड पॉइंट्स में व्यक्त उम्लॉट या एक्सेंट वाले अक्षर एकल कोड पॉइंट में मिल जाएँ (यदि संभव हो), जिनमें से कुछ वैध हो सकते हैं।

यदि परिणामी स्ट्रिंग पूरी तरह व्हाइटस्पेस है, तो **null** लौटाया जाता है।

## और देखें

* Class [Payments](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
