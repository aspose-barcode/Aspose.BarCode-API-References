---
title: Aspose::BarCode::Generation::HanXinExtCodetextBuilder class
linktitle: HanXinExtCodetextBuilder
second_title: Aspose.BarCode for C++ API Reference
description: 'How to use Aspose::BarCode::Generation::HanXinExtCodetextBuilder class in C++.'
type: docs
weight: 2600
url: /cpp/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class




```cpp
class HanXinExtCodetextBuilder : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AddAuto](./addauto/)(System::String) | Adds codetext fragment in Auto mode |
| [AddBinary](./addbinary/)(System::String) | Adds codetext fragment in Binary mode |
| [AddCommonChineseRegionOne](./addcommonchineseregionone/)(System::String) | Adds codetext fragment in [Common](../../aspose.barcode.common/) Chinese Region One mode |
| [AddCommonChineseRegionTwo](./addcommonchineseregiontwo/)(System::String) | Adds codetext fragment in [Common](../../aspose.barcode.common/) Chinese Region Two mode |
| [AddECI](./addeci/)(System::String, int32_t) | Adds codetext fragment in ECI mode |
| [AddGB18030FourByte](./addgb18030fourbyte/)(System::String) | Adds codetext fragment in GB18030 Four Byte mode |
| [AddGB18030TwoByte](./addgb18030twobyte/)(System::String) | Adds codetext fragment in GB18030 Two Byte mode |
| [AddGS1](./addgs1/)(System::String) | Adds codetext fragment in GS1 mode |
| [AddNumeric](./addnumeric/)(System::String) | Adds codetext fragment in Numeric mode |
| [AddText](./addtext/)(System::String) | Adds codetext fragment in Text mode |
| [AddUnicode](./addunicode/)(System::String) | Adds codetext fragment in Unicode mode |
| [AddURI](./adduri/)(System::String) | Adds codetext fragment in URI mode |
| [GetExtendedCodetext](./getextendedcodetext/)() | Returns codetext from Extended mode codetext builder |
| [HanXinExtCodetextBuilder](./hanxinextcodetextbuilder/)() |  |
## Remarks


Extended codetext generator for Han Xin Code for Extended Mode of EncodeMode





```cpp
[C#]
//Extended codetext mode
//create codetext
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
codeTextBuilder.AddGS1(@"(01)03453120000011(17)191125(10)ABCD1234(21)10");

var expectedStr = @"漄㐁全螅123qweıntəˈnæʃənəlΑΒΓΔΕabcabcbackslashes_should_be_doubled\000555:test(01)03453120000011(17)191125(10)ABCD1234(21)10";

//generate codetext
var str = codeTextBuilder.GetExtendedCodetext();

//generate
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

## See Also

* Namespace [Aspose::BarCode::Generation](../)
* Library [Aspose.BarCode for C++](../../)
