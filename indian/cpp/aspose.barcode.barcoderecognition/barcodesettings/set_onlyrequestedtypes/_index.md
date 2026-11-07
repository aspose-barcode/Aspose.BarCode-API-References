---
title: "विधि"
linktitle: "set_OnlyRequestedTypes"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " मेथड। केवल उन बारकोड प्रकारों को लौटाता है जो स्पष्ट रूप से पहचान के लिए निर्दिष्ट किए गए हैं। जब सक्षम हो, तो अन्य संगत या समकक्ष प्रकारों के पहचाने गए बारकोड फ़िल्टर कर दिए जाते हैं। डिफ़ॉल्ट मान C++ में गलत है।"
type: docs
weight: 600
url: /hi/cpp/aspose.barcode.barcoderecognition/barcodesettings/set_onlyrequestedtypes/
---
## BarcodeSettings::set_OnlyRequestedTypes method


केवल उन बारकोड प्रकारों को लौटाता है जो स्पष्ट रूप से पहचान के लिए निर्दिष्ट किए गए हैं। जब सक्षम किया जाता है, तो अन्य संगत या समकक्ष प्रकारों के मान्य बारकोड फ़िल्टर हो जाते हैं। डिफ़ॉल्ट मान false है।

```cpp
void Aspose::BarCode::BarCodeRecognition::BarcodeSettings::set_OnlyRequestedTypes(bool value)
```

## टिप्पणियाँ


यह उदाहरण दिखाता है कि कैसे पहचान परिणामों को केवल अनुरोधित बारकोड प्रकारों तक सीमित किया जाए
```cpp
[C#]
//EAN13 बारकोड उत्पन्न करें
using (BarcodeGenerator generator = new BarcodeGenerator(EncodeTypes.EAN13, "2383823482894"))
    generator.Save(@"c:\test.png");
//केवल UPCA बारकोड को पहचानें (कोई परिणाम नहीं, क्योंकि स्रोत EAN13 है)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = true;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
//संगत प्रकारों को पहचानें: EAN13, UPCA, ISSN, ISMN, ISBN (EAN13 को UPCA-समकक्ष के रूप में लौटाया जाएगा)
using (BarCodeReader reader = new BarCodeReader(@"c:\test.png", DecodeType.UPCA))
{
    reader.BarcodeSettings.OnlyRequestedTypes = false;
    foreach (BarCodeResult result in reader.ReadBarCodes())
        Console.WriteLine("BarCode CodeText: " + result.CodeText);
}
```


केवल उन बारकोड प्रकारों को लौटाता है जो स्पष्ट रूप से पहचान के लिए निर्दिष्ट किए गए हैं। डिफ़ॉल्ट मान गलत है।
## और देखें

* Class [BarcodeSettings](../)
* Namespace [Aspose::BarCode::BarCodeRecognition](../../)
* Library [Aspose.BarCode for C++](../../../)
