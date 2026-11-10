---
title: "Enum EnableChecksum"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.EnableChecksum enum. 1D बारकोड्स के लिए जनरेशन के दौरान चेकसम सक्षम करें"
type: docs
weight: 1280
url: /hi/net/aspose.barcode.generation/enablechecksum/
---
## EnableChecksum enumeration

1D बारकोड के जनरेशन के दौरान चेकसम सक्षम करें।

डिफ़ॉल्ट रूप से उन सिम्बोलॉजीज़ के लिए Yes माना जाता है जिनमें चेकसम अनिवार्य है, और जहाँ केवल चेकसम संभव है वहाँ No माना जाता है।

चेकसम कभी उपयोग नहीं किया गया: Codabar

चेकसम संभव है: Code39 Standard/Extended, Standard2of5, Interleaved2of5, Matrix2of5, ItalianPost25, DeutschePostIdentcode, DeutschePostLeitcode, VIN

Checksum हमेशा उपयोग किया जाता है: बाकी सिम्बोलॉजीज़

```csharp
public enum EnableChecksum
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| Default | `0` | यदि विनिर्देश द्वारा चेकसम आवश्यक है - इसे जोड़ा जाएगा। |
| Yes | `1` | यदि संभव हो तो हमेशा चेकसम का उपयोग करें। |
| No | `2` | चेकसम का उपयोग न करें। |

### और देखें

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


