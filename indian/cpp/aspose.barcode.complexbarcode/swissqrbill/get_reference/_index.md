---
title: "विधि"
linktitle: "get_Reference"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " विधि। C++ में लेनदार भुगतान संदर्भ प्राप्त करता है।"
type: docs
weight: 1100
url: /hi/cpp/aspose.barcode.complexbarcode/swissqrbill/get_reference/
---
## SwissQRBill::get_Reference method


क्रेडिटर भुगतान रेफ़रेंस प्राप्त करता है।

```cpp
System::String Aspose::BarCode::ComplexBarcode::SwissQRBill::get_Reference() const
```

## टिप्पणियाँ


SwissQR IBAN के लिए संदर्भ अनिवार्य है, अर्थात् CHxx30000xxxxxx से CHxx31999xxxxx तक की रेंज वाले IBAN।

यदि निर्दिष्ट किया गया है, तो संदर्भ या तो वैध SwissQR संदर्भ (ISR संदर्भ रूप के अनुरूप) या ISO 11649 (\"RFxxxx\") के अनुसार वैध लेनदार संदर्भ होना चाहिए। दोनों में फॉर्मेटिंग के लिए स्पेस हो सकते हैं।

लेनदार भुगतान संदर्भ।
## और देखें

* Class [SwissQRBill](../)
* Namespace [Aspose::BarCode::ComplexBarcode](../../)
* Library [Aspose.BarCode for C++](../../../)
