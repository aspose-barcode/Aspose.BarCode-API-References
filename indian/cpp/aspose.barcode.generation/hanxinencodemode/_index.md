---
title: "enum"
linktitle: "HanXinEncodeMode"
second_title: "Aspose.BarCode C++ के लिए API संदर्भ"
description: " enum. Han Xin कोड एन्कोडिंग मोड। C++ में ASCII/चाइनीज़ अक्षरों के साथ Auto या Unicode अक्षरों के लिए Unicode उपयोग करने की सलाह दी जाती है।"
type: docs
weight: 6900
url: /hi/cpp/aspose.barcode.generation/hanxinencodemode/
---
## HanXinEncodeMode enum


Han Xin कोड एन्कोडिंग मोड। ASCII / चीनी अक्षरों या Unicode अक्षरों के लिए Unicode के साथ Auto का उपयोग करने की सलाह दी जाती है।

```cpp
enum class HanXinEncodeMode
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| ऑटो | 0 | Auto मोड में, CodeText को अधिकतम डेटा कॉम्पैक्टनेस के साथ एन्कोड किया जाता है। Unicode अक्षरों को HanXin बारकोड विनिर्देश के अनुसार GB18030 एन्कोडिंग का उपयोग करके एन्कोड किया जाता है। |
| Binary | 1 | Binary मोड में, CodeText को अधिकतम डेटा संकुचन के साथ एन्कोड किया जाता है। यदि कोई यूनिकोड अक्षर मिलता है, तो एक exception फेंका जाता है। |
| ECI | 2 | ECI मोड में, संपूर्ण संदेश को निर्दिष्ट ECIEncoding में पुनः एन्कोड किया जाता है और ECI पहचानकर्ता डाला जाता है। यदि कोई ऐसा अक्षर मिलता है जो चयनित ECI एन्कोडिंग द्वारा समर्थित नहीं है, तो एक exception फेंका जाता है। कृपया ध्यान दें कि कुछ पुराने (2006 से पहले) स्कैनर इस मोड का समर्थन नहीं कर सकते हैं। |
| Unicode | 3 | Unicode मोड UTF8 एन्कोडिंग/कैरेक्टरसेट को Han Xin कोड में किसी भी टेक्स्ट डेटा को दर्शाने का तरीका डिजाइन करता है। |
| URI | 4 | URI मोड दर्शाता है कि Han Xin कोड में प्रतिनिधित्व किया गया डेटा Uniform Resource Identifier (URI) है, जो RFC 3986 को संदर्भित करता है। |
| Extended | 5 | Extended मोड आंतरिक मोडों के संयोजन की अनुमति देता है: Auto, Binary, Text, Numeric, URI, Unicode, ECI, [Common](../../aspose.barcode.common/) Chinese Region One, [Common](../../aspose.barcode.common/) Chinese Region Two, GB18030 Two Byte, GB18030 Four Byte। कोडटेक्स्ट को प्रीफ़िक्स और डबल बैकस्लैश के साथ मैन्युअली बनाया जा सकता है, उदाहरण के लिए: ":abc\\000009:ΑΒΓΔΕ:ab\\c" या [HanXinExtCodetextBuilder](../hanxinextcodetextbuilder/) का उपयोग करके। यदि कोडटेक्स्ट में ECI फ्रैगमेंट शामिल है, तो ECI फ्रैगमेंट के बाद केवल निम्नलिखित मोड कोडटेक्स्ट में हो सकते हैं: Auto, Binary, Text, Numeric, URI, ECI. |

## टिप्पणियाँ



```cpp
[C#]
// Auto मोड
var codetext = "1234567890ABCDEFGabcdefg,Han Xin Code";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Save("test.bmp");
}

// Binary मोड
byte[] encodedArr = { 0xFF, 0xFE, 0xFD, 0xFC, 0xFB, 0xFA, 0xF9 };
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin))
{
    generator.SetCodetext(encodedArr);
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Binary;
    generator.Save("test.bmp");
}

// ECI मोड
var codetext = "ΑΒΓΔΕ";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.ECI;
    generator.Parameters.Barcode.HanXin.ECIEncoding = ECIEncodings.ISO_8859_7;
    generator.Save("test.bmp");
}

// Unicode मोड
var codetext = "abcd АБВ ıntəˈnæʃənəl テスト 안녕하세요 테스트 테스트";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Unicode;
    generator.Save("test.bmp");
}

// URI मोड
var codetext = "https://www.test.com/%BC%DE%%%ab/search=test";
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, codetext))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.URI;
    generator.Save("test.bmp");
}

// Extended मोड
var str = @"\gb180302b:漄\gb180304b:㐁\region1:全\region2:螅\numeric:123\text:qwe\unicode:ıntəˈnæʃənəl" +
    @"\000009:ΑΒΓΔΕ\auto:abc\binary:abc\uri:backslashes_should_be_doubled\\000555:test";

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}

// Extended मोड के लिए HanXinExtCodetextBuilder का उपयोग करना (पिछले उदाहरण के समान कोडटेक्स्ट)
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
codeTextBuilder.AddURI(@"backslashes_should_be_doubled\000555:test");

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test";

//codetext उत्पन्न करें
var str = codeTextBuilder.GetExtendedCodetext();

//उत्पन्न करें
using (var generator = new BarcodeGenerator(EncodeTypes.HanXin, str))
{
    generator.Parameters.Barcode.HanXin.EncodeMode = EncodeMode.Extended;
    generator.Save("test.bmp");
}
```

## और देखें

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
