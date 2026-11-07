---
title: "Aspose::BarCode::Generation::HanXinExtCodetextBuilder क्लास"
linktitle: "HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: "C++ में Aspose::BarCode::Generation::HanXinExtCodetextBuilder क्लास का उपयोग कैसे करें।"
type: docs
weight: 2800
url: /hi/cpp/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class




```cpp
class HanXinExtCodetextBuilder : public System::Object
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [AddAuto](./addauto/)(System::String) | ऑटो मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddBinary](./addbinary/)(System::String) | बाइनरी मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddCommonChineseRegionOne](./addcommonchineseregionone/)(System::String) | [Common](../../aspose.barcode.common/) Chinese Region One मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddCommonChineseRegionTwo](./addcommonchineseregiontwo/)(System::String) | [Common](../../aspose.barcode.common/) Chinese Region Two मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddECI](./addeci/)(System::String, int32_t) | ECI मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddGB18030FourByte](./addgb18030fourbyte/)(System::String) | GB18030 चार बाइट मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddGB18030TwoByte](./addgb18030twobyte/)(System::String) | GB18030 दो बाइट मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddNumeric](./addnumeric/)(System::String) | न्यूमेरिक मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddText](./addtext/)(System::String) | टेक्स्ट मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddUnicode](./addunicode/)(System::String) | यूनिकोड मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddURI](./adduri/)(System::String) | URI मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [GetExtendedCodetext](./getextendedcodetext/)() | एक्सटेंडेड मोड कोडटेक्स्ट बिल्डर से कोडटेक्स्ट लौटाता है |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/)() |  |
## टिप्पणियाँ


EncodeMode के एक्सटेंडेड मोड के लिए Han Xin कोड का एक्सटेंडेड कोडटेक्स्ट जेनरेटर


```cpp
[C#]
//विस्तारित codetext मोड
//codetext बनाएं
var codeTextBuilder = new HanXinExtCodetextBuilder();
codeTextBuilder.AddGB18030TwoByte("漄");
codeTextBuilder.AddGB18030FourByte("㐁");
codeTextBuilder.AddCommonChineseRegionOne("全");
codeTextBuilder.AddCommonChineseRegionTwo("螅");
codeTextBuilder.AddNumeric("123");
codeTextBuilder.AddText("qwe");
codeTextBuilder.AddUnicode("ıntəˈnæʃənəl");
codeTextBuilder.AddECI("ΑΒΓΔΕ", 9);
codeTextBuilder.AddAuto("abc");
codeTextBuilder.AddBinary("abc");

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabc";

//codetext उत्पन्न करें
var str = codeTextBuilder.GetExtendedCodetext();

//उत्पन्न करें
using (var bg = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    bg.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    var img = bg.GenerateBarCodeImage();
    using (var r = new BarCodeReader(img, DecodeType.HanXin))
     {
        var found = r.ReadBarCodes();
        Assert.AreEqual(1, found.Length);
        Assert.AreEqual(expectedStr, found[0].CodeText);
      }
}
```

## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
