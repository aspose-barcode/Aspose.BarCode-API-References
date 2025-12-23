---
title: Class HanXinExtCodetextBuilder
second_title: Aspose.BarCode for .NET API Reference
description: Aspose.BarCode.Generation.HanXinExtCodetextBuilder class. Extended codetext generator for Han Xin Code for Extended Mode of EncodeMode
type: docs
weight: 1260
url: /net/aspose.barcode.generation/hanxinextcodetextbuilder/
---
## HanXinExtCodetextBuilder class

Extended codetext generator for Han Xin Code for Extended Mode of EncodeMode

```csharp
public class HanXinExtCodetextBuilder
```

## Constructors

| Name | Description |
| --- | --- |
| [HanXinExtCodetextBuilder](hanxinextcodetextbuilder/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [AddAuto](../../aspose.barcode.generation/hanxinextcodetextbuilder/addauto/)(string) | Adds codetext fragment in Auto mode |
| [AddBinary](../../aspose.barcode.generation/hanxinextcodetextbuilder/addbinary/)(string) | Adds codetext fragment in Binary mode |
| [AddCommonChineseRegionOne](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregionone/)(string) | Adds codetext fragment in Common Chinese Region One mode |
| [AddCommonChineseRegionTwo](../../aspose.barcode.generation/hanxinextcodetextbuilder/addcommonchineseregiontwo/)(string) | Adds codetext fragment in Common Chinese Region Two mode |
| [AddECI](../../aspose.barcode.generation/hanxinextcodetextbuilder/addeci/)(string, int) | Adds codetext fragment in ECI mode |
| [AddGB18030FourByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030fourbyte/)(string) | Adds codetext fragment in GB18030 Four Byte mode |
| [AddGB18030TwoByte](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgb18030twobyte/)(string) | Adds codetext fragment in GB18030 Two Byte mode |
| [AddGS1](../../aspose.barcode.generation/hanxinextcodetextbuilder/addgs1/)(string) | Adds codetext fragment in GS1 mode |
| [AddNumeric](../../aspose.barcode.generation/hanxinextcodetextbuilder/addnumeric/)(string) | Adds codetext fragment in Numeric mode |
| [AddText](../../aspose.barcode.generation/hanxinextcodetextbuilder/addtext/)(string) | Adds codetext fragment in Text mode |
| [AddUnicode](../../aspose.barcode.generation/hanxinextcodetextbuilder/addunicode/)(string) | Adds codetext fragment in Unicode mode |
| [AddURI](../../aspose.barcode.generation/hanxinextcodetextbuilder/adduri/)(string) | Adds codetext fragment in URI mode |
| [GetExtendedCodetext](../../aspose.barcode.generation/hanxinextcodetextbuilder/getextendedcodetext/)() | Returns codetext from Extended mode codetext builder |

## Examples

```csharp
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

### See Also

* namespace [Aspose.BarCode.Generation](../../aspose.barcode.generation/)
* assembly [Aspose.BarCode](../../)


