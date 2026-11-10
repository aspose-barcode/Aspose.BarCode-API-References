---
title: "क्लास HanXinExtCodetextBuilder"
second_title: "Aspose.BarCode for .NET API संदर्भ"
description: "Aspose.BarCode.Generation.HanXinExtCodetextBuilder क्लास। Han Xin कोड के विस्तारित मोड के लिए विस्तारित कोडटेक्स्ट जेनरेटर।"
type: docs
weight: 1380
url: /hi/net/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class

विस्तारित कोडटेक्स्ट जेनरेटर Han Xin कोड के लिए EncodeMode के Extended Mode के लिए

```csharp
public class HanXinExtCodetextBuilder
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [HanXinExtCodetextBuilder](hanxinextcodetextbuilder/)() | डिफ़ॉल्ट कन्स्ट्रक्टर। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [AddAuto](../../aspose.barcode.generation/hanxinextcodetextbuilder/addauto/)(string) | Auto मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddBinary](../../aspose.barcode.generation/hanxinextcodetextbuilder/addbinary/)(string) | Binary मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddCommonChineseRegionOne](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregionone/)(string) | Common Chinese Region One मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddCommonChineseRegionTwo](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregiontwo/)(string) | Common Chinese Region Two मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddECI](../../aspose.barcode.generation/hanxinextcodetextbuilder/addeci/)(string, int) | ECI मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddGB18030FourByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030fourbyte/)(string) | GB18030 Four Byte मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddGB18030TwoByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030twobyte/)(string) | GB18030 Two Byte मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddNumeric](../../aspose.barcode.generation/hanxinextcodetextbuilder/addnumeric/)(string) | Numeric मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddText](../../aspose.barcode.generation/hanxinextcodetextbuilder/addtext/)(string) | टेक्स्ट मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddUnicode](../../aspose.barcode.generation/hanxinextcodetextbuilder/addunicode/)(string) | यूनिकोड मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [AddURI](../../aspose.barcode.generation/hanxinextcodetextbuilder/adduri/)(string) | यूआरआई मोड में कोडटेक्स्ट फ्रैगमेंट जोड़ता है |
| [GetExtendedCodetext](../../aspose.barcode.generation/hanxinextcodetextbuilder/getextendedcodetext/)() | एक्सटेंडेड मोड कोडटेक्स्ट बिल्डर से कोडटेक्स्ट लौटाता है |

## उदाहरण

```csharp
[C#]
//Extended कोडटेक्स्ट मोड
//कोडटेक्स्ट बनाएं
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

//कोडटेक्स्ट उत्पन्न करें
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

### और देखें

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


