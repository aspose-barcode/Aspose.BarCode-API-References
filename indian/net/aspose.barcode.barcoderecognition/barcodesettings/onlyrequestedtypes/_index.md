---
title: "BarcodeSettings.OnlyRequestedTypes"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "BarcodeSettings प्रॉपर्टी। केवल वही बारकोड प्रकार लौटाता है जो पहचान के लिए स्पष्ट रूप से निर्दिष्ट किए गए हैं। जब सक्षम हो, तो अन्य संगत या समतुल्य प्रकारों के पहचाने गए बारकोड फ़िल्टर कर दिए जाते हैं। डिफ़ॉल्ट मान false है।"
type: docs
weight: 50
url: /hi/net/aspose.barcode.barcoderecognition/barcodesettings/onlyrequestedtypes/
---
## BarcodeSettings.OnlyRequestedTypes property

केवल उन बारकोड प्रकारों को लौटाता है जो पहचान के लिए स्पष्ट रूप से निर्दिष्ट किए गए हैं। जब सक्षम किया जाता है, तो अन्य संगत या समकक्ष प्रकारों के पहचाने गए बारकोड फ़िल्टर हो जाते हैं। डिफ़ॉल्ट मान false है।

```csharp
public bool OnlyRequestedTypes { get; set; }
```

### Property Value

केवल उन बारकोड प्रकारों को लौटाता है जो पहचान के लिए स्पष्ट रूप से निर्दिष्ट किए गए हैं। डिफ़ॉल्ट मान false है।

## उदाहरण

यह उदाहरण दर्शाता है कि कैसे पहचान परिणामों को केवल अनुरोधित बारकोड प्रकारों तक सीमित किया जाए

```csharp
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

### और देखें

* class [BarcodeSettings](../)
* namespace [Aspose.BarCode.BarCodeRecognition](../../../aspose.barcode.barcoderecognition/)
* assembly [Aspose.BarCode](../../../)


