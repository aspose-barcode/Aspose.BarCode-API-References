---
title: "GS1Codetext.TryParse"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "GS1Codetext मेथड. ब्रैकेटेड GS1 एलिमेंट स्ट्रिंग को रूप AIvalueAIvalue में पार्स करने का प्रयास करता है और संरचित वैधता त्रुटियां लौटाता है। मान के भीतर एक लिटरल  को  के रूप में लिखा जाना चाहिए, कोई अन्य एस्केप सीक्वेंस समर्थित नहीं है और  को एस्केप करने की आवश्यकता नहीं है।"
type: docs
weight: 140
url: /hi/net/aspose.barcode.complexbarcode/gs1codetext/tryparse/
---
## GS1Codetext.TryParse method

ब्रैकेटेड GS1 तत्व स्ट्रिंग को (AI)value(AI)value के रूप में पार्स करने का प्रयास करता है और संरचित वैधता त्रुटियाँ लौटाता है। मान के भीतर शाब्दिक '(' को \\( के रूप में लिखा जाना चाहिए; कोई अन्य एस्केप सीक्वेंस समर्थित नहीं है, और ')' को एस्केप करने की आवश्यकता नहीं है।

```csharp
public static bool TryParse(string value, out GS1Codetext result, 
    out GS1ValidationResult validationResult)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | स्ट्रिंग | पार्स करने के लिए ब्रैकेटेड GS1 एलिमेंट स्ट्रिंग। |
| परिणाम | GS1Codetext& | जब यह मेथड true लौटाता है, तो इसमें पार्स किया गया GS1 कोडटेक्स्ट होता है; अन्यथा null। |
| validationResult | GS1ValidationResult& | वैलिडेशन परिणाम शामिल करता है, या जब *value* null हो तो null। |

### वापसी मान

जब पार्सिंग सफल हो तो true; अन्यथा false।

### और देखें

* class [GS1ValidationResult](../../../aspose.barcode.common/gs1validationresult/)
* class [GS1Codetext](../)
* namespace [Aspose.BarCode.ComplexBarcode](../../../aspose.barcode.complexbarcode/)
* assembly [Aspose.BarCode](../../../)


