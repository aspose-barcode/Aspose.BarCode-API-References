---
title: "enum"
linktitle: "EnableChecksum"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "C++ में enum का उपयोग कैसे करें।"
type: docs
weight: 6700
url: /hi/cpp/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enum




```cpp
enum class EnableChecksum
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| डिफ़ॉल्ट | 0 | यदि विनिर्देश द्वारा चेकसम आवश्यक है - इसे संलग्न किया जाएगा। |
| हाँ | 1 | यदि संभव हो तो हमेशा चेकसम का उपयोग करें। |
| नहीं | 2 | चेकसम का उपयोग न करें। |

## टिप्पणियाँ


1D बारकोड उत्पन्न करते समय चेकसम सक्षम करें।

डिफ़ॉल्ट को उन प्रतीकात्मकताओं के लिए Yes माना जाता है जिनमें चेकसम अनिवार्य है, और जहाँ केवल चेकसम संभव है वहाँ No माना जाता है।

चेकसम कभी उपयोग नहीं किया जाता: Codabar

चेकसम संभव है: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

चेकसम हमेशा उपयोग किया जाता है: शेष प्रतीकात्मकताएँ
## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
